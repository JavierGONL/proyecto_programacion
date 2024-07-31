<div align='center'>
<figure> <img src="https://res.cloudinary.com/dm0p2ljin/image/upload/v1714416338/error-418_dtb3ak.png" alt="" width="300" height="auto"/></br>
<figcaption><b></b></figcaption></figure>
</div>

# proyecto_programacion

"""
descriccion aqui
"""


# diagramas y funcionamientos de las funciones
- funcionamiento de las puertas logicas en el proyecto
## puertas logicas

### puerta YES
<details><summary>explicacion</summary>
  - tabla de verdad:
  <table>
     <tr>
    <td> entrada </td> <td> salida </td> 
  </tr>
  <tr>
    <td> 0 </td> <td> 0 </td> 
  </tr>
  <tr>
    <td> 1 </td> <td> 1 </td> 
  </table>
<br>
- Explicación: La puerta lógica YES considera una única entrada y una única salida, la salida tiene siempre el mismo valor que la entrada. Se puede recrear con un transistor.
</details>

### puerta NOT
<details><summary>explicacion</summary>
  - tabla de verdad:
  <table>
     <tr>
    <td> entrada </td> <td> salida </td> 
  </tr>
  <tr>
    <td> 0 </td> <td> 1 </td> 
  </tr>
  <tr>
    <td> 1 </td> <td> 0 </td> 
</table>
<br>
- Explicación: La puerta lógica NOT considera una única entrada y una única salida, la salida tiene siempre el valor inverso al de la entrada. Esta puerta se utiliza para crear puertas como la NAND o la NOR entre otras, al colocarse en la salida de la puerta que se desea invertir. Se puede recrear con un transistor cuya salida conecta a tierra.
</details>

### puerta AND
<details><summary>explicacion</summary>
  - tabla de verdad:
  <table>
     <tr>
    <td> a </td> <td> b </td> <td> salida </td>
  </tr>
  <tr>
    <td> 0 </td> <td> 0 </td> <td> 0 </td>
  </tr>
  <tr>
    <td> 0 </td> <td> 1 </td> <td> 0 </td>
  </tr>
     <tr>
    <td> 1 </td> <td> 0 </td> <td> 0 </td>
  </tr>
     <tr>
    <td> 1 </td> <td> 1 </td> <td> 1 </td>
  </tr>
</table>
<br>
  - Explicacion: La puerta AND considera 2 entradas y una única salida en función de las entradas, encendiendose unicamente si ambas entradas están encendidas; en los otros casos la puerta se mantiene apagada. Se puede recrear con 2 transistores conectados en serie.
</details>

### puerta OR

<details><summary>explicacion</summary>
  - tabla de verdad:
  <table>
     <tr>
    <td> a </td> <td> b </td> <td> salida </td>
  </tr>
  <tr>
    <td> 0 </td> <td> 0 </td> <td> 0 </td>
  </tr>
  <tr>
    <td> 0 </td> <td> 1 </td> <td> 1 </td>
  </tr>
     <tr>
    <td> 1 </td> <td> 0 </td> <td> 1 </td>
  </tr>
     <tr>
    <td> 1 </td> <td> 1 </td> <td> 1 </td>
  </tr>
</table>
<br>
- Explicación: La puerta OR considera 2 entradas y una única salida en función de las entradas, tal que si alguna de las dos entradas está encendida, la salida lógica también está encendida; el único caso en dónde la salida se encuentra apagada es si ambas entradas se encunetran apagadas. Se puede recrear con 2 transistores conectados en paralelo.
</details>

### puerta XOR

<details><summary>explicacion</summary>
  - tabla de verdad:
  <table>
     <tr>
    <td> a </td> <td> b </td> <td> salida </td>
  </tr>
  <tr>
    <td> 0 </td> <td> 0 </td> <td> 0 </td>
  </tr>
  <tr>
    <td> 0 </td> <td> 1 </td> <td> 1 </td>
  </tr>
     <tr>
    <td> 1 </td> <td> 0 </td> <td> 1 </td>
  </tr>
     <tr>
    <td> 1 </td> <td> 1 </td> <td> 0 </td>
  </tr>
</table>
<br>
- Explicación: La puerta XOR considera 2 entradas y una única salida en función de las entradas, tal que si alguna de las dos entradas está encendida, la salida lógica también está encendida; su comportamiento es muy parecido al de la puerta OR, solo que a diferencia de esta, se apaga si ambas entradas se encuentran encendidas. Se puede recrear haciendo un cirucito híbrido entre la puerta AND y la OR(conectando ambos transistores tanto en serie como en paralelo), el circuito OR mantiene sus salidas originales, mientras que el circuito AND tiene la salida conectada a tierra.
</details>
