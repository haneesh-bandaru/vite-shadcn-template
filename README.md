# Vite + Shadcn Template

This template sets up a modern development environment using [Vite](https://vitejs.dev/) as the build tool and [Shadcn](https://shadcn.dev/) for UI components. It provides a foundation for fast and optimized web applications, with built-in support for modern JavaScript and CSS.

## Features

- **Vite** for fast development and optimized builds.
- **Shadcn** for a powerful and flexible component library.
- **TypeScript** for type-safe development.
- **ESLint** and **Prettier** for code quality and formatting.
- **CSS Modules** for scoped and maintainable styles.
- **Hot Module Replacement (HMR)** for instant updates during development.

## Installation

To set up this project, clone the repository and install dependencies.

```bash
git clone https://github.com/your-username/vite-shadcn-template.git
cd vite-shadcn-template
npm install
```

### Running the Development Server

Start the development server using Vite.

```bash
npm run dev
```

The application will be available at [http://localhost:5173](http://localhost:5173).

### Building for Production

To build the project for production, run:

```bash
npm run build
```

The output will be in the `dist/` directory.

### Previewing the Production Build

You can preview the production build with:

```bash
npm run preview
```

## Project Structure

```bash
├── public/               # Static assets
├── src/
│   ├── components/       # Shadcn UI components
│   ├── styles/           # Global styles and CSS Modules
│   ├── views/            # Application pages/views
│   ├── App.tsx           # Main app component
│   └── main.tsx          # Entry point
├── index.html            # Main HTML template
└── vite.config.ts        # Vite configuration
```

## Customization

- **Shadcn Components**: Customize Shadcn components in the `src/components/` folder.
- **CSS Modules**: Scoped CSS can be written in the `src/styles/` folder.
- **Vite Plugins**: Add or remove Vite plugins in `vite.config.ts`.

## Learn More

- [Vite Documentation](https://vitejs.dev/guide/)
- [Shadcn Documentation](https://shadcn.dev/docs/)
- [TypeScript Documentation](https://www.typescriptlang.org/)
