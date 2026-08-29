---
title: "Layer.IsVisible"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Layer प्रॉपर्टी। यह दर्शाने वाला मान प्राप्त या सेट करता है कि लेयर दृश्यमान है या नहीं।"
type: docs
weight: 180
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

लेयर दृश्यमान है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` यदि यह इंस्टेंस दृश्यमान है; अन्यथा, `false`।

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में LayerGroup की दृश्यता को कैसे बदल सकते हैं।

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// लेयर नामों में परिवर्तन करें और इसे सहेजें
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // समूह के भीतर सभी चीज़ों को बंद करें
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### देखें भी

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


