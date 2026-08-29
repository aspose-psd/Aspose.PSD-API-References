---
title: "ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство ColorBalanceAdjustmentLayer. Получает или задает Midtones Yellow Blue Balance"
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

Получает или задает значение Midtones Yellow Blue Balance.

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### Property Value

Баланс Midtones Yellow Blue.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Баланс Midtones Yellow Blue должен быть в диапазоне от -100 до +100. |

## Примеры

Следующий код демонстрирует поддержку ColorBalanceAdjustmentLayer.

```csharp
[C#]

var filePath = "ColorBalance.psd";
var outputPath = "ColorBalance_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    foreach (var layer in im.Layers)
    {
        var cbLayer = layer as ColorBalanceAdjustmentLayer;
        if (cbLayer != null)
        {
            cbLayer.ShadowsCyanRedBalance = 30;
            cbLayer.ShadowsMagentaGreenBalance = -15;
            cbLayer.ShadowsYellowBlueBalance = 40;
            cbLayer.MidtonesCyanRedBalance = -90;
            cbLayer.MidtonesMagentaGreenBalance = -25;
            cbLayer.MidtonesYellowBlueBalance = 20;
            cbLayer.HighlightsCyanRedBalance = -30;
            cbLayer.HighlightsMagentaGreenBalance = 67;
            cbLayer.HighlightsYellowBlueBalance = -95;
            cbLayer.PreserveLuminosity = true;
        }
    }

    im.Save(outputPath);
}
```

### См. также

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


