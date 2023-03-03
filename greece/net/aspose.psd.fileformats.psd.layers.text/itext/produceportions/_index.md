---
title: IText.ProducePortions
second_title: Aspose.PSD για Αναφορά API .NET
description: IText μέθοδος. Παράγει τα νέα τμήματα με εισόδου ή προεπιλεγμένες παραμέτρους.
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

Παράγει τα νέα τμήματα με εισόδου ή προεπιλεγμένες παραμέτρους.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portionsOfText | String[] | Τα τμήματα του κειμένου για δημιουργία νέων[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Ένα στυλ που, αν όχι μηδενικό, θα εφαρμοστεί στο νέο, διαφορετικά θα είναι προεπιλογή. |
| paragraphPrototype | ITextParagraph | Μια παράγραφος που, αν δεν είναι μηδενική, θα εφαρμοστεί στη νέα, διαφορετικά θα είναι προεπιλογή. |

### Επιστρεφόμενη Αξία

Επιστρέφει τις νέες μερίδες[`ITextPortion`](../../itextportion/) με βάση τις παραμέτρους εισόδου.

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να αποδώσετε διαφορετικά στυλ σε ένα επίπεδο κειμένου στο Aspose.PSD

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

    newPortions[0].Style.Underline = true; // Επεξεργασία στυλ κειμένου "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // Επεξεργασία στυλ κειμένου "2\r"
    newPortions[2].Style.FauxBold = true; // Επεξεργασία στυλ κειμένου "Έντονη"
    newPortions[3].Style.FauxItalic = true; // Επεξεργασία στυλ κειμένου "Italic\r"
    newPortions[3].Style.BaselineShift = -25; // Επεξεργασία στυλ κειμένου "Italic\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // Επεξεργασία στυλ κειμένου "Κείμενο με πεζά γράμματα"

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* συνέλευση [Aspose.PSD](../../../)


