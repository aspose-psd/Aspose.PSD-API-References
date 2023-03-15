---
title: PathStructure.StructureKey
second_title: Aspose.PSD voor .NET API-referentie
description: PathStructure veld. Identificeert de structuursleutel.
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
## PathStructure.StructureKey field

Identificeert de structuursleutel.

```csharp
public const int StructureKey;
```

### Voorbeelden

De volgende code demonstreert de mogelijkheid om een bestand te laden met de PathStructure-structuur.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Zie ook

* class [PathStructure](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* montage [Aspose.PSD](../../../)


