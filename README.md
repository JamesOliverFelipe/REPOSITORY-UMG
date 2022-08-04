# REPOSITORY-UMG

------------ Jimmy Yaque ------------------
given_file = open('Numeros.txt', 'r')

lines = given_file.readlines()

for line in lines:
    for c in line:
        if c.isdigit() == True:
            print('Numero encontrado : {}'.format(c))

given_file.close()
