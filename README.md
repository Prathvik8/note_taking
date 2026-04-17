#📌 Notes Management App
🚀 Overview

A simple notes management app built with Node.js and Express that allows users to create, view, and rename notes stored as text files using the file system.

🛠️ Tech Stack
Node.js, Express.js, EJS, Tailwind CSS, File System (fs)

✨ Features
Create notes (stored as .txt files)
View all notes dynamically
Read individual note content
Rename existing notes

🔗 Routes
GET / → View all notes
POST /create → Create note
GET /part7/files/:filename → Read note
GET /part7/views/edit/:filename → Edit note
POST /edit → Rename note
