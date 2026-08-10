---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος PsdImage. Προσθέτει το στρώμα"
type: docs
weight: 390
url: /el/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Προσθέτει το επίπεδο.

```csharp
public void AddLayer(Layer layer)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στρώση | Στρώση | Το στρώμα. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να σχεδιάσετε σε ένα νεοδημιουργημένο layer εάν χρησιμοποιηθεί η απλή έκδοση του κατασκευαστή στο Aspose.PSD

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

    // σχεδιάστε ένα ορθογώνιο με το εργαλείο Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // σχεδιάστε ένα άλλο ορθογώνιο με Solid Brush σε μπλε χρώμα
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


