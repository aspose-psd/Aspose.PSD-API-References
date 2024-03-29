---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry klas. Definieren Sie die LayerRessourcenRegistrierung für das Laden von PSDDateien.
type: docs
weight: 3390
url: /de/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

Definieren Sie die Layer-Ressourcen-Registrierung für das Laden von PSD-Dateien.

```csharp
public static class LayerResourcesRegistry
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Ruft die registrierten Deskriptoren ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Ruft den ersten unterstützten Opener-Deskriptor ab. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Ruft den ersten unterstützten Deskriptor anhand seines Typnamens ab. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Lädt[`LayerResource`](../layerresource/) Verwenden Sie den ersten gefundenen Öffner, der für die angegebenen geeignet ist*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Registriert den Öffner. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Hebt die Registrierung des Öffners auf. |

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Montage [Aspose.PSD](../../)


