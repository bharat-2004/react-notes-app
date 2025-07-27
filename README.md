# React Notes App

A simple and responsive notes application built with React and Vite.  
Users can add, search, and delete notes. Notes are saved in the browser’s local storage.

---

## 🚀 Features

- ✍️ **Add Notes** – Write and save notes (up to 200 characters)
- 🗑️ **Delete Notes** – Remove notes you no longer need
- 🔍 **Search Notes** – Filter notes by content
- 🌗 **Dark Mode** – Toggle between light and dark themes
- 💾 **Persistent Storage** – Notes are saved in local storage and persist across sessions

---

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- npm (comes with Node.js)

---

## 📦 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/bharat-2004/react-notes-app.git
   cd react-notes-app
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm run dev
   ```

   The app will open at: [http://localhost:5173](http://localhost:5173)

---

## 📁 Project Structure

```
src/
  components/
    AddNote.jsx
    Header.jsx
    Note.jsx
    NotesList.jsx
    Search.jsx
  App.jsx
  main.jsx
  index.css
```

---

## 🧑‍💻 Usage

- **Add a note:** Type in the textarea and click "Save"
- **Delete a note:** Click the trash icon on a note
- **Search notes:** Use the search bar to filter notes
- **Toggle dark mode:** Click "Toggle Mode" in the header

---

## ⚙️ Built With

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [nanoid](https://github.com/ai/nanoid)
- [react-icons](https://react-icons.github.io/react-icons/)
