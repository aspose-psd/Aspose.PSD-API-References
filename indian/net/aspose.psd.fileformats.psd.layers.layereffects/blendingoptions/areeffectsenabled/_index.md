---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BlendingOptions प्रॉपर्टी। सभी लेयर प्रभावों की दृश्यता प्राप्त करता है या सेट करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

सभी लेयर इफ़ेक्ट्स की दृश्यता को प्राप्त करता है या सेट करता है।

```csharp
public bool AreEffectsEnabled { get; set; }
```

## उदाहरण

दिखाता है कि कैसे AreEffectsEnabled प्रॉपर्टी का उपयोग करके लेयर प्रभावों को सक्षम या अक्षम किया जाए।

```csharp
[C#]

string srcFile = "2485.psd";
string outputOnFile = "on_2485.png";
string outputOffFile = "off_2485.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Save(outputOnFile);

    psdImage.Layers[1].BlendingOptions.AreEffectsEnabled = false;

    psdImage.Save(outputOffFile);
}
```

### देखें भी

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


