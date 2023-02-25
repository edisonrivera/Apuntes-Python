# Operadores ➗➖➕✖

| Operador | Operacion | Ejemplo |
|:--------:|:---------:|:------:|
|   `+`    |   Suma    | `1 + 2 = 3` |
|   `-`    |   Resta   | `4 - 2 = 2` |
|   `*`    | Multiplicación | `4 * 2 = 8` |
|   `**`   |  Potencia      | (base**exponente) `4**2 = 16` |
|   `/`    | División  | `5/2 = 2.5` |
|   `//`   | División entera | `5//2 = 2`  |
|   `%`    |   Módulo / Resto  | `4%2 = 0`  |

Nosotros ya sabemos como realizar operaciones básicas, sin embargo veamos uno ejemplos con cada **operador** antes mencionado.

### Jerarquía de Operaciones ♟
¿Podrías adivinar el resultado de las siguientes operaciones? 🤔

1. `1 + 2 * 3`
2. `2 * 2 ** 3`
3. `5 // 2 * 3`

Python sigue una jerarquía en las operaciones:

* **Primero** Operaciones en paréntesis. `()`
* **Segundo** Exponentes. `**`
* **Tercero** Multiplicación, División. `* / //`
* **Cuarto** Sumas, Restas. `+ -`

* Se debe tener en cuenta también que las operaciones se realizan de **izquierda a derecha** 👉👉👉👉

Por cierto el resultado de las operaciones anteriores:
1. `7`
2. `16`
3. `6`