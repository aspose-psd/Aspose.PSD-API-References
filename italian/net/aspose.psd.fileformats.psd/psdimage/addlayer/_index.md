---
title: PsdImage.AddLayer
second_title: Aspose.PSD per riferimento API .NET
description: PsdImage metodo. Aggiunge il livello.
type: docs
weight: 370
url: /it/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Aggiunge il livello.

```csharp
public void AddLayer(Layer layer)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layer | Layer | Lo strato. |

### Esempi

L'esempio seguente mostra come disegnare su un livello appena creato se viene utilizzata la versione del costruttore semplice in Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // disegna un rettangolo con lo strumento Penna
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // disegna un altro rettangolo con Solid Brush in colore blu
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Guarda anche

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assemblea [Aspose.PSD](../../../)


