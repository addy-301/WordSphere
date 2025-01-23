# Blogging Application

A feature-rich blogging application built using **ReactJS** and **TailwindCSS** for the frontend, with backend services powered by **Appwrite** (BaaS - Backend-as-a-Service). This application supports user authentication, user profile creation, and CRUD operations for blog posts.

---

## Features

- **User Authentication**: Secure user login and logout functionality.
- **User Profile**: Create and manage user profiles.
- **Blogging**: Create, read, update, and delete blog posts.
- **Rich Text Editing**: Create content using the **TinyMCE** text editor.
- **Responsive Design**: Fully responsive UI built with TailwindCSS.

---

## Tech Stack

### Frontend
- **ReactJS**: For building the user interface.
- **TailwindCSS**: For styling and responsive design.
- **TinyMCE**: For rich text editing.
- **React Hook Form**: For form handling and validation.
- **React Router DOM**: For client-side routing.
- **HTML React Parser**: For parsing and rendering HTML strings.
- **Redux Toolkit**: For state management.

### Backend
- **Appwrite**: A BaaS solution for handling authentication, database, and user management.

---

## Installation

### Prerequisites

Ensure you have the following installed:
- **Node.js** (>= 14.x)
- **npm** or **yarn**
- **Appwrite Server** (Refer to [Appwrite Documentation](https://appwrite.io/docs) for installation)

### Steps

1. **Clone the Repository**

   ```bash
   git clone [https://github.com/your-username/blogging-app.git](https://github.com/addy-301/WordSphere.git)
   cd WordSphere
   ```

2. **Install Dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Setup Environment Variables**

   Create a `.env` file in the root directory and add the following:

   ```env
   VITE_APPWRITE_URL=<APPWRITE_URL>
   VITE_APPWRITE_PROJECT_ID=<APPWRITE_PROJECT_ID>
   VITE_APPWRITE_DATABASE_ID=<APPWWRITE_DATABASE_ID>
   VITE_APPWRITE_COLLECTION_ID=<APPWRITE_COLLECTION_ID>
   VITE_APPWRITE_BUCKET_ID=<APPWRITE_BUCKET_ID>
   ```

4. **Run the Application**

   ```bash
   npm start
   # or
   yarn start
   ```

   The application will be available at `http://localhost:3000`.

---

## Usage

1. **Signup/Login**: Create an account or log in using existing credentials.
2. **Create Profile**: Complete your user profile.
3. **Manage Blogs**:
   - Create a new blog post.
   - Edit or delete your existing posts.
   - View all posts.

---

## Folder Structure

```
blogging-app/
├── public/               # Static files
├── src/                  # Source files
│   ├── appwrite/         # Appwrite configurations and API calls
│   │   ├── auth.js       # Authentication services
│   │   └── config.js     # Appwrite configuration settings
│   ├── components/       # Reusable components
│   │   ├── Footer/       # Footer component
│   │   ├── Header/       # Header component
│   │   ├── LogoutBtn.jsx # Logout button
│   │   ├── container/    # Container component
│   │   └── post-form/    # Post form component
│   │       └── PostForm.jsx
│   ├── pages/            # Application pages (Home, Login, Signup, etc.)
│   │   ├── AddPost.jsx   # Add post page
│   │   ├── AllPosts.jsx  # View all posts page
│   │   ├── EditPost.jsx  # Edit post page
│   │   ├── Home.jsx      # Home page
│   │   ├── Login.jsx     # Login page
│   │   ├── Post.jsx      # Single post page
│   │   └── Signup.jsx    # Signup page
│   ├── store/            # Redux store and slices
│   │   ├── authSlice.js  # Authentication slice
│   │   └── store.js      # Redux store configuration
│   ├── styles/           # CSS and Tailwind styles
│   │   ├── App.css       # Global styles
│   │   └── index.css     # Tailwind CSS
│   ├── utils/            # Utility functions
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Entry point
│   └── index.js          # Entry point for React
├── .env.sample           # Sample environment variables
├── .gitignore            # Git ignore file
├── README.md             # Documentation
├── eslint.config.js      # ESLint configuration
├── index.html            # HTML template
├── package-lock.json     # Package lock file
├── package.json          # Project dependencies
├── postcss.config.js     # PostCSS configuration
├── tailwind.config.js    # TailwindCSS configuration
└── vite.config.js        # Vite configuration
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [ReactJS](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Appwrite](https://appwrite.io/)
- [TinyMCE](https://www.tiny.cloud/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React Hook Form](https://react-hook-form.com/)
- [React Router DOM](https://reactrouter.com/)
- [HTML React Parser](https://github.com/remarkablemark/html-react-parser)

---
