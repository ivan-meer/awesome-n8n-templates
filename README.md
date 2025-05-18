
![](assets\banner.jpg)

<div align="center">

# 🚀 Awesome n8n Templates

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

*Коллекция продвинутых шаблонов автоматизации для платформы n8n*

[📚 Документация](https://docs.n8n.io) | [🌟 Начало работы](#-общее-описание) | [📦 Установка n8n](https://docs.n8n.io/getting-started/installation/)

</div>

---

## 📚 Содержание

<details open>
<summary><h3>📑 Быстрая навигация</h3></summary>

| Раздел | Описание | Статус |
|:-------|:----------|:--------|
| [🌐 Общее описание](#-общее-описание) | Обзор коллекции и её назначение | [![Status](https://img.shields.io/badge/status-ready-success)]() |
| [🔍 Категории воркфлоу](#-категории-воркфлоу) | Классификация рабочих процессов | [![Status](https://img.shields.io/badge/status-updating-blue)]() |
| [⭐ Ключевые воркфлоу](#-ключевые-воркфлоу) | Основные процессы и связи | [![Status](https://img.shields.io/badge/status-stable-success)]() |
| [📋 Шаблоны](#-примечательные-шаблоны) | Выдающиеся примеры | [![Status](https://img.shields.io/badge/status-new-yellow)]() |
| [🔧 Структура](#-техническая-структура) | Архитектура и компоненты | [![Status](https://img.shields.io/badge/status-stable-success)]() |
| [📝 Рекомендации](#-рекомендации-по-использованию) | Практики и советы | [![Status](https://img.shields.io/badge/status-ready-success)]() |
| [🚀 Развитие](#-потенциал-развития) | Планы расширения | [![Status](https://img.shields.io/badge/status-active-blue)]() |

</details>

---

## 🎯 Общее описание

<details open>
<summary><h3>📌 О проекте</h3></summary>

> 💡 **Коллекция автоматизированных рабочих процессов для n8n**

Проект представляет собой курируемый набор шаблонов для различных сценариев автоматизации, включающий:

- 🤖 Интеграции с AI-сервисами
- 📊 Инструменты анализа данных
- 🔄 Автоматизацию бизнес-процессов
- 🌐 Интеграции веб-сервисов

</details>

---

## 🔍 Категории воркфлоу

<details open>
<summary><h3>🤖 AI-ассистенты и чат-боты</h3></summary>

| Тип | Описание | Сложность | Статус |
|:-----|:----------|:------------|:--------|
| Персональные ассистенты | Поддержка голоса и текста | ⭐⭐ | [![Status](https://img.shields.io/badge/status-active-success)]() |
| Бизнес чат-боты | Клиентская поддержка | ⭐⭐⭐ | [![Status](https://img.shields.io/badge/status-stable-success)]() |
| Мессенджер боты | Интеграции с Telegram, WhatsApp, Discord | ⭐⭐⭐⭐ | [![Status](https://img.shields.io/badge/status-beta-yellow)]() |

```mermaid
graph LR
    A[Входящий запрос] --> B{Тип запроса}
    B -->|Текст| C[NLP обработка]
    B -->|Голос| D[Speech-to-Text]
    C --> E[AI анализ]
    D --> E
    E --> F[Формирование ответа]
    F --> G[Отправка пользователю]
```

</details>

<details>
<summary><h3>📊 Обработка данных и аналитика</h3></summary>

| Категория | Инструменты | Интеграции |
|:-----------|:-------------|:-------------|
| 📈 Анализ данных | • Pandas<br>• NumPy<br>• Jupyter | Google Sheets, Excel |
| 📊 Визуализация | • Plotly<br>• Matplotlib<br>• D3.js | Tableau, PowerBI |
| 🤖 ML/AI | • TensorFlow<br>• PyTorch<br>• Scikit-learn | AWS, GCP, Azure |

```mermaid
flowchart TD
    A[Источники данных] --> B[Предобработка]
    B --> C{Тип анализа}
    C -->|Статистика| D[Статистический анализ]
    C -->|ML| E[Машинное обучение]
    C -->|Визуализация| F[Создание отчетов]
    D & E --> F
    F --> G[Экспорт результатов]
```

</details>

<details>
<summary><h3>🔌 Интеграции с AI-сервисами</h3></summary>

| Сервис | Статус | Возможности | Документация |
|:--------|:---------|:-------------|:--------------|
| OpenAI | [![Status](https://img.shields.io/badge/status-active-success)](https://openai.com) | GPT, DALL-E | [Docs](https://platform.openai.com/docs) |
| Google Gemini | [![Status](https://img.shields.io/badge/status-beta-yellow)](https://gemini.google.com) | Мультимодальный AI | [Docs](https://ai.google.dev/docs) |
| Mistral.ai | [![Status](https://img.shields.io/badge/status-new-blue)](https://mistral.ai) | Открытые модели | [Docs](https://docs.mistral.ai) |
| Claude | [![Status](https://img.shields.io/badge/status-active-success)](https://anthropic.com) | Бизнес AI | [Docs](https://anthropic.com/claude) |
| Ollama | [![Status](https://img.shields.io/badge/status-experimental-orange)](https://ollama.ai) | Локальные модели | [Docs](https://ollama.ai/docs) |

</details>

<details>
<summary><h3>🔄 Автоматизация бизнес-процессов</h3></summary>

| Процесс | Компоненты | Интеграции | Статус |
|:---------|:------------|:------------|:--------|
| HR Автоматизация | • Онбординг<br>• Учет времени<br>• Оценка KPI | Slack, Trello, Jira | [![Status](https://img.shields.io/badge/status-stable-success)]() |
| Документооборот | • Генерация документов<br>• Согласование<br>• Архивация | Google Docs, OneDrive | [![Status](https://img.shields.io/badge/status-active-success)]() |
| CRM Процессы | • Лид-менеджмент<br>• Воронка продаж<br>• Аналитика | HubSpot, Salesforce | [![Status](https://img.shields.io/badge/status-beta-yellow)]() |

```mermaid
stateDiagram-v2
    [*] --> Инициация
    Инициация --> Выполнение
    Выполнение --> Проверка
    Проверка --> Завершение
    Проверка --> Корректировка
    Корректировка --> Выполнение
    Завершение --> [*]

    state Выполнение {
        [*] --> Задача1
        Задача1 --> Задача2
        Задача2 --> Задача3
        Задача3 --> [*]
    }
```

</details>

---

## 🌟 Ключевые воркфлоу

<details open>
<summary><h3>📊 Структура процессов</h3></summary>

```mermaid
graph TD
    A[Коллекция n8n] --> B[AI Ассистенты]
    A --> C[Обработка Данных]
    A --> D[Бизнес-процессы]
    A --> E[Интеграции]
    
    B --> B1[Чат-боты]
    B --> B2[Голосовые ассистенты]
    B --> B3[Специализированные агенты]
    
    C --> C1[Анализ текста]
    C --> C2[Обработка изображений]
    C --> C3[Работа с документами]
    
    D --> D1[HR автоматизация]
    D --> D2[Email обработка]
    D --> D3[CRM интеграции]
    
    E --> E1[OpenAI]
    E --> E2[Google Services]
    E --> E3[Базы данных]
```

</details>

---

## 🏆 Примечательные шаблоны

<details open>
<summary><h3>🔍 Топ шаблонов</h3></summary>

### 1️⃣ Интеллектуальный веб-поиск

[![Brave Search](https://img.shields.io/badge/Brave_Search-API-orange)](https://brave.com/search/api/)

- 🔍 Использование Brave Search API
- 📊 Семантическое ранжирование
- 🤖 Интеграция с Google Gemini

### 2️⃣ OpenAI примеры (5-в-1)

[![OpenAI](https://img.shields.io/badge/OpenAI-API-412991)](https://openai.com)

- 💬 Интеграция ChatGPT
- 🎨 Генерация изображений DALL-E
- 🗣️ Распознавание речи Whisper

### 3️⃣ Персональный шоппер для WooCommerce

[![WooCommerce](https://img.shields.io/badge/WooCommerce-Plugin-96588A)](https://woocommerce.com)

- 🔄 RAG (Retrieval Augmented Generation)
- 📁 Интеграция с Google Drive
- 🛍️ Чат-бот для e-commerce

</details>

---

## 🔧 Техническая структура

<details>
<summary><h3>⚙️ Архитектура проекта</h3></summary>

```mermaid
C4Context
    title Архитектура автоматизации
    
    Person(user, "Пользователь", "Инициатор процесса")
    System(n8n, "n8n", "Платформа автоматизации")
    System_Ext(ext_services, "Внешние сервисы", "API интеграции")
    System_Ext(storage, "Хранилище", "Данные и документы")
    
    Rel(user, n8n, "Запускает процессы")
    Rel(n8n, ext_services, "Интегрируется")
    Rel(n8n, storage, "Сохраняет данные")
    Rel(ext_services, storage, "Обменивается данными")
```

<details>
<summary>📄 Структура JSON файлов</summary>

```json
{
  "workflow": {
    "metadata": {
      "name": "Example Workflow",
      "version": "1.0.0"
    },
    "nodes": [],
    "connections": {}
  }
}
```
</details>

</details>

---

## 📋 Рекомендации по использованию

<details open>
<summary><h3>📝 Основные шаги</h3></summary>

1. 📚 Изучить [документацию](https://docs.n8n.io) каждого воркфлоу
2. 🔐 Настроить необходимые учетные данные
3. 🧪 Протестировать в тестовой среде
4. ⚙️ Адаптировать параметры

```mermaid
gantt
    title Процессы автоматизации
    dateFormat  YYYY-MM-DD
    section HR
    Рекрутинг           :a1, 2024-01-01, 30d
    Онбординг           :a2, after a1, 20d
    section Email
    Обработка           :b1, 2024-01-15, 14d
    Категоризация       :b2, after b1, 10d
    section CRM
    Интеграция          :c1, 2024-02-01, 21d
```

</details>

---

## 🚀 Потенциал развития

<details open>
<summary><h3>📈 Планы развития</h3></summary>

- 🔄 Добавление новых интеграций
- 🔧 Расширение функциональности
- 🔗 Создание комбинированных решений
- ⚡ Оптимизация производительности

</details>

---

## 📜 Лицензия

Распространяется под лицензией MIT. См. файл [LICENSE](LICENSE) для получения дополнительной информации.

---

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=n8n-io/n8n&type=Date)](https://star-history.com/#n8n-io/n8n&Date)

**Сделано с ❤️ для сообщества n8n**

</div>

        