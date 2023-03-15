---
title: RasterImage.Crop
second_title: Справочник по Aspose.PSD для .NET API
description: RasterImage метод. Обрезает указанный прямоугольник.
type: docs
weight: 240
url: /ru/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Обрезает указанный прямоугольник.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | Rectangle | Прямоугольник. |

### Примеры

В следующем примере кода показано, как обрезать изображение и сохранить его.

```csharp
[C#]

// Реализовать правильный метод Crop для файлов PSD.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Смотрите также

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* пространство имен [Aspose.PSD](../../rasterimage/)
* сборка [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Обрезать изображение со сдвигами.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | Int32 | Левый сдвиг. |
| rightShift | Int32 | Правильный сдвиг. |
| topShift | Int32 | Верхняя смена. |
| bottomShift | Int32 | Нижний сдвиг. |

### Смотрите также

* class [RasterImage](../)
* пространство имен [Aspose.PSD](../../rasterimage/)
* сборка [Aspose.PSD](../../../)


