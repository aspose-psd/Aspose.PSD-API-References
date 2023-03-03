---
title: Layer.Layer
second_title: Aspose.PSD für .NET-API-Referenz
description: Layer constructeur. Initialisiert eine neue Instanz vonLayer Klasse. Konstruktor für verzögerte Initialisierung.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Initialisiert eine neue Instanz von[`Layer`](../) Klasse. Konstruktor für verzögerte Initialisierung.

```csharp
public Layer()
```

### Beispiele

Das folgende Beispiel zeigt, wie Sie auf einer neu erstellten Ebene zeichnen können, wenn die einfache Konstruktorversion in Aspose.PSD verwendet wird

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

    // Zeichnen Sie ein Rechteck mit dem Stiftwerkzeug
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // zeichne ein weiteres Rechteck mit Solid Brush in blauer Farbe
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Siehe auch

* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Initialisiert eine neue Instanz von[`Layer`](../) Klasse.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Bild. |
| disposeImage | Boolean | wenn eingestellt`WAHR` [Bild entsorgen]. |

### Beispiele

Der folgende Code demonstriert die Fähigkeit, JPEG/PNG/etc-Bilddateien ohne direktes Laden in PsdImage zu laden.

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

### Siehe auch

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Initialisiert eine neue Instanz von[`Layer`](../) Klasse.

```csharp
public Layer(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Bildstrom |

### Beispiele

Das folgende Beispiel zeigt, wie Sie Bmp-, Jpeg-, Jpeg2000-, Png-, Psd-, Tiff- und Gif-Bilder als Ebenen zu PsdImage hinzufügen können

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

### Siehe auch

* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Initialisiert eine neue Instanz von[`Layer`](../) Klasse aus Byte-Arrays.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bounds | Rectangle | Die Schichtgrenzen. |
| redBytes | Byte[] | Die roten Bytes. |
| greenBytes | Byte[] | Die grünen Bytes. |
| blueBytes | Byte[] | Die blauen Bytes. |
| name | String | Der Ebenenname. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Byte-Arrays dürfen nicht leer sein oder Die Länge von Byte-Arrays muss den Grenzabmessungen entsprechen (bounds.Width * bounds.Height) |

### Siehe auch

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)


