---
title: "IText.ProducePortions"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة IText. تُنتج الأجزاء الجديدة باستخدام المعلمات المدخلة أو الافتراضية"
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

ينتج الأجزاء الجديدة باستخدام الإدخال أو المعلمات الافتراضية.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| portionsOfText | String[] | الأجزاء النصية لإنشاء [`ITextPortion`](../../itextportion/) جديد. |
| stylePrototype | ITextStyle | نمط، إذا لم يكن فارغًا، سيُطبق في الـ [`ITextPortion`](../../itextportion/) الجديد، وإلا سيكون الافتراضي. |
| paragraphPrototype | ITextParagraph | فقرة، إذا لم تكن فارغة، ستُطبق في الـ [`ITextPortion`](../../itextportion/) الجديد، وإلا ستكون الافتراضية. |

### قيمة الإرجاع

يرجع الأجزاء الجديدة [`ITextPortion`](../../itextportion/) بناءً على المعلمات المدخلة.

## أمثلة

المثال التالي يوضح كيف يمكنك عرض أنماط مختلفة في طبقة نص واحدة في Aspose.PSD

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

### انظر أيضًا

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


