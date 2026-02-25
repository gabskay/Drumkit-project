# Drumkit-project
# 🥁 Virtual Drum Kit

<img width="1875" height="928" alt="image" src="https://github.com/user-attachments/assets/11782a26-952f-4139-adc8-657b07b044d9" />

<!-- Make sure to upload a screenshot of your project to your repo and replace the link above! -->

A browser-based, interactive drum kit built with vanilla JavaScript. Play the drums using your computer keyboard with real-time visual feedback. Perfect for killing time or practicing your air-drumming skills.

## ✨ Features

- **Keyboard Playability:** Press keys (W, A, S ,D,J, K, L) to trigger different drum sounds.
- **Instant Visual Feedback:** Buttons animate on press (scale up and glow) to simulate a physical hit.
- **Rapid Hit Support:** The audio resets on each key press, allowing for fast drum rolls.
- **Responsive Design:** Works on different screen sizes (Desktop and Tablet).
- **Clean UI:** A modern, dark-themed interface with clearly labeled keys.

## 🛠️ Built With

- **HTML5:** For structuring the drum pads and audio elements.
- **CSS3:** For styling, grid layout, and animations.
- **JavaScript (ES6):** For handling keyboard events, audio control, and DOM manipulation.

## 🚀 Live Demo

Check out the live version hosted on GitHub Pages:

**(https://gabskay.github.io/Drumkit-project/)** 
<!-- Replace the link above with your actual GitHub Pages URL -->

## 🎮 How to Play

1.  Visit the [Live Demo][https://gabskay.github.io/Drumkit-project/] link.
2.  Make sure your cursor is focused on the browser window (click anywhere on the page).
3.  Press the keys displayed on the screen (e.g., **W**, **A**, **S**, **J**) to hear the corresponding drum sounds.
4.  Watch the pads light up as you play!

## 📁 Key Files Explained

- `index.html`: Contains the structure of the drum pads and audio sources.
- `style.css`: Handles all the styling, layout, and the `.playing` animation state.
- `script.js`: Contains the JavaScript logic for playing sounds and handling transitions.
- `/sounds/`: Folder containing the drum hit sound files.

## 💡 What I Learned

- Connecting keyboard events (`keydown`) to visual elements using `data-` attributes.
- The nuances of the HTML5 Audio API (specifically resetting the `currentTime` to allow for overlapping sounds).
- Using `transitionend` events to remove CSS classes after animations finish, keeping the code clean.
- Deploying a static site using GitHub Pages.

## 📬 Contact

Made with 🎧 by **Gabriel**

- LinkedIn:  [(https://www.linkedin.com/in/gabriel-kumadey-9918a833a/)]
- GitHub: [(https://github.com/gabskay)]

