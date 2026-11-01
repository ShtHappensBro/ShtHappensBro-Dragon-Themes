# ShtHappensBro's Dragon Themes 🐉

A collection of highly customizable, terminal-style cyberpunk themes for Discord. All themes feature custom fonts, glassmorphism sidebars, and high-contrast glowing dragon backgrounds. 

## 🎨 The Themes

### 1. Deathwing Red
The original cyberpunk terminal theme. Deep blacks, aggressive red neon, and a glowing Deathwing background.
<img width="1789" height="1086" alt="explorer_zGaMXoXucN" src="https://github.com/user-attachments/assets/2edb328a-7c91-4304-a1d4-872f119448ba" />

### 2. Frost Wyrm
A frosty, sub-zero variant. Features crisp cyan accents, frosted glass sidebars, and an icy blue dragon.
<img width="1792" height="1079" alt="Discord_FrkyZgClUY" src="https://github.com/user-attachments/assets/55cf825e-bfa9-4c1b-a024-703a4f68c56e" />

### 3. Twilight Tempest
An electric, arcane variant. Features deep purple neon, a stormy aesthetic, and a glowing violet dragon.
<img width="1799" height="1083" alt="Discord_5EmXUWh5Dd" src="https://github.com/user-attachments/assets/15562e13-9ad8-4d45-b00c-44ffe165a440" />

### 4. Emerald Surge
A high-voltage, toxic variant. Features neon green lightning accents and a glowing green dragon.
<img width="1787" height="1082" alt="Discord_RfzhmvUPZG" src="https://github.com/user-attachments/assets/45ae56d1-8f8a-467b-a489-17a80ef97600" />

---

## 📥 Installation

### BetterDiscord
1. Download the `.css` file for the theme you want.
2. Rename the file to `ThemeName.theme.css` (e.g., `Twilight-Tempest.theme.css`).
3. Place it in your BetterDiscord themes folder. *(Discord Settings -> BetterDiscord -> Themes -> Open Themes Folder)*.
4. Enable it in the BetterDiscord Themes menu.

### Vencord
**Method 1: Online Theme (Easiest)**
1. Copy the "Raw" link of the `.css` file from this GitHub page.
2. In Discord, go to **Vencord Settings -> Themes**.
3. Paste the link into the **"Online Themes"** text box.
4. Ensure the theme is toggled **ON**.

**Method 2: Local File**
1. Download the `.css` file.
2. Place it in your Vencord themes folder. *(Discord Settings -> Vencord -> Themes -> Open Themes Folder)*.
3. Rename the file to `ThemeName.css` (Vencord prefers `.css`).
4. Click **"Load missing Themes"** in Vencord and toggle it **ON**.
5. Make sure **"Enable Custom CSS"** is turned ON in Vencord's main settings.

---

## 🛠️ Troubleshooting: Brightness & Monitor Differences

Because everyone's monitor brightness is different, these themes use a CSS variable to control the background brightness. If the background looks too dark or washed out for you, there are two ways to fix it instantly.

### Method 1: The Light Mode Trick
The themes are coded to automatically boost the background brightness if you switch Discord to **Light Mode**. 
1. Go to Discord User Settings -> Appearance.
2. Switch to **Light Mode**. The background image will instantly get brighter.

### Method 2: Vencord/BetterDiscord Quick CSS (Live Editor)
If you want precise control, you can override the brightness variable live without touching the theme file. 

1. Open your client's Custom CSS menu *(Vencord Settings -> Themes -> Edit Quick CSS, or BetterDiscord -> Custom CSS)*.
2. Paste the following code:
```css
:root {
    --bg-brightness: 1.5 !important; 
}
