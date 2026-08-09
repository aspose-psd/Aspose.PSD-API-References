---
title: "IText.ProducePortions"
second_title: "Aspose.PSD for .NET API 参考"
description: "IText 方法。使用输入或默认参数生成新的部分"
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

使用输入或默认参数生成新的片段。

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| portionsOfText | String[] | 用于创建新[`ITextPortion`](../../itextportion/)的文本片段。 |
| stylePrototype | ITextStyle | 如果不为 null，则会在新[`ITextPortion`](../../itextportion/)中应用的样式，否则将使用默认值。 |
| paragraphPrototype | ITextParagraph | 如果不为 null，则会在新[`ITextPortion`](../../itextportion/)中应用的段落，否则将使用默认值。 |

### 返回值

返回基于输入参数的新[`ITextPortion`](../../itextportion/)片段。

## 示例

以下示例演示了如何在 Aspose.PSD 中的一个文本层中渲染不同的样式。

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

### 另请参阅

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


