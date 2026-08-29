---
title: "WarpSettings.GridSize"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство WarpSettings. Получает или задает размер сетки искажения. По умолчанию 1"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Получает или задает размер сетки искажения. По умолчанию 1.

```csharp
public Size GridSize { get; set; }
```

## Примеры

Следующий код демонстрирует поддержку свойства WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Получить настройки искажения
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Установить новый размер
    // Для Photoshop значение может быть от 1 до 50, и вы не можете корректно сохранить файл PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Установить допустимое значение
    warpSettings.GridSize = new Size(3, 3);

    // Отрисовать пример файла с сеткой x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### См. также

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


