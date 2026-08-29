---
title: "PathStructure.Prefix"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PathStructure प्रॉपर्टी। पाथ प्रीफ़िक्स प्राप्त या सेट करता है"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

पथ उपसर्ग को प्राप्त करता है या सेट करता है।

```csharp
public string Prefix { get; set; }
```

### Property Value

पूरा पथ।

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

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


