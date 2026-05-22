# 🥁 Drum Kit

An interactive virtual drum kit built using HTML, CSS, and JavaScript.  
Users can play different drum sounds either by clicking the drum buttons or by pressing corresponding keys on the keyboard.

---

## 🚀 Features

- Play drum sounds using mouse clicks
- Keyboard support for faster interaction
- Button press animation effect
- Responsive and simple UI
- Realistic drum sound effects

---

## 🎹 Controls

| Key | Sound |
|-----|--------|
| W   | Crash |
| A   | Kick Bass |
| S   | Snare |
| D   | Tom 1 |
| J   | Tom 2 |
| K   | Tom 3 |
| L   | Tom 4 |

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## ⚙️ How It Works

### Drum Button Events
Each button with the class `.drum` listens for click events.  
When clicked:
- The corresponding sound is played
- A button animation is triggered

### Keyboard Events
The webpage also listens for keyboard input using the `keypress` event.

### Sound Controller
The `makeSound()` function uses a `switch` statement to match keys with drum audio files.

### Button Animation
The `addAnimation()` function temporarily adds the `pressed` class to create a visual feedback effect.

---

## 📁 Project Structure

```bash
Drum-Kit/
│
├── index.html
├── style.css
├── index.js
│
├── sounds/
│   ├── crash.mp3
│   ├── kick-bass.mp3
│   ├── snare.mp3
│   ├── tom-1.mp3
│   ├── tom-2.mp3
│   ├── tom-3.mp3
│   └── tom-4.mp3
│
└── images/


▶️ How to Run
Download or clone the repository
Open the project folder
Run index.html in your browser