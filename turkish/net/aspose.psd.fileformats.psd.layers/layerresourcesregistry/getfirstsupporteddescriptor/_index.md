---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerResourcesRegistry yöntemi. İlk desteklenen açıcı tanımlayıcıyı alır"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

İlk desteklenen açıcı tanımlayıcısını alır.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Akış. |
| psdVersion | Int32 | PSD sürümü. |

### Dönüş Değeri

Katman kaynağı yükleyici tanımlayıcısı veya bu akış için desteklenen bir yükleyici tanımlayıcı yoksa null.

## Açıklamalar

İlk yükleyici aslında en son kaydedilen olacaktır.

### Ayrıca Bakınız

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


