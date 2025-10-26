# Calculator-GUI

Android-Style Calculator with 3D Math Graph
A beautiful Android/Samsung-style calculator with interactive 3D mathematical graph visualization built using Three.js. Features a responsive design and smooth animations.

https://img.shields.io/badge/Calculator-Android--Style-blue https://img.shields.io/badge/3D-Math%2520Graph-orange https://img.shields.io/badge/Deployed-Vercel-brightgreen

✨ Features
Android/Samsung-Inspired UI: Modern dark theme with blue accents

3D Math Graph Visualization: Interactive mathematical functions rendered with Three.js

Responsive Design: Works perfectly on desktop and mobile devices

Keyboard Support: Full keyboard input compatibility

Smooth Animations: Beautiful button interactions and transitions

Multiple Math Functions: Dynamic graph that changes based on calculations

Real-time Updates: Graph responds to your calculations in real-time

🚀 Live Demo
View Live Demo on Vercel

📋 Project Info
GitHub Repository: https://github.com/ArpitaBaghel810/Calculator-GUI.git

Developer: Arpita Baghel

Student ID: RA2411030030048

🛠️ Technologies Used
HTML5 - Structure and semantics

CSS3 - Styling and animations

JavaScript - Calculator logic and interactions

Three.js - 3D graphics and math visualization

Vercel - Deployment and hosting

📦 Installation & Local Development
Clone the repository

bash
git clone https://github.com/ArpitaBaghel810/Calculator-GUI.git
cd Calculator-GUI
Open in browser

bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Or simply open index.html in your browser
🌐 Deployment
Deploy to Vercel
Go to Vercel and sign in with GitHub

Click "New Project" and import your repository

Connect your GitHub account and select the Calculator-GUI repository

Vercel will automatically detect the configuration and deploy

Your site will be live at https://calculator-gui-arpita.vercel.app

Manual Deployment with Vercel CLI
Install Vercel CLI

bash
npm install -g vercel
Deploy

bash
vercel
Follow the prompts to complete deployment

📁 Project Structure
text
Calculator-GUI/
├── index.html          # Main application file
├── vercel.json         # Vercel deployment configuration
├── README.md           # Project documentation
└── assets/             # Optional assets folder
    ├── images/         # Screenshots and icons
    └── screenshots/    # Project screenshots
🎮 How to Use
Basic Calculator Operations
Numbers: Click number buttons or use keyboard

Operations: +, -, ×, ÷

Functions:

AC - Clear all

C - Clear current entry

⌫ - Delete last digit

% - Percentage

+/- - Toggle sign

. - Decimal point

Keyboard Shortcuts
Numbers: 0-9

Operators: +, -, *, /

Enter/Equal: = or Enter

Clear: Escape or Delete

Backspace: Backspace

Decimal: . (period)

3D Graph Features
The graph automatically changes based on calculation results

Four different mathematical functions:

Sine Wave

Cosine Wave

Complex Wave

Ripple Effect

Mouse/touch interaction for camera movement

🔧 Customization
Changing Color Scheme
Modify the CSS variables in the <style> section:

css
/* Primary colors */
.button.operator { background: #0072ff; }
.button.equals { background: #00c6ff; }
Adding New Math Functions
Extend the calculateFunction method in the MathGraph class:

javascript
case 'your-function':
    return yourCustomFunction(x, z);
📱 Browser Compatibility
Chrome 60+

Firefox 55+

Safari 12+

Edge 79+

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Three.js for 3D graphics capabilities

Vercel for seamless deployment

Android design guidelines for UI inspiration

📞 Support
If you have any questions or issues, please open an issue on GitHub.

Built with ❤️ by Arpita Baghel (RA2411030030048)

Deployed effortlessly on Vercel
