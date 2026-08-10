---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerGroup प्रॉपर्टी। फ़ोल्डर खुला है या नहीं प्राप्त या सेट करता है; यदि true सेट किया जाए तो समूह स्टार्टअप पर खुली अवस्था में रहेगा, अन्यथा न्यूनतम अवस्था में रहेगा"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

यदि `true` सेट किया जाए तो फ़ोल्डर खुला है या नहीं को प्राप्त करता है या सेट करता है; तब समूह प्रारंभ पर खुली स्थिति में रहेगा, अन्यथा संकुचित स्थिति में।

```csharp
public bool IsOpen { get; set; }
```

## उदाहरण

निम्नलिखित कोड दिखाता है कि IsOpen प्रॉपर्टी का उपयोग करके LayerGroup (फ़ोल्डर) को कैसे खोलें और बंद करें।

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

### देखें भी

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


