---
title: Layer.DisplayName
second_title: Aspose.PSD för .NET API-referens
description: Layer fast egendom. Hämtar eller ställer in visningsnamnet för lagret.
type: docs
weight: 100
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Hämtar eller ställer in visningsnamnet för lagret.

```csharp
public string DisplayName { get; set; }
```

### Fastighetsvärde

Visningsnamnet för lagret.

### Exempel

Följande exempel visar möjligheten att ställa in DisplayName-värdet, i vad lagernamnet visas korrekt.

```csharp
[C#]

// gör ändringar i lagernamn och spara det
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // ställ in nytt värde i egenskapen DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Se även

* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)


