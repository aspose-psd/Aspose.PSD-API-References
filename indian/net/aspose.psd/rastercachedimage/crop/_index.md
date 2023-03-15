---
title: RasterCachedImage.Crop
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: RasterCachedImage तरक. इमेज क क्रप कय ज रह है.
type: docs
weight: 90
url: /hi/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

इमेज को क्रॉप किया जा रहा है.

```csharp
public override void Crop(Rectangle rectangle)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | Rectangle | आयत। |

### उदाहरण

निम्न कोड विशिष्ट आयत द्वारा छवि को क्रॉप करने की क्षमता प्रदर्शित करता है।

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

    // पीएसडी बचाओ
    image.Save(exportPath, new PsdOptions());

    // पीएनजी सहेजें
    image.Save(exportPathPng, new PngOptions());
}
```

### यह सभी देखें

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* नाम स्थान [Aspose.PSD](../../rastercachedimage/)
* सभा [Aspose.PSD](../../../)


