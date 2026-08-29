---
title: "PostResource.Levels"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PostResource प्रॉपर्टी। पोस्टराइज़ लेयर के लेवल्स"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

पोस्टराइज़ लेयर के स्तर।

```csharp
public short Levels { get; set; }
```

### रिटर्न वैल्यू

लेवल्स int मान

## उदाहरण

निम्नलिखित कोड PostResource के हेरफेर की क्षमता को दर्शाता है।

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### देखें भी

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


