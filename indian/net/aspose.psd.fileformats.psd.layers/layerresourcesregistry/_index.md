---
title: "क्लास LayerResourcesRegistry"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry क्लास। PSD फ़ाइलों के लोडिंग के लिए लेयर संसाधन रजिस्ट्री को परिभाषित करता है"
type: docs
weight: 3790
url: /hi/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

PSD फ़ाइलों के लोडिंग के लिए लेयर रिसोर्सेज रजिस्ट्री को परिभाषित करें।

```csharp
public static class LayerResourcesRegistry
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | पंजीकृत डिस्क्रिप्टर प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | पहला समर्थित ओपनर डिस्क्रिप्टर प्राप्त करता है। |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | उसके प्रकार नाम द्वारा पहला समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | निर्दिष्ट *stream* के लिए उपयुक्त पहला मिला ओपनर का उपयोग करके [`LayerResource`](../layerresource/) लोड करता है। |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | ओपनर को पंजीकृत करता है। |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | ओपनर को अनपंजीकृत करता है। |

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


