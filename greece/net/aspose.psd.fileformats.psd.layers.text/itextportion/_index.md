---
title: Interface ITextPortion
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Text.ITextPortion διεπαφή. Διεπαφή για χειρισμό τμημάτων κειμένου
type: docs
weight: 3530
url: /el/net/aspose.psd.fileformats.psd.layers.text/itextportion/
---
## ITextPortion interface

Διεπαφή για χειρισμό τμημάτων κειμένου

```csharp
public interface ITextPortion
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Paragraph](../../aspose.psd.fileformats.psd.layers.text/itextportion/paragraph/) { get; } | Ορίζει το στυλ. |
| [Style](../../aspose.psd.fileformats.psd.layers.text/itextportion/style/) { get; } | Παίρνει το στυλ. |
| [Text](../../aspose.psd.fileformats.psd.layers.text/itextportion/text/) { get; set; } | Λαμβάνει ή ορίζει το κείμενο. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει ότι η στοίχιση κειμένου μέσω του ITextPortion για γλώσσες από δεξιά προς τα αριστερά λειτουργεί σωστά.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

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

Ο ακόλουθος κώδικας δείχνει πώς να λάβετε μέγεθος γραμματοσειράς για οποιοδήποτε τμήμα κειμένου στο επίπεδο κειμένου.

```csharp
[C#]

// Εξήχθη λάθος μέγεθος γραμματοσειράς 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Παλιό API (Χρησιμοποιώντας τη γραμματοσειρά της πρώτης παραγράφου)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Έλεγχος του βασικού μεγέθους γραμματοσειράς
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Έλεγχος πραγματικού μεγέθους γραμματοσειράς
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Νέο API (Ένα επίπεδο κειμένου μπορεί να περιέχει οποιαδήποτε ποσότητα μεγεθών γραμματοσειράς)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Έλεγχος του μεγέθους γραμματοσειράς του βασικού τμήματος
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Έλεγχος μεγέθους γραμματοσειράς πραγματικού τμήματος
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

Το ακόλουθο παράδειγμα κώδικα δείχνει τα τμήματα κειμένου επεξεργασίας και το στυλ κειμένου τους.

```csharp
[C#]

const double Tolerance = 0.0001;
var filePath = "ThreeColorsParagraphs.psd";
var outputPath = "ThreeColorsParagraph_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < im.Layers.Length; i++)
    {
        var layer = im.Layers[i] as TextLayer;

        if (layer != null)
        {
            var portions = layer.TextData.Items;

            if (portions.Length != 4)
            {
                throw new Exception();
            }

            // Έλεγχος κειμένου κάθε τμήματος
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Έλεγχος δεδομένων παραγράφων
            // Οι παράγραφοι έχουν διαφορετική αιτιολόγηση
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Όλες οι άλλες ιδιότητες της πρώτης και της δεύτερης παραγράφου είναι ίσες
            for (int j = 0; j < portions.Length; j++)
            {
                var paragraph = portions[j].Paragraph;

                if (Math.Abs(paragraph.AutoLeading - 1.2) > Tolerance ||
                    paragraph.AutoHyphenate != false ||
                    paragraph.Burasagari != false ||
                    paragraph.ConsecutiveHyphens != 8 ||
                    Math.Abs(paragraph.StartIndent) > Tolerance ||
                    Math.Abs(paragraph.EndIndent) > Tolerance ||
                    paragraph.EveryLineComposer != false ||
                    Math.Abs(paragraph.FirstLineIndent) > Tolerance ||
                    paragraph.GlyphSpacing.Length != 3 ||
                    Math.Abs(paragraph.GlyphSpacing[0] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[1] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[2] - 1) > Tolerance ||
                    paragraph.Hanging != false ||
                    paragraph.HyphenatedWordSize != 6 ||
                    paragraph.KinsokuOrder != 0 ||
                    paragraph.LetterSpacing.Length != 3 ||
                    Math.Abs(paragraph.LetterSpacing[0]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[1]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[2]) > Tolerance ||
                    paragraph.LeadingType != LeadingMode.Auto ||
                    paragraph.PreHyphen != 2 ||
                    paragraph.PostHyphen != 2 ||
                    Math.Abs(paragraph.SpaceBefore) > Tolerance ||
                    Math.Abs(paragraph.SpaceAfter) > Tolerance ||
                    paragraph.WordSpacing.Length != 3 ||
                    Math.Abs(paragraph.WordSpacing[0] - 0.8) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[1] - 1.0) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[2] - 1.33) > Tolerance ||
                    Math.Abs(paragraph.Zone - 36.0) > Tolerance)
                {
                    throw new Exception();
                }
            }

            // Έλεγχος δεδομένων στυλ
            // Τα στυλ έχουν διαφορετικά χρώματα και μέγεθος γραμματοσειράς
            if (Math.Abs(portions[0].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[1].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[2].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[3].Style.FontSize - 10) > Tolerance)
            {
                throw new Exception();
            }

            if (portions[0].Style.FillColor != Color.FromArgb(255, 145, 0, 0) ||
                portions[1].Style.FillColor != Color.FromArgb(255, 201, 128, 2) ||
                portions[2].Style.FillColor != Color.FromArgb(255, 18, 143, 4) ||
                portions[3].Style.FillColor != Color.FromArgb(255, 145, 42, 100))
            {
                throw new Exception();
            }

            for (int j = 0; j < portions.Length; j++)
            {
                var style = portions[j].Style;

                if (style.AutoLeading != true ||
                    style.HindiNumbers != false ||
                    style.Kerning != 0 ||
                    style.Leading != 0 ||
                    style.StrokeColor != Color.FromArgb(255, 175, 90, 163) ||
                    style.Tracking != 50)
                {
                    throw new Exception();
                }
            }

            // Παράδειγμα επεξεργασίας κειμένου
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Παράδειγμα αφαίρεσης τμημάτων κειμένου
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Παράδειγμα προσθήκης νέου τμήματος κειμένου
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Παράδειγμα επεξεργασίας παραγράφου και στυλ για τμήματα
            // Ορισμός σωστής αιτιολόγησης
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Διαφορετικά χρώματα για κάθε στυλ. Θα αλλάξει, αλλά η απόδοση δεν υποστηρίζεται πλήρως
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Διαφορετική γραμματοσειρά. Θα αλλάξει, αλλά η απόδοση δεν υποστηρίζεται πλήρως
            portions[0].Style.FontSize = 6;
            portions[1].Style.FontSize = 8;
            portions[2].Style.FontSize = 10;

            layer.TextData.UpdateLayerData();

            im.Save(outputPath, new PsdOptions(im));

            break;
        }
    }
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* συνέλευση [Aspose.PSD](../../)


