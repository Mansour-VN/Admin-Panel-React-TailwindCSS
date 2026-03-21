# Admin Panel - React + Tailwind CSS

A modern, responsive admin dashboard built with React and Tailwind CSS.  
This project includes reusable UI components, multiple dashboard pages, interactive charts, and app-like modules such as a calendar, kanban board, and rich text editor.

## Live Demo

[View Demo](https://admin-panel-react-tailwind-css.vercel.app/)

## Features

- Clean and responsive admin panel layout
- Light/Dark theme support
- Customizable accent color settings
- Reusable dashboard components (navbar, sidebar, cards, widgets)
- Data visualization pages (line, area, bar, pie, financial, stacked, pyramid)
- Productivity pages (kanban, calendar, rich text editor)
- Basic ecommerce-style dashboard experience

## Tech Stack

- React 17
- Tailwind CSS
- React Router v6
- Syncfusion React UI components
- React Icons
- Create React App

## Project Pages

- `Ecommerce`
- `Orders`
- `Employees`
- `Customers`
- `Kanban`
- `Calendar`
- `Editor`
- `Color Picker`
- `Charts` (Line, Area, Bar, Pie, Financial, Color Mapping, Pyramid, Stacked)

## Getting Started

### Prerequisites

- Node.js 16+ (recommended)
- npm

### Installation

```bash
git clone https://github.com/<your-username>/Admin-Panel-React-TailwindCSS.git
cd Admin-Panel-React-TailwindCSS
npm install
```

### Run in Development

```bash
npm start
```

Then open `http://localhost:3000`.

### Build for Production

```bash
npm run build
```

The optimized production build will be generated in the `build` folder.

## Available Scripts

- `npm start` - Run development server
- `npm run build` - Build production bundle
- `npm test` - Run test watcher
- `npm run eject` - Eject CRA configuration (irreversible)

## Folder Structure (Simplified)

```text
src/
  components/    # Reusable UI and chart components
  contexts/      # Global context and theme state
  data/          # Static dummy data
  pages/         # Route-level pages
  App.js         # App layout and routing
```

## Credits

- UI components and charting powered by [Syncfusion](https://www.syncfusion.com/react-components)
- Icons from [React Icons](https://react-icons.github.io/react-icons/)

## License

This project is open source and available under the MIT License.
