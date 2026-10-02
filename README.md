# Приветствие 
print('Здравствуйте! Я ваш финтес помощник.') 

# Узнаем данные
user_name = input('Как вас зовут? ')
print(f'Приятно познакомиться, {user_name}!')
user_age = int(input('Сколько вам лет? '))
user_weight = float(input('Сколько вы весите? '))
user_height = float(input('Какой у вас рост? Напишите в метрах через точку. ' ))

# Расчеты
water_per_kg = 30
water_ml_per_kg = 1000
bmi = user_weight / (user_height ** 2) 
bmi = round(bmi, 1)
water_ml = user_weight * water_per_kg 
water_l = water_ml / water_ml_per_kg

# Результат
print(f'Отчет для пользователя {user_name} готов')
print(f'Ваш индекс массы тела: {bmi}')
print(f'Рекомендуемая суточная норма воды: {water_l} литров')
print()
print('Расчет окончен, будьте здоровы!')
