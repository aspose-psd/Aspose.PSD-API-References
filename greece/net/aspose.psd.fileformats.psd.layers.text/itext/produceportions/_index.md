---
title: "IText.ProducePortions"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "IText μέθοδος. Δημιουργεί τα νέα τμήματα με εισαγόμενες ή προεπιλεγμένες παραμέτρους"
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Παράγει τα νέα τμήματα με είσοδο ή προεπιλεγμένες παραμέτρους.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portionsOfText | String[] | Τα τμήματα κειμένου για τη δημιουργία νέου [`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Ένα στυλ που, εάν δεν είναι null, θα εφαρμοστεί στο νέο [`ITextPortion`](../../itextportion/), διαφορετικά θα είναι προεπιλογή. |
| paragraphPrototype | ITextParagraph | Μια παράγραφος που, εάν δεν είναι null, θα εφαρμοστεί στο νέο [`ITextPortion`](../../itextportion/), διαφορετικά θα είναι προεπιλογή. |

### Τιμή Επιστροφής

Επιστρέφει τα νέα τμήματα [`ITextPortion`](../../itextportion/) βάσει των εισαγόμενων παραμέτρων.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να αποδώσετε διαφορετικά στυλ σε ένα στρώμα κειμένου στο Aspose.PSD

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

### Δείτε επίσης

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


