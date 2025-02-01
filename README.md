# Three.js with Vite: Dodecahedron and Box

This is my second Three.js project, where I explored using **Vite** as a build tool and added a **dodecahedron** and a **basic box** to the scene. This project demonstrates how to set up a Three.js project with Vite and create more complex 3D objects.

## Overview

In this project, I:

- Set up a Three.js project using **Vite** for fast development and bundling.
- Added a **dodecahedron** (a 12-sided polyhedron) and a **basic box** to the scene.
- Applied basic materials and lighting to the objects.
- Animated the scene to rotate the objects smoothly.

## Features

- A rotating **dodecahedron** and **box** in a 3D scene.
- Basic lighting setup with a `PointLight`.
- Smooth animations using `requestAnimationFrame`.
- Built with **Vite** for a modern development workflow.

## Technologies Used

- [Three.js](https://threejs.org/) - A JavaScript library for 3D rendering.
- [Vite](https://vitejs.dev/) - A fast build tool for modern web development.
- HTML5
- CSS3
- JavaScript (ES6+)

---

## Installation Steps

Follow these steps to run this project locally on your machine:

### Prerequisites

- Ensure you have [Node.js](https://nodejs.org/) installed (v14 or higher).
- A code editor like [VS Code](https://code.visualstudio.com/).

### Step 1: Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/hashan-athu/three-js-vite-getting-started.git
```

### Step 2: Navigate to the Project Directory

Move into the project folder:

```bash
cd your-repo-name
```

### Step 3: Install Dependencies

Install the required dependencies using npm:

```bash
npm install
```

### Step 4: Start the Development Server

Run the Vite development server:

```bash
npm run dev
```

### Step 5: Open the Project in Your Browser

Once the server is running, open your browser and navigate to:

```
Code Structure
Copy
your-repo-name/
├── public/              # Static assets (optional)
├── src/
│   ├── main.js          # Main JavaScript file with Three.js code
│   ├── style.css        # Optional CSS file for styling
├── index.html           # Main HTML file
├── vite.config.js       # Vite configuration file
├── package.json         # Project dependencies and scripts
├── README.md            # This file
└── screenshot.png       # Screenshot of the project (optional)
```

## How It Works

- The index.html file includes the necessary scripts and a canvas element for rendering the 3D scene.
- The main.js file contains the Three.js code to:
- Set up the scene, camera, and renderer.
- Create a dodecahedron and a box using THREE.DodecahedronGeometry and THREE.BoxGeometry.
- Add materials and lighting to the objects.
- Animate the scene using requestAnimationFrame.
- Vite is used to bundle the project and provide a fast development server.

## Future Improvements

- Add textures and advanced materials to the objects.
- Implement user interactions (e.g., mouse controls for rotation).
- Add more complex 3D models and animations.
- Explore post-processing effects (e.g., glows, shadows).

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any suggestions or improvements are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Happy coding! 🚀
