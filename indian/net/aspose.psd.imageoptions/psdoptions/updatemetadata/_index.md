---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdOptions प्रॉपर्टी। एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि मेटाडाटा अपडेट करना है या नहीं। यदि मान true है तो छवि सहेजते समय मेटाडाटा अपडेट किया जाएगा"
type: docs
weight: 110
url: /hi/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या [update metadata]। यदि मान true है, तो इमेज सहेजते समय मेटाडेटा अपडेट हो जाएगा।

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` यदि [मेटाडाटा अपडेट करें]; अन्यथा, `false`।

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

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


