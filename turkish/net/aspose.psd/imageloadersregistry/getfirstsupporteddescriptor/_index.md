---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ImageLoadersRegistry yöntemi. Belirtilen akış için uygun ve isteğe bağlı olarak loadOptions içeren ilk bulunan desteklenen tanımlayıcıyı alır"
type: docs
weight: 40
url: /tr/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Belirtilen *stream* için uygun olan ve isteğe bağlı olarak *loadOptions*'ı da dikkate alan ilk bulunan desteklenen tanımlayıcıyı alır.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Akış. |
| loadOptions | LoadOptions | Yükleme seçenekleri. |

### Dönüş Değeri

Belirtilen *stream* ve *loadOptions* destekleyen yükleyici tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null.

## Açıklamalar

İlk yükleyici tanımlayıcı gerçekte son kaydedilen olacaktır.

### Ayrıca Bakınız

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


