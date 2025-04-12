# Color Generator

![preview](https://i.imgur.com/oNvgku5.png)

## Overview
A React application that generates 10 shades and 10 tints of any base color you input. The app allows users to copy color hex codes to clipboard with a single click and provides visual feedback via toast notifications.

## Figma URL

[Color generator](https://www.figma.com/file/P2SJ5QGOZvi49EOpoVTvsT/Color-generator?node-id=0%3A1&t=ZY2gnIJ9zGTSXPW8-1)

## Features
- Generates 20 color variations (10 shades and 10 tints) from a base color
- Color input via color picker or hex code text input
- Copy color hex codes to clipboard with one click
- Visual feedback with toast notifications
- Responsive design that works on all screen sizes
- Clean, modern UI with color contrast awareness

## Installation
- Clone the repository:
```bash
git clone https://github.com/Durubhuru14/color-generator.git
cd color-generator
```

- Install dependencies:
```bash
npm install
```

- Run the development server:
```bash
npm run dev
```

## Technologies Used
- React
- Vite (or Create React App)
- values.js (for color generation)
- react-toastify (for notifications)
- Nanoid (for unique keys)
- CSS Modules

## How to Use
- Enter a color using either:
   - The color picker (click the color box)
   - A hex code in the text field (e.g., #ff627d)
- Click "Submit" to generate the color palette
- Click on any color to copy its hex code to clipboard
- You'll see a notification confirming the copy action

## Available Scripts
- `npm run dev`: Starts the development server
- `npm run build`: Builds the app for production
- `npm run lint`: Runs ESLint
- `npm run preview`: Previews the production build

## Dependencies
- react: ^18.2.0
- react-dom: ^18.2.0
- values.js: ^1.4.0
- react-toastify: ^9.1.3
- nanoid: ^4.0.2

## Dev Dependencies
- @vitejs/plugin-react: ^4.2.1
- vite: ^5.0.8
- eslint: ^8.55.0
- eslint-plugin-react: ^7.33.2
- eslint-plugin-react-hooks: ^4.6.0
- eslint-plugin-react-refresh: ^0.4.5