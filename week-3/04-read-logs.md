# Внимательное чтение логов

Показывает несколько smells:
- несколько однотипных запросов к одной таблице
- большое кол-во запросов вообще

Гипотеза к оценке/проверке: будет лучше, если необходимые данные из одной и той же таблицы собирать за один запрос.