# ЗАДАНИЕ ПО ТЕМЕ "Основные операторы"

number = int(input('Введите целое число от 3 до 20: '))
result = ''  # Создаем переменную для пароля

for i in range(1, (number + 1) // 2):  #
    for j in range(i + 1, number - i + 1):  #
        sum_ = i + j
        if number % sum_ == 0:
            result += str(i) + str(j)
print('Пароль:', result)