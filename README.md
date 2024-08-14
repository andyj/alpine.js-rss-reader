# Alpine.js RSS Reader

A simple RSS feed reader application using Alpine.js. This app fetches and displays posts from a BlueSky user feed, presenting them in a card layout using Bootstrap.

## Features

- Fetches and displays RSS feed data from BlueSky.
- Uses Alpine.js for interactivity and state management.
- Utilises Bootstrap for responsive styling and layout.
- Uniform card height to ensure a clean and consistent look.

## Live Demo

You can view a live demo at [https://andyj.github.io/alpine.js-rss-reader/](https://andyj.github.io/alpine.js-rss-reader/).

## Installation

To run this application locally, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/andyj/alpine.js-rss-reader.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd alpine.js-rss-reader
   ```

3. **Open the HTML File**

   Open `index.html` in your preferred web browser.

## How It Works

1. **Fetch RSS Feed:**
   The application fetches the RSS feed from BlueSky using a proxy service called [allorigins.win](https://allorigins.win) to bypass any CORS restrictions.

2. **Parse XML:**
   The fetched RSS feed is parsed using the `DOMParser` API to extract relevant data.

3. **Display Feed Items:**
   Feed items are displayed in a Bootstrap 5 grid 

## Dependencies (CDN's)

- [Alpine.js](https://alpinejs.dev/) 
- [Bootstrap](https://getbootstrap.com/)
- [All Origins](https://allorigins.win/)

## Code Overview

- **HTML:** Contains the structure and layout of the application, including Bootstrap classes for styling and Alpine.js directives for interactivity.
- **CSS:** Provides custom styles to ensure uniform card heights and layout consistency.
- **JavaScript:** Handles fetching, parsing, and displaying RSS feed data using Alpine.js.

## Customisation

To customise the feed URL or adjust the layout, modify the following sections:

- **Feed URL:** Change the URL in the `fetchFeed()` function inside the `<script>` tag in `index.html`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

For any issues or feature requests, please open an issue on the [GitHub repository](https://github.com/andyj/alpine.js-rss-reader/issues).

## License

This project is licensed under the [MIT License](https://andyj.github.io/alpine.js-rss-reader/Licence).

## Contact

If you have any questions leave a message through [Github issues](https://github.com/andyj/alpine.js-rss-reader/issues)

