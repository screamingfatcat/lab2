# TODO Посчитайте количество  месяцев, которое можно протянуть без долгов
money_capital = 20000  # Подушка безопасности
salary = 5000  # Ежемесячная зарплата
spend = 6000  # Траты за первый месяц
increase = 0.05  # Ежемесячный рост цен
mounth = 0  # Количество месяцев без долгов
money_capital = money_capital - spend + salary
while money_capital > 1000:
    mounth +=1
    spend = spend + spend * increase
    money_capital = money_capital - spend + salary
print("Количество месяцев, которое можно протянуть без долгов:", mounth)
