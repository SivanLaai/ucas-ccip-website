---
title: 团队
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: 全体成员
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - 实验室主任
        - 教授
        - 副教授
        - 博士后
        - 博士研究生
        - 硕士研究生
        - 本科生
        - 工程师
        - 访问学生
        - 毕业生

        # - principal_investigator
        # - professor
        # - associate_professor
        # - postdocs
        # - phd_students
        # - masters_students
        # - undergraduate_students
        # - engineer
        # - vistors
        # - intern
        # - alumni
      sort_by: Params.join_year
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      show_destination: true
      # background:
      #   # image:
      #   #   # filename: ucas-bridge.jpg
      #   #   filters:
      #   #     brightness: 0.9
      #   position: right
      #   color: "#f7f7f7"
---