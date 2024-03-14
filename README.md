Урок 7. Рефлексия

Разработайте атрибут позволяющий методу ObjectToString сохранять поля классов с использованием произвольного имени.

Метод StringToObject должен также уметь работать с этим атрибутом для записи значение в свойство по имени его атрибута.

[CustomName(“CustomFieldName”)]

public int I = 0.

Если использовать формат строки с данными использованной нами для предыдущего примера то пара ключ значение для свойства I выглядела бы CustomFieldName:0

Подсказка:

Если GetProperty(propertyName) вернул null то очевидно свойства с таким именем нет и возможно имя является алиасом заданным с помощью CustomName.
Возможно, если перебрать все поля с таким атрибутом то для одного из них propertyName = совпадает с таковым заданным атрибутом.
