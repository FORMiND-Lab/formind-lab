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

        Welcome to the Formal Methods & Intelligent Design Laboratory (**FORMiND Lab**), led by Dr. Min LI. Established in June 2025, FORMiND Lab is affiliated with both [NCTIEDA](https://www.nctieda.com/) and [the School of Integrated Circuits at Southeast University](https://ic.seu.edu.cn/); our research group is primarily based in Nanjing && Shenzhen, China.


        FORMiND Lab prioritizes **solid end-to-end improvements** in hardware design and verification, moving beyond paper/胶片-only "breakthroughs". Ultimately, our goal is to empower China's domestic hardware formal verification tools to achieve global leadership. 
  
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
        We will develop an **AI-augmented verification toolchain** based on [SymbiYosys](https://yosyshq.readthedocs.io/projects/sby/en/latest/), targeting pure RTL datapath verification. **With AI-native architectural principles embedded throughout the development lifecycle**, the enhanced codebase is scheduled for release by Q4 2025.

  - block: markdown
    id: publications
    content:
      title: Publications 
      subtitle: ''
      text: |
        **NOTE**: Following two years of intensive focus on industrial challenges (i.e., great HiSilicon in-house formal verification tool) without first-author publications, Min is now positioned to publish **production-ready rigorous papers** that bridge academia and industry. Good news coming soon!

  - block: contact
    id: contact
    content:
      title: Contact
      text: |
        Our lab will be headquartered at **Nanjing National EDA Innovation Center (NCTIEDA), Jiangbei, Nanjing**. We are looking for motivated students to join FORMiND lab as interns or Ph.D. students in Southeast University!

        Min welcomes discussions with qualified individuals over coffee! Please note that Min splits his time between **Shenzhen** and **Nanjing**; advance email coordination is preferred for on-site meetings.   
      email: minli.amoy@gmail.com
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

---
