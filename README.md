# Project Readme - Dynamic Quote Generator with Svelte

## Overview

This project is a dynamic quote generator web page built using Svelte, HTML, CSS, and JavaScript. It fetches random quotes from the [Quotable](https://api.quotable.io/) API, featuring a visually appealing background with a dynamically changing color, an animated noise effect, and custom font styling. Svelte is employed for a reactive and efficient front-end development experience.

## Features

1. **Dynamic Quote Display:**
   - The page fetches a random quote from the Quotable API and updates the displayed quote in real-time.

2. **Colorful Background:**
   - The background color of the page changes dynamically on each visit, creating a visually appealing atmosphere.

3. **Animated Noise Effect:**
   - An SVG element with a fractal noise filter produces an animated noise effect, enhancing the overall aesthetic of the page.

4. **Svelte Framework:**
   - Svelte is used for building reactive components and managing the dynamic behavior of the web page.

## Technologies Used

- **Svelte:** A reactive front-end framework for building efficient and dynamic web applications.
- **HTML:** The backbone of the web page structure.
- **CSS:** Inline styles are used for styling, and a custom font (Playfair Display) is imported.
- **JavaScript (Svelte):** The logic for fetching quotes, updating the background color, and managing dynamic content is implemented using Svelte components.
- **Quotable API:** A third-party API used to retrieve random quotes.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Install dependencies:

    ```bash
    cd <project-directory>
    npm install
    ```

3. Start the development server:

    ```bash
    npm run dev
    ```

4. Open your web browser and navigate to the provided local server URL.

## Project Structure

- **`src/App.svelte`:** The main Svelte component containing the structure and behavior of the web page.
- **`public/index.html`:** The entry HTML file.
- **`public/global.css`:** Global CSS styles.
- **`public/favicon.png`:** Project favicon.

## Customize

Feel free to customize the project:

- Change the Svelte components in the `src` directory to add or modify features.
- Adjust styles and behavior within the Svelte components and stylesheets.

## Credits

- **Quotable API:** [Quotable](https://api.quotable.io/) - Providing a diverse collection of quotes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute, suggest improvements, or use this project as a foundation for your creative web experiments with Svelte!
