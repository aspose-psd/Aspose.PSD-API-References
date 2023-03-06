---
title: Layer.Layer
second_title: Aspose.PSD voor .NET API-referentie
description: Layer constructeur. Initialiseert een nieuw exemplaar van hetLayer klas. Constructor voor luie initialisatie.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Initialiseert een nieuw exemplaar van het[`Layer`](../) klas. Constructor voor luie initialisatie.

```csharp
public Layer()
```

### Voorbeelden

Het volgende voorbeeld laat zien hoe u kunt tekenen op een nieuw gemaakte laag als de eenvoudige constructorversie wordt gebruikt in Aspose.PSD

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

    // teken een rechthoek met het gereedschap Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // teken nog een rechthoek met Solid Brush in blauwe kleur
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Zie ook

* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`Layer`](../) klasse.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | RasterImage | De afbeelding. |
| disposeImage | Boolean | indien ingesteld op`WAAR` [verwijder afbeelding]. |

### Voorbeelden

De volgende code demonstreert de mogelijkheid om JPEG/PNG/etc-afbeeldingsbestanden naar PsdImage te laden zonder direct te laden.

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

### Zie ook

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Initialiseert een nieuw exemplaar van het[`Layer`](../) klasse.

```csharp
public Layer(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De beeldstroom |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u Bmp-, Jpeg-, Jpeg2000-, Png-, Psd-, Tiff-, Gif-afbeeldingen als lagen kunt toevoegen aan PsdImage

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

### Zie ook

* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Initialiseert een nieuw exemplaar van het[`Layer`](../) klasse uit byte-arrays.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bounds | Rectangle | De laaggrenzen. |
| redBytes | Byte[] | De rode bytes. |
| greenBytes | Byte[] | De groene bytes. |
| blueBytes | Byte[] | De blauwe bytes. |
| name | String | De naam van de laag. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Byte-arrays mogen niet leeg zijn or Byte-arrays lengte moet gelijk zijn aan grensafmetingen (bounds.Width * bounds.Height) |

### Zie ook

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)


