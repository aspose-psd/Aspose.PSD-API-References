---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD for .NET API Referansı"
description: "CmykColorHelper yöntemi. Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştürür"
type: docs
weight: 120
url: /tr/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştürür.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | Int32[] | 32 bit tamsayı değerleri olarak sunulan RGB renkleri. |
| startIndex | Int32 | RGB renginin başlangıç indeksi. |
| uzunluk | Int32 | Dönüştürülecek RGB piksel sayısı. |
| rgbIccStream | Stream | RGB profil akışı. |
| cmykIccStream | Stream | CMYK profil akışı. |

### Dönüş Değeri

CMYK renkler bayt dizisi olarak sunulur.

### Ayrıca Bakınız

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


