---
title: LinkedLayersManager.UnlinkLayer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LinkedLayersManager तरक. परत क अनलंक करत है..
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/
---
## LinkedLayersManager.UnlinkLayer method

परत को अनलिंक करता है..

```csharp
public void UnlinkLayer(Layer layer)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layer | Layer | परत। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | परत शून्य है। |
| ArgumentException | परत का कंटेनर वर्तमान PsdImage जैसा ही होना चाहिए। |

### उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि आप Aspose.PSD में लिंक्ड लेयर्स में हेरफेर कैसे कर सकते हैं

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // सभी परतों को एक लिंक किए गए समूह में लिंक करें
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // एक परत के लिए आईडी मिलती है
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // लिंक ग्रुप आईडी द्वारा सभी लिंक्ड लेयर प्राप्त करता है।
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // समूह से प्रत्येक परत को अनलिंक करें
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // एक लिंक समूह आईडी के लिए NULL को पुनः प्राप्त करता है जिसकी समूह में कोई परत नहीं है।
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### यह सभी देखें

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* सभा [Aspose.PSD](../../../)


