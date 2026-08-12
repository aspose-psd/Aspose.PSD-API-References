---
title: "MlstResource.Items"
second_title: "Aspose.PSD för .NET API‑referens"
description: "MlstResource egenskap. Hämtar eller anger strukturerna"
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

Hämtar eller anger strukturerna.

```csharp
public OSTypeStructure[] Items { get; }
```

## Exempel

Följande kod demonstrerar stöd för MlstResource‑resursen som ger en låg‑nivå‑mekanism för att manipulera lagrets tillstånd.

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

    // Inaktivera lager 1 på bildruta 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Se även

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


