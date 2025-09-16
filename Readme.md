# The Angel Next Door Spoils Me Rotten - Fan Website

A fan website for the anime series "The Angel Next Door Spoils Me Rotten" (Otonari no Tenshi-sama ni Itsu no Ma ni ka Dame Ningen ni Sareteita Ken).
## About the Project

This website serves as a central hub for fans of the romantic comedy anime series. It combines informational content with interactive features to create an immersive fan experience. The site includes character profiles, episode tracking functionality, an image gallery, user reviews, and news updates.

## Technical Implementation

### Frontend Architecture
The website is built as a single-page application using vanilla HTML, CSS, and JavaScript. This approach was chosen for simplicity and fast loading times while maintaining full functionality.

### Styling Framework
Tailwind CSS v2.2.19 is used as the primary styling framework, providing:
- Utility-first approach for rapid development
- Consistent spacing and typography scales
- Responsive design utilities
- Built-in color palette and component classes

Custom CSS supplements Tailwind for:
- Complex animations and transitions
- Custom gradient backgrounds
- Interactive hover effects
- Theme switching functionality

### Typography and Fonts
Google Fonts integration provides the Poppins font family, offering:
- Multiple font weights (300, 400, 500, 600, 700)
- Modern, clean appearance
- Excellent readability across devices

## Key Features and Implementation

### Responsive Design System
The layout adapts to different screen sizes using:
- CSS Grid and Flexbox for layout structure
- Tailwind's responsive utilities (md:, lg: prefixes)
- Mobile-first design approach
- Breakpoints: 768px (tablet), 1024px (desktop)

### Interactive Components

#### Episode Progress Tracker
- Visual progress bars showing completion percentage
- Color-coded status system (green: completed, yellow: in-progress)
- Dynamic width calculation using inline styles
- Click-to-watch functionality with external links

#### Image Gallery with Modal
- Grid-based layout using CSS Grid
- Modal popup system with backdrop blur
- Event-driven image expansion
- Keyboard and click-to-close functionality

#### Theme Toggle
- CSS class-based theme switching
- Local state management for theme persistence
- Smooth color transitions across all elements
- Icon updates based on current theme

### Animation System

#### Floating Hearts Effect
- Continuous background animation using CSS keyframes
- Random positioning and timing
- Automatic cleanup to prevent memory leaks
- Configurable spawn intervals

#### Hover and Transition Effects
- Card elevation on hover using transform and box-shadow
- Smooth color transitions for interactive elements
- Scale animations for gallery images
- Fade-in effects for content loading

### Navigation Implementation
- Sticky positioning with smooth scrolling
- Mobile hamburger menu with toggle functionality
- Active section highlighting
- Smooth scroll behavior for anchor links

## Code Structure and Organization

### HTML Structure
The document follows semantic HTML5 principles:
- Proper heading hierarchy (h1, h2, h3)
- Semantic sections and navigation
- Accessible form elements
- Alt text for images

### CSS Architecture
Styles are organized into:
- Utility classes from Tailwind
- Custom component classes
- Animation keyframes
- Responsive design rules
- Theme-specific overrides

### JavaScript Functionality
Event-driven programming approach:
- Event listeners for user interactions
- DOM manipulation for dynamic content
- State management for theme and progress tracking
- Animation control and cleanup

## External Integrations

### Streaming Platform Links
Direct integration with:
- Aniwave for episode streaming
- MangaDex for manga reading
- YouTube for opening themes
- Novel Updates for light novel information

### Resource Loading
- Tailwind CSS from cdnjs.cloudflare.com
- Google Fonts API for typography

### File Structure
```
project/
├── index.html          # Main application file
├── README.md          # Project documentation
└── assets/            # External resources (if any)
```

## Developer Contact(zehaha)

- Slack: Hoshino_tls123
- WhatsApp: +20 114 734 3850
- GitHub: Tareq-Khalil

