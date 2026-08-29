---
title: "TextLayer.TransformMatrix"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство TextLayer. Получает или задает матрицу преобразования"
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

Получает или задает матрицу преобразования

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

Матрица преобразования

## Примеры

В следующем коде показано, как получить размер шрифта для любой части текста в текстовом слое.

```csharp
[C#]

// Получен неправильный размер шрифта 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Старый API (используется шрифт первого абзаца)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Проверка базового размера шрифта
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Проверка реального размера шрифта
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Новый API (один слой текста может содержать любое количество размеров шрифтов)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Проверка размера шрифта базовой части
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Проверка размера шрифта реальной части
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### См. также

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


