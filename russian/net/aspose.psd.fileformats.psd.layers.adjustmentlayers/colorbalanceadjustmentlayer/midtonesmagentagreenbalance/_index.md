---
title: ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance
second_title: Справочник по Aspose.PSD для .NET API
description: ColorBalanceAdjustmentLayer свойство. Получает или задает средний баланс пурпурнозеленого полутона.
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance property

Получает или задает средний баланс пурпурно-зеленого полутона.

```csharp
public short MidtonesMagentaGreenBalance { get; set; }
```

### Стоимость имущества

Средние тона пурпурно-зеленого баланса.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Средние тона Пурпурный Зеленый Баланс должен находиться в диапазоне от -100 до +100. |

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


