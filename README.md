# Self-Driving-CAR-ML-Vanilla-js
# 🚗 Self-Driving Car with Neural Networks (No Libraries)

This project implements a **self-driving car simulation** using only **Vanilla JavaScript + HTML Canvas**.  
The car learns to drive using a simple **feed-forward neural network**, trained via **neuro-evolution** (random mutation + survival of the fittest).  


---

## 🌟 Features
- Custom **road & physics engine** (no external libraries).
- Cars equipped with **sensors** that detect distance to borders/traffic.
- Lightweight **neural network implementation** (from scratch).
- Real-time **network visualizer**.
- **Save/Load best brain** with localStorage (💾 / 🗑️ buttons).
- Pure HTML/CSS/JS — works in any modern browser.

---

## 🧠 How It Works
1. **Sensors** project rays to detect distance from obstacles.
2. **Inputs** (normalized distances) feed into the neural network.
3. **Neural Network** outputs 4 values → `[forward, left, right, reverse]`.
4. **Car physics** update position, speed, and steering accordingly.
5. **Evolutionary training**:
   - Start with random brains.
   - The best car’s brain is saved.
   - Next generation = clones of best brain with small random mutations.

---

## 📂 Project Structure
