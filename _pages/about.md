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

My name is Yunhan Qiao. I am a Ph.D. candidate supervised by [Dr. Christopher Hundhausen](https://engineering.oregonstate.edu/people/christopher-hundhausen) at Oregon State University. Before that, I earned my M.S. in Software Engineering from Arizona State University, supervised by [Dr. Robert Likamwa](https://search.asu.edu/profile/3025945). My research interests include human-AI interaction, specifically how GenAI coding assistance tools (e.g., GitHub Copilot) can improve the efficiency of software engineering tasks without sacrificing code comprehension.


# 🔥 News


# 📝 Publications 
<strong>[CSEE&T '26]</strong> <a href="https://arxiv.org/pdf/2511.02922"><strong>Code Comprehension with GitHub Copilot: Performance Gains, Comprehension Trade-offs, and Behavioral Predictors in Brownfield Programming</strong></a>
<strong>Yunhan Qiao</strong>, Md Istiak Hossain Shihab, Summit Haque, Christopher Hundhausen
<em>In: The 38th International Conference on Software Engineering Education and Training (CSEE&T 2026)</em>
<em>(Under Review)</em>
<br>
<br>
<strong>[TOCE]</strong> <a href="YOUR_PAPER_LINK_HERE"><strong>Using SlackBot-Prompted Reflections to Promote Participation and Reduce Contribution Inequalities in Team Software Development Projects
</strong></a>
Ahsun Tariq, Phillip Conrad, Christopher Hundhausen, Sanjay Chandrasekaran, Yunhan Qiao, Summit Haque
<em>In: ACM Transactions on Computing Education (TOCE)</em>
<em>(Under Review)</em>
<br>
<br>
<strong>[TOCE]</strong> <a href="https://dl.acm.org/doi/pdf/10.1145/3785366"><strong>A Systematic Literature Review of the Use of GenAI Assistants for Code Comprehension: Implications for Computing Education and Practice</strong></a>
<strong>Yunhan Qiao</strong>, Md Istiak Hossain Shihab, Christopher Hundhausen
<em>In: ACM Transactions on Computing Education (TOCE)</em>
<br>
<br>
<strong>[ICER '25]</strong> <a href="https://dl.acm.org/doi/pdf/10.1145/3702652.3744219"><strong>The Effects of GitHub Copilot on Computing Students' Programming Effectiveness, Efficiency, and Processes in Brownfield Programming Tasks</strong></a>
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

My dissertation investigates code comprehension in GenAI-assisted development across four research questions:

---

**RQ1: How does GenAI support code comprehension? (Systematic Literature Review)**

<div style="border: 1px solid #e0e0e0; border-radius: 6px; padding: 14px; background: #fafafa; margin-bottom: 1.2em;">
  I conducted a Systematic Literature Review (SLR) of 31 studies (2022–2024) to categorize how GenAI assistants support code comprehension. The review identifies five categories of approaches: explaining software, enhancing pedagogy, enriching documentation, improving readability, and visualizing software. A key finding is that the literature focuses almost entirely on how GenAI <em>enhances</em> comprehension outcomes, largely overlooking how GenAI might <em>circumvent</em> traditional comprehension and sense-making processes.
  <div style="margin-top: 10px;">
    <strong>📄 Related Paper</strong>
    <ul style="margin: 6px 0 0 0; padding-left: 1.2em;">
      <li>
        <a href="https://dl.acm.org/doi/pdf/10.1145/3785366"><i class="fas fa-file-pdf" style="color:#c0392b;"></i> <strong>A Systematic Literature Review of the Use of GenAI Assistants for Code Comprehension: Implications for Computing Education and Practice</strong></a><br>
        <em>ACM Transactions on Computing Education (TOCE) 2026 — <strong>Published</strong></em>
      </li>
    </ul>
  </div>
</div>

---

**RQ2: How does GenAI assistance affect students' code comprehension in brownfield tasks?**

<div style="display: flex; gap: 20px; align-items: flex-start; border: 1px solid #e0e0e0; border-radius: 6px; padding: 14px; background: #fafafa; margin-bottom: 1.2em;">
  <div style="flex: 0 0 40%;">
    <img src="/images/RQ2-Final.png" alt="RQ2 Behavioral Analysis" style="width: 100%; border-radius: 4px;">
  </div>
  <div style="flex: 1;">
    I conducted a within-subjects study with 15 graduate CS students completing brownfield feature implementation tasks with and without GitHub Copilot. Despite significant performance gains (50.7% faster, 71.4% more tests passed), participants showed no overall comprehension improvement (p = 0.59) — a <em>comprehension-performance decoupling</em>. Behavioral analysis revealed the <strong>verification loop</strong> (WC→VC→WC) as the strongest predictor of comprehension (p &lt; 0.001, r = 0.96), distinguishing <em>Active Integrators</em> from <em>Passive Delegators</em>.
    <div style="margin-top: 10px;">
      <strong>📄 Related Papers</strong>
      <ul style="margin: 6px 0 0 0; padding-left: 1.2em;">
        <li>
          <a href="https://arxiv.org/pdf/2511.02922"><i class="fas fa-file-pdf" style="color:#c0392b;"></i> <strong>Code Comprehension with GitHub Copilot: Performance Gains, Comprehension Trade-offs, and Behavioral Predictors in Brownfield Programming</strong></a><br>
          <em>CSEE&T 2026 — <strong>Under Review</strong></em>
        </li>
        <li style="margin-top: 6px;">
          <a href="https://dl.acm.org/doi/pdf/10.1145/3702652.3744219"><i class="fas fa-file-pdf" style="color:#c0392b;"></i> <strong>The Effects of GitHub Copilot on Computing Students' Programming Effectiveness, Efficiency, and Processes in Brownfield Programming Tasks</strong></a><br>
          <em>ICER 2025 — <strong>Published</strong></em>
        </li>
      </ul>
    </div>
  </div>
</div>

---

**RQ3: What are expert best practices for comprehending legacy codebases with GenAI?**

<div style="border: 1px solid #e0e0e0; border-radius: 6px; padding: 14px; background: #fafafa; margin-bottom: 1.2em;">
  This study explores how expert MERN-stack developers (≥3 years of experience, daily GenAI use) comprehend and navigate a large-scale legacy codebase (~10× the size used in RQ2) using GitHub Copilot. Unlike the student study, this asks <em>how</em> experts maintain codebase understanding: what strategies they use to comprehend AI-generated code, how they hold system-level specifications in mind when evaluating AI suggestions, and when they choose to verify deeply versus accept output shallowly. These expert practices will serve as the empirical grounding for the pedagogical intervention in RQ4.
  <div style="margin-top: 10px;">
    <strong>📄 Related Papers</strong>
    <ul style="margin: 6px 0 0 0; padding-left: 1.2em;">
      <li><em>Venue TBD — <strong>Work in Progress</strong></em></li>
    </ul>
  </div>
</div>

---

**RQ4: How can expert best practices be translated into a pedagogical intervention?**

<div style="display: flex; gap: 20px; align-items: flex-start; border: 1px solid #e0e0e0; border-radius: 6px; padding: 14px; background: #fafafa; margin-bottom: 1.2em;">
  <div style="flex: 0 0 40%;">
    <img src="/images/RQ4.png" alt="RQ4 Eye-Tracking Agent Workflow" style="width: 100%; border-radius: 4px;">
  </div>
  <div style="flex: 1;">
    Building on the expert strategies identified in RQ3, this chapter designs and evaluates an AI-agent scaffolding intervention to train computing students to comprehend legacy codebases when using GenAI. The agent is implemented as a VSCode extension that continuously monitors gaze data, classifies the developer's comprehension level (Global / Component / Local), compares it against expert behavioral patterns from RQ3, and delivers deferred scaffolding nudges at natural breakpoints — without interrupting the developer's flow.
    <div style="margin-top: 10px;">
      <strong>📄 Related Papers</strong>
      <ul style="margin: 6px 0 0 0; padding-left: 1.2em;">
        <li><em>Venue TBD — <strong>Planned</strong></em></li>
      </ul>
    </div>
  </div>
</div>


# 💻 Internships
- *2020.08 - 2020.11*, Mocha Software Company, Nanjing, China.
