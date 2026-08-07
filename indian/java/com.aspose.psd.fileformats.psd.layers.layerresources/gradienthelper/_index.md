---
title: "GradientHelper"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ग्रेडिएंट प्रॉपर्टीज़ के लिए डेटा रूपांतरण को लागू करने वाली हेल्पर क्लास।"
type: docs
weight: 34
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

ग्रेडिएंट प्रॉपर्टीज़ के लिए डेटा रूपांतरण को लागू करने वाली हेल्पर क्लास।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL रंग मॉडल पूर्णांक स्थिरांक Noise ग्रेडिएंट के लिए। |
| [IntModelLAB](#IntModelLAB) | LBCL रंग मॉडल पूर्णांक स्थिरांक Noise ग्रेडिएंट के लिए। |
| [IntModelRGB](#IntModelRGB) | RGBC रंग मॉडल पूर्णांक स्थिरांक Noise ग्रेडिएंट के लिए। |
| [StrGradientNoise](#StrGradientNoise) | Noise gradient स्ट्रिंग स्थिरांक। |
| [StrGradientSolid](#StrGradientSolid) | Solid gradient स्ट्रिंग स्थिरांक। |
| [StrModelHSB](#StrModelHSB) | Noise gradient के लिए HSBL color model स्ट्रिंग स्थिरांक। |
| [StrModelLAB](#StrModelLAB) | Noise gradient के लिए LBCL color model स्ट्रिंग स्थिरांक। |
| [StrModelRGB](#StrModelRGB) | Noise gradient के लिए RGBC color model स्ट्रिंग स्थिरांक। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | GradientKind मान को स्ट्रिंग में बदलें। |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Noise रंग मॉडल के पूर्णांक मान को NoiseColorModel में परिवर्तित करता है। |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | NoiseColorModel इंस्टेंस को Noise रंग मॉडल के पूर्णांक मान में परिवर्तित करता है। |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | NoiseColorModel मान को स्ट्रिंग में बदलें। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | स्ट्रिंग मान को GradientKind में बदलें। |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | स्ट्रिंग मान को NoiseColorModel में बदलें। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientHelper() {#GradientHelper--}
```
public GradientHelper()
```


### IntModelHSB {#IntModelHSB}
```
public static final short IntModelHSB
```


HSBL रंग मॉडल पूर्णांक स्थिरांक Noise ग्रेडिएंट के लिए।

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL रंग मॉडल पूर्णांक स्थिरांक Noise ग्रेडिएंट के लिए।

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC रंग मॉडल पूर्णांक स्थिरांक Noise ग्रेडिएंट के लिए।

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Noise gradient स्ट्रिंग स्थिरांक।

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Solid gradient स्ट्रिंग स्थिरांक।

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Noise gradient के लिए HSBL color model स्ट्रिंग स्थिरांक।

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Noise gradient के लिए LBCL color model स्ट्रिंग स्थिरांक।

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Noise gradient के लिए RGBC color model स्ट्रिंग स्थिरांक।

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
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


GradientKind मान को स्ट्रिंग में बदलें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| gradientKind | int | GradientKind मान। |

**Returns:**
java.lang.String - स्ट्रिंग मान।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToNoiseColorModel(short colorModel) {#intToNoiseColorModel-short-}
```
public static short intToNoiseColorModel(short colorModel)
```


Noise रंग मॉडल के पूर्णांक मान को NoiseColorModel में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorModel | short | शोर रंग मॉडल का पूर्णांक मान। |

**Returns:**
short - NoiseColorModel इंस्टेंस।
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


NoiseColorModel इंस्टेंस को Noise रंग मॉडल के पूर्णांक मान में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorModel | short | NoiseColorModel इंस्टेंस। |

**Returns:**
short - Noise ग्रेडिएंट रंग मॉडल का पूर्णांक मान।
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


NoiseColorModel मान को स्ट्रिंग में बदलें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorModel | short | NoiseColorModel मान। |

**Returns:**
java.lang.String - रंग मॉडल का स्ट्रिंग मान।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


स्ट्रिंग मान को GradientKind में बदलें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | java.lang.String | स्ट्रिंग मान। |

**Returns:**
int - GradientKind मान।
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


स्ट्रिंग मान को NoiseColorModel में बदलें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorModel | java.lang.String | स्ट्रिंग मान। |

**Returns:**
short - NoiseColorModel मान।
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

