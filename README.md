1.	Какие действия необходимо выполнить чтобы подготовить среду разработки для инспекции кода?
В среде Github при работе с командами разработчиков про-граммного обеспечения обычно при подготовке необходимо выпол-нить следующие действия:
•	Добавить среду необходимых членов команды (организация и соавторы).
•	Обеспечить возможность отправки версий и их слияния (Pull Requests).
•	Обеспечить отслеживание ошибок (issues Github).
•	Реализовать возможность комментариев к строками URL-запросов.

2.	Какие методы существуют для настройки Github для совместной работы нескольких разработчиков?
Как правило, существует два способа настройки в Github для совместной работы необходимых членов команды:
•	Создание организаций. Владелец организации может создавать множество организаций с разными уровнями доступа для различных репозиториев.
•	Добавление сотрудников. Владелец репозитория может до-бавлять коллабораторов с доступом Read + Write для одного репозитория

3.	Что такое организация разработки в сервисе Github?
Организация разработки в сервисе GitHub представляет собой способ организации проектов и управления доступом к ним для группы разработчиков или организации. Ключевые аспекты организации разработки в GitHub:
• Репозитории: Организация может иметь свои репозитории для хранения и управления исходным кодом проектов. Репозитории могут быть публичными или приватными.
• Коллаборация: Члены организации могут работать вместе над проектами, делиться кодом, создавать запросы на слияние (Pull Requests) и обсуждать изменения.
• Управление доступом: Администраторы организации могут управлять доступом к репозиториям, устанавливать различные уровни доступа (например, чтение, запись) для членов организации.
• Проекты и задачи: GitHub предоставляет инструменты для управления проектами, создания задач, отслеживания ошибок и планирования работы над проектами.
• Вики и документация: Организация может использовать вики-страницы и другие инструменты для создания документации по проектам.
• Интеграция с другими сервисами: GitHub предлагает возможность интеграции с различными сервисами CI/CD, системами отслеживания ошибок, системами управления задачами и другими инструментами разработки.
• Аналитика и отчетность: GitHub предоставляет инструменты для анализа статистики по проектам, отслеживания активности участников и других метрик.
Организация разработки в GitHub помогает эффективно управлять проектами, сотрудничать над кодом и обеспечивать прозрачность в работе команды разработчиков.

4.	Какие уровни доступа могут быть заданы для организации в Github?
• Владелец (Owner): Владелец имеет полный доступ ко всем репозиториям в организации. Он может управлять членами организации, приглашать новых участников, изменять настройки безопасности и другие параметры.
• Администратор (Admin): Администраторы имеют почти такие же права, как и владелец. Они могут управлять репозиториями, приглашать новых участников, изменять настройки безопасности и другие параметры. Однако они не могут удалить организацию или изменить роль владельца.
• Член (Member): Члены имеют доступ к репозиториям и могут работать с кодом, создавать запросы на слияние и участвовать в проектах. Они обычно не имеют права изменять настройки организации.
• Стажер (Billing Manager): Этот уровень доступа предоставляет возможность управлять платежами и подписками организации.
• Публичный доступ (Public): Этот уровень доступа предоставляется для публичных репозиториев, к которым имеют доступ все пользователи GitHub.

5.	Какие параметры должны быть заданы при настройке отправки и слияния копии репозитория?
• URL удаленного репозитория (Remote URL): Необходимо указать URL удаленного репозитория, куда будут отправляться изменения.
• Ветка (Branch): Укажите ветку, которую вы хотите отправить на удаленный репозиторий или сливать с ним.
• Сообщение коммита (Commit Message): При отправке изменений в репозиторий важно добавить понятное сообщение коммита, описывающее сделанные изменения.
• Опции слияния (Merge Options): Если вы сливаете изменения из другой ветки или репозитория, убедитесь, что выбраны правильные опции слияния (например, fast-forward merge или merge commit).
• Конфликты (Conflicts): При возникновении конфликтов во время слияния, вам нужно будет разрешить их вручную. Обратите внимание на инструкции по разрешению конфликтов.
• Права доступа (Access Rights): Убедитесь, что у вас есть соответствующие права доступа для отправки и слияния изменений в удаленном репозитории.
• Тестирование изменений (Testing Changes): Перед отправкой изменений на удаленный репозиторий рекомендуется протестировать их локально, чтобы убедиться, что они работают корректно.
   
6.	Какие модели применяются при создании копии репозитория?
В Github есть две модели для создания копии репозитория.
Модель Fork & Pull – используется в общедоступном репозитории, на который у вас нет push-доступа
Share Repository Model – используется в частном репозитории, на который у нас есть push-доступ. В этом случае форк не требуется.

7.	Что такое «обзор кода»?
С каждой фиксацией изменений Github позволяет использовать чистый интерфейс для общих комментариев или даже конкретных комментариев к отдельной строчке кода.
Возможность делать комментарии или задавать вопросы по каждой отдельной строке кода очень полезна при проведении обзоров строка за строкой.
При обзоре кода могут быть использованы шаблоны URL-адресов, они предоставляют возможность отслеживать различия между фиксациями.
