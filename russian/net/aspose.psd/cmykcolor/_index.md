---
title: "Структура CmykColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.CmykColor struct. Цвет пикселя в CMYK"
type: docs
weight: 270
url: /ru/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

CMYK‑цвет пикселя.

```csharp
public struct CmykColor
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Получает пустое. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Получает значение компоненты cyan этой структуры [`Color`](../color/). |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Возвращает значение, указывающее, инициализирована ли эта структура [`Color`](../color/). |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Возвращает значение черного компонента этой структуры [`Color`](../color/). |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Возвращает значение пурпурного компонента этой структуры [`Color`](../color/). |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Возвращает значение желтого компонента этой структуры [`Color`](../color/). |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Создает структуру `CmykColor` из 32‑битных значений циана, пурпура, желтого и черного. Этот метод устарел. Пожалуйста, используйте более эффективный [`FromComponents`](../cmykcolorhelper/fromcomponents/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | Преобразование из 32‑битного ARGB в CMYKColor. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Определяет, равен ли указанный объект этому экземпляру. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Получить хеш‑код. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Получить значение. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | Преобразование из CMYKColor в 32‑битный ARGB Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToArgb32`](../cmykcolorhelper/toargb32/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | Преобразование из 32‑битного ARGB‑цвета в CMYKColor. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | Преобразование из CMYKColor в Color. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования. Этот метод устарел. Пожалуйста, используйте более эффективный [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


