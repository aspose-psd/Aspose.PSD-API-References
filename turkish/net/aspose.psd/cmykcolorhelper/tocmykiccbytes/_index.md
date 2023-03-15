---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD for .NET API Referansı
description: CmykColorHelper yöntem. Özel ICC profillerini kullanarak RGByi CMYKya dönüştürür.
type: docs
weight: 120
url: /tr/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Özel ICC profillerini kullanarak RGB'yi CMYK'ya dönüştürür.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixels | Int32[] | RGB renkleri, 32 bitlik tamsayı değerleri olarak sunuldu. |
| startIndex | Int32 | RGB renginin başlangıç dizini. |
| length | Int32 | Dönüştürülecek RGB piksel sayısı. |
| rgbIccStream | Stream | RGB profil akışı. |
| cmykIccStream | Stream | CMYK profil akışı. |

### Geri dönüş değeri

Bir bayt dizisi olarak sunulan CMYK renkleri.

### Ayrıca bakınız

* class [CmykColorHelper](../)
* ad alanı [Aspose.PSD](../../cmykcolorhelper/)
* toplantı [Aspose.PSD](../../../)


