# 📝 React Notes App

A modern, intuitive notes application built with React and Vite. Create, edit, delete, and manage your notes with persistent local storage.

![React](https://img.shields.io/badge/React-19.2.0-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.2.4-646CFF?logo=vite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Features

- **Create Notes**: Add new notes with a character limit of 100 characters
- **Edit Notes**: Modify existing notes inline
- **Delete Notes**: Remove unwanted notes with a single click
- **Character Counter**: Real-time character count display showing remaining characters
- **Persistent Storage**: Notes are automatically saved to browser's local storage
- **Responsive Design**: Clean, modern UI that works on all devices
- **Fast & Lightweight**: Built with Vite for optimal performance

##🚀 Demo

![App screenshot](src/assets/App%20screenshot.png)

## �🚀 Technologies Used

- **React 19.2.0** - Modern UI library with hooks
- **Vite 7.2.4** - Next-generation frontend build tool
- **UUID** - Unique identifier generation for notes
- **Local Storage API** - Persistent data storage
- **ESLint** - Code quality and consistency

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (version 14 or higher)
- npm or yarn package manager

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/shashiniahinsa/react-notes-app.git
   cd noteapp
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 📦 Available Scripts

- `npm run dev` - Start the development server with hot module replacement
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## 📁 Project Structure

```
noteapp/
├── public/              # Static assets
├── src/
│   ├── Components/      # React components
│   │   ├── Header.jsx   # App header component
│   │   ├── Notes.jsx    # Main notes container with state management
│   │   ├── Note.jsx     # Individual note display component
│   │   ├── CreateNote.jsx # Note creation/editing form
│   │   └── notes.css    # Component styles
│   ├── assets/          # Images and other assets
│   ├── App.jsx          # Main application component
│   ├── App.css          # Global app styles
│   ├── main.jsx         # Application entry point
│   └── index.css        # Global styles
├── eslint.config.js     # ESLint configuration
├── vite.config.js       # Vite configuration
├── package.json         # Dependencies and scripts
└── README.md           # Project documentation
```

## 💡 How It Works

### Component Architecture

1. **App.jsx**: Root component that renders the Header and Notes components
2. **Header.jsx**: Displays the application title
3. **Notes.jsx**: Main container managing note state, CRUD operations, and local storage
4. **Note.jsx**: Displays individual note with Edit and Delete buttons
5. **CreateNote.jsx**: Form component for creating and editing notes with character counter

### State Management

- Uses React hooks (`useState`, `useEffect`) for state management
- Notes array stored in component state
- Each note has a unique ID generated using UUID

### Local Storage

- Notes are automatically saved to browser's local storage
- Data persists across browser sessions
- Loaded on component mount and updated on every change

## 🎨 Features in Detail

### Creating a Note
- Type in the textarea (max 100 characters)
- Character counter shows remaining space
- Click "Save" to add the note

### Editing a Note
- Click "Edit" on any note
- The note transforms into an editable textarea
- Modify the text and click "Save" to update

### Deleting a Note
- Click "Delete" on any note
- Note is immediately removed from the list and local storage

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Shashini Ahinsa**
- GitHub: [@shashiniahinsa](https://github.com/shashiniahinsa)

## 🙏 Acknowledgments

- Built with [React](https://react.dev/)
- Powered by [Vite](https://vitejs.dev/)
- Icons and styling inspiration from modern design principles

---

⭐ Star this repository if you find it helpful!
