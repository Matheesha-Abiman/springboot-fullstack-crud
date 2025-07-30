# 🧑‍💻 User Dashboard

A simple and modern web app to manage users with add, update, and delete functionality. Built with plain HTML, CSS, and JavaScript, it connects to a backend REST API.

## ✨ Features

- 👀 View all users  
- ➕ Add new users  
- ✏️ Update existing users  
- 🗑️ Delete users with confirmation prompt  
- 📱 Responsive and clean design

## 🔗 API Endpoints

The frontend expects these backend endpoints:

- `GET /getusers` — fetch all users  
- `POST /adduser` — add a new user (`{ id, name }`)  
- `PUT /updateuser` — update user (`{ id, name }`)  
- `DELETE /deleteuser` — delete user (`{ id }`)
