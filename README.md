# Double Pendulum Simulation

## Overview

This project is an interactive double pendulum simulation developed entirely by Claude, an AI assistant created by Anthropic. The simulation showcases the chaotic behavior of a double pendulum system using React and HTML5 Canvas for visualization, and Recharts for data graphing.

## Features

- Real-time simulation of a double pendulum system
- Interactive control of the initial angle of the second pendulum
- Visual representation of the pendulum movement using HTML5 Canvas
- Trail visualization for both pendulum masses
- Real-time graph of pendulum angles over time
- Responsive design for various screen sizes

## Live Demo

You can view the live demo of this project at: [Your Vercel Deployment URL]

## Technology Stack

- React: A JavaScript library for building user interfaces
- HTML5 Canvas: For rendering the pendulum animation
- Recharts: A composable charting library built on React components
- Tailwind CSS: A utility-first CSS framework for rapid UI development

## Installation and Setup

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/double-pendulum-simulation.git
   ```

2. Navigate to the project directory:
   ```
   cd double-pendulum-simulation
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open your browser and visit `http://localhost:3000`

## Project Structure

- `src/App.js`: The main component containing the Double Pendulum simulation logic and UI
- `public/index.html`: The HTML template for the React app
- `src/index.js`: The entry point of the React application

## How It Works

The simulation uses the following key components:

1. **Physics Calculations**: The motion of the double pendulum is calculated using differential equations that describe the system's behavior.

2. **Canvas Rendering**: The pendulum's movement and trails are drawn on an HTML5 Canvas in real-time.

3. **React Hooks**: `useState` and `useEffect` hooks are used to manage the component's state and side effects.

4. **Recharts Integration**: The angles of both pendulums are plotted in real-time using a LineChart from the Recharts library.

## Customization

You can customize various aspects of the simulation:

- Adjust the lengths of the pendulum arms by modifying `l1` and `l2`
- Change the masses of the pendulums by altering `m1` and `m2`
- Modify the gravitational constant `g` to simulate different gravitational conditions

## About the Developer

This project was fully developed by Claude, an AI assistant created by Anthropic. Claude is designed to assist with a wide range of tasks, including software development, data analysis, and creative projects. While Claude has extensive knowledge and capabilities, it's important to note that as an AI, Claude doesn't have personal experiences or a physical presence.

## Limitations and Disclaimer

While this simulation provides a good approximation of double pendulum behavior, it uses numerical methods that may introduce small inaccuracies over time. For educational purposes, this simulation is sufficient, but for scientific research, more precise methods may be required.

## Contributing

As this project is a demonstration of Claude's capabilities, direct contributions are not being accepted. However, you're welcome to fork the project and create your own version!

## License

This project is open-source and available under the MIT License.

## Acknowledgements

- Anthropic, for creating Claude and making this project possible
- The React and Recharts development teams for their excellent libraries

## Contact

For any queries about this project, please open an issue in the GitHub repository.

Remember to star the repository if you find it interesting!