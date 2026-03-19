# 🚀 Network Port Scanner GUI

A fast and lightweight **multi-threaded TCP port scanner** with a clean graphical interface built using **Python & Tkinter**.

---

## ✨ Features

* 🎯 **Simple Interface** – Just enter target, start port, and end port
* ⚡ **High-Speed Scanning** – Uses multi-threading (up to 500 threads)
* 🔍 **Service Detection** – Identifies common services (HTTP, SSH, FTP, etc.)
* 📊 **Real-Time Progress** – Live progress bar and elapsed time tracking
* ⛔ **Stop Anytime** – Cancel scan safely during execution
* 💾 **Save Results** – Export open ports to a `.txt` file
* 🌍 **Cross-Platform** – Works on Windows, Linux, and macOS

---

## 🖥️ Demo
<p align="center">
<img width="958" height="639" alt="app png" src="https://github.com/user-attachments/assets/6463d9f4-8d17-4ae8-a54b-2168c3af50dc" />
</p>


---

## 🛠️ Requirements

* Python **3.7+**
* Tkinter (comes pre-installed with Python)

---

## 📦 Installation

```bash
git clone https://github.com/YOUR_USERNAME/Network-Port-Scanner-GUI.git
cd Network-Port-Scanner-GUI
```

---

## ▶️ Usage

```bash
python portscanergui.py
```

### Steps:

1. Enter **Target IP / Hostname**
2. Enter **Start Port** and **End Port**
3. Click **Start Scan**
4. View results in real-time
5. Save results if needed

---

## 📌 Example

* Target: `192.168.1.1`
* Port Range: `1 - 1024`

---

## 🔍 Supported Services

| Port | Service  |
| ---- | -------- |
| 21   | FTP      |
| 22   | SSH      |
| 80   | HTTP     |
| 443  | HTTPS    |
| 3306 | MySQL    |
| 3389 | RDP      |
| 8080 | HTTP-Alt |

---

## 📁 Project Structure

```
Network-Port-Scanner-GUI/
│── portscanergui.py
│── README.md
│── screenshots/
```

---

## ⚠️ Disclaimer

This tool is intended for **educational purposes only**.
Only scan networks or systems you have permission to test.

---

## 🧑‍💻 Author

**C Y Chetna Reddy**

---

## 📜 License

This project is licensed under the **MIT License**.
