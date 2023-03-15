---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API Referansı
description: ImageExportersRegistry yöntem. Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk desteklenen tanımlayıcıyı alır.
type: docs
weight: 40
url: /tr/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk desteklenen tanımlayıcıyı alır.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Image | Dışa aktarılacak resim. |
| options | ImageOptionsBase | Seçenekler. |

### Geri dönüş değeri

Belirtilen görüntüyü ve kaydetme seçeneklerini destekleyen dışa aktarıcı tanımlayıcısı veya böyle bir tanımlayıcı bulunmazsa null.

### Notlar

İlk ihracatçı tanımlayıcısı aslında en son kaydedilen tanımlayıcı olacaktır.

### Ayrıca bakınız

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* ad alanı [Aspose.PSD](../../imageexportersregistry/)
* toplantı [Aspose.PSD](../../../)


