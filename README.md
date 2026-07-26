# ✋ Aerial — Hand Gesture Drawing Board

Aerial is a browser-based virtual drawing board that lets you draw in the air using your hand gestures. It uses **MediaPipe Hands** for real-time hand tracking and HTML5 Canvas for smooth drawing, allowing users to paint without touching a mouse or stylus.

---

## ✨ Features

- 🎨 Draw using your index finger
- 🤏 Pinch gesture to adjust brush size dynamically
- 🖐️ Open palm to erase nearby strokes
- ✊ Hold a fist to clear the entire canvas
- 🤙 Thumb + pinky gesture to cycle brush colors
- 💾 Save artwork as PNG
- 🎥 Real-time webcam feed
- 🌈 Modern glassmorphism interface
- 📱 Responsive design for desktop and mobile browsers

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- MediaPipe Hands
- HTML5 Canvas API

---

## 📂 Project Structure

```
project/
│── index.html
│── README.md
```

The entire application is contained within a single HTML file.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/aerial.git
```

### 2. Open the project

Since browsers block webcam access from local files, **do not open `index.html` directly**.

Run a local server instead.

### Using Python

```bash
python -m http.server
```

or

```bash
python3 -m http.server
```

Then open:

```
http://localhost:8000
```

---

## 🎮 Gesture Controls

| Gesture | Action |
|----------|--------|
| ☝️ Index Finger | Draw |
| 🤏 Thumb + Index Pinch | Change brush size |
| ✌️ Index + Middle Finger | Move without drawing |
| 🖐️ Open Palm | Erase |
| ✊ Hold Fist | Clear entire canvas |
| 🤙 Thumb + Pinky | Switch brush color |

---

## 💾 Saving Artwork

Click the **Save PNG** button to download your current drawing as an image.

---

## ⚠️ Requirements

- Modern browser (Chrome, Edge, Firefox)
- Webcam
- HTTPS or localhost
- Camera permission enabled

---

## 🌐 External Libraries

MediaPipe Hands is loaded from the jsDelivr CDN:

- MediaPipe Hands
- Camera Utils

No installation is required.

---

## 📸 Screenshots

Add screenshots here.

```
/screenshots/home.png
/screenshots/drawing.png
/screenshots/gestures.png
```

---

## 🔮 Future Improvements

- Multiple brush styles
- Shape recognition
- Undo / Redo
- Handwriting recognition
- Multi-hand support
- Collaborative online drawing
- Pressure-sensitive brush simulation
- Custom color picker

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is available under the MIT License.

---

## 👨‍💻 Author

Developed with ❤️ using HTML, CSS, JavaScript, and MediaPipe Hands.
