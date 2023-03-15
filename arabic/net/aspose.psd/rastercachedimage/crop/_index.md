---
title: RasterCachedImage.Crop
second_title: Aspose.PSD لمرجع .NET API
description: RasterCachedImage طريقة. قص الصورة.
type: docs
weight: 90
url: /ar/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

قص الصورة.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rectangle | Rectangle | المستطيل. |

### أمثلة

يوضح الكود التالي القدرة على اقتصاص الصورة حسب مستطيل معين.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // حفظ مديرية الأمن العام
    image.Save(exportPath, new PsdOptions());

    // حفظ png
    image.Save(exportPathPng, new PngOptions());
}
```

### أنظر أيضا

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* مساحة الاسم [Aspose.PSD](../../rastercachedimage/)
* المجسم [Aspose.PSD](../../../)


