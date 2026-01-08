# TW-projekt

## Project Overview
This project is a small business website for "Taszarek Wieczorek Projekt sp. z o.o." It includes several pages that provide information about the business, its location, and contact details. The website is designed using Tailwind CSS for modern and responsive styling.

## Project Structure
```
TW-projekt
├── src
│   ├── index.html          # Main HTML page for the business
│   ├── lokalizacja.html    # Location page
│   ├── info.html           # Information page about the business
│   ├── kontakt.html        # Contact information page
│   └── input.css           # Main CSS file for Tailwind CSS
├── assety
│   ├── logo.png            # Logo image for the business
│   └── favikona.png        # Favicon image for the website
├── package.json             # npm configuration file
├── tailwind.config.js       # Tailwind CSS configuration file
├── postcss.config.js        # PostCSS configuration file
└── README.md                # Documentation for the project
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd TW-projekt
   ```

2. **Install Dependencies**
   Make sure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

3. **Build the CSS**
   To generate the CSS file using Tailwind, run:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```

4. **Open the HTML Files**
   You can open the HTML files in your browser to view the website.

## Usage
- The `src/index.html` file serves as the main entry point for the website.
- Each HTML file in the `src` directory is styled using Tailwind CSS classes for a consistent look and feel.
- Custom styles can be added in the `src/input.css` file.

## Contributing
Feel free to submit issues or pull requests for improvements or bug fixes.