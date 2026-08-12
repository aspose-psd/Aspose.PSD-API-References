---
title: "Clase SolidBrush"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Brushes.SolidBrush. Solid brush está destinado a dibujar continuamente con un color específico. Esta clase no puede ser heredada"
type: docs
weight: 200
url: /es/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

El pincel sólido está destinado a dibujar continuamente con un color específico. Esta clase no puede heredarse.

```csharp
public sealed class SolidBrush : Brush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Inicializa una nueva instancia de la clase `SolidBrush`. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Inicializa una nueva instancia de la clase `SolidBrush`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Obtiene o establece el color del brush. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea una nueva clonación profunda del [`Brush`](../../aspose.psd/brush/) actual. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |

## Ejemplos

Este ejemplo usa la clase Graphics para crear formas primitivas en la superficie de la Imagen. Para demostrar la operación, el ejemplo crea una nueva Imagen en formato PSD y dibuja formas primitivas en la superficie de la Imagen usando los métodos Draw expuestos por la clase Graphics, luego la exporta al formato de archivo PSD.

```csharp
[C#]

//Crea una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie Graphics
    graphics.Clear(Color.Wheat);

    //Dibuje un arco especificando el objeto Pen con color negro, 
    //un Rectángulo que rodea el arco, ángulo de inicio y ángulo de barrido
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Dibuje una curva Bézier especificando el objeto Pen con color azul y los puntos coordenados.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Dibuje una curva especificando el objeto Pen con color verde y una matriz de puntos
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Dibuje una elipse usando el objeto Pen y un rectángulo circundante
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dibuje una línea 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Dibuje un segmento de pastel
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Dibuje un polígono especificando el objeto Pen con color rojo y una matriz de puntos
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dibuje un rectángulo
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Cree un objeto SolidBrush y establezca sus diversas propiedades
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Dibuje una cadena usando el objeto SolidBrush y la Fuente, en un punto específico
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Cree una instancia de PngOptions y establezca sus diversas propiedades
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Guarda todos los cambios.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ver también

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


