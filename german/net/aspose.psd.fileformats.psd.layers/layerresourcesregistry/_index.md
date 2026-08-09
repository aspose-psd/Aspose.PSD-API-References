---
title: "Klasse LayerResourcesRegistry"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry Klasse. Definiert das Ebenenressourcen-Register für das Laden von PSD-Dateien"
type: docs
weight: 3790
url: /de/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

Definiert das Ressourcenregister für Ebenen beim Laden von PSD‑Dateien.

```csharp
public static class LayerResourcesRegistry
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Ermittelt die registrierten Deskriptoren. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Ermittelt den ersten unterstützten Öffner-Deskriptor. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Ermittelt den ersten unterstützten Deskriptor anhand seines Typnamens. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Lädt [`LayerResource`](../layerresource/) mithilfe des zuerst gefundenen Öffners, der für den angegebenen *Stream* geeignet ist. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Registriert den Öffner. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Deregistriert den Öffner. |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


