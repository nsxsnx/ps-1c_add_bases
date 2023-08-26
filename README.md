# Автоматическое добавление в список баз 1С на основе групп безопасности Active Directory
----
# Как пользоваться:
1. Создаем в Active Directory группу безопасности для каждой БД 1С. Включаем в группу учетные записи пользователей или группы пользователей, которым должна быть добавлена конкретаня база.
2. **Важно!** В поле description/описание группы указываем UNC-путь к файлу V8I с настроками базы. Пример: \\\\server.domain\\Path\\1c_base.v8i
3. Используем скрипт в качестве пользовательского логон-скрипта в Active Directory Group Policy
