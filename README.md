Color Palette Generator

A simple and interactive web application that generates random color palettes and allows users to copy hex codes with a single click.

🚀 Features
🎲 Generate random color palettes
📋 Click to copy hex codes to clipboard
✅ Visual feedback when copying (icon changes)
🎯 Click on either:
Copy button
Color box
💻 Fully responsive design
🛠️ Tech Stack
HTML5
CSS3 (Flexbox + Grid)
JavaScript (Vanilla JS)
Font Awesome Icons
📂 Project Structure
├── index.html     # Main HTML structure
├── styles.css     # Styling and layout
├── script.js      # Functionality and logic
⚙️ How It Works
1. Generate Palette
Clicking "Generate Palette" button:
Calls generatePalette()
Creates 5 random hex colors
Updates UI using updatePaletteDisplay()
2. Random Color Logic
function generateRandomColor()
Generates a hex color like #A1B2C3
Uses characters: 0-9 and A-F
3. Update UI
function updatePaletteDisplay(colors)
Loops through all .color-box
Updates:
Background color
Hex text value
4. Copy to Clipboard
Uses:
navigator.clipboard.writeText()
Supports:
Clicking copy icon
Clicking color block
5. Copy Feedback
function showCopySuccess(copyBtn)
Changes icon:
📋 → ✔️
Temporarily changes color
Reverts after 1.5 seconds
📸 UI Overview
5 color boxes displayed in a grid
Each box contains:
Color preview
Hex value
Copy button
🧪 How to Run
Download or clone the project
Open index.html in your browser

No build tools required ✅

📌 Future Improvements
🎯 Add color locking
🎨 Export palette (PNG / JSON)
🌙 Dark mode
📱 Save favorite palettes
🎛️ Adjust palette type (pastel, vibrant, etc.)
💡 Learning Highlights

This project helps you understand:

DOM manipulation
Event delegation
Clipboard API
Dynamic UI updates
Clean component structure
🙌 Author

Prabu M
