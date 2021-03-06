# Методология разработки
За основу взята методология Scrum и фреймворк масштабирования LESS
## Принципы
- Команда как часть продукта, процессы в команде аналогичны процессам в продукте
- Продукт существует в условиях возникновения сигналов на изменение продукта
- Для предсказуемости работы с сигналом, она разбивается на унифицированные этапы с определением критериев готовности на каждом этапе
- Работа команды представляется как обогащение контекста сигнала до достижения критерия готовности на каждом этапе
- Обработка сигнала должна происходить и завершаться максимально быстро с учетом приоритета сигналов
- Мониторинг продукта должен позволять отследить каждое изменение продукта
- Мониторинг обработки сигнала должен показывать этап и состояние на этапе для каждого сигнала, и отражать статистику обработки
- По результатам мониторинга обработки сигнала вносятся изменения в процессы и критерии обработки
## Цели
### Управление знаниями о продукте
- Шаринг знаний
- Повышение BUS фактора
- Развитие личных компетенций
- Снижение начальных требований к личным компетенциям
- Повышение информированности команды о продукте 
- Облегчение и ускорение процедуры онбординга
### Повышение степени готовности продукта и команды к изменению бизнеса
- Предсказуемая трудоемкость изменений
- Непрерывный процесс внутреннего улучшения и снижения энтропии
  * При реализации большинства изменений мера энтропии системы возрастает, необходим непрерывный фоновый процесс уменьшающий меру энтропии и когнитивную сложность ([Wiki](https://ru.wikipedia.org/wiki/%D0%AD%D0%BD%D1%82%D1%80%D0%BE%D0%BF%D0%B8%D1%8F#%D0%92_%D1%82%D0%B5%D0%BE%D1%80%D0%B8%D0%B8_%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8))
- Непрерывный процесс автоматизации рутинных операций
- Минимизация Time-To-Market
- Повышение привлекательности HR-бренда
- Облегчение маневра компетенциями
## Терминология
- Продукт
- Сигнал на изменение продукта
- Приоритет сигнала
- Мониторинг продукта
- Мониторинг обработки сигнала 
- Контекст сигнала
- Источник сигнала
- Этапы обработки сигнала
- Критерий готовности
- DoD - критерий окончания обработки сигнала (IMHO нужен на каждом шаге)
- DoR - критерий готовности контекста к обработки (IMHO нужен на каждом шаге) 
- Бэклог продукта
- Бэклог спринта
- Инкремент
- PBI
- Оценка PBI
- Возникающая работа
- Value
    * Прямая коммерческая выручка
    * Сокращение затрат
    * Уменьшение негативных клиентских эффектов 
## Источник сигнала
- Запрос PO Team на изменение продукта
    * Субъект: PO Team
    * Контекст сигнала: описан в DoR
- Аварийный инцидент
    * Получение сигнала об инциденте из технического мониторинга или линии поддержки
    * Установка приоритета и эскалация в соответствии с матрицей эскалации и здравым смыслом
    * Действия по прекращению инцидента
    * Планирование или проведение экспертного совета по предотвращению повторения инцидента
    * Контекст сигнала: постмортем тикет c принятыми мерами и таймингом, количеством пострадавших и потерь value, прикрепленными мерами порожденными экспертным советом
- Локальное клиентское обращение (DRTV)
    * Контекст сигнала: тикет DRTV с максимально подробным описанием проблемы
- Фоновый процесс улучшения
    * Субъект: Сообщества
    * Контекст сигнала: описан в DoR
- Мониторинг продукта
    * Субъект: PO Team
    * Контекст сигнала: описан в DoR
## Этапы обработки сигнала
## Мероприятия
- #### Overall PBR (IMHO Must die)
    * Цель
    * Участники
    * Артефакты на входе на каждого участника
    * Артефакты на выходе
    * Инструментарий
    * Синхронность online/асинхронность
- Single Team PBR
- Multiteam PBR 
- Sprint Planning
- Sprint Review
- Daily
- Overall Retro
- Team Retro
- Встреча сообщества
## Субъекты и роли
### Субъекты-команды
- PO Team
- LESS команды a,b,c
    * Кросс-функциональная команда, обладает всеми необходимыми персональными компонентными ролями для рeализации всех технических этапов, возможно с привлечением некоторых персон с недостающими компетенциями
    * Работает над этапами сообща с передачей ролевых компетенций
- Дежурная LESS команда
- Компонентная команда DevOps
- Команды сторонних проектов
    * Система рекомендаций
    * B2B
    * Voice
- Команды внешних проектов
    * Контент-партнеры
    * Партнеры-сервисы
- Компонентные сообщества
- Сообщество архитектуры
### Субъекты-персоны
- Путешественники
- Скрам-мастера
### Компонентные роли
- Server-Side Developer
- Client-Side Developer
- Designer
- QA
- Ментор компоненты
- TeamLead
- TechLead
- Скрам-мастер
### Развитие персональных компонентных ролей
- workshop
- Читательский клуб
## Инструментарий
### Miro 
- удобно
- легко потерять доски
- фиксируется только малая доля контекста
### Zoom 
- не очень удобно
- пока ничего лучше нет
### Jira 
### Confluence
### GitLab
