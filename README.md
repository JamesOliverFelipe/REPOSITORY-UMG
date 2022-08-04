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
-------------- JERRY CORDERO ------------------

class Cliente(Persona):
    nit = models.CharField('NIT', max_length=10, unique=True, null=True, blank=True, default='C/F')
    nombre_comercial = models.CharField('Nombre Comercial', max_length=100, null=True, blank=True)
    direccion = models.CharField('Dirección', max_length=150)

    class Meta():
        db_table = 'cliente'
        verbose_name = 'Cliente'
        verbose_name_plural = 'Clientes'
        unique_together = ['nombre', 'apellido']
    
    def __str__(self):
        return "%s - %s" % (self.nit, self.nombre_comercial)
