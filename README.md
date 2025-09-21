# IPv4 Subnet Calculator

A lightweight and hacker-themed web tool for calculating IPv4 subnets.
Supports multiple input formats like Subnet Mask, CIDR Notation, Wildcard Mask, and Host Requirement.

---

## 🚀 Features

* Accepts IPv4 address inputs in different formats:

  * **Subnet Mask** → `172.31.170.140 255.255.252.0`
  * **CIDR Notation** → `192.168.4.215/28`
  * **Wildcard Mask** → `172.16.45.45 0.0.15.255`
  * **Host Requirement** → `10.45.50.60 #52` (calculates subnet for 52 hosts)
* Displays detailed subnetting results:

  * Network address, Broadcast address
  * First/Last usable host & host range
  * Netmask, Wildcard, CIDR, IP Class, IP Type
  * Total/Usable hosts
  * Binary, Decimal, and Hexadecimal breakdowns
* Built with **HTML, CSS, and JavaScript** – no backend required
* Hacker-inspired UI with glowing green theme and background animations

---

## 📖 How It Works

1. Enter an IPv4 address in one of the supported formats.
2. Click **Calculate** to view results.
3. Results are shown in a detailed table with explanations.
4. Use **Clear** to reset inputs.

---

## 🧮 Manual Calculation Guide

This project also includes an **explanation section** with step-by-step guidance:

* How subnet masks work
* Converting to binary & hexadecimal
* Deriving total/usable hosts
* Calculating network & broadcast addresses
* Understanding CIDR and wildcard masks

Perfect for both **network engineers** and **students learning subnetting**.

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (with hacker-style effects)
* **JavaScript**

---

## 📂 Project Structure

```
.
├── index.html      # Main application
└── README.md       # Project documentation
```

---

## ⚡ Future Enhancements

* Add **IPv6 support**
* Export results to **CSV/JSON**
* Add **network visualization graphs**
* Mobile-friendly dark theme improvements

---

## 📜 License

This project is open-source under the **MIT License**.

---

## 👨‍💻 Author

Developed by [Hemanth Kumar M J](https://hemanthkumarmj.com)
