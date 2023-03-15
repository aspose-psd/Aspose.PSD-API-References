---
title: Layer.DisplayName
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Layer संपत्त. परत क प्रदर्शन नम प्रप्त य सेट करत है
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

परत का प्रदर्शन नाम प्राप्त या सेट करता है।

```csharp
public string DisplayName { get; set; }
```

### संपत्ति मूल्य

परत का प्रदर्शन नाम.

### उदाहरण

निम्न उदाहरण DisplayName मान को सेट करने की क्षमता प्रदर्शित करता है, जिसमें परत का नाम सही प्रदर्शित होता है।

```csharp
[C#]

// लेयर के नाम में बदलाव करें और इसे सेव करें
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

### यह सभी देखें

* class [Layer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* सभा [Aspose.PSD](../../../)


