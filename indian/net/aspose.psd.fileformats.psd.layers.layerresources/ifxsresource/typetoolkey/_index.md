---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IfxsResource फ़ील्ड। टाइप टूल जानकारी कुंजी"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

टाइप टूल जानकारी कुंजी।

```csharp
public const int TypeToolKey;
```

## उदाहरण

निम्नलिखित कोड IfxsResource के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // उदाहरण में प्रभावों के साथ 2 समूह लेयर हैं
    // एक प्रभाव वाला समूह लेयर
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // कई प्रभावों वाला समूह लेयर
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // इफ़ेक्ट्स की संख्या प्राप्त करें और उनकी मात्रा सत्यापित करें
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // ग्रुप लेयर में एक इफ़ेक्ट संसाधन 'IfxsResource' में है
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // ग्रुप लेयर में दो या अधिक इफ़ेक्ट्स संसाधन 'ImfxResource' में हैं
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // कई इफ़ेक्ट्स वाले ग्रुप लेयर में तीसरा शैडो जोड़ें
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### देखें भी

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


