---
title: Layer.Layer
second_title: Aspose.PSD för .NET API-referens
description: Layer byggare. Initierar en ny instans avLayer klass. Konstruktör för lat initialisering.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Initierar en ny instans av[`Layer`](../) klass. Konstruktör för lat initialisering.

```csharp
public Layer()
```

### Exempel

Följande exempel visar hur du kan rita på ett nyskapat lager om den enkla konstruktorversionen används i Aspose.PSD

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

    // rita en rektangel med pennverktyget
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // rita ytterligare en rektangel med Solid Brush i blå färg
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Se även

* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Initierar en ny instans av[`Layer`](../) class.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Bilden. |
| disposeImage | Boolean | om inställt på`Sann` [kassera bilden]. |

### Exempel

Följande kod visar förmågan att ladda JPEG/PNG/etc-bildfiler till PsdImage utan att laddas direkt.

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

### Se även

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Initierar en ny instans av[`Layer`](../) class.

```csharp
public Layer(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Bildströmmen |

### Exempel

Följande exempel visar hur du kan lägga till Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif-bilder som lager till PsdImage

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

### Se även

* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Initierar en ny instans av[`Layer`](../) klass från byte arrays.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bounds | Rectangle | Lagret avgränsar. |
| redBytes | Byte[] | De röda byten. |
| greenBytes | Byte[] | De gröna byten. |
| blueBytes | Byte[] | De blå byten. |
| name | String | Lagrets namn. |

### Undantag

| undantag | skick |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Bytematriser kan inte vara tomma eller Bytematrisernas längd måste vara lika med bounds dimensioner (bounds.Width * bounds.Height) |

### Se även

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)


