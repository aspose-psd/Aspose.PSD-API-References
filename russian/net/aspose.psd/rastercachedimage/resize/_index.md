---
title: RasterCachedImage.Resize
second_title: Справочник по Aspose.PSD для .NET API
description: RasterCachedImage метод. Изменяет размер изображения.
type: docs
weight: 120
url: /ru/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Изменяет размер изображения.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | Int32 | Новая ширина. |
| newHeight | Int32 | Новая высота. |
| resizeType | ResizeType | Тип изменения размера. |

### Примеры

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Смотрите также

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* пространство имен [Aspose.PSD](../../rastercachedimage/)
* сборка [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Изменяет размер изображения.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | Int32 | Новая ширина. |
| newHeight | Int32 | Новая высота. |
| settings | ImageResizeSettings | Настройки изменения размера. |

### Смотрите также

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* пространство имен [Aspose.PSD](../../rastercachedimage/)
* сборка [Aspose.PSD](../../../)


