<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ujjawal Rawat — Internship Portfolio</title>
  <meta name="description" content="Internship task portfolio: Ansible, Terraform, Docker Compose, Jenkins, EC2 deployments" />
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#9aa7bf; --accent:#4f46e5; --glass: rgba(255,255,255,0.03);
      --glass-2: rgba(255,255,255,0.02);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#071028 0%, #071730 60%);color:#e6eef8;min-height:100vh}
    .container{max-width:1100px;margin:36px auto;padding:28px}

    header{display:flex;gap:18px;align-items:center}
    .avatar{width:84px;height:84px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#06b6d4);display:flex;align-items:center;justify-content:center;font-weight:700;color:white;box-shadow:0 6px 22px rgba(79,70,229,0.15)}
    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .grid{display:grid;grid-template-columns:repeat(2,1fr);gap:18px;margin-top:20px}
    @media (max-width:880px){.grid{grid-template-columns:1fr}}

    .card{background:linear-gradient(180deg,var(--card),rgba(11,18,32,0.6));border-radius:12px;padding:16px;box-shadow:0 6px 20px rgba(2,6,23,0.6);border:1px solid var(--glass-2)}
    .card h3{margin:0 0 6px;font-size:16px}
    .muted{color:var(--muted);font-size:13px}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.03);font-weight:600;color:var(--accent);border:1px solid rgba(79,70,229,0.12)}

    .tasks{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:18px}
    @media (max-width:1100px){.tasks{grid-template-columns:repeat(2,1fr)}}
    @media (max-width:720px){.tasks{grid-template-columns:1fr}}

    .task-card{padding:14px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.02)}
    .task-card small{display:block;color:var(--muted);margin-bottom:8px}
    .task-card p{margin:8px 0 0;color:#d8e6ff}
    .actions{display:flex;gap:10px;margin-top:12px}
    .btn{padding:8px 12px;border-radius:8px;background:var(--accent);border:none;color:white;cursor:pointer;font-weight:600}
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted)}

    .gallery{margin-top:22px}
    .gallery-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
    @media (max-width:1000px){.gallery-grid{grid-template-columns:repeat(3,1fr)}}
    @media (max-width:700px){.gallery-grid{grid-template-columns:repeat(2,1fr)}}
    .thumb{border-radius:8px;overflow:hidden;border:1px solid rgba(255,255,255,0.03);background:#061226}
    .thumb img{width:100%;height:140px;object-fit:cover;display:block}

    footer{margin-top:28px;color:var(--muted);font-size:13px;text-align:center}

    /* small helpers */
    details{margin-top:10px}
    summary{cursor:pointer}
    .note{background:rgba(255,255,255,0.02);padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.02);color:var(--muted)}

    .kbd{display:inline-block;padding:6px 8px;border-radius:6px;background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.02);font-family:monospace;font-size:13px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">UR</div>
      <div>
        <h1>Ujjawal Rawat — Internship Portfolio</h1>
        <p class="lead">6 tasks completed — Ansible, Terraform, Docker Compose, Jenkins, EC2 deployments. Click cards to view details or open documents in this repo.</p>
      </div>
      <div style="margin-left:auto;text-align:right">
        <div class="pill">Due: 03/04/2026 • Done</div>
        <div class="muted" style="font-size:12px;margin-top:8px">Updated: Oct 3, 2025</div>
      </div>
    </header>

    <section class="grid">
      <div class="card">
        <h3>Project Summary</h3>
        <p class="muted">This repository contains detailed documentation and screenshots for 6 internship tasks. Each task includes step-by-step commands, configuration files, and verification steps. Use the portfolio site to share with mentors and recruiters.</p>

        <div style="margin-top:12px;display:flex;gap:8px;flex-wrap:wrap">
          <span class="pill">Ansible</span>
          <span class="pill">Terraform</span>
          <span class="pill">Jenkins</span>
          <span class="pill">Docker</span>
          <span class="pill">EC2</span>
        </div>

        <details>
          <summary style="margin-top:12px">How to use</summary>
          <div class="note">Place this file as <code class="kbd">index.html</code> in your repo root. Put screenshots in <code class="kbd">/screenshots/</code>. Edit the <code>imagesMap</code> array in the script below to match your screenshot filenames. Enable GitHub Pages from repo settings to publish this page.</div>
        </details>
      </div>

      <div class="card">
        <h3>Quick Links</h3>
        <p class="muted">Open the original docs stored in this repo or jump to the gallery.</p>
        <div style="margin-top:12px;display:flex;gap:8px;flex-wrap:wrap">
          <a class="btn" href="./Internship%20Task%20Documentation%201.docx" download>Doc 1</a>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%202.docx">Doc 2</a>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%203.docx">Doc 3</a>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%204.docx">Doc 4</a>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%205.docx">Doc 5</a>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%206.docx">Doc 6</a>
        </div>

        <div style="margin-top:12px" class="muted">Tip: If a doc link shows raw file, click the three dots on GitHub and select "View file" or download to open locally.</div>
      </div>
    </section>

    <section class="tasks">
      <div class="task-card">
        <small>Task 1</small>
        <h3>Ansible — Configuration Management</h3>
        <p>Install Docker, pull your Docker Hub image, and run container with restart policy. Playbook file: <code class="kbd">docker-playbook.yml</code>.</p>
        <div class="actions">
          <button class="btn" onclick="scrollToGallery('task1')">View Screenshots</button>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%201.docx">Open Doc</a>
        </div>
      </div>

      <div class="task-card">
        <small>Task 2</small>
        <h3>Terraform — EC2 Infrastructure</h3>
        <p>Terraform scripts to launch EC2, open ports 80 &amp; 22 and install Docker via user_data.</p>
        <div class="actions">
          <button class="btn" onclick="scrollToGallery('task2')">View Screenshots</button>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%202.docx">Open Doc</a>
        </div>
      </div>

      <div class="task-card">
        <small>Task 3</small>
        <h3>Docker Compose — Multi-Environment</h3>
        <p>docker-compose.yml to run Nginx static site and Watchtower for auto-updates.</p>
        <div class="actions">
          <button class="btn" onclick="scrollToGallery('task3')">View Screenshots</button>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%203.docx">Open Doc</a>
        </div>
      </div>

      <div class="task-card">
        <small>Task 4</small>
        <h3>Webhook Integration — GitHub → Jenkins</h3>
        <p>Configured GitHub webhook to trigger Jenkins build on push to main branch.</p>
        <div class="actions">
          <button class="btn" onclick="scrollToGallery('task4')">View Screenshots</button>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%204.docx">Open Doc</a>
        </div>
      </div>

      <div class="task-card">
        <small>Task 5</small>
        <h3>Deploy to EC2</h3>
        <p>SSH into EC2, pull image from Docker Hub, run container and expose on port 80/8080.</p>
        <div class="actions">
          <button class="btn" onclick="scrollToGallery('task5')">View Screenshots</button>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%205.docx">Open Doc</a>
        </div>
      </div>

      <div class="task-card">
        <small>Task 6</small>
        <h3>Jenkins Pipeline</h3>
        <p>Declarative Jenkinsfile to build Docker image and push to DockerHub (instantprachi namespace).</p>
        <div class="actions">
          <button class="btn" onclick="scrollToGallery('task6')">View Screenshots</button>
          <a class="btn ghost" href="./Internship%20Task%20Documentation%206.docx">Open Doc</a>
        </div>
      </div>
    </section>

    <section class="gallery" id="gallery">
      <h2 style="margin:0 0 10px">📸 Screenshots Gallery</h2>
      <p class="muted">Below are screenshots grouped by task. If images do not appear, make sure your screenshot files are uploaded to <code class="kbd">/screenshots</code> and that the filenames are listed in the script at the bottom of this file.</p>

      <div id="galleryWrapper">
        <!-- thumbnails will be injected by script -->
      </div>

    </section>

    <footer>
      Built with ❤️ by <strong>Ujjawal Rawat</strong> • Share: <a href="https://github.com/Ujjawal17-alt" style="color:inherit;opacity:0.85">github.com/Ujjawal17-alt</a>
    </footer>
  </div>

  <script>
    /*
      👉 Edit the imagesMap below to match your screenshot filenames.
      Structure: 'task1', 'task2', ... arrays contain filenames located in /screenshots/
      Example: imagesMap.task1 = ['task1_ssh.png','task1_playbook.png']
    */
    const imagesMap = {
      task1: [
        'task1_ssh.png',
        'task1_inventory.png',
        'task1_playbook.png',
        'task1_dockerps.png',
        'task1_browser.png'
      ],
      task2: ['task2_init.png','task2_apply.png','task2_ec2.png'],
      task3: ['task3_compose.png','task3_nginx.png'],
      task4: ['task4_webhook.png','task4_jenkins.png'],
      task5: ['task5_pull.png','task5_run.png','task5_web.png'],
      task6: ['task6_jenkinsfile.png','task6_build.png','task6_dockerhub.png']
    }

    function createThumb(src, alt){
      const div = document.createElement('div'); div.className='thumb';
      const img = document.createElement('img'); img.src=src; img.alt=alt; img.onerror = ()=>{img.src='data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="600" height="400"><rect width="100%" height="100%" fill="%23071C2A"/><text x="50%" y="50%" fill="%23fff" font-size="18" font-family="Arial" text-anchor="middle">Image not found</text></svg>'}
      div.appendChild(img); return div
    }

    function renderGallery(){
      const wrap = document.createElement('div'); wrap.className='gallery-grid';
      Object.keys(imagesMap).forEach(taskKey=>{
        const list = imagesMap[taskKey];
        list.forEach(fname=>{
          const path = './screenshots/' + fname;
          const thumb = createThumb(path, fname);
          wrap.appendChild(thumb);
        })
      })
      const target = document.getElementById('galleryWrapper');
      target.innerHTML=''; target.appendChild(wrap);
    }

    function scrollToGallery(task){
      const el = document.getElementById('gallery');
      el.scrollIntoView({behavior:'smooth', block:'start'});
      // highlight: briefly outline thumbnails (simple UX)
      setTimeout(()=>{
        const thumbs = document.querySelectorAll('.thumb');
        thumbs.forEach(t=>{t.style.boxShadow='0 8px 30px rgba(79,70,229,0.12)'; setTimeout(()=>t.style.boxShadow='',1200)})
      },300)
    }

    // initial render
    renderGallery();
  </script>
</body>
</html>
