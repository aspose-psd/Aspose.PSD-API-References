---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LayerGroup. يضيف الطبقة إلى مجموعة الطبقة"
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

يضيف الطبقة إلى مجموعة الطبقة.

```csharp
public void AddLayer(Layer layer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| طبقة | طبقة | الطبقة. |

## أمثلة

المثال التالي يوضح كيف يمكنك إضافة صور Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif كطبقات إلى PsdImage

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

### انظر أيضًا

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


