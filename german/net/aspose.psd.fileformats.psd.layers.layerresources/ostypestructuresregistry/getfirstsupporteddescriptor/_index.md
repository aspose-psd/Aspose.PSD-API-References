---
title: OSTypeStructuresRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD für .NET-API-Referenz
description: OSTypeStructuresRegistry methode. Ruft den ersten unterstützten OpenerDeskriptor ab.
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/
---
## OSTypeStructuresRegistry.GetFirstSupportedDescriptor method

Ruft den ersten unterstützten Opener-Deskriptor ab.

```csharp
public static IOSTypeStructureLoader GetFirstSupportedDescriptor(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |

### Rückgabewert

Der Layer-Ressourcen-Loader-Deskriptor oder null, wenn kein Loader-Deskriptor für diesen Stream unterstützt wird.

### Bemerkungen

Der erste Lader wird tatsächlich der letzte registrierte sein.

### Siehe auch

* interface [IOSTypeStructureLoader](../../iostypestructureloader/)
* class [OSTypeStructuresRegistry](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ostypestructuresregistry/)
* Montage [Aspose.PSD](../../../)


