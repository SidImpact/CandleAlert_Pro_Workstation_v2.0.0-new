
# CandleAlert_Pro_Workstation_v2.0.0-new
A professional desktop utility for financial traders that tracks precise candle close times and pushes automated alerts via audio, Discord, and Telegram.
# CandleAlert Pro Workstation 🕯️🔔

**CandleAlert** is a professional desktop utility built for active financial traders (Day Traders, Scalpers, Crypto, Forex). It tracks precise candle close times across your selected market session and provides reliable, buffered audio and webhook alerts right before the candle closes, so you never miss a critical trade setup.

![CandleAlert Pro](https://raw.githubusercontent.com/sidimpact/CandleAlert/main/media/screenshot.png)

## 🚀 Key Features (v2.0.0)

- **Precision Tracking**: Accurately tracks candle closes for multiple timeframes simultaneously (1m, 3m, 5m, 15m, 1H, 4H, Daily).
- **Custom Buffer Alerts**: Get notified exactly X seconds before the candle closes (e.g., alert me 15 seconds before the 5-minute candle closes).
- **Webhooks (New!)**: Seamlessly push alerts to **Discord** and **Telegram** automatically. 
- **Configuration Profiles**: Save and load different tracking setups (e.g., "Crypto Scalping" vs "NSE Intraday") with persistent memory.
- **Background Execution**: Minimizes quietly to your system tray so it doesn't clutter your taskbar.
- **Premium UI**: Built with CustomTkinter for a sleek, dark-mode, hardware-accelerated interface.

## 📥 Quick Start

1. Download the latest release from the [Releases page](https://github.com/sidimpact/CandleAlert/releases) or Gumroad.
2. Extract the ZIP file.
3. **Important for Windows 11**: Right-click the `.zip` or `.exe`, go to **Properties**, and check the **Unblock** box before running.
4. Double click `CandleAlert.exe` to launch the workstation!

## 🤝 Support the Developer
Built with ❤️ by **SID IMPACT**. If this tool helped you secure a profitable trade, consider supporting development:
- **Google Pay**: `sidbhimgaj.s14@okaxis`
- **PayPal**: [PayPal.me/siddharthSingh374](https://PayPal.me/siddharthSingh374)
- **Ko-fi**: [ko-fi.com/sidimpact](https://ko-fi.com/sidimpact)

---
*Disclaimer: CandleAlert is a utility tool and does not provide financial advice.*

# Installation Guide 🛠️

CandleAlert is designed to be fully portable. No complex installers or dependencies are required if you use the pre-compiled executable!

## Option 1: Standalone Windows App (Recommended for Traders)

1. **Download**: Download the `CandleAlert_Pro_Workstation_v2.0.0.zip` file from the official release page.
2. **Unblock the File (Critical for Windows 11)**:
   - Because this software is downloaded from the internet, Windows Smart App Control may flag it. 
   - **Before extracting**, Right-Click the `.zip` file and select **Properties**.
   - Check the **Unblock** box at the very bottom right and click Apply.
3. **Extract**: Unzip the folder to your preferred location (e.g., Desktop or Documents).
4. **Run**: Double-click `CandleAlert.exe` to launch the workstation.

## Option 2: Running from Python Source Code (For Developers)

If you prefer to run the raw source code or bypass SmartScreen completely:
1. Ensure Python 3.10+ is installed on your system.
2. Clone or download the repository.
3. Open a terminal in the folder and install dependencies:
   ```bash
   pip install customtkinter pystray pillow requests
   ```
4. Run the application:
   ```bash
   python candlealert.py
   ```

# CandleAlert Pro Workstation - User Guide 📖

Welcome to **CandleAlert Pro**! This guide will help you set up your tracking environment and never miss a critical trade confirmation again.

## The Dashboard (Countdown Tab)
The main screen displays the **Global Countdown Clock** targeting the next immediate candle close based on your active tracking settings. 

### Configuring Your Alerts
On the right panel, you can:
1. **Select Trading Market**: Adjusts the global session times (e.g., NSE, NYSE, Forex 24/7).
2. **Timeframe**: Select a timeframe to edit.
3. **Alert Me Before Close**: Set a buffer time (e.g., "15 Seconds" means the alarm will ring 15 seconds *before* the candle closes).
4. **Notification Sound**: Pick from various custom chimes and bells.

## Webhook Notifications (Alerts Tab)
CandleAlert can push notifications straight to your mobile devices or trading group via Discord and Telegram.
1. Go to the **Alerts** tab.
2. **Discord**: Paste your Discord Server Webhook URL and toggle the switch ON.
3. **Telegram**: Provide your Telegram Bot Token and the Chat ID (Group or Personal ID) and toggle the switch ON.
4. *Tip: You can use the "Test Connection" buttons to ensure your bots are configured correctly before live trading.*

## Configuration Profiles (Settings Tab)
Do you trade Forex in the morning and Crypto at night? Use profiles!
1. Set up all your timeframes, sounds, and buffers on the main screen.
2. Go to the **Settings** tab.
3. Click **➕ Save Current Setup** and name it (e.g., "Forex Session").
4. To switch setups later, simply select the profile from the dropdown and click **💾 Load Profile**.

## Running in the Background
When you click the `X` to close the application, it does not stop! It minimizes to your Windows System Tray (the small icons near your clock). Double-click the green bell icon to restore the workstation UI.
