---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ImageExportersRegistry yöntemi. Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan dışa aktarıcıyı oluşturur."
type: docs
weight: 30
url: /tr/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan dışa aktarıcıyı oluşturur.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Dışa aktarılacak görüntü. |
| seçenekler | ImageOptionsBase | Dışa aktarma için kullanılacak kaydetme seçenekleri. |

### Dönüş Değeri

Belirtilen görüntü ve kaydetme seçeneklerini destekleyen dışa aktarıcı ya da böyle bir dışa aktarıcı bulunamazsa null.

## Açıklamalar

İlk dışa aktarıcı aslında son kaydedilen olacaktır.

### Ayrıca Bakınız

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


