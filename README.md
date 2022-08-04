# REPOSITORY-UMG

------------ Jimmy Yaque ------------------
given_file = open('Numeros.txt', 'r')

lines = given_file.readlines()

for line in lines:
    for c in line:
        if c.isdigit() == True:
            print('Numero encontrado : {}'.format(c))

given_file.close()
/n
------------ Oliver Ruiz--------------------
<html>
<head>
<title>Calculadora</title> 
<link rel="stylesheet" type="text/css" href="calculadora.css" />
<script type="text/javascript" src="calculadora.js"></script>
</head>
<body>
<div class="calculadora"
<form action="#" name="calculadora" id="calculadora">
<p id="textoPantalla">0</p>
<p>
