# AI Agent Instructions for DoctorApplication

## Project Overview
DoctorApplication is a modern web application built with React and Vite, focusing on medical-related functionalities. The project uses a frontend-only architecture (currently) with modern React practices.

## Project Structure
```
DoctorApplication/
├── frontend/           # React + Vite frontend application
    ├── src/           # Source code
    │   ├── App.jsx    # Main application component
    │   └── main.jsx   # Application entry point
    ├── public/        # Static assets
    └── vite.config.js # Vite configuration
```

## Key Technologies & Patterns
- **Frontend Stack:**
  - React 19 with the new React Compiler enabled
  - Vite (using rolldown-vite) for build tooling
  - TailwindCSS for styling (`className='text-green-500'` pattern in components)
  - React Router DOM for routing
  - Axios for API calls

## Development Workflow

### Getting Started
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development server:
   ```bash
   npm run dev
   ```

### Build & Deploy
- Build command: `npm run build`
- Preview build: `npm run preview`

### Code Style & Linting
- ESLint is configured with React-specific rules
- Run linting: `npm run lint`

## Key Integration Points
- Axios is set up for API communication
- React Router DOM for client-side routing
- React Toastify for notifications

## Common Patterns
- Component files use `.jsx` extension
- TailwindCSS classes for styling
- React Compiler optimization enabled (impacts build performance)

## Performance Considerations
- The project uses the experimental React Compiler
- Vite is configured with rolldown for improved build performance