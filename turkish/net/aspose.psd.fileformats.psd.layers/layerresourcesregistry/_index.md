---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry sınıf. Yüklenen PSD dosyaları için katman kaynakları kaydını tanımlayın.
type: docs
weight: 3390
url: /tr/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

Yüklenen PSD dosyaları için katman kaynakları kaydını tanımlayın.

```csharp
public static class LayerResourcesRegistry
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Kayıtlı tanımlayıcıları alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Desteklenen ilk açıcı tanımlayıcıyı alır. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Tür adına göre desteklenen ilk tanımlayıcıyı alır. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Yükler[`LayerResource`](../layerresource/) belirtilene uygun ilk bulunan açıcıyı kullanmak*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Açıcıyı kaydeder. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Açıcının kaydını siler. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* toplantı [Aspose.PSD](../../)


