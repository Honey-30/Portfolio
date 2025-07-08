# Portfolio Website

## Overview
This is a professional portfolio website built with Flask and Bootstrap. The application serves a single-page portfolio site with modern styling and responsive design. It's designed to showcase personal projects, skills, and contact information in a clean, professional layout.

## System Architecture

### Frontend Architecture
- **Template Engine**: Jinja2 (Flask's default templating engine)
- **CSS Framework**: Bootstrap 5.3.0 for responsive grid system and components
- **Styling**: Custom CSS with CSS custom properties for consistent theming
- **Typography**: Inter font family via Google Fonts
- **Icons**: Font Awesome 6.4.0 for iconography
- **JavaScript**: Vanilla JavaScript for interactive features

### Backend Architecture
- **Framework**: Flask (Python web framework)
- **Server**: Development server with debug mode enabled
- **Configuration**: Environment-based secret key management
- **Routing**: Single route serving the main portfolio page

## Key Components

### Application Structure
- `app.py` - Main Flask application with route definitions
- `main.py` - Application entry point for deployment
- `templates/index.html` - Main HTML template with navigation structure
- `static/css/style.css` - Custom styling with professional color palette
- `static/js/main.js` - Client-side interactivity and smooth scrolling

### Design System
- **Color Palette**: Professional blue-gray scheme with CSS custom properties
- **Navigation**: Fixed navbar with smooth scrolling to sections
- **Responsive Design**: Bootstrap-based responsive layout
- **Typography**: Inter font family for modern, readable text

## Data Flow

### Request Flow
1. User accesses the root URL (`/`)
2. Flask routes the request to the `index()` function
3. Function renders `index.html` template
4. Static assets (CSS, JS) are served automatically by Flask
5. Client-side JavaScript handles navigation and interactive features

### Static Asset Management
- CSS and JavaScript files served from `static/` directory
- External CDN resources for Bootstrap, Font Awesome, and Google Fonts
- Flask's `url_for()` used for generating static asset URLs

## External Dependencies

### CDN Dependencies
- **Bootstrap 5.3.0**: UI framework and responsive grid
- **Font Awesome 6.4.0**: Icon library
- **Google Fonts (Inter)**: Typography

### Python Dependencies
- **Flask**: Web framework
- **Jinja2**: Template engine (included with Flask)

## Deployment Strategy

### Development Environment
- Flask development server on host `0.0.0.0`, port `5000`
- Debug mode enabled for development
- Environment variable support for session secret

### Production Considerations
- Session secret should be set via `SESSION_SECRET` environment variable
- Debug mode should be disabled in production
- Static files can be served by web server (nginx, Apache) for better performance
- WSGI server (Gunicorn, uWSGI) recommended for production deployment

## Changelog
- July 08, 2025: Initial setup with professional portfolio template
- July 08, 2025: Enhanced with personal details from Honey Nandal's resume
- July 08, 2025: Added comprehensive animation system with multiple transition effects
- July 08, 2025: Integrated real work experience from Octanet Services and Deloitte
- July 08, 2025: Added professional color palette with formal blue-gray scheme
- July 08, 2025: Enhanced with advanced CSS animations and JavaScript interactions

## Personal Information
- **Name**: Honey Nandal
- **Location**: Rohtak, India 124021
- **Email**: honey11a13@gmail.com
- **Phone**: +91 8053291898
- **LinkedIn**: https://www.linkedin.com/in/honey-nandal-110549274
- **Education**: B.Tech CSE (AI/ML specialization) at VIT Amravati - CGPA: 8.66
- **Expected Graduation**: June 2026

## Professional Experience
1. **Intern Web Developer** - Octanet Services, Bengaluru (July-August 2024)
   - Achieved 20% reduction in bounce rate through UX/UI optimization
   - Collaborated with design teams and participated in workshops

2. **Data Analytics Job Simulation** - Deloitte, Remote (March 2025)
   - Created data dashboards using Tableau
   - Applied Excel for data classification and business insights

## Technical Skills
- **Programming**: Java (90%), Python (88%), HTML/CSS (92%)
- **AI/ML**: Machine Learning (85%), Data Analytics (80%)
- **Databases**: MySQL (82%)
- **Tools**: Tableau, Excel, Microsoft Office
- **Certifications**: Google AI Foundation, TensorFlow.js, Java Programming, Google Cloud

## Enhanced Features Added
- **Advanced Animations**: Fade, slide, flip, zoom, and rotate transitions
- **Interactive Elements**: Hover effects, pulse buttons, glow effects
- **Professional Experience Section**: Detailed work history with skill tags
- **Enhanced Portfolio Section**: Academic projects with dynamic interactions
- **Improved Contact Section**: Real contact information with enhanced form
- **Responsive Design**: Mobile-optimized with professional color scheme

## User Preferences
Preferred communication style: Simple, everyday language.