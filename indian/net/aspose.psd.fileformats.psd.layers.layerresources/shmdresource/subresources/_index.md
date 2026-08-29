---
title: "ShmdResource.SubResources"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ShmdResource प्रॉपर्टी। श्म्ड संसाधन के उप-संसाधन प्राप्त करता है"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

shmd संसाधन के उप-संसाधनों को प्राप्त करता है।

```csharp
public LayerResource[] SubResources { get; }
```

## उदाहरण

निम्न कोड MlstResource रिसोर्स के समर्थन को दर्शाता है जो लेयर स्टेट्स को मैनिपुलेट करने के लिए लो-लेवल मैकेनिज़्म प्रदान करता है।

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // फ़्रेम 1 पर लेयर 1 को निष्क्रिय करें
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### देखें भी

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


