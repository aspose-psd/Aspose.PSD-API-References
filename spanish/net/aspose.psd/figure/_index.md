---
title: Class Figure
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Figure clase. La figura. Un contenedor para formas.
type: docs
weight: 1200
url: /es/net/aspose.psd/figure/
---
## Figure class

La figura. Un contenedor para formas.

```csharp
public class Figure : ObjectWithBounds
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Figure](figure/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Obtiene o establece los límites del objeto. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Obtiene o establece un valor que indica si esta figura es cerrada. Una figura cerrada hará una diferencia solo en caso de que las formas de la primera y la última figura sean formas continuas. En tal caso, el primer punto de la primera forma estará conectado por una línea recta desde el último punto de la última forma. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Obtiene los segmentos completos de la figura. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Obtiene las formas de las figuras. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Añade una forma a la figura. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Agrega un rango de formas a la figura. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Obtiene los límites del objeto. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Obtiene los límites del objeto. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Elimina una forma de la figura. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Elimina un rango de formas de la figura. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Invierte el orden de las formas de esta figura y el orden de los puntos de las formas. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Aplica la transformación especificada a la forma. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


