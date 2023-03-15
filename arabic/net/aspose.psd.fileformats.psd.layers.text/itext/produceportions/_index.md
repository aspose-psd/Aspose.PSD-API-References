---
title: IText.ProducePortions
second_title: Aspose.PSD لمرجع .NET API
description: IText طريقة. ينتج الأجزاء الجديدة بمدخلات أو معلمات افتراضية.
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

ينتج الأجزاء الجديدة بمدخلات أو معلمات افتراضية.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| portionsOfText | String[] | أجزاء النص لإنشاء جديد[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | نمط ، إن لم يكن فارغًا ، سيتم تطبيقه في الملف الجديد، وإلا سيكون الافتراضي. |
| paragraphPrototype | ITextParagraph | فقرة ، إن لم تكن لاغية ، سيتم تطبيقها في الجديد، وإلا سيكون الافتراضي. |

### قيمة الإرجاع

إرجاع الأجزاء الجديدة[`ITextPortion`](../../itextportion/) بناءً على معلمات الإدخال.

### أمثلة

يوضح المثال التالي كيف يمكنك عرض أنماط مختلفة في طبقة نص واحدة في Aspose.PSD

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

    newPortions[0].Style.Underline = true; // تحرير نمط النص "E = mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // تحرير نمط النص "2 \ r"
    newPortions[2].Style.FauxBold = true; // تحرير نمط النص "غامق"
    newPortions[3].Style.FauxItalic = true; // تحرير نمط النص "مائل \ r"
    newPortions[3].Style.BaselineShift = -25; // تحرير نمط النص "مائل \ r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // تحرير نمط النص "النص السفلي"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### أنظر أيضا

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* المجسم [Aspose.PSD](../../../)


