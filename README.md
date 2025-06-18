# Laragon Windows Portable 6.0.0 – Stable Version

**A complete, portable web development environment for Windows**  
🚀 Zero installation | 🔒 Password-protected | ⚡ Optimized performance  

---

## 🌟 Key Features

- **100% Portable**  
  Run directly from USB or any folder – no system modifications required.
- **Pre-configured Stack**  
  Apache, MySQL, PHP, Git, Composer, and cURL ready-to-use.
- **Auto Virtual Hosts**  
  Instant `*.test` domains for local development.

---

## 📦 Included Components

| Component       | Version               | Details                              |
|-----------------|-----------------------|--------------------------------------|
| 🐘 PHP          | 8.3.16 (ZTS)          | VC++ 2019, OPcache enabled          |
| 🐬 MySQL        | 8.4.3                 | Community Edition (GPL)              |
| 🐳 Apache       | 2.4.62                | Win64, OpenSSL 3.0                   |
| 🧬 Composer     | 2.4.1                 | Global binary included               |
| 🔄 cURL         | 8.12.1                | LibreSSL + zstd support              |
| 🧪 Git          | 2.48.1                | Windows-native build                 |

---

## 🚀 Getting Started

1. Extract the `.7z` archive of Laragon.
2. Run the executable file: **`LARAGON-INSTALL.exe`**
3. When prompted, enter the following password:

**Password:** `ian7672`

4. After installation completes, run `laragon.exe`.
5. Laragon will auto-start and configure services (Apache, MySQL, etc).
6. Start building your local PHP apps right away.

---

## 🛠️ Features

- Portable – No installation or system changes needed.
- Optimized for performance on Windows.
- Pre-configured Virtual Hosts and SSL.
- Integrated terminal, quick app installer, and more.

---

### System Requirements
- Microsoft Visual C++ Redistributable
- .NET Framework 4.8

---

## ⚡ Quick Commands

Use these in Laragon's terminal:
```bash
larg.exe start    # Start all services
larg.exe stop     # Stop all services
larg.exe status   # Check service status
```

---

## 🛠️ Advanced Features

- **SSL Ready**  
  Pre-configured HTTPS for `*.test` domains.
- **Database Management**  
  Includes Adminer for MySQL GUI access.

---

## 🔍 Environment Verification

Verify installed components:
### PHP
```bash
php -v
# Expected: PHP 8.3.16 (ZTS Visual C++ 2019 x64)
```

### MySQL
```bash
mysql --version
# Expected: mysql  Ver 8.4.3 for Win64
```

### Apache
```bash
httpd -v
# Expected: Apache/2.4.62 (Win64)
```

---

## 🔗 Resources

- [📚 Official Documentation](https://laragon.org/docs)
- [🐙 GitHub Releases](https://github.com/Ian7672/laragon-portable/releases)
- [🔄 PHP 8.3 Changes](https://www.php.net/releases/8.3/en.php)
- [❗ Troubleshooting Guide](https://laragon.org/docs/troubleshooting.html)

---

## 📜 License  
This portable edition is shared under the original Laragon license terms.  
MySQL remains licensed under GPL.

**© 2025 Ian7672** | All-in-One Portable Dev Environment for Windows
