---
title: "SmartFilter"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "स्मार्ट फ़िल्टरों की मूल लॉजिक को प्रोसेस करने के लिए क्लास।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, java.lang.Cloneable
```
public abstract class SmartFilter implements System.ICloneable, Cloneable
```

स्मार्ट फ़िल्टरों की मूल लॉजिक को प्रोसेस करने के लिए क्लास।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [SmartFilter()](#SmartFilter--) | [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | वर्तमान फ़िल्टर को इनपुट RasterImage छवि पर लागू करता है। |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | वर्तमान फ़िल्टर को इनपुट [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) मास्क डेटा पर लागू करता है। |
| [deepClone()](#deepClone--) | टाइप की वर्तमान उदाहरण का सदस्य-वार क्लोन बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ब्लेंडिंग मोड प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | स्मार्ट फ़िल्टर प्रकार पहचानकर्ता प्राप्त करता है। |
| [getName()](#getName--) | स्मार्ट फ़िल्टर नाम प्राप्त करता है। |
| [getOpacity()](#getOpacity--) | स्मार्ट फ़िल्टर की अपारदर्शिता मान प्राप्त करता है या सेट करता है। |
| [getSourceDescriptor()](#getSourceDescriptor--) | स्मार्ट फ़िल्टर डेटा के साथ स्रोत डिस्क्रिप्टर संरचना। |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त करता है या सेट करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | ब्लेंडिंग मोड प्राप्त करता है या सेट करता है। |
| [setEnabled(boolean value)](#setEnabled-boolean-) | स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त करता है या सेट करता है। |
| [setOpacity(double value)](#setOpacity-double-) | स्मार्ट फ़िल्टर की अपारदर्शिता मान प्राप्त करता है या सेट करता है। |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | स्मार्ट फ़िल्टर जानकारी को [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) डेटा में सहेजता है और लौटाता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartFilter() {#SmartFilter--}
```
public SmartFilter()
```


[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) क्लास का नया उदाहरण प्रारंभ करता है।

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


वर्तमान फ़िल्टर को इनपुट RasterImage छवि पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | रास्टर छवि। |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


वर्तमान फ़िल्टर को इनपुट [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) मास्क डेटा पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | मास्क डेटा वाली लेयर। |

### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


टाइप की वर्तमान उदाहरण का सदस्य-वार क्लोन बनाता है।

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


ब्लेंडिंग मोड प्राप्त करता है या सेट करता है।

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public abstract int getFilterId()
```


स्मार्ट फ़िल्टर प्रकार पहचानकर्ता प्राप्त करता है।

**Returns:**
int
### getName() {#getName--}
```
public abstract String getName()
```


स्मार्ट फ़िल्टर नाम प्राप्त करता है।

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


स्मार्ट फ़िल्टर की अपारदर्शिता मान प्राप्त करता है या सेट करता है।

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


स्मार्ट फ़िल्टर डेटा के साथ स्रोत डिस्क्रिप्टर संरचना।

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


ब्लेंडिंग मोड प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


स्मार्ट फ़िल्टर की अपारदर्शिता मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


स्मार्ट फ़िल्टर जानकारी को [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) डेटा में सहेजता है और लौटाता है।

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

