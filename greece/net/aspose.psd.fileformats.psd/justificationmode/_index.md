---
title: Enum JustificationMode
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.JustificationMode αρίθμηση. Η λειτουργία στοίχισης κειμένου.
type: docs
weight: 1650
url: /el/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

Η λειτουργία στοίχισης κειμένου.

```csharp
public enum JustificationMode
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Left | `0` | Το κείμενο αριστερής στοίχισης. |
| Right | `1` | Το κείμενο δεξιά στοίχισης. |
| Center | `2` | Το κεντρικό κείμενο. |

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη του JustificationMode enum για να ορίσετε τη στοίχιση κειμένου για τμήματα κειμένου.

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* συνέλευση [Aspose.PSD](../../)


