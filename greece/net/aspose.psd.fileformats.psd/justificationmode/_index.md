---
title: "Απαρίθμηση JustificationMode"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. Η λειτουργία στοίχισης κειμένου"
type: docs
weight: 1690
url: /el/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

Η λειτουργία στοίχισης κειμένου.

```csharp
public enum JustificationMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Left | `0` | Το αριστερό ευθυγραμμισμένο κείμενο. Σε λειτουργία αριστερά προς δεξιά, η θέση Left είναι Left. Σε λειτουργία δεξιά προς αριστερά, η θέση Left είναι Right. |
| Right | `1` | Το δεξιό ευθυγραμμισμένο κείμενο. Σε λειτουργία αριστερά προς δεξιά, η θέση Right είναι Right. Σε λειτουργία δεξιά προς αριστερά, η θέση Right είναι Left. |
| Center | `2` | Το κεντρικό κείμενο. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της απαρίθμησης JustificationMode για ορισμό της στοίχισης κειμένου σε τμήματα κειμένου.

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


