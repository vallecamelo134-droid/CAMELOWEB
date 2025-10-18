:root{ --bg:#0b0b0b; --muted:#9a9a9a; --accent:#ffffff }
*{box-sizing:border-box}
body{margin:0;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;background:var(--bg);color:var(--accent);line-height:1.6}
.container{max-width:1100px;margin:0 auto;padding:36px}
.site-header{border-bottom:1px solid rgba(255,255,255,0.05);position:sticky;top:0;background:transparent}
.logo{margin:0;font-size:20px}
.nav{display:flex;gap:20px}
.nav a{color:var(--muted);text-decoration:none}
.hero{padding:60px 0}
.hero-inner{display:flex;gap:40px;align-items:center}
.hero-text h2{font-size:32px;margin:0 0 12px}
.hero-text p{color:var(--muted);max-width:520px}
.btn{display:inline-block;margin-top:18px;padding:10px 16px;border:1px solid rgba(255,255,255,0.12);text-decoration:none}
.hero-image img{width:260px;height:260px;object-fit:cover;border-radius:8px;border:1px solid rgba(255,255,255,0.06)}
.section{padding:48px 0}
.section h3{font-size:20px;margin:0 0 14px}
.projects-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.project-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:12px;border-radius:8px}
.project-card img{width:100%;height:160px;object-fit:cover;border-radius:6px}
.project-content h4{margin:10px 0 6px}
.project-content p{color:var(--muted);font-size:14px}
.project-link{color:var(--accent);text-decoration:underline;font-size:14px}
.site-footer{padding:24px 0;border-top:1px solid rgba(255,255,255,0.03);text-align:center;color:var(--muted)}


/* Responsive */
@media(max-width:900px){.projects-grid{grid-template-columns:repeat(2,1fr)}.hero-inner{flex-direction:column-reverse;text-align:center}.hero-image img{width:180px;height:180px}}
@media(max-width:560px){.projects-grid{grid-template-columns:1fr}.nav{display:none}.container{padding:20px}}
