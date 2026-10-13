# Portfolio — Ruslan Kovalchuk / Портфолио

**Full-Stack Developer** · B2B automation · CRM · payments · scraping · Linux bring-up
Taiwan · Remote · [GitHub](https://github.com/Arctillect-RK) · [Telegram](https://t.me/Arctillect)

---

## 🇷🇺 Русский

### О себе
Делаю сквозные продукты: **сайт → калькулятор/конфигуратор → CRM → оплата → боты/парсеры**, а также
железо и системный уровень (порт mainline Linux на телефон). Коммерческие сайты ниже **до сих пор в проде**.

В каждом публичном репозитории README на **двух языках** (RU + EN): что это, стек, зачем каждая часть, поток.

### Публичные проекты (с кодом)

| Проект | Live | Стек (кратко) | Для чего |
|--------|------|----------------|----------|
| [vsesteklo](https://github.com/Arctillect-RK/vsesteklo) | [сайт](https://vsesteklo.ru/) · [CRM](https://crm.vsesteklo.ru/) | HTML/JS + **Vue CRM** + Node | Стекло: сайт + прайс + калькулятор + заявки + парсер |
| [directbeza](https://github.com/Arctillect-RK/directbeza) | [directbeza.ru](https://directbeza.ru/) | HTML/JS + **PHP/ЮKassa** + Node | Готовые РК Директ: каталог → оплата → доступ |
| [arborika](https://github.com/Arctillect-RK/arborika) | [arborika.ru](https://arborika.ru/) | HTML/CSS/Tailwind/JS | Мастерская столов: каталог + конфигуратор + заявки |
| [bristol-test](https://github.com/Arctillect-RK/bristol-test) | [bristol-test.ru](https://bristol-test.ru/) | **PHP + ЮKassa** + TG | Платный портал тестов + токен доступа |
| [magnit-test](https://github.com/Arctillect-RK/magnit-test) | [magnit-test.ru](https://www.magnit-test.ru/) | **PHP + ЮKassa** + TG | То же для Магнит Магнум |
| [arctos-redmi-note-8t](https://github.com/Arctillect-RK/arctos-redmi-note-8t) | — | **mainline Linux / postmarketOS / Phosh** | ArctOS: порт Linux на Redmi Note 8T, дисплей/GPU/Wi-Fi/модем + UI в стиле iOS |
| [webp-converter](https://github.com/Arctillect-RK/webp-converter) | — | Windows / Python | Пакетная конвертация PNG/JPEG/HEIC/AVIF/… → WebP |

### Приватные продукты (в проде, только ссылки — исходники закрыты)

Коммерческие проекты: показываю рабочий продукт, код не выкладываю.

| Продукт | Live | Стек (кратко) | Для чего |
|--------|------|----------------|----------|
| **AllFL** | [allfl.ru](https://allfl.ru/) | **Nuxt 4** / Vue 3 / Prisma / MySQL / ЮKassa | Фриланс-биржа без ленты откликов: система сама подбирает одного исполнителя из пула (очередь + веса), заказчик платит за размещение, исполнитель — комиссию только с выполненного. Эскроу, уровни, промо, гарантия «не нашли за 24 ч — размещение за наш счёт». |
| **РестаALL** | [restaall.ru](https://restaall.ru/) · [для заведений](https://restaall.ru/for-restaurants) · [для курьеров](https://restaall.ru/for-couriers) | Next.js 16 / React 19 / web-push | Витрина кафе и ресторанов небольшого города: заказ на сайте, доставка силами заведения, админка в браузере, push на новый заказ. Первое заведение — «Чёрная жемчужина». |
| **Такси Сасово** | [taxi.restaall.ru](https://taxi.restaall.ru/) | Next.js 16 / React 19 / web-push / ЮKassa | Заказ такси без карты: клиент пишет адрес текстом, видит ожидание и выбирает оплату. Кабинеты клиента/водителя/админа, раздача заказов по очереди на сервере, платное ожидание, push. |
| **SEO / scraping-набор** | — | Python | Продаваемые инструменты: Яндекс SERP + подсказки, парсер промо-объявлений и контактов, выгрузка в Excel. |
| **KP-бот** | — | Python / Telegram / SMTP | Поиск компаний (DuckDuckGo / 2ГИС / Яндекс), аудит их сайтов (калькулятор, форма, оплата, мобильная версия), подбор КП под «дыры» и рассылка с ручным подтверждением в Telegram. |

### Флагман — Vsesteklo CRM
Операционка стекольного бизнеса: прайс-контроль, инженерный калькулятор, заявки, парсер, модерация отзывов, роли.
Подробно: [vsesteklo/CRM.md](https://github.com/Arctillect-RK/vsesteklo/blob/main/CRM.md)

### Железо / система — ArctOS
Порт **mainline Linux (postmarketOS, ядро 7.2, Phosh)** на Xiaomi Redmi Note 8T (willow, SM6125):
с нуля подняты дисплей (DPU/DSI + своя панель), тачскрин, GPU Adreno 610, Wi-Fi WCN3990, Bluetooth,
датчики/автоповорот, модем, плюс перекроенный под iOS-подобный интерфейс Phosh.
Весь код, патчи ядра, драйверы и пошаговая инструкция: [arctos-redmi-note-8t](https://github.com/Arctillect-RK/arctos-redmi-note-8t).

---

## 🇬🇧 English

### About
I ship end-to-end products: **website → calculator/configurator → CRM → payments → bots/scrapers**, and I also
work at the hardware/system level (mainline Linux phone port). Commercial sites below are **still live in production**.

Each public repository has a **bilingual README** (RU + EN): overview, stack table, and flow.

### Public projects (with source)

| Project | Live | Stack (short) | Purpose |
|---------|------|---------------|---------|
| [vsesteklo](https://github.com/Arctillect-RK/vsesteklo) | [site](https://vsesteklo.ru/) · [CRM](https://crm.vsesteklo.ru/) | HTML/JS + **Vue CRM** + Node | Glass: site + prices + calculator + leads + parsers |
| [directbeza](https://github.com/Arctillect-RK/directbeza) | [directbeza.ru](https://directbeza.ru/) | HTML/JS + **PHP/YooKassa** + Node | Ready Direct campaigns: catalog → pay → access |
| [arborika](https://github.com/Arctillect-RK/arborika) | [arborika.ru](https://arborika.ru/) | HTML/CSS/Tailwind/JS | Custom tables workshop: catalog + configurator + leads |
| [bristol-test](https://github.com/Arctillect-RK/bristol-test) | [bristol-test.ru](https://bristol-test.ru/) | **PHP + YooKassa** + TG | Paid test portal + timed access |
| [magnit-test](https://github.com/Arctillect-RK/magnit-test) | [magnit-test.ru](https://www.magnit-test.ru/) | **PHP + YooKassa** + TG | Same pattern for Magnit Magnum |
| [arctos-redmi-note-8t](https://github.com/Arctillect-RK/arctos-redmi-note-8t) | — | **mainline Linux / postmarketOS / Phosh** | ArctOS: Linux port for Redmi Note 8T — display/GPU/Wi-Fi/modem + iOS-style UI |
| [webp-converter](https://github.com/Arctillect-RK/webp-converter) | — | Windows / Python | Batch PNG/JPEG/HEIC/AVIF/… → WebP converter |

### Private products (in production, links only — source closed)

Commercial projects: I show the live product, source stays private.

| Product | Live | Stack (short) | Purpose |
|--------|------|----------------|---------|
| **AllFL** | [allfl.ru](https://allfl.ru/) | **Nuxt 4** / Vue 3 / Prisma / MySQL / YooKassa | Freelance marketplace without a bidding feed: the system matches a single freelancer from a weighted pool; client pays for placement, freelancer pays commission only on completed work. Escrow, levels, promos, "no match in 24h — placement on us" guarantee. |
| **RestaALL** | [restaall.ru](https://restaall.ru/) · [for venues](https://restaall.ru/for-restaurants) · [for couriers](https://restaall.ru/for-couriers) | Next.js 16 / React 19 / web-push | Small-town restaurant storefront: order on the site, delivery by the venue itself, browser admin, push on new orders. First venue — "Black Pearl". |
| **Taxi Sasovo** | [taxi.restaall.ru](https://taxi.restaall.ru/) | Next.js 16 / React 19 / web-push / YooKassa | Map-free taxi ordering: client types the address, sees the wait and picks payment. Client/driver/admin cabinets, server-side round-robin dispatch, paid waiting, push. |
| **SEO / scraping toolkit** | — | Python | Sold tools: Yandex SERP + suggestions, promo-ad & contact scraper, Excel export. |
| **KP bot** | — | Python / Telegram / SMTP | Finds companies (DuckDuckGo / 2GIS / Yandex), audits their sites (calculator, form, payments, mobile), matches a pitch to the gaps and emails it with manual confirmation in Telegram. |

### Flagship — Vsesteklo CRM
Day-to-day ops for glass manufacturing: price control, engineering calculator, leads, parsers, review moderation, roles.
Details: [vsesteklo/CRM.md](https://github.com/Arctillect-RK/vsesteklo/blob/main/CRM.md)

### Hardware / system — ArctOS
A **mainline Linux (postmarketOS, kernel 7.2, Phosh)** port to the Xiaomi Redmi Note 8T (willow, SM6125):
display (DPU/DSI + a custom panel driver), touch, Adreno 610 GPU, WCN3990 Wi-Fi, Bluetooth, sensors/auto-rotate
and modem brought up from scratch, plus a Phosh reworked into an iOS-like UI.
Full code, kernel patches, drivers and a step-by-step guide: [arctos-redmi-note-8t](https://github.com/Arctillect-RK/arctos-redmi-note-8t).

---

## Contact / Контакты

Telegram: [@Arctillect](https://t.me/Arctillect) · GitHub: [Arctillect-RK](https://github.com/Arctillect-RK)
