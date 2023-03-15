---
title: Class MlstResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource कक्ष. एमएलएसट संसधन. इस वर्ग में अन्य बतं के अलव समयरेख पर परत क स्थत के बरे में जनकर शमल है
type: docs
weight: 2830
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

एमएलएसटी संसाधन. इस वर्ग में, अन्य बातों के अलावा, समयरेखा पर परत की स्थिति के बारे में जानकारी शामिल है।

```csharp
public class MlstResource : LayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MlstResource](mlstresource/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | डिस्क्रिप्टर संस्करण प्राप्त या सेट करता है। |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | संरचनाओं को प्राप्त या सेट करता है। |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | पीएसडी संस्करण प्राप्त करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | हस्ताक्षर हो जाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | टाइप टूल इंफो की. |

### उदाहरण

निम्न कोड MlstResource संसाधन के समर्थन को प्रदर्शित करता है जो लेयर स्टेट्स में हेरफेर करने के लिए एक निम्न-स्तरीय तंत्र देता है।

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

    // फ़्रेम 1 पर परत 1 को अक्षम करें
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### यह सभी देखें

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


