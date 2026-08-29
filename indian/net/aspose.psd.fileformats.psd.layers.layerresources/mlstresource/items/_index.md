---
title: "MlstResource.Items"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "MlstResource प्रॉपर्टी. संरचनाओं को प्राप्त या सेट करता है"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

संरचनाओं को प्राप्त करता है या सेट करता है।

```csharp
public OSTypeStructure[] Items { get; }
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

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


