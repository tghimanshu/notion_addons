# Notion Addons

A collection of HTML and CSS based add-ons, primarily designed for embedding in Notion or acting as standalone simple web pages.

## Project Overview

This repository contains lightweight web components. The primary feature currently is a "Beating Heart" animation that doubles as a day counter.

### Key Components

*   **`beating_heart.html`**: A standalone HTML file featuring a CSS-animated beating heart. It includes a JavaScript-based counter that displays the number of days passed since a specific start date (December 27, 2021).
*   **`index.html`**: A basic landing page/placeholder.

## Getting Started

### Prerequisites

*   A modern web browser (Chrome, Firefox, Safari, Edge).

### Installation

No installation is required. These are static HTML files.

1.  Clone the repository:
    ```bash
    git clone https://github.com/yourusername/notion_addons.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd notion_addons
    ```

### Usage

#### Local Testing
Simply open the HTML files in your browser.
*   **Mac/Linux**: `open beating_heart.html`
*   **Windows**: `start beating_heart.html`

#### Embedding in Notion
To use these as Notion widgets:
1.  Host the HTML file (e.g., using GitHub Pages, Vercel, or Netlify).
2.  Copy the URL of the hosted page.
3.  In Notion, type `/embed` and paste the URL.

## Documentation

The source code is fully documented with comments explaining the purpose of CSS animations and JavaScript logic.
-   **CSS**: Explains keyframes for animations (`beat`, `justBeat`) and class usages.
-   **JavaScript**: Explains the date calculation logic.

## Future Plans

See [FUTURE_PLAN.md](FUTURE_PLAN.md) for details on the roadmap and upcoming features.
