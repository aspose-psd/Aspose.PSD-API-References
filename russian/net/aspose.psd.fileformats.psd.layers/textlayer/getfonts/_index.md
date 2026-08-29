---
title: "TextLayer.GetFonts"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод TextLayer. Возвращает набор шрифтов текстового слоя"
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
{{< psd/tize >}}
## TextLayer.GetFonts method

Получает набор шрифтов текстового слоя.

```csharp
public TextFontInfo[] GetFonts()
```

### Возвращаемое значение

Набор шрифтов текстового слоя.

## Примеры

Следующий код демонстрирует, как Aspose.PSD получает свойства встроенного форматирования текстового слоя.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Загрузите существующее изображение в экземпляр класса PsdImage
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

### См. также

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


