---
title: Graphics.DrawRectangles
second_title: Aspose.PSD per riferimento API .NET
description: Graphics metodo. Disegna una serie di rettangoli specificati daRectangleF strutture.
type: docs
weight: 310
url: /it/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Disegna una serie di rettangoli specificati da[`RectangleF`](../../rectanglef/) strutture.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | RectangleF[] | Matrice di[`RectangleF`](../../rectanglef/) strutture che rappresentano i rettangoli da disegnare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -oppure- *rects* è zero. |

### Guarda anche

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Disegna una serie di rettangoli specificati da[`Rectangle`](../../rectangle/) strutture.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | Rectangle[] | Matrice di[`Rectangle`](../../rectangle/) strutture che rappresentano i rettangoli da disegnare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -oppure- *rects* è zero. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)


