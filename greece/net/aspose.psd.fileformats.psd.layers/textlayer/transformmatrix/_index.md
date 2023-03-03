---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD για Αναφορά API .NET
description: TextLayer ιδιοκτησία. Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού

```csharp
public double[] TransformMatrix { get; set; }
```

### Αξία περιουσίας

Ο πίνακας μετασχηματισμού

### Παραδείγματα

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

### Δείτε επίσης

* class [TextLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* συνέλευση [Aspose.PSD](../../../)


