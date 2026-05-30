# My Web Browser

A simple web browser application built to provide fast and easy access to websites.

## Features

- Open websites using a URL bar
- Back and Forward navigation
- Refresh page button
- Simple and user-friendly interface
- Lightweight and fast

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/my-web-browser.git
   ```

2. Open the project in your development environment.

3. Build and run the application.

## Usage

1. Launch the application.
2. Enter a website address in the URL bar.
3. Press Enter or click Go.
4. Browse the web.

## Technologies Used

- HTML
- CSS
- JavaScript

## Future Improvements

- Tab support
- Bookmarks
- Download manager
- Dark mode

## Contributing

Contributions are welcome. Feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License.

## Author

adeyi bl
<h2>MyWebsite Browser</h2>

<input type="text" id="search" placeholder="Search or enter URL..." style="width:80%; padding:10px; font-size:16px;">

<button onclick="goSearch()">Go</button>

<script>
function goSearch() {
    let input = document.getElementById("search").value;

    if (input.startsWith("http")) {
        window.location.href = input;
    } else {
        window.location.href = "https://www.google.com/search?q=" + input;
    }
}
</script>
<body style="margin:0; font-family:Arial, sans-serif; background:linear-gradient(135deg,#0f2027,#203a43,#2c5364); color:white;">

<div style="text-align:center; padding:40px;">

    <h1 style="font-size:40px; margin-bottom:10px;">⚡ MyWebsite Browser</h1>
    <p style="opacity:0.8;">A next-generation browsing experience</p>

    <div style="margin-top:40px;">

        <input id="searchBox" 
            placeholder="Search or enter website URL..." 
            style="width:70%; padding:15px; font-size:18px; border:none; border-radius:30px; outline:none;">

        <button onclick="go()" 
            style="padding:15px 25px; font-size:18px; border:none; border-radius:30px; margin-left:10px; cursor:pointer; background:#00c6ff; color:white;">
            Search
        </button>

    </div>

</div>

<script>
function go() {
    let input = document.getElementById("searchBox").value;

    if (input.startsWith("http")) {
        window.location.href = input;
    } else {
        window.location.href = "https://www.google.com/search?q=" + input;
    }
}
</script>

</body>
<body style="margin:0; font-family:Arial; background:#0b0f19; color:white;">

<!-- TOP BAR -->
<div style="display:flex; justify-content:space-between; align-items:center; padding:15px 20px; background:#111827;">

    <div style="font-size:20px; font-weight:bold;">
        🔷 Deeblaq Browser Hub
    </div>

    <!-- Rectangle Profile -->
    <div style="width:45px; height:45px; background:#00c6ff; border-radius:8px;"></div>

</div>

<!-- SEARCH SECTION -->
<div style="text-align:center; padding:60px 20px;">

    <h1>Welcome to Deeblaq Search</h1>

    <input id="searchBox" 
        placeholder="Search with Deeblaq..." 
        style="width:70%; padding:15px; font-size:18px; border-radius:10px; border:none;">

    <button onclick="search()" 
        style="padding:15px 25px; margin-left:10px; border:none; border-radius:10px; background:#00c6ff; color:white;">
        Search
    </button>

</div>

<!-- DOWNLOAD SECTION -->
<div style="padding:30px;">

    <h2>🎮 Download Games & Files</h2>

    <div style="display:flex; gap:20px; flex-wrap:wrap;">

        <a href="game1.zip" download 
           style="padding:15px; background:#1f2937; border-radius:10px; text-decoration:none; color:white;">
           Download Game 1
        </a>

        <a href="game2.zip" download 
           style="padding:15px; background:#1f2937; border-radius:10px; text-decoration:none; color:white;">
           Download Game 2
        </a>

        <a href="app.apk" download 
           style="padding:15px; background:#1f2937; border-radius:10px; text-decoration:none; color:white;">
           Download App
        </a>

    </div>

</div>

<script>
function search() {
    let input = document.getElementById("searchBox").value;

    // Deeblaq search (not Google branding)
    if (input.startsWith("http")) {
        window.location.href = input;
    } else {
        window.location.href = "https://www.google.com/search?q=" + input;
    }
}
</script>

</body>
<body style="margin:0; font-family:Arial; background:#0b0f19; color:white;">

<!-- TOP BAR -->
<div style="display:flex; justify-content:space-between; align-items:center; padding:15px; background:#111827; position:sticky; top:0;">

    <div style="font-weight:bold;">🔷 Deeblaq Hub</div>

    <div style="width:40px; height:40px; background:#00c6ff; border-radius:8px;"></div>

</div>

<!-- SEARCH BAR AT TOP -->
<div style="text-align:center; padding:20px; background:#0b0f19;">

    <input id="searchBox"
        placeholder="Search Deeblaq..."
        style="width:70%; padding:12px; border-radius:10px; border:none; font-size:16px;">

    <button onclick="search()"
        style="padding:12px 20px; border:none; border-radius:10px; background:#00c6ff; color:white;">
        Search
    </button>

</div>

<!-- CONTENT -->
<div style="padding:30px;">
    <h2>Welcome to Deeblaq Hub</h2>
    <p>Download games, apps and browse the web easily.</p>
</div>

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
<title>Deeblaq Hub - Download Games & Search Web</title>

<meta name="description" content="Deeblaq Hub lets you search the web and download games, apps, and files easily.">

<meta name="keywords" content="deeblaq, download games, browser, github pages, free games download">

</body>
<body style="margin:0; font-family:Arial; background:#0b0f19; color:white;">

<!-- TOP BAR -->
<div style="display:flex; justify-content:space-between; align-items:center; padding:15px; background:#111827; position:sticky; top:0;">

    <div style="font-weight:bold;">🔷 Deeblaq Hub</div>

    <div style="width:40px; height:40px; background:#00c6ff; border-radius:8px;"></div>

</div>

<!-- SEARCH BAR AT TOP -->
<div style="text-align:center; padding:20px; background:#0b0f19;">

    <input id="searchBox"
        placeholder="Search Deeblaq..."
        style="width:70%; padding:12px; border-radius:10px; border:none; font-size:16px;">

    <button onclick="search()"
        style="padding:12px 20px; border:none; border-radius:10px; background:#00c6ff; color:white;">
        Search
    </button>

</div>

<!-- CONTENT -->
<div style="padding:30px;">
    <h2>Welcome to Deeblaq Hub</h2>
    <p>Download games, apps and browse the web easily.</p>
</div>

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
