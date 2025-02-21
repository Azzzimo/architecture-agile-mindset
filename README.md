# Agile Mindset в проектировании систем. (4 дня)
_Архитектурный agile mindset – это обоснованность инженерных решений плюс инструменты работы с неопределённостью._

# Ожидания от аудитории
- Проектор
- Флипчарт с блоком бумаги, маркёры
- Стикеры
- Малярный скотч

# Программа
## Знакомство (1)
- Контекст: потребность формировать и развивать функцию системной архитектуры и сообщество
- Формат
- Материалы
- Обзор тренинга
- Разбивка на команды
- Знакомство и сбор проблем участников
- Перерывы: 11:30-11:45, 13:00-14:00, 15:30-15:45

## Зачем нужна архитектура – как не угробить компанию? (1)
- Что такое архитектура?
- Где граница дизайна, микро-дизайна и архитектуры?
- Кто является потребителем архитектурных артефактов?
- На какие вопросы должна отвечать выбранная архитектура?
### Архитектурный чек-лист
- Начинаем описание DoD

## Архитектурные точки зрения и документирование архитектуры – как тратить ресурсы сфокусированно и рано адресовать риски? (1)
- Какую картинку видите при слове «архитектура»?
- Что важнее – схема БД или concurrency design?
- Какие еще PoV можете выделить?
- В каком виде можно документировать архитектурные решения? Какие артефакты можно выдавать?
- Типовые PoV
- Как увидеть характеристики за диаграммами в PoV
### Архитектурный чек-лист
- Продолжаем описание DoD

## Архитектура как требования к компонентам – как обеспечить гибкость и снизить стоимость поддержки? (1)
- Принятые термины: модуль=функция, компонент=конструкция
- На какие предположения мы опираемся при проектировании с использованием готовых компонентов или внешних систем?
- Как можно сформулировать наши ожидания от внешних компонентов?
- Как адресовать риски несоответствия нашим ожиданиям?
- Инкрементальная архитектура
### Архитектурный чек-лист
- Продолжаем описание DoD

## Архитектура как план адресации проектных рисков – как повысить эффективность производства? (1)
- Какие требования предъявляет к архитектуре PM/РП?
- Можно по архитектуре создать план проекта?
- Параллельность работ и критический путь
### Архитектурный чек-лист
- Продолжаем описание DoD

## Системная инженерия: как принимать обоснованные и прозрачные для бизнеса инженерные решения? (1)
- От чего зависят решения в дизайне и архитектуре? Где найти ответы, чтобы обосновать их?
- А дальше?
- 5 «почему?»
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

---

## Ретроспектива по прошедшему дню (0.5)
- Что было ценного?
- Что следует улучшить?
- Что возьмете в производство?

## Архитектура как функция от требований – как делать что нужно, снизить rework и повысить удовлетворенность клиентов? (1)
- Какие виды требований можно выделить?
- Как можно определить «критические пути» в требованиях?
- Как требования определяют границы системы?
  - Бизнес-модель
  - Культура компании
  - Принципы и Методология
  - Внешние NFR:
    - Latency
    - Availability
    - Деградация
  - Внутренние NFR:
    - Simple Design - Делать просто. Лучше потом быстро переделать чем заранее пытаться сделать слишком гибко
    - Simple Design <-> Big Design Upfront (BDUF)
    - Readability
    - Maintainability
    - Testability
  - Функциональные Требования
  - Внутренние Функциональные Требования:
    - админка
    - мониторинг
    - логгинг
  - Дизайн
  - Продукт
- Какие знаете типовые переходы «профиль требований → типовая архитектура»?
- Отдельно про масштабируемость
- Типовые профили: «High-Load», учетные и интеграционные системы. Характерные риски.
- Отдельно про внутренние требования. Фитнес-функция.
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

## «Trade-off» и «Специализация» – как принимать решения в случае конструктивного конфликта требований? (1)
- В каком соответствии находятся требования?
- Как инженерными решениями адресовать эти связи между требованиями?
- Как относиться к шаблонам проектирования – их ценность и проблемы
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

## Системная инженерия: как проектировать в условиях внешней неопределенности (требований)? (1)
- Что вы делаете, если не знаете _что_ делать: требований сейчас и будущих изменений?
- Как меняется внутренняя модель качества?
- Процесс: BDUF vs YAGNI/KISS/Emergent design
- Инкапсуляция изменчивости
- Lean SWD: делегируй и откладывай
- Все уже придумано до нас: Cynefin Framework
- Поставки инкрементально vs итеративно
- Шаблоны декомпозиции требований: по сценариям и по шагам
- Процесс: Формальные vs самоорганизованные компании
- Процесс: Кросс-фунциональность и T-shaping
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

