# 🐧 TFT Client Theme

A minimalist plugin for the League of Legends client, powered by **Pengu Loader**, transforming your client into a dedicated **Teamfight Tactics** launcher.

---

## ✨ Features

- **🎮 TFT Focused** - Displays only Teamfight Tactics, hiding all other game modes
- **📱 Minimalist Interface** - Removes clutter such as Store, Loot, Collection, and unnecessary visual separators
- **👤 Streamlined Profile** - Hides Honor, Mastery, and Challenge tokens
- **✨ Clean UI** - Removes vertical separators, promotional links, and decorative elements

---

## 📋 Requirements

Before using this theme, ensure you have **Pengu Loader** installed.

👉 [Download Pengu Loader](https://pengu.lol/)

---

## 📥 Installation

### Option 1: Automatic Installation (Recommended) ⭐

1. Download the latest `.zip` release from the [Releases](https://github.com/kyso1/tft-client-theme/releases) page
2. Open your Pengu Loader plugins folder:
   - **Shortcut:** Press `Windows + R`, type `%localappdata%\PenguLoader\plugins\` and press Enter
3. Extract the `TFT-Client` folder from the ZIP directly into the plugins directory
4. Restart your League of Legends client

### Option 2: Manual Installation (For Developers)

1. Navigate to your plugins folder:
   ```
   C:\Users\<YourUser>\AppData\Local\PenguLoader\plugins\
   ```

2. Create a new folder named `TFT-Client`

3. Replicate the following folder structure:
   ```
   TFT-Client/
   ├── index.js
   ├── assets/
   │   └── set16.png
   └── css/
       └── tft.css
   ```

4. Add the files:
   - Copy the JavaScript code to `index.js`
   - Copy the CSS code to `css/tft.css`
   - Place your custom image in the `assets/` folder

---

## 🚀 Usage

1. Restart your League of Legends client
2. Pengu Loader will automatically inject the plugin
3. Enjoy your dedicated TFT interface!


---

## 📝 Credits

- **Developer:** Kyso
- **Platform:** [Pengu Loader](https://pengu.lol/)

---

## ⚠️ Disclaimer

This is a client-side modification using Pengu Loader. It is considered safe as it does not affect game mechanics, but use it at your own risk.
