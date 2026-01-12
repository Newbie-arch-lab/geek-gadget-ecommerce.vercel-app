# Setup Guide - GeeK-Gadget E-Commerce Website

## Quick Start

This project requires **NO installation** or **NO dependencies** - it's ready to run immediately!

## 🎯 Running the Project

### Method 1: Direct Browser (Simplest)
1. Navigate to the project folder
2. Double-click `index.html`
3. The website will open in your default browser
4. That's it! 🎉

### Method 2: VS Code/Cursor with Live Server (Best for Development)

#### Step 1: Install Live Server Extension
1. Open VS Code or Cursor
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "Live Server" by Ritwick Dey
4. Click "Install"

#### Step 2: Open the Project
1. In VS Code/Cursor, click "File" → "Open Folder"
2. Select the `geek-gadget-ecommerce.vercel-app-main` folder

#### Step 3: Start Live Server
1. Right-click on `index.html` in the file explorer
2. Select "Open with Live Server"
3. Your browser will open automatically at `http://127.0.0.1:5500`

**Benefits of Live Server:**
- Auto-refresh when you make changes
- Proper local server environment
- Better for testing and development

### Method 3: Using Python (If you have Python installed)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then open: `http://localhost:8000`

### Method 4: Using Node.js (If you have Node.js installed)
```bash
# Install http-server globally
npm install -g http-server

# Run the server
http-server
```
Then open the URL shown in the terminal (usually `http://localhost:8080`)

## 📋 System Requirements

**Minimum Requirements:**
- Any modern web browser (Chrome, Firefox, Edge, Safari, Opera)
- No additional software needed!

**For Development (Optional):**
- VS Code or Cursor (recommended code editor)
- Live Server extension (for auto-reload)

## 🔧 Recommended Extensions (Optional)

The project includes a `.vscode/extensions.json` file with recommended extensions. VS Code/Cursor will suggest these when you open the project.

### Essential Extension
- **Live Server** - For local development server with auto-reload

### Helpful Extensions (Optional)
- **Prettier** - Code formatter
- **Auto Rename Tag** - Automatically rename paired HTML tags
- **HTML CSS Support** - Better CSS support in HTML files
- **HTML CSS Class Completion** - Autocomplete CSS classes

## ✅ Verification

After opening the website, you should see:
- ✅ Promotional banner at the top
- ✅ Navigation bar with logo and menu
- ✅ Hero slider with rotating images
- ✅ Featured products section
- ✅ Shopping cart functionality
- ✅ All interactive features working

## 🌐 Browser Compatibility

The website works on:
- ✅ Google Chrome (recommended)
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari
- ✅ Opera
- ✅ Any modern browser with JavaScript enabled

## 🐛 Troubleshooting

### Website not loading?
- Make sure JavaScript is enabled in your browser
- Try a different browser
- Check browser console for errors (F12)

### Images not showing?
- Ensure you have an active internet connection (images load from Unsplash CDN)
- Check if CDN access is blocked by firewall

### Features not working?
- Clear browser cache and reload
- Make sure localStorage is enabled in browser settings
- Check browser console for JavaScript errors (F12)

## 📝 Notes

- **No build process required** - This is a static website
- **No dependencies** - Everything is included in the HTML file
- **No installation needed** - Just open and run
- **Works offline** - Once loaded, most features work offline (except CDN images)

## 🚀 Next Steps

1. Open `index.html` in your browser
2. Explore the website features
3. Test the shopping cart functionality
4. Try the search and filter features
5. Check responsiveness on different screen sizes

---

**Happy Coding! 🎉**
