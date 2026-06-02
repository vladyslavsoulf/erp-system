# ERP System — Enterprise Resource Planning

Реализация системы класса Enterprise Resource Planning (ERP) для управления
командами, задачами, кадровыми и финансовыми ресурсами компании среднего размера.

## Технологии

- **Frontend:** React
- **Backend:** Spring Boot (Java)
- **База данных:** PostgreSQL
- **CI/CD:** GitHub Actions
- **Управление задачами:** Trello

## Модули системы

- **HR-модуль** — сотрудники, договоры, отпуска, оценка эффективности
- **Модуль проектов** — задачи, распределение ресурсов
- **Финансовый модуль** — бюджеты, расходы, бухгалтерские отчёты
- **KPI-панель** — исполнительная панель в реальном времени

## Системные требования

- Java 17+
- Node.js 18+
- PostgreSQL 15+

## Запуск проекта

### Backend
```bash
cd backend
./mvnw spring-boot:run
```

### Frontend
```bash
cd frontend
npm install
npm start
```

## Структура веток

- `main` — стабильная версия
- `develop` — основная разработка
- `feature/hr-module` — HR-модуль
- `feature/finance-module` — финансовый модуль
- `feature/projects-module` — модуль проектов

## Автор

Vladyslav Clitman — [vladyslavsoulf](https://github.com/vladyslavsoulf)
