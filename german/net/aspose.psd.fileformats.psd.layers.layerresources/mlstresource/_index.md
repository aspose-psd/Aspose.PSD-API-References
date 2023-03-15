---
title: Class MlstResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource klas. Die mlstRessource. Diese Klasse enthält unter anderem Informationen über die Position der Ebene auf der Zeitleiste.
type: docs
weight: 2830
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

Die mlst-Ressource. Diese Klasse enthält unter anderem Informationen über die Position der Ebene auf der Zeitleiste.

```csharp
public class MlstResource : LayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MlstResource](mlstresource/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Ruft die Deskriptorversion ab oder legt sie fest. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Holt oder setzt die Strukturen. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | Ruft die Signatur ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Speichert den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


