
# Основные команды Git. Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.


**Git** — самая популярная в мире распределённая система контроля версий. Линус Торвальдс, разработчик ядра ОС Linux, создал этот инструмент ещё в 2005 году, а сегодня Git активно поддерживается как проект с открытым исходным кодом. Огромное количество открытых и коммерческих проектов используют Git для контроля версий.

>При первом использовании Git необходимо представиться. Для
этого нужно ввести в терминале 2 команды:
*git config --global user.name «Ваше имя английскими буквами»*, *git
config --global user.email ваша почта@example.com*

## Инициализация репозитория
**git init** - создать пустой репозиторий Git или вновь инициализировать существующий можно параметром init. При инициализации он создаст скрытую папку. В ней содержатся все объекты и ссылки, которые Git использует и создаёт в истории работы над проектом.

## Добавление отдельных файлов или всех файлов в область подготовленных файлов
**git add** - добавить отдельный файл в область подготовленных файлов можно параметром add с указанием имени файла. 

## Проверка статуса репозитория
**git status** – Просмотреть статус нужного репозитория можно по ключевому слову status: его действие распространяется на подготовленные, неподготовленные и неотслеживаемые файлы.

## Внесение изменений однострочным сообщением или через редактор
**git commit -m “message”** - при создании коммита в репозитории можно добавить однострочное сообщение с помощью параметра commit с флагом -m. Само сообщение вводится непосредственно после флага, в кавычках.
 – создание коммита.

## Просмотр истории коммитов с изменениями
**git log** - просматривать изменения, внесённые в репозиторий, можно с помощью параметра log. Он отображает список последних коммитов в порядке выполнения. Кроме того, добавив флаг -p, вы можете подробно изучить изменения, внесённые в каждый файл.

## Просмотр изменений до коммита
**git diff** - можно просматривать список изменений, внесённых в репозиторий, используя параметр diff. По умолчанию отображаются только изменения, не подготовленные для фиксации.

## Переход от одного коммита к другому
***git checkout*** – Восстановить файлы рабочего дерева, не подготовленные к коммиту, можно параметром checkout. Для проведения операции требуется указать путь к файлу. Если путь не указан, параметр git checkout изменит указатель HEAD, чтобы задать указанную ветку как текущую.

**git checkout master** – вернуться к актуальному состоянию и продолжить работу

**git pull** – получение изменений и слияние с локальной версией

**git push** – отправляет локальную версию репозитория на внешний

> &#8220;Прекарсный инструмент!&#8221;

