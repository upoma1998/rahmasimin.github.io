
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Rahma Simin Ali | Portfolio</title>
  <meta name="description" content="Rahma Simin Ali — Software Engineer & ML Researcher. Trustworthy ML, NLP/LLMs, IoT/CP systems, reliability-critical software." />

  <style>
    :root{
      --bg:#ffffff;
      --text:#111827;
      --muted:#6b7280;
      --link:#0366d6;
      --border:#e5e7eb;
      --chip:#f3f4f6;
      --max: 980px;
    }
    html { scroll-behavior:smooth; }
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      color:var(--text);
      background:var(--bg);
      line-height:1.6;
    }
    a{ color:var(--link); text-decoration:none; }
    a:hover{ text-decoration:underline; }

    /* Fixed nav like reference */
    nav{
      position:fixed; top:0; left:0; width:100%;
      background:#f8f8f8;
      border-bottom:1px solid #ddd;
      z-index:1000;
    }
    nav .wrap{
      max-width:var(--max);
      margin:0 auto;
      padding:10px 16px;
      display:flex;
      gap:18px;
      align-items:center;
      justify-content:center;
      flex-wrap:wrap;
    }
    nav a{ font-weight:700; color:var(--link); }

    /* Page layout */
    main{ padding-top:74px; }
    section{
      max-width:var(--max);
      margin:0 auto;
      padding:56px 16px;
      border-bottom:1px solid var(--border);
    }
    h1{ font-size:40px; margin:0 0 6px 0; line-height:1.15; }
    h2{ font-size:26px; margin:0 0 14px 0; }
    h3{ font-size:18px; margin:18px 0 8px 0; }
    p{ margin:0 0 12px 0; color:var(--text); }
    .muted{ color:var(--muted); }

    /* Hero */
    .hero{
      display:grid;
      grid-template-columns: 140px 1fr;
      gap:22px;
      align-items:center;
    }
    .avatar{
      width:140px; height:140px;
      border-radius:14px;
      object-fit:cover;
      border:1px solid var(--border);
      background:#fafafa;
    }
    .social{
      display:flex; gap:12px; flex-wrap:wrap;
      margin-top:10px;
    }
    .pill{
      display:inline-flex;
      align-items:center;
      gap:8px;
      border:1px solid var(--border);
      background:#fff;
      padding:8px 12px;
      border-radius:999px;
      font-weight:600;
      color:var(--text);
    }
    .pill:hover{ text-decoration:none; border-color:#cbd5e1; }

    /* Chips */
    .chips{ display:flex; gap:10px; flex-wrap:wrap; margin-top:10px; }
    .chip{
      background:var(--chip);
      border:1px solid var(--border);
      padding:6px 10px;
      border-radius:999px;
      font-size:13px;
      color:var(--muted);
      font-weight:600;
    }

    /* Resume blocks */
    .card{
      border:1px solid var(--border);
      border-radius:14px;
      padding:16px 16px;
      background:#fff;
      margin-top:12px;
    }
    ul{ margin:10px 0 0 18px; padding:0; }
    li{ margin:6px 0; }

    /* Projects filter like reference */
    .filters{
      display:flex;
      gap:10px;
      flex-wrap:wrap;
      margin:14px 0 18px 0;
    }
    .btn{
      border:1px solid var(--border);
      background:#fff;
      padding:8px 12px;
      border-radius:10px;
      cursor:pointer;
      font-weight:700;
      color:var(--text);
    }
    .btn.active{
      border-color:#93c5fd;
      background:#eff6ff;
      color:#1d4ed8;
    }
    .grid{
      display:grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap:14px;
    }
    @media (max-width: 760px){
      .hero{ grid-template-columns: 1fr; }
      .avatar{ width:120px; height:120px; }
      .grid{ grid-template-columns: 1fr; }
      nav .wrap{ justify-content:center; }
    }
    .proj{
      border:1px solid var(--border);
      border-radius:14px;
      padding:16px;
      background:#fff;
    }
    .proj .meta{
      margin-top:8px;
      display:flex;
      gap:8px;
      flex-wrap:wrap;
    }
    .tag{
      font-size:12px;
      padding:4px 8px;
      border-radius:999px;
      border:1px solid var(--border);
      color:var(--muted);
      background:#fafafa;
      font-weight:700;
    }
    .proj h3{ margin:0 0 8px 0; }
    .proj p{ margin:0; color:var(--muted); }

    /* Footer spacing */
    footer{
      max-width:var(--max);
      margin:0 auto;
      padding:34px 16px 60px 16px;
      color:var(--muted);
      font-size:14px;
    }
  </style>
  
</head>

<body>
  <nav>
    <div class="wrap">
      <a href="#resume">Resume</a>
      <a href="https://drive.google.com/file/d/1SdIhpDa4FnJ6BOgNUMNbUEYbrG-uV7WT/view?usp=sharing"
       target="_blank"
       rel="noopener noreferrer">
      Resume (PDF)
    </a>
      <a href="#projects">Projects</a>
      <a href="#achievements">Achievements</a>
      <a href="#leadership">Leadership</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <main>
    <!-- HERO / ABOUT -->
    <section id="about">
      <div class="hero">
        <!-- Put your photo at /assets/profile.jpg (or change the path here) -->
        <!-- <img class="avatar" src="assets/image.jpg" alt="Rahma Simin Ali" /> -->
         <img class="avatar" src="assets/NY.jpg" alt="Rahma Simin Ali" />
         <!-- <img class="avatar" src="assets/image.jpg" alt="Rahma Simin Ali" /> -->
        <div>
          <h1>Rahma Simin Ali</h1>
          <p class="muted"><strong>Software Engineer</strong> &nbsp;|&nbsp; <strong>Machine Learning Researcher</strong></p>

          <div class="social">
            <a class="pill" href="https://github.com/" target="_blank" rel="noreferrer">GitHub</a>
            <a class="pill" href="https://www.linkedin.com/" target="_blank" rel="noreferrer">LinkedIn</a>
            <a class="pill" href="mailto:rahmasimin@gmail.com">Email</a>
            <a class="pill" href="https://scholar.google.com/citations?hl=en&user=ImxU8DIAAAAJ&view_op=list_works&gmla=AH8HC4xTYBp80ZfyN29QRG22c-0nV0l93Dp6bEVvQG1rcPDHGIj2HspUynis0qLdeHEVLN6Hx46Em5uB7c59RAqx" target="_blank" rel="noreferrer">Google Scholar</a>
          </div>

          <div class="chips">
            <span class="chip">Trustworthy ML</span>
            <span class="chip">NLP / LLMs</span>
            <span class="chip">Low-Resource + Clinical NLP</span>
            <span class="chip">Software Engineering</span>
            <span class="chip">IoT / Cyber-Physical</span>
            <span class="chip">Reliability-Critical Systems</span>
          </div>
        </div>
      </div>

      <h2 style="margin-top:26px;">About me</h2>
      <p>
        I’m <strong>Rahma Simin Ali</strong> (she/her), a Software Engineer and Machine Learning Researcher with over
        <strong>2 years of industry experience</strong> at CloudlyIO and Cloudly Infotech Limited.
      </p>
      <p>
        My work sits at the intersection of trustworthy machine learning, natural language processing,
        cyber-physical systems, and reliability-critical software engineering. Across research and industry,
        I focus on a single guiding question:
        <em>How can we build intelligent systems whose behavior, reasoning, and failures remain reliable under real-world constraints?</em>
      </p>
      <p>
        I am currently applying to <strong>PhD programs in Computer Science (Fall 2026)</strong>, with research interests centered on
        ML systems, LLM reasoning faithfulness, low-resource NLP, and dependable AI for safety-critical domains.
      </p>
    </section>

    <!-- RESUME -->
    <section id="resume">
      <h2>My Resume</h2>

      <div class="card">
        <h3>Education</h3>
        <p><strong>B.Sc. in Computer Science and Engineering</strong> — Chittagong University of Engineering and Technology (CUET)</p>
        <ul>
          <li>GPA: <strong>3.74 / 4.00</strong> (Last 4 semesters: <strong>3.85</strong>)</li>
          <li>Merit Position: <strong>13th out of 126</strong></li>
          <li>Full merit-based undergraduate scholarship</li>
        </ul>
      </div>

      <div class="card">
        <h3>Publications</h3>
        <ul>
          <li><strong>ReTSoSPA</strong> — IoT-based Real Time Soil Sensing for Precision Agriculture (IEEE ICCIT 2024)</li>
          <li><strong>Optimizing Complexity of Quick Sort</strong> (ICCSCS 2020, Springer)</li>
        </ul>
      </div>

      <div class="card">
        <h3>Industry Experience</h3>
        <ul>
          <li><strong>Software Engineer</strong>, Cloudly Infotech Limited (2024–2025): correctness-critical backend systems; security; reliability</li>
          <li><strong>Software Engineer Intern</strong>, CloudlyIO (2023–2024): Rails, testing, background jobs, performance</li>
        </ul>
      </div>
    </section>

    <!-- PROJECTS (with filter) -->
    <section id="projects">
      <h2>Projects</h2>
      <p class="muted">Filter by category to quickly skim.</p>

      <div class="filters">
        <button class="btn active" data-filter="all">All</button>
        <button class="btn" data-filter="ml">Machine Learning</button>
        <button class="btn" data-filter="systems">Systems</button>
        <button class="btn" data-filter="software">Software Development</button>
      </div>

      <div class="grid" id="projectGrid">
        <!-- ML -->
        <div class="proj" data-cat="ml">
          <h3>LLM Fine-Tuning for Mathematical Reasoning Faithfulness</h3>
          <p>
            Curated step-aligned hints + fine-tuned LLMs to reduce inconsistent intermediate steps; controlled evaluation beyond final answer accuracy.
          </p>
          <div class="meta">
            <span class="tag">Machine Learning</span>
            <span class="tag">NLP / LLMs</span>
            <span class="tag">Trustworthy AI</span>
          </div>
        </div>

        <div class="proj" data-cat="ml">
          <h3>BanglaBERT for Alzheimer’s Detection</h3>
          <p>
            Built a low-resource clinical NLP benchmark by adapting DementiaNet with controlled translation and biomarker-preserving validation.
          </p>
          <div class="meta">
            <span class="tag">Clinical NLP</span>
            <span class="tag">Low-Resource</span>
            <span class="tag">Evaluation</span>
          </div>
        </div>

        <!-- Systems / IoT -->
        <div class="proj" data-cat="systems">
          <h3>ReTSoSPA / SoilSensingBD (IEEE ICCIT 2024)</h3>
          <p>
            End-to-end cyber-physical pipeline (sensors → wireless → ESP32 → cloud); 3,918 measurements; XGBoost 99% crop prediction accuracy.
          </p>
          <div class="meta">
            <span class="tag">IoT</span>
            <span class="tag">Cyber-Physical</span>
            <span class="tag">ML Systems</span>
          </div>
        </div>

        <!-- Software -->
        <div class="proj" data-cat="software">
          <h3>JEXCA Alumni Platform (2,500+ users)</h3>
          <p>
            Correctness-critical workflows (secure elections, payments, RBAC), fault tolerance, audit trails, and production incident response.
          </p>
          <div class="meta">
            <span class="tag">Backend</span>
            <span class="tag">Reliability</span>
            <span class="tag">Security</span>
          </div>
        </div>

        <div class="proj" data-cat="software">
          <h3>Attendance Automation (Biometric → HRM)</h3>
          <p>
            Automated ETL pipeline integrating ZKTime fingerprint machine with Laravel HRM; reduced manual reconciliation; improved tamper resistance.
          </p>
          <div class="meta">
            <span class="tag">Automation</span>
            <span class="tag">ETL</span>
            <span class="tag">Laravel</span>
          </div>
        </div>

        <div class="proj" data-cat="software">
          <h3>CloudBox: Role-Driven File Collaboration (AWS S3)</h3>
          <p>
            Secure multi-organization storage pipeline with strict permission enforcement and reliable access control.
          </p>
          <div class="meta">
            <span class="tag">AWS S3</span>
            <span class="tag">Access Control</span>
            <span class="tag">Scalability</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ACHIEVEMENTS -->
    <section id="achievements">
      <h2>Achievements</h2>
      <ul>
        <li>Merit Position: <strong>13th / 126</strong> (CUET)</li>
        <li>Full merit-based national undergraduate scholarship</li>
        <li>Appreciation Award for Outstanding Contribution — Cloudly (2025)</li>
        <li>Research Sub-Coordinator — CUET Computer Club</li>
        <li>National Girls’ Programming Contest participant (2019)</li>
      </ul>
    </section>

    <!-- LEADERSHIP -->
    <section id="leadership">
      <h2>Leadership</h2>
      <ul>
        <li>Organized coding competition with <strong>200+ participants</strong> at CUET CSE FEST</li>
        <li>Led seminars/workshops as Research Sub-Coordinator, CUET Computer Club</li>
        <li>Tutored math/science for school + undergraduate students</li>
        <li>Volunteer: Software Engineering best practices, IoT-based smart systems workshops</li>
      </ul>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2>Contact</h2>
      <p>If you are a faculty member or admissions committee member and would like to discuss my work, I’d be happy to connect.</p>
      <p>
        <strong>Email:</strong> <a href="mailto:rahmasimin@gmail.com">rahmasimin@gmail.com</a><br/>
        <strong>Website:</strong> <a href="https://upoma1998.github.io/rahmasimin.github.io/">rahma-simin.github.io</a>
      </p>
    </section>

    <footer>
      © <span id="year"></span> Rahma Simin Ali · Built with GitHub Pages
    </footer>
  </main>

  <script>
    // footer year
    document.getElementById("year").textContent = new Date().getFullYear();

    // project filter behavior (similar to reference site's category filtering)
    const buttons = document.querySelectorAll(".btn");
    const projects = document.querySelectorAll(".proj");

    buttons.forEach(btn => {
      btn.addEventListener("click", () => {
        buttons.forEach(b => b.classList.remove("active"));
        btn.classList.add("active");

        const f = btn.dataset.filter;
        projects.forEach(p => {
          const cat = p.dataset.cat;
          p.style.display = (f === "all" || f === cat) ? "block" : "none";
        });
      });
    });
  </script>
</body>
</html>
