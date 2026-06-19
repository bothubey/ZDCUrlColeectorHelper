# 🚀 ZDCURLCollector — Quick Start Guide

## ⚡ Run Server + Ngrok (Public Access)

```bash
/home/bittu/Desktop/ZDCURLCOLEECTOR/run_project.sh
```

* Starts backend server
* Launches Ngrok tunnel
* Generates public URL

---

## 🔍 Check Session Health

```bash
/home/bittu/Desktop/ZDCURLCOLEECTOR/check_sessions.sh
```

* Valid sessions
* Expired sessions
* Invalid cookies

---

## 🌐 Login & Capture Sessions

### Instagram

```bash
/home/bittu/Desktop/ZDCURLCOLEECTOR/login_helper.sh instagram
```

### Facebook

```bash
/home/bittu/Desktop/ZDCURLCOLEECTOR/login_helper.sh facebook
```

### LinkedIn

```bash
/home/bittu/Desktop/ZDCURLCOLEECTOR/login_helper.sh linkedin
```

### Pinterest

```bash
/home/bittu/Desktop/ZDCURLCOLEECTOR/login_helper.sh pinterest
```

* Opens real browser
* Manual login required
* Sessions auto-saved

---

## 📂 Session Storage

```
/home/bittu/Desktop/ZDCURLCOLEECTOR/sessions/
```

---

## 🧠 Notes

* Complete login before closing browser
* Re-run login if session expires
* Run session check regularly
* Ensure virtual environment is working

---

## 🛠️ Fix Issues

### Permission Error

```bash
chmod +x /home/bittu/Desktop/ZDCURLCOLEECTOR/run_project.sh
```

### Sessions Not Saving

* Check folder permissions
* Verify correct project path

---

## 🔐 Security

* Session cookies = full access
* Do NOT share `/sessions/`
* Store securely

---

## 💡 Tip

Combine:

* Ngrok URL 🌍
* Active sessions 🍪

→ Remote automation ready
