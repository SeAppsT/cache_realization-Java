*Тестовое задание*

# Cache

*Примечание*

Я знаю две трактовки кэша LFU:
* Каждый элемент имеет счетчик обращений, и, когда надо, удаляется элемент с наименьшим значением счетчика.
* Каждый элемент (помимо счетчика) знает физическое время, в которое он добавился, и при удалении оно учитывается для определения элемента, который *реже* всего использовался.

У меня реализована вторая.
