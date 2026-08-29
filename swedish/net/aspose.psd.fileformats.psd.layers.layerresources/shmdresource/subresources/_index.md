---
title: "ShmdResource.SubResources"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ShmdResource egenskap. Hämtar delresurserna för shmd-resursen"
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

Hämtar delresurserna för shmd-resursen.

```csharp
public LayerResource[] SubResources { get; }
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

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


