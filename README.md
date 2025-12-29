# 🎮 3D Obstacle Avoidance Game  
**CSC-317 – 3D Interactive Computer Graphics Final Project**

---

## 📌 Project Overview
This project is a **3D interactive obstacle avoidance game** developed using **Unity Engine** and **C#**.  
The player controls a character in a 3D environment and must **survive as long as possible** by avoiding incoming obstacles.  
The game demonstrates core concepts of **computer graphics**, **real-time rendering**, and **user interaction**.

---

## 🛠️ Tools & Frameworks Used
- **Unity Engine (3D)**
- **C# Programming Language**
- Unity Physics Engine (Rigidbody & Colliders)
- Unity UI System
- Standard Rendering Pipeline
- GitHub for version control

---

## 🎯 Game Overview & Objective
- The game starts at a **Main Menu** where the player selects a difficulty level.
- The gameplay scene loads with a **fade-in transition**.
- The player moves left and right to avoid obstacles.
- Obstacles continuously spawn and move toward the player.
- The score increases over time based on survival duration.
- When the player collides with an obstacle, the game ends.
- A **death overlay** appears showing the score and high score.
- The player can retry the game or return to the main menu.

**Objective:**  
Survive as long as possible and achieve the highest score.

---

## 🎮 Controls
| Action | Key |
|------|-----|
| Move Left | Left Arrow / A |
| Move Right | Right Arrow / D |
| Restart Game | R |
| Exit / Return to Menu | ESC |

---

## 🧩 Graphics Techniques Used

### 🔹 Lighting
- Uses Unity’s built-in lighting system
- Diffuse lighting and specular highlights
- Real-time illumination using Standard Shader

### 🔹 Camera Transformations
- Dynamic camera that follows the player
- Smooth tracking along a controlled axis
- Demonstrates view transformations

### 🔹 Texture Mapping & Materials
- Different materials for player and obstacles
- Uses albedo color, smoothness, and metallic properties
- Improves visual clarity and depth

### 🔹 Shaders
- Unity’s **Standard Shader** is used
- Handles lighting and shading internally
- No custom shaders implemented

### 🔹 Animations
- Physics-based movement and collisions
- Moving obstacles
- Player movement
- Fade-in and fade-out screen transitions

---

## 🖼️ Screenshots
The following screenshots are included in the project report and presentation:
![WhatsApp Image 2025-12-29 at 03 45 10](https://github.com/user-attachments/assets/8ff766be-1eb0-431b-a5d9-27e76847734b)
![WhatsApp Image 2025-12-29 at 03 48 47](https://github.com/user-attachments/assets/1e68f05c-619e-442a-89a0-1e4ef55fe057)
![WhatsApp Image 2025-12-29 at 04 01 38](https://github.com/user-attachments/assets/734ee824-0ebb-42a7-a039-ece4c7ccc65d)


---

## 🚀 How to Run the Game
1. Open **Unity Hub**
2. Select **Open Project**
3. Choose the project folder
4. Open the **Main Menu** scene
5. Press ▶ **Play**
6. Select a difficulty and start playing

---

---

## 👥 Division of Work Among Team Members

### **Member 1 – Core Gameplay & Systems**
- Implemented player movement and physics
- Developed obstacle behavior and collision detection
- Implemented difficulty system
- Managed scoring and high-score logic
- Handled game-over conditions and restart functionality

**Scripts:**
- GameManager.cs  
- PlayerMovement.cs  
- ObstacleMovement.cs  

---

### **Member 2 – UI, Camera & Scene Management**
- Designed and implemented the main menu UI
- Implemented difficulty selection
- Developed camera follow system
- Implemented fade-in and fade-out transitions
- Managed scene navigation and testing

**Scripts:**
- MainMenu.cs  
- Fade.cs  
- FollowTransform.cs  

---

## 📈 Performance & Design
- Real-time rendering at stable frame rates
- Modular, component-based architecture
- Easy to extend with new obstacles or features

---

## ✅ Conclusion
This project successfully demonstrates key **computer graphics concepts** such as 3D transformations, lighting, camera control, animation, and user interaction.  
The game is interactive, visually clear, and designed with scalability in mind for future enhancements.

---

## 📄 License
This project was developed for **educational purposes** as part of the **CSC-317 Computer Graphics course**.
