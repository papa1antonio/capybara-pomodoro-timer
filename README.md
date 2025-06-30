# 🦫 Capybara Pomodoro Timer

A beautiful and productive Pomodoro timer featuring our calm capybara friend. Built with React, TypeScript, and Tailwind CSS.

## ✨ Features

- 🍅 **Classic Pomodoro Technique**: 25-minute work sessions with 5-minute breaks
- 🎯 **Task Management**: Built-in todo list with points system
- 🏆 **Gamification**: Earn points and unlock achievements
- 🦫 **Adorable Companion**: Capybara buddy to keep you motivated
- 🎨 **Beautiful Themes**: 4 stunning themes (Zen Garden, Space Mission, Cozy Café, Gamer Zone)
- 🌍 **Multi-language**: Support for English, Portuguese, and Spanish
- 📊 **Progress Tracking**: Leaderboard and session statistics
- 🔗 **Social Sharing**: Share achievements on Reddit and other platforms
- 📱 **Responsive Design**: Works perfectly on all devices

## 🚀 Live Demo

Visit the live application: [Capybara Pomodoro Timer](https://your-netlify-url.netlify.app)

## 🛠️ Technology Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Deployment**: Netlify
- **API Integration**: Axios for Reddit sharing

## 📦 Installation & Development

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/capybara-pomodoro-timer.git
cd capybara-pomodoro-timer
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

4. **Open in browser**
Navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

## 🌐 Deployment Instructions

### Deploy to Netlify

#### Method 1: GitHub Integration (Recommended)

1. **Push to GitHub**
```bash
# Initialize git repository (if not already done)
git init
git add .
git commit -m "Initial commit: Capybara Pomodoro Timer"

# Create new repository on GitHub, then:
git remote add origin https://github.com/yourusername/capybara-pomodoro-timer.git
git branch -M main
git push -u origin main
```

2. **Connect to Netlify**
   - Go to [Netlify](https://netlify.com)
   - Click "New site from Git"
   - Connect your GitHub account
   - Select your repository
   - Configure build settings:
     - **Build command**: `npm run build`
     - **Publish directory**: `dist`
   - Click "Deploy site"

#### Method 2: Manual Deploy

1. **Build the project**
```bash
npm run build
```

2. **Deploy to Netlify**
   - Go to [Netlify](https://netlify.com)
   - Drag and drop the `dist` folder to the deploy area
   - Your site will be live instantly!

### Environment Variables (Optional)

If you want to customize Reddit integration:

1. In Netlify dashboard, go to Site settings > Environment variables
2. Add any custom configuration variables

## 🎮 How to Use

1. **Set Your Tasks**: Add tasks to the todo list to stay organized
2. **Choose Your Theme**: Select from 4 beautiful themes to match your mood
3. **Select Language**: Switch between English, Portuguese, and Spanish
4. **Start Focusing**: Click start to begin a 25-minute work session
5. **Take Breaks**: Enjoy guided break messages and watch your capybara buddy
6. **Earn Points**: Complete sessions and tasks to climb the leaderboard
7. **Share Success**: Share your achievements on Reddit and social media

## 🏆 Points System

- **Work Session Complete**: 25 points
- **Break Complete**: 10 points  
- **Task Completed**: 10 points
- **Task Added**: 5 points
- **Achievements**: Bonus points for milestones

## 🎨 Themes

- **Zen Garden**: Peaceful and calming environment
- **Space Mission**: Futuristic space exploration theme
- **Cozy Café**: Warm and comfortable coffee shop atmosphere
- **Gamer Zone**: Vibrant gaming-inspired design

## 🌍 Supported Languages

- 🇺🇸 English
- 🇧🇷 Português (Portuguese)
- 🇪🇸 Español (Spanish)

## 🔧 Configuration

### Reddit Integration

The app includes Reddit sharing functionality. To customize:

1. Edit `src/utils/redditApi.ts`
2. Update the `REDDIT_CONFIG` object with your settings
3. The app uses a manual sharing approach (opens Reddit in new tab) to avoid CORS issues

### Adding New Themes

1. Add new theme data to `src/data/themes.ts`
2. Include background image URL and capybara buddy image
3. Define color scheme for the theme

### Adding New Languages

1. Add translation data to `src/data/translations.ts`
2. Include all required translation keys
3. Add language option to the languages array in `App.tsx`

## 📱 Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Pomodoro Technique® by Francesco Cirillo
- Beautiful capybara images from various sources
- Inspiration from the productivity community
- Built with love for focused work and cute capybaras! 🦫

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/capybara-pomodoro-timer/issues) page
2. Create a new issue with detailed description
3. Join our community discussions

---

**Happy focusing with your capybara buddy! 🦫✨**
