---
title: "Layer.DisplayName"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Lagrets egenskap. Hämtar eller anger lagrets visningsnamn"
type: docs
weight: 110
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Hämtar eller anger lagrets visningsnamn.

```csharp
public string DisplayName { get; set; }
```

### Property Value

Lagrets visningsnamn.

## Exempel

Följande exempel demonstrerar möjligheten att sätta DisplayName-värdet, så att lagrets namn visas korrekt.

```csharp
[C#]

// gör ändringar i lagernamn och spara dem
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // sätt ett nytt värde i DisplayName-egenskapen
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Se även

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


