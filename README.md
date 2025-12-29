# ✊✋✌️ **Rock Paper Scissors Game**

## 📌 **Project Overview**
The Rock Paper Scissors Game is a simple and interactive web-based game built using HTML, CSS, and JavaScript. It allows a user to play against the computer, displays the result of each round, and keeps track of wins, losses, and ties. The game uses browser localStorage to persist the score even after page refresh.

---

## 🚀 **Features**
- Play Rock, Paper, or Scissors against the computer  
- Random computer move generation  
- Real-time result display  
- Score tracking for wins, losses, and ties  
- Persistent score storage using browser localStorage  
- Reset score functionality  
- Simple and user-friendly interface  

---

## 🛠️ **Tech Stack**
- HTML – Structure of the game interface  
- CSS – Styling, layout, and button design  
- JavaScript – Game logic and interactivity  
- LocalStorage – Persistent score storage  

---

## 🏗️ **PROJECT ARCHITECTURE**
The project follows a client-side architecture where all logic and data handling are performed in the browser without any backend server.

```USER INTERFACE (HTML + CSS)
↓
JAVASCRIPT GAME LOGIC
(RULES, SCORE CALCULATION)
↓
BROWSER LOCAL STORAGE
(SCORE PERSISTENCE)
```


---

### 🔹 **Architecture Breakdown**
- HTML (Structure)  
  Defines buttons, score display, and result section.

- CSS (Styling)  
  Handles layout, colors, button styles, and overall visual appearance.

- JavaScript (Logic)  
  Implements game rules, random computer moves, result evaluation, score updates, and reset functionality.

- LocalStorage (Data Layer)  
  Stores win, loss, and tie counts so scores persist across page reloads.

---

### 🔁 **Game Flow**
1. User selects Rock, Paper, or Scissors  
2. Computer randomly selects a move  
3. JavaScript compares moves and determines the result  
4. Scores are updated and saved in localStorage  
5. Result and updated scores are displayed on the UI  

---

## 📂 **File Structure**
rock-paper-scissors/
```│── rock.html
│── README.md
```


---

## ▶️ **How to Run the Project**
1. Download or clone the repository  
2. Open `rock.html` in any modern web browser  
3. Start playing the game  

No installation or server setup is required.

---

## 📚 **Key Learnings**
- DOM manipulation using JavaScript  
- Event handling with button clicks  
- Implementing game logic using conditions  
- Using localStorage for persistent data  
- Building an interactive project using core web technologies  

---

## 🔮 **Future Enhancements**
- Add sound effects and animations  
- Display round history  
- Improve UI with icons or images  
- Add difficulty levels or multiplayer mode  

