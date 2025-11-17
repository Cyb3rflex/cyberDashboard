🛡️ Cybersecurity Dashboard

A modern, interactive, and developer-friendly cybersecurity toolkit built with React, Tailwind CSS, and Framer Motion.
This dashboard provides quick access to essential security tools such as password strength analysis, IP lookup, hash generation, threat intelligence feeds, and simulated system monitoring.

## 🚀 Features

- 🔐 **Password Strength Checker**

	Analyze password entropy and security levels with real-time feedback.

- 🌍 **IP Address Lookup**

	Retrieve IP details such as location, ISP, timezone, and ASN using public APIs.

- 🧩 **Hash Generator**

	Generate cryptographic hashes (MD5, SHA1, SHA256) instantly.

- ⚠️ **Threat Intelligence Feed**

	Fetch and view the latest cybersecurity threats and vulnerabilities.

- 🖥️ **System Monitor**

	Simulated resource monitoring with CPU and memory usage updates.

- 🎨 **Smooth UI + Animations**

	Built with Tailwind CSS (Dark/Light mode), Framer Motion (Animations), and Lucide React (icon set).

## 📁 Project Structure

```
cybersecurity-dashboard/
│
├── public/
│   └── assets/
│
├── src/
│   ├── components/
│   │   ├── Sidebar.jsx
│   │   ├── Navbar.jsx
│   │   ├── ToolCard.jsx
│   │   ├── SectionHeader.jsx
│   │   └── ThemeToggle.jsx
│   │
│   ├── pages/
│   │   ├── Dashboard.jsx
│   │   ├── PasswordTool.jsx
│   │   ├── IpLookupTool.jsx
│   │   ├── ThreatFeed.jsx
│   │   ├── HashChecker.jsx
│   │   └── SystemMonitor.jsx
│   │
│   ├── layouts/
│   │   └── MainLayout.jsx
│   │
│   ├── utils/
│   │   ├── password.js
│   │   ├── iplookup.js
│   │   ├── hashChecker.js
│   │   └── constants.js
│   │
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
└── README.md
```

## 🛠️ Tech Stack

- **Frontend:** React, Vite, JSX
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **API:** ip-api.com (and custom threat feed)
- **Hashing:** crypto-js
- **Routing:** React Router DOM

## ⚙️ Installation & Setup

1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/cybersecurity-dashboard.git
cd cybersecurity-dashboard
```

2️⃣ Install dependencies

```bash
npm install
```

3️⃣ Run the development server

```bash
npm run dev
```

4️⃣ Build for production

```bash
npm run build
```

## 🌍 Available Tools

| Tool | Path | Description |
|------|------|-------------|
| Dashboard | `/` | Overview & quick access |
| Password Checker | `/password` | Strength scoring + feedback |
| IP Lookup | `/iplookup` | Geolocation & ASN lookup |
| Threat Feed | `/threats` | Latest CVE & attack intel |
| Hash Generator | `/hash` | MD5, SHA1, SHA256 generation |
| System Monitor | `/monitor` | CPU/Memory simulation |

## 🎯 Roadmap / Future Upgrades

- ✔️ Add JWT Decoder
- ✔️ Add Port Scanner (API-based)
- ✔️ Add WHOIS Lookup
- ✔️ Add DNS Lookup
- ✔️ Add Data Breach Checker (HIBP API)
- ✔️ Add Dark Mode persistence

## 📌 Contributing

Pull requests are welcome! If you have ideas, improvements, or want to add new tools, feel free to open an issue.

## 📜 License

This project is licensed under the MIT License — free to use and modify.

## 👨‍💻 Developer

Cyberflex 👾
Full-Stack Developer | Cybersecurity Analyst
Nigeria 🇳🇬

