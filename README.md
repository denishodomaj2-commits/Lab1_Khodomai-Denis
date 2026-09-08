print("Hello, world!")

print("\n--- Створення змінних ---")

age = 17
height = 1.75
name = "Іван"
is_student = True
complex_number = 3 + 4j

numbers = [1, 2, 3, 4, 5]
coordinates = (10, 20)
unique_numbers = {1, 2, 3}

student = {
    "name": "Іван",
    "age": 17
}

print("age =", age, "| Тип:", type(age))
print("height =", height, "| Тип:", type(height))
print("name =", name, "| Тип:", type(name))
print("is_student =", is_student, "| Тип:", type(is_student))
print("complex_number =", complex_number, "| Тип:", type(complex_number))
print("numbers =", numbers, "| Тип:", type(numbers))
print("coordinates =", coordinates, "| Тип:", type(coordinates))
print("unique_numbers =", unique_numbers, "| Тип:", type(unique_numbers))
print("student =", student, "| Тип:", type(student))

print("\n--- Арифметичні оператори ---")

a = 10
b = 3

print("Додавання:", a + b)
print("Віднімання:", a - b)
print("Множення:", a * b)
print("Ділення:", a / b)
print("Цілочисельне ділення:", a // b)
print("Остача від ділення:", a % b)
print("Піднесення до степеня:", a ** b)

print("\n--- Оператори порівняння ---")

print("a == b:", a == b)
print("a != b:", a != b)
print("a > b:", a > b)
print("a < b:", a < b)
print("a >= b:", a >= b)
print("a <= b:", a <= b)

print("\n--- Логічні оператори ---")

x = True
y = False

print("x and y:", x and y)
print("x or y:", x or y)
print("not x:", not x)

print("\n--- Оператори присвоєння ---")

c = 5
c += 2
print("c += 2:", c)

c -= 1
print("c -= 1:", c)

c *= 3
print("c *= 3:", c)

c /= 2
print("c /= 2:", c)

print("\n--- Умовний оператор ---")

if age >= 16:
    print("Вік достатній для прикладу умови.")
else:
    print("Вік менший за 16.")

print("\n--- Оператор in ---")

print("Чи є 3 у списку:", 3 in numbers)

print("\n--- Оператор is ---")

value = None
print("value is None:", value is None)

print("\n--- Кінець програми ---")
