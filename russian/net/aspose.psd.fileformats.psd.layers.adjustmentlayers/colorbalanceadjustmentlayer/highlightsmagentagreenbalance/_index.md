---
title: ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance
second_title: Справочник по Aspose.PSD для .NET API
description: ColorBalanceAdjustmentLayer свойство. Получает или задает баланс зеленого пурпурного для светлых участков.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance property

Получает или задает баланс зеленого пурпурного для светлых участков.

```csharp
public short HighlightsMagentaGreenBalance { get; set; }
```

### Стоимость имущества

Пурпурный баланс зеленого цвета.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Баланс зеленого пурпурного цвета светлых участков должен находиться в диапазоне от -100 до +100. |

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


