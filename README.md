tugas sekolah

i vibe coded it

![nyengir](nyengir/nyengir.jpg)

# Bullet Hell Game

A browser-based bullet hell shooter built with vanilla JavaScript and Canvas API.

## Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Git (optional, for cloning)

### Clone the Repository

```bash
git clone https://github.com/griimmv/bullet-hell.git
cd bullet-hell
```

### How to Run

1. **Open directly in browser** — double-click `index.html` or drag it into your browser window.
2. **Serve locally** (recommended for best performance):

   Using Python:
   ```bash
   python3 -m http.server 8080
   ```

   Using Node.js (`npx`):
   ```bash
   npx serve .
   ```

   Then open `localhost:(the port number you get)` in your browser.

### Controls

| Key | Action |
|-----|--------|
| W / Arrow Up | Move up |
| S / Arrow Down | Move down |
| A / Arrow Left | Move left |
| D / Arrow Right | Move right |
| B | Bomb (screen clear) |
| R | Restart (on game over) |

### Project Structure

```
bullet-hell/
├── index.html          # Main game (HTML + JS + CSS)
├── nyengir/
│   ├── nyengir.jpg     # Project image
│   └── asset/
│       ├── alien.jpg   # Enemy sprite
│       └── police.jpg  # Player sprite
└── README.md
```
