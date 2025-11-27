# NIT Jalandhar Research Dashboard

A comprehensive and interactive research analytics platform designed to showcase Dr. B.R. Ambedkar National Institute of Technology Jalandhar's academic excellence, research initiatives, and institutional achievements.

## 🎯 Overview

The NIT Jalandhar Research Dashboard is a modern, responsive web application that provides insights into the institute's research landscape across 9 engineering domains. It features real-time statistics, searchable research papers, faculty profiles, student achievements, and detailed analytics.

## ✨ Key Features

### 📊 Research Analytics
- Research papers across multiple domains
- Active engineering domains
- Ongoing research projects
- PhD-qualified faculty members
- Citations in 2024-25

### 🔍 Advanced Search
- Real-time search across papers, faculty, and domains
- Instant filtering of domain cards
- Quick access to research content

### 💻 Engineering Domains
1. **Computer Science & Engineering** - AI, ML, Data Science, Cybersecurity
2. **Electronics & Communication** - VLSI, Signal Processing, Embedded Systems
3. **Mechanical Engineering** - Robotics, Thermodynamics, Manufacturing
4. **Civil Engineering** - Structural, Environmental, Transportation
5. **Chemical Engineering** - Process Design, Nanotechnology, Biochemical
6. **Information Technology** - Cloud Computing, IoT, Blockchain
7. **Electrical Engineering** - Power Systems, Renewable Energy, Control
8. **Biotechnology** - Genetic Engineering, Biomedicine, Bioinformatics
9. **Mathematics & Computing** - Applied Math, Computational Math, Algorithms

### 👥 Faculty Directory
- Detailed faculty profiles with qualifications
- Research expertise and specializations
- Publication and citation records
- Student guidance information
- Contact details and social links

### 🏆 Student Achievements
- Top performing student showcase
- Research publications and awards
- JEE rankings and achievements
- Academic excellence recognition

### 📈 Analytics Dashboard
- Papers published by year
- Top domains analysis
- Average citations metrics
- International collaboration statistics

### 🎨 User Interface
- **Responsive Design** - Optimized for desktop, tablet, and mobile
- **Dark Mode Support** - Automatic detection with fallback option
- **Smooth Navigation** - Intuitive tab-based view switching
- **Animated Background** - Dynamic background slideshow
- **Glassmorphism Effects** - Modern frosted glass UI elements

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: CSS Variables for theming and spacing
- **Architecture**: Single-page application (SPA)
- **Accessibility**: WCAG compliant with semantic HTML

## 📁 Project Structure

```
├── index.html              # Main HTML file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required

## 📖 Usage

### Navigation
- **Home** - View dashboard overview and statistics
- **Engineering Domains** - Browse all 9 research domains
- **Faculty Directory** - Explore faculty profiles and expertise
- **Top Students** - View outstanding student achievements
- **Analytics** - Review research metrics and statistics

### Search Functionality
- Use the search bar to filter domain cards
- Search by domain name, keywords, or specializations
- Real-time filtering with instant results

### Domain Exploration
1. Click on any domain card
2. View subdomains and research areas
3. Browse recent research papers
4. Click papers to view faculty profiles

## 🎨 Design Features

### Color Scheme
- **Light Mode**: Professional blue and white palette
- **Dark Mode**: Dark blue and gray palette
- Both modes support 4.5:1 contrast ratio for accessibility

### Layout Components
- Responsive CSS Grid system
- Flexbox-based layouts
- Mobile-first approach
- Maximum width container (1200px)

### Animations
- Smooth transitions on hover
- Background image fadeout effects
- Card hover transformations
- Automatic background slideshow (5-second interval)

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px to 1023px
- **Mobile**: Below 768px

## 🔐 Security Features

- XSS prevention through text content handling
- External links with noopener/noreferrer
- Input validation for search functionality

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📊 Data Structure

### Domain Data Format
```javascript
{
  name: 'Domain Name',
  subdomains: ['Subdomain1', 'Subdomain2'],
  papers: [
    {
      title: 'Paper Title',
      authors: 'Author Names',
      year: 'Year',
      citations: 'Citation Count',
      faculty: 'Faculty ID'
    }
  ]
}
```

### Faculty Data Format
```javascript
{
  name: 'Dr. Name',
  title: 'Position',
  email: 'email@nitj.ac.in',
  phone: '+91-XXXXXXXXXX',
  qualification: 'PhD Details',
  experience: 'Years of Experience',
  expertise: 'Research Areas',
  publications: 'Publication Count',
  students: 'Student Guidance Info'
}
```

## 🎯 Future Enhancements

- [ ] Database integration for dynamic content
- [ ] Advanced filtering and sorting options
- [ ] Export research data (PDF, CSV)
- [ ] Student enrollment portal
- [ ] Publication submission system
- [ ] Research collaboration network visualization
- [ ] International partnership management
- [ ] Citation tracking and metrics
- [ ] Multi-language support

## 📝 Customization

### Changing Colors
Edit CSS variables in `:root` selector:
```css
:root {
  --color-primary: #1e40af;
  --color-surface: #ffffff;
  /* ... more variables ... */
}
```

### Adding New Domains
Update `domainData` object in JavaScript:
```javascript
const domainData = {
  newdomain: {
    name: 'New Domain Name',
    subdomains: ['Sub1', 'Sub2'],
    papers: [/* papers */]
  }
}
```

### Modifying Statistics
Update stat card values in the stats-grid section of HTML.

## 📄 License

This project is licensed under the MIT License - see LICENSE file for details.

## 👥 Contributors

- Website Development and Management Committee (WDMC), NIT Jalandhar
- Faculty of Research and Innovation
- Department of Computer Science & Engineering

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📞 Contact & Support

**NIT Jalandhar**
- 📍 G.T Road, Amritsar Bypass, Jalandhar, Punjab, India-144011
- 📞 +91-0181-5037855, 2690301, 2690453, 3082000
- 🌐 [Visit Website](https://www.nitj.ac.in)

**Social Media**
- 📘 [Facebook](https://facebook.com/nitjalandhar)
- 📷 [Instagram](https://instagram.com/nitjalandhar)
- 🐦 [Twitter](https://twitter.com/nitjalandhar)
- 💼 [LinkedIn](https://linkedin.com/school/nitjalandhar)
- 📺 [YouTube](https://youtube.com/@nitjalandhar)

## 📋 Changelog

### Version 1.0.0 (2025-11-27)
- Initial release
- Core dashboard functionality
- 9 engineering domains
- Faculty directory
- Student achievements showcase
- Dark mode support
- Mobile responsive design

## 🙏 Acknowledgments

- Dr. B.R. Ambedkar's vision for technical education
- NIT Jalandhar administration and faculty
- Web Development and Management Committee
- All contributing researchers and students

---

**Last Updated**: November 27, 2025  
**Developed by**: WDMC, NIT Jalandhar  
**© 2025 NIT Jalandhar. All rights reserved.**
