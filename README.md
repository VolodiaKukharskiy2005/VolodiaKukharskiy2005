beta = None
key = 1
while key == 1:
    print("Виберіть дію.", "Введіть 1 для підрахунку букв.","Введіть 2 для сортування слів в алфавітному порядку.", sep='\n')
    beta = int(input("Виберіть дію "))
    a = input()
    count = len(a)

    if beta == 1:

        letter = "a"
        print(letter, '=', a.count(letter))

    elif beta == 2:
        result = str(sorted(a.split(), key=str.lower))
        print(result)

        key = int(input('Enter 2 to exit code or enter to continue'))

