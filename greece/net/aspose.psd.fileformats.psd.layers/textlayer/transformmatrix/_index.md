---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "TextLayer ιδιότητα. Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού"
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

Ο πίνακας μετασχηματισμού

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να λάβετε το μέγεθος γραμματοσειράς για οποιοδήποτε τμήμα κειμένου στο στρώμα κειμένου.

```csharp
[C#]

// Εξήχθη λανθασμένο μέγεθος γραμματοσειράς 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Παλαιό API (Χρήση της γραμματοσειράς της πρώτης παραγράφου)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Έλεγχος του βασικού μεγέθους γραμματοσειράς
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Έλεγχος του πραγματικού μεγέθους γραμματοσειράς
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Νέο API (Ένα επίπεδο κειμένου μπορεί να περιέχει οποιαδήποτε ποσότητα μεγεθών γραμματοσειράς)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Έλεγχος του μεγέθους γραμματοσειράς της βασικής περιοχής
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Έλεγχος του μεγέθους γραμματοσειράς της πραγματικής περιοχής
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Δείτε επίσης

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


