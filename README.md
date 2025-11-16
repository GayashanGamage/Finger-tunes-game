# ⌨️ AI Typing Master

A modern, AI-powered typing practice application built with Vue.js that adapts to your skill level and focuses on your weak areas to improve typing proficiency effectively.

![Vue.js](https://img.shields.io/badge/Vue.js-3.x-4FC08D?logo=vue.js)
![CSS3](https://img.shields.io/badge/Styling-Pure_CSS-1572B6?logo=css3)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🚀 Features

### 🎯 Smart AI-Powered Content Generation
- **Dynamic Paragraph Creation**: AI generates unique typing content with random numbers, characters, and special symbols
- **Adaptive Difficulty**: Content complexity adjusts based on your typing performance
- **Topic-Based Practice**: Choose from various topics or let AI create custom content

### 📊 Comprehensive Performance Analytics
- **Real-time Speed Tracking**: Monitor your WPM (Words Per Minute) and accuracy
- **Detailed Error Analysis**: Identify specific keys and character combinations causing issues
- **Progress Visualization**: Track improvement over time with detailed statistics

### 🎮 Intelligent Practice System
- **Weakness-Focused Training**: Subsequent sessions automatically target your problem areas
- **Keyboard Layout Analysis**: Errors categorized by hand (left/right) and keyboard row position
- **Personalized Learning Path**: AI adapts content to address your specific typing challenges

### ⚡ User Experience
- **Clean, Minimal Interface**: Distraction-free typing environment
- **Real-time Feedback**: Instant correction highlighting and performance metrics
- **Session Timer**: Built-in timing with automatic results calculation
- **Responsive Design**: Works seamlessly across all devices

## 🛠️ Technology Stack

- **Frontend Framework**: Vue.js 3
- **Styling**: Pure CSS (No external UI libraries)
- **AI Integration**: Custom content generation algorithm
- **State Management**: Vue Composition API
- **Build Tool**: Vite

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/ai-typing-master.git

# Navigate to project directory
cd ai-typing-master

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## 🎯 How to Use

### Getting Started
1. **Launch the Application**: Open the app in your browser
2. **Choose Practice Mode**: Select a topic or let AI generate random content
3. **Start Typing**: Begin typing the generated paragraph
4. **Review Results**: Analyze your performance after completion or time expiration

### Understanding Your Results
- **Typing Speed**: WPM calculation with accuracy percentage
- **Error Distribution**: Visual breakdown of mistakes by keyboard region
- **Improvement Areas**: Specific keys and combinations recommended for practice
- **Progress Tracking**: Historical data to monitor your improvement journey

### Advanced Features
- **Weakness-Based Training**: Continue practicing to automatically focus on problem areas
- **Keyboard Heatmap**: Visual representation of your typing accuracy across the keyboard
- **Custom Sessions**: Set time limits or word count goals

## 🏗️ Project Structure

```
src/
├── components/
│   ├── TypingArea.vue      # Main typing interface
│   ├── ResultsPanel.vue    # Performance analytics display
│   ├── ContentGenerator.vue # AI content generation
│   └── ProgressTracker.vue # User progress monitoring
├── utils/
│   ├── aiGenerator.js      # AI content generation logic
│   ├── analytics.js        # Performance calculation utilities
│   └── keyboardLayout.js   # Keyboard mapping and analysis
├── styles/
│   ├── main.css           # Global styles and variables
│   └── components.css     # Component-specific styles
└── assets/
    └── keyboard-layouts/  # Keyboard visualization assets
```

## 🔧 Customization

### Adding New Topics
Modify the topic list in `src/utils/aiGenerator.js` to include your preferred practice categories.

### Adjusting Difficulty
Customize the AI content generation parameters to match different skill levels in the configuration files.

## 🤝 Contributing

We welcome contributions! Please feel free to submit pull requests, report bugs, or suggest new features.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🚀 Future Enhancements

- [ ] Multi-language support
- [ ] Competitive multiplayer mode
- [ ] Advanced AI difficulty scaling
- [ ] Integration with popular typing tests
- [ ] Social features and leaderboards

*Built with ❤️ using Vue.js and Pure CSS*
