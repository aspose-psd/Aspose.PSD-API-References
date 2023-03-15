---
title: Class MlstResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource klas. De mlst resource. Deze klasse bevat onder andere informatie over de positie van de laag op de tijdlijn.
type: docs
weight: 2830
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

De mlst resource. Deze klasse bevat onder andere informatie over de positie van de laag op de tijdlijn.

```csharp
public class MlstResource : LayerResource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MlstResource](mlstresource/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Haalt de versie van de descriptor op of stelt deze in. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Krijgt of stelt de structuren in. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Haalt de resourcelengte van de laag op in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | Krijgt de psd-versie. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | Krijgt de handtekening. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Slaat de opgegeven streamcontainer op. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


