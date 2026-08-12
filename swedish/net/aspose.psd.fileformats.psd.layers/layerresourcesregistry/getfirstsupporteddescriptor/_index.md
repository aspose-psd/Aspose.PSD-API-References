---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LayerResourcesRegistry metod. Hämtar den första stödda öppnardeskriptorn"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Hämtar den första stödda öppnarebeskrivaren.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen. |
| psdVersion | Int32 | PSD-versionen. |

### Returvärde

Lagerresursladdningsdeskriptorn eller null om ingen laddningsdeskriptör stöds för sådan ström.

## Anmärkningar

Den första laddaren kommer faktiskt att vara den sist registrerade.

### Se även

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


