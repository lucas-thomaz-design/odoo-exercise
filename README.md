# Bootstrap Custom Card Component

This project is a **custom Bootstrap card component** designed with SCSS, featuring navigation tabs, a responsive layout, and interactive elements.

## 🚀 Features
- **Bootstrap 4.3+ based** design.
- **Three tabs** with different functionalities:
  - **Tab 1**: Clickable list items that change an image.
  - **Tab 2**: Animated SVG loading indicator.
  - **Tab 3**: Full-height image display.
- **Custom SCSS styles**, including:
  - Custom **border-radius** and colors.
  - **Disabled tab** styling.
  - **Responsive layout** adjustments.
  - **Gap between navigation tabs**.
  
## 📂 Project Structure
```
/your-project-folder
├── index.html    # Main HTML file
├── styles.scss   # SCSS styles
├── styles.css    # Compiled CSS file
├── images/       # Folder for placeholder images
└── README.md     # This file
```

## 🛠️ Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/bootstrap-card-component.git
   cd bootstrap-card-component
   ```
2. Install dependencies (if needed for SCSS compilation):
   ```sh
   npm install -g sass
   ```
3. Compile SCSS to CSS:
   ```sh
   sass styles.scss styles.css --watch
   ```
4. Open `index.html` in a browser or run a local server:
   ```sh
   npx http-server
   ```

## 🌟 Customization
To modify Bootstrap variables, update `styles.scss` before importing Bootstrap:
```scss
$enable-rounded: false;
@import "bootstrap/scss/bootstrap";
```

## 📜 License
This project is open-source and available under the [MIT License](LICENSE). Feel free to modify and improve it! 🚀
