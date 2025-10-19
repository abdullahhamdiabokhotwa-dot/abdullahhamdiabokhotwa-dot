<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Abdullah Hamdi — Profile</title>
  <style>
    /* Reset & fonts */
    :root{
      --bg:#0b0f14;
      --panel:#0f1720;
      --muted:#98a0ab;
      --accent:#2ea44f;
      --card:#0d1620;
      --glass: rgba(255,255,255,0.03);
      --text:#e6eef6;
      --gap:20px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,Arial; background:var(--bg); color:var(--text);}
    a{color:inherit;text-decoration:none}
    .wrap{max-width:1200px;margin:24px auto;padding:24px;display:flex;gap:var(--gap);align-items:flex-start}
    /* Left column (profile) like GitHub) */
    .left{
      width:300px;
      min-width:240px;
      background:var(--panel);
      border-radius:12px;
      padding:20px;
      display:flex;
      flex-direction:column;
      gap:18px;
      box-shadow:0 6px 18px rgba(2,6,23,0.6);
    }
    .avatar{width:160px;height:160px;border-radius:50%;overflow:hidden;margin:6px auto;border:6px solid rgba(255,255,255,0.03)}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    .name{text-align:center}
    .name h1{margin:6px 0 0;font-size:20px}
    .handle{color:var(--muted);font-size:13px;margin-top:4px;text-align:center}
    .follow{display:block;margin:10px auto 0;padding:8px 18px;border-radius:8px;background:linear-gradient(180deg,#1b6b3b,#117a3b);color:white;font-weight:600;width:70%;text-align:center}
    .meta{color:var(--muted);font-size:13px;display:flex;flex-direction:column;gap:8px;padding-top:8px}
    .meta a{color:var(--muted);display:inline-flex;align-items:center;gap:8px}
    .achievements{display:flex;gap:8px;flex-wrap:wrap}
    .achievements img{width:48px;height:48px;border-radius:8px}
    .sidebar-section{background:var(--glass);padding:12px;border-radius:8px}
    /* Right column (README content) */
    .right{flex:1;display:flex;flex-direction:column;gap:18px}
    .card{background:var(--card);border-radius:12px;padding:20px;box-shadow:0 6px 18px rgba(2,6,23,0.5)}
    .hero{display:flex;gap:18px;align-items:flex-start}
    .hero .left-hero{flex:1}
    .hero .right-hero{width:360px;min-width:220px}
    h2{margin:0 0 12px;font-size:18px}
    p{margin:0 0 12px;color:var(--muted);line-height:1.45}
    ul{margin:0 0 12px 18px;color:var(--muted)}
    li{margin:8px 0}
    .icons{display:flex;gap:10px;align-items:center;flex-wrap:wrap}
    .tool{height:42px;width:auto}
    .projects{display:flex;gap:12px;flex-wrap:wrap}
    .project img{height:68px;border-radius:8px}
    .stats img{max-width:100%;border-radius:8px}
    .skill-list{display:flex;gap:12px;align-items:center;flex-wrap:wrap}
    .skill-pill{background:rgba(255,255,255,0.03);padding:8px 12px;border-radius:999px;color:var(--muted);font-weight:600}
    .progress{height:8px;background:rgba(255,255,255,0.04);border-radius:999px;overflow:hidden;width:220px}
    .progress > i{display:block;height:100%;background:linear-gradient(90deg,#2ea44f,#0ea5a2)}
    .contact-grid{display:flex;gap:12px;flex-wrap:wrap}
    .contact-card{background:rgba(255,255,255,0.02);padding:10px 12px;border-radius:8px;color:var(--muted)}
    footer{color:var(--muted);font-size:13px;text-align:center;margin-top:6px}
    @media (max-width:980px){
      .wrap{flex-direction:column;padding:16px}
      .left{width:100%;order:2}
      .right{order:1}
      .hero{flex-direction:column}
      .hero .right-hero{width:100%}
    }
  </style>
</head>
<body>
  <div class="wrap">

    <!-- LEFT: profile panel -->
    <aside class="left" aria-label="profile">
      <div class="avatar">
        <!-- placeholder avatar — replace with your image file -->
        <img src="https://avatars.githubusercontent.com/u/9919?v=4" alt="Profile avatar">
      </div>

      <div class="name">
        <h1>Abdullah Hamdi</h1>
        <div class="handle">Data Analysis · Machine Learning · Backend</div>
      </div>

      <a class="follow" href="#" aria-label="Follow">Follow</a>

      <div class="meta sidebar-section">
        <div><strong>Location</strong><div style="color:var(--muted);margin-top:6px">Cairo, Egypt</div></div>
        <div style="margin-top:8px">
          <strong>Contact</strong>
          <div style="margin-top:6px;color:var(--muted)">email@example.com</div>
        </div>
        <div style="margin-top:8px">
          <strong>Links</strong>
          <div style="margin-top:6px;display:flex;gap:8px;flex-direction:column">
            <a href="#" title="GitHub">GitHub</a>
            <a href="#" title="LinkedIn">LinkedIn</a>
          </div>
        </div>
      </div>

      <div class="sidebar-section">
        <strong>Achievements</strong>
        <div class="achievements" style="margin-top:10px">
          <img src="https://via.placeholder.com/48x48/2ea44f/ffffff?text=A" alt="ach1">
          <img src="https://via.placeholder.com/48x48/117a3b/ffffff?text=B" alt="ach2">
          <img src="https://via.placeholder.com/48x48/0ea5a2/ffffff?text=C" alt="ach3">
        </div>
      </div>

      <div class="sidebar-section" style="text-align:center">
        <div style="font-size:13px;color:var(--muted)">Profile stats</div>
        <div style="display:flex;gap:12px;justify-content:center;margin-top:10px">
          <div><strong>⭐</strong><div style="color:var(--muted);font-size:13px">Stars 0</div></div>
          <div><strong>🔀</strong><div style="color:var(--muted);font-size:13px">Forks 0</div></div>
        </div>
      </div>
    </aside>

    <!-- RIGHT: main README content -->
    <main class="right" aria-label="content">
      <!-- hero -->
      <section class="card hero">
        <div class="left-hero">
          <h2>Hey 👋, I'm Abdullah Hamdi!</h2>
          <p>I am a student at the Faculty of Computers & Artificial Intelligence. I focus on <strong>Data Analysis</strong>, <strong>Machine Learning</strong>, and <strong>Backend Development</strong>. I build data pipelines, models and backend systems — I enjoy turning data into products.</p>

          <div style="margin-top:8px">
            <ul>
              <li>🔭 Currently working on data analysis & backend projects</li>
              <li>🌱 Learning advanced ML techniques and scalable backend design</li>
              <li>💬 Ask me about data cleaning, model evaluation or REST APIs</li>
              <li>📫 Reach me: <span style="color:var(--muted)">email@example.com</span></li>
            </ul>
          </div>
        </div>

        <div class="right-hero">
          <!-- illustrative image -->
          <img src="https://raw.githubusercontent.com/rahul-jha98/rahul-jha98/main/techstack.gif" alt="tech stack" style="width:100%;border-radius:8px;display:block">
        </div>
      </section>

      <!-- Data Analysis -->
      <section class="card">
        <h2>📊 Data Analysis (priority)</h2>
        <p>Work includes: exploratory data analysis, data cleaning pipelines, visualization dashboards and reporting.</p>
        <div style="display:flex;gap:12px;align-items:center;margin-top:12px">
          <a class="project" href="#"><img alt="project1" src="https://via.placeholder.com/220x68?text=EDA+Dashboard"></a>
          <a class="project" href="#"><img alt="project2" src="https://via.placeholder.com/220x68?text=Sales+Analysis"></a>
        </div>
      </section>

      <!-- Machine Learning -->
      <section class="card">
        <h2>🤖 Machine Learning</h2>
        <p>Models & experiments: classification/regression baselines, feature engineering, evaluation and deployment-ready pipelines.</p>
        <ul>
          <li>Supervised models (scikit-learn)</li>
          <li>Deep learning experiments (TensorFlow/PyTorch)</li>
          <li>Model evaluation & monitored deployment</li>
        </ul>
      </section>

      <!-- Backend -->
      <section class="card">
        <h2>🔙 Backend Development</h2>
        <p>Building APIs, authentication, database schema and ETL for ML/data products. Focus on maintainability and testing.</p>
        <div class="projects" style="margin-top:12px">
          <a class="project" href="#"><img alt="api1" src="https://via.placeholder.com/220x68?text=REST+API"></a>
          <a class="project" href="#"><img alt="db" src="https://via.placeholder.com/220x68?text=DB+Design"></a>
        </div>
      </section>

      <!-- Skills & Tools -->
      <section class="card">
        <h2>🔨 Languages & Tools</h2>
        <div class="skill-list" style="margin-top:12px">
          <!-- icons kept left as requested -->
          <img class="tool" src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/cpp/cpp.svg" alt="C++">
          <img class="tool" src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/python/python.svg" alt="Python">
          <span class="skill-pill">Pandas</span>
          <span class="skill-pill">NumPy</span>
          <span class="skill-pill">Scikit-Learn</span>
          <span class="skill-pill">TensorFlow</span>
          <span class="skill-pill">Flask</span>
        </div>

        <div style="margin-top:14px;display:flex;gap:18px;flex-wrap:wrap;align-items:center">
          <div>
            <div style="font-size:13px;color:var(--muted);margin-bottom:6px">Python</div>
            <div class="progress"><i style="width:92%"></i></div>
          </div>
          <div>
            <div style="font-size:13px;color:var(--muted);margin-bottom:6px">C++</div>
            <div class="progress"><i style="width:72%"></i></div>
          </div>
        </div>
      </section>

      <!-- GitHub Stats -->
      <section class="card">
        <h2>📈 GitHub Stats</h2>
        <div style="display:flex;gap:12px;flex-wrap:wrap;margin-top:12px">
          <div class="stats" style="flex:1;min-width:260px"><img alt="overview" src="https://raw.githubusercontent.com/rahul-jha98/github-stats-transparent/output/generated/overview.svg"></div>
          <div class="stats" style="flex:1;min-width:260px"><img alt="languages" src="https://raw.githubusercontent.com/rahul-jha98/github-stats-transparent/output/generated/languages.svg"></div>
        </div>
      </section>

      <!-- Contact -->
      <section class="card">
        <h2>📫 Contact</h2>
        <div class="contact-grid" style="margin-top:12px">
          <div class="contact-card">Email: <strong>email@example.com</strong></div>
          <div class="contact-card">LinkedIn: <a href="#">linkedin.com/in/your</a></div>
          <div class="contact-card">GitHub: <a href="#">github.com/your</a></div>
        </div>
      </section>

      <footer>Built with ❤️ — Profile template for Abdullah Hamdi</footer>
    </main>
  </div>
</body>
</html>
