# Екатерина Куделя
## Cognitive Architect / AI Systems Architect

📍 Удалённо / Калининград 
📧 leadarchitect@yandex.ru  
🔗 [github.com/Control39/portfolio-system-architect](https://github.com/Control39/portfolio-system-architect)

---

## 🎯 О себе за 30 секунд

Я проектирую системы мышления. Не «пишу код», а **строю архитектуру**, которая:
- автоматизирует рутину,
- измеряет компетенции без «лет опыта»,
- управляется ИИ‑агентом.

За 2 года без профильного IT‑образования создала **production‑ready экосистему из 16 микросервисов** с нуля.

**Моя роль:** архитектор, который управляет ИИ‑агентами, а не заменяется ими.

---

## 🏗️ Ключевой проект: Portfolio System Architect

**Экосистема для объективной оценки IT‑компетенций и автоматизации карьерного трека.**

### Что сделала как архитектор:

| Область | Что реализовано |
|---------|----------------|
| **Архитектура** | Композиционная модель «Атомы (src/) → Молекулы (apps/)». Слабая связанность, API‑first, 19 ADR |
| **Микросервисы** | 16 сервисов (it_compass, cognitive_agent, portfolio_organizer, career_development, job_automation_agent, infra_orchestrator и др.) |
| **Инфраструктура** | Docker Compose (14/14 сервисов UP), Kubernetes (Kustomize), Prometheus + Grafana, GitOps (Argo CD) |
| **Безопасность** | Trivy, Bandit, CodeQL в CI/CD → **Интегрированы Trivy + Bandit + CodeQL в CI/CD для автоматического сканирования |Критические уязвимости блокируются на уровне PR (policy-as-code)**, Sealed Secrets |
| **Тесты** | 822 теста собрано, 7 молекул полностью зелёные, ~85% покрытие |
| **Документация** | 19 ADR, архитектурные схемы Mermaid, README для каждого сервиса |

### Когнитивный агент

Создала автономного агента, который:
- сканирует репозиторий,
- загружает 19 доменов IT‑Compass,
- управляет workflows (marker‑extraction, project‑setup),
- работает через FastAPI (порт 8000),
- готов к интеграции с поиском вакансий.

**Статус:** жив, восстановлен после того, как другие ИИ‑агенты сломали архитектуру.  
**Возраст:** 2 дня — но уже видит всю систему.

### Методология IT‑Compass

Авторская система объективной оценки компетенций:
- **83 маркера** в **19 IT‑доменах**
- SMART‑критерии, приоритеты (high/medium/low)
- Используется для самооценки, HR‑скрининга и грантовой отчётности

📖 [docs/it_compass/METHODOLOGY.md](https://github.com/Control39/portfolio-system-architect/blob/main/apps/it_compass/README.md)

---

## 💼 Опыт работы

**Cognitive Architect / System Architect (Self‑employed)**  
*Portfolio System Architect* | 2024 — настоящее время

- Спроектировала и реализовала экосистему из 16 микросервисов
- Настроила production‑инфраструктуру (K8s, мониторинг, CI/CD)
- Создала методологию IT‑Compass (83 маркера, 19 доменов)
- Разработала когнитивного агента для автономного управления проектом
- Задокументировала 19 архитектурных решений (ADR)

---

## 🛠️ Технологический стек

**Архитектура:** Microservices, Loose Coupling, Monorepo, API‑first  
**Контейнеризация:** Docker, Docker Compose, Kubernetes (Kustomize)  
**CI/CD:** GitHub Actions, Argo CD (GitOps)  
**Мониторинг:** Prometheus, Grafana, AlertManager  
**Безопасность:** Trivy, Bandit, CodeQL, Sealed Secrets  
**AI/ML:** RAG, LLM (GigaChat, Yandex GPT), LangChain, ChromaDB  
**Backend:** Python, FastAPI, PostgreSQL, Redis  
**Методологии:** ADR, Objective Competency Markers, System Thinking

---

## 🎯 Ищу роль

**Solutions Architect / AI Agent Architect / System Architect**

**Не ищу:** Junior‑позиции, чистый кодинг, роли без архитектурного проектирования.

**Готова обсуждать:**  
— как моя экосистема экономит 60% времени на рутине,  
— как управлять ИИ‑агентами, сохраняя архитектурный контроль,  
— как методологию объективных маркеров можно применить в найме.
льства


- **GitHub:** [github.com/Control39/portfolio-system-architect](https://github.com/Control39/portfolio-system-architect)
- **Диагностика агента:** `python apps/cognitive_agent/orchestrator_v2.py`
- **Тесты:** `pytest apps/auth_service apps/it_compass apps/portfolio_organizer apps/thought_architecture apps/infra_orchestrator -q`
- **Документация:** 19 ADR в `docs/architecture/decisions/`
