---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ImageLoadersRegistry yöntemi. Belirtilen akış için uygun ve isteğe bağlı olarak loadOptions içeren ilk bulunan yükleyiciyi oluşturur"
type: docs
weight: 30
url: /tr/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Belirtilen *stream* için uygun olan ve isteğe bağlı olarak *loadOptions*'ı da dikkate alan ilk bulunan yükleyiciyi oluşturur.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Akış. |
| loadOptions | LoadOptions | Yükleme seçenekleri. |

### Dönüş Değeri

Belirtilen *stream* ve *loadOptions* destekleyen yükleyici veya böyle bir yükleyici bulunamazsa null.

## Açıklamalar

İlk yükleyici aslında en son kaydedilen olacaktır.

### Ayrıca Bakınız

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


