---
# Leave the homepage title empty to use the site title
title:
date: 2025-06-16
type: landing

sections:
  - block: hero
    id: home
    content:
      title: |
        Introduction 
      image:
        filename: formind_logo.PNG
      text: |
        <br>

        Welcome to the Formal Methods and Intelligent Design Laboratory (**FORMiND Lab**), led by Dr. Min LI. Established in June 2025, FORMiND Lab is affiliated with both [NCTIEDA](https://www.nctieda.com/) and [the School of Integrated Circuits at Southeast University](https://ic.seu.edu.cn/); our research group is primarily based in Nanjing and Shenzhen, China.


        FORMiND Lab prioritizes **solid end-to-end improvements** in hardware design and verification, moving beyond paper/胶片-only "breakthroughs". Ultimately, our goal is to empower China's domestic hardware formal verification tools (with design considerations to follow) to achieve global leadership. 
  
  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |
        **June 2025**: 🎉Dr. Min Li departed from Huawei Noah's Ark Lab and just launched the FORMiND Lab website; he will join Southeast University this summer. 🎉Welcoming **Xudong Hu** as the inaugural member, who commences his Ph.D. program in Fall 2025.
  
  - block: people
    id: people
    content:
      title: People
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Ph.D. Students
          - Grad Students
          - Engineers
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: markdown
    id: tools
    content:
      title: Tools
      subtitle: ''
      text: | 
        We are developing **EquivFusion**, an AI-augmented verification toolchain built on [circt](https://github.com/llvm/circt). It unifies equivalence checking from algorithms to netlists for efficient sign-off. The codebase is scheduled for release by Q4 2025

  - block: markdown
    id: publications
    content:
      title: Publications 
      subtitle: ''
      text: |
        **NOTE**: Good news coming soon!

  - block: contact
    id: contact
    content:
      title: Contact
      text: |
        Our lab will be headquartered at **National EDA Innovation Center (NCTIEDA), Jiangbei, Nanjing**. We are looking for motivated students to join FORMiND Lab as research interns, master or Ph.D. students in Southeast University! Experienced engineers are also welcome - NCTIEDA offers competitive compensation packages exceeding industry standards in the EDA field.

        Min welcomes coffee discussions with students/researchers/engineers passionate about developing cutting-edge EDA tools! Please note that Min splits his time between **Shenzhen** and **Nanjing**; advance email coordination is preferred for on-site meetings.

        <br>
        <iframe src="https://calendar.google.com/calendar/embed?src=minli.amoy%40gmail.com&ctz=Asia%2FHong_Kong" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
      email: minli.amoy@gmail.com
      # Automatically link email and phone or display as text?
      autolink: true
    
    design:
      columns: '1'

---
