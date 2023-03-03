---
title: Enum TextOrientation
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.TextOrientation enum. Enumerazione per la modalità di orientamento del testo.
type: docs
weight: 4010
url: /it/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Enumerazione per la modalità di orientamento del testo.

```csharp
public enum TextOrientation
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Horizontal | `0` | L'orientamento orizzontale del testo. |
| Vertical | `2` | L'orientamento verticale del testo. |

### Esempi

Il codice seguente dimostra la possibilità di modificare la nuova proprietà TextOrientation. Ciò non influisce sul rendering al momento, ma consente solo di modificare il valore della proprietà.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Lettura corretta
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // Lettura corretta
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assemblea [Aspose.PSD](../../)


