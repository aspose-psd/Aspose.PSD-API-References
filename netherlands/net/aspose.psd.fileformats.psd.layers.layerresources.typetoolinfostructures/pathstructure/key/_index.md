---
title: PathStructure.Key
second_title: Aspose.PSD voor .NET API-referentie
description: PathStructure eigendom. Haalt de structuursleutel op.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

Haalt de structuursleutel op.

```csharp
public override int Key { get; }
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


