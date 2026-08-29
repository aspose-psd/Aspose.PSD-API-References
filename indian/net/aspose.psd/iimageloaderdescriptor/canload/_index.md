---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IImageLoaderDescriptor विधि। निर्धारित करता है कि इमेज लोडर निर्दिष्ट स्ट्रीम से नई इमेज पढ़ सकता है और वैकल्पिक रूप से loadOptions का उपयोग कर सकता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd/iimageloaderdescriptor/canload/
---
{{< psd/tize >}}
## IImageLoaderDescriptor.CanLoad method

निर्धारित करता है कि इमेज लोडर निर्दिष्ट स्ट्रीम से नई इमेज पढ़ सकता है या नहीं, और वैकल्पिक रूप से *loadOptions* का उपयोग करके।

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| streamContainer | StreamContainer | स्ट्रीम कंटेनर। |
| loadOptions | LoadOptions | फ़ाइल फ़ॉर्मेट विवरण *loadOptions* द्वारा निर्दिष्ट किया गया है। *loadOptions* null हो सकता है। |

### रिटर्न वैल्यू

`true` यदि इस डिस्क्रिप्टर द्वारा निर्मित इमेज लोडर स्ट्रीम से इमेज पढ़ सकता है; अन्यथा, `false`।

### देखें भी

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


