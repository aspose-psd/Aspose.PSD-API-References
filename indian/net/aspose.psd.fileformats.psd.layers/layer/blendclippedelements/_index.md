---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Layer प्रॉपर्टी। क्लिप्ड एलिमेंट के ब्लेंडिंग को प्राप्त करता है या सेट करता है"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

क्लिप किए गए तत्व के मिश्रण को प्राप्त करता है या सेट करता है।

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

क्लिप्ड एलिमेंट का ब्लेंडिंग।

## उदाहरण

निम्नलिखित कोड BlendClippedElements प्रॉपर्टी के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### देखें भी

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


