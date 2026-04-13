<p align="center">
  <img src=".github/assets/icon.png" width="120" height="120" alt="RWA Icon" />
</p>

<h1 align="center">RWA (Wave Machine)</h1>

<p align="center">
  <a href="#-обзор">🇷🇺 Русский</a>&nbsp;&nbsp;•&nbsp;&nbsp;<a href="#-overview">🇺🇸 English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-iOS%2017%2B-blue?style=flat-square" alt="iOS Platform" />
  <img src="https://img.shields.io/badge/platform-Android%208%2B-34A853?style=flat-square" alt="Android Platform" />
  <img src="https://img.shields.io/badge/language-Swift-orange?style=flat-square" alt="Swift" />
  <img src="https://img.shields.io/badge/language-Kotlin-7F52FF?style=flat-square" alt="Kotlin" />
  <img src="https://img.shields.io/badge/license-Proprietary-lightgrey?style=flat-square" alt="License" />
</p>

<br>

---

# 🇷🇺 Русский

<br>

<p align="center">
  <b>Мощное мобильное приложение для iOS и Android для управления панелью <a href="https://github.com/remnawave">Remnawave</a> — прямо с вашего телефона.</b>
</p>

<br>

## 📖 Обзор

**RWA** — нативное мобильное приложение для **iOS** и **Android**, предназначенное для администраторов панели Remnawave. Оно предоставляет полноценный мобильный дашборд для мониторинга и управления всей вашей инфраструктурой на ходу — с красивым, современным интерфейсом и данными в реальном времени.

- **iOS** — написано на Swift с использованием SwiftUI
- **Android** — написано на Kotlin с использованием Jetpack Compose и Material 3

Приложение поддерживает **английскую** и **русскую** локализации.

---

## ✨ Возможности

<details>
<summary><b>📊 Дашборд в реальном времени</b></summary>
<br>

Мгновенный обзор всей панели:

- **Онлайн-пользователи и активные подключения** — кто подключён прямо сейчас
- **Скорость загрузки/отдачи** — мониторинг пропускной способности в реальном времени
- **Статус нод** — мгновенная информация о том, какие ноды онлайн
- **Трафик за сегодня** — сводка дневного потребления
- **История активности за 24 часа** — тренды онлайна за последние сутки
- **Пользователи по статусу** — разбивка по активным, отключённым, ограниченным и истёкшим
- **Ресурсы панели и нод** — CPU, RAM, аптайм и метрики нагрузки

</details>

<details>
<summary><b>👥 Управление пользователями</b></summary>
<br>

Полный контроль над пользовательской базой:

- **Создание новых пользователей** прямо из приложения
- **Поиск и фильтрация** — поиск по имени, статусу, активности или описанию
- **Сортировка** по ID, имени пользователя, статусу или последнему онлайну
- **Детали пользователя** — трафик, подписка, устройства и многое другое
- **Управление подписками** — изменение дат истечения, установка лимитов трафика, включение/отключение
- **Управление устройствами** — просмотр и удаление подключённых устройств (контроль HWID)

</details>

<details>
<summary><b>🖥 Мониторинг нод</b></summary>
<br>

Следите за всеми серверными нодами:

- **Статус онлайн** для каждой ноды в реальном времени
- **CPU, RAM и аптайм** — мониторинг на одном экране
- **Аналитика трафика и нагрузки** по каждой ноде
- **Включение/отключение нод** мгновенно
- **Перезапуск** — мягкий или принудительный, для одной ноды или всех сразу
- **Управление хостами** — просмотр, включение, отключение и удаление хостов

</details>

<details>
<summary><b>📈 Метрики и аналитика</b></summary>
<br>

Глубокий анализ сетевого трафика:

- **Пропускная способность в реальном времени** по каждой ноде
- **Графики трафика** с настраиваемым диапазоном дат (2 дня, 7 дней, 30 дней, месяц, год)
- **Рейтинг нод** — какие ноды обрабатывают больше всего трафика
- **Входящие/исходящие метрики** по каждой ноде

</details>

<details>
<summary><b>🌐 История системных запросов (SRH)</b></summary>
<br>

Узнайте, откуда идёт ваш трафик:

- **Запросы по часам** — почасовое распределение
- **Топ-10 ASN** — какие сети генерируют больше всего запросов
- **Карта запросов** — географическая визуализация источников
- **Разбивка по приложениям** — какие приложения используются

