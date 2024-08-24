# net-income-sweetshop
print("Earned amount:")

earned_bubblegum = float(input("Bubblegum: £"))
earned_toffee = float(input("Toffee: £"))
earned_icecream= float(input("Ice Cream: £"))
earned_milk_chocolate = float(input("Milk Chocolate: £"))
earned_doughnut = float(input("Doughnuts: £"))
earned_pancake = float(input("Pancakes: £"))

total = earned_bubblegum + earned_toffee + earned_icecream + earned_milk_chocolate + earned_doughnut + earned_pancake
total_earned = round(total, 2)

print("\nIncome: £" + str(total_earned))




staff_expenses = float(input("\nStaff expenses: £"))
other_expenses = float(input("Other expenses: £"))
net_income = round(total - staff_expenses - other_expenses, 2)

print("\nNet income: £" + str(net_income ))
