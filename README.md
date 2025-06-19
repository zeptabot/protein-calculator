# Protein Cost Calculator

A mobile-friendly web application to help fitness enthusiasts find the most cost-effective protein sources for their diet.

## 📱 Features

- Calculate cost per 30g protein for various food items
- Track protein and fat content
- Compare different protein sources
- Save and manage your favorite items
- Mobile-responsive design
- Delete individual items or clear all entries
- Sort items by cost efficiency

## 🛍️ How to Use

1. **Add a New Item**
   - Enter the item name (e.g., "Textured Soy Protein")
   - Enter the seller/brand name
   - Enter the unit price (e.g., "10.99")
   - Enter the unit weight in grams (e.g., "500")
   - Enter the serving weight in grams (e.g., "30")
   - Enter protein per serving in grams (e.g., "20")
   - Click "Add Item"

2. **View Items**
   - Items are automatically sorted by cost per 30g protein (cheapest first)
   - Click the delete button to remove individual items
   - Use the "Clear All" button to remove all items

## 📱 How to Get Started

### Data Persistence (How your data is saved)
- **Automatic:** Your data is saved automatically in your browser using `localStorage`. This means you do NOT need any extra files or setup—just use the app and your data will stay even if you close or reopen your browser or device.
- **CSV Export/Import:** You can export your data as a CSV file for backup or to move your data to another device/browser. You can also import a CSV file to restore your data.
- **You do NOT need the CSV file for normal use.** The CSV is just for backup/sharing.

### 1. Using the Web Version
- Open the `protein_calculator.html` file in any web browser (desktop or mobile)
- No installation required
- Works on any device with a browser
- Data persists between sessions automatically

### 2. Using as a Mobile App
- Open the HTML file in your mobile browser
- Tap your browser's menu and choose "Add to Home Screen"
- Use it like a native app
- Data will persist between sessions

---

## 📦 CSV Export/Import (Optional)
- **Export CSV:** Click the "Export CSV" button to download your data as a CSV file for backup or sharing.
- **Import CSV:** Click the "Import CSV" button and select a CSV file to load data into the app.
- Useful for transferring your data to another device or browser.

---

### Tips for Using the App

1. **Adding Items**
   - Always check the nutrition label for accurate numbers
   - Enter the price exactly as shown on the store shelf
   - Double-check your numbers before adding

2. **Viewing Results**
   - Items will automatically sort from cheapest to most expensive
   - Use the delete button carefully - it requires confirmation
   - The "Clear All" button is permanent - use with caution

3. **Mobile Usage**
   - The app works on your phone's browser
   - Keep the nutrition label handy while entering data
   - Use landscape mode for easier typing

4. **Saving Your Work**
   - Your data is saved automatically
   - If you close the app, your data will still be there
   - You can view your saved items anytime


##  Tips

- The interface is fully responsive and works well on mobile devices
- Use the "Clear All" button carefully as it cannot be undone
- The delete button requires confirmation to prevent accidental deletions
- Items are automatically sorted by cost efficiency, making it easy to find the best deals

## 🤝 Contributing

Feel free to fork this repository and improve it! If you have suggestions for new features or find any bugs, please open an issue.

### Feature Wishlist

I would love for community members to help build out these exciting new features:

1.  **Common Items Database:** Integrate a public food database (like the USDA FoodData Central, an open-source NUTTAB, or the Canadian Nutrient File) to allow users to quickly add common protein products without manual entry.

2.  **LLM-Powered Data Entry:** Integrate a Large Language Model (LLM) that can automatically parse and fill in the nutrition data by simply pasting the text from a product description (e.g., from an Amazon page).

3.  **Native Mobile App with OCR:** Develop a true native mobile app (for Android/iOS) that uses Optical Character Recognition (OCR) to scan nutrition labels in real-time with the phone's camera, making data entry instant and effortless.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## Usage

1. Add protein items with their nutritional information
2. Calculate cost per 30g protein
3. Compare different items based on cost and nutritional value
4. Export your data for offline use
