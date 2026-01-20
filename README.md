🎬 Movie Playlist App (Next.js)
A simple movie playlist application built with Next.js, React, and Tailwind CSS.
Users can add movies, edit existing movies, upload posters, and manage data using localStorage.
The UI is fully responsive and optimized for mobile & desktop views.

✨ Features:

➕ Add a new movie (title, year, poster)

✏️ Edit existing movie details

🖼 Image upload with live preview

💾 Data stored in browser localStorage

📱 Fully responsive (mobile, tablet, desktop)

🎨 Modern UI with gradients & wave effects

⚡ Fast routing using Next.js App Router

🛠 Tech Stack

Next.js 13+ (App Router)

React

TypeScript

Tailwind CSS

lucide-react (icons)

📂 Project Structure
app/
├── add/          # Add movie page
├── edit/         # Edit movie page
├── playlist/     # Movie list page
├── main/         # Empty state / landing page
components/
├── MovieForm.tsx

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/your-repo-name.git

2️⃣ Install dependencies
npm install

3️⃣ Run the development server
npm run dev


Open http://localhost:3000
 in your browser.

📱 Responsive Design

Uses Tailwind responsive utilities (sm, md, lg)

Layout switches automatically on mobile

Tested using Chrome DevTools mobile view

Image container uses aspect-square for consistency

🧠 How Edit Works

Selected movie ID is saved in localStorage

Edit page loads movie data using that ID

Changes are saved back to localStorage

User is redirected to playlist

🧪 LocalStorage Example
[
  {
    "id": 1,
    "title": "Inception",
    "year": "2010",
    "imageUrl": "base64-image-string"
  }
]

📌 Future Improvements

Backend integration (MongoDB / Firebase)

Authentication

Delete movie feature

Pagination

Cloud image upload

👩‍💻 Author

Zainab Fatimah
IT Student | Learning Full-Stack Development
GitHub: https://github.com/Zainabfatimahh

⭐ If you like this project

Give it a ⭐ on GitHub — it really helps!
