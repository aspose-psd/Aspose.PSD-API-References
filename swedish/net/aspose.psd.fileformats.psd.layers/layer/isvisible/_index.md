---
title: "Layer.IsVisible"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Layer-egenskap. Hämtar eller anger ett värde som indikerar om lagret är synligt"
type: docs
weight: 180
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Hämtar eller anger ett värde som indikerar om lagret är synligt

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` om detta objekt är synligt; annars `false`.

## Exempel

Följande exempel visar hur du kan ändra LayerGroup‑synlighet i Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// gör ändringar i lagernamn och spara dem
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Stäng av allt inom en grupp
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Se även

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


