---
title: "IText.ProducePortions"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод IText. Создаёт новые части с входными или параметрами по умолчанию"
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Создает новые части с входными или параметрами по умолчанию.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| portionsOfText | String[] | Части текста для создания новых [`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Стиль, который, если не null, будет применён к новому [`ITextPortion`](../../itextportion/), иначе будет использоваться значение по умолчанию. |
| paragraphPrototype | ITextParagraph | Абзац, который, если не null, будет применён к новому [`ITextPortion`](../../itextportion/), иначе будет использоваться значение по умолчанию. |

### Возвращаемое значение

Возвращает новые части [`ITextPortion`](../../itextportion/) на основе входных параметров.

## Примеры

Следующий пример демонстрирует, как можно отрисовать разные стили в одном текстовом слое в Aspose.PSD

```csharp
[C#]

string sourceFile = "text212.psd";
string etalonFile = "Output_text212.psd";
string outputFile = "Output_text212.psd";

using (var img = (PsdImage)Image.Load(sourceFile))
{
    TextLayer textLayer = (TextLayer)img.Layers[1];
    IText textData = textLayer.TextData;
    ITextStyle defaultStyle = textData.ProducePortion().Style;
    ITextParagraph defaultParagraph = textData.ProducePortion().Paragraph;
    defaultStyle.FillColor = Color.DimGray;
    defaultStyle.FontSize = 51;

    textData.Items[1].Style.Strikethrough = true;

    ITextPortion[] newPortions = textData.ProducePortions(
        new string[]
        {
          "E=mc", "2\r", "Bold", "Italic\r",
          "Lowercasetext"
        },
        defaultStyle,
        defaultParagraph);

    newPortions[0].Style.Underline = true; // edit text style "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // edit text style "2\r"
    newPortions[2].Style.FauxBold = true; // edit text style "Bold"
    newPortions[3].Style.FauxItalic = true; // edit text style "Italic\r"
    newPortions[3].Style.BaselineShift = -25; // edit text style "Italic\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // edit text style "Lowercasetext"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### См. также

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


