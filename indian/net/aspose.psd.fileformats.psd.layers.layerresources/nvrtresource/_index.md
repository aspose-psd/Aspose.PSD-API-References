---
title: Class NvrtResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource कक्ष. क्लस NvrtResource. इनवर्ट एडजस्टमेंट लेयर क संसधन.
type: docs
weight: 2840
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
## NvrtResource class

क्लास NvrtResource. इनवर्ट एडजस्टमेंट लेयर का संसाधन.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`NvrtResource` वर्ग. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | का एक नया उदाहरण प्रारंभ करता है`NvrtResource` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/psdversion/) { get; } | PSD संस्करण प्राप्त करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | हस्ताक्षर हो जाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | प्रकार उपकरण जानकारी कुंजी। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि NvrtResource कैसे प्राप्त करें।

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // NvrtResource समर्थित है।
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### यह सभी देखें

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


