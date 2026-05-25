# BuyWise

BuyWise is a simple mobile-friendly price tracker web app. It helps me record product prices from different stores, search past purchase records, and compare the best unit price before buying.

## Features

- Add purchase records with brand, product name, store, date, price, quantity, and notes
- Auto-calculate final price based on price per unit and quantity
- Search by brand, product name, or store
- View past price history for each product
- See the best unit price previously purchased
- Smart autocomplete suggestions based on previous records
- English and Chinese language support
- Mobile-friendly app-style interface
- Export and import backup data
- Works without a backend server or database

## How It Works

This app is built with a single HTML file.

The purchase records are saved in the browser's localStorage. This means the data is stored on the device and browser where the app is used.

For example, if I use this app on iPhone Safari, the records are saved in Safari on that iPhone.

## Important Data Note

The data is not stored on GitHub.

GitHub Pages only hosts the app file. The actual purchase records are saved locally in the browser.

Please use the Export Backup feature regularly to keep a copy of the records.

## How to Use

1. Open the app in a mobile browser.
2. Tap the add button at the bottom.
3. Fill in the product details, store, price per unit, quantity, and date.
4. Save the record.
5. Use the search bar to quickly find previous prices.
6. Check the best unit price before buying again.

## Add to iPhone Home Screen

1. Open the GitHub Pages link in Safari.
2. Tap the Share button.
3. Select Add to Home Screen.
4. Rename the app if needed.
5. Tap Add.

The app will appear like a normal app icon on the iPhone Home Screen.

## Backup and Restore

Use Export Backup to download a JSON backup file.

Use Import Backup to restore records from a previous backup file.

Do not upload the backup JSON file to GitHub because it contains personal purchase records.

## Tech Stack

- HTML
- CSS
- JavaScript
- Browser localStorage

## Privacy

This app does not send purchase records to any server. Records are stored locally in the browser.

However, if the app is hosted on GitHub Pages, the app page itself is public. Other people can open the app URL, but they will not see my personal records unless I share my backup data with them.

## License

Personal project.
