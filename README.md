# 🎮 RecRoom Shutdown Countdown

A live countdown timer for the RecRoom game shutdown.

## Features

✨ **Live Updates** - Real-time countdown that updates every second  
🎨 **Beautiful UI** - Modern glassmorphism design with smooth animations  
📱 **Responsive** - Works perfectly on desktop, tablet, and mobile  
⚡ **Lightweight** - Pure HTML, CSS, and JavaScript (no dependencies)

## Usage

1. Open `index.html` in your web browser
2. **Important:** Edit the shutdown date in `index.html` (line 102):
   ```javascript
   const shutdownDate = new Date('2026-06-22 00:00:00 UTC').getTime();
   ```
   Replace `2026-06-22 00:00:00 UTC` with the actual RecRoom shutdown date

3. The countdown will automatically display and update every second

## Customization

- **Change the date**: Modify the `shutdownDate` variable in the script
- **Change the timezone**: Adjust the UTC time or use your local timezone
- **Customize colors**: Edit the CSS `background` and color values in the `<style>` section

## How It Works

The countdown calculates:
- **Days** remaining
- **Hours** remaining  
- **Minutes** remaining
- **Seconds** remaining

Once the shutdown date arrives, the countdown stops at 00:00:00 and displays "RecRoom has been shut down!"

## Files

- `index.html` - Complete countdown application (all-in-one file)
- `README.md` - This documentation

## Browser Support

Works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera

---

**Remember to update the shutdown date before using!** 🚀
