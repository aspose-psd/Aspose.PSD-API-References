---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD för .NET API-referens
description: LayerResourcesRegistry metod. Får den första öppnarbeskrivningen som stöds.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Får den första öppnarbeskrivningen som stöds.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen. |
| psdVersion | Int32 | PSD-versionen. |

### Returvärde

Lagerresursladdningsbeskrivningen eller null om ingen laddarbeskrivning stöds för sådan ström.

### Anmärkningar

Den första laddaren kommer faktiskt att vara den senast registrerade.

### Se även

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* hopsättning [Aspose.PSD](../../../)


