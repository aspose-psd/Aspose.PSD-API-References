---
title: ShmdResource.SubResources
second_title: Aspose.PSD für .NET-API-Referenz
description: ShmdResource eigendom. Ruft die Unterressourcen der shmdRessource ab.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Ruft die Unterressourcen der shmd-Ressource ab.

```csharp
public LayerResource[] SubResources { get; }
```

### Beispiele

Der folgende Code demonstriert die Unterstützung der MlstResource-Ressource, die einen Low-Level-Mechanismus zum Bearbeiten der Layer-Zustände bereitstellt.

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

    // Layer 1 auf Frame 1 deaktivieren
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Siehe auch

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* Montage [Aspose.PSD](../../../)


