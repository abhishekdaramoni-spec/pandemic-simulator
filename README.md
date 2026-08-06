# 🦠 India Pandemic Simulator (Prim's Algorithm)

An interactive browser-based pandemic simulation game that demonstrates how infectious diseases can spread through a network of connected Indian states using **Prim's Algorithm**. Players strategically protect states before the infection reaches them, balancing resource management and timing to achieve the highest survival efficiency.

---

## 📌 Overview

The India Pandemic Simulator is an educational web application that combines graph algorithms with epidemic simulation. Each Indian state is represented as a node in a weighted graph, and the virus spreads along the Minimum Spanning Tree (MST) generated using **Prim's Algorithm**.

The player must decide which states to protect before the infection spreads while managing a limited score.

---

## ✨ Features

- 🦠 Pandemic spread simulation
- 🌍 Indian state network visualization
- 🌳 Prim's Algorithm implementation
- 🎮 Interactive gameplay
- 🛡️ Protect states before infection
- 📊 Live statistics dashboard
- ⭐ Score-based gameplay
- ⚡ Adjustable simulation speed
- 📱 Runs directly in any modern web browser
- 🎨 Modern glassmorphism UI

---

## 🧠 Algorithm Used

This project demonstrates **Prim's Algorithm**, a greedy graph algorithm used to construct a **Minimum Spanning Tree (MST)**.

During the simulation:

- Every state is treated as a graph node.
- Connections between states are weighted edges.
- The infection spreads through the minimum-cost edge chosen by Prim's Algorithm.
- Players interrupt the spread by protecting vulnerable states.

This provides an interactive way to visualize graph traversal and greedy algorithms.

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- HTML Canvas API

No external libraries or frameworks are required.

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/abhishekdaramoni-spec/pandemic-simulator.git
```

Open the project folder.

Simply double-click the HTML file or open it in your preferred browser.

No installation is required.

---

## 🎮 How to Play

1. Open the simulator in your browser.
2. Click **Start**.
3. Watch the virus spread between connected states.
4. Protect safe states before they become infected.
5. Use your score wisely.
6. Try to maximize the number of protected and safe states.

---

## 🎯 Game Rules

- Infection starts from a random state.
- Virus spreads according to Prim's Algorithm.
- Protected states cannot become infected.
- Protecting states costs score.
- Late protection costs more than early protection.
- Your goal is to save as many states as possible while maintaining a high score.

---

## 📊 Dashboard

The simulator displays:

- 🟢 Safe States
- 🔵 Protected States
- 🔴 Infected States
- ⭐ Current Score
- 🎯 Efficiency Percentage
- 🏆 Performance Grade
- ⚠ Next Infection Prediction

---

## 📂 Project Structure

```
pandemic-simulator/
│
├── index.html
├── AI-Virus-Detection-Concept-777x518.jpg
└── README.md
```

---

## 📸 Screenshot

Add a screenshot of your simulator here.

Example:

```
screenshots/home.png
```

---

## 🔮 Future Improvements

- More Indian states
- Vaccination system
- Multiple virus variants
- Difficulty levels
- Sound effects
- Infection charts
- Leaderboard
- Save game progress
- Mobile optimization

---

## 🎓 Educational Purpose

This project helps learners understand:

- Prim's Algorithm
- Minimum Spanning Tree (MST)
- Graph data structures
- Greedy algorithms
- Disease spread simulation
- Canvas-based visualization
- JavaScript game development

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 👨‍💻 Author

**Abhishek Daramoni**

GitHub: https://github.com/abhishekdaramoni-spec

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 🌐 Live Demo

Try the Pandemic Simulator online:

🔗 https://lnkd.in/gNmNeN_2

Experience the interactive simulation of pandemic spread using **Prim's Algorithm**, protect states strategically, and observe how graph algorithms influence the spread of infection.
