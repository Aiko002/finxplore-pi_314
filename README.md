# FinXplore 

**Master Financial Markets with Interactive Learning & Gamification**

Fin Quest India is a comprehensive financial education platform designed specifically for Indian investors. Learn about stocks, crypto, options trading, forex, and more through interactive modules, simulations, and gamified experiences.

![Fin Quest India](https://img.shields.io/badge/Version-1.0.0-blue) ![React](https://img.shields.io/badge/React-18.3.1-blue) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-blue) ![Firebase](https://img.shields.io/badge/Firebase-12.4.0-orange)


MADE BY - PIYUSH SINGH ( https://www.linkedin.com/in/piyush-singh-023507359?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app  )
 &        Azzah-mallick ( https://www.linkedin.com/in/azzah-mallick-6192b21b0?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app )
## Table of Contents

- [Features](#-features)
- [Tech Stack](#️-tech-stack)
- [Getting Started](#-getting-started)
- [Learning Modules](#-learning-modules)
- [Gamification System](#-gamification-system)
- [Pages & Navigation](#-pages--navigation)
- [Development](#️-development)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)

## Features

### **Comprehensive Learning Modules**
- **Stocks 101**: Master NSE/BSE fundamentals and analysis techniques
- **Crypto Fundamentals**: Navigate blockchain, wallets, and India-specific regulations
- **Options Trading**: Learn calls, puts, Greeks, and hedging strategies
- **Forex Trading**: Currency pair trading with RBI regulations
- **Scam Awareness**: Protect against fake apps and social engineering
- **Mutual Funds & SIPs**: Systematic wealth building strategies

### **Gamification System**
- **XP & Leveling**: Earn experience points and level up
- **Achievement Notifications**: Celebrate learning milestones
- **Progress Tracking**: Visual progress bars and completion status
- **Leaderboard**: Compete with other learners
- **Animated Rewards**: Engaging visual feedback

### **Interactive Features**
- **Real-time Simulations**: Practice trading without risk
- **Interactive Quizzes**: Test your knowledge with immediate feedback
- **Progress Animations**: Smooth, engaging UI transitions
- **User Profiles**: Track your learning journey
- **Community Features**: Connect with fellow learners

### **Security & Compliance**
- **Firebase Authentication**: Secure user management
- **SEBI Compliance**: India-specific financial regulations
- **Data Privacy**: User data protection
- **Secure Payments**: Safe transaction processing

## Tech Stack

### **Frontend**
- **React 18.3.1** - Modern UI framework
- **TypeScript 5.8.3** - Type-safe development
- **Vite 5.4.19** - Fast build tool and dev server
- **Tailwind CSS 3.4.17** - Utility-first styling
- **shadcn/ui** - Beautiful, accessible components

### **UI Components & Libraries**
- **Framer Motion 12.23.24** - Smooth animations
- **Recharts 2.15.4** - Data visualization
- **Radix UI** - Headless UI primitives
- **Lucide React** - Beautiful icons
- **React Hook Form** - Form management
- **React Router DOM** - Client-side routing

### **Backend & Data**
- **Firebase 12.4.0** - Authentication, database, hosting
- **TanStack Query 5.83.0** - Server state management
- **React Query** - Data fetching and caching

### **Development Tools**
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixes

## Getting Started

### Prerequisites
- Node.js 18+ and npm
- Git
- Firebase account (for authentication and data)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/piyushxt43/finxplore-pi_314.git
cd finxplore-pi_314
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication and Firestore
   - Copy your Firebase config to `src/lib/firebase.ts`

4. **Start development server**
```bash
npm run dev
```

5. **Open your browser**
   - Navigate to `http://localhost:5173`
   - Start learning! 🎉

### Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run build:dev    # Build for development
npm run preview      # Preview production build
npm run lint         # Run ESLint
```

## Learning Modules

### **Stocks 101**
- **Duration**: 45 minutes
- **Difficulty**: Beginner
- **Lessons**: 6 lessons
- **Topics**: Stock basics, NSE/BSE, charts, P/E ratios, dividends, SEBI regulations

### ₿ **Crypto Fundamentals**
- **Duration**: 65 minutes
- **Difficulty**: Beginner
- **Lessons**: 7 lessons
- **Topics**: Blockchain, wallets, DeFi, NFTs, tax rules, scam prevention

### **Options Trading**
- **Duration**: 55 minutes
- **Difficulty**: Intermediate
- **Lessons**: 5 lessons
- **Topics**: Calls/puts, strike prices, Greeks, hedging, F&O expiry

### **Forex Trading**
- **Duration**: 48 minutes
- **Difficulty**: Intermediate
- **Lessons**: 5 lessons
- **Topics**: Currency pairs, RBI rules, leverage, technical analysis

### **Scam Awareness**
- **Duration**: 70 minutes
- **Difficulty**: Beginner
- **Lessons**: 7 lessons
- **Topics**: Fake apps, wallet drains, pump & dump, social engineering

### **Mutual Funds & SIPs**
- **Duration**: 42 minutes
- **Difficulty**: Beginner
- **Lessons**: 5 lessons
- **Topics**: SIP basics, fund types, expense ratios, tax saving

## Gamification System

### **XP & Leveling**
- Earn XP for completing lessons and quizzes
- Level up based on total XP earned
- Visual progress bars and animations

### **Achievements**
- Complete modules to unlock achievements
- Special badges for different milestones
- Notification system for rewards

### **Leaderboard**
- Compete with other learners
- Rank based on total XP and modules completed
- Monthly and all-time rankings

## Pages & Navigation

- **Home**: Landing page with featured modules
- **Learn**: Browse all learning modules
- **Simulations**: Interactive trading practice
- **Leaderboard**: Community rankings
- **Regulations**: SEBI and financial regulations
- **Profile**: User progress and achievements
- **Challenges**: Special learning challenges
- **Resources**: Additional learning materials
- **Community**: Connect with other learners

## Development

### Project Structure
```
src/
├── components/          # Reusable UI components
│   ├── ui/             # shadcn/ui components
│   ├── ModuleCard.tsx  # Module display component
│   ├── Navigation.tsx  # Main navigation
│   └── ...
├── pages/              # Route components
│   ├── Index.tsx       # Home page
│   ├── Learn.tsx       # Learning modules
│   └── ...
├── data/               # Static data and content
│   ├── modules.ts      # Module definitions
│   ├── content.ts      # Lesson content
│   └── ...
├── hooks/              # Custom React hooks
├── lib/                # Utilities and configurations
└── assets/             # Images and static files
```

### Key Components
- **ModuleCard**: Displays learning modules with progress
- **AnimatedProgress**: Smooth progress animations
- **AchievementNotification**: Celebration animations
- **XPAnimation**: Experience point animations
- **Navigation**: Main app navigation

### Data Management
- **Firebase Firestore**: User data and progress
- **Local State**: React Query for caching
- **Static Content**: TypeScript interfaces for type safety

## 🚀 Deployment

### Quick Deploy to Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/piyushxt43/finxplore-pi_314)

### Quick Deploy to Netlify
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/piyushxt43/finxplore-pi_314)

### Manual Deployment

#### Vercel
```bash
npm run build
npm run deploy:vercel
```

#### Netlify
```bash
npm run build
npm run deploy:netlify
```

### Detailed Deployment Guide
For complete deployment instructions, environment setup, and troubleshooting, see [DEPLOYMENT.md](./DEPLOYMENT.md)

### Environment Variables Required
Before deploying, set these environment variables in your hosting platform:

```bash
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
VITE_FIREBASE_MEASUREMENT_ID=your_measurement_id
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow TypeScript best practices
- Use meaningful commit messages
- Test your changes thoroughly
- Update documentation as needed

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **SEBI** - For regulatory guidelines and compliance
- **NSE/BSE** - For market data and educational resources
- **Firebase** - For backend infrastructure
- **shadcn/ui** - For beautiful UI components
- **React Community** - For the amazing ecosystem

---

**Made with ❤️ for Indian Investors**

*Start your financial education journey today and become a confident investor!* 🚀

---

### 📞 Support

- 📧 Email: support@finquestindia.com
- 💬 Discord: [Join our community](https://discord.gg/finquestindia)
- 📱 Twitter: [@FinQuestIndia](https://twitter.com/finquestindia)
- 📖 Documentation: [docs.finquestindia.com](https://docs.finquestindia.com)
