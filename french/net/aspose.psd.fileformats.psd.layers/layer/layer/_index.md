---
title: "Layer.Layer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur Layer. Initialise une nouvelle instance de la classe Layer. Constructeur pour l'initialisation paresseuse"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

Initialise une nouvelle instance de la classe [`Layer`](../). Constructeur pour l'initialisation paresseuse.

```csharp
public Layer()
```

## Exemples

L'exemple suivant montre comment vous pouvez dessiner sur une couche nouvellement créée si la version simple du constructeur est utilisée dans Aspose.PSD

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

    // dessinez un rectangle avec l'outil Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dessinez un autre rectangle avec Solid Brush en couleur bleue
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Initialise une nouvelle instance de la classe [`Layer`](../).

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | RasterImage | L'image. |
| disposeImage | Booléen | si défini sur `true` [dispose image]. |

## Exemples

Le code suivant démontre la capacité de charger des fichiers image JPEG/PNG/etc dans PsdImage sans chargement direct.

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

### Voir aussi

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Initialise une nouvelle instance de la classe [`Layer`](../).

```csharp
public Layer(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux d'image |

## Exemples

L'exemple suivant montre comment vous pouvez ajouter des images Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif en tant que calques à PsdImage

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

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Initialise une nouvelle instance de la classe [`Layer`](../) à partir de tableaux d'octets.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| limites | Rectangle | Les limites du calque. |
| redBytes | Byte[] | Les octets rouges. |
| greenBytes | Byte[] | Les octets verts. |
| blueBytes | Byte[] | Les octets bleus. |
| name | String | Le nom de la couche. |

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Les tableaux d'octets ne peuvent pas être vides ou la longueur des tableaux d'octets doit être égale aux dimensions des limites (bounds.Width * bounds.Height) |

### Voir aussi

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


