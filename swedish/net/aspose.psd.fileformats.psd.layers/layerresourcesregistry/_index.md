---
title: "Klass LayerResourcesRegistry"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry-klass. Definierar lagerresursregistret för inläsning av PSD-filer"
type: docs
weight: 3790
url: /sv/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

Definiera lagrets resurserregister för inläsning av PSD‑filer.

```csharp
public static class LayerResourcesRegistry
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Hämtar de registrerade beskrivarna. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Hämtar den första stödda öppnarebeskrivaren. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Hämtar den första stödda beskrivaren efter dess typnamn. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Laddar [`LayerResource`](../layerresource/) med den första funna öppnaren som är lämplig för den angivna *strömmen*. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Registrerar öppnaren. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Avregistrerar öppnaren. |

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


