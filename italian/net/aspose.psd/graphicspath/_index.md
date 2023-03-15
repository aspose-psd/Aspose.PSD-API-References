---
title: Class GraphicsPath
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.GraphicsPath classe. Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata.
type: docs
weight: 4320
url: /it/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Inizializza una nuova istanza di`GraphicsPath` classe. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Inizializza una nuova istanza di`GraphicsPath` classe. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Inizializza una nuova istanza di`GraphicsPath` classe. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Inizializza una nuova istanza di`GraphicsPath` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Ottiene o imposta i limiti dell'oggetto. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Ottiene le cifre del percorso. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Ottiene o imposta a[`FillMode`](../fillmode/) enumerazione che determina come gli interni delle forme in questo`GraphicsPath` sono pieni. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Aggiunge una nuova figura. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Aggiunge nuove figure. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Accoda l'oggetto specificato`GraphicsPath` a questo percorso. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Accoda l'oggetto specificato`GraphicsPath` a questo percorso. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Esegue un clone profondo di questo percorso grafico. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Applica la trasformazione specificata e quindi converte ciascuna curva in questa`GraphicsPath` in una sequenza di segmenti di linea collegati. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Converte ogni curva in questo`GraphicsPath` in una sequenza di segmenti di linea collegati. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) e utilizzando il specificato[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) e utilizzando il specificato[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) e utilizzando il specificato[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo`GraphicsPath` quando disegnato con il specificato[`Pen`](../pen/) e utilizzando il specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` nella regione di clip visibile del file specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Indica se il punto specificato è contenuto all'interno di questo`GraphicsPath` , utilizzando il file specificato[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Rimuove una figura. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Rimuove figure. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Svuota il percorso grafico e imposta il file[`FillMode`](../fillmode/) AAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Inverte l'ordine di figure, forme e punti in ciascuna forma di questo`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Applica la trasformazione specificata alla forma. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Aggiunge un contorno aggiuntivo al percorso. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Aggiunge un contorno aggiuntivo a`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Sostituisce questo`GraphicsPath` con curve che racchiudono l'area che viene riempita quando questo percorso viene disegnato dalla penna specificata. |

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


