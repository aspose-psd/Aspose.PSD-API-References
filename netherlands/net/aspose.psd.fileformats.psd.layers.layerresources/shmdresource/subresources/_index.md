---
title: ShmdResource.SubResources
second_title: Aspose.PSD voor .NET API-referentie
description: ShmdResource eigendom. Haalt de subbronnen op van shmd resource.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Haalt de subbronnen op van shmd resource.

```csharp
public LayerResource[] SubResources { get; }
```

### Voorbeelden

De volgende code demonstreert de ondersteuning van de MlstResource-resource die een mechanisme op laag niveau biedt om de laagstatussen te manipuleren.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Schakel laag 1 uit op frame 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Zie ook

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* montage [Aspose.PSD](../../../)


