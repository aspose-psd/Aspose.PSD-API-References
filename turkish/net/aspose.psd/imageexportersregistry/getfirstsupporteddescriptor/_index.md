---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ImageExportersRegistry yöntemi. Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır."
type: docs
weight: 40
url: /tr/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Dışa aktarılacak görüntü. |
| seçenekler | ImageOptionsBase | Seçenekler. |

### Dönüş Değeri

Belirtilen görüntü ve kaydetme seçeneklerini destekleyen dışa aktarıcı tanımlayıcı; böyle bir tanımlayıcı bulunamazsa null döner.

## Açıklamalar

İlk dışa aktarıcı tanımlayıcı aslında en son kayıt edilen olacaktır.

### Ayrıca Bakınız

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


