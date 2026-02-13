/* Basic Reset */

/* Container */
.container { width:90%; max-width:1200px; margin:0 auto; }

/* Header */
header { background:#fff; position:sticky; top:0; box-shadow:0 2px 8px rgba(0,0,0,0.05); z-index:1000; }
header .container { display:flex; justify-content:space-between; align-items:center; padding:15px 0; }
header h1 { color:#0f172a; }
header nav a { text-decoration:none; margin-left:20px; color:#334155; font-weight:500; transition:0.3s; }
header nav a:hover { color:#2563eb; }

/* Hero */
.hero { text-align:center; padding:80px 0; background:linear-gradient(to right, #e0f2fe, #ffffff); }
.hero img { width:160px; border-radius:50%; margin-bottom:20px; }
.hero h2 { font-size:42px; margin-bottom:10px; }
.hero h2 span { color:#2563eb; }
.hero p { font-size:20px; margin-bottom:25px; }
.btn { padding:12px 30px; background:#2563eb; color:white; text-decoration:none; border-radius:5px; transition:0.3s; }
.btn:hover { background:#1e40af; }

/* Sections */
section { padding:60px 0; opacity:0; transform:translateY(40px); transition:all 1s ease; }
section.show { opacity:1; transform:translateY(0); }
section h3 { font-size:32px; margin-bottom:25px; color:#0f172a; text-align:center; }
section p { max-width:800px; margin:0 auto 20px auto; text-align:center; }

/* Skills Grid */
.skills-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(150px,1fr)); gap:20px; margin-top:30px; }
.skill { background:white; padding:20px; border-radius:8px; box-shadow:0 5px 15px rgba(0,0,0,0.05); text-align:center; transition:0.3s; }
.skill:hover { transform:translateY(-5px); }

/* Stats */
.stats-grid { display:flex; justify-content:space-around; flex-wrap:wrap; margin-top:30px; }
.stat { background:white; padding:30px; border-radius:10px; width:200px; margin:10px; box-shadow:0 5px 15px rgba(0,0,0,0.05); }
.stat .count { font-size:36px; color:#2563eb; display:block; margin-bottom:5px; }

/* Contact */
#contact form { display:flex; flex-direction:column; max-width:500px; margin:0 auto; }
#contact input, #contact textarea { padding:10px; margin-bottom:15px; border:1px solid #ccc; border-radius:5px; }
#contact button { padding:12px; background:#2563eb; color:white; border:none; border-radius:5px; cursor:pointer; transition:0.3s; }
#contact button:hover { background:#1e40af; }

/* Footer */
footer { text-align:center; background:#0f172a; color:white; padding:25px 0; }
footer a { color:#fff; text-decoration:none; margin:0 10px; }
footer a:hover { color:#2563eb; }

/* Responsive */
@media(max-width:768px){
  .hero h2 { font-size:32px; }
  .stats-grid { flex-direction:column; align-items:center; }
}# Web-page
