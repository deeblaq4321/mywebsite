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
