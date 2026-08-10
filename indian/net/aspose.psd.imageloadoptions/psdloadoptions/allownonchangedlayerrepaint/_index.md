---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdLoadOptions प्रॉपर्टी। यह निर्धारित करता है कि रेंडरिंग के दौरान मूल लेयर पिक्सेल को संरक्षित किया जाए या नहीं, यदि लेयर में कोई परिवर्तन नहीं किया गया है।"
type: docs
weight: 20
url: /hi/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

यदि लेयर में कोई बदलाव नहीं किया गया है तो रेंडरिंग के दौरान मूल लेयर पिक्सेल को संरक्षित करना चाहिए या नहीं, इसे प्राप्त करता है या सेट करता है।

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` अपरिवर्तित लेयर्स के मूल पिक्सेल को रखने के लिए; अन्यथा, `false`।

## उदाहरण

निम्नलिखित कोड नई व्यवहार को दर्शाता है जो परिवर्तनों से पहले लेयर्स की स्वचालित पुनःरंगाई को रोकता है।

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### देखें भी

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


