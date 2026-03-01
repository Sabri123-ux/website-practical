# Project Title: Professional Portfolio Website

## Group Information
- **Student 1:** Irupaal Mohomed Sabri - ITBIN-2313-0096 - Role: Devops Engineer
- **Student 2:** T. Thusanthani - ITBIN-2211-0305 - Role: Frontend Developer
- **Student 3:** A. M. Sahjath - ITBIN-2313-0097 - Role: Frontend Developer

## Project Description
A modern, responsive portfolio website designed to showcase professional skills, projects, and contact information. This application features a clean interface with smooth animations, project showcases, and a functional contact form. Built with vanilla HTML, CSS, and JavaScript, it demonstrates best practices in web development and responsive design.

## Live Deployment
🔗 **Live URL:** https://sabri123-ux.github.io/website-practical

## Technologies Used
- HTML5, CSS3, JavaScript
- Font Awesome Icons
- GitHub Actions
- GitHub Pages

## Features
- Feature 1: Responsive Navigation Bar with smooth scrolling to all sections
- Feature 2: Interactive Skills Section with animated progress bars
- Feature 3: Working Contact Form with validation and success message

## Branch Strategy
We implemented the following branching strategy:
- `main` - Production branch
- `develop` - Integration branch
- `feature/*` - Feature development branches

## Individual Contributions

### Irupal Mohomed Sabri (Student 1 - Devops Engineer)
- Repository setup and configuration on GitHub
- GitHub Actions CI/CD pipeline implementation for automated deployment
- Deployment setup and management on GitHub Pages
- Created complete HTML structure for all sections
- Added semantic HTML5 tags for better accessibility
- Key commits: `feat: initialize HTML structure`, `ci: add GitHub Actions workflow`, `docs: create README`

### T. Thusanthani (Student 2 - Frontend Developer)
- Designed complete styling for the entire website
- Created responsive layouts using CSS Flexbox and Grid
- Developed navigation bar styling with hover effects
- Styled hero section with gradient background
- Designed skill cards and project cards with animations
- Implemented media queries for mobile responsiveness
- Key commits: `style: add base CSS styles`, `style: design navbar and hero`, `responsive: add mobile layout`

### A. M. Sahjath (Student 3 - Frontend Developer)
- Implemented smooth scrolling functionality for navigation links
- Created contact form validation with error checking
- Added "Hire Me" button functionality with alert message
- Implemented skill bar animations on scroll
- Added DOM manipulation for dynamic content updates
- Created event listeners for user interactions
- Key commits: `feat: add smooth scrolling`, `feat: implement form validation`, `feat: add button functionality`

## Setup Instructions

### Prerequisites
- Git
- Docker & Docker Compose
- Web Browser

### Installation
```bash
# Clone the repository
git clone https://github.com/Sabri123-ux/website-practical.git

# Navigate to project directory
cd website-practical

# Open index.html in your browser
start index.html  # For Windows
open index.html   # For Mac
```

### Docker Deployment
```bash
# build and run with docker-compose
docker-compose up --build -d

# visit in browser at http://localhost:8080

# to stop and remove containers
docker-compose down
```