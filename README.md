# HyperspaceAI-AutoReconnect
This repository contains a Tampermonkey UserScript that ensures automatic reconnection to HyperspaceAI. The script detects when the connection is lost and attempts to reconnect automatically, handling common errors like WebGPU pop-ups and authentication issues.

# 📌Features
✅ Monitors connection status and attempts to reconnect automatically.

✅ Closes WebGPU error pop-ups to prevent failures.

✅ Reloads the page if the maximum reconnection attempts are reached.

✅ Uses an improved selector for the connection button.

✅ Tweaks to bypass potential API blocks.

# 🛠️ How to Use
1 - Install the Tampermonkey extension in your browser.

2 - Copy and paste the script into a new Tampermonkey script.

3 - Save and enable the script.

4 - Go to https://node.hyper.space, and the script will do the rest! 🚀

# ⚠️ Notes
If the script doesn’t work properly, try closing and reopening the page.

The script relies on a CSS selector for the connection button, which may change over time.

For support or improvements, feel free to open an issue.
