---
title: PathStructure.PathStructure
second_title: Aspose.PSD voor .NET API-referentie
description: PathStructure constructeur. Initialiseert een nieuw exemplaar van hetPathStructure klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Initialiseert een nieuw exemplaar van het[`PathStructure`](../) klasse.

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keyName | ClassID | De sleutelnaam. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* montage [Aspose.PSD](../../../)


