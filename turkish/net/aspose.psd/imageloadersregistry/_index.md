---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageLoadersRegistry sınıf. Görüntü yükleyici kayıt defterini temsil eder.
type: docs
weight: 4780
url: /tr/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Görüntü yükleyici kayıt defterini temsil eder.

```csharp
public static class ImageLoadersRegistry
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Kayıtlı tanımlayıcıları alır. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Kayıtlı resim yükleme formatlarını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Belirtilene uygun bulunan ilk yükleyiciyi oluşturur.*stream* ve isteğe bağlı olarak*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Belirtilen için uygun bulunan ilk desteklenen tanımlayıcıyı alır*stream* ve isteğe bağlı olarak*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Tür adına göre desteklenen ilk dosya biçimini alır. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Tür adına göre desteklenen ilk tanımlayıcıyı alır. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Belirtilen resim yükleyici tanımlayıcısını kaydeder. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Yükleyiciyi kaydeder. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Yükleyicinin kaydını siler. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


