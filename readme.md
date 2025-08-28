# To-Do-Er 📅

A modern, sleek weekly task manager with daily breakdown functionality. Built for professionals who need organized, weekly planning with sophisticated design and seamless cross-device synchronization.

## ✨ Features

### 📊 **Weekly Organization**
- **ISO Week System** - Monday-start weeks with proper year transitions
- **Daily Breakdown** - Monday through Friday individual sections + Weekend combined
- **Week Navigation** - Easy previous/next week browsing
- **Date Display** - Clear week dates and day-specific formatting

### 🎯 **Task Management**
- **Full CRUD Operations** - Create, Read, Update, Delete tasks
- **Progress Tracking** - Visual progress bars with percentage completion
- **Notes System** - Add detailed notes to any task
- **Completion Status** - Mark tasks complete/incomplete
- **Copy Between Days** - Duplicate tasks across days with all data preserved

### 🎨 **Modern Design**
- **Dark Glassmorphism Theme** - Contemporary UI with backdrop blur effects
- **Gradient Accents** - Day-specific color themes for visual organization
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Elegant Typography** - Playfair Display font for sophisticated appearance
- **Micro-animations** - Smooth transitions and hover effects

### 💾 **Data & Persistence**
- **localStorage Storage** - Data persists across browser sessions
- **Auto-expanding Sections** - Smart collapse/expand based on content
- **Drag & Drop** - Move tasks between days intuitively
- **Auto-save** - Changes saved immediately without manual action

### 📱 **Cross-Platform**
- **Progressive Web App** ready
- **Touch-optimized** controls for mobile devices
- **Keyboard shortcuts** - Escape to exit modes, Enter to add tasks
- **Accessibility features** - High contrast and reduced motion support

## 🚀 Live Demo

**[Try To-Do-Er Now →](https://w0rkar0und.github.io/to-do-er/)**

## 📖 How to Use

### Adding Tasks
1. Navigate to any day section (Monday-Weekend)
2. Type in the "Add task..." input field
3. Press Enter or click "Add" button
4. Task appears in that day's section

### Managing Tasks
- **Progress**: Enter percentage in number field, click "Set"
- **Complete**: Click the checkmark (✓) button
- **Copy**: Click copy button (⧉), then click target day
- **Edit**: Click edit button (✎) to modify title/notes
- **Delete**: Click delete button (✗), then click again to confirm

### Navigation
- **Week Navigation**: Use arrow buttons in header
- **Collapse Sections**: Click day headers to minimize/expand
- **Copy Mode**: Press Escape to exit copy mode

### Keyboard Shortcuts
- **Enter** - Add new task (when input focused)
- **Escape** - Exit copy mode
- **Ctrl+Shift+D** - Toggle debug mode

## 🛠️ Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with custom properties, gradients, backdrop-filter
- **Vanilla JavaScript** - No frameworks, pure JS for performance
- **Google Fonts** - Playfair Display typography
- **localStorage API** - Client-side data persistence
- **CSS Grid & Flexbox** - Responsive layout system

## 📁 Project Structure

```
to-do-er/
├── index.html          # Complete single-file application
├── README.md          # This file
└── .gitignore         # Git ignore rules (optional)
```

## 🚀 Quick Start

### Option 1: Use the Live Version
Visit **[https://w0rkar0und.github.io/to-do-er/](https://w0rkar0und.github.io/to-do-er/)** and start using immediately.

### Option 2: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/w0rkar0und/to-do-er.git
   cd to-do-er
   ```

2. Open `index.html` in your browser:
   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   
   # Using Node.js (if installed)
   npx http-server
   
   # Or simply open the file directly
   open index.html
   ```

3. Navigate to `http://localhost:8000` (if using a local server)

## 📊 Data Storage

All data is stored locally in your browser using `localStorage`. This means:
- ✅ **Private** - Your data stays on your device
- ✅ **Fast** - No network requests for task operations
- ✅ **Offline** - Works without internet connection
- ⚠️ **Browser-specific** - Data doesn't sync between different browsers/devices

### Data Structure
```javascript
{
  "2025-W34": {
    "monday": [tasks],
    "tuesday": [tasks],
    // ... other days
  }
}
```

## 🎯 Use Cases

- **Weekly Planning** - Organize tasks by specific days
- **Project Management** - Track progress on daily goals
- **Personal Productivity** - Maintain work-life balance with weekend planning
- **Team Coordination** - Visual daily task distribution
- **Habit Tracking** - Monitor recurring weekly activities

## 🔧 Customization

The app uses CSS custom properties for easy theming:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --success-gradient: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  --bg-primary: #0f0f23;
  /* ... other variables */
}
```

## 🌟 Browser Support

- **Chrome/Edge** 88+ (recommended)
- **Firefox** 87+
- **Safari** 14+
- **Mobile browsers** - iOS Safari 14+, Chrome Mobile 88+

**Required Features:**
- CSS `backdrop-filter` support
- ES6+ JavaScript features
- CSS Grid and Flexbox
- localStorage API

## 🤝 Contributing

This is a personal productivity tool, but suggestions and improvements are welcome:

1. **Issues** - Report bugs or request features via GitHub Issues
2. **Discussions** - Share use cases and workflow ideas
3. **Forks** - Feel free to fork and customize for your needs

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Typography** - [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) by Claus Eggers Sørensen
- **Inspiration** - Modern productivity apps and task management principles
- **Design** - Contemporary glassmorphism and dark UI trends

---

**Made with ❤️ for productivity enthusiasts**

*Last updated: August 2025*