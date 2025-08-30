# Little Lemon Booking Website

## Project Description
The Little Lemon Booking Website is a front-end web application that allows users to easily book a table at the Little Lemon restaurant. This project was developed as part of a front-end developer capstone assignment and focuses on building a responsive and user-friendly booking experience using modern web development practices.
## Screenshots
Here are some screeenshots of the application showcasing the Booking functionality.

<img src="https://user-images.githubusercontent.com/20054991/226729651-63c82654-20d7-4783-b1a9-4c97afae96d4.png" width="400" /> <img src="https://user-images.githubusercontent.com/20054991/226729826-bf712977-9165-40e7-ab62-93cd6bf47ef7.png" width="400" /> <img src="https://user-images.githubusercontent.com/20054991/226729975-8cb4f6c3-e0f5-4271-bd8b-8a2f04bb623e.png" width="400" />

Little Lemon Restaurant - Table Booking System
A modern, responsive React web application for booking tables at the Little Lemon restaurant. This project demonstrates best practices in React development, accessibility, form validation, and responsive design.

🎯 Project Overview
This application is built based on a Figma design and implements a complete table booking system with the following features:

Responsive Design: Mobile-first approach with breakpoints for various screen sizes
Form Validation: Comprehensive form validation using React Hook Form and Yup
Accessibility: Full ARIA support and semantic HTML structure
Unit Testing: Comprehensive test coverage for all components
Modern UI/UX: Clean, intuitive interface matching the Figma design
✨ Features
🎨 Design Implementation
Header: Little Lemon logo with stylized lemon icon and leaf
Booking Form: Complete form with all required fields from the design
Restaurant Image: Visual representation of restaurant interior with table setups
Footer: Consistent branding with the header
📱 Responsive Design
Desktop: Two-column layout with form on left, image on right
Tablet: Optimized spacing and sizing
Mobile: Single-column layout with proper touch targets
✅ Form Validation
Required Fields: All fields are mandatory
Input Validation: Name and prename must be at least 2 characters
Real-time Feedback: Immediate validation feedback with error messages
Accessibility: Proper ARIA labels and error announcements
♿ Accessibility Features
Semantic HTML: Proper use of landmarks, headings, and form elements
ARIA Support: Labels, descriptions, and live regions
Keyboard Navigation: Full keyboard accessibility
Screen Reader Support: Proper labeling and announcements
🚀 Getting Started
Prerequisites
Node.js (version 16 or higher)
npm or yarn package manager
Installation
Clone the repository

git clone <repository-url>
cd template-integration
Install dependencies

npm install
Start the development server

npm start
Open your browser Navigate to http://localhost:3000

Available Scripts
npm start - Runs the app in development mode
npm test - Launches the test runner
npm run build - Builds the app for production
npm run eject - Ejects from Create React App (not recommended)
🧪 Testing
The project includes comprehensive unit tests for all components:

# Run all tests
npm test

# Run tests with coverage
npm test -- --coverage

# Run tests in watch mode
npm test -- --watch
Test Coverage
BookingForm: Form validation, submission, accessibility
Header: Rendering and semantic structure
RestaurantImage: Visual elements and layout
Footer: Branding consistency
App: Overall application integration
🏗️ Project Structure
src/
├── components/
│   ├── Header/
│   │   ├── Header.tsx
│   │   ├── Header.css
│   │   └── __tests__/
│   ├── BookingForm/
│   │   ├── BookingForm.tsx
│   │   ├── BookingForm.css
│   │   └── __tests__/
│   ├── RestaurantImage/
│   │   ├── RestaurantImage.tsx
│   │   ├── RestaurantImage.css
│   │   └── __tests__/
│   └── Footer/
│       ├── Footer.tsx
│       ├── Footer.css
│       └── __tests__/
├── App.tsx
├── App.css
└── index.tsx
🎨 Design System
Color Palette
Primary: #FFD700 (Golden Yellow)
Secondary: #228B22 (Forest Green)
Background: #FFFFFF (White)
Text: #000000 (Black)
Accent: #E0E0E0 (Light Gray)
Typography
Font Family: Arial, sans-serif
Headings: Bold, various sizes
Body Text: Regular weight, readable sizes
Spacing
Container: Max-width 1200px
Padding: 20px base, responsive adjustments
Gaps: 15px-60px between elements
📱 Responsive Breakpoints
Desktop: 1024px and above
Tablet: 768px - 1023px
Mobile: 480px - 767px
Small Mobile: Below 480px
♿ Accessibility Compliance
WCAG 2.1 AA standards
Semantic HTML structure
ARIA labels and descriptions
Keyboard navigation support
Screen reader compatibility
Color contrast compliance
🔧 Technologies Used
React 18 - Modern React with hooks
TypeScript - Type safety and better development experience
React Hook Form - Efficient form handling
Yup - Schema validation
CSS3 - Modern styling with Flexbox and Grid
Jest - Testing framework
React Testing Library - Component testing utilities
📋 Evaluation Criteria Met
✅ Design and UX/UI Implementation: Complete Figma design integration ✅ Accessibility Tags: Full ARIA support and semantic HTML ✅ Unit Tests: Comprehensive test coverage for all components ✅ Functional Booking Form: Complete form with validation ✅ Semantics and Responsiveness: Proper HTML structure and mobile-first design ✅ Git Repository: Project committed to version control

🚀 Deployment
Build for Production
npm run build
The build folder contains the production-ready application.

Deploy to Netlify/Vercel
Connect your Git repository
Set build command: npm run build
Set publish directory: build
Deploy automatically on push
🤝 Contributing
Fork the repository
Create a feature branch
Make your changes
Add tests for new functionality
Ensure all tests pass
Submit a pull request
