<style>
/* Simple nav bar styling */
nav {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: #f8f8f8;
  padding: 10px;
  text-align: center;
  border-bottom: 1px solid #ddd;
  z-index: 1000;
}
nav a {
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
  color: #0366d6;
}
nav a:hover {
  text-decoration: underline;
}

/* Add spacing so content isn't hidden under nav */
section {
  padding: 80px 20px 40px 20px;
  max-width: 900px;
  margin: auto;
}
</style>

<nav>
  <a href="#about">About</a>
  <a href="#resume">Resume</a>
  <a href="#projects">Projects</a>
  <a href="#achievements">Achievements</a>
  <a href="#leadership">Leadership</a>
  <a href="#contact">Contact</a>
</nav>


<section id="about">
  <h2>About Me</h2>

  <p>
    I’m <strong>Rahma Simin Ali</strong> (she/her), a <strong>Software Engineer and Machine Learning Researcher</strong>
    with over <strong>2 years of industry experience</strong> at CloudlyIO and Cloudly Infotech Limited.
  </p>

  <p>
    My work lies at the intersection of <strong>trustworthy machine learning</strong>,
    <strong>natural language processing</strong>, <strong>cyber-physical systems</strong>,
    and <strong>reliability-critical software engineering</strong>.
    Across both research and industry, I focus on understanding not only how intelligent
    systems succeed, but how and why they fail.
  </p>

  <p>
    I am guided by a central research question:
    <em>
      How can we build intelligent systems whose behavior, reasoning, and failure modes
      remain reliable under real-world constraints?
    </em>
  </p>

  <p>
    I am currently applying to <strong>PhD programs in Computer Science (Fall 2026)</strong>,
    with research interests centered on <strong>machine learning systems</strong>,
    <strong>LLM reasoning faithfulness</strong>, <strong>low-resource NLP</strong>,
    and <strong>dependable AI for safety-critical domains</strong>.
  </p>
</section>

<section id="resume">
  <h2>Academic Background</h2>

  <p>
    <strong>B.Sc. in Computer Science and Engineering</strong><br>
    Chittagong University of Engineering and Technology (CUET), Bangladesh
  </p>

  <ul>
    <li>GPA: <strong>3.74 / 4.00</strong> (Last 4 semesters: <strong>3.85</strong>)</li>
    <li>Merit Position: <strong>13th out of 126</strong></li>
    <li>Full merit-based undergraduate scholarship through national competition</li>
  </ul>

  <p>
    My undergraduate training provided a strong foundation in algorithms, systems,
    and empirical evaluation, which later shaped my research direction toward
    dependable and real-world machine learning systems.
  </p>
</section>

<section id="projects">
  <h2>Research & Technical Projects</h2>

  <h3>Domain-Specialized Fine-Tuning of LLMs for Mathematical Reasoning</h3>
  <p><em>2025 – Present</em></p>

  <ul>
    <li>
      Curated a structured dataset of mathematical problems with step-aligned solutions
      and hints to evaluate <strong>reasoning faithfulness</strong>, not just final-answer accuracy.
    </li>
    <li>
      Fine-tuned large language models to reduce hallucinated or inconsistent intermediate steps,
      including experiments on <strong>non-English (Bangla) corpora</strong>.
    </li>
    <li>
      Designed controlled evaluation protocols to analyze reasoning stability and failure modes
      across unseen problems.
    </li>
    <li>
      Manuscript in preparation for submission to an <strong>ACL-affiliated NLP workshop</strong>.
    </li>
  </ul>

  <h3>ReTSoSPA: IoT-Based Real-Time Soil Sensing for Precision Agriculture</h3>
  <p><em>Undergraduate Thesis · IEEE ICCIT 2024</em></p>

  <ul>
    <li>
      Designed and deployed an end-to-end cyber-physical pipeline integrating calibrated soil sensors,
      NRF24L01 wireless nodes, an ESP32 gateway, and cloud synchronization.
    </li>
    <li>
      Collected <strong>3,918 real-world sensor measurements</strong> across multiple agricultural sites.
    </li>
    <li>
      Evaluated seven machine learning models and achieved <strong>99% accuracy</strong> using XGBoost.
    </li>
    <li>
      Implemented real-time analytics, automated alerts, and fertilizer recommendation logic
      robust to noisy field conditions.
    </li>
  </ul>

  <h3>Clinical NLP in Low-Resource Settings (ASD & Alzheimer’s Detection)</h3>

  <ul>
    <li>
      Developed CNN-based and classical ML models for early detection of
      <strong>Autism Spectrum Disorder</strong> using structured behavioral features.
    </li>
    <li>
      Constructed a Bangla Alzheimer’s detection benchmark by adapting the DementiaNet
      English corpus under ethical constraints.
    </li>
    <li>
      Preserved clinically salient linguistic biomarkers during cross-lingual transfer,
      addressing challenges unique to low-resource clinical NLP.
    </li>
  </ul>

  <h3>Reliability-Critical Software Systems (Industry)</h3>

  <ul>
    <li>
      Engineered correctness-critical backend systems for <strong>JEXCA</strong>, an alumni platform
      serving over 2,500 users, including secure elections, RBAC, and payment workflows.
    </li>
    <li>
      Diagnosed and mitigated production security incidents involving AWS SES and IAM,
      migrating static credentials to secure secret management.
    </li>
    <li>
      Designed automated attendance and file-collaboration systems emphasizing
      fault tolerance, consistency, and access control.
    </li>
  </ul>
</section>

<section id="achievements">
  <h2>Honors & Achievements</h2>

  <ul>
    <li>Ranked <strong>13th out of 126</strong> in undergraduate cohort at CUET</li>
    <li>Full merit-based national scholarship recipient</li>
    <li>Appreciation Award for Outstanding Contribution, Cloudly (2025)</li>
    <li>Research Sub-Coordinator, CUET Computer Club</li>
    <li>Participant, National Girls’ Programming Contest (2019)</li>
  </ul>
</section>

<section id="leadership">
  <h2>Leadership & Service</h2>

  <ul>
    <li>
      Organized coding competitions with over 200 participants as part of CUET CSE FEST.
    </li>
    <li>
      Led research seminars and workshops as Research Sub-Coordinator of the CUET Computer Club.
    </li>
    <li>
      Conducted tutoring sessions in mathematics and science for secondary and undergraduate students.
    </li>
    <li>
      Volunteered in workshops on software engineering best practices and IoT-based smart systems.
    </li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>

  <p>
    If you are a faculty member, admissions committee member, or researcher interested in my work,
    I would be happy to connect.
  </p>

  <p>
    📧 <strong>Email:</strong> rahmasimin@gmail.com<br>
    🌐 <strong>Website:</strong> https://rahma-simin.github.io
  </p>
</section>
