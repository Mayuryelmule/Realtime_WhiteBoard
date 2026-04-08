🖌️ PepBoard - Real-Time Collaborative Whiteboard

PepBoard is a real-time collaborative drawing application where multiple users can draw, write, and interact on a shared canvas. It supports tools like pencil, eraser, sticky notes, image upload, undo/redo, and live synchronization using WebSockets.

🚀 Features
✏️ Pencil tool with adjustable size & color
🧽 Eraser tool
📌 Sticky notes (draggable & editable)
🖼️ Upload and place images
↩️ Undo / Redo functionality
💾 Download canvas as image
🍔 Responsive hamburger menu
🌐 Real-time collaboration using Socket.io
🛠️ Tech Stack

Frontend:

HTML5
CSS3
JavaScript
Canvas API

Backend:

Node.js
Express.js
Socket.io

📂 Project Structure
```
PepBoard/
│── public/
│   ├── css/
│   ├── js/
│   ├── NewIcons/
│   └── index.html
│
│── express.js
│── package.json
│── README.md
```
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/pepboard.git
cd pepboard
2. Install dependencies
npm install
3. Run the server
npm start
4. Open in browser
http://localhost:3000
🔌 How It Works
The canvas captures mouse events (mousedown, mousemove, mouseup).
These events are sent to the server via Socket.io.
The server broadcasts them to all connected clients.
All users see the drawing in real-time.
📸 Functionalities Overview
🎨 Drawing
Draw freely using pencil tool
Change color and stroke size
🧽 Erasing
Remove drawings using eraser
📝 Sticky Notes
Create movable notes
Add text or images
🖼️ Image Upload
Upload images to canvas
🔄 Undo / Redo
Continuous undo/redo with press hold
💾 Download
Export canvas as PNG
🌍 Deployment

You can deploy this project on:

Render
Railway
Heroku (legacy)

Make sure to:

Set PORT from environment variables
Serve static files correctly
🧪 Future Improvements
User authentication
Room-based collaboration
Save/load board state
Mobile touch support improvement
Whiteboard themes
🤝 Contributing

Contributions are welcome!

Fork the repo
Create a new branch
Make changes
Submit a pull request
📜 License

This project is licensed under the ISC License.

🙌 Acknowledgement

Inspired by collaborative tools like online whiteboards and learning platforms.
