---
title: Class HatchBrush
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Brushes.HatchBrush classe. Definisce un pennello rettangolare con uno stile di tratteggio un colore di primo piano e un colore di sfondo. Questa classe non può essere ereditata.
type: docs
weight: 130
url: /it/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Definisce un pennello rettangolare con uno stile di tratteggio, un colore di primo piano e un colore di sfondo. Questa classe non può essere ereditata.

```csharp
public sealed class HatchBrush : Brush
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Ottiene o imposta il colore degli spazi tra le linee tratteggiate. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Ottiene o imposta il colore delle linee tratteggiate. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Ottiene o imposta lo stile di tratteggio di questo pennello. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore dovrebbe essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea un nuovo clone profondo della corrente[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |

### Esempi

Questo esempio mostra la creazione e l'utilizzo degli oggetti Pen. L'esempio crea una nuova immagine e disegna rettangoli sulla superficie dell'immagine.

```csharp
[C#]

//Crea un'istanza di Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea un'istanza di Graphics e inizializzala con l'oggetto Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Cancella la superficie grafica con il colore bianco
    graphics.Clear(Aspose.PSD.Color.White);

    //Crea un'istanza di Pen con colore Red e larghezza 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Crea un'istanza di HatchBrush e impostane le proprietà
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Crea un'istanza di Pen
    // inizializzalo con l'oggetto HatchBrush e la larghezza
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Disegna rettangoli specificando l'oggetto Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Disegna rettangoli specificando l'oggetto Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Crea le opzioni di esportazione e le inizializza.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // salva tutte le modifiche.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Guarda anche

* class [Brush](../../aspose.psd/brush/)
* spazio dei nomi [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assemblea [Aspose.PSD](../../)


