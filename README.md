## 编译环境安装
### 安装环境变量
- nodejs环境安装
https://blog.csdn.net/zimeng303/article/details/112167688
- go环境安装
查看 https://blog.csdn.net/qq_42313447/article/details/114403953
- hugo环境安装
查看 https://github.com/gohugoio/hugo/releases/v0.125.7

### Clone项目
```
git clone https://gitee.com/SivanLaai/ucas-ccip-website.git
```
or
```
git clone git@gitee.com:SivanLaai/ucas-ccip-website.git
```

### 编译运行
```
cd ucas-ccip-website
hugo server -D -p 1313
```

### 浏览主页

http://localhost:1313/

## 内容添加
### 人员添加

1. 进入目录```content/zh/authors```
2. 假如人名是张三，则在目录```content/zh/authors```下添加文件夹```san-zhang```,对应张三的拼音```zhang san```，但是为了在网站中方便索引就需要组织成```san-zhang```
3. 进入目录```san-zhang```，添加2个文件，分别如下:
    - ```index.md``` (个人详细信息)
    
    ``` yaml
        ---
        # Display name
        title: 张三

        # Full Name (for SEO)
        first_name: 三
        last_name: 张

        # Is this the primary user of the site?
        superuser: false

        # Role/position
        # 填写博士研究生/硕士研究生
        role: 硕士研究生
        # 新生入学年份，必填写
        join_year: 2023
        # 毕业年份，毕业生需要更新，填写该值表示该学生已经毕业
        graduated_year: 
        # 毕业去向，毕业生填写
        destination:  

        # Organizations/Affiliations
        organizations:
          - name: 计算机科学与技术学院
            url: 'https://scce.ucas.ac.cn'  
          - name: 中国科学院大学
            url: 'https://www.ucas.ac.cn'

        # Short bio (displayed in user profile at end of posts)
        bio: 

        interests:
          - 机器学习

        education:
          courses:
            # course 填写 学位 专业， 需要用空格隔开，如下所示
            - course: 硕士 电子信息
            # institution 填写 高校名称,学院名称， 需要用逗号隔开，如下所示，如不知学院，则只添加高校名称，并去掉逗号
              institution: 中国科学院大学,计算机科学与技术学院
            # year 填写 入学时间和毕业时间，如还在读，则只填写入学时间既可 
              year: 2024
            - course: 本科 自动化
              institution: 中国科学院大学  
              year: 2019-2023

        # Social/Academic Networking
        # For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
        #   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
        #   form "mailto:your-email@example.com" or "#contact" for contact widget.
        social:
          - icon: envelope
            icon_pack: fas
            # 填写邮箱
            link: 'mailto:邮箱地址'
          # - icon: twitter
          #   icon_pack: fab
          #   link: https://twitter.com/GeorgeCushen
          # - icon: google-scholar
          #   icon_pack: ai
          #   link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
          # - icon: github
          #   icon_pack: fab
          #   link: https://github.com/gcushen
        # Link to a PDF of your resume/CV from the About widget.
        # To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
        # - icon: cv
        #   icon_pack: ai
        #   link: files/cv.pdf

        # Enter email to display Gravatar (if Gravatar enabled in Config)
        # 此处不用填写
        email: ''

        # Highlight the author in author lists? (true/false)
        highlight_name: false

        # Organizational groups that you belong to (for People widget)
        #   Set this to `[]` or comment out if you are not using People widget.

        # 用户分组，根据真实情况填写以下角色
        # - 实验室主任
        # - 教授
        # - 副教授
        # - 博士后
        # - 博士研究生
        # - 硕士研究生
        # - 本科生
        # - 工程师
        # - 访问学生
        # - 毕业生
        user_groups:
          - 硕士研究生

        ---
        ### 导师
        - 徐俊刚

        ### 获奖情况
        - 2021 数学建模大赛省级一等奖 
        -  (如无则删除本项，同时删除本项标题)

        ### 工作经历
        - 2019-2020 华为技术有限公司
        -  (如无则删除本项，同时删除本项标题)
    ```
    - ```avatar.jpg``` or ```avatar.png``` (个人头像)
### 文章添加

 参照```content/zh/post/21-12-01-aaai/index.md```

- 文章名称是```21-12-01-aaai```
- 文章内容在```index.md```
- 还可以在```index.md```同目录添加feature.png，作为文章封面图

### 成果添加
```yaml
publication_types:
  - paper-conference
```
- 会议论文 ```content/zh/publications/conferences/```,设置文章类型如下：
```yaml
publication_types: 
 - paper-conference
```
- 期刊论文 ```content/zh/publications/journals/```,设置文章类型如下：
```yaml
publication_types: 
 - article-journal
```
- 专利 ```content/zh/publications/patents/```,设置文章类型如下：
```yaml
publication_types: 
 - patent
```
- 软件著作权 ```content/zh/publications/software-copyrights/```,设置文章类型如下：
```yaml
publication_types: 
 - software-copyright
```
