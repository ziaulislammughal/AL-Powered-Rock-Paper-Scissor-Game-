Here’s your text with emojis added for better engagement! 🎮👋✊✌️  

---

# 🎉 AI-Powered Rock-Paper-Scissors Game Using Hand Gestures ✋✊✌️

This project is a Python-based implementation of the classic game **Rock-Paper-Scissors** 🎮 using **hand gestures** for control. The game leverages **OpenCV** 📸 and a hand tracking module 🖐️ to detect gestures in real-time and lets you compete against an AI 🤖.

---

## 📚 Table of Contents
- [📄 Description](#description)
- [🔧 Dependencies](#dependencies)
- [⚙️ Setup](#setup)
- [🛠️ How It Works](#how-it-works)
- [🎯 Usage](#usage)
- [💖 Acknowledgements](#acknowledgements)
- [🔗 Links](#links)

---

## 📄 Description  

This project uses a **webcam** 📷 to track your **hand gestures** and allows you to play **Rock-Paper-Scissors** against an AI 🤖. The game relies on the **cvzone** library for hand tracking 🖐️ and **OpenCV** for video processing 🎥.  
Show different hand gestures:  
- ✊ for **Rock**  
- ✋ for **Paper**  
- ✌️ for **Scissors**  

The game evaluates the moves, determines the winner 🏆, and updates the score after each round! 🎲  

---

## 🔧 Dependencies  

You’ll need the following Python libraries:  

- **opencv-python** 📸: For video capture and image processing.  
- **cvzone** 🖐️: For hand gesture detection and interface enhancements.  
- **time** ⏱️: For tracking the timer.  
- **random** 🎲: For generating AI moves.  

💡 Install them with:  
```bash
pip install opencv-python cvzone
```

---

## ⚙️ Setup  

1️⃣ **Clone This Repository:**  
```bash
git clone https://github.com/ziaulislammughal/AI-Powered-Rock-Paper-Scissor-Game  
cd AI-Powered-Rock-Paper-Scissor-Game  
```  

---

## 🛠️ How It Works  

### 🖐️ Hand Detection:  
The **cvzone.HandTrackingModule** detects your hand and interprets gestures:  
- **Rock** ✊: All fingers down (fist).  
- **Paper** ✋: All fingers up (open hand).  
- **Scissors** ✌️: Two fingers up (index and middle).  

### 🤖 Game Logic:  
- AI generates a random move 🎲.  
- Your gesture is compared to the AI's to decide the winner 🏆.  
- Scores are updated 📊 after each round.  

### ⏱️ Timer and Game States:  
Press **'s'** to start the game 🎮. After a **3-second timer**, results are shown along with the updated score.  

### 🖼️ Real-Time Feedback:  
The screen updates with your gesture ✋, AI's move 🤖, and the **scoreboard** 🏆.  

---

## 🎯 Usage  

### 🚀 Start the Game:  
Press **'s'** to begin 🕹️.  

### 🤘 Gestures:  
- **Rock** ✊: Closed fist.  
- **Paper** ✋: Open hand.  
- **Scissors** ✌️: Two fingers up.  

### 🔁 Play:  
Results are displayed after each round! Press **'s'** to play again 🎉.  

### ❌ Exit:  
Press **Esc** to quit the game 🔚.  

---

## 💖 Acknowledgements  

- **cvzone** 🖐️ for simplifying hand gesture detection.  
- Basic AI logic 🤖 implemented using Python.  

---

## 🔗 Links  

- 📂 [GitHub Repository](https://github.com/ziaulislammughal/AI-Powered-Rock-Paper-Scissor-Game)  
- 💼 [LinkedIn Profile](https://www.linkedin.com/in/ziaulislammughal)  
- 📺 [YouTube Channel](https://www.youtube.com/@AIwithzia)  

---

## 📜 License  

This project is open-source 🛠️ under the **MIT License**. Feel free to **fork, modify**, and contribute! 🚀  

---
