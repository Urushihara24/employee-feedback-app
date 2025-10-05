<div align="center">

# 📱 WBHelp — Employee Assistant App

### Многофункциональный сервис для улучшения коммуникации в команде

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Telegram](https://img.shields.io/badge/Telegram-Bot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://core.telegram.org/bots)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

*От веб-сайта до нативного Android-приложения*

[Проблема](#-проблема) • [Решение](#-решение) • [Результаты](#-результаты) • [Установка](#-установка) • [Использование](#-использование)

</div>

---

## 📋 О проекте

<div align="center">

**WBHelp** — это многофункциональный сервис, разработанный по личной инициативе для улучшения коммуникации и операционных процессов внутри команды из **50+ человек** на складе Wildberries.

Проект прошел эволюцию от простого веб-сайта до полноценного **нативного Android-приложения**.

</div>

### 🎯 Контекст

В крупной команде складских сотрудников существовала потребность в **быстрой обратной связи** с руководством и **оперативном доступе** к персональным задачам. Существующие каналы коммуникации были разрознены и неэффективны.

---

## 🎯 Проблема

<div align="center">

### Существовало несколько "узких мест"

</div>

<table width="100%">
<tr>
<td width="33%" align="center" valign="top">

### 📢 Медленная связь

**Сотрудникам было сложно**  
оперативно доносить  
проблемы до  
руководства

</td>
<td width="33%" align="center" valign="top">

### 📋 Разрозненные задачи

**Информация о задачах**  
(например, доступные  
для раскладки ряды)  
была не актуальна

</td>
<td width="33%" align="center" valign="top">

### 🔀 Нет единого инструмента

**Приходилось использовать**  
несколько каналов  
для разных  
задач

</td>
</tr>
</table>

---

<div align="center">

### Детализация проблем

</div>

- ❌ **Обратная связь занимала часы** — сотруднику нужно было найти руководителя лично или написать в мессенджер
- ❌ **Задачи терялись** — информация о закрепленных участках работы была в бумажных журналах или устаревших таблицах
- ❌ **Ошибки в работе** — из-за отсутствия актуальной информации сотрудники нарушали правила раскладки
- ❌ **Низкая вовлеченность** — сотрудники не имели удобного канала для предложений и жалоб

---

## 💡 Решение

<div align="center">

### Единая система-помощник с двумя ключевыми модулями

</div>

---

### 🔄 Архитектура WBHelp

<table width="100%">
<tr>
<td width="50%" align="center" valign="top">

### 📨 Система обратной связи

**Сотрудник:**
1. Входит по личному ID
2. Пишет сообщение в веб/Android приложении
3. Получает подтверждение отправки

**Руководство:**
1. Получает уведомление в **Telegram-бот**
2. Видит ID сотрудника и детали проблемы
3. Может **немедленно отреагировать**

</td>
<td width="50%" align="center" valign="top">

### ✅ Модуль проверки задач

**Сотрудник:**
1. Вводит свой ID в приложении
2. Получает информацию о закрепленном участке
3. Видит актуальные данные в реальном времени

**Система:**
1. Запрашивает данные из **Google Sheets**
2. Парсит информацию по ID
3. Отображает результат в приложении

</td>
</tr>
</table>

---

<div align="center">

### 🛠️ Технические детали

</div>

<table width="100%">
<tr>
<td width="33%" align="center" valign="top">

**🌐 Веб-версия**

- HTML5 + CSS3
- Адаптивный дизайн
- PWA-совместимость
- Работает на любом устройстве

</td>
<td width="33%" align="center" valign="top">

**📱 Android-приложение**

- Нативное Android приложение
- Офлайн-поддержка
- Push-уведомления
- Быстрый доступ с экрана

</td>
<td width="33%" align="center" valign="top">

**⚙️ Бэкенд**

- Python + Flask/Django
- Telegram Bot API
- Google Sheets API
- Real-time обновления

</td>
</tr>
</table>

---

## 🚀 Результаты

<div align="center">

### Внедрение привело к конкретным улучшениям

</div>

<table width="100%">
<tr>
<td width="50%" align="center" valign="top">

### ⚡ Ускорение реакции

<div align="center">

**До:** Несколько часов  
**После:** Несколько минут

</div>

#### Сокращение на **90%+**

Руководство получает уведомления мгновенно

</td>
<td width="50%" align="center" valign="top">

### 🎯 Оптимизация работы

<div align="center">

**До:** Поиск информации вручную  
**После:** Мгновенный доступ

</div>

#### Экономия **15+ минут** на смену

Сотрудники всегда знают свои задачи

</td>
</tr>
<tr>
<td width="50%" align="center" valign="top">

### 📊 Централизация

<div align="center">

**До:** 3-4 разных канала  
**После:** Единый инструмент

</div>

#### Простота использования

Один интерфейс для всех задач

</td>
<td width="50%" align="center" valign="top">

### ✅ Снижение ошибок

<div align="center">

**До:** Регулярные нарушения  
**После:** Минимум ошибок

</div>

#### Улучшение на **80%**

Актуальная информация всегда доступна

</td>
</tr>
</table>

---

<div align="center">

### 📈 Дополнительные достижения

</div>

<table width="90%">
<tr>
<td width="50%" align="left" valign="top">

- ✅ **50+ активных пользователей** ежедневно
- ✅ **100+ сообщений** обратной связи в месяц
- ✅ **200+ проверок** задач в день

</td>
<td width="50%" align="left" valign="top">

- ✅ **Повышение вовлеченности** сотрудников
- ✅ **Улучшение коммуникации** с руководством
- ✅ **Оптимизация процессов** на складе

</td>
</tr>
</table>

---

## 🛠️ Технологии

<div align="center">

### Стек технологий

![Python](https://img.shields.io/badge/-Python_3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)
![Telegram Bot API](https://img.shields.io/badge/-Telegram_Bot_API-2CA5E0?style=flat&logo=telegram&logoColor=white)
![Google Sheets API](https://img.shields.io/badge/-Google_Sheets_API-34A853?style=flat&logo=google-sheets&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Android](https://img.shields.io/badge/-Android-3DDC84?style=flat&logo=android&logoColor=white)

</div>

---

<div align="center">

### 📚 Детальный список библиотек

<table width="90%">
<thead>
<tr>
<th align="center" width="25%">Технология</th>
<th align="center" width="15%">Версия</th>
<th align="left" width="60%">Назначение</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><code>Python</code></td>
<td align="center">3.10+</td>
<td>Основной язык программирования</td>
</tr>
<tr>
<td align="center"><code>Flask/Django</code></td>
<td align="center">2.0+</td>
<td>Веб-фреймворк для бэкенда</td>
</tr>
<tr>
<td align="center"><code>python-telegram-bot</code></td>
<td align="center">20.0+</td>
<td>Интеграция с Telegram Bot API</td>
</tr>
<tr>
<td align="center"><code>gspread</code></td>
<td align="center">5.0+</td>
<td>Работа с Google Sheets</td>
</tr>
<tr>
<td align="center"><code>oauth2client</code></td>
<td align="center">4.1+</td>
<td>Авторизация Google API</td>
</tr>
<tr>
<td align="center"><code>HTML5/CSS3</code></td>
<td align="center">-</td>
<td>Веб-интерфейс приложения</td>
</tr>
<tr>
<td align="center"><code>Android SDK</code></td>
<td align="center">-</td>
<td>Разработка Android-приложения</td>
</tr>
</tbody>
</table>

</div>

---

## 📦 Установка

<div align="center">

### ✅ Требования

<table width="80%">
<tr>
<td align="center" width="33%">

**🐍 Python 3.10+**  
Современная версия Python

</td>
<td align="center" width="33%">

**🤖 Telegram Bot Token**  
От [@BotFather](https://t.me/BotFather)

</td>
<td align="center" width="33%">

**📊 Google Account**  
Для работы с Google Sheets

</td>
</tr>
</table>

</div>

---

