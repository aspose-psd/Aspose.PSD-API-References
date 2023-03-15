---
title: IText.TextOrientation
second_title: Aspose.PSD per riferimento API .NET
description: IText proprietà. Ottiene o imposta lorientamento del testo.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Ottiene o imposta l'orientamento del testo.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Valore della proprietà

L'orientamento del testo.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* assemblea [Aspose.PSD](../../../)


