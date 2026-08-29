---
title: "Clase ArcShape"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Shapes.ArcShape. Representa una forma de arco"
type: docs
weight: 5960
url: /es/net/aspose.psd.shapes/arcshape/
---
{{< psd/tize >}}
## ArcShape class

Representa una forma de arco.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | Inicializa una nueva instancia de la clase `ArcShape`. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | Inicializa una nueva instancia de la clase `ArcShape`. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | Inicializa una nueva instancia de la clase `ArcShape`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Obtiene los límites del objeto. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Obtiene el centro de la forma. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | Obtiene el punto final de la forma. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Obtiene un valor que indica si la forma tiene segmentos. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | Obtiene o establece un valor que indica si la forma ordenada está cerrada. Al procesar una forma ordenada cerrada, los puntos de inicio y fin no tienen significado. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Obtiene el punto inferior izquierdo del rectángulo. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Obtiene el punto superior izquierdo del rectángulo. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Obtiene la altura del rectángulo. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Obtiene el ancho del rectángulo. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Obtiene el punto inferior derecho del rectángulo. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Obtiene el punto superior derecho del rectángulo. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | Obtiene los segmentos de la forma. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Obtiene o establece el ángulo de inicio. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | Obtiene el punto inicial de la forma. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Obtiene o establece el ángulo de barrido. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | Obtiene los límites del objeto. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | Obtiene los límites del objeto. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | Invierte el orden de los puntos de esta forma. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Aplica la transformación especificada a la forma. |

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

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


