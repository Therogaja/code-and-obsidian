# Empezando

### Objetivos de aprendizaje

Después de esta sección

- Habrás escrito y ejecutado tu primer programa en Python.
- Sabrás cómo utilizar el comando de impresión.
- Podrás utilizar la programación para operaciones aritméticas.

Los programas informáticos constan de _comandos_ , cada uno de los cuales indica al ordenador que realice una acción. El ordenador ejecuta estos comandos uno por uno. Entre otras cosas, los comandos pueden utilizarse para realizar cálculos, comparar elementos en la memoria del ordenador, modificar el funcionamiento del programa, transmitir mensajes o solicitar información al usuario del programa.

Comencemos la programación familiarizándonos con el `print`comando que _imprime_ texto. En este contexto, imprimir significa básicamente que el programa mostrará texto en la pantalla.

El siguiente programa imprimirá la línea "¡Hola!":

```python
print("Hi there!")
```

Cuando se ejecuta el programa, produce esto:

Salida:

<font color="#8064a2">¡Hi there!</font>

El programa no funcionará a menos que el código esté escrito exactamente como se indica arriba. Por ejemplo, intentar ejecutar el comando de impresión sin las comillas, así:

```python
print(Hi there!)
```

no imprimirá el mensaje, sino que provocará un error:

Salida:

<font color="#8064a2">Archivo "", línea 1</font>
<font color="#8064a2">  print(Hí there!)</font>
<font color="#8064a2">                   ^</font>
<font color="#8064a2">SyntaxError: sintaxis no válida</font>

==En resumen, si desea imprimir texto, todo el texto debe estar entre comillas o Python no lo interpretará correctamente.==

## Emoticon
Por favor escribe un programa que imprima un emoticono: :-)
```python
print(":-)")
```

Salida: 

<font color="#8064a2">:-)</font>

## Un programa de múltiples comandos

Múltiples comandos escritos sucesivamente se ejecutarán en orden del primero al último. Por ejemplo, este programa

```python
print("Welcome to Introduction to Programming!")
print("First we will practice using the print command.")
print("This program prints three lines of text on the screen.")
```

imprime las siguientes líneas en la pantalla:

<font color="#8064a2">Welcome to Introduction to Programming! </font>
<font color="#8064a2">First we will practice using the print command. </font>
<font color="#8064a2">This program prints three lines of text on the screen.</font>
### Arregla el código: Siete Hermanos


"Seitsemän veljestä" es una de las primeras novelas escritas en finlandés. Es la historia de siete hermanos huérfanos que aprenden a abrirse camino en el mundo ( [más información en Wikipedia](https://en.wikipedia.org/wiki/Seitsem%C3%A4n_veljest%C3%A4) ).

Se supone que este programa imprime los nombres de los hermanos en orden alfabético, pero aún no funciona correctamente. Por favor, arreglen el programa para que los nombres se impriman en el orden correcto.

```python
print("Simeoni")
print("Juhani")
print("Eero")
print("Lauri")
print("Aapo")
print("Tuomas")
print("Timo")
```

```python
# Fix the code

print("Aapo")

print("Eero")

print("Juhani")

print("Lauri")

print("Simeoni")

print("Timo")

print("Tuomas")
```

salida: 

<font color="#8064a2">Aapo</font>
<font color="#8064a2">Eero</font>
<font color="#8064a2">Juhani</font>
<font color="#8064a2">Lauri</font>
<font color="#8064a2">Simeoni</font>
<font color="#8064a2">Timo</font>
<font color="#8064a2">Tuomas</font>
### Rema, rema, rema tu bote


Por favor, escriba un programa que imprima las siguientes líneas exactamente como están escritas aquí, con puntuación y todo:

Row, row, row your boat,
Gently down the stream.
Merrily, merrily, merrily,
merrily, Life is but a dream.

```python
# Write your solution here

print("Row, row, row your boat,")

print("Gently down the stream.")

print("Merrily, merrily, merrily, merrily,")

print("Life is but a dream.")
```

salida :

<font color="#8064a2">Row, row, row your boat,</font>
<font color="#8064a2">Gently down the stream.</font>
<font color="#8064a2">Merrily, merrily, merrily, merrily,</font>
<font color="#8064a2">Life is but a dream.</font>
## Operaciones aritméticas

También puedes incluir operaciones aritméticas dentro de un `print`comando. Al ejecutarlo, se imprimirá el resultado de la operación. Por ejemplo, el siguiente programa

```python
print(2 + 5)
print(3 * 3)
print(2 + 2 * 10)
```


Salida:

<font color="#8064a2">7 9 22</font>

Observe la ausencia de comillas en las operaciones aritméticas anteriores. Las comillas se usan para indicar _cadenas_ . En programación, las cadenas son secuencias de caracteres. Pueden constar de letras, números y cualquier otro tipo de carácter, como signos de puntuación. Las cadenas no son simplemente palabras como las entendemos comúnmente, sino que una sola cadena puede tener la misma longitud que varias oraciones completas. Las cadenas suelen imprimirse exactamente como se escriben. Por lo tanto, los dos comandos siguientes producen dos resultados bastante diferentes:

```python
print(2 + 2 * 10)
print("2 + 2 * 10")
```

Salida:

<font color="#8064a2">22 2 + 2 * 10</font>

Con la segunda línea de código, Python no calcula el resultado de la operación, sino que la imprime como una cadena. Por lo tanto, las cadenas se imprimen tal como se escriben, sin referencia a su contenido.

## Comentando[

Cualquier línea que comience con el símbolo numeral `#`, también conocido como almohadilla o numeral, es un comentario. Esto significa que cualquier texto en esa línea después del `#`símbolo no afectará en absoluto el funcionamiento del programa. Python simplemente lo ignorará.

Los comentarios se utilizan para explicar el funcionamiento de un programa, tanto al programador como a quienes leen el código. En este programa, un comentario explica el cálculo realizado en el código:

```python
print("Hours in a year:")
# there are 365 days in a year and 24 hours in each day
print(365*24)
```

Cuando se ejecuta el programa, el comentario no será visible para el usuario:

Salida:

<font color="#8064a2">Hours in a year: 8760</font>

También se pueden agregar comentarios breves al final de una línea:

```python
print("Hours in a year:")
print(365*24) # 365 days, 24 hours in each day
```

### Minutos en un año

Escriba un programa que muestre la cantidad de minutos de un año. Use código Python para realizar el cálculo, como en el ejemplo anterior.
```python
print("minutos en un año:")

print(60*24*365) #365 dias, 24 horas, 60 segundos en una hora
```

Salida:

<font color="#8064a2">minutos en un año: 525600</font>
### Imprime algún código

Hasta ahora, probablemente hayas usado comillas dobles `"`para imprimir cadenas. Además de las comillas dobles, Python también acepta comillas simples `'`.

Esto resulta útil si alguna vez desea imprimir las comillas reales:

```python

print('"Come right back!", shouted the police officer.')
```

Salida:

<font color="#8064a2">"Come right back!", shouted the police officer.</font>

Por favor escriba un programa que imprima lo siguiente:

print("Hello there!")

```python
print('print("Hello there!")')
```

Salida:

<font color="#8064a2">print("Hello there!")</font>