f = open("out.txt", "r")

count = 0
for list in f:
    list = int(list)
    sum_num = +list
    count += 1
s = sum_num / count

print("Cреднее значение: ", s)
print("Сумма чисел: ", sum_num)
