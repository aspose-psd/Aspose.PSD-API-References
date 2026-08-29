---
title: "GraphicsPath.AddFigures"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método GraphicsPath. Añade nuevas figuras"
type: docs
weight: 60
url: /es/net/aspose.psd/graphicspath/addfigures/
---
{{< psd/tize >}}
## GraphicsPath.AddFigures method

Agrega nuevas figuras.

```csharp
public void AddFigures(Figure[] figures)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figuras | Figure[] | Las figuras a añadir. |

## Ejemplos

Este ejemplo crea una nueva Image y dibuja una variedad de formas usando Figures y GraphicsPath en la superficie de la Image

```csharp
[C#]

//Cree una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie Graphics
    graphics.Clear(Color.Wheat);

    //Crea una instancia de la clase GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crea una instancia de la clase Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Agregar Shape al objeto Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Crea una instancia de la clase Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Agregar Shape al objeto Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Agrega el objeto Figure a GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Dibuja la ruta con el objeto Pen de color negro
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Crea opciones de exportación e inicialízalas.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Guarda todos los cambios.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Ver también

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


