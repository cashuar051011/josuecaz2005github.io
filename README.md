<!DOCTYPE html>
<html>
	<head>
		<title>Hello World</title>
	</head>
	<body>
		<h1>Hello, World!</h1>
	</body>
</html>


# Lista de números
numeros = [1, 2, 3, 4, 5]
print("Lista de números:", numeros)

# Lista de cadenas de texto
nombres = ["Juan", "María", "Pedro"]
print("Lista de nombres:", nombres)

# Lista mixta
mixta = [1, "Hola", 3.14, True]
print("Lista mixta:", mixta)

# Acceder a elementos de la lista
print("Primer elemento de la lista de números:", numeros[0])
print("Último elemento de la lista de nombres:", nombres[-1])

# Modificar elementos de la lista
numeros[2] = 10
nombres.append("Luis")

# Eliminar elementos de la lista
del mixta[1]
nombres.remove("Juan")

# Longitud de la lista
print("Longitud de la lista de números:", len(numeros))

# Ordenar la lista
numeros.sort()
print("Lista de números ordenada:", numeros)

# Buscar un elemento en la lista
if "María" in nombres:
    print("María está en la lista de nombres")

# Iterar sobre la lista
for numero in numeros:
    print(numero)



<dl>
  <dt>HTML</dt>
  <dd>Lenguaje de marcado utilizado para estructurar el contenido de una página web.</dd>
  
  <dt>CSS</dt>
  <dd>Lenguaje de estilo utilizado para definir la apariencia y presentación de una página web.</dd>
  
  <dt>JavaScript</dt>
  <dd>Lenguaje de programación utilizado para agregar interactividad y funcionalidad a una página web.</dd>
  
  <dt>Python</dt>
  <dd>Lenguaje de programación de alto nivel conocido por su simplicidad y legibilidad de código.</dd>
</dl>



<table>
  <tr>
    <th>Nombre</th>
    <th>Edad</th>
    <th>País</th>
  </tr>
  <tr>
    <td>John Doe</td>
    <td>30</td>
    <td>Estados Unidos</td>
  </tr>
  <tr>
    <td>Jane Smith</td>
    <td>25</td>
    <td>Canadá</td>
  </tr>
  <tr>
    <td>Carlos García</td>
    <td>35</td>
    <td>México</td>
  </tr>
</table>


<img src="https://www.dodge.com.ec/img/slider/globales/web/durango-01.jpg" alt="Dodge Durango STR">

<a href="https://www.dodge.com.ec/">
  Visita el sitio web de Dodge Ecuador
</a>

