---
title: Pen
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce un oggetto utilizzato per disegnare linee curve e figure.
type: docs
weight: 5130
url: /it/net/aspose.psd/pen/
---
## Pen class

Definisce un oggetto utilizzato per disegnare linee, curve e figure.

```csharp
public class Pen : TransparencySupporter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il specificato[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il colore specificato. |
| [Pen](pen#constructor_1)(Brush, float) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il specificato[`Brush`](./brush) e[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il specificato[`Color`](./color) e[`Width`](./width) proprietà. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment) { get; set; } | Ottiene o imposta l'allineamento per questo[`Pen`](../pen) . |
| [Brush](../../aspose.psd/pen/brush) { get; set; } | Ottiene o imposta il[`Brush`](./brush) che determina gli attributi di questo[`Pen`](../pen) . |
| [Color](../../aspose.psd/pen/color) { get; set; } | Ottiene o imposta il colore di questo[`Pen`](../pen) . |
| [CompoundArray](../../aspose.psd/pen/compoundarray) { get; set; } | Ottiene o imposta una matrice di valori che specifica una penna composta. Una penna composta disegna una linea composta composta da linee e spazi paralleli. |
| [CustomEndCap](../../aspose.psd/pen/customendcap) { get; set; } | Ottiene o imposta un limite personalizzato da utilizzare alla fine delle linee tracciate con questo[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap) { get; set; } | Ottiene o imposta un limite personalizzato da utilizzare all'inizio delle linee disegnate con questo[`Pen`](../pen) . |
| [DashCap](../../aspose.psd/pen/dashcap) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo[`Pen`](../pen) . |
| [DashOffset](../../aspose.psd/pen/dashoffset) { get; set; } | Ottiene o imposta la distanza dall'inizio di una linea all'inizio di una sequenza di trattini. |
| [DashPattern](../../aspose.psd/pen/dashpattern) { get; set; } | Ottiene o imposta una matrice di trattini e spazi personalizzati. |
| [DashStyle](../../aspose.psd/pen/dashstyle) { get; set; } | Ottiene o imposta lo stile utilizzato per le linee tratteggiate disegnate con questo[`Pen`](../pen) . |
| [EndCap](../../aspose.psd/pen/endcap) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato alla fine delle righe disegnate con questo[`Pen`](../pen) . |
| [LineJoin](../../aspose.psd/pen/linejoin) { get; set; } | Ottiene o imposta lo stile di unione per le estremità di due linee consecutive disegnate con questo[`Pen`](../pen) . |
| [MiterLimit](../../aspose.psd/pen/miterlimit) { get; set; } | Ottiene o imposta il limite dello spessore del giunto su un angolo smussato. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity) { get; set; } | Ottiene o imposta l'opacità dell'oggetto. Il valore deve essere compreso tra 0 e 1. Il valore 0 significa che l'oggetto è completamente visibile, il valore 1 significa che l'oggetto è completamente opaco. |
| [PenType](../../aspose.psd/pen/pentype) { get; } | Ottiene lo stile delle linee disegnate con questo[`Pen`](../pen) . |
| [StartCap](../../aspose.psd/pen/startcap) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato all'inizio delle linee disegnate con questo[`Pen`](../pen) . |
| [Transform](../../aspose.psd/pen/transform) { get; set; } | Ottiene o imposta una copia della trasformazione geometrica per questo[`Pen`](../pen) . |
| [Width](../../aspose.psd/pen/width) { get; set; } | Ottiene o imposta la larghezza di questo[`Pen`](../pen) , in unità dell'oggetto Graphics utilizzato per il disegno. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform#multiplytransform)(Matrix) | Moltiplica la matrice di trasformazione per questo[`Pen`](../pen) dal specificato[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Moltiplica la matrice di trasformazione per questo[`Pen`](../pen) dal specificato[`Matrix`](../matrix) nell'ordine specificato. |
| [ResetTransform](../../aspose.psd/pen/resettransform)() | Reimposta la matrice di trasformazione geometrica per questo[`Pen`](../pen) all'identità. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform#rotatetransform)(float) | Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform#scaletransform)(float, float) | Ridimensiona la trasformazione geometrica locale in base ai fattori specificati. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale in base ai fattori specificati nell'ordine specificato. |
| [SetLineCap](../../aspose.psd/pen/setlinecap)(LineCap, LineCap, DashCap) | Imposta i valori che determinano lo stile del cappuccio utilizzato per terminare le linee tracciate da questo[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform#translatetransform)(float, float) | Converte la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Converte la trasformazione geometrica locale in base alle dimensioni specificate nell'ordine specificato. |

### Esempi

Questo esempio mostra la creazione e l'utilizzo di oggetti Pen. L'esempio crea una nuova immagine e disegna rettangoli sulla superficie dell'immagine.

```csharp
[C#]

//Crea un'istanza di Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea un'istanza di Graphics e inizializzala con l'oggetto Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Cancella la superficie grafica con il colore bianco
    graphics.Clear(Aspose.PSD.Color.White);

    //Crea un'istanza di Pen con colore rosso e larghezza 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Crea un'istanza di HatchBrush e imposta le sue proprietà
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Crea un'istanza di Pen
    //inizializzalo con l'oggetto HatchBrush e la larghezza
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Disegna rettangoli specificando l'oggetto Penna
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Disegna rettangoli specificando l'oggetto Penna
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Crea opzioni di esportazione e inizializzale.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // salva tutte le modifiche.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Guarda anche

* class [TransparencySupporter](../transparencysupporter)
* spazio dei nomi [Aspose.PSD](../../aspose.psd)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
