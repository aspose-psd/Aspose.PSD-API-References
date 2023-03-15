---
title: Image.Load
second_title: Aspose.PSD για Αναφορά API .NET
description: Image μέθοδος. Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο.
type: docs
weight: 20
url: /el/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης. |

### Επιστρεφόμενη Αξία

Η φορτωμένη εικόνα.

### Δείτε επίσης

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο.

```csharp
public static Image Load(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου για τη φόρτωση της εικόνας από. |

### Επιστρεφόμενη Αξία

Η φορτωμένη εικόνα.

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη φόρτωση ενός υπάρχοντος αρχείου εικόνας σε μια παρουσία του Aspose.PSD.Image χρησιμοποιώντας την καθορισμένη διαδρομή αρχείου

```csharp
[C#]

//Δημιουργία παρουσίασης εικόνας και αρχικοποίηση με ένα υπάρχον αρχείο εικόνας από τη θέση του δίσκου
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    //Κάνε κάποια επεξεργασία εικόνας
}
```

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

* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Φορτώνει μια νέα εικόνα από την καθορισμένη ροή.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης. |

### Επιστρεφόμενη Αξία

Η φορτωμένη εικόνα.

### Δείτε επίσης

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

Φορτώνει μια νέα εικόνα από την καθορισμένη ροή.

```csharp
public static Image Load(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή από την οποία θα φορτωθεί η εικόνα. |

### Επιστρεφόμενη Αξία

Η φορτωμένη εικόνα.

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση αντικειμένων System.IO.Stream για τη φόρτωση ενός υπάρχοντος αρχείου εικόνας

```csharp
[C#]

//Δημιουργήστε μια παρουσία του FileStream
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Δημιουργήστε μια παρουσία της κλάσης Image και φορτώστε ένα υπάρχον αρχείο μέσω του αντικειμένου FileStream καλώντας τη μέθοδο Load
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        //Κάνε κάποια επεξεργασία εικόνας.
    }
}
```

### Δείτε επίσης

* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)


