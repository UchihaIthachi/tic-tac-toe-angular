# Tic Tac Toe Game

## Overview

A modern Tic Tac Toe game built with Angular, styled using Tailwind CSS, and enhanced with Angular animations. The game features a clean UI and provides a fun, interactive experience for users.

## Features

- **Responsive Design**: Works well on various screen sizes.
- **Interactive UI**: Displays messages for game state changes.
- **Player Interaction**: Allows players to make moves and see game results.
- **Animations**: Smooth transitions and animations for a better user experience.

## Tech Stack

- **Frontend**: Angular, Tailwind CSS
- **Animations**: Angular Animations

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/tic-tac-toe.git
   cd tic-tac-toe
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Run the Application**

   ```bash
   ng serve
   ```

   Open your browser and navigate to `http://localhost:4200` to see the application in action.

### Building for Production

To build the application for production, use:

```bash
ng build --prod
```

The output will be placed in the `dist/` directory.

### Project Structure

- `src/app/`
  - `components/` - Contains Angular components for the game.
  - `services/` - Contains services for game logic (if any).
  - `animations/` - Defines Angular animations.
- `src/styles/` - Contains Tailwind CSS styles.
- `src/environments/` - Environment configurations.
- `angular.json` - Angular CLI configuration.
- `tailwind.config.js` - Tailwind CSS configuration.
