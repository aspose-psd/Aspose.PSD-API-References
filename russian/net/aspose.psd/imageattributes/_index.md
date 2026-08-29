---
title: "Класс ImageAttributes"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.ImageAttributes класс. Объект ImageAttributes содержит информацию о том, как цвета растровых изображений и метафайлов изменяются во время рендеринга. Объект ImageAttributes поддерживает несколько настроек коррекции цвета, включая матрицы коррекции цвета, матрицы коррекции в градациях серого, значения гамма‑коррекции, таблицы цветовых карт и пороговые значения цвета. Во время рендеринга цвета могут быть скорректированы, затемнены, осветлены и удалены. Чтобы применить такие манипуляции, инициализируйте объект ImageAttributes и передайте путь к этому объекту ImageAttributes вместе с путём к Image в метод DrawImage."
type: docs
weight: 5080
url: /ru/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

Объект `ImageAttributes` содержит информацию о том, как цвета растровых изображений и метафайлов изменяются во время рендеринга. Объект `ImageAttributes` поддерживает несколько настроек коррекции цвета, включая матрицы коррекции цвета, матрицы коррекции в градациях серого, значения гамма‑коррекции, таблицы цветовых карт и пороговые значения цвета. Во время рендеринга цвета могут быть скорректированы, затемнены, осветлены и удалены. Чтобы применить такие манипуляции, инициализируйте объект `ImageAttributes` и передайте путь к этому объекту `ImageAttributes` (вместе с путём к [`Image`](../image/)) в метод DrawImage.

```csharp
public sealed class ImageAttributes
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Очищает таблицу переназначения цветов кисти этого объекта `ImageAttributes`. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Очищает ключ цвета (диапазон прозрачности) для категории по умолчанию. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Очищает ключ цвета (диапазон прозрачности) для указанной категории. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Очищает матрицу коррекции цвета для категории по умолчанию. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Очищает матрицу коррекции цвета для указанной категории. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Отключает гамма‑коррекцию для категории по умолчанию. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Отключает гамма‑коррекцию для указанной категории. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Очищает настройку NoOp для категории по умолчанию. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Очищает настройку NoOp для указанной категории. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Очищает настройку выходного канала CMYK (циан‑пурпур‑желтый‑чёрный) для категории по умолчанию. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Очищает настройку выходного канала (циан‑пурпур‑желтый‑чёрный) для указанной категории. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Очищает настройку цветового профиля выходного канала для категории по умолчанию. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Очищает настройку цветового профиля выходного канала для указанной категории. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Очищает таблицу переназначения цветов для категории по умолчанию. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Очищает таблицу переназначения цветов для указанной категории. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Очищает значение порога для категории по умолчанию. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Очищает значение порога для указанной категории. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Устанавливает таблицу перекраски цветов для категории кисти. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Устанавливает цветовой ключ для категории по умолчанию. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для указанной категории. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Устанавливает матрицу коррекции цвета для указанной категории. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Устанавливает значение гаммы для категории по умолчанию. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Устанавливает значение гаммы для указанной категории. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Отключает коррекцию цвета для категории по умолчанию. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Отключает коррекцию цвета для указанной категории. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑черный) для категории по умолчанию. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑черный) для указанной категории. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Устанавливает файл цветового профиля канала вывода для категории по умолчанию. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Устанавливает файл цветового профиля канала вывода для указанной категории. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Устанавливает таблицу перекраски цветов для категории по умолчанию. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Устанавливает таблицу перекраски цветов для указанной категории. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Устанавливает порог (диапазон прозрачности) для категории по умолчанию. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Устанавливает порог (диапазон прозрачности) для указанной категории. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Устанавливает режим обтекания, который используется для определения того, как размещать текстуру по фигуре или на границах фигуры. Текстура размещается по фигуре, заполняя её, когда текстура меньше фигуры, которую она заполняет. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по фигуре или на границах фигуры. Текстура размещается по фигуре, заполняя её, когда текстура меньше фигуры, которую она заполняет. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по фигуре или на границах фигуры. Текстура размещается по фигуре, заполняя её, когда текстура меньше фигуры, которую она заполняет. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


