---
title: Class PsdOptions
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageOptions.PsdOptions τάξη. Η μορφή αρχείου psd δημιουργεί επιλογές.
type: docs
weight: 4900
url: /el/net/aspose.psd.imageoptions/psdoptions/
---
## PsdOptions class

Η μορφή αρχείου psd δημιουργεί επιλογές.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`PsdOptions` τάξη. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Αρχικοποιεί μια νέα παρουσία του`PsdOptions` τάξη. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Αρχικοποιεί μια νέα παρουσία του`PsdOptions` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των bit ανά κανάλι χρώματος. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Λαμβάνει ή ρυθμίζει τον αριθμό των καναλιών χρώματος. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία χρώματος psd. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης psd. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη γραμματοσειρά αντικατάστασης (γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε ράστερ, εάν η υπάρχουσα γραμματοσειρά επιπέδου στο αρχείο PSD δεν εμφανίζεται στο σύστημα). Για να λάβετε το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορείτε να χρησιμοποιήσετε το επόμενο απόσπασμα κώδικα : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] οικογένειες = col.Families; stringN defaultFont; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλών σελίδων |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων προόδου. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. Μπορεί να είναι PSD ή PSB. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [refresh image preview data] - επιλογή που χρησιμοποιείται για τη μεγιστοποίηση της συμβατότητας με άλλα προγράμματα προβολής εικόνων PSD. Λάβετε υπόψη ότι η σχεδίαση επιπέδων κειμένου στην τελική διάταξη δεν υποστηρίζεται για Compact Framework platform |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν - Κατάργηση του καθολικού πόρου της μηχανής κειμένου - Χρησιμοποιείται για ορισμένα αρχεία psd σε επίπεδο κειμένου, μόνο σε περίπτωση που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για απόντα επίπεδα γραμματοσειρών που σχετίζονται με επίπεδα κειμένου). Μετά τη χρήση αυτής της επιλογής, ο χρήστης πρέπει να κάνει το επόμενο που ανοίγει στο αρχείο Photoshop: Μενού "Κείμενο" -&gt; "Επεξεργασία γραμματοσειρών που λείπουν". Μετά από αυτήν τη λειτουργία, όλο το κείμενο θα εμφανιστεί ξανά. Λάβετε υπόψη ότι αυτή η λειτουργία μπορεί να προκαλέσει κάποιες τελικές αλλαγές στη διάταξη. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | Λαμβάνει ή ορίζει τους πόρους psd. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία εικόνας. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής ραστεροποίησης. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση του αρχείου psd. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | Λήψη ή ρύθμιση XMP data container |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |

### Παραδείγματα

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

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο εικόνας σε κάποια θέση δίσκου, όπως καθορίζεται από την ιδιότητα Source της παρουσίας PsdOptions. Ορίζονται πολλές ιδιότητες για την παρουσία PsdOptions πριν από τη δημιουργία της πραγματικής εικόνας. Ειδικά η ιδιότητα Source, που αναφέρεται στην πραγματική θέση του δίσκου σε αυτήν την περίπτωση.

```csharp
[C#]

//Δημιουργήστε μια παρουσία του PsdOptions και ορίστε τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του FileCreateSource και αντιστοιχίστε την ως πηγή για την παρουσία του PsdOptions
//Δεύτερη παράμετρος Boolean καθορίζει εάν το αρχείο που θα δημιουργηθεί είναι Temporal ή όχι
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Δημιουργήστε μια παρουσία της εικόνας και αρχικοποιήστε την με την παρουσία της PsdOptions καλώντας τη μέθοδο Δημιουργία
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Κάνε κάποια επεξεργασία εικόνας

    // αποθήκευση όλων των αλλαγών
    image.Save();
}
```

Το ακόλουθο παράδειγμα δείχνει ότι η ανάγνωση και η αποθήκευση των αρχείων PSD 16 bit σε κλίμακα του γκρι στα 16 bit ανά κανάλι RGB λειτουργεί σωστά και χωρίς εξαίρεση.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Εδώ δεν πρέπει να υπάρχει εξαίρεση.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Το ακόλουθο παράδειγμα δείχνει ότι η ανάγνωση και η αποθήκευση των αρχείων PSD 16 bit της κλίμακας του γκρι σε 8 bit ανά κανάλι Η κλίμακα του γκρι λειτουργεί σωστά και χωρίς εξαίρεση.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Εδώ δεν πρέπει να υπάρχει εξαίρεση.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να χρησιμοποιήσετε τη λειτουργία συνδυασμού επιπέδων PassThrough στο Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Το ακόλουθο παράδειγμα δείχνει ότι η πρόοδος μετατροπής του εγγράφου λειτουργεί σωστά και χωρίς εξαίρεση.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

Αυτό το παράδειγμα δείχνει πώς μπορείτε να φορτώσετε πληροφορίες εικονοστοιχείων σε έναν πίνακα τύπου χρώματος, να χειριστείτε τον πίνακα και να τον επαναφέρετε στην εικόνα. Για να εκτελέσετε αυτές τις λειτουργίες, αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο εικόνας (σε μορφή PSD) χρησιμοποιώντας το αντικείμενο MemoryStream.

```csharp
[C#]

//Δημιουργήστε μια παρουσία του MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Δημιουργήστε μια παρουσία του PsdOptions και ορίστε τις διάφορες ιδιότητές του, συμπεριλαμβανομένης της ιδιότητας Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Δημιουργία μιας παρουσίας εικόνας
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Λάβετε τα pixel της εικόνας καθορίζοντας την περιοχή ως όριο εικόνας
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Κάντε βρόχο πάνω από τον πίνακα και ορίζει το χρώμα του εναλλακτικού εικονοστοιχείου με ευρετήριο
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ρυθμίστε το χρώμα του εικονοστοιχείου με ευρετήριο σε κίτρινο
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Ρυθμίστε το χρώμα του εικονοστοιχείου με ευρετήριο σε μπλε
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Εφαρμογή των αλλαγών pixel στην εικόνα
        image.SavePixels(image.Bounds, pixels);

        // αποθήκευση όλων των αλλαγών.
        image.Save();
    }

    //Εγγραφή MemoryStream σε Αρχείο
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

Το ακόλουθο παράδειγμα δείχνει ότι η ανάγνωση και η αποθήκευση των αρχείων PSD 16 bit της κλίμακας του γκρι λειτουργεί σωστά και χωρίς εξαίρεση.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // Εδώ δεν πρέπει να υπάρχει εξαίρεση.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### Δείτε επίσης

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* χώρος ονομάτων [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* συνέλευση [Aspose.PSD](../../)


