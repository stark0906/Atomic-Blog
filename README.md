# 📖 Atomic Blog

Atomic Blog is a React-based blogging platform that allows users to browse, search, add, archive, and unarchive blog posts. It leverages **React Hooks** and **API calls** to fetch blog data and stores user information persistently using **local storage**.

## 🚀 Features

- 🔍 **Search Blogs** – Find blogs from the available list.
- 📝 **Add Custom Blogs** – Users can create and display custom blog cards.
- 📂 **Archive/Unarchive Blogs** – Organize blogs by archiving and unarchiving them.
- 🔄 **Persistent State** – Uses **local storage** to save user data and resume from the last state.
- 🌐 **Fetch Blogs from API** – Dynamically loads blog data.

## 🛠 Tech Stack

- **Frontend:** React.js, React Hooks (useState, useEffect)
- **Data Management:** Local Storage, API Calls (Fetch/Axios)
- **Styling:** CSS/Tailwind (Optional)

## 📦 Installation

Clone the repository and install dependencies:

```sh
git clone https://github.com/yourusername/Atomic-Blog.git
cd Atomic-Blog
npm install  # or yarn install
```

## ▶️ Running the Application

```sh
npm start  # or yarn start
```

The app will be live at **http://localhost:5173/** (default Vite port).

## 🏗 Build for Production

```sh
npm run build
```

This will generate a `dist/` folder with optimized files.

## 📂 Project Structure

```
Atomic-Blog/
│── src/
│   ├── App-memo.js        # Memoized version of the app
│   ├── App-v1.js          # Previous version of the app
│   ├── App.js             # Main application component
│   ├── PostContext.js     # Context for managing posts
│   ├── Test.js            # Test component
│   ├── index.js           # Entry point
│   ├── style.css          # Global styles
│── public/                # Static assets
│── package.json           # Dependencies and scripts

```

## 🔥 Future Enhancements

- ✨ User authentication & profile management
- 🗃️ Backend integration for persistent data storage
- 🌙 Dark mode support

## 🤝 Contributing

Feel free to fork, raise issues, or create pull requests!



