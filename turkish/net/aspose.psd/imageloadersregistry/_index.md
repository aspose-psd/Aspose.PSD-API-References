---
title: "Sınıf ImageLoadersRegistry"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageLoadersRegistry sınıfı. Görüntü yükleyicileri kayıt defterini temsil eder."
type: docs
weight: 5300
url: /tr/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Görüntü yükleyiciler kayıt defterini temsil eder.

```csharp
public static class ImageLoadersRegistry
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Kayıtlı tanımlayıcıları alır. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Kayıtlı görüntü yükleme formatlarını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Belirtilen *stream* için uygun olan ve isteğe bağlı olarak *loadOptions*'ı da dikkate alan ilk bulunan yükleyiciyi oluşturur. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Belirtilen *stream* için uygun olan ve isteğe bağlı olarak *loadOptions*'ı da dikkate alan ilk bulunan desteklenen tanımlayıcıyı alır. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Tür adıyla ilk desteklenen dosya formatını alır. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Tür adına göre ilk desteklenen tanımlayıcıyı alır. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Belirtilen görüntü yükleyici tanımlayıcısını kaydeder. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Yükleyiciyi kaydeder. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Yükleyicinin kaydını siler. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


