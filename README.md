# Interactive 3D Portfolio Website

Welcome to my interactive 3D portfolio website built with React, TypeScript, and Three.js. This project showcases an immersive web experience featuring a 3D character model that responds to user interactions, smooth scroll animations, and modern web technologies.

## 🚀 Features

- **Interactive 3D Character**: A responsive 3D model that tracks mouse movement and reacts to user interactions
- **Smooth Animations**: GSAP-powered scroll-triggered animations for a polished user experience
- **Responsive Design**: Fully responsive layout that works across all device sizes
- **Performance Optimized**: Efficient rendering and optimized 3D graphics
- **Modern Tech Stack**: Built with cutting-edge web technologies

## 🛠️ Tech Stack

- **Frontend**: React, TypeScript
- **3D Graphics**: Three.js, @react-three/fiber, @react-three/drei
- **Physics**: @react-three/cannon, @react-three/rapier
- **Animations**: GSAP, Framer Motion
- **UI Components**: Custom-built with CSS modules
- **Build Tool**: Vite
- **Additional**: WebGL, HTML5, CSS3

## 📦 Dependencies

- `react`, `react-dom` - Core React functionality
- `@react-three/fiber` - React renderer for Three.js
- `@react-three/drei` - Useful helpers for React Three Fiber
- `@react-three/cannon` - Physics engine for React Three Fiber
- `@react-three/postprocessing` - Post-processing effects
- `three` - 3D library
- `gsap` - Advanced animation library
- `lenis` - Smooth scrolling solution

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio
   ```

3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

4. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open your browser and visit `http://localhost:5173` (or the address shown in your terminal)

## 📁 Project Structure

```
src/
├── components/           # React components
│   ├── Character/        # 3D character implementation
│   ├── styles/           # CSS styles
│   ├── utils/            # Utility functions
│   └── ...               # Other components
├── context/              # React context providers
├── data/                 # Static data files
├── utils/                # Global utility functions
├── App.tsx              # Main application component
├── config.ts            # Configuration and content
└── ...                  # Other root files
```

## 🛠️ Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check for code issues

## ⚙️ Configuration

The project includes a `config.ts` file where you can customize:
- Developer information (name, title, description)
- Social media links
- Project details
- Experience information
- Skills and technologies

## 🎨 Customization

To customize this portfolio for your own use:

1. Update `src/config.ts` with your personal information
2. Replace images in the `public` directory with your own
3. Modify the CSS files in `src/components/styles/` to match your preferred styling
4. Update or replace the 3D models if needed

## 📸 Preview

![Portfolio Preview](https://github.com/user-attachments/assets/3c4557e7-6392-4928-b8a9-7b2476ef4edd)

## 🚨 Note about GSAP Club Plugins

This project uses GSAP for animations. Some advanced features require GSAP Club plugins which are not open source. For the trial version, you can use the trial plugins for development, but note that you cannot host the site publicly without a GSAP Club membership. For hosting, please check: https://gsap.com/docs/v3/Installation/

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request if you have ideas for improvements or new features.

## 🐛 Issues

If you encounter any issues or bugs, please open an issue in the repository with a detailed description.
