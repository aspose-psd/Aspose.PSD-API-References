---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry klas. Definieer het laagbronnenregister voor het laden van PSDbestanden.
type: docs
weight: 3390
url: /nl/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

Definieer het laagbronnenregister voor het laden van PSD-bestanden.

```csharp
public static class LayerResourcesRegistry
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Haalt de geregistreerde descriptors op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Haalt de eerste ondersteunde opener-descriptor op. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Haalt de eerste ondersteunde descriptor op met zijn typenaam. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Ladingen[`LayerResource`](../layerresource/) de eerst gevonden opener gebruiken die geschikt is voor de gespecificeerde*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Registreert de opener. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Registreert de opener. |

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* montage [Aspose.PSD](../../)


