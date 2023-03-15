---
title: ShmdResource.SubResources
second_title: Aspose.PSD för .NET API-referens
description: ShmdResource fast egendom. Hämtar underresurserna för shmdresursen.
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Hämtar underresurserna för shmd-resursen.

```csharp
public LayerResource[] SubResources { get; }
```

### Exempel

Följande kod visar stöd för MlstResource-resursen som ger en lågnivåmekanism för att manipulera lagertillstånden.

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

    // Inaktivera lager 1 på ram 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Se även

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* hopsättning [Aspose.PSD](../../../)


