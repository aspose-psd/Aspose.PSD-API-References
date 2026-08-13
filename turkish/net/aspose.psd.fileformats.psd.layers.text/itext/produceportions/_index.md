---
title: "IText.ProducePortions"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IText yöntemi. Girdi veya varsayılan parametrelerle yeni bölümler üretir"
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Giriş veya varsayılan parametrelerle yeni bölümleri üretir.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portionsOfText | String[] | Yeni [`ITextPortion`](../../itextportion/) oluşturmak için metin bölümleri. |
| stylePrototype | ITextStyle | Yeni [`ITextPortion`](../../itextportion/) içinde uygulanacak bir stil, null değilse, aksi takdirde varsayılan olur. |
| paragraphPrototype | ITextParagraph | Yeni [`ITextPortion`](../../itextportion/) içinde uygulanacak bir paragraf, null değilse, aksi takdirde varsayılan olur. |

### Dönüş Değeri

Girdi parametrelerine göre yeni bölümleri [`ITextPortion`](../../itextportion/) döndürür.

## Örnekler

Aşağıdaki örnek, Aspose.PSD içinde bir metin katmanında farklı stilleri nasıl renderleyebileceğinizi gösterir.

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

### Ayrıca Bakınız

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


