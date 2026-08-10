---
title: "XmpBasicPackage.ContainsKey"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "XmpBasicPackage मेथड। निर्धारित करता है कि निर्दिष्ट कुंजी में कुंजी मौजूद है या नहीं"
type: docs
weight: 40
url: /hi/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

निर्धारित करता है कि निर्दिष्ट कुंजी में कुंजी मौजूद है या नहीं।

```csharp
public override bool ContainsKey(string key)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कुंजी | String | जाँचने के लिए कुंजी। |

### रिटर्न वैल्यू

यदि निर्दिष्ट कुंजी में कुंजी मौजूद है तो true लौटाता है।

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


