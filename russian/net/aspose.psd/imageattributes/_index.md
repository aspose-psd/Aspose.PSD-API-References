---
title: Class ImageAttributes
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.ImageAttributes сорт. АнImageAttributes Объект содержит информацию о том как цвета растрового изображения и метафайла манипулируются во время рендеринга. АнImageAttributes Объект поддерживает несколько настроек настройки цвета включая матрицы настройки цвета матрицы настройки оттенков серого значения гаммакоррекции таблицы карты цветов и пороговые значения цвета. Во время рендеринга цвета можно корректировать затемнять осветлять и удалять. Чтобы применить такие манипуляции инициализируйтеImageAttributesобъект и пройти путь этогоImageAttributes объекта вместе с путемImage  в метод DrawImage.
type: docs
weight: 4610
url: /ru/net/aspose.psd/imageattributes/
---
## ImageAttributes class

Ан`ImageAttributes` Объект содержит информацию о том, как цвета растрового изображения и метафайла манипулируются во время рендеринга. Ан`ImageAttributes` Объект поддерживает несколько настроек настройки цвета, включая матрицы настройки цвета, матрицы настройки оттенков серого, значения гамма-коррекции, таблицы карты цветов и пороговые значения цвета. Во время рендеринга цвета можно корректировать, затемнять, осветлять и удалять. Чтобы применить такие манипуляции, инициализируйте`ImageAttributes`объект и пройти путь этого`ImageAttributes` объекта (вместе с путем[`Image`](../image/) ) в метод DrawImage.

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
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Очищает таблицу переназначения цветов кисти от этого`ImageAttributes` объект. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Очищает ключ цвета (диапазон прозрачности) для категории по умолчанию. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Очищает ключ цвета (диапазон прозрачности) для указанной категории. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Очищает матрицу настройки цвета для категории по умолчанию. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Очищает матрицу настройки цвета для указанной категории. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Отключает гамма-коррекцию для категории по умолчанию. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Отключает гамма-коррекцию для указанной категории. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Очищает настройку NoOp для категории по умолчанию. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Очищает настройку NoOp для указанной категории. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Очищает настройку выходного канала CMYK (голубой-пурпурный-желтый-черный) для категории по умолчанию. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Очищает настройку выходного канала (голубой-пурпурный-желтый-черный) для указанной категории. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Очищает настройку цветового профиля выходного канала для категории по умолчанию. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Очищает настройку цветового профиля выходного канала для указанной категории. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Очищает таблицу переназначения цветов для категории по умолчанию. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Очищает таблицу переназначения цветов для указанной категории. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Очищает пороговое значение для категории по умолчанию. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Очищает пороговое значение для указанной категории. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Устанавливает таблицу переназначения цветов для категории кистей. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Устанавливает ключ цвета для категории по умолчанию. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Задает матрицу настройки цвета и матрицу настройки оттенков серого для категории по умолчанию. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Задает матрицу настройки цвета и матрицу настройки оттенков серого для категории по умолчанию. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Задает матрицу настройки цвета и матрицу настройки оттенков серого для указанной категории. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Задает матрицу настройки цвета для категории по умолчанию. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Задает матрицу настройки цвета для категории по умолчанию. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Задает матрицу настройки цвета для указанной категории. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Устанавливает значение гаммы для категории по умолчанию. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Устанавливает значение гаммы для указанной категории. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Отключает настройку цвета для категории по умолчанию. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Отключает настройку цвета для указанной категории. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Устанавливает выходной канал CMYK (голубой-пурпурный-желтый-черный) для категории по умолчанию. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Устанавливает выходной канал CMYK (голубой-пурпурный-желтый-черный) для указанной категории. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Устанавливает файл цветового профиля выходного канала для категории по умолчанию. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Устанавливает файл цветового профиля выходного канала для указанной категории. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Задает таблицу переназначения цветов для категории по умолчанию. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Задает таблицу переназначения цветов для указанной категории. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Устанавливает порог (диапазон прозрачности) для категории по умолчанию. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Устанавливает порог (диапазон прозрачности) для указанной категории. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Устанавливает режим переноса, который используется для решения о том, как размещать текстуру поперек формы или на границах формы. Текстура накладывается на фигуру, чтобы заполнить ее, когда текстура меньше, чем фигура, которую она заполняет. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Устанавливает режим обтекания и цвет, используемые для решения, как разместить текстуру поперек формы или на границах формы. Текстура накладывается на фигуру, чтобы заполнить ее, когда текстура меньше, чем фигура, которую она заполняет. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Устанавливает режим обтекания и цвет, используемые для решения, как разместить текстуру поперек формы или на границах формы. Текстура накладывается на фигуру, чтобы заполнить ее, когда текстура меньше, чем фигура, которую она заполняет. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


