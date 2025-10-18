# Undercooked  
A variation of the trending game *Overcooked*  

---

## Table of Contents  
- [Detailed Description](#detailed-description)  
- [Gameplay](#gameplay)  
- [Architecture](#architecture)  
- [Files](#files)  
- [Results](#results)  

---

## Detailed Description  
**Undercooked** is a fast-paced, cooperative multiplayer cooking game inspired by *Overcooked*, where players must work together to prepare and serve as many dishes as possible within a limited time.  

I designed and developed this game using **Unity**, implementing all core game mechanics with **C#** and utilizing **Object-Oriented Programming** principles to structure the gameplay systems.  
The project’s focus was to create a synchronized multiplayer experience by leveraging **Unity Netcode for GameObjects**, enabling multiple players to play together in real-time through a server-client architecture.  

In addition to programming, I also integrated 3D models and animations created in **Blender** to bring the kitchen and characters to life.  

---

## Gameplay  
- Players coordinate to chop, cook, and assemble ingredients into completed dishes before time runs out.  
- Each player has different tasks that must be efficiently divided to achieve the highest number of completed orders.  
- The challenge increases as more complex recipes and obstacles are introduced in later levels.  
- Communication and teamwork are key to achieving high scores.  

---

## Architecture  
- **Unity Netcode for GameObjects (NGO):** Used to synchronize player movements, object interactions, and completed orders between the server and connected clients.  
- **C# Scripts:** Manage all gameplay logic, including order spawning, timers, recipe tracking, and scoring systems.  
- **Blender Models:** Used for kitchen props, utensils, and food models integrated into Unity.  
- **Server-Client Synchronization:** The server handles the game’s main state and validates all interactions to ensure fairness and prevent desyncs.  

---

## Files  
- `PlayerController.cs`: Handles player movement, input, and interaction logic.  
- `OrderManager.cs`: Manages order generation, validation, and scoring.  
- `GameNetworkManager.cs`: Manages server-client communication and synchronization through Unity Netcode.  
- `KitchenObject.cs`: Defines interactable objects such as ingredients, utensils, and cooking stations.  
- `UIManager.cs`: Controls in-game user interface, including order display, timers, and scores.  

---

## Results  
- Developed a fully functional multiplayer co-op experience with real-time synchronization.  
- Improved gameplay fluidity and reduced desynchronization using **Netcode for GameObjects**.  
- Enhanced user retention and engagement through cooperative gameplay.  
- Successfully simulated team-based coordination challenges similar to *Overcooked* while maintaining smooth multiplayer performance.  
