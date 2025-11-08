# Instagram Auto Follower Bot 🤖

This Python project automates the process of logging into Instagram, navigating to a target account’s followers list, and following users using **Selenium WebDriver**.

⚠️ **Disclaimer:** This script is for educational purposes only. Using automation to interact with Instagram may violate their Terms of Service and can result in your account being banned. Use responsibly.

---

## 🚀 Features

- Logs into Instagram automatically.
- Navigates to a specified account’s followers list.
- Scrolls through followers and clicks “Follow” buttons.
- Handles common popup dialogs (cookies, notifications, etc.).

---

## 🧰 Requirements

- Python 3.8 or higher
- Google Chrome browser
- ChromeDriver (compatible with your Chrome version)
- Selenium library

---

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/insta-follower-bot.git
   cd insta-follower-bot
   ```

2. **Install dependencies:**

   ```bash
   pip install selenium
   ```

3. **Download ChromeDriver:**  
   - Visit: [https://chromedriver.chromium.org/downloads](https://chromedriver.chromium.org/downloads)
   - Ensure it matches your Chrome version.
   - Add it to your system PATH or the same folder as the script.

---

## ⚙️ Configuration

Open the Python file and update the following constants:

```python
SIMILAR_ACCOUNT = "buzzfeedtasty"  # Target account to scrape followers from
USERNAME = "YOUR_USERNAME"         # Your Instagram username
PASSWORD = "YOUR_PASSWORD"         # Your Instagram password
```

---

## ▶️ Usage

Run the bot with:

```bash
python main.py
```

The bot will:
1. Open Chrome and go to Instagram.
2. Log into your account.
3. Visit the target account’s followers list.
4. Scroll and attempt to follow users.

---

## 🧠 Notes

- Avoid using the bot too frequently — it can trigger anti-bot detection.
- Always verify the XPath and CSS selectors if Instagram updates its layout.
- Use a test or secondary account to reduce risk.

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

### 🧑‍💻 Author
**Param Sangani**  
[GitHub Profile](https://github.com/ParamDesperado)
