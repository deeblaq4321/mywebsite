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
        </a>

    </div>

</div>

<!-- SCRIPT -->
<script>
function search() {
    let input = document.getElementById("searchBox").value;

    if (input.startsWith("http")) {
        window.location.href = input;
    } else {
        window.location.href = "https://www.google.com/search?q=" + input;
    }
}
</script>

</body>
</html>
<!-- Website Header -->
<header>
    <div class="logo">Deeblaq</div>
    <div class="profile"></div>
</header>

<!-- Main Search Section -->
<div class="container">
    <h1>Search the Web</h1>

    <!-- Search Form -->
    <form action="https://www.google.com/search" method="GET">
        <input type="text" name="q" class="search-box"
        placeholder="Search anything...">

        <button class="search-btn">Search</button>
    </form>
</div>

<!-- Downloads Section -->
<div class="downloads">
    <h2>Downloads</h2>

    <!-- Games Card -->
    <div class="card">
        <h3>Games</h3>
        <p>Download your favorite games.</p>
    </div>

    <!-- Apps Card -->
    <div class="card">
        <h3>Apps</h3>
        <p>Download useful applications.</p>
    </div>
</div>

<!-- End of Website -->
