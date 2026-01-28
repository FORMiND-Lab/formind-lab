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
        **Jan. 2026**: 🎉1x**ICLR** and 1x**TCAD**, many thanks for all co-authors. We officially launched a collaboration with the HiSilicon Formal Verification Group, aiming to develop efficient word-level solvers and a bug-hunting framework for multi-property hardware verification. We are also delighted to welcome **Shenghu Han**, **Yusen Mo**, **Yiting Yang** and **Zixiang Fu**, who will join the FORMiND Lab in Fall 2026. In addition, we have three openings for Master’s candidates in 2026, and interested students are warmly encouraged to contact us via email.

        **Dec. 2025**: We have open‑sourced **EquivFusion**, a verification toolchain built on CIRCT. The main contributors are Mengxia, Baoqi, Jiaying and Min. 

        **Sept. 2025**:  🎉One paper (Dependency Matters: Enhancing LLM Reasoning with Explicit Knowledge Grounding) has been accepted by NeurIPS 2025. Congrats to Xiangyu Wen, our awesome intern at Huawei (co-supervised by Junhua and me).

        **Aug. 2025**: 🎉Warmly welcoming five new students **Yan Jiang**, **Shibo Zhao**, **Jiongming Chen**, **Jieying Wu**, and **Yang Zhang**, who will join the FORMiND Lab as master’s students in Fall 2025. Looking forward to an exciting journey together!

        **Jul. 2025**: Min has safely landed at SEU! With four master's spots open, he's welcoming students passionate about AI4Formal to join the journey.

        **Jun. 2025**: 🎉Dr. Min Li departed from Huawei Noah's Ark Lab and just launched the FORMiND Lab website; he will join Southeast University this summer. 🎉Welcoming **Xudong Hu** as the inaugural member, who commences his Ph.D. program in Fall 2025.
  
  - block: people
    id: people
    content:
      title: People
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Professor
          - Students
          - Grad Students
          - Project Manager
          - Engineers
          - Visitors
          - Alumni
          # - Super-Supervisor
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
        - [**EquivFusion**](https://github.com/FORMiND-Lab/EquivFusion) aims to unify equivalence checking from algorithms to netlists for efficient sign‑off. The project is built on [CIRCT](https://github.com/llvm/circt) and is still in an early development stage, and we welcome feedback and collaboration as it continues to evolve.

  - block: markdown
    id: talks
    content:
      title: Talks
      subtitle: ''
      text: |
        - **From Generation to Verified Synthesis: Bridging Industrial Reality via C-Guided Agents** [📄](files/talks/From_Generation_to_Verified_Synthesis.pdf)  
          01/2026: (Designer Forum 1) Toward Autonomous Chip Design: From Foundation Models to AgenticEDA, ASP-DAC26.
        - **Applications and Prospects of Formal Methods in Hardware Verification Tools** [📄](files/talks/ict_is_youth_202508.pdf) [🎬](https://www.bilibili.com/video/BV19NePzNEus?buvid=XU9CB8E97888E6317C8C629982ABDD4E78952&from_spmid=default-value&is_story_h5=false&mid=%2Bgp5S7io8OxAw1lwmhrOGA%3D%3D&plat_id=116&share_from=ugc&share_medium=android&share_plat=android&share_session_id=5ae10524-3e8d-4159-a3dd-8cc7f3c6c1e2&share_source=WEIXIN&share_tag=s_i&spmid=united.player-video-detail.0.0&timestamp=1755747203&unique_k=Z6McQfX&up_id=36888575&vd_source=de3e205d459754fb14d7c47bd6cf0433&p=9&spm_id_from=333.788.videopod.episodes)  
          08/2025: 2025 CCF Formal Methods Committee Youth Academic Forum — Symposium on the Application of Formal Methods in Foundational Software / IS, CAS.
        - **Opportunities and Challenges of Hardware Formal Verification in the Era of Large Language Models** [📄](files/talks/ict_ac_summer_school_202507.pdf)  
          07/2025: *LLM4xPU* Summer School, State Key Lab of Processors, ICT, CAS.


  - block: markdown
    id: publications
    content:
      title: Publications 
      subtitle: ''
      text: |
        - <span class="pub-badge pub-badge--preprint">preprint</span>**EquivFusion: Unifying Hardware Equivalence Checking from Algorithms to Netlists via MLIR** [📄](files/EquivFusion_FSE2026.pdf)  
          Jiaying Zhu, Baoqi Zhang, Kezhi Li, Hao Yan, Qiang Xu, **Min Li**  
          In submission to ACM International Conference on the Foundations of Software Engineering - Tool Demonstrations Track, 2026.
        - <span class="pub-badge pub-badge--tcad">TCAD</span>**From Contrastive to Generative Alignment: Large-Scale Hierarchical Multi-Modal Pre-training for Hotspot Detection**  
          Xinyun Zhang, Yuyang Chen, Yiwen Wu, Su Zheng, Ran Chen, **Min Li**, Hao Geng, Binwu Zhu, Mingxuan Yuan, Bei Yu  
          IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2026.
        - <span class="pub-badge pub-badge--iclr">ICLR</span>**Reasoning Scaffolding: Distilling the Flow of Thought from LLMs** [🔗](https://arxiv.org/abs/2509.23619)[📄](files/papers/2509.23619v2.pdf)  
          Xiangyu Wen, Junhua Huang, Zeju Li, **Min Li**, Jianyuan Zhong, Zhijian Xu, Mingxuan Yuan, Yongxiang Huang, Qiang Xu  
          International Conference on Learning Representations, 2026.
        - <span class="pub-badge pub-badge--neurips">NeurIPS</span>**Dependency Matters: Enhancing LLM Reasoning with Explicit Knowledge Grounding** [🔗](https://openreview.net/forum?id=DlkM0q4Cvk)[📄](files/papers/12159_Dependency_Matters_Enhan.pdf)  
          Xiangyu Wen, **Min Li**, Junhua Huang, Jianyuan Zhong, Zhijian Xu, Zeju Li, Yongxiang Huang, Mingxuan Yuan, Qiang Xu  
          Conference on Neural Information Processing Systems, 2025.


  - block: contact
    id: contact
    content:
      email: min.li@seu.edu.cn
      # Automatically link email and phone or display as text?
      autolink: true
      title: Contact
      text: |
        Our lab is headquartered at **National EDA Innovation Center (NCTIEDA), Jiangbei, Nanjing**. We are looking for motivated students to join FORMiND Lab as research interns, master or Ph.D. students in Southeast University! 

        Min welcomes coffee discussions with students/researchers/engineers passionate about developing cutting-edge EDA tools! Please note that Min splits his time between **Shenzhen** and **Nanjing**; advance email coordination is preferred for on-site meetings.

        **Calendar**
        <br>
        <iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=2&ctz=Asia%2FHong_Kong&showPrint=0&mode=WEEK&src=bWlubGkuYW1veUBnbWFpbC5jb20&src=ZW4uY2hpbmEjaG9saWRheUBncm91cC52LmNhbGVuZGFyLmdvb2dsZS5jb20&color=%23039be5&color=%230b8043" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>    
    design:
      columns: '1'

---
