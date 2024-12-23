# 2048_Game.github.io
 
# 2048 Game with Beautiful Animated Background

A modern implementation of the classic 2048 game featuring a stunning animated background with aurora effects and floating particles. This project combines engaging gameplay with aesthetic visual elements to create an immersive gaming experience.

## 🎮 Game Features

### Core Gameplay
- **4x4 Grid**: Classic 2048 gameplay on a 4x4 board
- **Tile Merging**: Combine tiles with the same numbers to create larger numbers
- **Score Tracking**: Real-time score calculation based on merged tile values
- **New Tile Generation**: Random spawning of new '2' tiles after each move
- **Game Over Detection**: Automatically detects when no more moves are possible

### Controls
- **Arrow Keys**:
  - ⬆️ Up Arrow: Slide tiles upward
  - ⬇️ Down Arrow: Slide tiles downward
  - ➡️ Right Arrow: Slide tiles to the right
  - ⬅️ Left Arrow: Slide tiles to the left

### Visual Elements
1. **Dynamic Background**
   - Shifting gradient background with smooth color transitions
   - Aurora effect with moving colored gradients
   - Floating particle system with randomized movements
   - Pulsing glow effects for depth and atmosphere

2. **Tile Design**
   - Distinct color scheme for each number value
   - Responsive tile animations during merges
   - Clear number display with optimized contrast
   - Progressive color changes as numbers increase

## 🛠️ Technical Features

### Responsive Design
- Flexible layout that adapts to different screen sizes
- Centered game board with proper spacing
- Clearly visible score display
- Smooth animations and transitions

### Game Logic
- Efficient tile merging algorithm
- Random tile generation with fair distribution
- Score calculation system
- Movement validation and boundary checking

### Visual Effects
1. **Background Animations**
   - Multiple layered animations running simultaneously
   - Particle system with randomized parameters
   - Blur effects for depth
   - Opacity variations for visual interest

2. **Color Schemes**
   ```css
   2    -> #eee4da (Light beige)
   4    -> #ece0ca (Darker beige)
   8    -> #f4b174 (Orange)
   16   -> #f59575 (Salmon)
   32   -> #f57c5f (Dark salmon)
   64   -> #f65d3b (Red-orange)
   128  -> #edce71 (Light yellow)
   256  -> #edcc63 (Yellow)
   512  -> #edc561 (Dark yellow)
   1024 -> #ecc744 (Gold)
   2048 -> #ecc230 (Dark gold)
   4096 -> #fe3d3d (Red)
   8192 -> #ff2020 (Bright red)
   ```

## 🎯 How to Play

1. Start the game by opening index.html
2. Use arrow keys to move tiles in desired direction
3. Tiles with the same number will merge when they collide
4. After each move, a new tile (value of 2) appears
5. Goal is to create a tile with the number 2048
6. Game continues until no more moves are possible