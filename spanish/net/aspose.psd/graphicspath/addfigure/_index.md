---
title: GraphicsPath.AddFigure
second_title: Referencia de API de Aspose.PSD para .NET
description: GraphicsPath método. Agrega una nueva figura.
type: docs
weight: 50
url: /es/net/aspose.psd/graphicspath/addfigure/
---
## GraphicsPath.AddFigure method

Agrega una nueva figura.

```csharp
public void AddFigure(Figure figure)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| figure | Figure | La figura a agregar. |

### Ejemplos

Estos ejemplos hacen uso de las clases GraphicsPath y Graphics para crear y manipular figuras en una superficie de imagen. El ejemplo crea una nueva imagen y dibuja rutas con la ayuda de la clase GraphicsPath. Al final, se llama al método DrawPath expuesto por la clase Graphics para representar las rutas en la superficie. Finalmente, la imagen se exporta a formato de archivo Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Agregar formas al objeto Figura
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Agregar objeto Figura a GraphicsPath
    graphicspath.AddFigure(figure);

    //Dibujar ruta con objeto Pluma de color Negro
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Crear una instancia de TiffOptions y establecer sus diversas propiedades
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // guarda todos los cambios.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ver también

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* espacio de nombres [Aspose.PSD](../../graphicspath/)
* asamblea [Aspose.PSD](../../../)


