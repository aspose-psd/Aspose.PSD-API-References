---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "XmpBasicPackage प्रॉपर्टी। निर्दिष्ट कुंजी वाले ऑब्जेक्ट को प्राप्त या सेट करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

निर्दिष्ट कुंजी के साथ ऑब्जेक्ट को प्राप्त करता है या सेट करता है।

```csharp
public override object this[string key] { get; set; }
```

| पैरामीटर | विवरण |
| --- | --- |
| कुंजी | मान को पहचानने वाली कुंजी। |

### रिटर्न वैल्यू

निर्दिष्ट कुंजी के साथ ऑब्जेक्ट लौटाता है।

### Property Value

ऑब्जेक्ट।

## उदाहरण

निम्नलिखित कोड दर्शाता है कि UpdateMetadata विकल्प का उपयोग करके xmp डेटा में CreatorTool मान को कैसे अपडेट किया जाए।

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // यदि आप चाहते हैं कि निर्माता टूल बदल जाए, तो सुनिश्चित करें कि "UpdateMetadata" प्रॉपर्टी true पर सेट है। यह डिफ़ॉल्ट रूप से true पर सेट है।
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // छवि सहेजना। 
    image.Save(path, psdOptions);

    // कोड में निर्माता टूल की जाँच।
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // यहाँ अद्यतन किया गया निर्माता टूल जानकारी होगी।
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### देखें भी

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


