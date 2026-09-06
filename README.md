# 👋 Привет, я Дмитрий

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%">
  <defs>
    <linearGradient id="paperGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#fef9e7;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f5e6c8;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="rollGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#d4a574;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#8b6f47;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#d4a574;stop-opacity:1" />
    </linearGradient>
    <filter id="shadow">
      <feDropShadow dx="2" dy="4" stdDeviation="3" flood-opacity="0.3"/>
    </filter>
  </defs>
  
  <!-- Рулон бумаги (левый) -->
  <ellipse cx="50" cy="100" rx="25" ry="80" fill="url(#rollGrad)" filter="url(#shadow)">
    <animate attributeName="rx" values="25;25;25" dur="3s" begin="0s" fill="freeze"/>
  </ellipse>
  
  <!-- Развёртывающаяся бумага -->
  <rect x="50" y="20" width="0" height="160" fill="url(#paperGrad)" filter="url(#shadow)">
    <animate attributeName="width" values="0;700" dur="2.5s" begin="0.5s" fill="freeze" calcMode="spline" keySplines="0.25 0.1 0.25 1"/>
  </rect>
  
  <!-- Текстура бумаги (линии) -->
  <g opacity="0.1">
    <line x1="50" y1="50" x2="750" y2="50" stroke="#8b6f47" stroke-width="0.5">
      <animate attributeName="x2" values="50;750" dur="2.5s" begin="0.5s" fill="freeze"/>
    </line>
    <line x1="50" y1="80" x2="750" y2="80" stroke="#8b6f47" stroke-width="0.5">
      <animate attributeName="x2" values="50;750" dur="2.5s" begin="0.5s" fill="freeze"/>
    </line>
    <line x1="50" y1="110" x2="750" y2="110" stroke="#8b6f47" stroke-width="0.5">
      <animate attributeName="x2" values="50;750" dur="2.5s" begin="0.5s" fill="freeze"/>
    </line>
    <line x1="50" y1="140" x2="750" y2="140" stroke="#8b6f47" stroke-width="0.5">
      <animate attributeName="x2" values="50;750" dur="2.5s" begin="0.5s" fill="freeze"/>
    </line>
  </g>
  
  <!-- Текст слогана -->
  <text x="400" y="85" font-family="Georgia, serif" font-size="22" font-weight="bold" fill="#2c3e50" text-anchor="middle" opacity="0">
    Делаю то, что работает сегодня.
    <animate attributeName="opacity" values="0;1" dur="1s" begin="2s" fill="freeze"/>
  </text>
  <text x="400" y="125" font-family="Georgia, serif" font-size="22" font-weight="bold" fill="#2c3e50" text-anchor="middle" opacity="0">
    Изучаю то, что будет работать завтра.
    <animate attributeName="opacity" values="0;1" dur="1s" begin="2.5s" fill="freeze"/>
  </text>
  
  <!-- Декоративные элементы -->
  <circle cx="750" cy="100" r="8" fill="#e74c3c" opacity="0">
    <animate attributeName="opacity" values="0;0.8" dur="0.5s" begin="3s" fill="freeze"/>
    <animate attributeName="r" values="0;8" dur="0.5s" begin="3s" fill="freeze"/>
  </circle>
  <circle cx="730" cy="100" r="5" fill="#f39c12" opacity="0">
    <animate attributeName="opacity" values="0;0.6" dur="0.5s" begin="3.2s" fill="freeze"/>
    <animate attributeName="r" values="0;5" dur="0.5s" begin="3.2s" fill="freeze"/>
  </circle>
</svg>

> **Делаю то, что работает сегодня.  Изучаю то, что будет работать завтра.**

---

