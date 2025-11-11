# Mobile Numerology Calculator

A Progressive Web App (PWA) for Vedic Numerology Analysis of mobile numbers. Calculate compatibility, get detailed reports, and analyze names using the Chaldean numerology system.

## Features

✨ **Complete Numerology Analysis**
- Pairing Analysis (Step 1)
- Compound of Mobile No. Total (Step 2)
- Single Digit to PN/DN (Step 3)
- Grand Total Score Calculation

📊 **Detailed Reports**
- Two-page comprehensive report format
- Personal information section
- Name Number Calculation using Chaldean Chart
- Name alphabets matching analysis
- Print-friendly design

📱 **Progressive Web App**
- Install as mobile app
- Works offline
- Fast loading
- Responsive design for all devices

## Installation & Setup

### Option 1: GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and save
5. Your app will be available at: `https://yourusername.github.io/numerology-calculator`

### Option 2: Local Hosting

```bash
# Clone the repository
git clone https://github.com/yourusername/numerology-calculator.git
cd numerology-calculator

# Use any local server
# Python 3
python -m http.server 8000

# Node.js
npx serve

# Then open http://localhost:8000
```

## File Structure

```
numerology-calculator/
├── index.html          # Main application
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
└── README.md          # This file
```

## Installation as PWA

### On Mobile
1. Open the app in your mobile browser
2. Tap "Add to Home Screen" or "Install App"
3. Name it and install

### On Desktop (Chrome/Edge)
1. Open the app in your browser
2. Click the install icon in the address bar
3. Click "Install"

## How to Use

1. **Enter Your Details**
   - First Name (Required)
   - Middle Name (Optional)
   - Last Name (Optional)
   - Date of Birth (Required)
   - Mobile Number - 10 digits (Required)

2. **Click Calculate Now**
   - View all three steps of analysis
   - Get your total points score
   - Recommendation (≥75 = TO BE CONSIDERED)

3. **View Full Report**
   - Page 1: Analysis details
   - Page 2: Name number calculation & matching

4. **Print or Share**
   - Click "Print Report" to save as PDF
   - Calculate another number anytime

## Numerology System

This app uses the **Chaldean Numerology** system:

| Number | Letters |
|--------|---------|
| 1 | A, I, J, Q, Y |
| 2 | B, K, R |
| 3 | C, G, L, S |
| 4 | D, M, T |
| 5 | E, H, N, X |
| 6 | U, V, W |
| 7 | O, Z |
| 8 | F, P |
| 9 | O, Z |

## Scoring System

- **Step 1 (Pairing Analysis)**: 5 points per good pairing (Max 45)
- **Step 2 (Compound)**: 30 points if Friend/Neutral
- **Step 3 (Single Digit)**: 25 points if Friend/Neutral
- **Total**: Maximum 100 points

**Recommendation**: Score ≥ 75 = Mobile Number TO BE CONSIDERED

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Offline Support

The app works completely offline thanks to Service Worker caching. Once loaded, all functionality is available without internet.

## Technologies Used

- HTML5
- CSS3 (with Gradients & Flexbox)
- Vanilla JavaScript
- Service Workers
- Web App Manifest

## Development

To modify or enhance the app:

1. Edit `index.html` for UI changes
2. Modify calculations in the JavaScript section
3. Update `manifest.json` for app metadata
4. Test locally with `python -m http.server`

## License

This project is open source and available for personal and commercial use.

## Credits

Developed using Vedic Numerology principles and Chaldean numeral system.

## Support

For issues or suggestions, please create an issue in the repository.

---

**Version**: 33  
**Last Updated**: 2024  
**Status**: Production Ready