---
title: "क्लास LinkedLayersManager"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager क्लास. Linked layers manager क्लास"
type: docs
weight: 3800
url: /hi/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
{{< psd/tize >}}
## LinkedLayersManager class

लिंक्ड लेयर्स मैनेजर क्लास।

```csharp
public sealed class LinkedLayersManager
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | लेयर को लिंक समूह आईडी द्वारा प्राप्त करता है। |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | लेयर से जुड़ा लिंक समूह आईडी प्राप्त करता है। |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | इनपुट लेयर्स को लिंक करता है और LingGroupId लौटाता है। |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | लेयर को अनलिंक करता है.. |

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में Linked Layers को कैसे हेरफेर कर सकते हैं।

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // सभी लेयर्स को एक लिंक्ड समूह में लिंक करें।
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // एक लेयर के लिए आईडी प्राप्त करता है।
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // लिंक समूह आईडी द्वारा सभी लिंक्ड लेयर्स प्राप्त करता है।
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // समूह से प्रत्येक लेयर को अनलिंक करें।
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // उस लिंक समूह आईडी के लिए NULL लौटाता है जिसमें समूह में कोई लेयर नहीं है।
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


