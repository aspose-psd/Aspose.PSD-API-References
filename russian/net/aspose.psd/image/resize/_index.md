---
title: "Image.Resize"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Image. Изменяет размер изображения"
type: docs
weight: 200
url: /ru/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Изменяет размер изображения.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | Int32 | Новая ширина. |
| newHeight | Int32 | Новая высота. |
| resizeType | ResizeType | Тип изменения размера. |

### См. также

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Изменяет размер изображения. Используется значение по умолчанию NearestNeighbourResample.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | Int32 | Новая ширина. |
| newHeight | Int32 | Новая высота. |

## Примеры

Следующий пример демонстрирует, как изменить размер изображения PSD и результат, который мы получаем с помощью Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### См. также

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Изменяет размер изображения.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | Int32 | Новая ширина. |
| newHeight | Int32 | Новая высота. |
| настройки | ImageResizeSettings | Настройки изменения размера. |

### См. также

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


