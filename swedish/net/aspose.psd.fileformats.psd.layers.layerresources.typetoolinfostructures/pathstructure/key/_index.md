---
title: "PathStructure.Key"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PathStructure-egenskap. Hämtar strukturnyckeln"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
{{< psd/tize >}}
## PathStructure.Key property

Hämtar strukturnyckeln.

```csharp
public override int Key { get; }
```

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


