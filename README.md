# Webcode-Agency-Website

A modern, responsive agency website built with React, Vite, Tailwind CSS, and Firebase. This project showcases a professional digital agency portfolio with a clean design, smooth user experience, and powerful backend integration.

## 🌟 Features

- **React 18**: Modern JavaScript library for building user interfaces.
- **Vite Build Tool**: Lightning-fast development server and optimized production builds.
- **Tailwind CSS + DaisyUI**: Utility-first CSS framework with beautiful pre-built components.
- **Mock Authentication**: Integrated context-based authentication system with persistent sessions.
- **Responsive Design**: Fully responsive layout that works across all devices.
- **Modern UI/UX**: Clean and professional interface with smooth animations and glassmorphism effects.
- **Analytics Dashboard**: User-protected dashboard with interactive data visualization using Recharts.


## 📁 Project Structure

```text
Webcode-Agency-Website/
│
├── public/                       # Static assets
│   ├── logo.png                  # Agency logo/favicon
│   └── images/                   # Public images
│       ├── blogs/                # Blog post images
│       └── authors/              # Author profile images
│
├── src/                          # Source files
│   │
│   ├── assets/                   # Project assets
│   │   └── rocket-icon.png       # Error page icon
│   │
│   ├── components/               # Reusable React components
│   │   ├── ErrorPage.jsx         # 404 error page component
│   │   ├── Footer.jsx            # Footer component with newsletter
│   │   ├── HeadingSection.jsx    # Reusable heading section
│   │   ├── Login.jsx             # Login form with social auth
│   │   ├── Navbar.jsx            # Navigation bar component
│   │   └── Register.jsx          # Registration form
│   │
│   ├── context/                  # React Context providers
│   │   └── AuthContext.jsx       # Authentication context & provider
│   │
│   ├── firebase/                 # Firebase configuration
│   │   └── firebase.config.js    # Firebase initialization
│   │
│   ├── pages/                    # Page components
│   │   ├── blogs/
│   │   │   └── Blogs.jsx         # Blog listing page
│   │   ├── dashboard/
│   │   │   └── Dashboard.jsx     # User dashboard (protected)
│   │   └── home/
│   │       ├── CompanyLogos.jsx  # Company Logo Showcase page
│   │       ├── FAQs.jsx          # FAQS Showcase page
│   │       ├── HeroSection.jsx   # Hero page
│   │       ├── Home.jsx          # Main landing page
│   │       ├── Newsletter.jsx    # News Letter page
│   │       ├── Pricing.jsx       # Pricing plans page
│   │       ├── Services.jsx      # Services showcase page
│   │       ├── TeamSection.jsx   # Team showcase page
│   │       ├── Testimonials.jsx  # Testimonials showcase page
│   │       └── ToolsSection.jsx  # Tools showcase page
│   │
│   ├── routes/                   # Route protection
│   │   └── PrivateRoute.jsx      # Protected route wrapper
│   │
│   ├── App.css                   # App-specific styles & animations
│   ├── App.jsx                   # Main App component with layout
│   ├── index.css                 # Tailwind CSS imports
│   └── main.jsx                  # Application entry point & routing
│
├── .gitignore                    # Git ignore rules
├── eslint.config.js              # ESLint configuration
├── index.html                    # HTML entry point
├── package.json                  # Dependencies and scripts
├── package-lock.json             # Locked dependency versions
├── postcss.config.js             # PostCSS configuration
├── tailwind.config.js            # Tailwind CSS configuration
├── vercel.json                   # Vercel deployment configuration
├── vite.config.js                # Vite build configuration
└── README.md                     # Project documentation

```

## 🎯 Key Features Implemented

### 1. Authentication System
- Email/Password simulation for registration and login.
- Protected routes for authenticated users (Dashboard).
- Context-based state management.
- Session persistence using LocalStorage.

### 2. Form & UI Libraries
- **React Hook Form 7.54.2**: Performant form validation
- **React 18**: Beautiful alert/modal popups
- **React 18**: Popular icon library


### 3. Development Tools
- **ESLint**: Code linting and quality assurance
- **PostCSS**: CSS transformation and optimization
- **Autoprefixer**: Automatic vendor prefixing

## 📝 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Mahfuz**
- GitHub: [@mdmahfuz307](https://github.com/mdmahfuz307)

---
Built with ❤️ using React, Vite, and Tailwind CSS.
