# hello
number = int(input("Ingrese número:"))
is_primo = True
for primo in range(2, number):
  if (number % primo == 0):
    return False
print(is_primo)
