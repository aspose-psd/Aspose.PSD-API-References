---
title: "GaussianBlurSmartFilter"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "GaussianBlur स्मार्ट फ़िल्टर।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class GaussianBlurSmartFilter extends SmartFilter
```

GaussianBlur स्मार्ट फ़िल्टर।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter--) | [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) वर्ग का नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [FilterType](#FilterType) | वर्तमान स्मार्ट फ़िल्टर का पहचानकर्ता। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | वर्तमान फ़िल्टर को इनपुट RasterImage छवि पर लागू करता है। |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | वर्तमान फ़िल्टर को इनपुट [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) मास्क डेटा पर लागू करता है। |
| [crate_internalized(DescriptorStructure sourceDescriptor)](#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | टाइप की वर्तमान उदाहरण का सदस्य-वार क्लोन बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ब्लेंडिंग मोड प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | स्मार्ट फ़िल्टर प्रकार पहचानकर्ता प्राप्त करता है। |
| [getName()](#getName--) | स्मार्ट फ़िल्टर नाम प्राप्त करता है। |
| [getOpacity()](#getOpacity--) | स्मार्ट फ़िल्टर की अपारदर्शिता मान प्राप्त करता है या सेट करता है। |
| [getRadius()](#getRadius--) | गॉसियन स्मार्ट फ़िल्टर की त्रिज्या प्राप्त करता है या सेट करता है। |
| [getSourceDescriptor()](#getSourceDescriptor--) | स्मार्ट फ़िल्टर डेटा के साथ स्रोत डिस्क्रिप्टर संरचना। |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त करता है या सेट करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | ब्लेंडिंग मोड प्राप्त करता है या सेट करता है। |
| [setEnabled(boolean value)](#setEnabled-boolean-) | स्मार्ट फ़िल्टर की सक्षम स्थिति प्राप्त करता है या सेट करता है। |
| [setOpacity(double value)](#setOpacity-double-) | स्मार्ट फ़िल्टर की अपारदर्शिता मान प्राप्त करता है या सेट करता है। |
| [setRadius(double value)](#setRadius-double-) | गॉसियन स्मार्ट फ़िल्टर की त्रिज्या प्राप्त करता है या सेट करता है। |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | स्मार्ट फ़िल्टर जानकारी को [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) डेटा में सहेजता है और लौटाता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussianBlurSmartFilter() {#GaussianBlurSmartFilter--}
```
public GaussianBlurSmartFilter()
```


[GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) वर्ग का नया उदाहरण प्रारंभ करता है।

### FilterType {#FilterType}
```
public static final int FilterType
```


वर्तमान स्मार्ट फ़िल्टर का पहचानकर्ता।

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

### crate_internalized(DescriptorStructure sourceDescriptor) {#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static GaussianBlurSmartFilter crate_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter)
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
public int getFilterId()
```


स्मार्ट फ़िल्टर प्रकार पहचानकर्ता प्राप्त करता है।

**Returns:**
int
### getName() {#getName--}
```
public String getName()
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
### getRadius() {#getRadius--}
```
public final double getRadius()
```


गॉसियन स्मार्ट फ़िल्टर की त्रिज्या प्राप्त करता है या सेट करता है।

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

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


गॉसियन स्मार्ट फ़िल्टर की त्रिज्या प्राप्त करता है या सेट करता है।

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

