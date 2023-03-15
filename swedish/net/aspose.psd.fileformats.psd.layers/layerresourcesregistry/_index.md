---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry klass. Definiera lagerresursregistret för PSDfiler som laddas.
type: docs
weight: 3390
url: /sv/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

Definiera lagerresursregistret för PSD-filer som laddas.

```csharp
public static class LayerResourcesRegistry
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Hämtar de registrerade beskrivningarna. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Får den första öppnarbeskrivningen som stöds. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Hämtar den första beskrivningen som stöds efter dess typnamn. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Laddar[`LayerResource`](../layerresource/) använder först hittade öppnare som är lämplig för det specificerade*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Registrerar öppnaren. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Avregistrerar öppnaren. |

### Se även

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* hopsättning [Aspose.PSD](../../)


