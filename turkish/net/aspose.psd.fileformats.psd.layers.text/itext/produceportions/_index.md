---
title: IText.ProducePortions
second_title: Aspose.PSD for .NET API Referansı
description: IText yöntem. Yeni bölümleri girdi veya varsayılan parametrelerle üretir.
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

Yeni bölümleri girdi veya varsayılan parametrelerle üretir.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| portionsOfText | String[] | Yeni oluşturulacak metin bölümleri[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Null değilse yeni stilde uygulanacak bir stil, aksi takdirde varsayılan olacaktır. |
| paragraphPrototype | ITextParagraph | Null değilse yeni paragrafta uygulanacak bir paragraf, aksi takdirde varsayılan olacaktır. |

### Geri dönüş değeri

Yeni bölümleri döndürür[`ITextPortion`](../../itextportion/) giriş parametrelerine göre.

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de tek bir metin katmanında farklı stilleri nasıl oluşturabileceğinizi göstermektedir.

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

    newPortions[0].Style.Underline = true; // "E=mc" metin stilini düzenle
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // "2\r" metin stilini düzenle
    newPortions[2].Style.FauxBold = true; // "Kalın" metin stilini düzenle
    newPortions[3].Style.FauxItalic = true; // "İtalik\r" metin stilini düzenle
    newPortions[3].Style.BaselineShift = -25; // "İtalik\r" metin stilini düzenle
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // "Küçük harfli metin" metin stilini düzenle

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### Ayrıca bakınız

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* toplantı [Aspose.PSD](../../../)


