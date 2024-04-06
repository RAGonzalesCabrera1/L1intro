# L1intro

## Colaboradores

Aquí puedes listar los colaboradores de tu proyecto.

## Lenguaje de programación

- Python

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
