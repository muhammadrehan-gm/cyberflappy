# cyberflappy
By CyberRAP group (us).
1. Introduction 
  CyberFlappy is an interactive 2D graphical desktop game developed using the C programming language and the Raylib library. The project builds on the classic       arcade game concept by adding dynamic speed scaling, changing environments based on score, and random environmental events to make the gameplay more engaging      and chalenging. 
2. Existing System 
  Traditional 2D arcade games such as  Flappy Bird  ,  Space  Waves  , and  Geometry Dash  feature popular survival mechanics: 
  ●  Flappy Bird:  Simple controls where the player taps  to flap upward through static vertical pipes, but the background and obstacle style remain repetitive         throughout the run. 
  ●  Geometry Dash & Space Waves:  Fast-paced rhythm-based  games featuring geometric obstacles and changing layouts, though typica ly based on fixed level             designs rather than open survival gameplay. 
3. Problem Statement 
  Most classic single-button arcade games become repetitive very quickly: 
  ●  The visual theme and obstacles remain the same from start to finish. 
  ●  The player only needs to dodge one single type of obstacle (standard vertical pilars). 
  ●  The lack of unexpected events or environmental forces makes the game predictable once the player learns the basic rhythm. 
4. Proposed Solution 
  CyberFlappy solves these issues by combining score-based progression with unpredictable random events: 
  ●  Score-Based Stage Progression:  As the player's score  increases, the environment automaticaly updates. The game transitions from standard classical pi lars       to custom geometric-style shapes that require passing through different gap angles. 
  ●  Independent Random Events:  Instead of fixed levels,  the game triggers temporary surprise events during a run (such as a sudden windy canyon, or an ocean         theme with flying hazards) to test player reflexes. 
  ●  Dynamic Speed Scaling:  The game gradualy speeds up  over time, increasing the difficulty naturaly as the player survives longer. 
5. Salient Features 
  ●  Simple 2D Graphics:  Clean visuals rendered using the Raylib multimedia library in C. 
  ●  Stage Transitions (Based on Score): 
    ○  Stage 1 (Classic Style):  Standard green pilars with clear gaps. 
    ○  Stage 2 (Geometric Style):  Inspired by shapes from  games like  Geometry Dash  , featuring angled blocks and floating shapes. 
  ●  Random In-Game Events: 
    ○  Windy Canyon Event:  Sudden wind forces that push objects toward right to left and players need to dodge them. 
    ○  Ocean Event:  Floating objects and incoming flying  obstacles that cross the screen at different heights. 
  ●  Dynamic Speed Scaling:  The horizontal movement speed  of obstacles increases as the player scores more points. 
  ●  Score Tracking:  Real-time display of the current score. 
6. Tools and Technologies 
  ●  Programming Language:  C Language 
  ●  Graphics Library:  Raylib (for window creation, drawing  shapes, and handling keyboard inputs)
  ●  Development Environment (IDE):  Visual Studio Code (VS Code). 
  ●  Operating System:  Windows.  
●  Development Environment (IDE):  Visual Studio Code (VS Code). 
●  Operating System:  Windows. 
RA
