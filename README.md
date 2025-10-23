# Financial Aid Facts vs. Myths Worksheet

An interactive educational tool designed to help students and parents separate financial aid myths from facts through an engaging quiz format.

## 📋 Overview

This project is an interactive web application that presents 10 common financial aid myths and facts in a quiz format. Users can test their knowledge, receive immediate feedback, and learn valuable information about college financial aid processes.

## ✨ Features

- **Interactive Quiz Format**: 10 carefully curated financial aid statements to test knowledge
- **Real-time Feedback**: Immediate feedback with explanations for each answer
- **Progress Tracking**: Visual progress bar and statistics tracking
- **Dark/Light Mode**: Toggle between themes for comfortable viewing
- **Auto-save Functionality**: Progress is automatically saved in browser storage
- **PDF Export**: Download results and blank templates as PDF files
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Reflection Section**: Space for users to reflect on their learning experience

## 🎯 Educational Value

The worksheet covers essential financial aid topics including:
- FAFSA completion requirements and benefits
- Income-based aid eligibility misconceptions
- Scholarship application strategies
- Student loan interest and repayment facts
- Athletic scholarship realities
- Community college financial aid options

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start taking the quiz immediately!

### Usage
1. **Take the Quiz**: Read each statement and select whether it's a MYTH or FACT
2. **Get Feedback**: Receive immediate explanations and additional insights
3. **Track Progress**: Monitor your progress with the built-in progress tracker
4. **Reflect**: Use the reflection section to process your learning
5. **Export Results**: Download your results as a PDF for future reference

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: No frameworks required
- **jsPDF**: Client-side PDF generation
- **Local Storage**: Automatic progress saving

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full feature experience with hover effects
- **Tablet**: Touch-friendly interface with adapted layouts
- **Mobile**: Streamlined design for smaller screens

## 🎨 Customization

The application uses CSS custom properties (variables) for easy theming:
- Brand colors can be modified in the `:root` selector
- Dark mode colors are defined in the `.dark-mode` class
- All transitions and animations can be customized

## 📊 Data Structure

The quiz data is stored in a JavaScript array with the following structure:
```javascript
{
    id: number,
    statement: string,
    isMyth: boolean,
    factExplanation: string,
    extraInfo: string
}
```

## 🔧 Development

### Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes to the code
4. Refresh the browser to see changes

### Adding New Questions
To add new myths/facts to the quiz:
1. Add a new object to the `mythsData` array in the JavaScript section
2. Follow the existing data structure format
3. The application will automatically include the new question

## 📄 PDF Export Features

The application includes two PDF export options:
1. **Results PDF**: Complete quiz results with performance metrics
2. **Template PDF**: Blank worksheet for offline use

## 🎓 Educational Use Cases

Perfect for:
- **High School Students**: Learning about financial aid before college
- **College Students**: Understanding their current aid packages
- **Parents**: Gaining knowledge to help their children
- **Financial Aid Counselors**: Educational tool for workshops
- **Community Organizations**: Financial literacy programs

## 🤝 Contributing

We welcome contributions to improve this educational tool:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## 📞 Support

For questions or support, please contact:
- [**My College Finance Technical Feedback Form**](https://docs.google.com/forms/d/e/1FAIpQLScyBwnqiz1L3ZOxV3C4f40jsOAW-YCw8xxfoBhPg2mgORshFA/viewform)

## 📜 License

© 2025 My College Finance. All rights reserved.

## 🙏 Acknowledgments

**Created by**: [Thiink Media Graphics](https://www.thiinkmediagraphics.com/)  
**In partnership with**: [My College Finance](https://www.mycollegefinance.com/)

---

*This educational tool is designed to help students and families make informed decisions about college financing. Always consult with financial aid professionals for personalized advice.*