## Системная инженерия: как проектировать в условиях внутренней неопределенности? (1)
- Что вы делаете, если не знаете, _как_ делать?
- Ключевые ожидания к компонентам, исходя из требований
## Работа с инженерными гипотезами
- Ранние проверки ключевых контрактов
- Внешняя и внутренняя экспертиза
- Тесты как ранняя проверка контракта
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

## Системная инженерия: архитектура как функция от технологического процесса производства (1)
- Влияют ли принятые процессные и иженерные практики на архитектуру системы?
- Типовой DevOps Pipeline
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

## Системная инженерия: архитектура как функция от структуры компании – закон Конвея (1)
- Как структура информационных потоков определяет ключевые решения
- Шаблоны коллективного владения системой по Эвансу
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

## Системная инженерия: архитектура как функция от культуры компании (1)
### Культура
- Как мы ведем себя, когда никто не видит, “дефолтное” поведение?
- Прокликаете ли фичу, даже если нет четкого указания?
- Культуры по Шнайдеру
- Самовоспроизводство культуры
- Управление культурой
### Культурный аспект: совместная деятельность - коммуникации и ответственности
- Роли (деятельности) четко сфокусированы на участниках?
- Или роли (деятельности) "размазаны" по участникам?
- Раздеялем роль/деятельность/функцию и должность и участника команды
- В гибких компаниях какой подход более производителен?
### Архитектурный чек-лист
- A = F(?)
- Продолжаем описание DoD

---

## Ретроспектива по прошедшему дню (0.5)
- Что было ценного?
- Что следует улучшить?
- Что возьмете в производство?

## Системная инженерия: архитектура как функция от бизнес-модели (1)
- Как бизнес может зарабатывать на IT?
- Зачем система нужна бизнесу?
- В какие артефакты превращаются ожидания бизнеса?
### Шаблоны бизнес-моделей: 
- Заказ vs Продукт
- Outsource vs In-house
- Проекты vs Сервис
- B2C vs B2B vs B2G
- Стартап vs Зрелая
- Зарабатывать самим vs Развитие под поглощение
### Архитектурный чек-лист
- A = F(?)
- Какие метрики процесса ожидают бизнесы?
- Продолжаем описание DoD

## Гибкость в принятии архитектурных решений – что еще мы не учитываем, убивая проекты и продукты? (1)
- Архитектура как функция от доверия менеджмента команде
- Архитектура как функция от доверия команды менеджменту
- Архитектура как функция от структуры компании
- Архитектура как функция от партнеров
- Архитектура как функция от корпоративной политики
### Архитектура как функция от унаследованных систем: Solution Architecture
- Reuse
- Специализация vs обобщение
- Роль документации и тестов

## Характер agile design и ожидания от производственной системы (1)
### Характер современной продуктовой разработки: recap
- Неопределённость
- Инновационность
- Тиражируемость
- Воспроизводимость конкурентами
- Снижение лояльности клиентов
### Ожидания бизнеса от производства: recap
- Скорость
- Гибкость
- Качество
- "Марафон", сервис
### Agile Design: recap
- Четко обоснованный – сфокусированный на бизнес-результате
- Результат открытого честного общения
- Архитектурная деятельность размыта по команде
- Time-boxed
- Инкрементальный
- Известные риски адресованы рано, реализация отложенная
- Не делаем «в пустоту»
- Четкое понимание, кому и зачем передается работа дальше
- Характерная для сервисных отношений модель внутреннего качества
### Манифестируем себя как продуктовые agile команды
- Какую производственную структуру выберете?
- Какую культуру манифестируете бизнесу?
- Какие метрики своего процесса манифестируете бизнесу?

## Продуктовая бизнес-модель (1)
- Практика Lean Canvas как продуктовая гипотеза
- Практика Vision и шаблон
### Фиксируем продуктовую гипотезу
### Фиксируем Vision

## Scope продукта (1)
- Практика Story Mapping
- Формат User Story: name, story, acceptance criteria, NFRs
### Фиксируем беклог

---

## Ретроспектива по прошедшему дню (0.5)
- Что было ценного?
- Что следует улучшить?
- Что возьмете в производство?

## Системный дизайн: итерация 01 (1.5)
- Выбор POVs
- Проектирование
- Архитектурное кросс-ревью

## Системный дизайн: итерация 02 (1.5)
- Backlog refinement 
- Выбор POVs
- Проектирование
- Архитектурное кросс-ревью

## Системный дизайн: итерация 03 (1.5)
- Backlog refinement 
- Выбор POVs
- Проектирование
- Архитектурное кросс-ревью


## Прочее
- Dual Track Agile - проверять гипотизу на "одноразовых" продуктах
- Multi Modal Agile - когда одноразовые продукты живут параллельно рядом с основной системой
