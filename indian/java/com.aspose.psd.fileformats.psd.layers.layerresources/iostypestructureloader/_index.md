---
title: "IOSTypeStructureLoader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "संसाधन लोडर।"
type: docs
weight: 84
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/
---
```
public interface IOSTypeStructureLoader
```

यह [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) संसाधन लोडर है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.psd.StreamContainer-) | निर्धारित करता है कि क्या [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) संसाधन निर्दिष्ट StreamContainer से लोड किया जा सकता है। |
| [load(StreamContainer streamContainer)](#load-com.aspose.psd.StreamContainer-) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) को लोड करता है। |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.psd.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


निर्धारित करता है कि क्या [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) संसाधन निर्दिष्ट StreamContainer से लोड किया जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

**Returns:**
boolean - true यदि [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) संसाधन निर्दिष्ट StreamContainer से लोड किया जा सकता है; अन्यथा, false।
### load(StreamContainer streamContainer) {#load-com.aspose.psd.StreamContainer-}
```
public abstract OSTypeStructure load(StreamContainer streamContainer)
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) को लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | लोड करने के लिए स्ट्रीम कंटेनर। |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource.
