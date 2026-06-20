# 🚀 ZDCURLCollector — Quick Start Guide

## ⚡ Run Server + Ngrok (Public Access)
Run the all-in-one startup script:
```bash
/home/bittu/Desktop/ZDCURLCOLEECTORFINAL/run_project.sh
```
* **Starts backend server**
* **Launches Ngrok tunnel**
* **Generates public URL**

---

## 🔍 Check Session Health
Audit your session cookies to ensure you are logged in to the scraping platforms:
```bash
/home/bittu/Desktop/ZDCURLCOLEECTORFINAL/check_sessions.sh
```
* **Valid sessions**
* **Expired sessions**
* **Invalid cookies**

---

## 🌐 Login & Capture Sessions
To scrape platforms requiring authentication, execute the login helper script for each platform:

* **Instagram**
  ```bash
  /home/bittu/Desktop/ZDCURLCOLEECTORFINAL/login_helper.sh instagram
  ```
* **Facebook**
  ```bash
  /home/bittu/Desktop/ZDCURLCOLEECTORFINAL/login_helper.sh facebook
  ```
* **LinkedIn**
  ```bash
  /home/bittu/Desktop/ZDCURLCOLEECTORFINAL/login_helper.sh linkedin
  ```
* **Pinterest**
  ```bash
  /home/bittu/Desktop/ZDCURLCOLEECTORFINAL/login_helper.sh pinterest
  ```

* **Opens real browser**
* **Manual login required** (solve 2FA / captchas if prompted)
* **Sessions auto-saved** on exit/pressing Enter in CLI

---

## 📂 Session Storage
All exported cookies are stored securely as JSON files in:
```text
/home/bittu/Desktop/ZDCURLCOLEECTORFINAL/sessions/
```

---

## 🧠 Notes
* **Complete login before closing browser**
* **Re-run login** if a session expires or gets invalidated
* **Run session check regularly** to avoid failing jobs
* **Ensure virtual environment is working** (`venv/` directory is healthy)

---

## 🛠️ Fix Issues

### Permission Error
If the scripts are not executable, run:
```bash
chmod +x /home/bittu/Desktop/ZDCURLCOLEECTORFINAL/run_project.sh
chmod +x /home/bittu/Desktop/ZDCURLCOLEECTORFINAL/check_sessions.sh
chmod +x /home/bittu/Desktop/ZDCURLCOLEECTORFINAL/login_helper.sh
```

### Sessions Not Saving
* **Check folder permissions** to ensure the script can write to `sessions/`
* **Verify correct project path** is matching `.env` settings

---

## 🔐 Security
> [!WARNING]
> **Session cookies allow full account access.**
> Do **NOT** share files under `/home/bittu/Desktop/ZDCURLCOLEECTORFINAL/sessions/` with anyone. Store them securely.

---

## 💡 Tip
Combine:
* **Ngrok URL** 🌍
* **Active sessions** 🍪

→ **Remote automation ready!**
