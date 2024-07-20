
# Collab Canvas

A real-time collaborative drawing application built with Next.js, React, and Socket.io. This project allows multiple users to draw on a shared canvas, with changes broadcasted in real-time to all connected clients.

## Working


https://github.com/user-attachments/assets/0ab4dabd-38bc-4a43-999b-8b48b3f42d50


The application uses the HTML Canvas API to draw lines and images. When a new user connects, the current state of the canvas is sent from the server, allowing them to see the latest version of the drawing.

## Features

- **Real-time Collaboration**: Draw on a shared canvas with others in real-time.
- **Color Picker**: Choose from a wide range of colors using the ChromePicker.
- **Clear Canvas**: Clear the entire canvas with a single click.
- **Persistent State**: Canvas state is shared and persisted across sessions.


## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS, React-Color
- **Backend**: Express.js, Socket.io
- **Language**: TypeScript


## Installation

### Requirements

- Node.js (v14.x or later)
- npm or yarn

### Steps

1. Clone the repository:

```bash
git clone https://github.com/yourusername/collab-canvas.git
cd collaborative-drawing-app
```

2. Install dependencies for the client and server:

```bash
cd client
npm install
cd ../server
npm install

```
    
## Usage
### Starting the Server
1. Navigate to the **server** directory:

```bash
cd server
```
2. Start the server:

```bash
npm run server
```
### Starting the Client
1. Navigate to the **client** directory:
```bash
cd client
```
2. Start the development server:
```bash
npm run dev
```
3. Open your browser and go to **http://localhost:3000** to start drawing.
## Project Structure
### Client
- **globals.css**: Tailwind CSS imports and custom styles.
- **page.tsx**: Main component that sets up the canvas, color picker, and socket connections.
- **useDraw.ts**: Custom hook for handling drawing logic and canvas state.
- **drawLine.ts**: Utility function to draw lines on the canvas.
- **tailwind.config.js/ts**: Tailwind CSS configuration.
### Server
- **index.ts**: Sets up the Express server and Socket.io connections.

## Contributing

Contributions are always welcome!

1. Fork the repository.
2. Create a new branch ```git checkout -b feature/your-feature```
3. Commit your changes ```git commit -m 'Add some feature'```
4. Push to the branch ```git push origin feature/your-feature```
5. Open a pull request.


## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License

