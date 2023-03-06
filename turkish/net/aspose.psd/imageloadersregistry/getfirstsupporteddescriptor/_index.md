---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API Referansı
description: ImageLoadersRegistry yöntem. Belirtilen için uygun bulunan ilk desteklenen tanımlayıcıyı alırstream ve isteğe bağlı olarakloadOptions .
type: docs
weight: 40
url: /tr/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Belirtilen için uygun bulunan ilk desteklenen tanımlayıcıyı alır*stream* ve isteğe bağlı olarak*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Akış. |
| loadOptions | LoadOptions | Yükleme seçenekleri. |

### Geri dönüş değeri

Belirtileni destekleyen yükleyici tanımlayıcısı*stream* Ve*loadOptions* veya böyle bir tanımlayıcı bulunmazsa null.

### Notlar

İlk yükleyici tanımlayıcısı aslında en son kaydedilen tanımlayıcı olacaktır.

### Ayrıca bakınız

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* ad alanı [Aspose.PSD](../../imageloadersregistry/)
* toplantı [Aspose.PSD](../../../)


