﻿## Create README.md and add content
echo "# Notes Maker Backend App

A simple and efficient backend for a notes-making web application. This app allows users to create, edit, and manage notes with a customizable filename feature. Built using **HTML, CSS, JavaScript, EJS, Express.js, and Node.js**.

## Features
- 📝 Create, edit, and delete notes  
- 📂 Edit filenames for better organization  
- 🌐 Supports EJS for dynamic templating  
- 🚀 Fast and lightweight with Express.js  

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript, EJS  
- **Backend:** Node.js, Express.js  
- **Storage:** JSON / Database (optional)  

## Installation
1. Clone the repository:
   \`\`\`sh
   git clone https://github.com/tmk798/notesmakerbackendapp.git
   \`\`\`
2. Navigate to the project folder:
   \`\`\`sh
   cd notesmakerbackendapp
   \`\`\`
3. Install dependencies:
   \`\`\`sh
   npm install
   \`\`\`
4. Start the server:
   \`\`\`sh
   node app.js
   \`\`\`
5. Open in browser:
   \`\`\`
   http://localhost:3000
   \`\`\`

## API Endpoints
| Method | Endpoint      | Description          |
|--------|-------------|----------------------|
| GET    | /notes       | Fetch all notes     |
| POST   | /notes       | Add a new note      |
| PUT    | /notes/:id   | Edit an existing note |
| DELETE | /notes/:id   | Delete a note       |

## Contributing
Pull requests are welcome! 🚀  

## License
MIT License" > README.md

# Add, commit, and push the README.md file to GitHub
git add README.md
git commit -m "Added README.md"
git push origin main

