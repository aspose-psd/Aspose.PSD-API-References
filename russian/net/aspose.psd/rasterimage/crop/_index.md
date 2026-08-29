---
title: "RasterImage.Crop"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RasterImage. Обрезает указанный прямоугольник."
type: docs
weight: 240
url: /ru/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

Обрезает указанный прямоугольник.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| прямоугольник | Rectangle | Прямоугольник. |

## Примеры

Следующий пример кода показывает, как обрезать изображение и сохранить его.

```csharp
[C#]

// Реализуйте корректный метод Crop для файлов PSD.
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

### См. также

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Обрезать изображение со смещениями.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | Int32 | Левый сдвиг. |
| rightShift | Int32 | Правый сдвиг. |
| topShift | Int32 | Верхний сдвиг. |
| bottomShift | Int32 | Нижний сдвиг. |

### См. также

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


