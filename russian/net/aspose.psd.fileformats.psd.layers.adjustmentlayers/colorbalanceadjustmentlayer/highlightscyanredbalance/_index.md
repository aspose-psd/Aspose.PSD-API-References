---
title: "ColorBalanceAdjustmentLayer.HighlightsCyanRedBalance"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство ColorBalanceAdjustmentLayer. Получает или задает баланс светлых тонов Cyan Red"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightscyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.HighlightsCyanRedBalance property

Получает или задает значение Highlights Cyan Red Balance.

```csharp
public short HighlightsCyanRedBalance { get; set; }
```

### Property Value

Баланс светлых тонов Cyan Red.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Баланс светлых тонов Cyan Red должен находиться в диапазоне от -100 до +100. |

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


