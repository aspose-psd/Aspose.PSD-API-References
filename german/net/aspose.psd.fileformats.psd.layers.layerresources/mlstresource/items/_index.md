---
title: "MlstResource.Items"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "MlstResource-Eigenschaft. Ruft die Strukturen ab oder legt sie fest"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

Liest oder setzt die Strukturen.

```csharp
public OSTypeStructure[] Items { get; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung der MlstResource-Ressource, die einen Low-Level-Mechanismus zum Manipulieren des Ebenenzustands bietet.

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

    // Deaktiviere Ebene 1 im Frame 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Siehe auch

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


