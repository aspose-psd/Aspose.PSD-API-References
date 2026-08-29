---
title: "क्लास PathStructure"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure क्लास. पथ संरचना"
type: docs
weight: 3610
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
{{< psd/tize >}}
## PathStructure class

पाथ संरचना।

```csharp
public sealed class PathStructure : OSTypeStructure
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | `PathStructure` क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | संरचना कुंजी प्राप्त करता है। |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | कुंजी नाम प्राप्त करता है या सेट करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की लंबाई बाइट्स में प्राप्त करता है। |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | पथ को प्राप्त करता है या सेट करता है। |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | पथ उपसर्ग को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | हेडर की लंबाई प्राप्त करता है। |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | संरचना कुंजी की पहचान करता है। |

## उदाहरण

निम्नलिखित कोड PathStructure संरचना के साथ फ़ाइल लोड करने की क्षमता को दर्शाता है।

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### देखें भी

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


