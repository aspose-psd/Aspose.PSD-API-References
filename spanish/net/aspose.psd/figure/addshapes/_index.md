---
title: Figure.AddShapes
second_title: Referencia de API de Aspose.PSD para .NET
description: Figure método. Agrega un rango de formas a la figura.
type: docs
weight: 70
url: /es/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

Agrega un rango de formas a la figura.

```csharp
public void AddShapes(Shape[] shapes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| shapes | Shape[] | Las formas para agregar. |

### Ejemplos

Este ejemplo crea una nueva imagen y dibuja una variedad de formas usando Figuras y GraphicsPath en la superficie de la imagen.

```csharp
[C#]

//Crear una instancia de Imagen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crear e inicializar una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Borrar superficie gráfica
    graphics.Clear(Color.Wheat);

    //Crear una instancia de la clase GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crear una instancia de la clase Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    // Agregar forma al objeto de figura
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Crear una instancia de la clase Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    // Agregar forma al objeto de figura
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Agregar objeto Figura a GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Dibujar ruta con objeto Pluma de color Negro
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Crear opciones de exportación e inicializarlas.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // guarda todos los cambios.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Ver también

* class [Shape](../../shape/)
* class [Figure](../)
* espacio de nombres [Aspose.PSD](../../figure/)
* asamblea [Aspose.PSD](../../../)


