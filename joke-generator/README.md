# 🎭 Random Joke Generator

A fun, interactive web application that generates random jokes using external APIs. Perfect for getting a laugh!

## ✨ Features

- 🎲 **Random Joke Generation** - Get jokes from an external API
- 💬 **Multiple Joke Types** - Single-part and two-part jokes
- 📂 **Categories** - Programming, General, Knock-knock, etc.
- 🎯 **Joke History** - Keep track of recent jokes
- 📤 **Share Jokes** - Share to social media or copy to clipboard
- ⚙️ **Settings** - Filter by joke type and content
- 📊 **Stats** - Track laughs and jokes generated
- 📱 **Responsive Design** - Works on all devices
- 🎨 **Beautiful UI** - Modern gradient design with smooth animations

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (to fetch jokes from API)

### Installation

1. Clone or download the repository
2. Navigate to the `joke-generator` folder
3. Open `index.html` in your browser

**That's it!** No installation or dependencies needed.

## 🎮 How to Use

1. Click the **"Get a Joke"** button to generate a random joke
2. Use the **settings** to customize joke types:
   - Check "Allow 2-part jokes" for longer setups
   - Uncheck "Include NSFW jokes" for family-friendly content
3. Click **"Share 📤"** to share the joke
4. View your **recent jokes** in the history
5. Watch your **stats** update as you generate more jokes

## 🔌 APIs Used

### JokeAPI v2
- **URL**: `https://v2.jokeapi.dev/joke/Any`
- **Features**: 
  - Single and two-part jokes
  - Multiple categories
  - Content filtering (NSFW, religious, political, etc.)
  - No authentication required
  - Rate limit: Generous (1000+ requests/day)

**Example Response (Single):**
```json
{
  "error": false,
  "category": "Programming",
  "type": "single",
  "joke": "Why do Java developers wear glasses? Because they don't C#",
  "flags": {"nsfw": false, "religious": false}
}
```

**Example Response (Two-part):**
```json
{
  "error": false,
  "category": "Knock-Knock",
  "type": "twopart",
  "setup": "Knock knock",
  "delivery": "Who's there?",
  "flags": {"nsfw": false}
}
```

## 📁 Project Structure

```
joke-generator/
├── index.html          # Main HTML structure
├── joke-style.css      # Styling and animations
├── joke-script.js      # JavaScript logic
└── README.md          # Documentation (this file)
```

## 🎨 Customization

### Change Colors
Edit the CSS variables in `joke-style.css`:

```css
:root {
    --primary-color: #2563eb;      /* Change to your color */
    --accent-color: #10b981;
    --background-light: #f8fafc;
}
```

### Add More Features
In `joke-script.js`, you can:

1. **Add different joke APIs**:
```javascript
const JOKES_API = 'https://api.example.com/joke';
```

2. **Add more categories**:
```javascript
const categories = ['Programming', 'Knock-Knock', 'Dad Jokes'];
```

3. **Store jokes in localStorage**:
```javascript
localStorage.setItem('jokes', JSON.stringify(recentJokes));
```

## 📊 Statistics

The app tracks:
- 📝 Total jokes generated
- 😄 Total laughs counted (1-5 per joke)
- 📜 Last 5 jokes viewed

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| IE 11   | ⚠️ Limited |

## 🔒 Privacy

- No data is stored on servers
- No tracking or analytics
- Jokes are fetched from public API
- Your settings are local to your browser

## 🛠️ Troubleshooting

### "Failed to fetch joke" error
- Check your internet connection
- The API might be temporarily unavailable
- Try again in a few moments

### Share button not working
- Web Share API not available on your browser
- The joke will be copied to clipboard instead
- Works on: Chrome, Firefox, Safari, Edge

### No jokes found with those settings
- Try unchecking "Allow 2-part jokes"
- Or check "Include NSFW jokes"
- Some filters might be too restrictive

## 📝 License

MIT License - Feel free to use and modify!

## 🎉 Have Fun!

Generate jokes, share laughs, and enjoy! 😄

---

**Pro Tip**: Share your funniest jokes with friends using the Share button! 📤
