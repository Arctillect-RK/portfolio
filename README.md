# Portfolio — Ruslan Kovalchuk

**Full-Stack Developer** · B2B automation · CRM · payments · scraping  
Taiwan · Remote · [GitHub](https://github.com/Arctillect-RK) · [Telegram](https://t.me/Arctillect)

> Коммерческие сайты ниже **до сих пор в проде** (не мёртвые демки).

В каждом репо — README: **стек / зачем каждая часть / поток**.

---

## Проекты

### 1. [Vsesteklo](https://github.com/Arctillect-RK/vsesteklo) — **флагман**
| | |
|--|--|
| **Live** | [vsesteklo.ru](https://vsesteklo.ru/) · **[crm.vsesteklo.ru](https://crm.vsesteklo.ru/)** |
| **Стек** | HTML/CSS/JS (сайт) · **Vue SPA (CRM)** · **Node** API · parser |
| **Для чего** | Производство стекла: сайт + операционка (прайс, калькулятор, заявки, парсер, отзывы, роли) |
| **Док** | [CRM.md](https://github.com/Arctillect-RK/vsesteklo/blob/main/CRM.md) |

### 2. [DirectBeza](https://github.com/Arctillect-RK/directbeza)
| | |
|--|--|
| **Live** | [directbeza.ru](https://directbeza.ru/) |
| **Стек** | HTML/JS витрина · **PHP + ЮKassa** (оплата/webhook) · **Node/Express** (локальный API) |
| **Для чего** | Готовые РК Яндекс.Директ: каталог → оплата → выдача доступа |

### 3. [Arborika](https://github.com/Arctillect-RK/arborika)
| | |
|--|--|
| **Live** | [arborika.ru](https://arborika.ru/) |
| **Стек** | HTML · CSS/Tailwind · JS · SEO |
| **Для чего** | Мастерская столов: каталог, материалы, заявки |

### 4. [Bristol-Test](https://github.com/Arctillect-RK/bristol-test)
| | |
|--|--|
| **Live** | [bristol-test.ru](https://bristol-test.ru/) |
| **Стек** | **PHP** · **ЮKassa** · Telegram · токены доступа |
| **Для чего** | Платный портал ответов: оплата → сессия с поиском |

### 5. [Magnit-Test](https://github.com/Arctillect-RK/magnit-test)
| | |
|--|--|
| **Live** | [magnit-test.ru](https://www.magnit-test.ru/) |
| **Стек** | **PHP** · **ЮKassa** (общий webhook с metadata) · Telegram |
| **Для чего** | То же для тестов Магнит Магнум |

### 6. [SEO Combine](https://github.com/Arctillect-RK/seo-combine)
| | |
|--|--|
| **Тип** | локальный инструмент |
| **Стек** | **Node.js** · **Puppeteer** (+ stealth) · HTML UI |
| **Для чего** | Подсказки Яндекса + SERP + кластеры + Excel |

### 7. [Promo Parser](https://github.com/Arctillect-RK/promo-parser)
| | |
|--|--|
| **Тип** | локальный веб-инструмент |
| **Стек** | **Python FastAPI** · **Playwright** · SQLite · openpyxl |
| **Для чего** | Промо из SERP + контакты с сайтов + прокси/капча |

---

## Сводный стек

| Слой | Где используется |
|------|------------------|
| **PHP** | DirectBeza оплата, Bristol, Magnit |
| **Node.js** | Vsesteklo API/parser, DirectBeza local, SEO Combine |
| **Python** | Promo Parser (FastAPI) |
| **Vue** | Vsesteklo CRM SPA |
| **HTML/CSS/JS** | все публичные сайты |
| **ЮKassa + webhooks** | DirectBeza, Bristol, Magnit |
| **Puppeteer / Playwright** | SEO Combine, Promo Parser |
| **Telegram bots** | уведомления о заказах/лидах |

---

## Contact

Telegram: [@Arctillect](https://t.me/Arctillect) · GitHub: [Arctillect-RK](https://github.com/Arctillect-RK)
