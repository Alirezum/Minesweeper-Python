
# 🧨 Minesweeper Game in Python

A simple yet fully functional implementation of the classic **Minesweeper** game using Python and the `tkinter` GUI library. This project is designed for educational purposes and can be easily modified or extended.
## 🚀 Features

- Classic Minesweeper gameplay logic
    
- Interactive grid with left/right-click behavior
    
- Configurable grid size and mine count
    
- Visual feedback using `tkinter`
    
- Well-structured code using classes and utility modules
    

## 📁 Project Structure

```
minesweeper/
├── main.py         # Entry point – initializes and runs the game
├── cell.py         # Cell class – handles cell logic and UI behavior
├── settigns.py     # Game settings (e.g., grid size, mine count) ← (typo: should be settings.py)
├── utils.py        # Helper functions (random placement, etc.)
```

## 🛠️ Requirements

- Python 3.x
    
- No external libraries needed – just standard Python and `tkinter`
    

> **Note**: `tkinter` comes pre-installed with most Python distributions. If not, you can install it via your package manager:
> 
> - Ubuntu/Debian: `sudo apt install python3-tk`
>     
> - Arch: `sudo pacman -S tk`
>     

## 🧩 How to Play

1. Clone the repo:
    
    ```bash
    git clone https://github.com/yourusername/minesweeper.git
    cd minesweeper
    ```
    
2. Run the game:
    
    ```bash
    python main.py
    ```
    
3. Left-click to reveal a cell, right-click to flag a mine. Avoid the mines!
    

## ⚙️ Customization

Edit `settigns.py` to adjust:

- `GRID_SIZE`: Number of cells in one row/column
    
- `MINES_COUNT`: Total number of mines
    

Example:

```python
GRID_SIZE = 10
MINES_COUNT = 15
```

## 💡 Future Improvements

- Add difficulty levels (easy/medium/hard)
    
- Timer and score tracking
    
- Sound effects and animations
    
- Save/load game state
    


---

## 📄 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

