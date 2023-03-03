---
title: Class Pen
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Pen clase. Define un objeto utilizado para dibujar líneas curvas y figuras.
type: docs
weight: 5200
url: /es/net/aspose.psd/pen/
---
## Pen class

Define un objeto utilizado para dibujar líneas, curvas y figuras.

```csharp
public class Pen : TransparencySupporter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Inicializa una nueva instancia del`Pen` clase con el especificado[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Inicializa una nueva instancia del`Pen` clase con el color especificado. |
| [Pen](pen/#constructor_1)(Brush, float) | Inicializa una nueva instancia del`Pen` clase con el especificado[`Brush`](./brush/) y[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Inicializa una nueva instancia del`Pen` clase con el especificado[`Color`](./color/) y[`Width`](./width/) propiedades. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Obtiene o establece la alineación para este`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Obtiene o establece el[`Brush`](./brush/) que determina los atributos de este`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Obtiene o establece el color de este`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Obtiene o establece una matriz de valores que especifica una pluma compuesta. Un bolígrafo compuesto dibuja una línea compuesta formada por líneas paralelas y espacios. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Obtiene o establece un límite personalizado para usar al final de las líneas dibujadas con este`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Obtiene o establece un límite personalizado para usar al comienzo de las líneas dibujadas con este`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Obtiene o establece el estilo de mayúscula utilizado al final de los guiones que forman las líneas discontinuas dibujadas con este`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Obtiene o establece la distancia desde el inicio de una línea hasta el inicio de un patrón de guiones. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Obtiene o establece una matriz de guiones y espacios personalizados. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Obtiene o establece el estilo utilizado para las líneas discontinuas dibujadas con este`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Obtiene o establece el estilo de mayúscula utilizado al final de las líneas dibujadas con este`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Obtiene o establece el límite del grosor de la unión en una esquina a inglete. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Obtiene o establece la opacidad del objeto. El valor debe estar entre 0 y 1. El valor de 0 significa que el objeto es completamente visible, el valor de 1 significa que el objeto es completamente opaco. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Obtiene el estilo de las líneas dibujadas con este`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Obtiene o establece el estilo de mayúscula utilizado al comienzo de las líneas dibujadas con este`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Obtiene o establece una copia de la transformación geométrica para este`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Obtiene o establece el ancho de este`Pen` , en unidades del objeto Graphics utilizado para dibujar. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multiplica la matriz de transformación para este`Pen` por el especificado[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplica la matriz de transformación para este`Pen` por el especificado[`Matrix`](../matrix/) en el orden especificado. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Restablece la matriz de transformación geométrica para este`Pen` a identidad. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Gira la transformación geométrica local en el ángulo especificado. Este método antepone la rotación a la transformación. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Gira la transformación geométrica local el ángulo especificado en el orden especificado. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Escala la transformación geométrica local según los factores especificados. Este método antepone la matriz de escala a la transformación. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Escala la transformación geométrica local según los factores especificados en el orden especificado. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Establece los valores que determinan el estilo de cap usado para terminar las líneas dibujadas por este`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a la transformación. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Ejemplos

Este ejemplo muestra la creación y el uso de objetos Pen. El ejemplo crea una nueva imagen y dibuja rectángulos en la superficie de la imagen.

```csharp
[C#]

//Crear una instancia de Imagen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea una instancia de Graphics e inicialízala con el objeto Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Limpiar la superficie de gráficos con color blanco
    graphics.Clear(Aspose.PSD.Color.White);

    //Crear una instancia de Pen con color Rojo y ancho 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Crear una instancia de HatchBrush y establecer sus propiedades
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Crear una instancia de Pen
    //inicializarlo con objeto HatchBrush y ancho
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Crear opciones de exportación e inicializarlas.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // guarda todos los cambios.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Ver también

* class [TransparencySupporter](../transparencysupporter/)
* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


