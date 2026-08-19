---
permalink: /
title: ""
excerpt: ""
author_profile: false
show_masthead: false
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

<header class="profile-hero">
  <img class="profile-photo" src="/{{ site.author.avatar }}" alt="Portrait of Yunhan Qiao">
  <div class="profile-summary">
    <p class="profile-eyebrow">Researcher · Educator · Software Engineer</p>
    <h1 class="profile-name">Yunhan Qiao</h1>
    <p class="profile-role">Ph.D. Candidate · Computer Science · Human–AI Interaction</p>
    <nav class="profile-links" aria-label="Contact and academic profiles">
      <a href="mailto:{{ site.author.email }}">Email</a>
      <a href="{{ site.author.googlescholar }}">Google Scholar</a>
      <a href="{{ site.author.cv }}">CV</a>
      <a href="https://github.com/{{ site.author.github }}">GitHub</a>
      <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>
    </nav>
    <div class="research-focus">
      <span class="focus-dot" aria-hidden="true"></span>
      <span><strong>Research focus</strong> GenAI-assisted software development and code comprehension</span>
    </div>
  </div>
</header>

<div class="about-intro">
  <p>My name is Yunhan Qiao. I am a Ph.D. candidate supervised by <a href="https://engineering.oregonstate.edu/people/christopher-hundhausen">Dr. Christopher Hundhausen</a> at Oregon State University. Before that, I earned my M.S. in Software Engineering from Arizona State University, supervised by <a href="https://search.asu.edu/profile/3025945">Dr. Robert Likamwa</a>.</p>
  <p>My research investigates how GenAI coding assistance tools, including GitHub Copilot, can improve the efficiency of software engineering tasks without sacrificing code comprehension.</p>
</div>


# News
- *Jun 2026:* Invited to serve on the Program Committee for the 58th ACM Technical Symposium on Computer Science Education (SIGCSE TS 2027).
- *Jun 22, 2026:* Passed my Ph.D. preliminary examination at Oregon State University.


# Publications

<ul class="pub-list">

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">TOCE</span>
      <span class="pub-status published">Published</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3785366">A Systematic Literature Review of the Use of GenAI Assistants for Code Comprehension: Implications for Computing Education Research and Practice</a></div>
      <div class="pub-authors"><strong>Yunhan Qiao</strong>, Md. Istiak Hossain Shihab, Christopher Hundhausen</div>
      <div class="pub-venue">ACM Transactions on Computing Education (TOCE), vol. 26, no. 2, pp. 1&ndash;33, 2026</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">TOCE</span>
      <span class="pub-status published">Published</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="#">Using Slackbot-Prompted Reflections to Promote Participation and Reduce Contribution Inequalities in Team Software Development Projects</a></div>
      <div class="pub-authors">Ahsun Tariq, Phillip Conrad, Christopher Hundhausen, S. Chandrasekaran, <strong>Yunhan Qiao</strong>, Summit Haque</div>
      <div class="pub-venue">ACM Transactions on Computing Education (TOCE), 2026</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">ICER '25</span>
      <span class="pub-status published">Published</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3702652.3744219">The Effects of GitHub Copilot on Computing Students' Programming Effectiveness, Efficiency, and Processes in Brownfield Coding Tasks</a></div>
      <div class="pub-authors">Md. Istiak Hossain Shihab, Christopher Hundhausen, Ahsun Tariq, Summit Haque, <strong>Yunhan Qiao</strong>, Brian W. Mulanda</div>
      <div class="pub-venue">Proceedings of the 2025 ACM Conference on International Computing Education Research (ICER '25), Vol. 1, pp. 407&ndash;420</div>
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

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">SIGCSE '27</span>
      <span class="pub-status under-review">Under Submission</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="https://arxiv.org/pdf/2511.02922">Code Comprehension with GitHub Copilot: Performance Gains, Comprehension Trade-offs, and Behavioral Predictors in Brownfield Programming</a></div>
      <div class="pub-authors"><strong>Yunhan Qiao</strong>, Md. Istiak Hossain Shihab, Summit Haque, Christopher Hundhausen</div>
      <div class="pub-venue">Under submission, 58th ACM Technical Symposium on Computer Science Education (SIGCSE 2027)</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">SIGCSE '27</span>
      <span class="pub-status under-review">Under Submission</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="#">Teaching GenAI-Assisted Software Development in Computing Education: An Experimental Study</a></div>
      <div class="pub-authors"><strong>Yunhan Qiao</strong>, Christopher Hundhausen, Md. Istiak Hossain Shihab</div>
      <div class="pub-venue">Under submission, 58th ACM Technical Symposium on Computer Science Education (SIGCSE 2027)</div>
    </div>
  </li>

  <li class="pub-entry">
    <div class="pub-left">
      <span class="pub-badge">ICSE '27</span>
      <span class="pub-status under-review">Under Submission</span>
    </div>
    <div class="pub-right">
      <div class="pub-title"><a href="#">Unraveling the Codebase: Exploring GenAI Adoption for Program Comprehension Among Expert Developers in Brownfield Programming Tasks</a></div>
      <div class="pub-authors"><strong>Yunhan Qiao</strong>, Md. Istiak Hossain Shihab, Ahsun Tariq, Christopher Hundhausen</div>
      <div class="pub-venue">Under submission, 49th IEEE/ACM International Conference on Software Engineering (ICSE 2027)</div>
    </div>
  </li>

</ul>


# Research & Teaching Experience
- *Sep 2023 &ndash; Present:* Graduate Research Assistant, Seal Lab, Oregon State University. Empirical studies of GenAI tools for code comprehension and CS education; designs and runs controlled experiments and mixed-methods analysis (qualitative + quantitative).
- *2024 &ndash; 2025:* Graduate Teaching Assistant, Oregon State University. CS 362: Software Engineering II.

# Education

<div class="education-list">
  <div class="education-entry">
    <div class="education-date">2023 &mdash; 2027</div>
    <div class="education-details">
      <div class="education-degree">Ph.D., Computer Science <span class="education-note">(expected)</span></div>
      <div class="education-school">Oregon State University</div>
    </div>
  </div>
  <div class="education-entry">
    <div class="education-date">2021 &mdash; 2023</div>
    <div class="education-details">
      <div class="education-degree">M.S., Software Engineering</div>
      <div class="education-school">Arizona State University</div>
    </div>
  </div>
  <div class="education-entry">
    <div class="education-date">2017 &mdash; 2020</div>
    <div class="education-details">
      <div class="education-degree">B.E., Information Technology</div>
      <div class="education-school">Southern Cross University</div>
    </div>
  </div>
  <div class="education-entry">
    <div class="education-date">2016 &mdash; 2020</div>
    <div class="education-details">
      <div class="education-degree">B.E., Software Engineering</div>
      <div class="education-school">Guangxi University of Science and Technology</div>
    </div>
  </div>
</div>


# Skills
- **Research Methods:** Mixed-methods empirical research, controlled experiments, semi-structured interviews, thematic analysis, survey design, behavioral log analysis, statistical analysis.
- **Programming:** Python, Java, C.
- **Web Development:** HTML, CSS, React, Express, Flask.
- **Databases:** MySQL, PostgreSQL, MongoDB.
- **GenAI / AI Tools:** Claude Code, OpenAI Codex, Google Gemini, GitHub Copilot.
- **Tooling:** Git / GitHub, LaTeX.
- **Languages:** English (fluent), Mandarin Chinese (native).

# Internships
- *Aug 2020 &ndash; Nov 2020*, Mocha Software Company, Nanjing, China.
