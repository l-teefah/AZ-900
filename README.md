# ☁️ AZ-900 Azure Fundamentals Study Hub

An interactive web-based study platform for Microsoft Azure AZ-900 certification preparation. This repository contains comprehensive quiz materials and a 
modern study interface to help master Azure fundamentals, I used it to prepare and study when I took AZ-900 exam, my notes can also be accessed [here](https://github.com/l-teefah/AZ-900/blob/main/MS%20AZ-900.pdf).


## 🚀 Live Demo

Access the study hub [here](https://l-teefah.github.io/AZ-900/)


## 📚 What's Included

### [Interactive Study Hub](index.html)
- **🕐 Pomodoro Study Timer** - Built-in timer with 15/25/45 minute presets
- **📊 Progress Tracking** - Visual progress bars for each quiz section
- **📈 Study Statistics** - Real-time tracking of study sessions, time spent, and streaks
- **🏆 Achievement System** - Completion badges and motivation features
- **📱 Responsive Design** - Works perfectly on desktop, tablet, and mobile

### Quiz Sections
1. [**Azure Fundamentals**](General_quiz.html)
   - Core cloud computing concepts
   - Azure architecture basics
   - Foundational knowledge

2. [**Architecture & Services**](AZ-900_Architecture&Services_Quiz.html)
   - Azure compute services
   - Storage solutions
   - Database services
   - Networking fundamentals

3. [**Azure Networking**](AZ-900_Networking_Quiz.html)
   - Virtual networks (VNets)
   - Load balancers and gateways
   - Network security
   - Connectivity solutions


## 🎯 Features

### Study Timer
- **Pomodoro Technique Support** - Default 25-minute study sessions
- **Flexible Timing** - Choose between 15, 25, or 45-minute sessions
- **Automatic Progress Tracking** - Time spent studying is tracked automatically
- **Session Completion Rewards** - Celebrate completed study sessions

### Progress Management
- **Visual Progress Bars** - See your completion percentage for each section
- **Study Streak Counter** - Track consecutive days of study
- **Time Tracking** - Monitor time spent on each section
- **Achievement Badges** - Unlock completion rewards

### User Experience
- **Modern Azure-themed Design** - Professional Microsoft Azure color scheme
- **Smooth Animations** - Engaging hover effects and transitions
- **Mobile Responsive** - Study anywhere on any device
- **Intuitive Navigation** - Easy switching between quiz sections


## 🛠️ Setup Instructions

### Option 1: GitHub Pages (Recommended)
1. **Fork or Download** this repository
  
2. **Upload files** to your GitHub repository:
   ```
   📁 Your Repository
   ├── index.html
   ├── General_quiz.html
   ├── AZ-900_Architecture&Services_Quiz.html
   └── AZ-900_Networking_Quiz.html
   ```
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Click Save
     
4. **Access your site** at `https://yourusername.github.io/repository-name`

### Option 2: Other Hosting Platforms
- **Netlify**: Drag and drop the entire folder onto netlify.com
- **Vercel**: Connect your GitHub repository to Vercel
- **Surge.sh**: Use command line `surge` in your project folder


## 📖 How to Use

1. **Start at the Hub** - Open `index.html` to access the main study interface
2. **Set Study Goals** - Use the built-in timer for focused study sessions
3. **Take Quizzes** - Click "🚀 Start Quiz" for any section you want to study
4. **Track Progress** - Watch your progress bars fill up as you complete sections
5. **Mark Completion** - Use "✅ Mark Complete" when you finish a section
6. **Build Streaks** - Study daily to build your study streak counter


## 🎓 Study Tips

- **Use the Pomodoro Technique**: Study for 25 minutes, then take a 5-minute break
- **Complete sections in order**: Start with Fundamentals, then Architecture & Services, then Networking
- **Track your time**: Use the timer to stay focused and build consistent study habits
- **Review regularly**: Come back to completed sections for reinforcement
- **Set daily goals**: Aim for at least one 25-minute study session per day


## 🔧 Customization

### Adding New Quiz Sections
1. Create a new HTML quiz file
2. Add a new section card in `index.html`
3. Update the JavaScript arrays to include the new section
4. Add progress tracking for the new section

### Modifying Timer Settings
Edit the timer presets in the JavaScript section:

```javascript
// Change default timer duration
let timeLeft = 25 * 60; // 25 minutes in seconds

// Add new timer preset buttons
<button class="btn btn-secondary" onclick="setTimer(60)">60 min</button>
```

### Styling Changes
- Colors and themes can be modified in the CSS section
- The Azure color scheme uses `#0078d4` as the primary color
- Responsive breakpoints are set for mobile devices


## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers


## 🤝 Contributing

Feel free to contribute improvements:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request


## 📄 License

This project is open source and available under the [MIT License](LICENSE).


## 🎯 About AZ-900

The Microsoft Azure Fundamentals (AZ-900) exam is designed for candidates who want to demonstrate foundational knowledge of cloud services and how those services are provided with Microsoft Azure. This study hub covers all major exam domains:

- **Cloud Concepts** (25-30%)
- **Azure Services** (35-40%)
- **Security, Privacy, Compliance, and Trust** (25-30%)
- **Azure Pricing and Support** (25-30%)


## 📞 Troubleshooting

If you encounter any issues or have suggestions:
- Open an issue in this repository
- Check that all HTML files are in the same directory
- Ensure your web server supports static HTML files

---

**Good luck with your AZ-900 certification! ☁️🚀**

