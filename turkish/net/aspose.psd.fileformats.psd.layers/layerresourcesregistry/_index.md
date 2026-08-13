---
title: "LayerResourcesRegistry sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry sınıfı. PSD dosyalarının yüklenmesi için katman kaynakları kayıt defterini tanımlar."
type: docs
weight: 3790
url: /tr/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

PSD dosyalarının yüklenmesi için katman kaynakları kayıt defterini tanımlayın.

```csharp
public static class LayerResourcesRegistry
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Kayıtlı tanımlayıcıları alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | İlk desteklenen açıcı tanımlayıcısını alır. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Tür adına göre ilk desteklenen tanımlayıcıyı alır. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Belirtilen *stream* için uygun bulunan ilk açıcıyı kullanarak [`LayerResource`](../layerresource/) yükler. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Açıcıyı kaydeder. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Açıcı kaydını siler. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


