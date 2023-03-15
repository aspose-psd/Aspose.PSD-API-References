---
title: LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerResourcesRegistry methode. LädtLayerResource Verwenden Sie den ersten gefundenen Öffner der für die angegebenen geeignet iststream .
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Lädt[`LayerResource`](../../layerresource/) Verwenden Sie den ersten gefundenen Öffner, der für die angegebenen geeignet ist*stream* .

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| psdVersion | Int32 | Die PSD-Version. |

### Rückgabewert

Die geladen[`LayerResource`](../../layerresource/) oder null, wenn kein Öffner gefunden wird.

### Bemerkungen

Der erste Öffner wird tatsächlich der letzte registrierte sein.

### Siehe auch

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* Montage [Aspose.PSD](../../../)


