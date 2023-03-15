---
title: Class PdfOptions
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageOptions.PdfOptions τάξη. Οι επιλογές PDF.
type: docs
weight: 4870
url: /el/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

Οι επιλογές PDF.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη γραμματοσειρά αντικατάστασης (γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε ράστερ, εάν η υπάρχουσα γραμματοσειρά επιπέδου στο αρχείο PSD δεν εμφανίζεται στο σύστημα). Για να λάβετε το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορείτε να χρησιμοποιήσετε το επόμενο απόσπασμα κώδικα : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] οικογένειες = col.Families; stringN defaultFont; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλών σελίδων |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος της σελίδας. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | Οι επιλογές του πυρήνα PDF |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Λαμβάνει ή ορίζει μεταδεδομένα για το έγγραφο. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων προόδου. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία εικόνας. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής ραστεροποίησης. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει το κοντέινερ μεταδεδομένων XMP. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να εξάγετε αρχεία Adobe Illustrator σε μορφή PDF στο Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Το ακόλουθο παράδειγμα δείχνει ότι το AsposePSD υποστηρίζει τα αρχεία PSB που εξάγονται σε μορφή PSD.

```csharp
[C#]

// Υποστήριξη αποθήκευσης PSB ως PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Ο ακόλουθος κώδικας αποθηκεύει το PsdImage ως έγγραφο PDF με επιλέξιμο κείμενο.

```csharp
[C#]

// Η αποθήκευση PSD σε PDF δεν παρέχει επιλέξιμο κείμενο
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη της εξαγωγής PsdImage σε μορφή Pdf.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* χώρος ονομάτων [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* συνέλευση [Aspose.PSD](../../)


