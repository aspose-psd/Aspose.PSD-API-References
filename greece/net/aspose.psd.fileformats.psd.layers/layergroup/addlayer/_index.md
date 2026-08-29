---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος LayerGroup. Προσθέτει τη στρώση στην ομάδα στρώσεων"
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

Προσθέτει το επίπεδο στην ομάδα επιπέδων.

```csharp
public void AddLayer(Layer layer)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στρώση | Στρώση | Το στρώμα. |

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

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


