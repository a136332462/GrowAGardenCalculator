# 🌱 Grow a Garden Calculator (GAG Calculator)

[![Website](https://img.shields.io/badge/Website-https://www.gagcalculatortool.com-blue)](https://www.gagcalculatortool.com)
[![GitHub](https://img.shields.io/badge/GitHub-GrowAGardenCalculator-green)](https://github.com/a136332462/GrowAGardenCalculator)
[![Next.js](https://img.shields.io/badge/Next.js-15.3.0-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.3-38B2AC)](https://tailwindcss.com/)

## 📖 Project Overview

**Grow a Garden Calculator** is a comprehensive calculation tool website designed specifically for the "Grow a Garden" game. This tool helps players accurately calculate plant values, pet growth time, egg hatching speed, and other important game data, enabling players to make more informed gaming decisions.

### 🌟 Key Features

- 🎯 **Precise Calculations**: Based on actual game data, providing accurate calculation results
- 🌍 **Multi-language Support**: Supports Chinese, English, and Japanese
- 📱 **Responsive Design**: Perfectly adapts to desktop and mobile devices
- ⚡ **Real-time Calculation**: Input data updates calculation results instantly
- 🎨 **Modern UI**: Uses Tailwind CSS and shadcn/ui component library
- 🔧 **Multiple Layouts**: Supports both side-by-side and stacked display modes

## 🛠️ Tech Stack

### Frontend Framework
- **Next.js 15.3.0** - React full-stack framework
- **React 19.0.0** - User interface library
- **TypeScript 5.0** - Type-safe JavaScript

### Styling and UI
- **Tailwind CSS 3.4.3** - Utility-first CSS framework
- **shadcn/ui** - High-quality React component library
- **Lucide React** - Beautiful icon library
- **Framer Motion** - Animation library

### Internationalization
- **next-intl 4.0.2** - Internationalization solution

### Database and Authentication
- **Supabase** - Backend as a Service (BaaS)
- **Stripe** - Payment processing
- **Resend** - Email service

### Deployment and Infrastructure
- **Vercel** - Deployment platform
- **Cloudflare R2** - Object storage
- **Upstash Redis** - Caching service

## 🎮 Core Features

### 1. 🌿 Plant Value Calculator

This is the core feature of the website, providing comprehensive plant value calculations:

#### Plant Selection
- **100+ Plants**: Covers all plant types in the game
- **Categorized Browsing**: Organized by seed shop, events, updates, etc.
- **Search Function**: Supports Chinese and English search
- **Minimum Weight Limits**: Automatically sets minimum weight for each plant

#### Mutation System
- **50+ Mutations**: Including rainbow, gold, shocked, frozen, etc.
- **Multiplier Calculation**: Precisely calculates mutation effects on plant value
- **Conflict Detection**: Automatically handles mutually exclusive mutation combinations
- **Admin Mutations**: Supports special admin mutations
- **Search and Sort**: Sort by value, alphabetical order, or original order

#### Calculation Parameters
- **Weight Adjustment**: Weight input precise to 0.001kg
- **Quantity Settings**: Supports batch calculation of 1-200 plants
- **Friend Boost**: 0-50% friend boost settings
- **Real-time Calculation**: Input data updates results instantly

#### Result Display
- **Precise Value**: Shows calculated plant value
- **Price Range**: Toggle to display simplified number format
- **Plant List**: Save calculation results for multiple plants
- **Total Function**: Automatically calculates total value of all plants in the list

### 2. ⚡ Pet Experience Calculator

Helps players calculate the time needed for pets to grow from current level to target level:

#### Basic Settings
- **Current Age**: Pet's current level (1-100)
- **Target Age**: Desired target level
- **Experience Rate**: Real-time display of current experience gain rate

#### Experience Source Configuration
- **Owls**: Up to 8 owls, each can set individual experience/second
- **Brown Mouse**: Provides experience every 8 minutes, customizable value
- **Grey Mouse**: Provides experience every 10 minutes, customizable value
- **Starfish**: Continuously provides experience/second
- **Additional Bonuses**: Custom experience/second and percentage bonuses

#### Calculation Results
- **Experience Rate**: Shows total experience gain rate
- **Total Experience Required**: Total experience needed from current to target level
- **Growth Time**: Displays required time in seconds, hours, and days
- **Time Estimation**: Time estimation precise to 1 decimal place

### 3. 🥚 Egg Hatching Speed Calculator

Calculates egg hatching time with pet assistance:

#### Basic Parameters
- **Hatching Time**: Original hatching time (hours and minutes)
- **Speed Bonus**: Hatching speed bonus in percentage form

#### Pet Configuration
- **Kiwis**: Up to 8 kiwis, each with cooldown time and reduction time
- **Eagles**: Up to 8 eagles, each with cooldown time, reduction time, and trigger probability
- **Smart Limits**: Automatically limits total pets to 8

#### Calculation Logic
- **Real-time Simulation**: Simulates hatching progress every second
- **Pet Skills**: Calculates pet skill triggers and effects
- **Probability Calculation**: Considers eagle skill probability triggers
- **Time Saved**: Shows time saved compared to original time

### 4. ⚖️ Pet Weight Calculator

Predicts future weight at different ages based on pet's current weight and age:

#### Input Parameters
- **Current Weight**: Pet's current weight (kg)
- **Pet Age**: Current age (1-100)

#### Calculation Features
- **Key Ages**: Shows predicted weight at ages 10, 25, 50, 75, 100
- **Complete List**: View weight for all ages 1-100
- **Linear Growth**: Based on actual game growth formula
- **Approximation Notice**: Clearly marks results as approximations

### 5. 💰 Value to Weight Calculator

Reverse calculation: Calculate required plant weight based on target value:

#### Features
- **Target Value**: Input desired plant value
- **Reverse Calculation**: Calculate required weight based on currently selected plant and mutations
- **Real-time Updates**: Automatically updates calculation results when parameters are modified
- **Smart Tips**: Provides appropriate prompts when no plant or mutation is selected

## 🎨 User Interface Features

### Layout Options
- **Default Layout**: Vertically stacked card layout
- **Side-by-side Layout**: Left-right split wide-screen layout
- **Layout Memory**: Automatically saves user's layout preferences

### Interactive Experience
- **Debounced Calculation**: Avoids performance issues from frequent calculations
- **Real-time Feedback**: Instant validation and prompts for input fields
- **Keyboard Navigation**: Complete keyboard accessibility support
- **Screen Reader**: Supports accessibility access

### Visual Design
- **Theme Switching**: Supports light and dark themes
- **Gradient Background**: Beautiful gradient background effects
- **Colored Mutations**: Each mutation has unique color identification
- **Responsive Grid**: Adapts to different screen sizes

## 🌐 Multi-language Support

The website supports three languages, providing a complete localized experience:

### Supported Languages
- 🇨🇳 **Chinese** - Simplified Chinese interface
- 🇺🇸 **English** - English interface  
- 🇯🇵 **Japanese** - 日本語インターフェース

### Localized Content
- **Interface Text**: All buttons, labels, and prompt messages
- **Plant Names**: Localized names for 100+ plants
- **Mutation Names**: Localized names for 50+ mutations
- **Calculation Instructions**: Detailed function descriptions and usage guides

## 📱 Mobile Optimization

### Responsive Design
- **Mobile First**: Prioritizes mobile user experience
- **Touch Friendly**: Button sizes and spacing suitable for touch operations
- **Simplified Layout**: Automatically adjusts to single-column layout on mobile
- **Performance Optimization**: Performance optimization for mobile devices

### Mobile Features
- **Dropdown Selection**: Uses dropdown menus instead of button groups on mobile
- **Swipe Operations**: Supports swipe gesture operations
- **Virtual Keyboard**: Optimized numeric input experience
- **Offline Support**: Basic functions support offline use

## 🔧 Developer Features

### Code Quality
- **TypeScript**: Complete type safety
- **ESLint**: Code quality checking
- **Prettier**: Code formatting
- **Husky**: Git hook management

### Performance Optimization
- **Code Splitting**: On-demand component loading
- **Image Optimization**: Automatic image compression and format conversion
- **Caching Strategy**: Smart cache management
- **Bundle Analysis**: Package size analysis and optimization

### Deployment and Monitoring
- **Vercel Deployment**: Automatic deployment to Vercel platform
- **Performance Monitoring**: Integrated performance monitoring tools
- **Error Tracking**: Complete error tracking system
- **SEO Optimization**: Search engine optimization

## 🚀 Quick Start

### Requirements
- Node.js 18.0 or higher
- pnpm package manager

### Installation Steps

1. **Clone Repository**
```bash
git clone https://github.com/a136332462/GrowAGardenCalculator.git
cd GrowAGardenCalculator
```

2. **Install Dependencies**
```bash
pnpm install
```

3. **Environment Configuration**
```bash
cp .env.example .env.local
# Edit .env.local file and fill in necessary environment variables
```

4. **Start Development Server**
```bash
pnpm dev
```

5. **Access Application**
Open browser and visit [http://localhost:3000](http://localhost:3000)

### Build Production Version
```bash
pnpm build
pnpm start
```

## 📊 Project Structure

```
gagcalculator/
├── app/                    # Next.js app routes
│   ├── [locale]/          # Internationalization routes
│   ├── api/               # API routes
│   └── auth/              # Authentication related
├── components/            # React components
│   ├── home/             # Home page components
│   ├── ui/               # UI component library
│   └── shared/           # Shared components
├── lib/                  # Utility libraries
│   ├── calculator-data.ts # Calculator data
│   ├── calculator-logic.ts # Calculation logic
│   └── supabase/         # Database related
├── i18n/                 # Internationalization config
├── config/               # Configuration files
└── public/               # Static resources
```

## 🤝 Contributing

We welcome all forms of contributions! Please check the following guidelines:

### How to Contribute
1. Fork this repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Types of Contributions
- 🐛 **Bug Fixes**: Report and fix bugs
- ✨ **New Features**: Add new calculation features
- 📝 **Documentation**: Improve documentation and translations
- 🎨 **UI/UX**: Improve user interface
- ⚡ **Performance**: Performance optimization
- 🔧 **Tools**: Development tool improvements

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **@neyzu** - Mutation and multiplier data compilation
- **Grow a Garden Community** - Game data support
- **All Contributors** - Code contributions and feedback

## 📞 Contact Us

- 🌐 **Website**: [https://www.gagcalculatortool.com](https://www.gagcalculatortool.com)
- 📧 **Email**: Contact via GitHub Issues
- 🐛 **Issue Reports**: [GitHub Issues](https://github.com/a136332462/GrowAGardenCalculator/issues)

---

**Grow a Garden Calculator** - Making your garden calculations easier! 🌱✨ 