---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PathStructure कंस्ट्रक्टर। PathStructure क्लास का एक नया उदाहरण प्रारंभ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

[`PathStructure`](../) क्लास का एक नया उदाहरण प्रारंभ करता है।

```csharp
public PathStructure(ClassID keyName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| keyName | ClassID | कुंजी नाम। |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


