---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство ITextStyle. Возвращает или задает стандартное вертикальное римское выравнивание. Это основано на значении ресурса BaselineDirection и применяется только при вертикальной ориентации текста."
type: docs
weight: 170
url: /ru/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Получает или задает стандартное вертикальное римское выравнивание. Это, основанное на значении ресурса BaselineDirection, применяется только при вертикальной ориентации текста.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## Примеры

Следующий код демонстрирует поддержку нового свойства IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Следующий код демонстрирует возможность редактировать новое свойство IsStandardVerticalRomanAlignmentEnabled.
// Это не влияет на рендеринг в данный момент, а только позволяет изменить значение свойства.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Корректное чтение
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
        // Корректное чтение
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### См. также

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


