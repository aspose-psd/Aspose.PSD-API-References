---
title: Class StreamSource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Sources.StreamSource classe. Rappresenta unorigine del flusso.
type: docs
weight: 5620
url: /it/net/aspose.psd.sources/streamsource/
---
## StreamSource class

Rappresenta un'origine del flusso.

```csharp
public sealed class StreamSource : Source
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Inizializza una nuova istanza di`StreamSource` classe. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Inizializza una nuova istanza di`StreamSource` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Ottiene un valore che indica se il flusso deve essere eliminato ogni volta che il contenitore viene eliminato. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Ottiene il flusso. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Ottiene il contenitore del flusso. |

### Esempi

Questo esempio usa la classe Graphics per creare forme primitive sulla superficie Image. Per dimostrare l'operazione, l'esempio crea una nuova immagine in formato PSD e disegna forme primitive sulla superficie dell'immagine usando i metodi Draw esposti dalla classe Graphics, quindi esportala nel formato di file PSD.

```csharp
[C#]

//Crea un'istanza di Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inizializza un'istanza della classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Superficie grafica chiara
    graphics.Clear(Color.Wheat);

    // Disegna un arco specificando l'oggetto Pen di colore nero, 
    //a Rettangolo che circonda l'arco, l'angolo iniziale e l'angolo di apertura
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // Disegna un Bezier specificando l'oggetto Pen con colore blu e punti coordinati.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // Disegna una curva specificando l'oggetto Pen di colore verde e un array di punti
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // Disegna un'ellisse usando l'oggetto Pen e un rettangolo circostante
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Disegna una linea 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // Disegna un segmento di torta
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Disegna un poligono specificando l'oggetto Pen di colore rosso e un array di punti
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Disegna un rettangolo
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Crea un oggetto SolidBrush e imposta le sue varie proprietà
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // Disegna una stringa usando l'oggetto e il carattere SolidBrush, in un punto specifico
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Crea un'istanza di PngOptions e imposta le sue varie proprietà
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // salva tutte le modifiche.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Guarda anche

* class [Source](../../aspose.psd/source/)
* spazio dei nomi [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assemblea [Aspose.PSD](../../)


