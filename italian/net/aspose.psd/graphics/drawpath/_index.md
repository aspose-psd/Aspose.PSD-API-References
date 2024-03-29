---
title: Graphics.DrawPath
second_title: Aspose.PSD per riferimento API .NET
description: Graphics metodo. Disegna aGraphicsPath .
type: docs
weight: 270
url: /it/net/aspose.psd/graphics/drawpath/
---
## Graphics.DrawPath method

Disegna a[`GraphicsPath`](../../graphicspath/) .

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) che determina il colore, la larghezza e lo stile del tracciato. |
| path | GraphicsPath | [`GraphicsPath`](../../graphicspath/) disegnare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -oppure- *path* è zero. |

### Esempi

Questi esempi utilizzano la classe GraphicsPath e Graphics per creare e manipolare figure su una superficie immagine. L'esempio crea una nuova immagine e disegna percorsi con l'aiuto della classe GraphicsPath. Alla fine viene chiamato il metodo DrawPath esposto dalla classe Graphics per rendere i percorsi sulla superficie. Infine l'immagine viene esportata nel formato di file Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Aggiungi forme all'oggetto Figura
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Aggiungi l'oggetto Figura a GraphicsPath
    graphicspath.AddFigure(figure);

    //Disegna il percorso con l'oggetto Penna di colore Nero
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Crea un'istanza di TiffOptions e imposta le sue varie proprietà
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // salva tutte le modifiche.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Guarda anche

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)


