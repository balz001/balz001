# "input.txt" файлын ашу және оқу
with open('input.txt', 'r') as input_file:
    number = int(input_file.read().strip())  # Оқылған санны сандық дайындалдырып алу

# Санның квадратын есептеу
square = number ** 2

# "output.txt" файлына квадратты санды жазу
with open('output.txt', 'w') as output_file:
    output_file.write(str(square))

