# FKFK Sniper — downloads

Watches KFUPM sections, alerts you on Telegram the moment a seat opens, and registers you automatically.

## ⬇️ Download: [latest version](https://github.com/couldbeaUser/fkfk-sniper-release/releases/latest)

**Mac** (Apple chip: M1 or newer) — `FKFK-Sniper.dmg`
1. Open the .dmg and drag **FKFK Sniper** into **Applications**.
2. Open it. The first time macOS blocks it: **System Settings → Privacy & Security → Open Anyway**.
   If it says the app is "damaged", run this in Terminal, then open it again:
   `xattr -dr com.apple.quarantine "/Applications/FKFK Sniper.app"`
3. Needs Google Chrome installed.

**Windows** — `FKFK-Sniper-windows.zip`
1. Unzip it (right-click → Extract All).
2. Open the folder and double-click **Install FKFK Sniper.bat**.
3. If Windows SmartScreen appears: **More info → Run anyway**.

## First start
The app asks for:
- **Your own Telegram bot**: in Telegram message **@BotFather**, send `/newbot`, copy the token it gives you,
  paste it in the app, then press **START** in your new bot.
- **Your KFUPM username, password and term.** The password is kept in your computer's Keychain /
  Credential Manager only.

Then add sections in Telegram, e.g. `/add 21542` or `/add MATH208-02`, and `/autoreg on`. `/help` lists everything.

## Updates
The app checks for new versions by itself and shows **Update now**. Your settings stay as they are.

If you're on the same Wi-Fi as a friend who also uses it, both send `/interval 3` so KFUPM doesn't block the connection.