</details>

<details>
<summary><b>💰 Биллинг инфраструктуры</b></summary>
<br>

Отслеживайте расходы на хостинг и графики оплат:

- **Биллинг нод** — привязка нод к хостинг-провайдерам с датами оплаты
- **История платежей** — полный журнал всех оплат
- **Управление провайдерами** — организация нод по хостинг-провайдерам
- **Предстоящие платежи** — не пропустите ни одного дедлайна
- **Ежемесячные расходы** — обзор трат и общая сумма
- **Отметить как оплаченное** — обновление дат биллинга в одно касание

</details>

<details>
<summary><b>🔔 Push-уведомления</b></summary>
<br>

Будьте в курсе с мгновенными оповещениями:

- **События нод** — офлайн/онлайн, создание, изменение, удаление
- **События пользователей** — создание, отключение, истечение, первое подключение, лимиты трафика
- **Оповещения о подписках** — истекает через 72ч/48ч/24ч, уже истекла
- **Напоминания о биллинге** — предстоящие платежи, просроченные оплаты
- **Системные события** — запуск панели, попытки входа
- **Гибкая настройка** — включение/отключение отдельных категорий и событий

</details>

<details>
<summary><b>💻 SSH-терминал</b></summary>
<br>

Подключайтесь к серверам, не покидая приложение:

