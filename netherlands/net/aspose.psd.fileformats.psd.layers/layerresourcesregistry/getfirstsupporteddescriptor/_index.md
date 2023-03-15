---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD voor .NET API-referentie
description: LayerResourcesRegistry methode. Haalt de eerste ondersteunde openerdescriptor op.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Haalt de eerste ondersteunde opener-descriptor op.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom. |
| psdVersion | Int32 | De PSD-versie. |

### Winstwaarde

De laagresourceladerdescriptor of null als er geen loaderdescriptor wordt ondersteund voor een dergelijke stream.

### Opmerkingen

De eerste lader zal de laatst geregistreerde zijn.

### Zie ook

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* montage [Aspose.PSD](../../../)


