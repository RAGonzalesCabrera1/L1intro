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

\documentclass{article}
\usepackage{amsmath}

\begin{document}

La fórmula para calcular la resistencia es:

\[
\boxed{
R = \frac{1}{{2\pi f_c C}}
}
\]

\end{document}
\includegraphics[width=0.5\textwidth]{[URL_de_la_imagen](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiptwpx7_5woUnxivArKeDcXqzP2LJPUFsv3gFLi9uJ2zfYtwfOOCLLA4l8tbcZzKX9dg2tI1yvHYQQhmJVCpyKOpV33l41s9L7CzN0vVYzhda9O8BtmFBRTxzqFIEHww6v1CZ0xruk0Kyv/s1600/descarga.png)}
