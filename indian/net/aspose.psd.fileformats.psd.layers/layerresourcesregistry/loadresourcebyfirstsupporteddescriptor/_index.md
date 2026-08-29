---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerResourcesRegistry मेथड। निर्दिष्ट स्ट्रीम के लिए उपयुक्त पहला मिला ओपनर उपयोग करके LayerResource लोड करता है"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

पहला मिला उपयुक्त ओपनर उपयोग करके निर्दिष्ट *स्ट्रीम* के लिए [`LayerResource`](../../layerresource/) लोड करता है।

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | स्ट्रीम। |
| psdVersion | Int32 | PSD संस्करण। |

### रिटर्न वैल्यू

लोड किया गया [`LayerResource`](../../layerresource/) या null यदि कोई ओपनर नहीं मिला।

## टिप्पणियाँ

पहला ओपनर वास्तव में अंतिम पंजीकृत होगा।

### देखें भी

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


