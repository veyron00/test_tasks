# УДАЛЕНИЕ ДУБЛИКАТОВ С ПОЛЕДОВАТЕЛЬНОСТИ / REMOVING DUPLICATES FROM SEQUENCE
# Пожалуйста, решите следующую простую задачу. Можно использовать любые инструменты.
#
# Дано: список dict-объектов вида вида {"key": "value"}, например [{"key1": "value1"}, {"k1": "v1", "k2": "v2", "k3": "v3"}, {}, {}, {"key1": "value1"}, {"key1": "value1"}, {"key2": "value2"}].
#
# Напишите функцию, которая удаляет дубликаты из этого списка. Для примера выше возвращаемое значение может быть равно [{"key1": "value1"}, {"k1": "v1", "k2": "v2", "k3": "v3"}, {}, {"key2": "value2"}].
# Обязательное условие: функция не должна иметь сложность O(n^2).



my_seq = [{"key1": "value1"}, {"k1": "v1", "k2": "v2", "k3": "v3"}, {}, {}, {"key1": "value1"}, {"key1": "value1"}, {"key2": "value2"}]

def checking_for_duplicates(seq: list)-> list:
    no_duplicates = []
    for value in seq:
        if value not in no_duplicates:
            no_duplicates.append(value)
        else:
            continue
    return no_duplicates


print(checking_for_duplicates(my_seq))
