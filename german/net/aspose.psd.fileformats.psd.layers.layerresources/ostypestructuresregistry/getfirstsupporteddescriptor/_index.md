---
title: "OSTypeStructuresRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "OSTypeStructuresRegistry-Methode. Gibt den ersten unterstützten Öffner-Deskriptor zurück."
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry.GetFirstSupportedDescriptor method

Ermittelt den ersten unterstützten Öffner-Deskriptor.

```csharp
public static IOSTypeStructureLoader GetFirstSupportedDescriptor(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream. |

### Rückgabewert

Der Layer-Resource-Loader-Deskriptor oder null, wenn kein Loader-Deskriptor für einen solchen Stream unterstützt wird.

## Hinweise

Der erste Loader ist tatsächlich der zuletzt registrierte.

### Siehe auch

* interface [IOSTypeStructureLoader](../../iostypestructureloader/)
* class [OSTypeStructuresRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


