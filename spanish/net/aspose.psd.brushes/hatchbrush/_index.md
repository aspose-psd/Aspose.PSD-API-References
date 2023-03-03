---
title: Class HatchBrush
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Brushes.HatchBrush clase. Define un pincel rectangular con un estilo de sombreado un color de primer plano y un color de fondo. Esta clase no se puede heredar.
type: docs
weight: 130
url: /es/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Define un pincel rectangular con un estilo de sombreado, un color de primer plano y un color de fondo. Esta clase no se puede heredar.

```csharp
public sealed class HatchBrush : Brush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Obtiene o establece el color de los espacios entre las líneas de sombreado. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Obtiene o establece el color de las líneas de sombreado. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Obtiene o establece el estilo de sombreado de este pincel. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor de 0 significa que el pincel es completamente visible, el valor de 1 significa que el pincel es completamente opaco. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea un nuevo clon profundo del actual[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |

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

* class [Brush](../../aspose.psd/brush/)
* espacio de nombres [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* asamblea [Aspose.PSD](../../)


