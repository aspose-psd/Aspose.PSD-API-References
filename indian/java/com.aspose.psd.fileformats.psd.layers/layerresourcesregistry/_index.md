---
title: "LayerResourcesRegistry"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लेयर संसाधन रजिस्ट्री का प्रतिनिधित्व करता है।"
type: docs
weight: 26
url: /hi/java/com.aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Inheritance:**
java.lang.Object
```
public final class LayerResourcesRegistry
```

लेयर संसाधन रजिस्ट्री का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LayerResourcesRegistry()](#LayerResourcesRegistry--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, int psdVersion)](#getFirstSupportedDescriptor-java.io.InputStream-int-) | पहला समर्थित ओपनर डिस्क्रिप्टर प्राप्त करता है। |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | उसके टाइप नाम द्वारा पहला समर्थित डिस्क्रिप्टर प्राप्त करता है। |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | रजिस्टर्ड डिस्क्रिप्टर प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-) | निर्दिष्ट स्ट्रीम के लिए उपयुक्त पहला पाया गया ओपनर उपयोग करके [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) लोड करता है। |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerDefaultPsdOptions_internalized()](#registerDefaultPsdOptions-internalized--) | डिफ़ॉल्ट PSD विकल्पों को रजिस्टर करता है। |
| [registerOpener(ILayerResourceLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | ओपनर को रजिस्टर करता है। |
| [registerPsdLoadOptions_internalized(PsdLoadOptions load)](#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-) | PSD लोड विकल्पों को रजिस्टर करता है। |
| [toString()](#toString--) |  |
| [unregisterOpener(ILayerResourceLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | ओपनर को अनरजिस्टर करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerResourcesRegistry() {#LayerResourcesRegistry--}
```
public LayerResourcesRegistry()
```


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
### getFirstSupportedDescriptor(InputStream stream, int psdVersion) {#getFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


पहला समर्थित ओपनर डिस्क्रिप्टर प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | स्ट्रीम। |
|  | psdVersion | int | PSD संस्करण। |

--------------------

पहला लोडर वास्तव में अंतिम पंजीकृत होगा। |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static ILayerResourceLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


उसके टाइप नाम द्वारा पहला समर्थित डिस्क्रिप्टर प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | डिस्क्रिप्टर प्रकार का नाम। |

--------------------

पहला ओपनर डिस्क्रिप्टर वास्तव में अंतिम पंजीकृत होगा। |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static ILayerResourceLoader[] getRegisteredDescriptors()
```


रजिस्टर्ड डिस्क्रिप्टर प्राप्त करता है।

मान: पंजीकृत डिस्क्रिप्टर।

**Returns:**
com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


निर्दिष्ट स्ट्रीम के लिए उपयुक्त पहला पाया गया ओपनर उपयोग करके [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | स्ट्रीम। |
|  | psdVersion | int | PSD संस्करण। |

--------------------

पहला ओपनर वास्तव में अंतिम पंजीकृत होगा। |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerDefaultPsdOptions_internalized() {#registerDefaultPsdOptions-internalized--}
```
public static void registerDefaultPsdOptions_internalized()
```


डिफ़ॉल्ट PSD विकल्पों को रजिस्टर करता है।

### registerOpener(ILayerResourceLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void registerOpener(ILayerResourceLoader openerDescriptor)
```


ओपनर को रजिस्टर करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | पंजीकरण के लिए ओपनर डिस्क्रिप्टर। |

### registerPsdLoadOptions_internalized(PsdLoadOptions load) {#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-}
```
public static void registerPsdLoadOptions_internalized(PsdLoadOptions load)
```


PSD लोड विकल्पों को रजिस्टर करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| load | [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) | लोड। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(ILayerResourceLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void unregisterOpener(ILayerResourceLoader openerDescriptor)
```


ओपनर को अनरजिस्टर करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | अनपंजीकरण के लिए ओपनर डिस्क्रिप्टर। |

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

