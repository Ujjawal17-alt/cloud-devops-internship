<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DevOps Internship Tasks by Ujjawal Rawat</title>
<style>
:root{
  --bg:#0f1724; --card:#0b1220; --muted:#9aa7bf; --accent:#4f46e5; --accent-hover:#6366f1;
  --glass:rgba(255,255,255,0.03); --glass-2:rgba(255,255,255,0.02);
  font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
}
*{box-sizing:border-box; transition: all 0.3s;}
body{margin:0;background:linear-gradient(180deg,#071028 0%,#071730 60%);color:#e6eef8;min-height:100vh;}
.container{max-width:1100px;margin:40px auto;padding:28px;}
header{display:flex;align-items:center;gap:20px;flex-wrap:wrap;}
.avatar{width:80px;height:80px;border-radius:50%;background:linear-gradient(135deg,var(--accent),#06b6d4); display:flex;align-items:center;justify-content:center;font-weight:700;color:white;font-size:28px;box-shadow:0 6px 22px rgba(79,70,229,0.15);}
h1{margin:0;font-size:28px;}
p.lead{margin:6px 0;color:var(--muted);}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px;margin-top:25px;}
@media(max-width:880px){.grid{grid-template-columns:1fr;}}
.card{background:linear-gradient(180deg,var(--card),rgba(11,18,32,0.6));border-radius:12px;padding:20px;box-shadow:0 6px 25px rgba(2,6,23,0.6);border:1px solid var(--glass-2);}
.card h3{margin:0 0 10px;font-size:18px;}
.muted{color:var(--muted);font-size:13px;}
.tasks{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:20px;}
@media(max-width:1100px){.tasks{grid-template-columns:repeat(2,1fr);}}
@media(max-width:720px){.tasks{grid-template-columns:1fr;}}
.task-card{padding:16px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.02);box-shadow:0 6px 18px rgba(0,0,0,0.25);transition: transform 0.3s, box-shadow 0.3s;}
.task-card:hover{transform: translateY(-5px); box-shadow:0 12px 25px rgba(0,0,0,0.35);}
.task-card small{display:block;color:var(--muted);margin-bottom:6px;}
.task-card p{margin:6px 0;color:#d8e6ff;}
.actions{display:flex;gap:10px;margin-top:12px;flex-wrap:wrap;}
.btn{padding:8px 14px;border-radius:8px;background:var(--accent);border:none;color:white;cursor:pointer;font-weight:600;text-decoration:none;box-shadow:0 4px 12px rgba(79,70,229,0.3);}
.btn:hover{background:var(--accent-hover);}
.btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted);}
.btn.ghost:hover{color:white;border-color:var(--accent);background:rgba(79,70,229,0.1);}
.gallery{margin-top:28px;}
.gallery-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;}
@media(max-width:1000px){.gallery-grid{grid-template-columns:repeat(3,1fr);}}
@media(max-width:700px){.gallery-grid{grid-template-columns:repeat(2,1fr);}}
.thumb{border-radius:10px;overflow:hidden;border:1px solid rgba(255,255,255,0.03);background:#061226;cursor:pointer;transition: transform 0.3s;}
.thumb img{width:100%;height:150px;object-fit:cover;display:block;}
.thumb:hover{transform: scale(1.05);}
footer{margin-top:32px;color:var(--muted);font-size:13px;text-align:center;}
.kbd{display:inline-block;padding:6px 8px;border-radius:6px;background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.02);font-family:monospace;font-size:13px;}
</style>
</head>
<body>
<div class="container">
<header>
<div class="avatar">UR</div>
<div>
<h1>DevOps Internship Tasks by Ujjawal Rawat</h1>
<p class="lead">6 internship tasks completed — Terraform, Docker, Ansible, Jenkins, EC2 deployments.</p>
</div>
</header>

<section class="grid">
<div class="card">
<h3>Project Summary</h3>
<p class="muted">Full documentation and screenshots for all 6 internship tasks with step-by-step commands, configs, and verification.</p>
</div>
<div class="card">
<h3>Quick Links</h3>
<div style="margin-top:10px;display:flex;gap:8px;flex-wrap:wrap">
<a class="btn" href="#">Doc 1</a>
<a class="btn ghost" href="#">Doc 2</a>
<a class="btn ghost" href="#">Doc 3</a>
<a class="btn ghost" href="#">Doc 4</a>
<a class="btn ghost" href="#">Doc 5</a>
<a class="btn ghost" href="#">Doc 6</a>
</div>
</div>
</section>

