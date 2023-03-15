---
title: Class ArcShape
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Shapes.ArcShape clase. Representa una forma de arco.
type: docs
weight: 5460
url: /es/net/aspose.psd.shapes/arcshape/
---
## ArcShape class

Representa una forma de arco.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | Inicializa una nueva instancia del`ArcShape` clase. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | Inicializa una nueva instancia del`ArcShape` clase. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | Inicializa una nueva instancia del`ArcShape` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Obtiene los límites del objeto. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Obtiene el centro de la forma. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | Obtiene el punto de forma final. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Obtiene un valor que indica si la forma tiene segmentos. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | Obtiene o establece un valor que indica si la forma ordenada está cerrada. Cuando se procesa una forma ordenada cerrada, los puntos inicial y final no tienen significado. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Obtiene el punto del rectángulo inferior izquierdo. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Obtiene el punto del rectángulo superior izquierdo. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Obtiene la altura del rectángulo. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Obtiene el ancho del rectángulo. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Obtiene el punto del rectángulo inferior derecho. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Obtiene el punto superior derecho del rectángulo. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | Obtiene los segmentos de forma. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Obtiene o establece el ángulo de inicio. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | Obtiene el punto de forma inicial. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Obtiene o establece el ángulo de barrido. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | Obtiene los límites del objeto. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | Obtiene los límites del objeto. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | Invierte el orden de los puntos de esta forma. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Aplica la transformación especificada a la forma. |

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

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* espacio de nombres [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* asamblea [Aspose.PSD](../../)


