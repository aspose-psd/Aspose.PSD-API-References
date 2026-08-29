---
title: "Layer.DisplayName"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Layer property. लेयर के डिस्प्ले नाम को प्राप्त या सेट करता है"
type: docs
weight: 110
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

लेयर का डिस्प्ले नाम प्राप्त करता है या सेट करता है।

```csharp
public string DisplayName { get; set; }
```

### Property Value

लेयर का डिस्प्ले नाम।

## उदाहरण

निम्न उदाहरण दिखाता है कि कैसे DisplayName मान को सेट किया जा सकता है, जिससे लेयर नाम सही ढंग से प्रदर्शित हो।

```csharp
[C#]

// लेयर नामों में परिवर्तन करें और इसे सहेजें
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // DisplayName प्रॉपर्टी में नया मान सेट करें
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### देखें भी

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


