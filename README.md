# New-code
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Apurba Dev Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#0f172a;
    color:#fff;
    display:flex;
}

/* Sidebar */
.sidebar{
    width:250px;
    background:#111827;
    height:100vh;
    padding:20px;
    position:fixed;
}

.sidebar h2{
    color:#a855f7;
    margin-bottom:20px;
}

.sidebar ul{
    list-style:none;
}

.sidebar ul li{
    padding:12px;
    margin:8px 0;
    background:#1f2937;
    border-radius:8px;
    cursor:pointer;
}

.sidebar ul li:hover{
    background:#a855f7;
}

/* Main */
.main{
    margin-left:250px;
    padding:20px;
    width:100%;
}

/* Profile Card */
.profile{
    display:flex;
    justify-content:space-between;
    background:#1f2937;
    padding:20px;
    border-radius:15px;
}

.profile img{
    width:100px;
    height:100px;
    border-radius:50%;
}

.profile h1{
    font-size:24px;
}

.btn{
    padding:10px 15px;
    background:#a855f7;
    border:none;
    color:#fff;
    border-radius:8px;
    cursor:pointer;
}

/* Cards */
.cards{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:15px;
    margin-top:20px;
}

.card{
    background:#1f2937;
    padding:15px;
    border-radius:12px;
}

/* Skills */
.skill-bar{
    margin:10px 0;
}

.bar{
    height:8px;
    background:#374151;
    border-radius:10px;
    overflow:hidden;
}

.fill{
    height:8px;
    background:#a855f7;
}

/* Projects */
.projects{
    margin-top:20px;
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:15px;
}

.project{
    background:#1f2937;
    padding:10px;
    border-radius:10px;
}

.project img{
    width:100%;
    border-radius:10px;
}

/* Right panel */
.right{
    position:fixed;
    right:0;
    top:0;
    width:250px;
    height:100vh;
    background:#111827;
    padding:20px;
}

</style>
</head>

<body>

<!-- Sidebar -->
<div class="sidebar">
<h2>My Profile</h2>
<ul>
<li>Dashboard</li>
<li>About</li>
<li>Skills</li>
<li>Projects</li>
<li>Experience</li>
<li>Contact</li>
</ul>
</div>

<!-- Main Content -->
<div class="main">

<div class="profile">
    <div>
        <h1>Apurba Dev</h1>
        <p>Web Developer</p>
        <p>Dhaka, Bangladesh</p>
        <button class="btn">Edit Profile</button>
    </div>
    <img src="https://i.ibb.co/7Wf8q4Q/user.jpg" alt="profile">
</div>

<!-- Cards -->
<div class="cards">
    <div class="card">Projects: 12</div>
    <div class="card">Experience: 2+</div>
    <div class="card">Certificates: 6</div>
</div>

<!-- About -->
<div class="card" style="margin-top:20px;">
<h3>About Me</h3>
<p>I am a web developer who builds modern websites.</p>
</div>

<!-- Skills -->
<div class="card" style="margin-top:20px;">
<h3>Skills</h3>

<div class="skill-bar">HTML
<div class="bar"><div class="fill" style="width:95%"></div></div>
</div>

<div class="skill-bar">CSS
<div class="bar"><div class="fill" style="width:90%"></div></div>
</div>

<div class="skill-bar">JavaScript
<div class="bar"><div class="fill" style="width:80%"></div></div>
</div>

</div>

<!-- Projects -->
<h3 style="margin-top:20px;">Projects</h3>
<div class="projects">

<div class="project">
<img src="https://via.placeholder.com/300">
<p>Portfolio Website</p>
</div>

<div class="project">
<img src="https://via.placeholder.com/300">
<p>E-Commerce</p>
</div>

<div class="project">
<img src="https://via.placeholder.com/300">
<p>Admin Dashboard</p>
</div>

</div>

</div>

<!-- Right Panel -->
<div class="right">
<h3>Quick Info</h3>
<p>Contact: apurba@email.com</p>
<p>Phone: +880...</p>
</div>

</body>
</html>
