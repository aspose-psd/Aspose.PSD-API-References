---
title: "Перечисление RenderQuality"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality перечисление. Описывает качество рендеринга искажения"
type: docs
weight: 3990
url: /ru/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Описывает качество рендеринга искажения.

```csharp
public enum RenderQuality
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Turbo | `4` | Самый быстрый вариант, но качество ухудшается. |
| VeryFast | `18` | Если вам нужна скорость, это может подойти для небольших искривлений. |
| Fast | `35` | Позволяет ускорить рендеринг с небольшим падением качества. |
| Normal | `60` | Рекомендуемое значение для большинства искривлений |
| Good | `130` | Выше стандартного качества, но медленнее. Рекомендуется для сильных искажений. |
| Excellent | `260` | Самый медленный вариант. Рекомендуется для сильных искажений и высоких разрешений. |

## Примеры

Следующий код демонстрирует свойство WarpSettings.RenderQuality для настройки деформации искажения.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Он получает WarpSettings из Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Он задает размер области обработки искажения
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Здесь не должно быть ошибок
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


