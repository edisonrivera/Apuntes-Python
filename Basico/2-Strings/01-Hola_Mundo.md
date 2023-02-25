# Hola Mundo 🔡🔠

Los **strings** nos sirven para mostrar mensajes al usuario. 👤

```python
print("Hola Mundo!")
print("Concatenar" + "Palabras" + "Se" + "Puede")
print("También", "Podemos", "Separar", "Cada", "Palabra", "Por", "Comas")
```

**Output**
```
Hola Mundo!
ConcatenarPalabrasSePuede
También Podemos Separar Cada Palabra Por Comas
```

* Podemos usar **comillas simples** `" "` o **comillas dobles** `' '`.
* `Concatenar` significa poder 'unir' palabras con el símbolo `+`.
* `Separar con comas` se refiere a especificar una serie de **argumentos** (Los veremos más adelante)

### **Trucos con strings** 🏆

1. Podemos separar cada palabra con un símbolo a nuestro gusto.
   + Esto únicamente funcionará cuando `separemos por comas` el mensaje.

```python
print("📅 La fecha de hoy es:")
print("03", "02", "2023", sep="/")
```
**Output**
```
📅 La fecha de hoy es:
03/02/2023
```
---

¡Todo esto es maravilloso!, pero... Cada vez que usemos un `print` el mensaje termina con un `salto de línea`. Veamos como mostrar el mensaje anterior en una sola linea. 🔗

* Un salto de línea se indica con `\n`.
```python
print("😀", "😊", "😚", sep="\n")
```
**Output**
```
😀
😊
😚
```

---
2. Finalizar un mensaje con algo a nuestro gusto.
```python
print("La fecha de hoy es:", end=" ")
print("03", "02", "2023", sep="/")
```
**Output**
```
La fecha de hoy es: 03/02/2023
```

* En este caso con el argumento `end` indicamos como queremos que finalize la línea.
---

<div align="center">
    <h2 style="font-weight: bold">EJERCICIOS 📃</h2>
</div>


```
Mostrar con 1 línea de código lo siguiente:
    *    
   ***   
  *****  
 ******* 
*********
```