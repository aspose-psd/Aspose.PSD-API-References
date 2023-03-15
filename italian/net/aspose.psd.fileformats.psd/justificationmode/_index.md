---
title: Enum JustificationMode
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.JustificationMode enum. La modalità di allineamento del testo.
type: docs
weight: 1650
url: /it/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

La modalità di allineamento del testo.

```csharp
public enum JustificationMode
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Left | `0` | Il testo di allineamento a sinistra. |
| Right | `1` | Il testo allineato a destra. |
| Center | `2` | Il testo centrale. |

### Esempi

Il codice seguente illustra il supporto dell'enumerazione JustificationMode per impostare l'allineamento del testo per le parti di testo.

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

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assemblea [Aspose.PSD](../../)


