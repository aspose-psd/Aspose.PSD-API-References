---
title: "ImageExportersRegistry"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इमेज एक्सपोर्टर्स रजिस्ट्री का प्रतिनिधित्व करता है।"
type: docs
weight: 57
url: /hi/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

इमेज एक्सपोर्टर्स रजिस्ट्री का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला निर्यातकर्ता बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | पंजीकृत निर्यातकर्ता डिस्क्रिप्टर प्राप्त करता है। |
| [getRegisteredFormats()](#getRegisteredFormats--) | पंजीकृत निर्यात फ़ॉर्मेट प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | निर्दिष्ट छवि निर्यातकर्ता डिस्क्रिप्टर को पंजीकृत करता है। |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | निर्यातकर्ता को पंजीकृत करता है। |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | निर्यातकर्ता को पंजीकरण रद्द करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageExportersRegistry() {#ImageExportersRegistry--}
```
public ImageExportersRegistry()
```


### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला निर्यातकर्ता बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | निर्यात करने के लिए छवि। |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | निर्यात के लिए उपयोग करने वाले सहेजने विकल्प। |

--------------------

पहला निर्यातकर्ता वास्तव में अंतिम पंजीकृत होगा। |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


निर्दिष्ट सहेजने विकल्पों और छवि के लिए उपयुक्त पहला मिला समर्थित डिस्क्रिप्टर प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | निर्यात करने के लिए छवि। |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | विकल्प। |

--------------------

पहला निर्यातकर्ता डिस्क्रिप्टर वास्तव में अंतिम पंजीकृत होगा। |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


पंजीकृत निर्यातकर्ता डिस्क्रिप्टर प्राप्त करता है।

मान: पंजीकृत निर्यातकर्ता डिस्क्रिप्टर।

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


पंजीकृत निर्यात फ़ॉर्मेट प्राप्त करता है।

मान: पंजीकृत निर्यात फ़ॉर्मेट।

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### register(IImageExporterDescriptor imageExporterDescriptor) {#register-com.aspose.psd.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor imageExporterDescriptor)
```


निर्दिष्ट छवि निर्यातकर्ता डिस्क्रिप्टर को पंजीकृत करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | छवि निर्यातकर्ता डिस्क्रिप्टर। |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


निर्यातकर्ता को पंजीकृत करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | पंजीकृत करने के लिए निर्यातकर्ता डिस्क्रिप्टर। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


निर्यातकर्ता को पंजीकरण रद्द करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | पंजीकरण रद्द करने के लिए निर्यातकर्ता डिस्क्रिप्टर। |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

