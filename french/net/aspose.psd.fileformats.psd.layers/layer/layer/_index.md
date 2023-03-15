---
title: Layer.Layer
second_title: Référence de l'API Aspose.PSD pour .NET
description: Layer constructeur. Initialise une nouvelle instance duLayer classe. Constructeur pour linitialisation paresseuse.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Initialise une nouvelle instance du[`Layer`](../) classe. Constructeur pour l'initialisation paresseuse.

```csharp
public Layer()
```

### Exemples

L'exemple suivant montre comment vous pouvez dessiner sur un calque nouvellement créé si la version du constructeur simple est utilisée dans Aspose.PSD

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

    // dessine un rectangle avec l'outil Plume
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dessine un autre rectangle avec Solid Brush de couleur bleue
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Voir également

* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Initialise une nouvelle instance du[`Layer`](../) classe.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image. |
| disposeImage | Boolean | si réglé sur`vrai` [disposer image]. |

### Exemples

Le code suivant montre la possibilité de charger des fichiers image JPEG/PNG/etc dans PsdImage sans chargement direct.

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

### Voir également

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Initialise une nouvelle instance du[`Layer`](../) classe.

```csharp
public Layer(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux d'images |

### Exemples

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

### Voir également

* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Initialise une nouvelle instance du[`Layer`](../) classe à partir de tableaux d'octets.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| bounds | Rectangle | La couche délimite. |
| redBytes | Byte[] | Les octets rouges. |
| greenBytes | Byte[] | Les octets verts. |
| blueBytes | Byte[] | Les octets bleus. |
| name | String | Le nom de la couche. |

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Les tableaux d'octets ne peuvent pas être vides ou La longueur des tableaux d'octets doit être égale aux dimensions limites (bounds.Width * bounds.Height) |

### Voir également

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)


