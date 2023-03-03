---
title: ITextStyle.FontIndex
second_title: Справочник по Aspose.PSD для .NET API
description: ITextStyle свойство. Получает индекс шрифта.
type: docs
weight: 110
url: /ru/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
## ITextStyle.FontIndex property

Получает индекс шрифта.

```csharp
public int FontIndex { get; }
```

### Стоимость имущества

Шрифт.

### Примеры

Следующий код демонстрирует, как Aspose.PSD получает свойства встроенного форматирования текстового слоя.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Загружаем существующее изображение в экземпляр класса PsdImage
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // получает шрифты, содержащиеся в текстовом слое
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### Смотрите также

* interface [ITextStyle](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* сборка [Aspose.PSD](../../../)