![Вайб-кодер](https://img.shields.io/badge/🎵_Вайб--кодер-Open_Code-8A2BE2?style=for-the-badge)
![Статус](https://img.shields.io/badge/🟢_Открыт_к_проектам-да-2ECC71?style=for-the-badge)
![Обучение](https://img.shields.io/badge/📚_Учусь_в-Zerocoder-FF6B35?style=for-the-badge)
![Подход](https://img.shields.io/badge/⚡_MVP-за_дни,_не_месяцы-3498DB?style=for-the-badge)

---

## 🧑‍💻 Кто я

Начинающий фрилансер с техническим складом ума и основной работой, которая не связана с IT. Фриланс для меня — это **дополнительный заработок + полигон для освоения вайб-кодинга**, который стремительно меняет индустрию. Я уверен: навыки, которые я прокачиваю сегодня, помогут мне и на основной работе завтра.

> 🎯 Мой принцип: не писать ТЗ на 40 страниц, а **быстро собирать работающий продукт** и доводить его до результата.

---

## 🔄 Мой процесс вайб-кодинга

💡 **Идея**  
↓  
✍️ **Промпт в Open Code**  
↓  
🤖 **AI генерирует MVP**  
↓  
🔍 *Консультация с QWEN (если нужно)*  
↓  
🛠️ **Доработка и тестирование**  
↓  
✅ **Готовый продукт**

Я не просто «нажимаю кнопку» в нейросети. Я ставлю задачу, контролирую результат и **отвечаю за то, что отдаю клиенту**.

---

## 📂 Мои проекты

### 🌐 Сайты (6 штук)

Создаю современные сайты под задачи клиента. Один из проектов включает **интерактивный калькулятор расчётов**, встроенный прямо на страницу.

> *Результат: рабочий сайт, переданный клиенту.*

---

### 🤖 ВК-бот «Блюда от бот-повара»

Чат-бот для сообщества ВКонтакте, который отвечает пользователям с помощью **искусственного интеллекта через ProxyAPI**. Бот ведёт диалог, а не просто выдаёт заготовленные ответы.

> *Результат: живой, интерактивный бот для реального сообщества.*

---

### 🏊 Конструктор бассейнов с 3D-визуализацией

Калькулятор с **3D-визуализацией изменения размера бассейна** в реальном времени + расчёт необходимого оборудования. Да, визуально получилось скромно, но сам принцип интерактивного 3D — реализован.

> *Результат: работающий инструмент с визуалом и расчётами.*

---

## 🧰 Что я умею

| Область | Детали |
|---|---|
| 🌐 Сайты | Лендинги, многостраничники, встроенные калькуляторы |
| 🤖 Чат-боты | ВКонтакте, интеграция AI через ProxyAPI |
| 📐 Калькуляторы | Расчёты, 3D-визуализация, подбор оборудования |
| 🎵 Вайб-кодинг | Open Code, промпт-инжиниринг, работа с AI |
| 📚 Обучение | Курс в Zerocoder, постоянное расширение кругозора |

---

## 🙋 Почему со мной стоит работать

- ✅ **Довожу до конца** — не бросаю проект на полпути
- ✅ **Ответственный** — соблюдаю сроки и договорённости
- ✅ **Коммуникабельный** — всегда на связи, объясняю простым языком
- ✅ **Добрый и отзывчивый** — мне важно, чтобы клиент остался доволен
- ✅ **Быстро учусь** — сегодня делаю сайты, завтра осваиваю новый инструмент

---

## 📫 Связаться со мной

Готов обсудить ваш проект — **сайт, бот, калькулятор или что-то новое**. Пишите, договоримся!

| Канал | Контакт |
|---|---|
| 📱 **MAX** | Личные сообщения |
| 📱 **WhatsApp** | Личные сообщения |
| 📧 **Email** | [DmmShiryev@yandex.ru](mailto:DmmShiryev@yandex.ru) |

---

<p align="center">
  <i>«Делаю то, что работает сегодня. Изучаю то, что будет работать завтра.»</i>
</p>

<p align="center">
  Ваша идея + мой промпт = готовый продукт. ⭐ за поддержку, ЛС — за сотрудничество.
Заглянули на профиль? Спасибо. Поставьте ⭐ — мне будет приятно. А если есть проект — давайте сделаем его вместе.
</p>
