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

<p class="about-intro">
My name is Yunhan Qiao. I am a Ph.D. candidate supervised by <a href="https://engineering.oregonstate.edu/people/christopher-hundhausen">Dr. Christopher Hundhausen</a> at Oregon State University. Before that, I earned my M.S. in Software Engineering from Arizona State University, supervised by <a href="https://search.asu.edu/profile/3025945">Dr. Robert Likamwa</a>. My research interests include human-AI interaction, specifically how GenAI coding assistance tools (e.g., GitHub Copilot) can improve the efficiency of software engineering tasks without sacrificing code comprehension.
</p>


# 🔥 News


# 📝 Publications

<ul class="pub-list">

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">CSEE&amp;T '26</span>
      <span class="pub-status under-review">Under Review</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="https://arxiv.org/pdf/2511.02922">Code Comprehension with GitHub Copilot: Performance Gains, Comprehension Trade-offs, and Behavioral Predictors in Brownfield Programming</a></div>
      <div class="pub-authors"><strong>Yunhan Qiao</strong>, Md Istiak Hossain Shihab, Summit Haque, Christopher Hundhausen</div>
      <div class="pub-venue">The 38th International Conference on Software Engineering Education and Training (CSEE&amp;T 2026)</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">TOCE</span>
      <span class="pub-status published">Published</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="#">Using SlackBot-Prompted Reflections to Promote Participation and Reduce Contribution Inequalities in Team Software Development Projects</a></div>
      <div class="pub-authors">Ahsun Tariq, Phillip Conrad, Christopher Hundhausen, Sanjay Chandrasekaran, <strong>Yunhan Qiao</strong>, Summit Haque</div>
      <div class="pub-venue">ACM Transactions on Computing Education (TOCE), 2026</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">TOCE</span>
      <span class="pub-status published">Published</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3785366">A Systematic Literature Review of the Use of GenAI Assistants for Code Comprehension: Implications for Computing Education and Practice</a></div>
      <div class="pub-authors"><strong>Yunhan Qiao</strong>, Md Istiak Hossain Shihab, Christopher Hundhausen</div>
      <div class="pub-venue">ACM Transactions on Computing Education (TOCE), 2026</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">ICER '25</span>
      <span class="pub-status published">Published</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3702652.3744219">The Effects of GitHub Copilot on Computing Students' Programming Effectiveness, Efficiency, and Processes in Brownfield Programming Tasks</a></div>
      <div class="pub-authors">Md Istiak Hossain Shihab, Christopher Hundhausen, Ahsun Tariq, Summit Haque, <strong>Yunhan Qiao</strong>, Brian Mulanda Wise</div>
      <div class="pub-venue">Proceedings of the 2025 ACM Conference on International Computing Education Research (ICER '25)</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">AIxSE '25</span>
      <span class="pub-status published">Published</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="https://mmotwani.com/publications/publication_sources/Motwani25aixse.pdf">LLM-Guided Differential Fuzzing for Detecting Platform-Specific Bugs in Scientific Applications</a></div>
      <div class="pub-authors">Manish Motwani, Aakash Kulkarni, <strong>Yunhan Qiao</strong>, Matthew Davis, Ziyan Chen</div>
      <div class="pub-venue">Proceedings of the IEEE International Conference on AI x Software Engineering (AIxSE '25)</div>
    </div>
  </li>

</ul>


# 🎖 Honors and Awards
- *2023 Fall – Present:* Research Assistantship, Oregon State University.
- *2024 Spring, 2024 & 2025 Summer:* Teaching Assistantship (CS362 Software Engineering II).

# 📖 Education
- *2023 – 2027*, Ph.D. in Computer Science, Oregon State University, Corvallis, Oregon.
- *2021 – 2023*, M.S. in Software Engineering, Arizona State University, Tempe, Arizona.

# 💼 Research Projects

<p>My dissertation investigates code comprehension in GenAI-assisted development across four progressive research projects.</p>

<div class="rq-grid">

  <!-- RQ1 -->
  <div class="rq-card">
    <div class="rq-card-header">
      <span class="rq-label">Project 1</span>
      <h3>How does GenAI support code comprehension? — Systematic Literature Review</h3>
      <span class="pub-status published" style="margin-left:auto;">Published</span>
    </div>
    <div class="rq-card-body">
      <div class="rq-image">
        <img src="/images/RQ1-taxonomy-v2.png" alt="Taxonomy of GenAI Approaches for Code Comprehension">
      </div>
      <div class="rq-content">
        <p>I conducted a Systematic Literature Review (SLR) of 31 studies (2022–2024) to categorize how GenAI assistants support code comprehension. The review identifies five categories of approaches: explaining software, enhancing pedagogy, enriching documentation, improving readability, and visualizing software. A key finding is that the literature focuses almost entirely on how GenAI <em>enhances</em> comprehension outcomes, largely overlooking how GenAI might <em>circumvent</em> traditional comprehension and sense-making processes.</p>
        <div class="rq-papers">
          <div class="rq-papers-label">Related Paper</div>
          <ul>
            <li>
              <i class="fas fa-file-pdf"></i>
              <span class="paper-info">
                <a href="https://dl.acm.org/doi/pdf/10.1145/3785366">A Systematic Literature Review of the Use of GenAI Assistants for Code Comprehension: Implications for Computing Education and Practice</a>
                <span class="paper-venue">ACM Transactions on Computing Education (TOCE) 2026 &mdash; <strong>Published</strong></span>
              </span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- RQ2 -->
  <div class="rq-card">
    <div class="rq-card-header">
      <span class="rq-label">Project 2</span>
      <h3>How does GenAI assistance affect students' code comprehension in brownfield tasks?</h3>
      <span class="pub-status under-review" style="margin-left:auto;">Under Review</span>
    </div>
    <div class="rq-card-body">
      <div class="rq-image">
        <img src="/images/RQ2-Final.png" alt="RQ2 Behavioral Analysis Results">
      </div>
      <div class="rq-content">
        <p>I conducted a within-subjects study with 15 graduate CS students completing brownfield feature implementation tasks with and without GitHub Copilot. Despite significant performance gains (50.7% faster, 71.4% more tests passed), participants showed no overall comprehension improvement (p = 0.59) &mdash; a <em>comprehension-performance decoupling</em>. Behavioral analysis revealed the <strong>verification loop</strong> (WC→VC→WC) as the strongest predictor of comprehension (p &lt; 0.001, r = 0.96), distinguishing <em>Active Integrators</em> from <em>Passive Delegators</em>.</p>
        <div class="rq-papers">
          <div class="rq-papers-label">Related Papers</div>
          <ul>
            <li>
              <i class="fas fa-file-pdf"></i>
              <span class="paper-info">
                <a href="https://arxiv.org/pdf/2511.02922">Code Comprehension with GitHub Copilot: Performance Gains, Comprehension Trade-offs, and Behavioral Predictors in Brownfield Programming</a>
                <span class="paper-venue">CSEE&amp;T 2026 &mdash; <strong>Under Review</strong></span>
              </span>
            </li>
            <li>
              <i class="fas fa-file-pdf"></i>
              <span class="paper-info">
                <a href="https://dl.acm.org/doi/pdf/10.1145/3702652.3744219">The Effects of GitHub Copilot on Computing Students' Programming Effectiveness, Efficiency, and Processes in Brownfield Programming Tasks</a>
                <span class="paper-venue">ICER 2025 &mdash; <strong>Published</strong></span>
              </span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- RQ3 -->
  <div class="rq-card">
    <div class="rq-card-header">
      <span class="rq-label">Project 3</span>
      <h3>What are expert best practices for comprehending legacy codebases with GenAI?</h3>
      <span class="pub-status in-progress" style="margin-left:auto;">Work in Progress</span>
    </div>
    <div class="rq-card-body no-image">
      <div class="rq-content">
        <p>This study explores how expert MERN-stack developers (≥3 years of experience, daily GenAI use) comprehend and navigate a large-scale legacy codebase (~10× the size used in RQ2) using GitHub Copilot. Unlike the student study, this asks <em>how</em> experts maintain codebase understanding: what strategies they use to comprehend AI-generated code, how they hold system-level specifications in mind when evaluating AI suggestions, and when they choose to verify deeply versus accept output shallowly. These expert practices will serve as the empirical grounding for the pedagogical intervention in RQ4.</p>
        <div class="rq-papers">
          <div class="rq-papers-label">Related Papers</div>
          <ul>
            <li>
              <i class="fas fa-flask"></i>
              <span class="paper-info">
                <span class="paper-venue">Venue TBD &mdash; <strong>Work in Progress</strong></span>
              </span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- RQ4 -->
  <div class="rq-card">
    <div class="rq-card-header">
      <span class="rq-label">Project 4</span>
      <h3>How can expert best practices be translated into a pedagogical intervention?</h3>
      <span class="pub-status planned" style="margin-left:auto;">Planned</span>
    </div>
    <div class="rq-card-body">
      <div class="rq-image">
        <img src="/images/RQ4.png" alt="RQ4 Eye-Tracking AI Agent Workflow">
      </div>
      <div class="rq-content">
        <p>Building on the expert strategies identified in RQ3, this chapter designs and evaluates an AI-agent scaffolding intervention to train computing students to comprehend legacy codebases when using GenAI. The agent is implemented as a VSCode extension that continuously monitors gaze data, classifies the developer's comprehension level (Global / Component / Local), compares it against expert behavioral patterns from RQ3, and delivers deferred scaffolding nudges at natural breakpoints — without interrupting the developer's flow.</p>
        <div class="rq-papers">
          <div class="rq-papers-label">Related Papers</div>
          <ul>
            <li>
              <i class="fas fa-flask"></i>
              <span class="paper-info">
                <span class="paper-venue">Venue TBD &mdash; <strong>Planned</strong></span>
              </span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

</div>


# 💻 Internships
- *2020.08 – 2020.11*, Mocha Software Company, Nanjing, China.
