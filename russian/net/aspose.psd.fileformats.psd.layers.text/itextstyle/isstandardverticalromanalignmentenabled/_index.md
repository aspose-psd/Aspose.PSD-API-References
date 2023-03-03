---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Справочник по Aspose.PSD для .NET API
description: ITextStyle свойство. Получает или задает стандартное вертикальное выравнивание римлянином. На основе значения ресурса BaselineDirection применяется только в том случае еслиVertical .
type: docs
weight: 170
url: /ru/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Получает или задает стандартное вертикальное выравнивание римлянином. На основе значения ресурса BaselineDirection применяется только в том случае, еслиVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Примеры

Следующий код демонстрирует поддержку нового свойства IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Следующий код демонстрирует возможность редактирования нового свойства IsStandardVerticalRomanAlignmentEnabled.
// В данный момент это не влияет на рендеринг, а только позволяет редактировать значение свойства.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Правильное чтение
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Правильное чтение
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Смотрите также

* interface [ITextStyle](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* сборка [Aspose.PSD](../../../)


