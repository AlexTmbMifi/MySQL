# MySQL
Конспект занятий по MySQL на русском языке. Краткое содержание основным тем.

# 1. База данных. Применение. Требования к современным базам данных. Виды представления информации

**Данные** - это любая организованная информация об отдельной сущности (человек, предмет, организация).
**База данных** - это структурированная коллекция данных.

Применяются в различных сферах деятельности, такие как медицина, бизнес, финансы и другие.

Современные базы данных отвечают следующим **требованиям**:

1. Хранение объемных баз данных
2. Высокая степень организованности
3. Доступ к данным

Выделяют следующие **представления** информации:

1. Плоские файлы (**CSV-файлы**). Нет строгой организации информации.
2. Иерархическая модель. Позволяет эффективно описать модель организации, однако данная модель далека от реальной картины, так как связи между объектами могут быть гораздо сложнее.
3. Сетевая модель. Учитывает дополнительные связи между объектами, однако сложно контролировать все связи и менять их структуру.
4. Реляционная модель. Табличное представление данных. Удобно производить вставку данных, обновление и удаление, когда таблицы являются независимыми.
5. Модель ключ-значение. Очень полезное представление в плане производительности, но неэффективно для анализа данных.
6. Документная модель. Удобна для разворачивание масштабных проектов, т.к. файлы в формате **JSON** или **XML** описывают полную информацию.
