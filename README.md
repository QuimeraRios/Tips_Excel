# Tips_Excel
Usos prácticos de Excel

1. Excel posee muchas teclas rápidas sin embargo una combinación útil es aquella que nos permite pasar la información de estilo tabla horizontal a tabla vertical.

Es decir, se tiene una información horizontal que necesitamos organizar en formato vertical para poder aplicar las funciones de Excel. El proceso seria: 
1. Seleccionamos el rango de datos
2. le damos Control+C
3. Nos ubicamos donde queremos pegar la información y luego realizamos la 
4. combinación de teclas: Alt + E+ S + T  ( lo que nos lleva a la ventana de pegado especial transponer)
5. le damos enter

2. Adecuar siempre el tamaño de las columnas según el contenido, aveces puede ser dispendioso, para ello, recomendaria colocar o manejar una plantilla base.
   Una plantilla que posea el ajuste automatico de columnas: en el codigo vamos a escribir en la selección de Worksheet, colocamos: (esto ajusta automaticamente todas las columnas).
   
   Private Sub Worksheet_Activate()
    Cells.EntireColumn.AutoFill
   End Sub
