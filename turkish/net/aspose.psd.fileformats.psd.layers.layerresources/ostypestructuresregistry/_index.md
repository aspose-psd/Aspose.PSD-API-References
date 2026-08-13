---
title: "Sınıf OSTypeStructuresRegistry"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry sınıfı. OSTypeStructure kaynak kayıt defterini temsil eder."
type: docs
weight: 3200
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

[`OSTypeStructure`](../ostypestructure/) kaynak kayıt defterini temsil eder.

```csharp
public static class OSTypeStructuresRegistry
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | Kayıtlı tanımlayıcıları alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | İlk desteklenen açıcı tanımlayıcısını alır. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | Tür adına göre ilk desteklenen tanımlayıcıyı alır. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | Belirtilen *stream* için uygun bulunan ilk açıcıyı kullanarak [`OSTypeStructure`](../ostypestructure/) yükler. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | Açıcıyı kaydeder. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | Açıcı kaydını siler. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


