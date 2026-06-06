---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: documentation
assignees: ''

---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Deeblaq Browser</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f7fa;
}

header{
    background:#111827;
    color:white;
    padding:15px 30px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.hero{
    text-align:center;
    padding:80px 20px;
}

.hero h1{
    font-size:50px;
    margin-bottom:15px;
}

.hero p{
    font-size:18px;
    color:#555;
    margin-bottom:30px;
}

.search-box{
    max-width:700px;
    margin:auto;
    display:flex;
}

.search-box input{
    flex:1;
    padding:15px;
    border:2px solid #ddd;
    border-radius:30px 0 0 30px;
    outline:none;
    font-size:16px;
}

.search-box button{
    padding:15px 30px;
    border:none;
    background:#2563eb;
    color:white;
    border-radius:0 30px 30px 0;
    cursor:pointer;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    padding:50px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.card h3{
    margin-bottom:10px;
}

.profile{
    width:45px;
    height:45px;
    background:white;
    color:#111827;
    border-radius:10px;
    display:flex;
    justify-content:center;
    align-items:center;
    font-weight:bold;
}

footer{
    background:#111827;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}
</style>
</head>

<body>

<header>
    <div class="logo">DEEBLAQ</div>

    <nav>
        <a href="#">Home</a>
        <a href="#">Search</a>
        <a href="#">Games</a>
        <a href="#">Downloads</a>
        <a href="#">About</a>
    </nav>

    <div class="profile">DB</div>
</header>

<section class="hero">
    <h1>Welcome to Deeblaq</h1>
    <p>Search, Browse, Discover and Download Content Easily.</p>

    <div class="search-box">
        <input type="text" id="searchInput" placeholder="Search the web...">
        <button onclick="searchWeb()">Search</button>
    </div>
</section>

<section class="features">

    <div class="card">
        <h3>Fast Search</h3>
        <p>Find information quickly with Deeblaq Search.</p>
    </div>

    <div class="card">
        <h3>Downloads</h3>
        <p>Download games, apps, and resources.</p>
    </div>

    <div class="card">
        <h3>Modern Design</h3>
        <p>Clean and responsive layout for all devices.</p>
    </div>

</section>

<footer>
    <p>© 2026 Deeblaq. Created by Ayodele Blessing.</p>
</footer>

<script>
function searchWeb(){
    let query = document.getElementById("searchInput").value;

    if(query !== ""){
        window.open(
          "https://www.google.com/search?q=" + encodeURIComponent(query),
          "_blank"
        );
    }
}
</script>

</body>
</html>
