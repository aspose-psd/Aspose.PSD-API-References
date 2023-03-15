---
title: LayerGroup.IsOpen
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LayerGroup संपत्त. फ़ल्डर open ह जत है य सेट ह जत है यद इसे सेट कय जत हैसत्य स्टर्ट अप पर समूह खुले रज्य में हग अन्यथ न्यूनतम स्थत में
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

फ़ोल्डर open हो जाता है या सेट हो जाता है यदि इसे सेट किया जाता है`सत्य` स्टार्ट अप पर समूह खुले राज्य में होगा, अन्यथा न्यूनतम स्थिति में।

```csharp
public bool IsOpen { get; set; }
```

### उदाहरण

निम्न कोड दिखाता है कि IsOpen गुण का उपयोग करके LayerGroup (फ़ोल्डर) को कैसे खोला और बंद किया जाए।

```csharp
[C#]

// रनटाइम पर IsOpen प्रॉपर्टी को पढ़ने और लिखने का उदाहरण।
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### यह सभी देखें

* class [LayerGroup](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* सभा [Aspose.PSD](../../../)


