---
title: FillLayer.ReplaceNonTransparentColors
second_title: Справочник по Aspose.PSD для .NET API
description: FillLayer метод. Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфаканала для сохранения гладких краев. Примечание если вы используете его на изображениях без прозрачности все цвета будут заменены одним цветом.
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorArgb | Int32 | Новое значение цвета ARGB для замены непрозрачных цветов. |

### Примеры

Следующий код демонстрирует поддержку 16-битного CMYK ColorMode и возможность рисования с помощью класса Aspose.PSD.Graphics.

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### Смотрите также

* class [FillLayer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* сборка [Aspose.PSD](../../../)


