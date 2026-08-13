---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ImageExtensions yöntemi. Image'ı Image'a dönüştürür"
type: docs
weight: 10
url: /tr/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Image'ı Image'a dönüştürür.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Dönüştürülecek Image. |

### Dönüş Değeri

Dönüştürülmüş Image.

## Açıklamalar

Uyarı, GDI görüntüsü *image*'den daha düşük sınırlara sahip olabilir. Görüntünün tüm bölümlerini elde etmek için daha güvenli uzantı yöntemi ToGdiImageFull kullanın.

### Ayrıca Bakınız

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


