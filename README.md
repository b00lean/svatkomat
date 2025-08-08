# České jmeniny - Telegram Mini App

A Telegram mini app that displays Czech name days for today and tomorrow. The app shows who has their name day today and tomorrow based on the Czech name day calendar.

## Features

- **Today's Name Day**: Shows who has their name day today
- **Tomorrow's Name Day**: Shows who will have their name day tomorrow
- **Beautiful Design**: Red gradient cards with white text and rounded corners
- **Czech Localization**: All text is in Czech
- **Responsive Design**: Works on all device sizes

## Files

- `index.html` - Main HTML file with the app structure and styling
- `script.js` - JavaScript file containing the Czech name day data and app logic
- `README.md` - This documentation file

## Setup Instructions

### 1. Create a Telegram Bot

1. Message [@BotFather](https://t.me/botfather) on Telegram
2. Send `/newbot` command
3. Follow the instructions to create your bot
4. Save the bot token for later use

### 2. Create a Mini App

1. Message [@BotFather](https://t.me/botfather) again
2. Send `/newapp` command
3. Select your bot
4. Choose "Custom App" option
5. Enter app title: "České jmeniny"
6. Enter app short description: "Zobrazuje české jmeniny pro dnešek a zítřek"
7. Upload a photo for your app icon (optional)
8. Save the app URL for deployment

### 3. Deploy the App

You can deploy this app to any static hosting service:

#### Option A: GitHub Pages
1. Create a new GitHub repository
2. Upload the files (`index.html`, `script.js`)
3. Go to Settings → Pages
4. Select source branch and save
5. Use the provided URL as your app URL

#### Option B: Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the folder containing your files
3. Use the provided URL as your app URL

#### Option C: Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload files
3. Use the provided URL as your app URL

### 4. Configure the Mini App

1. Go back to [@BotFather](https://t.me/botfather)
2. Send `/myapps` to see your apps
3. Select your app
4. Choose "App Settings"
5. Set the app URL to your deployed URL
6. Configure other settings as needed

## Usage

1. Users can access the mini app through your bot
2. The app will automatically show today's and tomorrow's name days
3. The information is displayed in beautiful red gradient cards with white text
4. All dates are formatted in Czech

## Technical Details

- **Framework**: Pure HTML, CSS, and JavaScript
- **Telegram Integration**: Uses Telegram Web App API
- **Data**: Complete Czech name day calendar for the entire year
- **Styling**: Modern gradient design with rounded corners
- **Localization**: Czech language support

## Customization

You can customize the app by:

1. **Changing Colors**: Modify the CSS gradients in `index.html`
2. **Adding More Data**: Extend the `nameDays` object in `script.js`
3. **Modifying Layout**: Adjust the HTML structure and CSS
4. **Adding Features**: Implement additional functionality like search or calendar view

## Browser Compatibility

The app works in all modern browsers that support:
- ES6 JavaScript
- CSS Grid and Flexbox
- CSS Gradients
- CSS Animations

## License

This project is open source and available under the MIT License.
