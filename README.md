# Задача дедубликации торговых точек

Этот проект включает в себя написание кода на Python для дедубликации торговых точек, а также создание и обновление связанных SQL-таблиц.

# Структура проекта
processing.ipynb: Jupyter Notebook, содержащий весь код Python, использованный для обработки и дедубликации данных.
python_task.sql: SQL-файл, включающий структуру таблиц и команды для вставки данных.
README.md: Этот файл, описывающий проект и его компоненты.
# Работа в Python
Дедубликация данных: processing.ipynb содержит код Python для идентификации и удаления дубликатов из набора данных торговых точек. Все шаги обработки подробно описаны в ноутбуке.
Подготовка к импорту в SQL: После обработки данных, ноутбук генерирует CSV-файлы, которые затем могут быть импортированы в SQL-базу данных.

# Работа с SQL
Создание таблиц: python_task.sql содержит SQL-команды для создания необходимых таблиц в базе данных.
Импорт данных: Файл также включает команды INSERT для добавления обработанных данных в эти базы данных.
Настройка связей: В файле описаны внешние ключи и связи между таблицами, что обеспечивает целостность данных.
