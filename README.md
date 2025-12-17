# To Do List App

A full-stack todo list application built with React (frontend) and Node.js + Express (backend).

## Prerequisites

- Node.js installed on your system
- npm (comes with Node.js)

## Installation

1. **Clone or download this repository**

2. **Setup Frontend:**
   - Navigate to `Code/frontend/` folder
   - **Copy the `package.json` file** to the `Frontend/` folder (one level up)
   - Open terminal in the `Frontend/` folder
   - Run `npm install`
   - **Copy ALL files and folders** from `Code/frontend/` to `Frontend/` folder
   - Replace files if asked

3. **Setup Backend:**
   - Navigate to `Code/backend/` folder
   - **Copy the `package.json` file** to the `Backend/` folder (one level up)
   - Open terminal in the `Backend/` folder
   - Run `npm install`
   - **Copy ALL files and folders** from `Code/backend/` to `Backend/` folder
   - Replace files if asked

**Important:** You must copy the files from the `Code` folder to the main `Frontend` and `Backend` folders for the app to work properly!

## Starting the Application

### 1. Start the Backend Server

Open a terminal and run:

```bash
cd Lightaking-Source-Code/Backend
node index.js
```

Wait a few seconds until you see: **"DataBase connected!"**

### 2. Start the Frontend

Open a **new terminal** and run:

```bash
cd Lightaking-Source-Code/Frontend
npm run dev
```

A browser tab should automatically open with the app!

## Folder Structure

```
Lightaking-Source-Code/
├── Frontend/          # React frontend
│   ├── src/
│   ├── package.json
│   └── ...
├── Backend/           # Node.js + Express backend
│   ├── index.js
│   ├── package.json
│   └── ...
└── README.md
```

## Troubleshooting

- If `npm install` fails, try deleting `node_modules` and `package-lock.json`, then run `npm install` again
- Make sure you're in the correct directory (frontend or backend) when running commands
- Check that all environment variables are set correctly

## License

Open Source - Feel free to use and modify!

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
