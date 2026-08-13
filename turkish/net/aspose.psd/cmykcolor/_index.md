---
title: "Yapı CmykColor"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.CmykColor yapısı. Pikselin CMYK rengi"
type: docs
weight: 270
url: /tr/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

Pikselin CMYK rengi.

```csharp
public struct CmykColor
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Boş olanı alır. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Bu [`Color`](../color/) yapısının camgöbeği bileşen değerini alır. |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Bu [`Color`](../color/) yapısının başlatılmamış olup olmadığını gösteren bir değer alır. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Bu [`Color`](../color/) yapısının siyah bileşen değerini alır. |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Bu [`Color`](../color/) yapısının macenta bileşen değerini alır. |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Bu [`Color`](../color/) yapısının sarı bileşen değerini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | 32 bit cyan, magenta, yellow ve black değerlerinden bir `CmykColor` yapısı oluşturur. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`FromComponents`](../cmykcolorhelper/fromcomponents/) kullanın. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | 32 bit ARGB'den CMYKColor'a dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToCmyk`](../cmykcolorhelper/tocmyk/) kullanın. |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Belirtilen Nesnenin bu örnek ile eşit olup olmadığını belirler. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Hash kodunu al. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Değere dön. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | CMYKColor'dan 32 bit ARGB Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToArgb32`](../cmykcolorhelper/toargb32/) kullanın. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | 32 bit ARGB renginden CMYKColor'a dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToCmyk`](../cmykcolorhelper/tocmyk/) kullanın. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | CMYKColor'dan Color'a dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToArgb`](../cmykcolorhelper/toargb/) kullanın. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToArgb`](../cmykcolorhelper/toargb/) kullanın. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) kullanın. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) kullanın. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | CMYKColor'dan Color'a icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) kullanın. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | CMYKColor'dan Color'a icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) kullanın. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


