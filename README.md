# DIU-ALUMNI-WEB-PORTAL
Key Features:
For Unregistered Users:

Home Page with portal overview and statistics
Registration with full profile details
Login functionality

For Registered Users:

Profile Management - Update personal information, bio, company details
Skills Management - Add/remove skills with tags
Social Links - Add LinkedIn, GitHub, Facebook profiles
Polls - Participate in community polls
Alumni Directory - Search and view other alumni
Password Change - Secure password update
Account Deletion - Delete account option

For Admin Users:

Admin Dashboard with statistics
Create Posts - Share announcements with community
Alumni Management - Search, view details, delete accounts
Email System - Send emails to all alumni, recent graduates, or specific users
User Statistics - Track total alumni, active users, etc.

Technical Features:

Responsive Design - Works on all devices
Modern UI - Glassmorphism design with gradients and animations
In-Memory Storage - Simulated database functionality
Form Validation - Comprehensive input validation
Search Functionality - Real-time search for alumni
Role-Based Access - Different features for users vs admins

Default Accounts:

Admin: admin@diu.edu.bd / admin123
User: sarah@example.com / user123

The portal is fully functional with a beautiful, modern interface. Users can register, login, manage their profiles, participate in polls, and connect with other alumni. Admins have full control over the system with additional management capabilities.

Programming Languages Used:
Frontend:

HTML5 - Structure and markup
CSS3 - Styling, animations, responsive design, gradients, glassmorphism effects
JavaScript (Vanilla JS) - All interactive functionality, form handling, user management

Current Backend:

None - This is currently a frontend-only application
All data is stored in-memory using JavaScript variables
No server-side processing

Current Database:

None - Uses in-memory JavaScript objects/arrays to simulate database functionality
Data is lost when you refresh the page (not persistent)

Limitations of Current Approach:

No Data Persistence - All data is lost on page refresh
No Real Authentication - Security is simulated
No Real Email Sending - Email functionality is mocked
Single User Session - No multi-user support
No File Uploads - Cannot handle profile pictures, documents
