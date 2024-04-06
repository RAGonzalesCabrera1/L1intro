# L1intro

## Colaboradores

Aquí puedes listar los colaboradores de tu proyecto.

## Lenguaje de programación

- Python

``` vb
Module Module1
    Sub Main()
        ' Definir valor de fc y C
        Dim fc As Double = 1000 ' Frecuencia de corte en Hz
        Dim C As Double = 0.00000047 ' Valor del capacitor en faradios (470uF)

        ' Calcular el valor de R utilizando la fórmula despejada
        Dim R As Double = 1 / (2 * Math.PI * fc * C)

        ' Imprimir el resultado
        Console.WriteLine("El valor de R es: " & R)
    End Sub
End Module
```

La fórmula para calcular la resistencia (\( R \)) en función de la frecuencia de corte (\( f_c \)) y la capacitancia (\( C \)) es:

\[
R = \frac{1}{{2\pi f_c C}}
\]

La fórmula para calcular la resistencia es:

<div align="center">
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;R=\frac{1}{{2\pi&space;f_c&space;C}}" title="\Large R=\frac{1}{{2\pi f_c C}}" />
</div>

La fórmula para calcular la resistencia es:

<div align="center">
    <img src="[URL_de_la_imagen](https://camo.githubusercontent.com/57f53b9884b1da74088541f764ad6abcd56864eaa291f7e343f89a76d87d48d6/68747470733a2f2f6c617465782e636f6465636f67732e636f6d2f7376672e6c617465783f5c4c617267652673706163653b523d5c667261637b317d7b7b325c70692673706163653b665f632673706163653b437d7d)" style="color:white;" />
</div>
