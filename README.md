![year][0] ![status][1] ![progress][2]

## Summary

**Технологии программирования**

**МФТИ, ФПМИ, 2022 год**

# Аннотация

*Курс про все, что связано с созданием ПО, кроме непосредственно написания программного кода*

Курс состоит из лекций и семинарских занятий.

Лекционный материал включает краткий обзор важных с точки зрения процесса разработки понятий: методы отладки и этапы исправления дефектов ПО, критерии хорошей и неудачной архитектуры, этапы проектирования и разработки, методологии разработки.

Цель курса — дать слушателям, которые параллельно изучают языки программирования, алгоритмы и т. п., информацию и дополнительные знания, какими инструментами можно пользоваться и на что обращать внимание при создании рыночного программного продукта.

# План лекций

## :white_check_mark: [Лекция №0](https://github.com/demist/techprog_mipt_2022/blob/main/slides/ТП%20МФТИ%202022%2C%20лекция%201.pdf)

[*запись лекции*](https://youtu.be/9WmPY_FDGsI)

- План курса
- Правила оценки
- Информация о заданиях
- Контрольные мероприятия

## :white_check_mark: [Лекция №1](https://github.com/demist/techprog_mipt_2022/blob/main/slides/ТП%20МФТИ%202022%2C%20лекция%201.pdf)

[*запись лекции*](https://youtu.be/9WmPY_FDGsI)

### Принципы проектирования ПО, часть 1

- Что такое архитектура ПО
- Что такое "Проектирование ПО"?
- По каким критериям можно оценить архитектуру? 
	- Критерии хорошей архитектуры
		- Эффективность
		- Гибкость
		- Расширяемость
		- Масштабируемость, тестируемость, возможность повторного использования, сопровождаемость
	- Критерии неудачной архитектуры
		- Жесткость
		- Хрупкость
		- Неподвижность
- Принцип *High Cohesion / Low Coupling*

## :white_check_mark: [Лекция №2](https://github.com/demist/techprog_mipt_2022/blob/main/slides/ТП%20МФТИ%202022%2C%20лекция%202.pdf)

[*запись лекции*](https://youtu.be/DIjRE-WxVrQ)

### Принципы проектирования ПО, часть 2

- Принципы SOLID
	- **S**ingle responsibility principle
	- **O**pen-closed principle
	- **L**iskov substitutional principle
	- **I**nterface segregation principle
	- **D**ependency inversion principle
- Закон Деметры
- *YAGNI*
- *DRY / DIE*
- *KISS*

> [Лекция Роберта *Uncle Bob* Мартина  про SOLID](https://www.youtube.com/watch?v=zHiWqnTWsn4)

## :white_check_mark: [Лекция №3](https://github.com/demist/techprog_mipt_2022/blob/main/slides/ТП%20МФТИ%202022%2C%20лекция%203.pdf)

[*запись лекции*](https://youtu.be/H36N153odgY)

### Основные диаграммы UML

- Что такое UML? 
	- Базовое понятие о нотации UML
- Диаграмма вариантов использования
	- Понятие о вариантах использования
	- Понятие об акторах
	- Нотация диаграммы вариантов использования
- Диаграмма классов
	- Понятие о классах
	- Нотация диаграммы классов
	- Выделение сущностей
		- Карточки CRC
		- Метод Аббота
- Диаграмма последовательности
	- Нотация диаграммы последовательности
- Диаграмма состояний
	- Нотация диаграммы состояний
- Диаграмма деятельности
	- Нотация диаграммы деятельности

> [UML Cheat Sheet](https://www.guru99.com/uml-cheatsheet-reference-guide.html)

## :white_check_mark: [Лекция №4](https://github.com/demist/techprog_mipt_2022/blob/main/slides/ТП%20МФТИ%202022%2C%20лекция%204.pdf)

[*запись лекции*](https://youtu.be/7ItLSXeeTkE)

### Этапы развития проекта

- Основные этапы жизненного цикла проектирования, реализации и внедрения ПО
- Формирование требований
- Разработка концепции
- Техническое задание
- Эскизный проект
    - Понятие о MVP и примеры MVP
- Технический проект
- Рабочая документация
- Поставка / ввод в действие
- Сопровождение 
- Вывод из эксплуатации

## :white_check_mark: [Лекция №5](https://github.com/demist/techprog_mipt_2022/blob/main/slides/ТП%20МФТИ%202022%2C%20лекция%205.pdf)

[*запись лекции*](https://t.me/c/1587908103/33)

### Методологии разработки ПО

- Основные понятия
- Факторы, оказывающие влияние на процесс разработки
	- Внешние факторы
	- Внутренние факторы
- Каскадная модель
- V-модель
- Инкрементная модель
- Итерационная модель
- Спиральная модель
- RAD-модель 
- Семейство гибких методологий
	- Agile-манифест
	- Scrum
	- Kanban

> [Статья про методологии разработки](https://acodez.in/12-best-software-development-methodologies-pros-cons/)

## :white_check_mark: [Лекция №6](https://github.com/demist/techprog_mipt_2022/blob/main/slides/ТП%20МФТИ%202022%2C%20лекция%206.pdf)

[*запись лекции*](https://t.me/c/1587908103/48)

### Отладка ПО, ч.1: работа с ошибками ПО

- Основные этапы отладки ПО
- Воспроизведение дефекта
	- Необходимая информация для воспроизведения
- Анализ дефекта
	- Понятие root-cause
	- Условия возникновения
	- Область повреждения
	- Необходимые выводы
- Дизайн исправления 
	- Технический
	- Архитектурный
	- Технологический
- Исправление дефекта
- Валидация исправления
- Интеграция исправления в код или целевую систему
- Дополнительные валидации после интеграции

## :fire: Лекция 24.03

### Промежуточная контрольная работа + долги по Agile

- Сначала пишем контрольную, на нее у вас будет **45 минут**
- Далее обсуждаем долги с прошлых лекций:
	- Семейство гибких методологий
		- Agile-манифест
		- Scrum
		- Kanban

### Подробности про контрольную

#### Кто когда пишет? 
- Группы, у которых в расписании есть лекция по ТП и нет пересечений с другими предметами - пишут контрольную **24.03 в 17:05**
	- Кто пропустил - идете в деканат, деканат говорит уважительная у вас причина или нет
		- Если уважительная - напишете контрольную в специальный день в конце семестра; никаких санкций за это вам не грозит
			- Если болеете - лучше не писать КР 24.03, т.к. аргументация "я плохо написал, т.к. болел" - приниматься не будет. Лечитесь, напишете потом 
		- Если неуважительная - это ваш выбор; написать эту контрольную вы уже не сможете
		- Команда преподавателей курса не разбирается, у кого какая причина - такие сообщения будем просто игнорировать и по умолчанию считать, что причина неуважительная (до получения соответствующей информации от деканата)
		- Решить вопросы с деканатом (про уважительную причину) нужно до **30 апреля включительно**, т.к. 1 мая мы сядем формировать списки тех, кто должен написать промежуточную КР в дополнительный день
	- Особо смышленные - кто решит написать с другими группами не в свой день - мы же знаем вашу группу, так что вы просто получите за контрольную "0", проверять мы вашу работу не будем, а за обман команды преподавателей - обнулим баллы за семестр и пойдете на устный зачет; *армии такие находчивые нужны*
- Группы, у которых в расписании лекции по ТП нет / есть пересечения с другими предметами - пишут контрольную **28.03 в 13:00**
	- Про уважительные / неуважительные причины - то же самое, что и написано выше, с тем лишь исключением, что у вас уважительная причина должна быть 28.03
	- Кто хочет написать 24.03 вместе со всеми - можете писать 24.03
- **Важная ремарка**: варианты КР 24.03 и 28.03 будут разными, но сложность мы постараемся сделать одинаковой. Тем не менее, всегда найдутся люди, которые считают, что один из вариантов был легче. Никаких "нормировок" на тот вариант, который *будет считаться студентами легче* и т.п. не будет - предупреждаем заранее, так что не тратьте свое и наше время на подобные вопросы. Да, 100% одинаковыми по сложности варианты не получатся, т.к. это физически невозможно, так что кому-то *повезет*, но это не будет иметь определяющего значения (т.к. варианты +- все равно будут одинаковы)

#### Правила игры
- На контрольную отводится **45 минут**
- Контрольная пройдет на базе Google Forms
	- Если у вас пропал интернет в процессе решения контрольной - **не перезагружайте страницу**, просто ждите, когда интернет появится; если страницу перезагрузите - ответы могут пропасть
	- Лучше перед заполнением формы зайти в свой google-аккаунт (например, в аккаунт МФТИ, он есть у всех) - тогда ответы будут кэшироваться локально (проверялось на практике, но лучше в целом не рисковать и не перезагружать страницу)
	- О технических проблемах сообщать **строго до конца контрольной**. После того, как время контрольной вышло - никакие жалобы на технические проблемы не принимаются
	- О технических проблемах пишем в общий чат курса в telegram. Туда и только туда, т.к. по опыту все задают одни и те же вопросы. 
		- Перед отправкой вопроса просьба просмотреть предыдущие сообщения - вдруг на ваш вопрос уже ответили
	- Содержательные вопросы по материалам КР задаем **строго в личных сообщениях в telegram лектору @demist**, за вопросы в общем чате - 0 баллов за КР автоматом (причина: часто такие вопросы являются подсказкой для других студентов)
		- Перед отправкой вопроса еще раз перечитайте внимательно вопрос КР - может быть, вы неправильно его поняли
		- Студентов много, так что и вопросов может быть потенциально много. Отвечать будем всем, но, очевидно, что всем моментально ответить не получится (*лектор существует в единственном экземпляре*). **Не пингуйте** в стиле "?", "ответьте пожалуйста" и т.п. Ответим мы всем, но в порядке очереди (*в каком порядке вопросы поступали*). За пинг - **0 баллов за КР**
		- Пока на ваш вопрос не ответили - не теряйте время, отвечайте на другие вопросы
	- **Обратите внимание**: после ответа на все вопросы нужно нажать кнопку *ОТПРАВИТЬ*. Если вы эту кнопку не нажали - ответов мы не получили, а значит, вы получите за КР 0 баллов
		- Апелляции после контрольной в стиле "я забыл нажать кнопку отправить" - приниматься не будут
		- После отправки ответов google-формы показывают сообщение в стиле "ваш ответ отправлен"
		- Если вы указали свою почту - туда должна будет прийти копия ваших ответов
			- **ВНИМАНИЕ** копия ответов не всегда приходит моментально, иногда попадает в *Спам*, иногда вообще не приходит - таковы уж google-формы. Не нужно дергать команду преподавателей - мы тут вам ничем помочь не сможем. Хотите пожаловаться - жалуйтесь в службу поддержки Google
			- **ВАЖНО** Ситуаций, что google-формы сказали "Ответ записан" (неважно пришло письмо или нет) и ответ мы не получаем - за 2+ года ни разу не замечено. Так что сообщение "Ответ записан" первично, письмо с копией - вторично
		- **ВАЖНО** Иногда после нажатия *ОТПРАВИТЬ* google-формы просят пройти капчу - когда они это просят, непредсказуемо (*возможно, если вы занимались непотребствами*), поэтому, на всякий случай, закладывайте на отправку ответов минимум 30 секунд (если все-таки капчу вас попросят заполнить)
- Вас ждут тестовые вопросы и вопросы с ответом в свободной форме
	- Не нужно спрашивать *а сколько вопросов?*, *а какая разбалловка?* и т.п. Разбалловку вы увидите непосредственно в форме, а остальные вопросы - следствие нервов, не более того. Лучше потратьте свое время на подготовку, а не на написание подобных вопросов
	- На вопросы с ответом в свободной форме - отвечать **строго своими словами**. Копирование ответа из слайдов лекции / интернета / соседа-товарища и т.п. == плагиат, **за плагиат - 0 баллов за КР**
		- Все ответы будут прогнаны через систему *Антиплагиат*
		- Мы не будем разбираться, кто написал оригинальный ответ, а кто скопировал - 0 баллов получат все, у кого в ответах будет повторяющаяся фраза
	- Отвечать старайтесь лаконично и по сути - **от этого напрямую зависит скорость проверки**
	- Не нужно давать зазубренные ответы или воспроизвести лекцию - пишите, как понимаете

#### Что будет на контрольной

Вопросы будут исключительно по лекционному материалу. В промежуточную контрольную войдут все темы лекций №1 - №6, кроме темы про *семейство гибких методологий* (ее мы на лекциях разобрать не успели)

#### Когда проверим? 

- Ориентировочно - в течение полутора - двух недель (студентов много, а проверять будем аккуратно)
- Возможно, быстрее (если все напишут лаконично). Возможно - медленнее (если многие напишут *Войну и Мир* или ответы будут удручать проверяющих)
- Про *удручать проверяющих* - факт. Проверить 50 хороших работ за вечер - приятно, а за то же время вымучать проверку 20 работ с полубредом - страдание
- Не нужно нас пинговать вопросом *когда проверите?*
	- Как только проверим - результаты опубликуем
	- На текущие образовательные процессы результат КР никакого влияния не имеет
	- Аргументация из серии *ну я хочу понимать как я написал КР, чтобы планировать дальнейшие действия по курсу* - контрпродуктивна для образовательного процесса
		- Учиться надо хорошо и все отчетные мероприятия (контрольные, задания, проект) - делать максимально хорошо
		- Позиция *посчитаю, как мне набрать на троечку* понимания среди преподавательского состава не находит

#### Как будет оцениваться? 

- Тестовые вопросы будут оцениваться бинарно (*правильно / неправильно*). В вопросах с множественным выбором - правильным считается только полный ответ. Баллы за частичный ответ не начисляются
- Вопросы со свободным ответом - ставится балл от *0* до *полный балл за вопрос* в зависимости от качества ответа
- **Нормировки по результатам контрольной не будет**
	- Даже если лучший балл будет в районе 50% от полного балла за КР - значит, такие баллы все и получат
	- Аргументация: курс читается, кажется, пятый или уже даже шестой год, за это время удалось выверить тот уровень вопросов по курсу, на которые студенты за Х минут в состоянии ответить при хорошей подготовке. То же относится и к материалу лекций.
	- Соответственно, ситуация *преподавательский состав выдал гробы* исключается
	- Соответственно, что заслужили - то получили. **Невысокий уровень знаний всех студентов по дисциплине не является поводом для снижения требований по дисциплине**
	- Тем не менее, несмотря на то, что вопрос про нормировку поднимается практически каждый год - каждый год находятся студенты, которые пишут контрольную если не на полный балл, то практически на полный
	- Очень надеюсь, что этот год не станет исключением. *Иначе команда преподавателей впадет в депрессию*

## :soon: Лекция №7

### Отладка ПО, ч.2: техники отладки

- Запуск программ в отладчике (трассировка)
	- Софтверный дебаггер
	- "Железный" дебаггер
	- Удаленный дебаггер
- Логирование
	- Работы системы
	- Программного кода
- Анализ программного кода без исполнения программы
	- "Метод пристального взгляда"
	- Статические анализаторы
- Анализ поведения системы
	- Упрощение сценария
	- Ограничение объема данных
	- Упрощение данных / запроса
- UNIT-тестирование
- Прототипирование
- Отладка с помощью дампов
- Отладка с помощью перехватов
- Профилирование кода
- Выполнение кода в другой среде
- Отладка методом RPC (*Remote procedure call*)
- Отладка путем анализа документации
- Отладка трансляцией кода 
	- Трансляция "вниз"
	- Трансляция "вверх"
- Отладка разработкой интерпретатора
- Метод индукции
- Метод дедукции
- Обратное движение по алгоритму

## :soon: Лекция №8

### Управление качеством ПО, ч.1

- Понятие о качестве ПО
- Характеристики и атрибуты качества ПО
- Основые аспекты качества ПО
- Парадокс тестировщика
- Соответствие ожиданиям stakeholder'ов
- Качество и деньги
	- Десятичное правило качества
	- Важные аспекты
- Ручное тестирования
	- Класс эквивалентности
	- Граничные значения
- 7 ключевых инструментов качества
	- Причинно-следственная диаграмма Исикавы
	- Блок-схема
	- Контрольный листок

## :soon: Лекция №9

### Управление качеством ПО, ч.2

- 7 ключевых инструментов качества (*продолжение*)
	- Контрольная карта (карта Шухарта)
		- Примеры
	- Гистограмма
	- Диаграмма Парето
	- Диаграмма разбрасывания
- Ручное тестирование. Практические советы
- Автоматизированное тестирование 
	- Основные аспекты
	- Жизненный цикл автотеста
	- Практические советы
	- Как на практике?

## :soon: Лекция №10

### CI/CD/CD

- CI/CD/CD
- Понятие о Continuous Integration
- Понятие о Continuous Delivery
- Понятие о Continuous Deployment
- Пример организации процесса разработка из индустрии
	- Этап проектирования
	- Этап реализации
	- Этап сдачи задачи
	- Подготовка к выпуску версии

> [TravisCI](https://www.travis-ci.com/)

> [TeamCity](https://www.jetbrains.com/teamcity/)

> [GitHub Actions](https://github.com/features/actions)

> [Jenkins](https://www.jenkins.io/)

## :soon: Лекция №11

### Архитектурные паттерны

- Классификация архитектуры ПО
	- Локальные
	- Распределенные
		- Файл-серверные
		- Клиент-серверные
			- Двухзвенные
			- Трехзвенные
			- Многозвенные
- Локальные приложения 
	- MVC (*Model-View-Controller*)
- Клиент-серверная архитектура 
	- Тонкий и толстый клиент
	- Трехзвенная архитектура
- Оценка нагрузки на систему
- Тип проекта и влияние на нагрузку
- Ресурсы для обеспечения производительности 
- Масштабирование
	- Горизонтальное
	- Вертикальное
	- Функциональное разбиение
	- Шардинг
- Типичная архитектура веб-сервиса
- Типичная архитектура нагруженной информационной системы

## :soon: Лекция №12

### Базовые понятия о языках программирования

- Парадигмы программирования
	- Императивное программирование
		- Описание
		- Примеры
		- "Вложенные парадигмы"
			- Процедурное программирование
			- Структурное программирование
			- Аспектно-ориентированное программирование
			- Объектно-ориентированное программирование
			- Обобщенное программирование
	- Декларативное программирование
		- Пример-объяснение
		- "Вложенные парадигмы"
			- Логическое программирование 
			- Функциональное программирование
	- Общая схема парадигм
	- Метапрограммирование
	- Реализация парадигм в языках программирования
- Компилируемые и интерпретируемые языка
	- Определения
	- Примеры
- Типизация
	- Сильная / слабая типизация
	- Статическая / динамическая типизация
	- Явная / неявная типизация

[0]:https://img.shields.io/badge/year-2022-blue
[1]:https://img.shields.io/badge/status-running-green
[2]:https://progress-bar.dev/50/