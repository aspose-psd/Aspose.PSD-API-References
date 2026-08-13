---
title: "Sınıf ImageExportersRegistry"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageExportersRegistry sınıfı. Görüntü dışa aktarıcı kayıt defterini temsil eder"
type: docs
weight: 5130
url: /tr/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

Görüntü dışa aktarıcılar kayıt defterini temsil eder.

```csharp
public static class ImageExportersRegistry
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Kayıtlı dışa aktarıcı tanımlayıcılarını alır. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Kayıtlı dışa aktarma formatlarını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan dışa aktarıcıyı oluşturur. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Dışa aktarıcıyı kaydeder. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Dışa aktarıcıyı kayıttan çıkarır. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


