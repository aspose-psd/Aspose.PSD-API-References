---
title: Image.Save
second_title: Aspose.PSD για Αναφορά API .NET
description: Image μέθοδος. Αποθηκεύει τα δεδομένα της εικόνας στην υποκείμενη ροή.
type: docs
weight: 230
url: /el/net/aspose.psd/image/save/
---
## Save() {#save}

Αποθηκεύει τα δεδομένα της εικόνας στην υποκείμενη ροή.

```csharp
public void Save()
```

### Δείτε επίσης

* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου. |
| options | ImageOptionsBase | Οι επιλογές. |

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

Αυτό το παράδειγμα δείχνει τα απλά βήματα για την αποθήκευση μιας εικόνας. Για να δείξουμε αυτήν τη λειτουργία, φορτώνουμε ένα υπάρχον αρχείο από κάποια θέση δίσκου, εκτελούμε τη λειτουργία περιστροφής στην εικόνα και αποθηκεύουμε την εικόνα σε μορφή αρχείου Jpeg χρησιμοποιώντας Διαδρομή αρχείου

```csharp
[C#]

//Δημιουργήστε μια παρουσία κλάσης εικόνας και αρχικοποιήστε την με ένα υπάρχον αρχείο μέσω της διαδρομής αρχείου
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Περιστροφή της εικόνας κατά 180 μοίρες γύρω από τον άξονα Χ
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Αποθηκεύστε την εικόνα ως Jpeg στη διαδρομή αρχείου με τις προεπιλεγμένες ρυθμίσεις JpegOptions
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να αλλάξετε την ορατότητα LayerGroup στο Aspose.PSD

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

        // Απενεργοποιήστε τα πάντα μέσα σε μια ομάδα
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να σχεδιάσετε σε ένα επίπεδο που δημιουργήθηκε πρόσφατα εάν χρησιμοποιείται η απλή έκδοση κατασκευαστή στο Aspose.PSD

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

    // σχεδιάστε ένα ορθογώνιο με το εργαλείο στυλό
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // σχεδιάστε ένα άλλο ορθογώνιο με το Solid Brush σε μπλε χρώμα
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου. |
| options | ImageOptionsBase | Οι επιλογές. |
| boundsRectangle | Rectangle | Η εικόνα προορισμού περιορίζει το ορθογώνιο. Ρυθμίστε το κενό ορθογώνιο για όρια χρήσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | επιλογές |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Η αποθήκευση εικόνας απέτυχε. |

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή στην οποία αποθηκεύονται τα δεδομένα της εικόνας. |
| optionsBase | ImageOptionsBase | Οι επιλογές αποθήκευσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | επιλογές Βάση |
| ArgumentException | Δεν είναι δυνατή η αποθήκευση στην καθορισμένη μορφή, καθώς δεν υποστηρίζεται αυτήν τη στιγμή.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Η εξαγωγή εικόνας απέτυχε. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη διαδικασία αποθήκευσης μιας εικόνας στο MemoryStream. Για την επίδειξη αυτής της λειτουργίας, το παράδειγμα φορτώνει ένα υπάρχον αρχείο από κάποια θέση δίσκου, εκτελεί τη λειτουργία Περιστροφή στην εικόνα και Αποθήκευση της εικόνας σε μορφή Gif

```csharp
[C#]

//Δημιουργήστε μια παρουσία του MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Δημιουργήστε μια παρουσία κλάσης εικόνας και αρχικοποιήστε την με ένα υπάρχον αρχείο μέσω της διαδρομής αρχείου
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Περιστροφή της εικόνας κατά 180 μοίρες γύρω από τον άξονα Χ
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Αποθηκεύστε την εικόνα ως PSD στο MemoryStream με τις προεπιλεγμένες ρυθμίσεις GifOptions
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή στην οποία αποθηκεύονται τα δεδομένα της εικόνας. |
| optionsBase | ImageOptionsBase | Οι επιλογές αποθήκευσης. |
| boundsRectangle | Rectangle | Η εικόνα προορισμού περιορίζει το ορθογώνιο. Ορίστε το κενό ορθογώνιο για χρήση ορίων πηγής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | επιλογές Βάση |
| ArgumentException | Δεν είναι δυνατή η αποθήκευση στην καθορισμένη μορφή, καθώς δεν υποστηρίζεται αυτήν τη στιγμή.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Η εξαγωγή εικόνας απέτυχε. |

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)


