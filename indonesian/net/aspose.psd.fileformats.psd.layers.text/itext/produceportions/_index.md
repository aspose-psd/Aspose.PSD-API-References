---
title: "IText.ProducePortions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "IText metode. Menghasilkan bagian-bagian baru dengan parameter masukan atau default"
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Menghasilkan bagian baru dengan input atau parameter default.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portionsOfText | String[] | Bagian-bagian teks untuk membuat [`ITextPortion`](../../itextportion/) baru. |
| stylePrototype | ITextStyle | Gaya yang, jika tidak null, akan diterapkan pada [`ITextPortion`](../../itextportion/) baru, jika tidak maka akan menjadi default. |
| paragraphPrototype | ITextParagraph | Paragraf yang, jika tidak null, akan diterapkan pada [`ITextPortion`](../../itextportion/) baru, jika tidak maka akan menjadi default. |

### Nilai Kembalian

Mengembalikan bagian-bagian baru [`ITextPortion`](../../itextportion/) berdasarkan parameter masukan.

## Contoh

Contoh berikut menunjukkan cara Anda dapat merender gaya berbeda dalam satu lapisan teks di Aspose.PSD

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

### Lihat Juga

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


