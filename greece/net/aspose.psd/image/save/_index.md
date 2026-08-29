---
title: "Image.Save"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Image. Αποθηκεύει τα δεδομένα της εικόνας στην υποκείμενη ροή"
type: docs
weight: 240
url: /el/net/aspose.psd/image/save/
---
{{< psd/tize >}}
## Save() {#save}

Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα.

```csharp
public void Save()
```

### Δείτε επίσης

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου. |
| επιλογές | ImageOptionsBase | Οι επιλογές. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να εξάγετε αρχεία Adobe Illustrator σε μορφή PDF στο Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Το παρακάτω παράδειγμα δείχνει ότι το AsposePSD υποστηρίζει την εξαγωγή αρχείων PSB σε μορφή PSD.

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

Ο παρακάτω κώδικας αποθηκεύει το PsdImage ως έγγραφο PDF με δυνατότητα επιλογής κειμένου.

```csharp
[C#]

// Η αποθήκευση PSD σε PDF δεν παρέχει δυνατότητα επιλογής κειμένου
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

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

Το παρακάτω παράδειγμα δείχνει ότι η Στοίχιση Κειμένου μέσω ITextPortion για γλώσσες δεξιά‑προς‑αριστερά λειτουργεί σωστά.

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

Αυτό το παράδειγμα δείχνει τα απλά βήματα για Save μια Image. Για να επιδείξουμε αυτή τη λειτουργία, φορτώνουμε ένα υπάρχον αρχείο από κάποια θέση δίσκου, εκτελούμε τη λειτουργία Rotate στην Image και Save την Image σε μορφή αρχείου Jpeg χρησιμοποιώντας File Path.

```csharp
[C#]

//Δημιουργήστε μια παρουσία της κλάσης image και αρχικοποιήστε την με ένα υπάρχον αρχείο μέσω File path
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Περιστρέψτε την εικόνα κατά 180 μοίρες γύρω από τον άξονα X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Αποθηκεύστε την Image ως Jpeg στο File Path με τις προεπιλεγμένες ρυθμίσεις JpegOptions
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να αλλάξετε την ορατότητα του LayerGroup στο Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// κάντε αλλαγές στα ονόματα των επιπέδων και αποθηκεύστε το
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Απενεργοποιήστε όλα μέσα σε μια ομάδα
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να σχεδιάσετε σε ένα νεοδημιουργημένο layer εάν χρησιμοποιηθεί η απλή έκδοση του κατασκευαστή στο Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // σχεδιάστε ένα ορθογώνιο με το εργαλείο Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // σχεδιάστε ένα άλλο ορθογώνιο με Solid Brush σε μπλε χρώμα
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου. |
| επιλογές | ImageOptionsBase | Οι επιλογές. |
| boundsRectangle | Rectangle | Το ορθογώνιο ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση ως όρια πηγής. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | επιλογές |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Αποθήκευση εικόνας απέτυχε. |

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα της εικόνας. |
| optionsBase | ImageOptionsBase | Οι επιλογές αποθήκευσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Δεν είναι δυνατή η αποθήκευση στη συγκεκριμένη μορφή επειδή αυτή δεν υποστηρίζεται αυτή τη στιγμή.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Εξαγωγή εικόνας απέτυχε. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη διαδικασία αποθήκευσης μιας εικόνας σε MemoryStream. Για να επιδείξει αυτή τη λειτουργία, το παράδειγμα φορτώνει ένα υπάρχον αρχείο από κάποια θέση δίσκου, εκτελεί λειτουργία περιστροφής στην εικόνα και αποθηκεύει την εικόνα σε μορφή Gif.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Δημιουργήστε μια παρουσία της κλάσης image και αρχικοποιήστε την με ένα υπάρχον αρχείο μέσω File path
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Περιστρέψτε την εικόνα κατά 180 μοίρες γύρω από τον άξονα X
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Αποθηκεύστε την εικόνα ως PSD σε MemoryStream με τις προεπιλεγμένες ρυθμίσεις GifOptions
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα της εικόνας. |
| optionsBase | ImageOptionsBase | Οι επιλογές αποθήκευσης. |
| boundsRectangle | Rectangle | Το ορθογώνιο ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση των ορίων της πηγής. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Δεν είναι δυνατή η αποθήκευση στη συγκεκριμένη μορφή επειδή αυτή δεν υποστηρίζεται αυτή τη στιγμή.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Εξαγωγή εικόνας απέτυχε. |

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


