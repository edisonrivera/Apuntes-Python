# Métodos 🥋

Son **funciones** (Luego las veremos), que ya vienen implementas automáticamente en Python. 🐍


* La variable que ocuparé para usar los métodos será: `cadena = "hola mundo"`

| Método | ¿Qué hace? | Código | Salida |
|:--------:|:---------:|:------:|:-------:|
| `capitalize()` | Transorma la primera letra a mayúscula | `cadena.capitalize()` | **Hola mundo**
| `count(<caracter>)` | Retorna la cantidad de veces del caracter que elijamos  | `cadena.count('o')` | **2** |
| `center(<longitud>, <caracter>)`    | Centra nuestra con una longitud dada y podemos indicarle un caracter | `cadena.center(20, '_')` | **-----hola mundo-----**|
| `title()` | Tranforma la primera letra de cada palabra a una mayúscula | `cadena.title()` | **Hola Mundo** |
| `upper()` | Transforma todas las letras a mayúsculas  | `cadena.upper()` | **HOLA MUNDO** |
| `lower()` | Transforma todas las letras a minúsculas | `cadena.lower()`  | **hola mundo** |
| `swapcase()` | Si la letra es mayúscula la transforma en minúscula y viceversa  | `cade.swapcase()` | **HOLA MUNDO** |

* Estos son métodos más "fáciles" y cómunes, ahora veremos algunos métodos más complejos.

## **strip** 🔧
Este método nos sirve para quitar los espacios en blanco tanto de la izquiera como la derecha de una cadena de texto.

```python
variable = "   Mensaje 😁   "
print(variable.strip())
```
**Output**
```
Mensaje 😁
```

---
## **replace** 🔁
Con este métodos podemos reemplazar cualquier caracter con uno nuevo.
```python
variable = "Mensaje 😁"
print(variable.replace("😁", "😈"))
```

* El **primer argumento** es el caracter que vamos a cambiar y el **segundo argumento** será el reemplazo.

**Output**
```
Mensaje 😈
```

---
## startswith() 🔜 & endswith() 🔚 
* `startswith()`: Saber si la cadena **empieza** con letras o palabras en específico.
* El resultado que obtendremos será una **variable booleana**.
```python
variable = "Mensaje de Prueba 🤑"
print(variable.startswith("Prueba"))
```
**Output**
```
False
```
> El mensaje no empieza con la palabra **Prueba**.


* `endsswith()`: Saber si la cadena **termina** con letras o palabras en específico.

```python
variable = "Mensaje de Prueba 🤑"
print(variable.endswith("🤑"))
```
**Output**
```
True
```
> El mensaje si termina con 🤑

---
## isalnum(), isalpha(), isnumeric() 🔢🆎

* `isalnum()`: Saber si la cadena de texto de compone **únicamente** por **letras y números**.
* `isalpha()`: Con esto sabremos si la cadena de texto únicamente contiene **letras**.
* `isnumeric()`: Sabremos si la cadena de texto se compone **únicamente** por **números**.
  * Este método reconoce números de todas partes (Números romanos, exponentes...)

* `isdigit()`: Detecta si la cadena de texto contiene **números únicamente de 0 a 9**.

* El resultado que obtendremos será una **variable booleana**.
* Ten cuidado con los espacios en blanco, algunos métodos retornan `False` por contenerlos. ⚠

```python
texto = "Esternocleidomastoideo"
numeros = "ⅪⅢ"
mix = "H0l4"
digitos = "0123456789"

print(texto.isalpha())
print(numeros.isnumeric())
print(mix.isalnum())
print(digitos.isdigit())
```
**Output**
```
True
True
True
True
```