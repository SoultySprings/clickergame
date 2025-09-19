# ✨ Click-Upgrades: Polished Canvas Demo

This is a web-based clicker game built to showcase a polished user interface and dynamic visual effects using the **HTML5 Canvas API** and vanilla JavaScript. The core game logic is a straightforward sequential upgrade system, but the focus is on creating a satisfying and visually rich user experience.



## 🚀 Features

* **🎨 Dynamic Canvas Background**: A multi-layered, procedurally generated nebula background with twinkling stars and drifting orbs that create a sense of depth and motion.
* **🖱️ Interactive 3D Button**: A glossy, animated button rendered on the canvas that provides tactile feedback through scaling animations, particle bursts, and ripple effects on every click.
* **✨ Animated UI Elements**: Stats update with smooth transitions, affordable shop items gently pulse, and new items animate into view, making the UI feel alive and responsive.
* **⚙️ Customizable Game Progression**:
    * Choose from presets like "fast" (50 clicks per upgrade) or the "original" (375 clicks per upgrade).
    * Set custom parameters for base click power, target clicks-per-upgrade, and the total number of tiers.
* **💾 State Persistence**: Your progress, including points, current tier, and settings, is automatically saved to your browser's `localStorage`. Manual save and reset options are also available.
* **⌨️ Full Keyboard Controls**: Play the entire game without a mouse!
    * **Space**: Click for points
    * **B**: Buy the next available upgrade
    * **1-9**: Buy a specific tier (if available)
    * **S**: Save progress
    * **R**: Reset the game
    * **H**: Open the help modal
* **📱 Responsive Design**: The layout fluidly adapts to different screen sizes, making it playable on both desktop and mobile devices.

## 🎮 How to Play

1.  **Click the button** (or press `Space`) to earn points.
2.  Use your points to **buy the next available upgrade** from the shop on the right.
3.  Each upgrade **increases your click power**, allowing you to earn points faster.
4.  Use the **presets or custom fields** to change the game's pacing and generate a new set of items.

## 🛠️ Technologies Used

* **HTML5**: Base structure and content.
* **CSS3**: Modern styling including CSS Variables, Flexbox, Grid, and keyframe animations.
* **JavaScript (ES6+)**: All game logic, state management, and direct DOM/Canvas manipulation without any external libraries or frameworks.

## 📂 How to Run Locally

Since this project uses only vanilla web technologies, you can run it without any build steps.

1.  Clone the repository:
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Navigate to the project directory:
    ```sh
    cd your-repo-name
    ```
3.  Open the `index.html` file in your favorite web browser.
