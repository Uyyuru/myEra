
🎨 MyEra Sticker Canvas
A React-based web application built as part of the MyEra Frontend Internship mini-task. This app enables users to place, drag, and manage stickers on a 600x400 interactive canvas using react-konva.

✨ Features
Fixed Canvas Size: A 600x400 Konva canvas for sticker placement and arrangement.

Add Stickers: Three buttons allow adding different stickers at default positions.

Drag & Drop: Stickers are draggable with their positions maintained.

Download as PNG: Export the current canvas layout as an image.

Bonus – Delete Stickers: Double-click a sticker to remove it.

Bonus – Grid Snapping: Stickers snap to a 40x40 grid for better alignment.

🛠️ Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/myera-sticker-app.git
cd myera-sticker-app
Install Dependencies

bash
Copy
Edit
npm install
Run the App

bash
Copy
Edit
npm start
Open in Browser
Navigate to http://localhost:3000 to use the app.

📺 Demo
[Add a 1-minute demo video or GIF here]

Showcase how to add, drag, delete, and download stickers.

🧰 Technologies Used
React – UI and state management

react-konva – React bindings for Konva canvas library

Konva – Canvas rendering and drag/drop functionality

use-image – To load sticker images

CSS – Flexbox for layout and styling

🗂 Project Structure
pgsql
Copy
Edit
myera-sticker-app/
├── public/
│   ├── index.html
│   └── stickers/
│       ├── sticker1.png
│       ├── sticker2.png
│       └── sticker3.png
├── src/
│   ├── components/
│   │   ├── Canvas.js
│   │   └── StickerButton.js
│   ├── App.js
│   ├── App.css
│   └── index.js
├── README.md
├── package.json
└── .gitignore
📝 Notes
Sticker images are small PNGs (e.g., 50x50) located in public/stickers/.

The app runs completely on the client side (no backend or persistence).

Bonus features like deletion and snapping enhance user experience.

Git commits follow a clear and descriptive format (e.g., Add drag-and-drop, Implement grid snapping).

📌 Usage Guide
Click a sticker button to add a sticker to the canvas.

Drag the sticker to reposition it.

Double-click a sticker to delete it (if enabled).

Click Download Canvas to save the current layout as a PNG.

