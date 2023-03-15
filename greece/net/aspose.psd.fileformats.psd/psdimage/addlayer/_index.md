---
title: PsdImage.AddLayer
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage μέθοδος. Προσθέτει το επίπεδο.
type: docs
weight: 370
url: /el/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Προσθέτει το επίπεδο.

```csharp
public void AddLayer(Layer layer)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layer | Layer | Το στρώμα. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να σχεδιάσετε σε ένα επίπεδο που δημιουργήθηκε πρόσφατα εάν χρησιμοποιείται η απλή έκδοση κατασκευαστή στο Aspose.PSD

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

    // σχεδιάστε ένα ορθογώνιο με το εργαλείο στυλό
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // σχεδιάστε ένα άλλο ορθογώνιο με το Solid Brush σε μπλε χρώμα
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


