---
title: Class Pen
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Pen classe. Definisce un oggetto utilizzato per disegnare linee curve e figure.
type: docs
weight: 5200
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
| [Pen](pen/#constructor)(Brush) | Inizializza una nuova istanza di`Pen` classe con l'oggetto specificato[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Inizializza una nuova istanza di`Pen` classe con il colore specificato. |
| [Pen](pen/#constructor_1)(Brush, float) | Inizializza una nuova istanza di`Pen` classe con l'oggetto specificato[`Brush`](./brush/) E[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Inizializza una nuova istanza di`Pen` classe con l'oggetto specificato[`Color`](./color/) E[`Width`](./width/) proprietà. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Ottiene o imposta l'allineamento per this`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Ottiene o imposta il[`Brush`](./brush/) che ne determina gli attributi`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Ottiene o imposta il colore di this`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Ottiene o imposta una matrice di valori che specifica una penna composta. Una penna composta disegna una linea composta composta da linee parallele e spazi. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Ottiene o imposta un limite personalizzato da utilizzare alla fine delle righe disegnate con this`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Ottiene o imposta un limite personalizzato da utilizzare all'inizio delle righe disegnate con this`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Ottiene o imposta la distanza dall'inizio di una linea all'inizio di un modello di trattino. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Ottiene o imposta un array di trattini e spazi personalizzati. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Ottiene o imposta lo stile utilizzato per le linee tratteggiate disegnate con this`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato alla fine delle linee disegnate con this`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Ottiene o imposta lo stile di unione per le estremità di due linee consecutive disegnate con this`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Ottiene o imposta il limite dello spessore del giunto su un angolo squadrato. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Ottiene o imposta l'opacità dell'oggetto. Il valore deve essere compreso tra 0 e 1. Il valore 0 significa che l'oggetto è completamente visibile, il valore 1 significa che l'oggetto è completamente opaco. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Ottiene lo stile delle linee disegnate con this`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato all'inizio delle linee disegnate con this`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Ottiene o imposta una copia della trasformazione geometrica per this`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Ottiene o imposta la larghezza di this`Pen` , in unità dell'oggetto Graphics utilizzato per il disegno. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Moltiplica la matrice di trasformazione per questo`Pen` da quanto specificato[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Moltiplica la matrice di trasformazione per questo`Pen` da quanto specificato[`Matrix`](../matrix/) nell'ordine specificato. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Reimposta la matrice di trasformazione geometrica per questo`Pen` all'identità. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Ridimensiona la trasformazione geometrica locale in base ai fattori specificati. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale in base ai fattori specificati nell'ordine specificato. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Imposta i valori che determinano lo stile del capo utilizzato per terminare le linee disegnate da questo`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |

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

* class [TransparencySupporter](../transparencysupporter/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


