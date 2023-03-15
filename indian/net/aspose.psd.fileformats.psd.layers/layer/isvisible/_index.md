---
title: Layer.IsVisible
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Layer संपत्त. एक मन प्रप्त करत है य सेट करत है ज इंगत करत है क परत दृश्यमन है
type: docs
weight: 170
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि परत दृश्यमान है

```csharp
public bool IsVisible { get; set; }
```

### संपत्ति मूल्य

`सत्य` यदि यह उदाहरण दिखाई दे रहा है; अन्यथा,`असत्य` .

### उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में LayerGroup दृश्यता को कैसे बदल सकते हैं

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// लेयर के नाम में बदलाव करें और इसे सेव करें
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // एक समूह के अंदर सब कुछ बंद कर दें
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### यह सभी देखें

* class [Layer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* सभा [Aspose.PSD](../../../)


