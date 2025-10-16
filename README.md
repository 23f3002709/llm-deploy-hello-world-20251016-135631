# Hello World · Bootstrap 5 Single-Page App

A minimal, production-ready single-page web application that displays "Hello World" using Bootstrap 5. This project is designed for static hosting (e.g., GitHub Pages) and includes clean, accessible markup, inline CSS/JS, and graceful error handling.

## Features
- Bootstrap 5 UI via CDN (no build step required)
- Single-file app: semantic HTML with inline CSS and JavaScript
- h1 heading with `id="greeting"` set to `Hello World`
- Data URI asset embedded as a JavaScript constant (no external image requests)
- Responsive, accessible layout with a simple navbar and cards
- Copy-to-clipboard functionality with fallback for older browsers
- Works entirely offline after first load (aside from CDN assets)

## Quick Start
- Download or clone the repository
- Open `index.html` directly in your browser

No additional setup is required.

## Usage
- Visit the page and verify the large heading reads "Hello World".
- Click "Copy greeting" to copy the heading text to your clipboard.
- Scroll to the About section to see an embedded logo served via data URI.

## Technical Overview
- Libraries: [Bootstrap 5.3](https://getbootstrap.com/) via CDN for styles and the JS bundle (Popper included).
- Structure: A single HTML file (`index.html`) containing:
  - `<link>` tag for Bootstrap CSS from a CDN
  - Inline `<style>` for custom styles
  - Inline `<script>` with initialization logic and error handling
  - A data URI constant for an inline SVG logo
- No frameworks, bundlers, or backend services required

### Why inline CSS and JS?
Keeping custom CSS and JS inline simplifies the project and ensures compatibility with static hosting platforms like GitHub Pages while remaining easy to audit.

## Deployment
- This project is static and can be hosted on any static hosting platform.
- For GitHub Pages, push the files to a repository and enable Pages.
- To run locally, simply open `index.html` in your browser.

## Browser Support
- Modern evergreen browsers (Chrome, Edge, Firefox, Safari)
- Degrades gracefully where some APIs (e.g., Clipboard) are unavailable

## Project Structure
- `index.html` — The entire application (HTML, inline CSS, inline JS)
- `README.md` — This documentation
- `.gitignore` — Common web project, IDE, and OS ignores

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file if provided, or the text below:

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
