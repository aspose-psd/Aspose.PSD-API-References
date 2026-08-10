---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "XmpBasicPackage मेथड। मान सेट करता है"
type: docs
weight: 120
url: /hi/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

मान सेट करता है।

```csharp
public override void SetValue(string key, IXmlValue value)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कुंजी | String | जोड़े गए मान के साथ पहचाने गए कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| मान | IXmlValue | जोड़ने के लिए मान। |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


