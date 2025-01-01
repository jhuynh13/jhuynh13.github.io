# Portfolio Website

This is a simple portfolio website built using HTML, CSS, and Tailwind CSS. It showcases projects and skills in a clean and responsive layout.

## Project Structure

```
portfolio-website
├── src
│   ├── index.html        # Main HTML document for the portfolio site
│   ├── styles
│   │   └── tailwind.css  # Tailwind CSS styles
│   └── scripts
│       └── main.js       # JavaScript for interactivity
├── tailwind.config.js    # Tailwind CSS configuration
├── package.json          # npm configuration
└── README.md             # Project documentation
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd portfolio-website
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Build the Tailwind CSS:
   ```
   npx tailwindcss -i ./src/styles/tailwind.css -o ./dist/styles.css --watch
   ```

4. Open `src/index.html` in your browser to view the portfolio.

## Features

- Responsive design using Tailwind CSS
- Interactive elements powered by JavaScript
- Easy customization through Tailwind configuration

## Usage Guidelines

- Modify `src/index.html` to update the content of the portfolio.
- Customize styles in `src/styles/tailwind.css` as needed.
- Add any additional JavaScript functionality in `src/scripts/main.js`. 

## License

This project is open-source and available under the MIT License.