<section class="tasks">
<div class="task-card">
<small>Task 1</small>
<h3>Ansible — Configuration Management</h3>
<p>Install Docker, pull Docker image, run container with restart policy. Playbook: <code class="kbd">docker-playbook.yml</code></p>
<div class="actions">
<button class="btn" onclick="scrollToGallery('task1')">View Screenshots</button>
<a class="btn ghost" href="#">Open Doc</a>
</div>
</div>

<div class="task-card">
<small>Task 2</small>
<h3>Terraform — EC2 Infrastructure</h3>
<p>Launch EC2, open ports 80 & 22, install Docker via user_data.</p>
<div class="actions">
<button class="btn" onclick="scrollToGallery('task2')">View Screenshots</button>
<a class="btn ghost" href="#">Open Doc</a>
</div>
</div>

<div class="task-card">
<small>Task 3</small>
<h3>Docker Compose — Multi-Environment</h3>
<p>Run Nginx static site with optional Watchtower container.</p>
<div class="actions">
<button class="btn" onclick="scrollToGallery('task3')">View Screenshots</button>
<a class="btn ghost" href="#">Open Doc</a>
</div>
</div>

<div class="task-card">
<small>Task 4</small>
<h3>Webhook Integration — GitHub → Jenkins</h3>
<p>Configure webhook to trigger Jenkins job on push to main.</p>
<div class="actions">
<button class="btn" onclick="scrollToGallery('task4')">View Screenshots</button>
<a class="btn ghost" href="#">Open Doc</a>
</div>
</div>

<div class="task-card">
<small>Task 5</small>
<h3>Deploy to EC2</h3>
<p>SSH into EC2, pull Docker image, run container, expose on port 80/8080.</p>
<div class="actions">
<button class="btn" onclick="scrollToGallery('task5')">View Screenshots</button>
<a class="btn ghost" href="#">Open Doc</a>
</div>
</div>

<div class="task-card">
<small>Task 6</small>
<h3>Jenkins Pipeline</h3>
<p>Declarative Jenkinsfile to build Docker image and push to DockerHub.</p>
<div class="actions">
<button class="btn" onclick="scrollToGallery('task6')">View Screenshots</button>
<a class="btn ghost" href="#">Open Doc</a>
</div>
</div>
</section>

<section class="gallery" id="gallery">
<h2>📸 Screenshots Gallery</h2>
<p class="muted">Screenshots grouped by task. Place all files in <code class="kbd">/screenshots/</code></p>
<div id="galleryWrapper"></div>
</section>

<footer>
Built with ❤️ by Ujjawal Rawat • <a href="https://github.com/Ujjawal17-alt" style="color:inherit;opacity:0.85">github.com/Ujjawal17-alt</a>
</footer>
</div>

<script>
const imagesMap={
task1:['task1_ssh.png','task1_inventory.png','task1_playbook.png','task1_dockerps.png','task1_browser.png'],
task2:['task2_init.png','task2_apply.png','task2_ec2.png'],
task3:['task3_compose.png','task3_nginx.png'],
task4:['task4_webhook.png','task4_jenkins.png'],
task5:['task5_pull.png','task5_run.png','task5_web.png'],
task6:['task6_jenkinsfile.png','task6_build.png','task6_dockerhub.png']
};
function createThumb(src, alt){
const div=document.createElement('div'); div.className='thumb';
const img=document.createElement('img'); img.src=src; img.alt=alt;
img.onerror=()=>{img.src='data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="400" height="250"><rect width="100%" height="100%" fill="%23071C2A"/><text x="50%" y="50%" fill="%23fff" font-size="18" font-family="Arial" text-anchor="middle">Image not found</text></svg>'};
div.appendChild(img); return div;
}
function renderGallery(){
const wrap=document.createElement('div'); wrap.className='gallery-grid';
Object.keys(imagesMap).forEach(taskKey=>{imagesMap[taskKey].forEach(fname=>{wrap.appendChild(createThumb('./screenshots/'+fname,fname));});});
document.getElementById('galleryWrapper').innerHTML=''; 
document.getElementById('galleryWrapper').appendChild(wrap);
}
function scrollToGallery(task){document.getElementById('gallery').scrollIntoView({behavior:'smooth', block:'start'});}
renderGallery();
</script>
</body>
</html>
