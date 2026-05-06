


#README.md 

#Michael Portfolio System

A **dynamic, database-driven professional portfolio website** designed to replace traditional CVs with a modern, interactive, and scalable web platform.


## Overview

This project is a full-stack web application that allows visitors to explore projects, learn about the developer, and make contact, while providing an **admin dashboard** for managing content dynamically.


## Features

### Public Features

* View projects dynamically from database
* Project detail pages
* Responsive modern UI
* Contact form (stored in database)
* Smooth animations and interactive design

### Admin Features

* Secure login system
* Add / Edit / Delete projects
* View user messages
* Dashboard control panel


## System Architecture

The system follows a **modular MVC-inspired structure**:

User → Router → Controller → Model → Database → View


## Project Structure

```
michael_portfolio/
│
├── assets/        # CSS, JS, images
├── components/    # Header, Navbar, Footer
├── config/        # Database and system config
├── core/          # Router, Controllers, Models
├── backend/       # API logic
├── pages/         # Public pages
├── admin/         # Admin panel
├── database/      # SQL file
├── routes/        # Route definitions
│
├── .env           # Environment variables
├── index.php      # Entry point
└── README.md
```

---

## Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Tools:** VS Code, GitHub


## Installation Guide

### 1. Clone the repository

```bash
git clone https://github.com/your-username/michael_portfolio.git
```


### 2. Move project to server directory

* For XAMPP → `htdocs/`
* For live hosting → upload via cPanel or FTP


### 3. Setup database

* Create a database in MySQL
* Import `database/portfolio.sql`


### 4. Configure environment

Create a `.env` file:

DB_HOST=localhost
DB_NAME=portfolio
DB_USER=root
DB_PASS=
```


### 5. Run the project

Open in browser:

```
http://localhost/michael_portfolio/
```


## Admin Access

```
URL: /admin
Username: admin
Password: (set in database)
```


## Database Tables

* `projects` → stores portfolio projects
* `messages` → stores contact form submissions
* `users` → admin authentication


## Future Improvements

* AI chatbot integration
* Live API monitoring dashboard
* GitHub project auto-sync
* Mobile app version


## Contributing

This is a personal portfolio project, but suggestions and ideas are welcome.


## License

This project is open-source and available under the MIT License.


## Author

**Michael**
AI Developer | Embedded Systems Enthusiast | Full-Stack Engineer


## Final Note

This project is designed to demonstrate **real-world software engineering skills**, including backend development, system architecture, and scalable design.

If you like it, consider giving it a ⭐ on GitHub!
