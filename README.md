# MCQ Management System

A web-based MCQ (Multiple Choice Questions) management system for educational institutions with role-based access for administrators, teachers, and students.

## Features

- **Multi-role System**: Separate interfaces for admins, teachers, and students
- **Admin Panel**: User management, reports, and system settings
- **Teacher Panel**: Test creation, management, and result viewing
- **Student Panel**: Test taking, result viewing, and personal dashboard

## Project Structure

```
mcqmanagement/
├── Index.html                 # Main landing page with role selection
├── admin_1_login.html         # Admin login page
├── admin_2_register.html      # Admin registration page
├── admin_3_dashboard.html     # Admin dashboard
├── admin_4_users.html         # Admin users management
├── admin_5_reports.html       # Admin reports section
├── admin_6_settings.html      # Admin settings page
├── teacher_1_login.html       # Teacher login page
├── teacher_2_register.html    # Teacher registration page
├── teacher_3_dashboard.html   # Teacher dashboard
├── student_1_login.html       # Student login page
├── student_2_register.html    # Student registration page
├── student_3_dashboard.html   # Student dashboard
```

## Technologies Used

- HTML5
- CSS3 (with modern styling and responsive design)
- JavaScript (for basic functionality)
- Google Fonts (Inter font family)
- Font Awesome (icon library)
- Unsplash (background images)

## How to Use

1. Open `Index.html` in a web browser
2. Select your role (Admin, Teacher, or Student)
3. Use the appropriate credentials to login
4. Navigate through the role-specific dashboard

## Responsive Design

All pages are designed to be responsive and work on various screen sizes including desktop, tablet, and mobile devices.

## Security Note

This is a frontend-only implementation. All data is stored locally in the browser. For a production system, you would need to implement server-side authentication and data persistence.

## License

This project is free to use and modify.