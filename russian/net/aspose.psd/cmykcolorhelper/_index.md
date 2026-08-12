---
title: "Класс CmykColorHelper"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.CmykColorHelper. Вспомогательные методы для работы с цветом CMYK, представленным как знаковое 32‑битное целое значение. Предоставляет аналогичный API, как у структуры CmykColor. Он более лёгкий, потому что цвет CMYK представлен просто как Int32, а не как структура с внутренними полями. По возможности предпочтительно использовать статические методы этого класса вместо устаревшей структуры CmykColor."
type: docs
weight: 280
url: /ru/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

Вспомогательные методы для работы с цветом CMYK, представленным как знаковое 32‑битное целое значение. Предоставляет аналогичный API, как у структуры [`CmykColor`](../cmykcolor/). Он более лёгкий, потому что цвет CMYK представлен просто как Int32, а не как структура с внутренними полями. По возможности предпочтительно использовать статические методы этого класса вместо устаревшей структуры [`CmykColor`](../cmykcolor/).

```csharp
public static class CmykColorHelper
```

## Методы

| Имя | Описание |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Создаёт CMYK из 32‑битных значений циана, мадженты, желтого и черного. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Получает значение компоненты циана. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Получает значение компоненты черного. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Получает значение компоненты мадженты. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Получает значение компоненты желтого. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | Преобразование цвета CMYK в цвет ARGB. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | Преобразование цветов CMYK в цвета ARGB. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | Преобразование цветов CMYK в цвета ARGB. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | Преобразование цвета CMYK в цвет ARGB с использованием ICC‑преобразования и профилей по умолчанию. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования и профилей по умолчанию. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | Преобразование цвета CMYK в цвет ARGB с использованием ICC‑преобразования и пользовательского профиля. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования и пользовательских профилей. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | Преобразование цвета ARGB в цвет CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | Преобразование цветов ARGB в цвета CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | Преобразование цвета ARGB в цвет CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | Преобразование цветов ARGB в цвета CMYK. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Преобразует RGB в CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и профилей по умолчанию. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и профилей по умолчанию. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и пользовательских профилей. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Преобразует RGB в CMYK с использованием пользовательских ICC профилей. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


