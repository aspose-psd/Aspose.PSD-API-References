---
title: PathStructure.Path
second_title: Aspose.PSD voor .NET API-referentie
description: PathStructure eigendom. Haalt of stelt het pad in.
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

Haalt of stelt het pad in.

```csharp
public string Path { get; set; }
```

### Eigendoms-waarde

Het volledige pad.

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


