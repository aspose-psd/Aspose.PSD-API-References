---
title: "PathStructure.Length"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PathStructure प्रॉपर्टी। OSTypeStructure की लंबाई बाइट्स में प्राप्त करता है"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की लंबाई बाइट्स में प्राप्त करता है।

```csharp
public override int Length { get; }
```

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


