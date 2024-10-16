# Code123
16.10.24 код
# 1
age = int(input("Введите ваш возраст: "))
if age > 14:
    print("Добро пожаловать!")
elif age == 14:
    print("Вам 14 лет! Поздравляю!")
elif age < 14:
    print("Вам ещё рано!")
# 2
secret = input("Введите секретный пароль: ")
password = input("Введите пароль: ")
if password == secret:
    print("Доступ разрешён!")
else:
    print("Неверный пароль!")

# 3
sim = input("Введите символ: ")
numbers = "0, 1, 2, 3, 4, 5, 6, 7, 8, 9"
latin = "q, w, e, r, t, y, u, i, o, p, a, s, d, f, g, h, j, k, l, z, x, c, v, b, n, m, ё, й, ц, у, к, е, н, г, ш, щ, з, х, ъ, ф, ы, в, а, п, р, о, л, д, ж, э, я, ч, с, м, и, т, ь, б, ю"
if sim in numbers:
    print("Это цифра!")
elif sim in latin:
    print("Это буква!")
else:
    print("Это не цифра и не буква!")

# 4
total = 0
sale = int(input("Введите цену товара: "))
if sale > 1000:
    total = sale * 0.9
    print(total)
elif 500 < sale <= 1000:
    total = sale * 0.95
    print(total)
elif  0 < sale <= 500:
    total = sale
    print(total)

# 1
sum = 0
for i in range(1, 6):
    x = int(input("Введите число: "))
    sum += x
print(sum)

# 2
y = 1
x = int(input())
for x in range(1, x):
    y = x*(x-1)
    x -= 1
print(y)
