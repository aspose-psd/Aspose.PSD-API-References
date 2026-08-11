---
title: "IText.ProducePortions"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "IText 메서드. 입력 또는 기본 매개변수로 새로운 부분들을 생성합니다"
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

입력 매개변수 또는 기본 매개변수로 새로운 부분들을 생성합니다.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portionsOfText | String[] | 새로운 [`ITextPortion`](../../itextportion/)을 만들기 위한 텍스트 부분들. |
| stylePrototype | ITextStyle | 새로운 [`ITextPortion`](../../itextportion/)에 적용될 스타일이며, null이 아니면 적용되고, 그렇지 않으면 기본값이 됩니다. |
| paragraphPrototype | ITextParagraph | 새로운 [`ITextPortion`](../../itextportion/)에 적용될 단락이며, null이 아니면 적용되고, 그렇지 않으면 기본값이 됩니다. |

### 반환 값

입력 매개변수를 기반으로 새로운 [`ITextPortion`](../../itextportion/) 부분들을 반환합니다.

## 예제

다음 예제는 Aspose.PSD에서 하나의 텍스트 레이어에 서로 다른 스타일을 렌더링하는 방법을 보여줍니다.

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

### 또 보기

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


