---
title: Class Figure
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Figure classe. La figura. Un contenitore per le forme.
type: docs
weight: 1200
url: /it/net/aspose.psd/figure/
---
## Figure class

La figura. Un contenitore per le forme.

```csharp
public class Figure : ObjectWithBounds
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Figure](figure/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Ottiene o imposta i limiti dell'oggetto. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Ottiene o imposta un valore che indica se questa figura è chiusa. Una figura chiusa farà la differenza solo nel caso in cui la prima e l'ultima forma della figura siano forme continue. In tal caso il primo punto della prima forma sarà collegato da una linea retta dall'ultimo punto dell'ultima forma. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Ottiene i segmenti della figura intera. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Ottiene le forme della figura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Aggiunge una forma alla figura. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Aggiunge una gamma di forme alla figura. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Rimuove una forma dalla figura. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Rimuove una serie di forme dalla figura. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Inverte l'ordine delle forme di questa figura e l'ordine dei punti delle forme. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Applica la trasformazione specificata alla forma. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


