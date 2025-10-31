# 2D Mario-Style Platformer Game  
Mini Project Report and Documentation  

## Project Overview  
This project is a 2D side-scrolling platformer game inspired by the classic Mario series.  
Developed using Python and the Pygame library, the game features sprite-based animation, collision physics, scoring systems, GUI integration, and level-based progression.  

The project was undertaken as part of our academic mini project to explore the fundamentals of game development, software collaboration, and version control using GitHub.

## Objectives  
- Design and develop a functional 2D platformer game in Python.  
- Implement realistic physics for player motion and collisions.  
- Develop GUI screens for menus, scores, and game flow.  
- Integrate sound and visual assets.  
- Collaborate effectively using Git and GitHub with equal contribution.  
- Prepare comprehensive documentation and report.

## Technologies Used
| Category | Tools Used |
|-----------|------------|
| Programming Language | Python |
| Game Framework | Pygame |
| IDE | Visual Studio Code |
| Graphics Design | Tiled, Photoshop |
| Version Control | Git and GitHub |


## Features Implemented  
- Player movement and jumping mechanics with gravity  
- Collision detection with platforms, enemies, and collectibles  
- Collectible coins and scoring mechanism  
- Start, pause, and game-over screens  
- Background music and sound effects  
- Enemy AI with patrol movement  
- Multiple levels with progressive difficulty  
- On-screen GUI displaying health, score, and level  


## Project Flow  

### 1. Main Menu  
Displays options to start the game, view controls, or exit.  

### 2. Gameplay  
The player navigates through obstacles, collects coins, and avoids enemies.  

### 3. Game Over / Victory Screen  
Displays the player’s final score and provides a restart option.


## Team Members and Contributions  

| Name | Contribution Summary |
|------|-----------------------|
| **Karan Koyande** | Implemented player mechanics, including movement, jump physics, and collision detection. Managed repository setup and version control workflow. |
| **Dhiraj Salekar** | Designed GUI (start, pause, and game-over screens), score display, and user interface. Worked on integrating sound effects and music. |
| **Karan Naglekar** | Developed enemy AI and patrol logic. Created and optimized level layouts using Tiled. Conducted testing and gameplay balancing. |
| **Jaydip Ingle** | Worked on background design, integrated sprite assets, and managed asset organization. Assisted in debugging and documentation. |


## File-Wise Commit Responsibilities  

| File / Folder | Description | Committed By |
|----------------|-------------|--------------|
| `main.py` | Main game loop, input handling, and transitions | Karan Koyande |
| `player.py` | Player movement, gravity, and collision handling | Karan Koyande |
| `enemy.py` | Enemy AI logic and patrol behavior | Karan Naglekar |
| `gui.py` | Menus, score display, and GUI elements | Dhiraj Salekar |
| `/assets/sprites` | Character, enemy, and collectible sprites | Jaydip Ingle |
| `/assets/backgrounds` | Background art and tile sets | Jaydip Ingle |
| `/assets/sounds` | Sound effects and background music | Dhiraj Salekar |
| `/levels` | Level design files created using Tiled | Karan Naglekar |
| `README.md` | Project documentation and report | All Members |


## GitHub Workflow  

The team followed a structured version control process using GitHub:  
- Each member created a separate branch for their assigned module.  
- Weekly merges were reviewed and approved through pull requests.  
- Clear commit messages were maintained to document progress.  
- Conflicts were resolved through team discussions and branch coordination.  

## Challenges Faced  

1. **Frame Rate Optimization**  
   - Initially, frequent redraws caused lag during collisions.  
   - Fixed by updating only active sprites each frame.

2. **Sprite Animation Synchronization**  
   - Animation speed didn’t match jump and walk cycles.  
   - Resolved by timing frame updates with velocity changes.

3. **Sound Delay Issues**  
   - Some systems experienced lag in playing audio files.  
   - Solution: Used `pygame.mixer.pre_init()` for preloading.

4. **Merge Conflicts**  
   - Occurred when two members worked on `main.py` simultaneously.  
   - Solution: Clear ownership assigned per file, followed by code reviews.

5. **Level Design Scaling**  
   - Imported level maps didn’t align with sprite grid size.  
   - Fixed by rescaling tile dimensions to match sprite size.


## Difficulties Faced and What Didn’t Go as Planned  

- The settings and customization menu could not be completed due to time constraints.  
- Planned boss-level logic was dropped due to animation complexity.  
- Initial background images caused inconsistent color blending with tiles.  
- Multiplayer mode was discussed but postponed for a future release.  

## Future Improvements  

- Add more advanced enemy AI and boss fights.  
- Introduce checkpoints and save/load feature.  
- Create additional levels with varying environments.  
- Implement local multiplayer or co-op play.  
- Optimize rendering and memory usage for better performance.  
- Add support for controller input and customizable key bindings.  

## Documentation Summary  

| File | Purpose |
|------|----------|
| `main.py` | Game loop, state transitions, and event handling |
| `player.py` | Manages player physics, input, and animation |
| `enemy.py` | Controls enemy logic and movement patterns |
| `gui.py` | Handles menus, HUD, and score display |
| `/levels` | Tiled maps defining platform layouts |
| `/assets` | Contains all images, sounds, and sprites |

## Learning Outcomes  

- Enhanced understanding of **event-driven programming** in Python.  
- Gained practical experience with **sprite animation and physics simulation**.  
- Developed skills in **modular programming** and **team-based collaboration**.  
- Learned **version control best practices** and **Git workflow management**.  
- Understood the challenges of real-time rendering and frame optimization.  

## Conclusion  

This project provided an in-depth understanding of the fundamentals of 2D game development using Python.  
Through team collaboration, we successfully implemented key game mechanics, integrated GUI, and optimized performance.  
Despite facing challenges, the project strengthened our technical, collaborative, and problem-solving skills.

## Submission Details  

- **Project Title:** 2D Mario-Style Platformer Game  
- **Course:** Mini Project – Game Development using Python  
- **Team Size:** 4 Members  
- **Duration:** 3 Weeks 
- **Team Members:**  
  - Karan Koyande  
  - Dhiraj Salekar  
  - Karan Naglekar  
  - Jaydip Ingle
