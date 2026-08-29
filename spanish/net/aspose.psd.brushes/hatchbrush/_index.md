---
title: "Clase HatchBrush"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Brushes.HatchBrush. Define un brush rectangular con un estilo de trama, un color de primer plano y un color de fondo. Esta clase no se puede heredar"
type: docs
weight: 130
url: /es/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Define un pincel rectangular con un estilo de trama, un color de primer plano y un color de fondo. Esta clase no puede heredarse.

```csharp
public sealed class HatchBrush : Brush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HatchBrush](hatchbrush/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Obtiene o establece el color de los espacios entre las líneas de trama. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Obtiene o establece el color de las líneas de trama. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Obtiene o establece el estilo de trama de este brush. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea una nueva clonación profunda del [`Brush`](../../aspose.psd/brush/) actual. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |

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

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


