---
title: Class PolygonShape
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Shapes.PolygonShape classe. Rappresenta una forma poligonale.
type: docs
weight: 5510
url: /it/net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

Rappresenta una forma poligonale.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Inizializza una nuova istanza di`PolygonShape` classe. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Inizializza una nuova istanza di`PolygonShape` classe. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Inizializza una nuova istanza di`PolygonShape` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Ottiene i limiti dell'oggetto. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Ottiene il centro della forma. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Ottiene il punto di forma finale. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Ottiene un valore che indica se la forma ha segmenti. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Ottiene o imposta i punti della curva. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Ottiene i segmenti della forma. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Ottiene il punto iniziale della forma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Inverte l'ordine dei punti per questa forma. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Applica la trasformazione specificata alla forma. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* spazio dei nomi [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assemblea [Aspose.PSD](../../)


