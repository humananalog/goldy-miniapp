# Goldy - Telegram Mini App

A mobile-optimized Telegram mini app for managing gold transactions (Buy/Sell) with XGT tokens, gold weight tracking, and HKD pricing.

## Features

✨ **Optimized for Mobile**
- Compact, responsive layout that fits all screen sizes
- Touch-friendly controls with 44px minimum tap targets
- Smooth scrolling with fixed submit button

🔵🔴 **Buy/Sell Buttons**
- Large, easy-to-tap transaction type selection
- Visual feedback with gold highlight on active state
- Instant haptic feedback on Telegram-compatible devices

📅 **Interactive Calendar Picker**
- Finger-friendly date selection (36px cells)
- Month navigation with arrow buttons
- Today's date highlighted
- Selected date clearly displayed
- Responsive and works on all screen sizes

💰 **Transaction Form**
- XGT Tokens input
- Gold Weight (troy ounces) input
- Amount in HKD (Hong Kong Dollars) input
- Real-time validation with error messages
- Confirmation before submission

🎨 **Design**
- Black background with gold accents (premium feel)
- Telegram theme color integration
- Mobile-first approach
- No scroll bounce, optimal UX

## Technical Stack

- 📄 HTML5 with semantic structure
- 🎨 CSS3 with CSS Grid for calendar
- 🔧 Vanilla JavaScript (no dependencies)
- 📱 Telegram Web App SDK integration
- ⚡ Haptic feedback support

## How to Use

1. Open the mini app in Telegram
2. Select transaction type (Buy or Sell)
3. Pick a date from the calendar
4. Enter XGT tokens amount
5. Enter gold weight in troy ounces
6. Enter amount in HKD
7. Tap Submit to confirm
8. Transaction data is sent to backend

## Installation

```bash
# Clone the repository
git clone https://github.com/humananalog/goldy-miniapp.git
cd goldy-miniapp

# Deploy to Vercel or any static hosting
# Just serve the public/index.html file
```

## Recent Improvements (v2)

- ✅ Compact screen-fitting layout for mini apps
- ✅ Fixed button activation with proper event handling
- ✅ Redesigned calendar with working date selection
- ✅ Mobile touch optimizations
- ✅ Proper scrolling behavior
- ✅ Improved haptic feedback
- ✅ Reduced padding and spacing for small screens

## Browser Support

- 📱 Telegram Mobile App (iOS & Android)
- 🌐 Telegram Web
- ✅ Chrome, Safari, Firefox on mobile

## License

MIT

## Contact

For issues and feedback, please open a GitHub issue.
