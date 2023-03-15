---
title: Class MlstResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource klass. Mlstresursen. Den här klassen innehåller bland annat information om lagrets position på tidslinjen.
type: docs
weight: 2830
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

Mlst-resursen. Den här klassen innehåller bland annat information om lagrets position på tidslinjen.

```csharp
public class MlstResource : LayerResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MlstResource](mlstresource/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Hämtar eller ställer in deskriptorversionen. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Hämtar eller ställer in strukturerna. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | Får signaturen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Sparar den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | Typverktygets infonyckel. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


