# 🗂️ File System Watcher (Python Desktop App)

This is a Windows desktop application built with **Python**, **Tkinter**, and **SQLite**, using the **Watchdog** library to monitor changes in a specified directory.

---

## 🚀 Features

✅ **Real-time file tracking**  
✅ **SQLite database logging**  
✅ **Query system** – filter changes by:
- File extension
- Event type (created, deleted, modified, moved)
- Date

✅ **Email support** – export full or filtered logs to CSV and email them directly.

---

## 🛠️ Technologies Used

- **Python**
- **Tkinter** – GUI for user interaction
- **Watchdog** – monitors file system changes
- **SQLite** – stores event logs
- **smtplib** – sends emails with CSV attachments

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/8a64dac8-dba1-4e95-9c23-48b12c1087ef)


---

## 🧪 How It Works

1. The user selects a directory to watch.
2. Any changes (new file, delete, rename, edit) are logged into a local SQLite database.
3. The **Query** button allows filtering of results.
4. The **Send Email** button sends the logs (entire or filtered) as a `.csv` file.

---

## 📥 Installation

```bash
git clone https://github.com/dteshager/file-watcher-app.git
cd file-watcher-app
pip install -r requirements.txt
python app.py
