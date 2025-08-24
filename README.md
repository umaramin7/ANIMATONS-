Key Press Detector 🎹
A simple and elegant web application that displays the key you press on your keyboard in real-time.
🌟 Features

Real-time Key Detection: Displays any key pressed on the keyboard instantly
Clean Minimal Design: Dark theme with centered typography
Special Key Handling: Shows "SPC" for spacebar presses
Responsive Layout: Works on all screen sizes
No Dependencies: Pure HTML, CSS, and JavaScript

🚀 Demo
Simply open the application and start typing - the large letter in the center will change to whatever key you press!
📁 Project Structure
key-press-detector/
├── index.html          # Main HTML file
├── ls.css             # Stylesheet
├── index.js           # JavaScript functionality
└── README.md          # Project documentation
🛠️ Installation

Clone the repository
bashgit clone https://github.com/umaramin7/key-press-detector.git

Navigate to project directory
bashcd key-press-detector

Open in browser
bash# Simply open index.html in your preferred browser
# Or use Live Server extension in VS Code


💻 Usage

Open index.html in any modern web browser
Click anywhere on the page to ensure it's focused
Press any key on your keyboard
Watch as the display updates to show your keypress!

Special Keys:

Spacebar displays as "SPC"
All other keys show their actual character/name

🎨 Customization
Changing Colors
Edit the CSS variables in ls.css:
css#main {
    background-color: #222; /* Dark background */
}

h1 {
    color: #555; /* Text color */
}
Changing Font Size
Modify the font-size in ls.css:
cssh1 {
    font-size: 5rem; /* Adjust as needed */
}
🔧 Technical Details

HTML5 for structure
CSS3 with Flexbox for styling and layout
Vanilla JavaScript for keyboard event handling
Gilroy Font Family (falls back to system fonts)

🤝 Contributing

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📝 License
This project is open source and available under the MIT License.
🐛 Known Issues

Gilroy font may not load on all systems (graceful fallback included)
Some special keys might display system-specific names

🔮 Future Enhancements

 Key press animation effects
 Sound effects for key presses
 Key press history/log
 Customizable themes
 Mobile touch support

📞 Contact
Your Name - Umar - umaramin78894@gmail.com
Project Link: https://github.com/umaramin7/key-press-detector

⭐ Don't forget to star this repo if you found it helpful!
