---
title: Class ArcShape
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Shapes.ArcShape classe. Rappresenta una forma ad arco.
type: docs
weight: 5460
url: /it/net/aspose.psd.shapes/arcshape/
---
## ArcShape class

Rappresenta una forma ad arco.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | Inizializza una nuova istanza di`ArcShape` classe. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | Inizializza una nuova istanza di`ArcShape` classe. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | Inizializza una nuova istanza di`ArcShape` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Ottiene i limiti dell'oggetto. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Ottiene il centro della forma. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | Ottiene il punto di forma finale. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Ottiene un valore che indica se la forma ha segmenti. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | Ottiene o imposta un valore che indica se la forma ordinata è chiusa. Quando si elabora una forma ordinata chiusa, i punti iniziale e finale non hanno significato. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Ottiene il punto del rettangolo in basso a sinistra. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Ottiene il punto del rettangolo in alto a sinistra. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Ottiene l'altezza del rettangolo. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Ottiene la larghezza del rettangolo. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Ottiene il punto del rettangolo in basso a destra. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Ottiene il punto del rettangolo in alto a destra. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | Ottiene i segmenti della forma. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Ottiene o imposta l'angolo iniziale. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | Ottiene il punto iniziale della forma. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Ottiene o imposta l'angolo di sweep. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | Inverte l'ordine dei punti per questa forma. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Applica la trasformazione specificata alla forma. |

### Esempi

Questo esempio crea una nuova Image e disegna una varietà di forme usando Figures e GraphicsPath sulla superficie Image

```csharp
[C#]

//Crea un'istanza di Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inizializza un'istanza della classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Superficie grafica chiara
    graphics.Clear(Color.Wheat);

    //Crea un'istanza della classe GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crea un'istanza della classe Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Aggiungi forma all'oggetto Figura
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Crea un'istanza della classe Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Aggiungi forma all'oggetto Figura
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Aggiungi l'oggetto Figura a GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Disegna il percorso con l'oggetto Penna di colore Nero
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Crea le opzioni di esportazione e le inizializza.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // salva tutte le modifiche.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Guarda anche

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* spazio dei nomi [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assemblea [Aspose.PSD](../../)


