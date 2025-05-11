# Facebook Signup Form Simulator 

> ⚠️ **Disclaimer**: This project does **not** create real Facebook accounts. It is a training simulation for web automation, UI testing, and CAPTCHA handling. For ethical and legal use only.
https://t.me/danirueaq
---


## 🌐 Multilingual README

* [🇺🇸 English](#english)
* [🇨🇳 中文 (Chinese)](#%E4%B8%AD%E6%96%87-chinese)
* [🇷🇺 Русский (Russian)](#%D1%80%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-russian)

---

## 🇺🇸 English


### 🚀 Features

* Facebook-style responsive signup form (HTML/CSS/JS)
* CAPTCHA emulator for practice
* Form validation feedback
* Compatible with Playwright, Puppeteer, Selenium
* Fully multilingual interface

### 🛠️ Tech Stack

* Frontend: HTML5, CSS3, JavaScript
* Backend (optional): Flask or Express.js
* Automation Tools: Selenium, Playwright

### 📦 Installation

```bash
git clone https://github.com/yourusername/facebook-signup-simulator.git
cd facebook-signup-simulator
npm install   # or pip install -r requirements.txt if using Flask
```

### ▶️ Example Automation (Python + Playwright)

```python
from playwright.sync_api import sync_playwright

with sync_playwright() as p:
    browser = p.chromium.launch(headless=False)
    page = browser.new_page()
    page.goto("http://localhost:8000")
    page.fill("#first_name", "John")
    page.fill("#last_name", "Doe")
    page.fill("#email", "john@example.com")
    page.click("#submit")
```

### 🧠 Contribution

PRs welcome — especially internationalization, CAPTCHA modules, and UI improvements.

### 📜 License

MIT License — for education and research only.

---

## 🇨🇳 中文 (Chinese)

### 📌 简介

这是一个用于模拟 Facebook 注册过程的教育项目，适合测试表单自动化、验证码训练以及浏览器脚本实践。

### 🚀 功能

* 模拟 Facebook 风格的注册表单
* 验证码模拟器
* 表单校验功能
* 支持 Playwright、Selenium 等自动化工具
* 多语言界面支持

### 🛠️ 技术栈

* 前端：HTML5, CSS3, JavaScript
* 后端（可选）：Flask 或 Express.js
* 自动化工具：Selenium, Playwright

### 📦 安装

```bash
git clone https://github.com/yourusername/facebook-signup-simulator.git
cd facebook-signup-simulator
npm install   # 或 pip install -r requirements.txt
```

### ▶️ 示例脚本（Python + Playwright）

```python
from playwright.sync_api import sync_playwright

with sync_playwright() as p:
    browser = p.chromium.launch(headless=False)
    page = browser.new_page()
    page.goto("http://localhost:8000")
    page.fill("#first_name", "张")
    page.fill("#last_name", "三")
    page.fill("#email", "zhangsan@example.com")
    page.click("#submit")
```

### 🧠 欢迎贡献

欢迎 PR，特别是语言翻译、验证码模块与 UI 改进。

### 📜 许可证

MIT License（仅供学习用途）

---

## 🇷🇺 Русский (Russian)

### 📌 Обзор

Это учебный симулятор формы регистрации Facebook. Предназначен для практики автоматизации форм, работы с CAPTCHA и скриптов для браузера.

### 🚀 Возможности

* Адаптивная форма регистрации в стиле Facebook
* Модуль CAPTCHA для тренировки
* Проверка данных формы
* Совместимость с Playwright, Selenium
* Многоязычный интерфейс

### 🛠️ Технологии

* HTML5, CSS3, JavaScript
* (опционально) Flask или Express.js
* Автоматизация: Selenium, Playwright

### 📦 Установка

```bash
git clone https://github.com/yourusername/facebook-signup-simulator.git
cd facebook-signup-simulator
npm install   # или pip install -r requirements.txt
```

### ▶️ Пример скрипта (Python + Playwright)

```python
from playwright.sync_api import sync_playwright

with sync_playwright() as p:
    browser = p.chromium.launch(headless=False)
    page = browser.new_page()
    page.goto("http://localhost:8000")
    page.fill("#first_name", "Иван")
    page.fill("#last_name", "Петров")
    page.fill("#email", "ivan@example.com")
    page.click("#submit")
```

### 🧠 Контрибуция

Pull Request'ы приветствуются. Особенно приветствуются улучшения CAPTCHA, UI и переводы.

### 📜 Лицензия

MIT License (только в образовательных целях)
