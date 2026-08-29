---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerResourcesRegistry-Methode. Gibt den ersten unterstützten Öffner-Deskriptor zurück"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Ermittelt den ersten unterstützten Öffner-Deskriptor.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream. |
| psdVersion | Int32 | Die PSD-Version. |

### Rückgabewert

Der Layer-Resource-Loader-Deskriptor oder null, wenn kein Loader-Deskriptor für einen solchen Stream unterstützt wird.

## Hinweise

Der erste Loader ist tatsächlich der zuletzt registrierte.

### Siehe auch

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


