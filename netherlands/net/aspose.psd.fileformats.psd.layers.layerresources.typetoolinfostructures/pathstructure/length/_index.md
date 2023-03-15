---
title: PathStructure.Length
second_title: Aspose.PSD voor .NET API-referentie
description: PathStructure eigendom. Krijgt deOSTypeStructure lengte in bytes.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Krijgt de[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) lengte in bytes.

```csharp
public override int Length { get; }
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


