# Salesforce Clone

A responsive web application that replicates the core visual design and layout of Salesforce CRM using pure HTML and CSS. This project demonstrates advanced CSS techniques, responsive design principles, and modern web development practices.

## 🚀 Features

- **Authentic Salesforce UI**: Pixel-perfect recreation of Salesforce's interface design
- **Responsive Design**: Fully responsive layout that works across all devices
- **Pure CSS Implementation**: Built without JavaScript frameworks or libraries
- **Modern CSS Techniques**: Utilizes Flexbox, Grid, CSS Variables, and advanced selectors
- **Cross-browser Compatible**: Works seamlessly across all modern browsers
- **Semantic HTML**: Clean, accessible HTML structure following best practices

## 🎯 Components Included

- **Navigation Bar**: Top navigation with search functionality and user menu
- **Sidebar Navigation**: Collapsible sidebar with app launcher and menu items
- **Dashboard Layout**: Main dashboard with cards, charts placeholders, and data tables
- **List Views**: Data table layouts mimicking Salesforce list views
- **Form Layouts**: Contact/lead creation forms with Salesforce styling
- **Modal Windows**: Popup modals for actions and confirmations
- **Cards & Widgets**: Various card components and dashboard widgets
- **Responsive Tables**: Mobile-friendly data tables with horizontal scrolling

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure and accessibility
- **CSS3**: Advanced styling with modern CSS features
  - CSS Grid & Flexbox for layout
  - CSS Variables for theming
  - Media queries for responsiveness
  - CSS animations and transitions
  - Custom properties and calculations

## 📁 Project Structure

```
salesforce-clone/
│
├── index.html                 # Main dashboard page
├── css/
│   ├── styles.css            # Main styleshee
├── assets/
│   ├── images/              # Icons and images
│   └── fonts/              
└── README.md
```

## 🚀 Getting Started

### Prerequisites

No special requirements needed! This project runs in any modern web browser.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/salesforce-clone.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd salesforce-clone
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html
   # OR
   python -m http.server 8000  # For local development server
   ```

## 📱 Responsive Design

The application is fully responsive and optimized for:

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: 320px to 767px

Key responsive features:
- Collapsible sidebar navigation
- Stacked card layouts on mobile
- Horizontal scrolling tables
- Touch-friendly navigation elements

## 🎨 Design System

### Color Palette
- **Primary Blue**: #0176d3 (Salesforce brand blue)
- **Background**: #f3f2f2 (Light gray background)
- **White**: #ffffff (Cards and containers)
- **Text Gray**: #3e3e3c (Primary text)
- **Border Gray**: #dddbda (Subtle borders)

### Typography
- **Font Family**: Salesforce Sans, Arial, sans-serif
- **Heading Sizes**: 28px, 24px, 20px, 18px, 16px
- **Body Text**: 14px
- **Small Text**: 12px

## 🌟 Key CSS Features

### Advanced Layouts
```css
.dashboard-grid {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  gap: 1rem;
}

.sidebar {
  display: flex;
  flex-direction: column;
  position: sticky;
  top: 0;
}
```

### Custom Properties
```css
:root {
  --sf-blue: #0176d3;
  --sf-gray-bg: #f3f2f2;
  --sf-white: #ffffff;
  --border-radius: 4px;
  --spacing-small: 0.5rem;
  --spacing-medium: 1rem;
}
```

### Responsive Utilities
```css
@media (max-width: 768px) {
  .desktop-only { display: none; }
  .mobile-stack { flex-direction: column; }
}
```

## 🔧 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 📸 Screenshots

*Add screenshots of your application here*

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Salesforce for the original design inspiration
- CSS Grid and Flexbox specifications
- Modern web design principles and best practices

## 📞 Contact
Project Link:- https://dulcet-starship-801c22.netlify.app/

---

⭐ **Star this repo if you found it helpful!** ⭐
