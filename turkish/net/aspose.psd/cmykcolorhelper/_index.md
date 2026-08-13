---
title: "CmykColorHelper sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.CmykColorHelper sınıfı. CMYK rengini imzalı 32 bit tam sayı değeri olarak çalışmak için yardımcı yöntemler. CmykColor yapısı gibi benzer bir API sağlar. CMYK rengi yalnızca Int32 olarak sunulduğu için, iç alanları olan bir yapı yerine daha hafiftir. Mümkün olduğunda, kullanımdan kaldırılmış CmykColor yapısı yerine bu sınıfın statik yöntemlerini tercih edin."
type: docs
weight: 280
url: /tr/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

CMYK rengini imzalı 32-bit tam sayı değeri olarak çalışmak için yardımcı yöntemler. [`CmykColor`](../cmykcolor/) yapısı gibi benzer bir API sağlar. CMYK rengi yalnızca Int32 olarak sunulduğu için, iç alanları olan bir yapı yerine daha hafiftir. Mümkün olduğunda, kullanımdan kaldırılmış [`CmykColor`](../cmykcolor/) yapısı yerine bu sınıfın statik yöntemlerini tercih edin.

```csharp
public static class CmykColorHelper
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 32-bit cyan, magenta, yellow ve black değerlerinden CMYK oluşturur. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Cyan bileşen değerini alır. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Black bileşen değerini alır. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Magenta bileşen değerini alır. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Yellow bileşen değerini alır. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | CMYK renginden ARGB rengine dönüşüm. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | CMYK renklerinden ARGB renklerine dönüşüm. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | CMYK renklerinden ARGB renklerine dönüşüm. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | CMYK renginden ARGB Rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | CMYK renginden ARGB rengine, özel profil ile Icc dönüşümü kullanılarak dönüşüm. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | CMYK renklerinden ARGB renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | ARGB renginden CMYK rengine dönüşüm. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | ARGB renklerinden CMYK renklerine dönüşüm. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | ARGB renginden CMYK rengine dönüşüm. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | ARGB renklerinden CMYK renklerine dönüşüm. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | RGB'yi CMYK'ye dönüştürür. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştürür. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


