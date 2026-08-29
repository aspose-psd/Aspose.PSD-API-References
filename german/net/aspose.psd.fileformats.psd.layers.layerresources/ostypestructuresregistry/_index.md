---
title: "Klasse OSTypeStructuresRegistry"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry Klasse. Stellt das OSTypeStructure-Ressourcen-Register dar"
type: docs
weight: 3200
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

Stellt das [`OSTypeStructure`](../ostypestructure/) Ressourcen-Register dar.

```csharp
public static class OSTypeStructuresRegistry
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | Ermittelt die registrierten Deskriptoren. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | Ermittelt den ersten unterstützten Öffner-Deskriptor. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | Ermittelt den ersten unterstützten Deskriptor anhand seines Typnamens. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | Lädt [`OSTypeStructure`](../ostypestructure/) mit dem zuerst gefundenen Öffner, der für den angegebenen *stream* geeignet ist. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | Registriert den Öffner. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | Deregistriert den Öffner. |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


