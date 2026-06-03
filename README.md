<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Deeblaq Hub - Search & Downloads</title>

    <meta name="description" content="Deeblaq Hub is a fast platform to search the web and download games, apps, and files easily.">
    <meta name="keywords" content="deeblaq, download games, browser, search engine, github pages">

</head>

<body style="margin:0; font-family:Arial; background:#0b0f19; color:white;">

<!-- TOP BAR -->
<div style="display:flex; justify-content:space-between; align-items:center; padding:15px; background:#111827; position:sticky; top:0;">

    <div style="font-weight:bold; font-size:18px;">
        🔷 Deeblaq Hub
    </div>

    <!-- Rectangle Profile -->
    <div style="width:40px; height:40px; background:#00c6ff; border-radius:8px;"></div>

</div>

<!-- SINGLE SEARCH BAR -->
<div style="text-align:center; padding:50px 20px;">

    <h2>Search Deeblaq Hub</h2>

    <input id="searchBox"
        placeholder="Search or enter website..."
        style="width:70%; padding:15px; border-radius:10px; border:none; font-size:16px; outline:none;">

    <br><br>

    <button onclick="search()"
        style="padding:12px 25px; border:none; border-radius:10px; background:#00c6ff; color:white; font-size:16px;">
        Search
    </button>

</div>

<!-- DOWNLOAD SECTION -->
<div style="padding:30px;">

    <h2>🎮 Download Games & Apps</h2>

    <div style="display:flex; gap:15px; flex-wrap:wrap; margin-top:20px;">

        <a href="game1.zip" download
           style="padding:15px; background:#1f2937; border-radius:10px; color:white; text-decoration:none;">
           Download Game 1
        </a>

        <a href="game2.zip" download
           style="padding:15px; background:#1f2937; border-radius:10px; color:white; text-decoration:none;">
           Download Game 2
        </a>

        <a href="app.apk" download
           style="padding:15px; background:#1f2937; border-radius:10px; color:white; text-decoration:none;">
           Download App
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Deeblaq Search</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f8f9fa;
    min-height:100vh;
}

header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 40px;
}

.logo{
    font-size:32px;
    font-weight:bold;
    color:#1a73e8;
}

.profile{
    width:50px;
    height:50px;
    border-radius:12px;
    background:#1a73e8;
}

.main{
    text-align:center;
    margin-top:120px;
}

.main h1{
    font-size:60px;
    color:#1a73e8;
    margin-bottom:30px;
}

.search-form{
    display:flex;
    justify-content:center;
    gap:10px;
}

.search-box{
    width:60%;
    max-width:700px;
    padding:18px;
    border:1px solid #ddd;
    border-radius:50px;
    font-size:18px;
}

.search-btn{
    padding:18px 30px;
    border:none;
    border-radius:50px;
    background:#1a73e8;
    color:white;
    cursor:pointer;
    font-size:16px;
}

.search-btn:hover{
    background:#1557b0;
}

.features{
    margin-top:80px;
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
}

.card{
    background:white;
    width:250px;
    padding:20px;
    border-radius:15px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

footer{
    text-align:center;
    margin-top:60px;
    padding:20px;
    color:#666;
}
</style>
</head>

<body>

<header>
    <div class="logo">Deeblaq</div>
    <div class="profile"></div>
</header>

<section class="main">
    <h1>Deeblaq Search</h1>

    <form class="search-form"
          action="https://www.google.com/search"
          method="GET">
        <input type="text"
               name="q"
               class="search-box"
               placeholder="Search the web...">

        <button type="submit"
                class="search-btn">
                Search
        </button>
    </form>
</section>

<section class="features">

    <div class="card">
        <h3>Web Search</h3>
        <p>Search the internet quickly and easily.</p>
    </div>

    <div class="card">
        <h3>Downloads</h3>
        <p>Download games, apps, and useful files.</p>
    </div>

    <div class="card">
        <h3>Fast Access</h3>
        <p>Open your favorite websites in one click.</p>
    </div>

</section>

<footer>
    © 2026 Deeblaq Search. All Rights Reserved.
</footer>

</body>
</html>
```
