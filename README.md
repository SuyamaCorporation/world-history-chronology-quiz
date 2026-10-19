# World History Chronological Event Ordering Quiz

A drag-and-drop history quiz where you arrange historical events in chronological order.

## Features

- **35+ event sets** across 3 eras: Ancient, Medieval, Modern
- **Drag-and-drop** interface using HTML5 draggable API
- **Up/Down buttons** as fallback for touch/keyboard users
- **4 Category modes**: All Eras, Ancient (pre-500 CE), Medieval (500–1500), Modern (1500–present)
- **10 rounds per game**, each with 5 events to order
- **Scoring**: 5 pts (all correct), 3 pts (1 wrong), 1 pt (2 wrong), 0 pts (3+ wrong)
- **Results** shown after each round with correct order and years
- **High score** saved per category in localStorage
- Final results screen with per-round breakdown

## Usage

1. Open `index.html` in a modern browser
2. Choose a historical category
3. Drag events into chronological order (earliest first)
4. Submit your order and see how you did
5. Complete 10 rounds to see your final score

## Technical Details

- Single-file SPA, no server required
- Tailwind CSS via CDN
- HTML5 Drag-and-Drop API with visual feedback
- All 35+ event sets hardcoded with accurate historical years
- localStorage for high score persistence per category
- ARIA labels for accessibility
