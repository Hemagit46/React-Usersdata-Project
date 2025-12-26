# React User Management App with Avatars

This is a React single-page application that displays user profiles fetched from an open API. Each user profile includes an avatar, personal details, and action buttons. The application also allows creating new users using a **Create User** button. The UI is styled using **Tailwind CSS**.

---

## 📌 Features

- Fetch and display user data from an API
- Display user avatars using DiceBear Avatars
- Create new users using a **Create User** button
- Edit user details using a modal
- Like / Unlike user profiles (toggle button)
- Delete user profiles with confirmation popup
- Loading indicator while fetching data
- Responsive UI using Tailwind CSS

-------------------------------------

## 🧑‍💻 User Details Displayed

Each user profile shows:
- Avatar
- Name
- Email
- Phone
- Address
- Website
- Company name

------------------------------------

## 🎨 Avatar Integration

Avatars are generated dynamically using DiceBear based on the username.

Avatar URL format:
https://avatars.dicebear.com/v2/avataaars/{username}.svg?options[mood][]=happy

--------------------------------


## 🛠️ Technologies Used

- React
- JavaScript (ES6+)
- Tailwind CSS
- Vite
- HTML & CSS
- REST API
- Git & GitHub

- ------------------------
data/
|--data.json

react-task/
├── src/
│ ├── components/
|     |-Create.jsx
|     |-EditModal.jsx
|     |-UserProfile.jsx
│ ├── assets/
│ ├── App.jsx
│ ├── main.jsx
│ └── App.css
├── public/
├── index.html
├── package.json
├── tailwind.config.js
└── README.md

-------------------------------

## ▶️ How to Run the Project

1. Clone the repository:
   
-->git clone: " https://github.com/Hemagit46/React-Usersdata-Project.git "

2.Navigate to the project folder:

-->cd react-task

3.Install dependencies:

-->npm install

4.Start the development server:
--> npm run dev

------------------------------------------------

🚀 Future Enhancements
Backend integration
Database support
Authentication
Search and filter users
UI animations and improvements

-------------------------------------------------

👩‍💻 Author
Hemasree

--------------------------------------------------

📄 License
This project is developed for learning and practice purposes.

### ✅ After pasting, run:

git add README.md
git commit -m "Added project README"
git push





