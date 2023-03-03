---
title: Figure.AddShapes
second_title: Aspose.PSD per riferimento API .NET
description: Figure metodo. Aggiunge una gamma di forme alla figura.
type: docs
weight: 70
url: /it/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

Aggiunge una gamma di forme alla figura.

```csharp
public void AddShapes(Shape[] shapes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | Shape[] | Le forme da aggiungere. |

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

* class [Shape](../../shape/)
* class [Figure](../)
* spazio dei nomi [Aspose.PSD](../../figure/)
* assemblea [Aspose.PSD](../../../)


