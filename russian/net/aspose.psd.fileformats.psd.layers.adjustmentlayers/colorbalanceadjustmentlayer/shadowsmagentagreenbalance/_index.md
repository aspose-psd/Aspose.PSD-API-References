---
title: ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance
second_title: Справочник по Aspose.PSD для .NET API
description: ColorBalanceAdjustmentLayer свойство. Получает или задает баланс зеленого пурпурного для теней.
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance property

Получает или задает баланс зеленого пурпурного для теней.

```csharp
public short ShadowsMagentaGreenBalance { get; set; }
```

### Стоимость имущества

Тени Пурпурно-зеленый баланс.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Shadows Magenta Green Balance должен находиться в диапазоне от -100 до +100. |

### Примеры

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

### Смотрите также

* class [ColorBalanceAdjustmentLayer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* сборка [Aspose.PSD](../../../)


