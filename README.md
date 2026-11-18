# Максим Лопатин

**Руководитель направления разработки / Team Lead (Python).** Воронеж · удалённо, гибрид.

Строю системы, которые работают на реальном производстве: цифровая маркировка «Честный Знак» и GS1 DataMatrix — от ПЛК на линии до backend, приложений на ТСД и обмена с 1С.

> 8 лет в IT · 5 лет коммерческой разработки на Python · команда 5 человек · маркировка на всех заводах холдинга · −96% расходов на техподдержку

### Чем занимаюсь

- **Руковожу направлением цифровой идентификации** в «Молвесте» с октября 2025: команда 5 человек — 4 инженера (Backend, Mobile, Embedded) и я. Приоритеты, найм, процессы, административная часть.
- **Отвечаю за продукт целиком:** от заказа кодов и входного контроля DataMatrix GS1 от типографий до печати, прослеживаемости партий и обмена с 1С:ERP.
- **Держу экономику:** перевёл поддержку с интеграторов на собственную систему — расходы на техподдержку снизились на 96%.
- **Выстроил процессы:** код-ревью, CI/CD, unit- и интеграционное тестирование, планёрки и ретроспективы; менторю инженеров.
- **Продолжаю писать код:** Python (Django, DRF, FastAPI), PostgreSQL, Docker, Kotlin/Android, OpenCV. Интеграции с ПЛК Delta (LD), ТСД и промышленными принтерами (Zebra/TSC, ZPL).
- **Использую агентное программирование:** OpenCode + LLM, правила под проект, разработка блоками и коммиты по задачам — до 4 проектов параллельно.

### Проекты

**Рабочий контур**

- **[PartyManagementSystem](https://github.com/lopatin2012/PartyManagementSystem)** — ядро экосистемы: управление жизненным циклом партий, генерация УИП, интеграция с True API / СУЗ «Честного Знака». Django, DRF, PostgreSQL.
- **[PrintingMachine](https://github.com/lopatin2012/PrintingMachine)** — управление промышленной печатью: Zebra/TSC и ZPL, асинхронная очередь, контроль статусов принтеров, иерархия «цех → линия → принтер». FastAPI.
- **[VerificatorDataMatrix](https://github.com/lopatin2012/VerificatorDataMatrix)** — верификатор качества печати по ISO/IEC 15415: грейдинг, heatmap дефектов, PDF-отчёты, web-интерфейс, fallback-локатор на нейросети.
- **[signature_service](https://github.com/lopatin2012/signature_service)** — отказоустойчивый микросервис электронной подписи CAdES-BES на FastAPI: Windows (CAdESCOM) и Linux (КриптоПро CSP).
- **[free_digital_marking](https://github.com/lopatin2012/free_digital_marking)** — открытая реализация работы с True API и СУЗ: жизненный цикл кодов, привязка к партиям, отчёты о нанесении.
- **[CowMarks](https://github.com/lopatin2012/CowMarks)** — Android-приложение для ТСД: сбор и печать кодов, обмен с терминалом.

**Инструменты и эксперименты**

- **[production-line-sim](https://github.com/lopatin2012/production-line-sim)** — симулятор производственного участка на чистом Python: виртуальная линия, принтеры Zebra/TSC (ZPL), HMI, шина событий. Позволяет тестировать интеграции без железа.
- **[digital_help](https://github.com/lopatin2012/digital_help)** — помощник для Android-терминалов в работе с интегратором ОКТО.
- **[ScannerData](https://github.com/lopatin2012/ScannerData)** — чтение данных с COM-порта: контроль кодов (годен или дубль).
- **[TabletopScanner](https://github.com/lopatin2012/TabletopScanner)** — приложение для настройки настольных сканеров.
- **[code_okto_v2](https://github.com/lopatin2012/code_okto_v2)** — автоматизация заказа кодов на сайте интегратора ОКТО (Selenium).
- **[gameDM](https://github.com/lopatin2012/gameDM)** — кликер про внедрение обязательной маркировки DataMatrix — на vanilla JS, без сборки.

### Стек

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-34A853?logo=android&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![GS1 DataMatrix](https://img.shields.io/badge/GS1_DataMatrix-0068A5)
![True API](https://img.shields.io/badge/True_API-00A651)
![ZPL](https://img.shields.io/badge/ZPL-000000)
![PLC Delta](https://img.shields.io/badge/PLC_Delta-607D8B)
![ТСД](https://img.shields.io/badge/%D0%A2%D0%A1%D0%94-455A64)

### Связаться

- Telegram: [@HaHo4eJIoBeK](https://t.me/HaHo4eJIoBeK)
- Резюме на hh.ru: [voronezh.hh.ru/resume/331f7862…](https://voronezh.hh.ru/resume/331f7862ff11021d980039ed1f456e71565355)
- Email: [lopatin.maxim2012@gmail.com](mailto:lopatin.maxim2012@gmail.com)
