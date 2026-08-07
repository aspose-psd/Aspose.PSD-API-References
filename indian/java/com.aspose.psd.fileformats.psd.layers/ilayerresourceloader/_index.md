---
title: "ILayerResourceLoader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लेयर रिसोर्स लोडर।"
type: docs
weight: 32
url: /hi/java/com.aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---
```
public interface ILayerResourceLoader
```

लेयर रिसोर्स लोडर।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [canLoad(StreamContainer streamContainer, int psdVersion)](#canLoad-com.aspose.psd.StreamContainer-int-) | निर्धारित करता है कि लेयर रिसोर्स निर्दिष्ट StreamContainer से लोड किया जा सकता है या नहीं। |
| [load(StreamContainer streamContainer, int psdVersion)](#load-com.aspose.psd.StreamContainer-int-) | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) को लोड करता है। |
### canLoad(StreamContainer streamContainer, int psdVersion) {#canLoad-com.aspose.psd.StreamContainer-int-}
```
public abstract boolean canLoad(StreamContainer streamContainer, int psdVersion)
```


निर्धारित करता है कि लेयर रिसोर्स निर्दिष्ट StreamContainer से लोड किया जा सकता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psdVersion | int | PSD संस्करण। |

**Returns:**
बूलियन - true यदि लेयर रिसोर्स निर्दिष्ट StreamContainer से लोड किया जा सकता है; अन्यथा false।
### load(StreamContainer streamContainer, int psdVersion) {#load-com.aspose.psd.StreamContainer-int-}
```
public abstract LayerResource load(StreamContainer streamContainer, int psdVersion)
```


[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) को लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | लोड करने के लिए स्ट्रीम कंटेनर। |
| psdVersion | int | PSD संस्करण। |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded resource.
