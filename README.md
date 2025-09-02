<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Alla Yashasri – Amazon SDE Resume</title>
  <style>
    :root {
      --ink: #0f172a;       /* slate-900 */
      --muted: #475569;     /* slate-600 */
      --accent: #0ea5e9;    /* sky-500 */
      --line: #e2e8f0;      /* slate-200 */
    }
    * { box-sizing: border-box; }
    html, body { margin: 0; padding: 0; }
    body {
      font-family: "Inter", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color: var(--ink);
      line-height: 1.35;
      background: #ffffff;
    }
    .page {
      max-width: 900px;
      margin: 28px auto;
      padding: 28px 36px;
      border: 1px solid var(--line);
      border-radius: 14px;
    }
    header {
      display: grid;
      grid-template-columns: 1fr;
      gap: 6px;
      margin-bottom: 12px;
    }
    h1 {
      font-size: 32px;
      margin: 0 0 2px 0;
      letter-spacing: 0.2px;
      font-weight: 800;
    }
    .meta {
      font-size: 14px;
      color: var(--muted);
      display: flex;
      flex-wrap: wrap;
      gap: 10px 18px;
    }
    .meta a { color: inherit; text-decoration: none; border-bottom: 1px dotted var(--muted); }
    .rule { height: 1px; background: var(--line); margin: 10px 0 18px; }

    h2 {
      font-size: 15px;
      text-transform: uppercase;
      letter-spacing: 1.2px;
      color: var(--accent);
      margin: 16px 0 8px;
    }
    p { margin: 0 0 8px; }
    ul { margin: 6px 0 0 18px; padding: 0; }
    li { margin: 4px 0; }

    .grid-2 {
      display: grid;
      grid-template-columns: 1.1fr 1fr;
      gap: 22px;
    }

    .tagline { font-size: 14.5px; color: var(--ink); }

    /* Print styles for one-page fit */
    @media print {
      body { background: #fff; }
      .page { border: none; margin: 0; padding: 0.6in; }
      a { color: #000; text-decoration: none; }
      .grid-2 { grid-template-columns: 1.05fr 1fr; gap: 18px; }
    }
  </style>
</head>
<body>
  <main class="page" role="main">
    <header>
      <h1>Alla Yashasri</h1>
      <div class="meta">
        <span>Visakhapatnam, Andhra Pradesh</span>
        <span>Email: <a href="mailto:allayashasri@gmail.com">allayashasri@gmail.com</a></span>
        <span>Phone: 9110799834</span>
        <span>LinkedIn: <a href="https://www.linkedin.com/in/alla-yashasri-125294289/" target="_blank" rel="noreferrer noopener">linkedin.com/in/alla-yashasri-125294289</a></span>
      </div>
    </header>

    <div class="rule"></div>

    <section aria-label="Objective">
      <h2>Career Objective</h2>
      <p class="tagline">
        Aspiring Software Development Engineer with strong foundations in object‑oriented programming, data structures, algorithms,
        and distributed systems. Skilled in Python, SQL, and Java with proven problem‑solving ability. Eager to build scalable,
        high‑quality software at Amazon.
      </p>
    </section>

    <section aria-label="Education">
      <h2>Education</h2>
      <p><strong>B.Tech – Electronics & Communication Engineering (ECE)</strong></p>
      <p>Vignan’s Institute of Engineering for Women, JNTU‑GV | 2022–Present | CGPA: 8.2</p>
    </section>

    <section aria-label="Skills">
      <h2>Technical Skills</h2>
      <div class="grid-2">
        <div>
          <p><strong>Languages:</strong> Python, Java, C</p>
          <p><strong>Core CS:</strong> Data Structures & Algorithms (DSA), Object‑Oriented Programming (OOP), DBMS, OS</p>
        </div>
        <div>
          <p><strong>Tools:</strong> Pandas, NumPy, SQL, Excel (Pivot Tables, Dashboards)</p>
          <p><strong>Cloud:</strong> Google Workspace, GCP basics / Distributed systems fundamentals</p>
        </div>
      </div>
    </section>

    <section aria-label="Experience">
      <h2>Professional Experience</h2>
      <p><strong>Python Full Stack Development Intern</strong></p>
      <ul>
        <li>Built Python programs for data analysis and reporting.</li>
        <li>Created dashboards and visual reports to track performance and optimize workflows.</li>
        <li>Automated repetitive tasks to improve efficiency and reliability.</li>
      </ul>

      <p><strong>Content Creator & Team Coordinator</strong></p>
      <ul>
        <li>Analyzed engagement data using SQL and Excel to identify patterns and optimization strategies.</li>
        <li>Coordinated multi‑member teams to achieve timely, accurate project delivery.</li>
        <li>Presented findings through concise reports and stakeholder updates.</li>
      </ul>
    </section>

    <section aria-label="Projects">
      <h2>Academic Projects & Leadership</h2>
      <ul>
        <li><strong>RFID‑Based Attendance System</strong> – Hardware/software integration; focused on problem solving and optimization.</li>
        <li>Mentored juniors in SQL, Python programming, and algorithmic problem solving.</li>
      </ul>
    </section>

    <section aria-label="Strengths">
      <h2>Key Strengths</h2>
      <p>Problem‑solving · Analytical reasoning · Communication · Leadership</p>
    </section>

    <section aria-label="Extra">
      <h2>Extra‑Curricular</h2>
      <p>Google Cloud workshops · Cultural activities (dance, singing)</p>
    </section>
  </main>
</body>
</html>
