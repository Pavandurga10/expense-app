# expense-app
A 3-tier expense tracker web application deployed on AWS EC2 using Nginx, Node.js and MySQL
## Architecture
- **Frontend** - Nginx web server serving static HTML/CSS/JS
- **Backend** - Node.js REST API running on port 8080
- **Database** - MySQL storing all transaction data

## Tech Stack
- AWS EC2 (3 instances)
- Nginx
- Node.js & Express
- MySQL
- systemd (service management)
- Linux (Amazon Linux)

## Features
- Add expenses
- View all transactions
- Delete transactions
- Health check endpoint

## Deployment
- Backend runs as a non-root user (expense) for security
- Managed via systemd service for auto restart and boot startup
- Database credentials passed via environment variables

## What I Learned
- Linux server setup and management
- 3-tier application deployment
- systemd service configuration
- AWS EC2 instance management
- Security best practices (non-root users, sudo)
```

**Step 3 — Save and exit:**
```
Esc
:wq
Enter
