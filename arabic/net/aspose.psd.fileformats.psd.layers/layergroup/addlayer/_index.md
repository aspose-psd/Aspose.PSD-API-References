---
title: LayerGroup.AddLayer
second_title: Aspose.PSD لمرجع .NET API
description: LayerGroup طريقة. يضيف الطبقة إلى مجموعة الطبقات.
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

يضيف الطبقة إلى مجموعة الطبقات.

```csharp
public void AddLayer(Layer layer)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| layer | Layer | طبقة. |

### أمثلة

يوضح المثال التالي كيف يمكنك إضافة صور Bmp و Jpeg و Jpeg2000 و Png و Psd و Tiff و Gif كطبقات إلى PsdImage

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

### أنظر أيضا

* class [Layer](../../layer/)
* class [LayerGroup](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* المجسم [Aspose.PSD](../../../)


