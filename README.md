# Instagram Link Redirect - LineMan Allison

A smart redirect page that detects in-app browsers (TikTok, Instagram, Facebook, etc.) and shows instructions to open in a regular browser, otherwise automatically redirects to the target Instagram profile.

## Features

- 🔍 Detects in-app browsers from major social platforms
- 📱 Shows clear instructions with animated GIF when in-app browser is detected
- 🚀 Auto-redirects to Instagram profile when opened in regular browser
- 💅 Beautiful glassmorphic UI with custom background
- 🎯 Preserves UTM parameters and URL fragments

## Target

Redirects to: [https://www.instagram.com/thelinemangirl/](https://www.instagram.com/thelinemangirl/)

## Files

- `index.html` - Main page with detection logic and UI
- `background.png` - Custom background image
- `finger.png` - Pointer icon for instructions
- `point.gif` - Animated instruction GIF
- `vercel.json` - Vercel deployment configuration

## Deployment

### Vercel (Recommended)

1. Push this repository to GitHub
2. Import the project in [Vercel](https://vercel.com)
3. Deploy with default settings

### Netlify

1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository

## Customization

To change the redirect target, edit `index.html` line 209:

```javascript
const TARGET_URL = "https://www.instagram.com/thelinemangirl/";
```

To change the background image, replace `background.png` with your own image.

## Testing

- Add `?test=true` to the URL to preview the in-app browser view
- Add `?debug=true` to see user agent information

## License

MIT
