---
title: PathStructure.StructureKey
second_title: Aspose.PSD för .NET API-referens
description: PathStructure fält. Identifierar strukturnyckeln.
type: docs
weight: 60
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
## PathStructure.StructureKey field

Identifierar strukturnyckeln.

```csharp
public const int StructureKey;
```

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


