# Library Management System - Frontend

React frontend for the Smart Library Management System.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build
```

The app will open at [http://localhost:3000](http://localhost:3000)

## 📁 Component Structure

```
src/
├── components/
│   ├── BookForm.jsx     # Form to add new books
│   ├── BookForm.css     # Form styling
│   ├── BookList.jsx     # Display book collection
│   └── BookList.css     # List styling
├── App.jsx              # Main application component
├── App.css              # App styling
├── index.js             # React entry point
└── index.css            # Global styles
```

## 🎨 Features

- **BookForm Component** (`.jsx`)
  - Input fields for title, author, ISBN, year
  - Form validation
  - Success/error messages
  - State management with useState

- **BookList Component** (`.jsx`)
  - Responsive card layout
  - Delete functionality with confirmation
  - Empty state handling
  - Loading state

> **Note**: All React components use `.jsx` extension following strict SPA best practices. This clearly distinguishes JSX-containing files from plain JavaScript files.

- **State Management**
  - useState for form inputs and book list
  - useEffect for fetching data on mount
  - Dynamic UI updates without reload

## 📱 Responsive Design

Supports screens from 320px and above:
- Mobile: 320px - 767px
- Tablet: 768px - 1023px
- Desktop: 1024px+

## 🔗 API Integration

Frontend connects to backend at `http://localhost:5000/api`

The proxy is configured in `package.json`:
```json
"proxy": "http://localhost:5000"
```

## 🛠️ Tech Stack

- React 18
- React Hooks (useState, useEffect)
- CSS3 (Flexbox, Grid, Media Queries)
- Fetch API for HTTP requests
- **JSX Extension**: All React components use `.jsx` for strict SPA compliance
