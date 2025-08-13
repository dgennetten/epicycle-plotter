# Epicycle Spirograph

An interactive mathematical visualization that creates beautiful spirograph patterns using epicycles. Built with React and HTML5 Canvas.

## Features

- **Interactive Controls**: Adjust the number of circles (1-10), radius, and speed for each circle
- **Real-time Animation**: Watch as the epicycles create intricate patterns
- **Dark/Light Mode**: Toggle between dark and light themes
- **Responsive Design**: Adapts to different screen sizes
- **Play/Pause Controls**: Start and stop the animation at any time
- **Reset Functionality**: Clear the current pattern and start fresh

## How It Works

The application uses the mathematical concept of epicycles - circles moving around other circles. Each circle rotates around the previous circle's position, creating complex and beautiful patterns. The final shape is the result of combining all the circular motions.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

1. Start the development server:
   ```bash
   npm start
   ```

2. Open your browser and navigate to `http://localhost:3000`

3. The application will automatically open in your default browser

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `build` folder.

## Usage

1. **Start the Animation**: Click the "Play" button to begin the animation
2. **Adjust Parameters**: Use the sliders to modify circle radius and speed
3. **Change Circle Count**: Use the number input to add or remove circles
4. **Toggle Theme**: Use the dark mode checkbox to switch between themes
5. **Reset**: Click "Reset" to clear the current pattern and start over

## Technical Details

- **Frontend**: React 18 with functional components and hooks
- **Styling**: Tailwind CSS for responsive design
- **Animation**: HTML5 Canvas with requestAnimationFrame for smooth 60fps animation
- **State Management**: React useState and useEffect hooks

## Browser Support

This application works best in modern browsers that support:
- ES6+ JavaScript features
- HTML5 Canvas
- CSS Grid and Flexbox
- requestAnimationFrame API

## License

This project is open source and available under the MIT License.


