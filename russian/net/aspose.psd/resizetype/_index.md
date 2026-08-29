---
title: "Перечисление ResizeType"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.ResizeType. Указывает тип изменения размера."
type: docs
weight: 5870
url: /ru/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Указывает тип изменения размера.

```csharp
public enum ResizeType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Пиксели не сохраняются во время операции изменения размера. |
| LeftTopToLeftTop | `1` | Левая верхняя точка нового изображения будет совпадать с левой верхней точкой оригинального изображения. При необходимости будет выполнено обрезание. |
| RightTopToRightTop | `2` | Правая верхняя точка нового изображения будет совпадать с правой верхней точкой оригинального изображения. При необходимости будет выполнено обрезание. |
| RightBottomToRightBottom | `3` | Правая нижняя точка нового изображения будет совпадать с правой нижней точкой оригинального изображения. При необходимости будет выполнено обрезание. |
| LeftBottomToLeftBottom | `4` | Левая нижняя точка нового изображения будет совпадать с левой нижней точкой оригинального изображения. Обрезка будет выполнена при необходимости. |
| CenterToCenter | `5` | Центр нового изображения будет совпадать с центром оригинального изображения. Обрезка будет выполнена при необходимости. |
| LanczosResample | `6` | Пересэмплирование с использованием алгоритма Lanczos с a=3. |
| NearestNeighbourResample | `7` | Пересэмплирование с использованием алгоритма ближайшего соседа. |
| AdaptiveResample | `8` | Пересэмплирование с использованием адаптивного алгоритма, основанного на взвешенной и смешанной рациональной функции и алгоритмах интерполяции Lanczos3. |
| BilinearResample | `9` | Пересэмплирование с использованием билинейной интерполяции. Предварительная фильтрация изображения допускается для удаления шума перед пересэмплированием, при необходимости. |
| HighQualityResample | `10` | Высококачественное пересэмплирование |
| CatmullRom | `11` | Метод кубической интерполяции Catmull-Rom. |
| CubicConvolution | `12` | Метод кубической интерполяции Cubic Convolution |
| CubicBSpline | `13` | Метод кубической интерполяции CubicBSpline |
| Mitchell | `14` | Метод кубической интерполяции Mitchell |
| SinC | `15` | Метод кубической интерполяции Sinc (Lanczos3) |
| Bell | `16` | Метод интерполяции Bell |

## Примеры

Следующий код демонстрирует, как изменить размер изображения с новым типом изменения размера SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Следующий код демонстрирует, как изменить размер изображения с новым типом изменения размера Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Следующий код демонстрирует, как изменить размер изображения с новым типом изменения размера Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Следующий код демонстрирует, как изменить размер изображения с новым типом изменения размера CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Следующий код демонстрирует, как изменить размер изображения с новым типом изменения размера CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Следующий код демонстрирует, как изменить размер изображения с новым типом изменения размера CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


