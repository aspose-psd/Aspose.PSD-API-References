---
title: "GraphicsPath.AddFigure"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método GraphicsPath. Añade una nueva figura"
type: docs
weight: 50
url: /es/net/aspose.psd/graphicspath/addfigure/
---
{{< psd/tize >}}
## GraphicsPath.AddFigure method

Agrega una nueva figura.

```csharp
public void AddFigure(Figure figure)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figura | Figura | La figura a añadir. |

## Ejemplos

Este ejemplo utiliza las clases GraphicsPath y Graphics para crear y manipular Figuras en una superficie de Imagen. El ejemplo crea una nueva Imagen y dibuja rutas con la ayuda de la clase GraphicsPath. Al final se llama al método DrawPath expuesto por la clase Graphics para renderizar las rutas en la superficie. Finalmente, la imagen se exporta al formato de archivo Tiff.

```csharp
[C#]

//Crea una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie Graphics
    graphics.Clear(Color.Wheat);

    //Crea una instancia de la clase GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crea una instancia de la clase Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Agrega formas al objeto Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Agrega el objeto Figure a GraphicsPath
    graphicspath.AddFigure(figure);

    //Dibuja la ruta con el objeto Pen de color negro
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Crea una instancia de TiffOptions y establece sus diversas propiedades
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Guarda todos los cambios.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ver también

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


