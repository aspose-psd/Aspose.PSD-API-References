---
title: "Κλάση PsdOptions"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.ImageOptions.PsdOptions. Οι επιλογές δημιουργίας μορφής αρχείου psd."
type: docs
weight: 5390
url: /el/net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

Οι επιλογές δημιουργίας μορφής αρχείου psd.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdOptions`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα του φόντου. Μπορεί να φαίνεται κάτω από διαφανή αντικείμενα. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των δυαδικών ψηφίων ανά κανάλι χρώματος. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των καναλιών χρώματος. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία χρώματος του psd. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης του psd. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλαπλών σελίδων. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. Μπορεί να είναι PSD ή PSB. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [refresh image preview data] - επιλογή που χρησιμοποιείται για μεγιστοποίηση της συμβατότητας με άλλους προβολείς εικόνων PSD. Παρακαλώ σημειώστε ότι η σχεδίαση των στρωμάτων κειμένου στην τελική διάταξη δεν υποστηρίζεται για την πλατφόρμα Compact Framework. |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν - Αφαίρεση του παγκόσμιου πόρου μηχανής κειμένου - Χρησιμοποιείται για ορισμένα αρχεία psd με στρώματα κειμένου, μόνο στην περίπτωση που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώματα κειμένου με απουσία γραμματοσειρών). Μετά τη χρήση αυτής της επιλογής, ο χρήστης πρέπει να εκτελέσει τα εξής στο αρχείο που άνοιξε στο Photoshop: Μενού "Text" -> "Process absent fonts". Μετά από αυτή τη λειτουργία, όλο το κείμενο θα εμφανιστεί ξανά. Παρακαλώ σημειώστε ότι αυτή η λειτουργία μπορεί να προκαλέσει κάποιες αλλαγές στην τελική διάταξη. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | Λαμβάνει ή ορίζει τους πόρους psd. Εάν η τιμή: NULL - τότε αποθηκεύει τους αρχικούς ImageResources (προεπιλεγμένη συμπεριφορά) Not Empty - τότε αποθηκεύει τους πόρους που περάστηκαν σε αυτή την ιδιότητα + [required resources] Empty - τότε αποθηκεύονται μόνο [required resources]. Απαιτούμενοι πόροι: ResolutionInfoResource, XmpResource |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [update metadata]. Εάν η τιμή είναι true, τα μεταδεδομένα θα ενημερωθούν κατά την αποθήκευση μιας εικόνας. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση του αρχείου psd. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | Λάβετε ή ορίστε το δοχείο δεδομένων XMP. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να εξάγετε αρχείο AI σε μορφή PSD και PNG στο Aspose.PSD

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

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο Image σε κάποια θέση δίσκου όπως καθορίζεται από την ιδιότητα Source του αντικειμένου PsdOptions. Πολλές ιδιότητες του αντικειμένου PsdOptions ορίζονται πριν δημιουργηθεί η πραγματική εικόνα. Ιδιαίτερα η ιδιότητα Source, που αναφέρεται στην πραγματική θέση δίσκου σε αυτή την περίπτωση.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του PsdOptions και ορίστε τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε ένα στιγμιότυπο του FileCreateSource και αναθέστε το ως Source για το στιγμιότυπο του PsdOptions
//Η δεύτερη παράμετρος Boolean καθορίζει εάν το αρχείο που θα δημιουργηθεί είναι IsTemporal ή όχι
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Δημιουργήστε ένα στιγμιότυπο του Image και αρχικοποιήστε το με το στιγμιότυπο του PsdOptions καλώντας τη μέθοδο Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //κάντε κάποια επεξεργασία εικόνας

    // αποθηκεύστε όλες τις αλλαγές
    image.Save();
}
```

Το παρακάτω παράδειγμα δείχνει ότι η ανάγνωση και η αποθήκευση των αρχείων Grayscale 16 bit PSD σε 16bit ανά κανάλι RGB λειτουργεί σωστά και χωρίς εξαίρεση.

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

Το παρακάτω παράδειγμα δείχνει ότι η ανάγνωση και η αποθήκευση των αρχείων Grayscale 16 bit PSD σε 8 bit ανά κανάλι Grayscale λειτουργεί σωστά και χωρίς εξαίρεση.

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

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να χρησιμοποιήσετε τη λειτουργία ανάμειξης στρώματος PassThrough στο Aspose.PSD

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

Το παρακάτω παράδειγμα δείχνει ότι η πρόοδος μετατροπής εγγράφου λειτουργεί σωστά και χωρίς εξαίρεση.

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

Αυτό το παράδειγμα δείχνει πώς να φορτώνει πληροφορίες Pixel σε έναν Πίνακα τύπου Color, να επεξεργάζεται τον πίνακα και να τον επαναφέρει στην εικόνα. Για την εκτέλεση αυτών των λειτουργιών, αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο Image (σε μορφή PSD) χρησιμοποιώντας το αντικείμενο MemoryStream.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Δημιουργήστε ένα στιγμιότυπο του PsdOptions και ορίστε τις διάφορες ιδιότητές του, συμπεριλαμβανομένης της ιδιότητας Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Δημιουργήστε ένα στιγμιότυπο του Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Αποκτήστε τα pixel της εικόνας καθορίζοντας την περιοχή ως όριο της εικόνας
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Επανάληψη πάνω στον πίνακα και ορίζει το χρώμα του εναλλακτικού ευρετηριασμένου pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ορίστε το χρώμα του ευρετηριασμένου pixel σε κίτρινο
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Ορίστε το χρώμα του ευρετηριασμένου pixel σε μπλε
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Εφαρμόστε τις αλλαγές pixel στην εικόνα
        image.SavePixels(image.Bounds, pixels);

        // αποθηκεύστε όλες τις αλλαγές.
        image.Save();
    }

    //Γράψτε το MemoryStream σε αρχείο
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

Το παρακάτω παράδειγμα δείχνει ότι η ανάγνωση και η αποθήκευση των αρχείων Grayscale 16-bit PSD λειτουργούν σωστά και χωρίς εξαίρεση.

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
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


