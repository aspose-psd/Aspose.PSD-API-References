---
title: PathStructure.Path
second_title: Aspose.PSD för .NET API-referens
description: PathStructure fast egendom. Hämtar eller ställer in sökvägen.
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

Hämtar eller ställer in sökvägen.

```csharp
public string Path { get; set; }
```

### Fastighetsvärde

Den fullständiga sökvägen.

### Exempel

Följande kod visar förmågan att ladda fil med PathStructure-struktur.

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
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* hopsättning [Aspose.PSD](../../../)


