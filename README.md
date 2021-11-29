from math import tan, pi

print("Введите количество сторон:")

n = int(input())

n = round(n)

print("Введите длину одной стороны:")

s = int(input())


area = (n * s ** 2) / (4 * tan(pi / n))

print(area) 

n = int(input())

sum = (n * (n + 1)) / 2

print(sum)

