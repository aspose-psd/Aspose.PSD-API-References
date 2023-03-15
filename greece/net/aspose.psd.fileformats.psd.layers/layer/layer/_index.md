---
title: Layer.Layer
second_title: Aspose.PSD για Αναφορά API .NET
description: Layer κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουLayer τάξη. Κατασκευαστής για lazy προετοιμασία.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`Layer`](../) τάξη. Κατασκευαστής για lazy προετοιμασία.

```csharp
public Layer()
```

### Παραδείγματα

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

### Δείτε επίσης

* class [Layer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* συνέλευση [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`Layer`](../) τάξη.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | RasterImage | Η εικόνα. |
| disposeImage | Boolean | εάν έχει οριστεί σε`αληθής` [διάθεση εικόνας]. |

### Παραδείγματα

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* συνέλευση [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`Layer`](../) τάξη.

```csharp
public Layer(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή της εικόνας |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να προσθέσετε εικόνες Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif ως επίπεδα στο PsdImage

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* συνέλευση [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`Layer`](../) κλάση από πίνακες byte.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bounds | Rectangle | Το στρώμα περιορίζεται. |
| redBytes | Byte[] | Τα κόκκινα bytes. |
| greenBytes | Byte[] | Τα πράσινα byte. |
| blueBytes | Byte[] | Τα μπλε byte. |
| name | String | Το όνομα του επιπέδου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Οι πίνακες byte δεν μπορούν να είναι κενοί or Το μήκος των πινάκων byte πρέπει να ισούται με διαστάσεις ορίων (όρια.Πλάτος * όρια.Ύψος) |

### Δείτε επίσης

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* συνέλευση [Aspose.PSD](../../../)


