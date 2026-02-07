# FitLife Gym Management System (Final Project)

Welcome to the FitLife Gym repository. This project is a hybrid/polyglot database upgrade (MySQL + MongoDB)

## 👥 The Team & Roles
| Role | Assigned To | Branch Name |
| :--- | :--- | :--- |
| **Project Lead / Back-end** | Lance Gabriel Buncab | `backend/api-logic` |
| **Front-end** | Sheryn Mae Abril | `frontend/ui-design` |
| **Back-end (API/PHP)** | Rehan Rafael Recto, Jan Samuel Sultan | `backend/api-logic` |
| **Database (MySQL/MongoDB)**| Klein Vincent De Guzman, Karol Joy Ronquillo | `database/hybrid-setup` |
| **Documentation** | Charl Christopher Peñada | Overall Oversight |

---

## 🌿 Branching Workflow
To prevent code conflicts, we are using a **Role-Based Branching** strategy. 

1. **Check out your branch:** Go to the branch selector on GitHub or run `git checkout [your-branch-name]` in your terminal.
2. **Work in your folder:** Only edit files within your assigned directory (e.g., Sheryn works in `frontend/ui-setup`).
3. **Commit & Sync:** Once your feature is working, commit your changes with a clear message and **Sync/Push** them to GitHub.
4. **Integration:** Periodically, we will merge all role-branches into the `develop` branch for testing.

---

## 📁 Repository Structure
```text
fitlife-gym-management-system/
├── app-frontend/      # HTML, CSS, JS, and Vue.js files (Sheryn)
├── app-backend/       # PHP API logic (Lance, Rehan, Jan)
│   ├── config/        # Database connection settings
│   ├── controllers/   # Route handling
│   └── models/        # Data logic (SQL & NoSQL)
└── database/          # SQL scripts & MongoDB collection structures (Klein, Karol)
