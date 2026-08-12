---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод FillLayer. Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа для получения плавных краев. Обратите внимание, что при использовании на изображениях без прозрачности все цвета будут заменены одним цветом."
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorArgb | Int32 | Новое значение ARGB цвета для замены непрозрачных цветов. |

## Примеры

Следующий код демонстрирует поддержку 16‑битного режима цвета CMYK и возможность рисования с использованием класса Aspose.PSD.Graphics.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### См. также

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


