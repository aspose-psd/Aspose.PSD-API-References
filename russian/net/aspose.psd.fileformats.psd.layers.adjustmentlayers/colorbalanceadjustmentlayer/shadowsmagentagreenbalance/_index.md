---
title: "ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство ColorBalanceAdjustmentLayer. Получает или задает Shadows Magenta Green Balance"
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsmagentagreenbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance property

Получает или задает значение Shadows Magenta Green Balance.

```csharp
public short ShadowsMagentaGreenBalance { get; set; }
```

### Property Value

Shadows Magenta Green Balance.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Shadows Magenta Green Balance должно быть в диапазоне от -100 до +100. |

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