- **Встроенный терминал** — полный SSH-доступ к любой ноде
- **Несколько методов аутентификации** — пароль или ключ (OpenSSH, PEM, PKCS#8)
- **Безопасное хранение** — учётные данные хранятся в iOS Keychain / Android EncryptedSharedPreferences
- **Пресеты команд** — сохраняйте и повторно используйте частые команды в одно касание
- **Настройка для каждой ноды** — разные учётные данные для каждого сервера

</details>

<details>
<summary><b>👥 Отряды (Squads)</b></summary>
<br>

Организуйте пользователей в группы для удобного управления.

</details>

<details>
<summary><b>⚙️ Настройки подписки</b></summary>
<br>

Настройте поведение подписок прямо с телефона:

- Название профиля и ссылка на поддержку
- Интервал обновления
- Рандомизация хостов
- Ограничение устройств по HWID
- Пользовательские сообщения для различных статусов
- Пользовательские заголовки ответов

</details>

<details>
<summary><b>📱 Виджеты на домашнем экране</b></summary>
<br>

Ключевые метрики доступны без открытия приложения:

- Виджет **«Онлайн-пользователи»** — малый и средний размеры
- Виджет **«Скорость загрузки»** — малый и средний размеры
- Виджет **«Трафик за сегодня»** — малый и средний размеры
- Виджет **«Общий дашборд»** — большой размер (Android)
- Настраиваемый интервал обновления
- Настраиваемый диапазон графиков и период трафика

</details>

<details>
<summary><b>🔒 Безопасность</b></summary>
<br>

Защитите приложение биометрической аутентификацией:

- **iOS:** Face ID / Touch ID / Optic ID
- **Android:** отпечаток пальца / PIN / графический ключ / пароль устройства
- Автоблокировка при сворачивании приложения
- Резервный пароль

</details>

<details>
<summary><b>🎨 Кастомизация</b></summary>
<br>

Сделайте приложение своим:

- **Настройка панели вкладок** — выберите, какие вкладки отображать
- **Выбор иконки приложения** — несколько стилей на выбор
- **Настройки автообновления** — интервалы обновления данных

</details>

---

## 📸 Скриншоты

> *Скриншоты скоро будут*

---

## 📋 Требования

| | |
|---|---|
| **iOS** | iOS 17.0 или новее (iPhone или iPad) |
| **Android** | Android 8.0 (API 26) или новее |
| **Сервер** | Работающий экземпляр панели [Remnawave](https://github.com/remnawave) |

---

## 📥 Установка


<p align="center">
  <a href="https://apps.apple.com/us/app/wave-machine/id6760419820">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="68" style="vertical-align: middle;" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/egvill/RWA-Mobile-App/releases/latest">
    <img src="https://img.shields.io/github/downloads/egvill/RWA-Mobile-App/total?style=for-the-badge&logo=android&label=Download%20Android&color=34A853" alt="Download Android" height="40" style="vertical-align: middle;" />
  </a>

  <!-- <a href="https://github.com/egvill/RWA-Mobile-App/releases/latest"> -->
    <!-- <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Загрузить в Google Play" height="68" style="vertical-align: middle;" /> -->
  <!-- </a> -->
</p>

---

## 🚀 Начало работы

1. **Установите** приложение на устройство
2. **Откройте** RWA — пошаговая настройка проведёт вас через начальную конфигурацию
3. **Подключитесь** к панели Remnawave, указав URL панели и API-ключ
4. **Исследуйте** дашборд, управляйте пользователями, следите за нодами и многое другое

---

## 🌍 Локализация

| Язык | Статус |
|------|--------|
| 🇷🇺 Русский | ✅ Полная поддержка |
| 🇺🇸 English | ✅ Полная поддержка |

---

## 🔐 Конфиденциальность

- Все данные передаются напрямую между вашим устройством и панелью Remnawave
- SSH-учётные данные надёжно хранятся в iOS Keychain / Android EncryptedSharedPreferences (AES-256)
- Никакие пользовательские данные не собираются и не передаются третьим лицам
- Firebase используется исключительно для доставки push-уведомлений и базовой аналитики

---

## 📄 Лицензия

Данный проект является проприетарным программным обеспечением. Все права защищены.

<br>
<br>

---

# 🇺🇸 English

<br>

<p align="center">
  <b>A powerful iOS & Android companion app for managing your <a href="https://github.com/remnawave">Remnawave</a> panel — right from your pocket.</b>
</p>

<br>

## 📖 Overview

**RWA** is a native mobile application for **iOS** and **Android**, designed for administrators of the Remnawave panel. It provides a comprehensive mobile dashboard to monitor, manage, and control your entire infrastructure on the go — with a beautiful, modern interface and real-time data.

- **iOS** — built with Swift and SwiftUI
- **Android** — built with Kotlin, Jetpack Compose, and Material 3

The app supports **English** and **Russian** localizations.

---

## ✨ Features

<details>
<summary><b>📊 Live Dashboard</b></summary>
<br>

A real-time overview of your entire panel at a glance:

- **Online users & active connections** — see who's connected right now
- **Download/upload speed** — live bandwidth monitoring across all nodes
- **Node status** — instantly know which nodes are online
- **Today's traffic** — daily bandwidth consumption summary
- **24-hour activity history** — see online trends over the past day
- **Users by status** — breakdown of active, disabled, limited, and expired users
- **Panel & node resource usage** — CPU, RAM, uptime, and load metrics

</details>

<details>
<summary><b>👥 User Management</b></summary>
<br>

Full control over your user base:

- **Create new users** directly from the app
- **Search & filter** — find users by name, status, activity, or description
- **Sort** by ID, username, status, or last online time
- **User details** — view traffic usage, subscription info, devices, and more
- **Manage subscriptions** — update expiration dates, set traffic limits, enable/disable users
- **Device management** — view and remove connected devices (HWID control)

</details>

<details>
<summary><b>🖥 Node Monitoring</b></summary>
<br>

Keep track of all your server nodes:

- **Real-time online status** for every node
- **CPU, RAM & uptime** monitoring at a glance
- **Traffic & load analytics** per node
- **Enable/disable nodes** instantly
- **Graceful or force restart** — restart individual nodes or all at once
- **Host management** — view, enable, disable, and delete hosts per node

</details>

<details>
<summary><b>📈 Metrics & Analytics</b></summary>
<br>

Deep insights into your network traffic:

- **Realtime bandwidth** per node with live updates
- **Traffic over time** charts with configurable date ranges (2 days, 7 days, 30 days, calendar month, year)
- **Top nodes ranking** — see which nodes handle the most traffic
- **Inbound/outbound metrics** per node

</details>

<details>
<summary><b>🌐 System Request History (SRH)</b></summary>
<br>

Understand where your traffic comes from:

- **Requests by hour** — hourly distribution chart
- **Top 10 ASN** — which networks generate the most requests
- **Request map** — geographic visualization of request origins
- **App breakdown** — see which applications are being used

</details>

<details>
<summary><b>💰 Infrastructure Billing</b></summary>
<br>

Track your hosting costs and payment schedules:

- **Billing nodes** — assign nodes to hosting providers with billing dates
- **Payment history** — full log of all payments
- **Provider management** — organize nodes by hosting provider
- **Upcoming payments** — never miss a billing deadline
- **Monthly spending** overview and total spend tracking
- **Mark as paid** — update billing dates with one tap

</details>

<details>
<summary><b>🔔 Push Notifications</b></summary>
<br>

Stay informed with instant alerts:

- **Node events** — offline/online, created, modified, deleted
- **User events** — created, disabled, expired, first connection, traffic limits
- **Subscription alerts** — expiring in 72h/48h/24h, already expired
- **Billing reminders** — upcoming payments, overdue alerts
- **Service events** — panel started, login attempts
- **Granular control** — enable/disable individual notification categories and events

</details>

<details>
<summary><b>💻 SSH Terminal</b></summary>
<br>

Connect to your servers without leaving the app:

- **Built-in terminal** — full SSH access to any node
- **Multiple auth methods** — password or key file (OpenSSH, PEM, PKCS#8)
- **Secure storage** — credentials stored in iOS Keychain / Android EncryptedSharedPreferences
- **Command presets** — save and reuse frequently used commands with one tap
- **Per-node configuration** — different credentials for each server

</details>

<details>
<summary><b>👥 Squads</b></summary>
<br>

Organize users into groups for easier management.

</details>

<details>
<summary><b>⚙️ Subscription Settings</b></summary>
<br>

Configure subscription behavior from your phone:

- Profile title and support link
- Update interval control
- Host randomization
- HWID (hardware ID) device limiting
- Custom remark messages for different user states
- Custom response headers

</details>

<details>
<summary><b>📱 Home Screen Widgets</b></summary>
<br>

Key metrics available at a glance without opening the app:

- **Online Users** widget — small and medium sizes
- **Download Speed** widget — small and medium sizes
- **Today's Traffic** widget — small and medium sizes
- **Combined Dashboard** widget — large size (Android)
- Configurable refresh interval
- Customizable chart time range and traffic period

</details>

<details>
<summary><b>🔒 Security</b></summary>
<br>

Protect the app with biometric authentication:

- **iOS:** Face ID / Touch ID / Optic ID
- **Android:** Fingerprint / PIN / Pattern / Device password
- Auto-lock when the app goes to background
- Passcode fallback

</details>

<details>
<summary><b>🎨 Customization</b></summary>
<br>

Make the app yours:

- **Tab bar customization** — choose which tabs appear in the main bar
- **App icon picker** — multiple icon styles to choose from
- **Auto-refresh settings** — configure polling intervals for live data

</details>

---

## 📸 Screenshots

> *Screenshots coming soon*

---

## 📋 Requirements

| | |
|---|---|
| **iOS** | iOS 17.0 or later (iPhone or iPad) |
| **Android** | Android 8.0 (API 26) or later |
| **Server** | A running [Remnawave](https://github.com/remnawave) panel instance |

---

## 📥 Installation

<p align="center">
  <a href="https://apps.apple.com/us/app/wave-machine/id6760419820">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="68" style="vertical-align: middle;" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/egvill/RWA-Mobile-App/releases/latest">
    <img src="https://img.shields.io/github/downloads/egvill/RWA-Mobile-App/total?style=for-the-badge&logo=android&label=Download%20Android&color=34A853" alt="Download Android" height="40" style="vertical-align: middle;" />
  </a>
  <!-- <a href="https://play.google.com/store/apps/details?id=com.rwpanel.adminmonitor"> -->
    <!-- <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="68" style="vertical-align: middle;" /> -->
  <!-- </a> -->
</p>

---

## 🚀 Getting Started

1. **Install** the app on your device
2. **Open** RWA — a guided onboarding will walk you through the setup
3. **Connect** to your Remnawave panel by entering the panel URL and API key
4. **Explore** the dashboard, manage users, monitor nodes, and more

---

## 🌍 Localization

| Language | Status |
|----------|--------|
| 🇷🇺 Russian | ✅ Fully supported |
| 🇺🇸 English | ✅ Fully supported |

---

## 🔐 Privacy

- All data is transmitted directly between your device and your Remnawave panel
- SSH credentials are stored securely in iOS Keychain / Android EncryptedSharedPreferences (AES-256)
- No user data is collected or shared with third parties
- Firebase is used solely for push notification delivery and basic analytics

---

## 📄 License

This project is proprietary software. All rights reserved.

---

<p align="center">
  Made with ❤️ for the <a href="https://github.com/BEDOLAGA-DEV">Bedolaga</a> and Remnawave community
</p>
