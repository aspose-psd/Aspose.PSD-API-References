---
title: Class AiImage
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Ai.AiImage τάξη. The Adobe Illustrator AI Image
type: docs
weight: 1260
url: /el/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

The Adobe Illustrator (AI) Image

```csharp
public sealed class AiImage : Image
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [AiImage](aiimage/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η παλέτα αυτόματης προσαρμογής. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Λαμβάνει τα bit της εικόνας ανά πλήθος pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Παίρνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το[`Image`](../../aspose.psd/image/) δοχείο. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Λαμβάνει την ενότητα δεδομένων. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Λαμβάνει μια τιμή της μορφής αρχείου |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Λαμβάνει την ενότητα οριστικοποίησης. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Λαμβάνει την κεφαλίδα. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λήψη ή ρύθμιση της οθόνης διακοπής. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτήν τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Λαμβάνει τις ενότητες του επιπέδου. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η χρωματική παλέτα δεν χρησιμοποιείται όταν τα εικονοστοιχεία αναπαρίστανται απευθείας. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Λαμβάνει την ενότητα ρύθμισης. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Αποκτά την έκδοση του Adobe Illustrator format |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | Προσθέτει την ενότητα επιπέδου AI. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Αποθηκεύει προσωρινά τα δεδομένα και διασφαλίζει ότι δεν θα πραγματοποιηθεί πρόσθετη φόρτωση δεδομένων από το υποκείμενο[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στην καθορισμένη μορφή αρχείου που αντιπροσωπεύεται από τις περασμένες επιλογές αποθήκευσης. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές με βάση τις ρυθμίσεις του αρχικού αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρήσουμε το βάθος bit και άλλες παραμέτρους της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, αν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια αποθηκεύστε το χρησιμοποιώντας το [`Save`](../../aspose.psd/datastreamsupporter/save/) Με τη μέθοδο, θα παραχθεί η εικόνα εξόδου PNG με 8 bit ανά pixel. Για να το αποφύγετε και να αποθηκεύσετε εικόνα PNG με 1 bit ανά pixel, χρησιμοποιήστε αυτήν τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και να τις μεταφέρετε στο[`Save`](../../aspose.psd/image/save/)μέθοδος ως δεύτερη παράμετρος. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/)() | Αποθηκεύει τα δεδομένα της εικόνας στην υποκείμενη ροή. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα εικόνων. |

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

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να εξάγετε αρχείο AI σε μορφή PSD και PNG στο Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη της εξαγωγής μορφής Ai σε μορφές PSD, PNG, JPG, GIF και TIF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### Δείτε επίσης

* class [Image](../../aspose.psd/image/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* συνέλευση [Aspose.PSD](../../)


