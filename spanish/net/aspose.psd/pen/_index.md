---
title: "Clase Pen"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Pen. Define un objeto utilizado para dibujar líneas, curvas y figuras"
type: docs
weight: 5690
url: /es/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Define un objeto usado para dibujar líneas, curvas y figuras.

```csharp
public class Pen : TransparencySupporter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Inicializa una nueva instancia de la clase `Pen` con el [`Brush`](./brush/) especificado. |
| [Pen](pen/#constructor_2)(Color) | Inicializa una nueva instancia de la clase `Pen` con el color especificado. |
| [Pen](pen/#constructor_1)(Brush, float) | Inicializa una nueva instancia de la clase `Pen` con el [`Brush`](./brush/) y la [`Width`](./width/) especificados. |
| [Pen](pen/#constructor_3)(Color, float) | Inicializa una nueva instancia de la clase `Pen` con las propiedades [`Color`](./color/) y [`Width`](./width/) especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Obtiene o establece la alineación para este `Pen`. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Obtiene o establece el [`Brush`](./brush/) que determina los atributos de este `Pen`. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Obtiene o establece el color de este `Pen`. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Obtiene o establece una matriz de valores que especifica un pen compuesto. Un pen compuesto dibuja una línea compuesta de líneas paralelas y espacios. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Obtiene o establece una tapa personalizada para usar al final de las líneas dibujadas con este `Pen`. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Obtiene o establece una tapa personalizada para usar al comienzo de las líneas dibujadas con este `Pen`. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Obtiene o establece el estilo de tapa utilizado al final de los guiones que forman líneas discontinuas dibujadas con este `Pen`. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Obtiene o establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Obtiene o establece una matriz de guiones y espacios personalizados. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Obtiene o establece el estilo utilizado para líneas discontinuas dibujadas con este `Pen`. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Obtiene o establece el estilo de tapa utilizado al final de las líneas dibujadas con este `Pen`. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este `Pen`. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Obtiene o establece el límite del grosor de la unión en una esquina en inglete. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Obtiene o establece la opacidad del objeto. El valor debe estar entre 0 y 1. Un valor de 0 significa que el objeto es totalmente visible, un valor de 1 significa que el objeto es totalmente opaco. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Obtiene el estilo de las líneas dibujadas con este `Pen`. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Obtiene o establece el estilo de tapa utilizado al comienzo de las líneas dibujadas con este `Pen`. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Obtiene o establece una copia de la transformación geométrica para este `Pen`. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Obtiene o establece el ancho de este `Pen`, en unidades del objeto Graphics utilizado para dibujar. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multiplica la matriz de transformación de este `Pen` por la [`Matrix`](../matrix/) especificada. |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplica la matriz de transformación de este `Pen` por la [`Matrix`](../matrix/) especificada en el orden indicado. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Restablece la matriz de transformación geométrica de este `Pen` a la identidad. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rota la transformación geométrica local por el ángulo especificado en el orden indicado. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Escala la transformación geométrica local por los factores especificados en el orden indicado. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Establece los valores que determinan el estilo de tapa utilizado para terminar las líneas dibujadas por este `Pen`. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden indicado. |

## Ejemplos

Este ejemplo muestra la creación y uso de objetos Pen. El ejemplo crea una nueva Image y dibuja Rectangles en la superficie de Image.

```csharp
[C#]

//Cree una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea una instancia de Graphics y inicialízala con un objeto Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie de Graphics con el color White
    graphics.Clear(Aspose.PSD.Color.White);

    //Crea una instancia de Pen con el color Red y ancho 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Crea una instancia de HatchBrush y establece sus propiedades
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Crea una instancia de Pen
    //inicialízala con un objeto HatchBrush y ancho
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Dibuja Rectangles especificando el objeto Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Dibuja Rectangles especificando el objeto Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Crea opciones de exportación e inicialízalas.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Guarda todos los cambios.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Ver también

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


