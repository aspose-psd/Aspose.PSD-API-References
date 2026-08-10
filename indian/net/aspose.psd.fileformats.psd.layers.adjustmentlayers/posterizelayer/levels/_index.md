---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PosterizeLayer प्रॉपर्टी। पोस्टराइज़ लेयर के स्तर"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

पोस्टराइज़ लेयर के स्तर।

```csharp
public short Levels { get; set; }
```

## उदाहरण

निम्नलिखित कोड PosterizeLayer के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    foreach (Layer layer in image.Layers)
    {
        if (layer is PosterizeLayer)
        {
            ((PosterizeLayer)layer).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### देखें भी

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


