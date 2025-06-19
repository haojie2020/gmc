---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      user_groups:
        - Principal Investigator
        - Researchers
        - Student Assistant
        - Technician
        - Visitors
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: people
    content:
      title: Alumni
      user_groups:
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true      # 可以改为 false 如果不显示以前的头衔
      show_organization: true   # 需要主题支持
      show_social: false

        # **脚注图片 block**（推荐插入到最后）
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
       <div style="width:100%;text-align:center;">
        <img src="/media/funding.jpg" alt="Funding" style="display:inline-block;max-width:1000px;width:80vw;min-width:120px;height:auto;margin:0 auto;border:none;box-shadow:none;background:transparent;" />
       </div>

---
