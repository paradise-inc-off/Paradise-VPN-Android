<p align="center">
  <img src="assets/banner.png" alt="Баннер" width="70%">
  <img src="assets/Preview-1.png" alt="Превью" width="20%">
</p>

<p align="center">
<a href="https://github.com/paradise-inc-off/Paradise-VPN-Android/stargazers"><img src="https://img.shields.io/github/stars/paradise-inc-off/Paradise-VPN-Android?style=for-the-badge&logo=github" alt="GitHub Stars"></a>
<a href="https://github.com/paradise-inc-off/Paradise-VPN-Android/releases"><img src="https://img.shields.io/github/downloads/paradise-inc-off/Paradise-VPN-Android/total?style=for-the-badge&logo=github" alt="Downloads"></a>
<a href="https://github.com/paradise-inc-off/Paradise-VPN-Android/releases/latest"><img src="https://img.shields.io/github/v/release/paradise-inc-off/Paradise-VPN-Android?style=for-the-badge&logo=github" alt="Latest Release"></a>
<a href="https://github.com/paradise-inc-off/Paradise-VPN-Android/releases/latest"><img src="https://img.shields.io/github/release-date/paradise-inc-off/Paradise-VPN-Android?style=for-the-badge&logo=github" alt="Release Date"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android 8+">
  <img src="https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin">
  <a href="https://www.virustotal.com/gui/file/eef5bcb36fe40ff6f25c921b28082caebba4ba6a642c012a2650e4ea558ee45f">
    <img src="https://img.shields.io/badge/VirusTotal-Проверить-394EFF?style=for-the-badge&logo=virustotal&logoColor=white" alt="VirusTotal">
  </a>
</p>

Официальный Android-клиент **Paradise VPN** с нативным VPN-подключением, современным Material 3 Expressive интерфейсом и управлением аккаунтом прямо из приложения.

> Актуальная версия: **0.9.0**

---

## ✨ Возможности

* 🔐 Нативное VPN-подключение через Android `VpnService`
* ⚡ Xray-core Native TUN
* 🌐 TCP / UDP, IPv4 / IPv6
* 🌍 Автоматический режим **Auto** и ручной выбор локации
* 👤 Вход и регистрация по Email
* ✈️ Авторизация через Telegram
* 🎁 Активация пробного периода
* 💳 Управление подпиской и оплатой
* 🎟️ Промокоды и баланс
* 📱 Управление устройствами
* 🎁 Реферальная система и подарки
* 💬 Обращения в поддержку
* ⚡ Плитка VPN в быстрых настройках Android
* 🇷🇺 Русский и 🇬🇧 English
* 🔄 Автоматическое обновление конфигурации серверов

---

## 🔐 VPN

Paradise VPN использует системный Android `VpnService` и нативный **Xray-core TUN**.

```text
Android-приложения
        ↓
Android VpnService
        ↓
Xray TUN
        ↓
Paradise VPN
        ↓
VPN-сервер
        ↓
Интернет
```

Приложение получает готовую конфигурацию от инфраструктуры Paradise VPN и поддерживает серверную балансировку, DNS, маршрутизацию и автоматический выбор серверов.

Режим **Auto** самостоятельно использует актуальную серверную конфигурацию, а при необходимости пользователь может выбрать конкретную локацию вручную.

---

## 👤 Аккаунт и подписка

Большинство функций Paradise VPN доступны без перехода в Telegram-бот или браузер:

* профиль;
* подписка;
* продление;
* способы оплаты;
* баланс;
* промокоды;
* устройства;
* автоплатёж;
* реферальная система;
* подарки;
* поддержка.

Новые пользователи могут зарегистрироваться и активировать доступный пробный период непосредственно в приложении.

---

## ⚡ Быстрое подключение

Paradise VPN можно добавить в **быстрые настройки Android**.

Плитка позволяет:

* подключить последнюю выбранную локацию или `Auto`;
* отключить VPN повторным нажатием;
* видеть текущее состояние подключения без открытия приложения.

---

## 🎨 Интерфейс

Приложение создано на современном Android-стеке:

`Kotlin` · `Jetpack Compose` · `Material 3 Expressive` · `Navigation 3` · `Haze`

Поддерживаются эффекты Blur / Glass, Expressive Motion и отдельный onboarding при первом запуске.

---

## 🛡️ Безопасность

Данные авторизации хранятся в зашифрованном виде с использованием **Android Keystore + AES/GCM**.

Чувствительные серверные ключи и административные данные не хранятся внутри APK.

### SHA-256 — Paradise VPN 0.8.6

```text
EEF5BCB36FE40FF6F25C921B28082CAEBBA4BA6A642C012A2650E4EA558EE45F
```

[![VirusTotal](https://img.shields.io/badge/VirusTotal-Открыть%20отчёт-394EFF?style=for-the-badge\&logo=virustotal\&logoColor=white)](https://www.virustotal.com/gui/file/eef5bcb36fe40ff6f25c921b28082caebba4ba6a642c012a2650e4ea558ee45f)

---

## 📥 Установка

1. Откройте [Releases](https://github.com/paradise-inc-off/Paradise-VPN-Android/releases).
2. Выберите последнюю версию.
3. Скачайте `.apk` из раздела **Assets**.
4. Откройте APK на Android-устройстве.
5. Разрешите установку из этого источника, если Android попросит.
6. Установите и запустите Paradise VPN.
7. Войдите в аккаунт или зарегистрируйтесь.

При первом подключении Android попросит разрешение на создание VPN-подключения.

> Скачивайте Paradise VPN только из официального GitHub-репозитория или с официальных ресурсов Paradise VPN.

---

## 🔗 Официальные ресурсы

🌐 **Сайт:** https://paradisevpn.su

📢 **Telegram:** [@para_dise_vpn](https://t.me/para_dise_vpn)

🤖 **Telegram-бот:** [@paradise_vpn_bot](https://t.me/paradise_vpn_bot)

👤 **Личный кабинет:** https://cabinet.paradisevpn.su

---

<p align="center">
  <b>Paradise VPN for Android</b><br>
  Быстро. Удобно. Нативно.
</p>
