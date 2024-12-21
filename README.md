# Counter Program

A simple and interactive counter application built with HTML, CSS, and JavaScript. This project allows users to increase, decrease, or reset a counter with intuitive buttons.

## How It Works

The application consists of a counter label and three buttons for controlling the counter value:

- **Decrease button**: Decrements the counter by one.
- **Reset button**: Resets the counter to zero.
- **Increase button**: Increments the counter by one.

## Features

- **Semantic HTML5**: The project uses clean, semantic HTML for better accessibility and SEO.
- **Modern CSS**:
  - Utilizes **`@layer`** for modular and organized styling.
  - Leverages the **`light-dark()`** function for automatic color adjustments based on user preference.
  - Implements a **modern wrapper approach** for a responsive, flexible layout.
- **Accessibility-oriented**:
  - Full **dark mode support** that follows the system's color scheme preference.
  - **Keyboard Navigation**: The buttons are fully accessible via keyboard for users relying on keyboard navigation.

## Technologies Used

- **Vanilla HTML**: For structuring the content.
- **Vanilla CSS**: For styling the content.
- **Vanilla JavaScript**: For implementing the counter logic.
- **Open Props**: A library for better theming, providing predefined design tokens like colors, sizes, and spacing.
- **Vite**: Frontend tooling used for development and build optimization.

## Installation

To run the project locally, follow the instructions below:

### Prerequisites

Ensure that you have the following installed:

- Node.js (>= 18.0.0)
- npm (>= 10.0.0)

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yoursgaurav/counter-program.git
   cd counter-program
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Run the development server**:

   ```bash
   npm run dev
   ```

   This will start the Vite development server. You can open your browser and navigate to `http://localhost:5173` to see the counter in action.

   Optionally, you can add the `--host` flag to expose the Vite project to the network.

## Project Structure

```
counter-program/
├── public/
│   ├── screenshots/         # Directory to store screenshots (light and dark mode)
│   │   ├── dark-mode.png    # Screenshot for dark mode
│   │   └── light-mode.png   # Screenshot for light mode
│   └── vite.svg             # Vite logo being used for favicon
├── src/
│   ├── main.js              # JavaScript file containing the counter logic
│   └── style.css            # CSS file with styling and design
├── .gitignore               # Gitignore file to exclude unnecessary files from version control
├── index.html               # Main HTML file for the app
├── package-lock.json        # Dependency lock file for npm
├── package.json             # Project dependencies and scripts
├── README.md                # This README file
```

## Screenshots

### Light Mode Version:

![Counter Program Screenshot (light mode)](/public/screenshots/light-mode.png)

### Dark Mode Version:

![Counter Program Screenshot (dark mode)](/public/screenshots/dark-mode.png)

_An example of the interactive counter in action._

## Contributing

Feel free to fork this project, submit issues, and make pull requests. Contributions are welcome!
