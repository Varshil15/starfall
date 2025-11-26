# 🎮 Starfall - Minecraft Survival Server Website

A modern, fully responsive website for your Minecraft survival server built with HTML, CSS, and JavaScript.

## ✨ Features

### 🎨 Design & UI
- **Modern Gaming Aesthetic**: Premium colors with Minecraft/gaming vibes
- **Dark/Light Mode Toggle**: Persistent theme preference saved in localStorage
- **Smooth Animations**: Hover effects, transitions, and scroll animations
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Clean & Professional**: Attractive layout with intuitive navigation

### 🧭 Navigation
- Sticky navbar with smooth scroll to sections
- Hamburger menu for mobile devices
- "Join Discord" button prominently displayed
- Active section highlighting

### 🏠 Home Section
- Hero section with server logo
- Engaging tagline and call-to-action buttons
- "Copy Server IP" functionality
- Server statistics display (players, uptime, protection)
- Animated scroll indicator

### 🛒 Store Section
Three main categories with multiple items:

#### **Ranks** (4 items)
- VIP Rank - $4.99
- VIP+ Rank - $9.99
- MVP Rank - $19.99
- Elite Rank - $34.99

#### **Crate Keys** (4 items)
- Common Key - $1.99
- Rare Key - $3.99
- Epic Key - $7.99
- Legendary Key - $14.99

#### **Tags** (6 items)
- Lightning Tag - $2.49
- Dragon Tag - $2.49
- Love Tag - $2.49
- Warrior Tag - $2.49
- Mystic Tag - $2.49
- Frost Tag - $2.49

**Purchase System**: Modal popup directing users to DM admin on Discord

### 📜 Rules Section
Three comprehensive rule categories:
1. **Playing on the Server**: Anti-cheat, griefing, exploits, etc.
2. **In-Game Chat Rules**: Spam, harassment, language guidelines
3. **Discord Server Rules**: TOS compliance, NSFW, channel usage

### 🎯 Additional Features
- **Scroll-to-Top Button**: Appears after scrolling down
- **Purchase Modal**: Professional popup for store purchases
- **Smooth Scrolling**: Between sections via navigation
- **Parallax Effects**: Hero section background animation
- **Intersection Observer**: Fade-in animations on scroll
- **Custom Scrollbar**: Themed scrollbar design
- **Console Easter Eggs**: Fun messages for developers

## 🚀 Quick Start

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize Server IP**: Edit `script.js` line 84 to change the server IP:
   ```javascript
   const serverIP = 'play.starfall.net'; // Change this
   ```
3. **Update Discord Admin**: Edit `index.html` line 496 to change the Discord username displayed in the purchase modal

## 🎨 Customization Guide

### Change Colors
Edit the CSS variables in `styles.css` (lines 4-35):
```css
:root {
    --primary-color: #00d4ff;
    --secondary-color: #7b2cbf;
    --accent-color: #ff006e;
    /* ... more colors */
}
```

### Update Store Items
Edit `index.html` in the Store Section:
- Change item names, descriptions, and prices
- Add/remove items by copying the `.store-item` div structure
- Update icons using [Font Awesome icons](https://fontawesome.com/icons)

### Modify Rules
Edit `index.html` in the Rules Section:
- Add/remove rules in each category
- Customize the warning message at the bottom

### Change Server Logo
Replace `logo.jpg` with your server's logo (recommended size: 512x512px)

## 📱 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔗 Important Links to Update

1. **Discord Invite**: Currently set to `https://discord.gg/XpXS7DxP92`
   - Update in `index.html` (appears multiple times)
2. **Server IP**: Edit in `script.js` line 84
3. **Discord Admin Username**: Edit in `index.html` line 496

## 📂 File Structure

```
Starfall/
├── index.html      # Main HTML structure
├── styles.css      # All styling and animations
├── script.js       # JavaScript functionality
├── logo.jpg        # Server logo
└── README.md       # This file
```

## ⚙️ Configuration

### Dark/Light Mode
The theme preference is automatically saved in the browser's localStorage. Users can toggle between themes using the button in the navigation bar.

### Mobile Responsiveness
The site automatically adjusts for different screen sizes:
- **Desktop**: Full navigation bar with all links
- **Tablet**: Adjusted grid layouts
- **Mobile**: Hamburger menu, stacked layouts

## 🎯 Features Breakdown

### JavaScript Functionality (`script.js`)
- Theme toggle with localStorage persistence
- Hamburger menu for mobile navigation
- Smooth scrolling to sections
- Copy server IP to clipboard
- Purchase modal popup system
- Scroll-to-top button
- Scroll animations with Intersection Observer
- Parallax effects
- Active navigation highlighting
- Dynamic copyright year

### CSS Features (`styles.css`)
- CSS custom properties for theming
- Responsive grid layouts
- Hover effects and transitions
- Gradient backgrounds
- Custom scrollbar styling
- Modal animations
- Card hover effects
- Media queries for all screen sizes

## 💡 Tips

1. **Performance**: All resources are optimized for fast loading
2. **SEO**: Add meta descriptions and keywords in the `<head>` section
3. **Analytics**: Add Google Analytics or similar by inserting the tracking code before `</head>`
4. **Favicon**: Add a favicon by placing `favicon.ico` in the root directory and adding:
   ```html
   <link rel="icon" type="image/x-icon" href="favicon.ico">
   ```

## 🐛 Troubleshooting

**Issue**: Logo not displaying
- **Solution**: Ensure `logo.jpg` is in the same directory as `index.html`

**Issue**: Theme not persisting
- **Solution**: Check browser localStorage is enabled

**Issue**: Hamburger menu not working
- **Solution**: Ensure JavaScript is enabled in the browser

**Issue**: Store items not aligned
- **Solution**: Clear browser cache and reload

## 📞 Support

For questions or issues with this website template:
- Discord: https://discord.gg/XpXS7DxP92

## 🎉 Credits

- **Fonts**: Google Fonts (Poppins, Orbitron)
- **Icons**: Font Awesome 6.4.0
- **Design**: Custom gaming-themed design for Minecraft servers

---

**Made with ❤️ for the Minecraft community**

Enjoy your new server website! 🎮✨
