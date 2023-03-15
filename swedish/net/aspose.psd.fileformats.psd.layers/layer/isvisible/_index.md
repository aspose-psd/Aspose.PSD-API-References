---
title: Layer.IsVisible
second_title: Aspose.PSD för .NET API-referens
description: Layer fast egendom. Hämtar eller ställer in ett värde som anger om lagret är synligt
type: docs
weight: 170
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Hämtar eller ställer in ett värde som anger om lagret är synligt

```csharp
public bool IsVisible { get; set; }
```

### Fastighetsvärde

`Sann` om denna instans är synlig; annat,`falsk` .

### Exempel

Följande exempel visar hur du kan ändra LayerGroup-synlighet i Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// gör ändringar i lagernamn och spara det
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Stäng av allt i en grupp
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
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)


