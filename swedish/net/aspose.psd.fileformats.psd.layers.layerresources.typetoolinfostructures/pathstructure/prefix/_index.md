---
title: "PathStructure.Prefix"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PathStructure-egenskap. Hämtar eller anger sökvägsprefixet"
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

Hämtar eller anger sökvägsprefixet.

```csharp
public string Prefix { get; set; }
```

### Property Value

Den fullständiga sökvägen.

## Exempel

Följande kod demonstrerar förmågan att läsa in en fil med PathStructure-struktur.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Se även

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


