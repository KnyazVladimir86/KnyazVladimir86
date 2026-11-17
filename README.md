# Привет! Я Владимир Байрамов (KnyazVladimir86)

**AI Systems Architect** | Локальная разработка LLM-систем, автономные агенты, предиктивная аналитика.

Я проектирую и разрабатываю автономные ИИ-системы, которые работают локально (без отправки данных во внешние API), с фокусом на безопасность, воспроизводимость и интеграцию в продакшн-инфраструктуру.

## Мои флагманские проекты (демо-срезы)

Все проекты — приватные, но содержат полные демо-срезы (Docker, README, инструкции). По запросу предоставлю доступ или покажу логи/метрики.

| Проект | Назначение | Ключевые технологии | Статус |
|--------|------------|---------------------|--------|
| **[CURSUS_PERPETUUS](https://github.com/KnyazVladimir86/CURSUS_PERPETUUS)** | Автономная мультиагентная система разработки ПО. Оркестратор на чистом `asyncio`, изоляция агентов в Docker. | Python, asyncio, Docker, AST-валидация | MVP |
| **[VIVA_INTEGRA](https://github.com/KnyazVladimir86/VIVA_INTEGRA)** | Платформа анализа медицинских документов. OCR + ансамбль агентов, Human-in-the-loop, шифрование. **PII полностью удалён.** | FastAPI, Qwen2.5-VL, Fernet, Docker | MVP |
| **[MERCATOR_REALIS](https://github.com/KnyazVladimir86/MERCATOR)** | Торговая платформа для MOEX. ML-ансамбль, контроль рисков, исполнение сделок. | LightGBM, T-Invest API, WebSocket, ISS Poller | MVP |
| **[VOX_DOCTRINA](https://github.com/KnyazVladimir86/VOX_DOCTRINA)** | Система транскрибации и семантического анализа врачебных консультаций. | Whisper, LangChain, FastAPI, conftest.py | MVP |
| **[PROMETHEUS_Logistics](https://github.com/KnyazVladimir86/PROMETHEUS)** | Мониторинг дрейфа данных и качества ML-моделей в реальном времени. | DriftDetector, null-bytes sanitizer, CI/CD | MVP |

> **Остальные проекты (ANIMA, MEMORIA, SONOMATIX, STRATA_MATRIX)** — специализированные платформы под узкие задачи. Полный список и доступ — по запросу.

## Технологический стек

- **Backend & API:** FastAPI, Starlette, REST, HTTP/2, WebSocket.
- **LLM & Agents:** Local LLMs (Ollama, llama.cpp), LangChain, Qwen, Llama3.
- **ML & Data:** Pandas, NumPy, Scikit-learn, LightGBM, XGBoost.
- **Containerization:** Docker, Docker Compose, изоляция сетей.
- **Data Engineering:** SQL (PostgreSQL), ETL, парсинг, валидация данных.

## Как запустить демо-срез любого проекта

1. Склонируйте нужный репозиторий.
2. Убедитесь, что у вас установлен Docker.
3. Выполните в корне проекта:
   ```bash
   docker-compose up --build

    ```
4.  Интерфейс доступен по адресу `http://localhost:80XX` (указан в README проекта).

---

**Контакты:**
- Email: valdemarb1986@gmail.com
- Город: Сочи, Россия (GMT+3)
