---
title: IText.ProducePortions
second_title: Aspose.PSD untuk Referensi .NET API
description: IText metode. Menghasilkan bagian baru dengan input atau parameter default.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

Menghasilkan bagian baru dengan input atau parameter default.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| portionsOfText | String[] | Bagian teks yang akan dibuat baru[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Sebuah gaya yang, jika bukan nol, akan diterapkan pada yang baru, jika tidak akan menjadi default. |
| paragraphPrototype | ITextParagraph | Paragraf yang, jika bukan nol, akan diterapkan di paragraf baru, jika tidak akan menjadi default. |

### Nilai Pengembalian

Mengembalikan porsi baru[`ITextPortion`](../../itextportion/) berdasarkan parameter masukan.

### Contoh

Contoh berikut menunjukkan bagaimana Anda bisa membuat gaya yang berbeda dalam satu lapisan teks di Aspose.PSD

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

    newPortions[0].Style.Underline = true; // edit gaya teks "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // edit gaya teks "2\r"
    newPortions[2].Style.FauxBold = true; // edit gaya teks "Bold"
    newPortions[3].Style.FauxItalic = true; // edit gaya teks "Italic\r"
    newPortions[3].Style.BaselineShift = -25; // edit gaya teks "Italic\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // edit gaya teks "Teks huruf kecil"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### Lihat juga

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* perakitan [Aspose.PSD](../../../)


