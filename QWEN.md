# TinkerQubits Foundation Website

## Project Overview

TinkerQubits Foundation is an educational technology organization focused on digital literacy, skills development, and creating opportunities for students in technology education. The website serves as a comprehensive platform showcasing their mission, programs, publications, partnerships, and impact through an interactive and visually engaging design.

The website consists of multiple interconnected HTML pages with modern CSS styling, responsive design, and JavaScript functionality. It features a well-structured navigation system with dropdown menus, gallery sections, publication showcases, and interactive elements throughout.

### Key Features:
- Responsive design that works across different device sizes
- Interactive gallery with filtering and lightbox functionality
- Publication showcase with embedded PDF viewing capabilities
- Partner and incubation organization display
- Vision and mission sections with animated elements
- Problem/solution presentation with visual imagery
- Practice platform demonstration

## Project Structure

The website has a flat file structure with HTML pages and supporting assets:

```
website/
├── indexfour.html (Main gallery page)
├── indextwo.html (Main landing page with navigation)
├── platform.html (Publications and platform showcase)
├── problem.html (Problem/solution presentation)
├── seamless/ (Subdirectory with animated pattern page)
├── 1stbook.jpg, 2ndbook.png, etc. (Book cover images)
├── IMG20250201142959.jpg, etc. (Event/gallery images)
├── logo-v3-cut-275x116.png (Website logo)
├── partner logos (various .png, .webp files)
├── PDF files (Educational content)
└── other HTML pages (.html files)
```

## Core Pages

### Main Landing Page (indextwo.html)
- Features the main navigation with dropdown menus
- Includes problem/solution sections with visual imagery
- Displays vision and mission with animated elements
- Shows publication grid and practice platform preview
- Partners and incubation organization showcase
- Responsive design with mobile menu toggle

### Gallery Page (indexfour.html)
- Interactive image gallery with category filtering
- Lightbox functionality for image viewing
- Hover effects and animations
- Statistics display showing training sessions, events, etc.

### Platform Page (platform.html)
- Displays educational publications with cover images
- Interactive PDF modal viewer
- Platform demonstration with screenshot
- Responsive grid layout for different screen sizes

### Solutions Page (problem.html)
- Problem identification with four key areas
- Interactive cards with learn more functionality
- Popup modals with detailed information
- Responsive design for all screen sizes

## Technologies Used

- **HTML5**: Semantic structure and content organization
- **CSS3**: Modern styling with flexbox, grid, animations, and responsive design
- **JavaScript**: Interactive elements, modal functionality, animations, and responsive behavior
- **Responsive Design**: Multiple breakpoints for different screen sizes
- **Accessibility**: Proper ARIA attributes, keyboard navigation support, and focus management

## Building and Running

The website is a static HTML/CSS/JavaScript project that can be run directly in a web browser:

1. **Local Development**: Simply open any HTML file in a web browser
2. **Local Server**: For full functionality (especially PDF viewing), run a local HTTP server:
   - Python: `python -m http.server 8000`
   - Node.js: `npx http-server`
3. **Production Deployment**: Upload all files to any web hosting service that supports static files

## Development Conventions

- HTML files use semantic structure with proper accessibility attributes
- CSS follows a mobile-first responsive approach with media queries
- JavaScript is embedded within HTML files with modular functions
- Image assets are optimized for web display
- PDF files are presented through modal viewers
- Consistent color scheme and typography across all pages

## Customization Points

1. **Content Updates**:
   - Update text content in HTML files
   - Replace images with new ones (maintaining same file names)
   - Add new PDF files to publications section

2. **Navigation**:
   - Modify navigation menu in the main HTML file
   - Update dropdown menu items as needed

3. **Styling**:
   - CSS is contained within each HTML file (some external styles may be added if needed)
   - Color scheme can be modified in the CSS variables/gradient definitions

4. **Functionality**:
   - JavaScript functions can be modified to change behavior
   - Modal functionality can be extended or customized

## Key Functionality

- **Image Gallery**: Filterable gallery with lightbox and keyboard navigation
- **PDF Viewer**: Modal-based PDF viewing for educational content
- **Responsive Navigation**: Mobile-friendly dropdown menus
- **Interactive Elements**: Hover effects, animations, and dynamic content
- **Accessibility**: Keyboard navigation and screen reader support

## Contact Information

- **TinkerQubits Foundation**
- Address: 7/2, Assisi Nagar, P.L Lokhande Marg, Chembur(W), Mumbai - 400089
- Phone: +91 98190 44922 | +91 8624 995979
- Email: rinsa@tinkerqubits.org | info@tinkerqubits.org