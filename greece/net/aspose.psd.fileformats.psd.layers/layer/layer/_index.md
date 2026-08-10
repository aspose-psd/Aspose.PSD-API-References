---
title: "Layer.Layer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής Layer. Αρχικοποιεί μια νέα παρουσία της κλάσης Layer. Κατασκευαστής για lazy initialization"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Layer`](../). Κατασκευαστής για lazy initialization.

```csharp
public Layer()
```

## Παραδείγματα

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

### Δείτε επίσης

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Layer`](../).

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | RasterImage | Η εικόνα. |
| disposeImage | Boolean | αν οριστεί σε `true` [dispose image]. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα φόρτωσης αρχείων εικόνας JPEG/PNG/κτλ στο PsdImage χωρίς άμεση φόρτωση.

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Layer`](../).

```csharp
public Layer(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή εικόνας |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να προσθέσετε εικόνες Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif ως στρώσεις στο PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`Layer`](../) από πίνακες byte.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όρια | Rectangle | Τα όρια του στρώματος. |
| redBytes | Byte[] | Τα κόκκινα bytes. |
| greenBytes | Byte[] | Τα πράσινα bytes. |
| blueBytes | Byte[] | Τα μπλε bytes. |
| όνομα | String | Το όνομα του στρώματος. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Τα Byte arrays δεν μπορούν να είναι κενά ή το μήκος των Byte arrays πρέπει να ισούται με τις διαστάσεις των bounds (bounds.Width * bounds.Height) |

### Δείτε επίσης

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


