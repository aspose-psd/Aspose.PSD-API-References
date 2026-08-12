---
title: "Перечисление WarpStyles"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles. Типы поддерживаемых стилей искажения"
type: docs
weight: 4020
url: /ru/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Типы поддерживаемых стилей искажения.

```csharp
public enum WarpStyles
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Стиль устанавливается, когда слой без деформации |
| Custom | `1` | Стиль со свободным перемещением точек |
| Arc | `2` | Стиль искажения «Дуга» |
| ArcUpper | `3` | Стиль искажения «Верхняя дуга» |
| ArcLower | `4` | Стиль искажения «Нижняя дуга» |
| Arch | `5` | Стиль искажения «Арка» |
| Bulge | `6` | Стиль искажения «Выпуклость» |
| Flag | `7` | Стиль искажения «Флаг» |
| Fish | `8` | Стиль искажения «Рыба» |
| Rise | `9` | Стиль искажения «Подъём» |
| Wave | `10` | Стиль искажения «Волна» |
| Twist | `11` | Тип искажения «Вихрь» |
| Squeeze | `12` | Тип искажения «Сжатие» |
| Inflate | `13` | Тип деформации Inflate |

## Примеры

Следующий код демонстрирует, как управлять WarpSettings для выполнения трансформации искажения на SmartObjectLayer и TexLayer.

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


