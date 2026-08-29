---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ColorPaletteHelper. Получает цветовую палитру из растрового изображения, палитризует изображение, если у него нет палитры. Если палитра существует, она будет использована вместо выполнения вычислений"
type: docs
weight: 60
url: /ru/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Получает палитру цветов из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | RasterImage | Растровое изображение. |
| entriesCount | Int32 | Желаемое количество записей. |

### Возвращаемое значение

Цветовая палитра, начинающаяся с самых часто встречающихся цветов из *image* и содержащая *entriesCount* записей.

### См. также

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Получает палитру цветов из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Желаемое количество записей. |

### Возвращаемое значение

Цветовая палитра, начинающаяся с самых часто встречающихся цветов из *image* и содержащая *entriesCount* записей.

### См. также

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Получает палитру цветов из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Желаемое количество записей. |
| useImagePalette | Boolean | Если установлено, будет использовать собственную палитру изображения, если она доступна |

### Возвращаемое значение

Цветовая палитра, начинающаяся с самых часто встречающихся цветов из *image* и содержащая *entriesCount* записей.

### См. также

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


