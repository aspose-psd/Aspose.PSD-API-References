---
title: "PathStructure.Key"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PathStructure प्रॉपर्टी। संरचना कुंजी प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
{{< psd/tize >}}
## PathStructure.Key property

संरचना कुंजी प्राप्त करता है।

```csharp
public override int Key { get; }
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


