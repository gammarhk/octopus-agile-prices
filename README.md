# ⚡ Octopus Agile Prices

A simple PWA that shows Octopus Energy Agile half-hourly electricity prices.

No login needed — uses the public Octopus Energy API.

## Features

- Current price displayed prominently with colour coding
- Today's and tomorrow's half-hourly price chart
- Cheapest upcoming time slots
- Auto-refreshes every 5 minutes
- Works offline (shows last-fetched prices)
- Installable as a home screen app on iOS/Android

## Deploy to GitHub Pages

1. Create a new repo on GitHub
2. Push these files:

```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin git@github.com:YOUR_USERNAME/agile-prices.git
git push -u origin main
```

3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch, **/ (root)** folder
6. Click **Save**
7. Your site will be live at `https://YOUR_USERNAME.github.io/agile-prices/`

## Add to iPhone Home Screen

1. Open the site URL in **Safari**
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

## Configuration

Default region is **J (South East)**. Tap the region button in the app to change it. The choice is saved locally.
