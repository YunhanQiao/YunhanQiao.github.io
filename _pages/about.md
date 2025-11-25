---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is Yunhan Qiao. I am a Ph.D. candidate supervised by [Prof. Christopher Hundhausen](https://engineering.oregonstate.edu/people/christopher-hundhausen) at Oregon State University. Before that, I earned my M.S. in Software Engineering from Arizona State University, supervised by [Dr. Robert Likamwa](https://search.asu.edu/profile/3025945). My research interests include human-AI interaction, specifically how GenAI coding assistance tools (e.g., GitHub Copilot) can improve the efficiency of software engineering tasks without sacrificing code comprehension.


# 🔥 News


# 📝 Publications 
<strong>[ICPC '26]</strong> <a href="https://arxiv.org/pdf/2511.02922"><strong>Comprehension-Performance Gap in GenAI-Assisted Brownfield Programming: A Replication and Extension</strong></a>
<strong>Yunhan Qiao<strong>, Christopher Hundhausen, Summit Haque, Md Istiak Hossain Shihab
<em>In: Proceedings of the 48th International Conference on Program Comprehension</em>
<em>(Under Review)</em>
<br>
<br>
<strong>[ICSE-SEET '26]</strong> <a href="YOUR_PAPER_LINK_HERE"><strong>Focusing Sprint Retrospectives Towards Equality of Contributions in Team Projects</strong></a>
Ahsun Tariq, Phillip Conard, Andrew Yu, Christopher Hundhausen, <strong>Yunhan Qiao</strong>
<em>In: Proceedings of the 48th International Conference on Software Engineering: Software Engineering Education and Training</em>
<em>(Under Review)</em>
<br>
<br>
<strong>[TOCE]</strong> <a href="https://arxiv.org/pdf/2510.17894"><strong>A Systematic Literature Review of the Use of GenAI Assistants for Code Comprehension: Implications for Computing Education and Practice</strong></a>
<strong>Yunhan Qiao</strong>, Md Istiak Hossain Shihab, Christopher Hundhausen
<em>In: ACM Transactions on Computing Education (TOCE)</em>
<br>
<br>
<strong>[ICER '25]</strong> <a href="https://dl.acm.org/doi/full/10.1145/3702652.3744219"><strong>The Effects of GitHub Copilot on Computing Students' Programming Effectiveness, Efficiency, and Processes in Brownfield Programming Tasks</strong></a>
Md Istiak Hossain Shihab, Christopher Hundhausen, Ahsun Tariq, Summit Haque, <strong>Yunhan Qiao</strong>, Brian Mulanda Wise, Christopher Sanchez
<em>In: Proceedings of the 2025 ACM Conference on International Computing Education Research (ICER '25)</em>
<br>
<br>
<strong>[AIxSE '25]</strong> <a href="https://mmotwani.com/publications/publication_sources/Motwani25aixse.pdf"><strong>LLM-Guided Differential Fuzzing for Detecting Platform-Specific Bugs in Scientific Applications</strong></a>
Manish Motwani, Aakash Kulkarni, <strong>Yunhan Qiao<strong>, Matthew Davis, Ziyan Chen
<em>In: Proceedings of the IEEE International Conference on AI x Software Engineering (AIxSE '25)</em>




# 🎖 Honors and Awards
- *2023 Fall - Present:* Research Assistantship. 
- *2024 Spring, 2024,2025 Summer:* Teaching Assistantship (CS362 Software Engineering II).

# 📖 Educations
- *2023 - 2027*, Ph.D. in Computer Science, Oregon State University, Corvallis, Oregon. 
- *2021 - 2023*, M.S. in Software Engineering, Arizona State University, Tempe, Arizona.

# 💼 Projects
**Program Comprehension of Integration Tasks using Copilot:**
![Workflow](/images/workflow.png)
Generative AI(GenAI) offers new opportunities to support programming in various ways. For example, GitHub Copilot has been shown to enhance productivity in software development significantly (e.g., solving basic programming tasks, enhancing code readability, etc.). While GitHub Copilot has proven effective at solving basic programming tasks, it is unclear whether Copilot can be successfully leveraged to help developers with code comprehension in brownfield programming. Given that novices struggle with AI-generated code due to poorly crafted prompts, this can increase their frustration levels. We speculate that they would also struggle to construct prompts to help them understand existing code. This raises two key research questions:
- *Research Question 1:* Do GenAI coding assistance tools affect novices' code comprehension in brownfield programming tasks?
- *Research Question 2:* What strategies do experts use to leverage GenAI coding assistance to help them understand an existing code base?
- *Research Question 3:* Can we extract the best practices from experts and apply those practices for computing students/novice programmers to help them onboard the legacy codebases?


# 💻 Internships
- *2020.08 - 2020.11*, Mocha Software Company, Nanjing, China.
