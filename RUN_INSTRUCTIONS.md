# How to Run the React Application Locally

## Prerequisites
- Node.js (v14 or higher) - [Download here](https://nodejs.org/)
- npm (comes with Node.js) or yarn

## Step-by-Step Instructions

### 1. Install Dependencies (if not already installed)
Open your terminal/command prompt in the project directory and run:

```bash
npm install
```

This will install all required dependencies including React, Tailwind CSS, and other packages.

### 2. Start the Development Server
Once dependencies are installed, run:

```bash
npm start
```

This will:
- Start the React development server
- Automatically open your browser at `http://localhost:3000`
- Enable hot-reloading (changes will refresh automatically)

### 3. View the Application
The application will be available at:
- **Local:** http://localhost:3000
- **Network:** The terminal will also show a network URL you can use on other devices

### 4. Stop the Server
Press `Ctrl + C` in the terminal to stop the development server.

## Other Useful Commands

### Build for Production
```bash
npm run build
```
Creates an optimized production build in the `build` folder.

### Run Tests
```bash
npm test
```

## Troubleshooting

### Port Already in Use
If port 3000 is already in use, React will ask if you want to use another port. Press `Y` to confirm.

### Dependencies Not Installing
- Make sure you have Node.js installed: `node --version`
- Try deleting `node_modules` and `package-lock.json`, then run `npm install` again

### Module Not Found Errors
- Run `npm install` again to ensure all dependencies are installed
- Make sure you're in the correct project directory

## Quick Start (All in One)
```bash
# Navigate to project directory
cd "C:\Users\Shiwangi Singh\Downloads\creator shop"

# Install dependencies
npm install

# Start the server
npm start
```

