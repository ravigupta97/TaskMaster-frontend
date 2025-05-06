# 📋 TaskMaster Frontend

TaskMaster Frontend is a responsive and user-friendly web interface that interacts with the TaskMaster Backend API to manage user tasks efficiently. Built using plain HTML, CSS, and JavaScript, this frontend handles user authentication, task creation, updates, analytics, and more.

---

## 🌐 Live Demo

🟢 **Frontend**: [https://your-frontend-url.netlify.app](https://your-frontend-url.netlify.app)  
🟢 **Backend API**: [https://smart-task-manager-backend.onrender.com](https://smart-task-manager-backend.onrender.com/))

---

## 🚀 Features

- 🔐 JWT-based user authentication
- 📝 Add, edit, delete tasks
- 📊 Task analytics dashboard for admins
- 👤 Role-based navigation (User/Admin)
- 📱 Responsive design (mobile-friendly)
- 🌈 Smooth UI animations and transitions

---

## 📁 Folder Structure

```text
TaskMaster-frontend/
├── assets/               # Images, icons, and fonts
├── css/                  # Stylesheets
│   └── style.css         # Main styling
├── js/                   # Scripts
│   ├── main.js           # UI interaction & navigation logic
│   ├── login.js          # Login functionality
│   ├── register.js       # Signup logic
│   ├── tasks.js          # Task management logic
│   ├── analytics.js      # Admin analytics chart rendering
│   └── utils.js          # Utility methods (token handling, API calls)
├── index.html            # Landing page
├── login.html            # Login page
├── register.html         # Registration page
├── dashboard.html        # User dashboard
├── admin.html            # Admin analytics page

```
## 📦 Deployment

This frontend is deployed on [Netlify](https://www.netlify.com/). To deploy your own:

1. Push the frontend repo to GitHub.
2. Go to [app.netlify.com](https://app.netlify.com).
3. Click **"New site from Git"**.
4. Connect your GitHub repo and follow the setup steps.
5. Add a `_redirects` file in the root directory as shown above to handle API proxying.

---

## 🔐 Authentication Flow

- On login/register: JWT token is stored in `localStorage`.
- All authenticated requests include the header:  
  `Authorization: Bearer <token>`
- Navigation options dynamically change based on the user's role (e.g., User vs Admin).

---

## 📷 Screenshots

> *(Include screenshots or GIFs here showing the login page, user dashboard, and admin analytics view)*

---

## 📂 Backend Repo

🔗 **[TaskMaster Backend GitHub Repository](https://github.com/ravigupta97/TaskMaster-backend)**

---

## 🧑‍💻 Author

**Ravi Gupta**  
💼 [GitHub Profile](https://github.com/ravigupta97)

