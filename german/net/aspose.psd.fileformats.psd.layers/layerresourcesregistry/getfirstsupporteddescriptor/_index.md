---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerResourcesRegistry methode. Ruft den ersten unterstützten OpenerDeskriptor ab.
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Ruft den ersten unterstützten Opener-Deskriptor ab.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| psdVersion | Int32 | Die PSD-Version. |

### Rückgabewert

Der Layer-Ressourcen-Loader-Deskriptor oder null, wenn kein Loader-Deskriptor für diesen Stream unterstützt wird.

### Bemerkungen

Der erste Lader wird tatsächlich der letzte registrierte sein.

### Siehe auch

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* Montage [Aspose.PSD](../../../)


