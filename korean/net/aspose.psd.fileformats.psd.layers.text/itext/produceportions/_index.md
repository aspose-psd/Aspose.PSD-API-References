---
title: IText.ProducePortions
second_title: .NET API 참조용 Aspose.PSD
description: IText 방법. 입력 또는 기본 매개변수로 새 부분을 생성합니다.
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

입력 또는 기본 매개변수로 새 부분을 생성합니다.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| portionsOfText | String[] | 새로 만들 텍스트 부분[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | null이 아닌 경우 새 항목에 적용되는 스타일그렇지 않으면 기본값이 됩니다. |
| paragraphPrototype | ITextParagraph | null이 아닌 경우 새 항목에 적용될 단락그렇지 않으면 기본값이 됩니다. |

### 반환 값

새 부분을 반환합니다.[`ITextPortion`](../../itextportion/) 입력 매개변수를 기반으로 합니다.

### 예

다음 예제는 Aspose.PSD의 하나의 텍스트 레이어에서 다양한 스타일을 렌더링하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "text212.psd";
string etalonFile = "Ethalon_text212.psd";
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

    newPortions[0].Style.Underline = true; // 텍스트 스타일 편집 "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // 텍스트 스타일 "2\r" 편집
    newPortions[2].Style.FauxBold = true; // 텍스트 스타일 "Bold" 편집
    newPortions[3].Style.FauxItalic = true; // 텍스트 스타일 편집 "Italic\r"
    newPortions[3].Style.BaselineShift = -25; // 텍스트 스타일 편집 "Italic\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // 텍스트 스타일 편집 "Lowercasetext"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### 또한보십시오

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* 집회 [Aspose.PSD](../../../)


