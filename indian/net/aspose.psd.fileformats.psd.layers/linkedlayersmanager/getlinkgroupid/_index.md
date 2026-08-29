---
title: "LinkedLayersManager.GetLinkGroupId"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LinkedLayersManager मेथड। लेयर से जुड़े लिंक ग्रुप ID को प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLinkGroupId method

लेयर से जुड़ा लिंक समूह आईडी प्राप्त करता है।

```csharp
public short GetLinkGroupId(Layer layer)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| लेयर | लेयर | लेयर। |

### रिटर्न वैल्यू

लिंक ग्रुप आईडी।

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


