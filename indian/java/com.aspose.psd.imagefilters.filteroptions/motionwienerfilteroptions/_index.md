---
title: "MotionWienerFilterOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Deconvolution फ़िल्टर विकल्प     मोशन डीब्लर"
type: docs
weight: 18
url: /hi/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

डीकन्वॉल्यूशन फ़िल्टर विकल्प डिब्लर मोशन
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | MotionWienerFilterOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | कोण को ग्रेडस में प्राप्त या सेट करता है। |
| [getBrightness()](#getBrightness--) | brightness को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | यह दर्शाने वाला मान प्राप्त या सेट करता है कि यह [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) ग्रेस्केल है। |
| [getLength()](#getLength--) | लंबाई को प्राप्त या सेट करता है। |
| [getSmooth()](#getSmooth--) | स्मूद को प्राप्त या सेट करता है। |
| [getSnr()](#getSnr--) | SNR (signal-to-noise ratio) को प्राप्त या सेट करता है, अनुशंसित सीमा 0.002 - 0.009, डिफ़ॉल्ट मान = 0.007। |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस आंशिक रूप से लोड है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | कोण को ग्रेडस में प्राप्त या सेट करता है। |
| [setBrightness(double value)](#setBrightness-double-) | brightness को प्राप्त करता है या सेट करता है। |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | यह दर्शाने वाला मान प्राप्त या सेट करता है कि यह [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) ग्रेस्केल है। |
| [setLength(int value)](#setLength-int-) | लंबाई को प्राप्त या सेट करता है। |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस आंशिक रूप से लोड है या नहीं। |
| [setSmooth(double value)](#setSmooth-double-) | स्मूद को प्राप्त या सेट करता है। |
| [setSnr(double value)](#setSnr-double-) | SNR (signal-to-noise ratio) को प्राप्त या सेट करता है, अनुशंसित सीमा 0.002 - 0.009, डिफ़ॉल्ट मान = 0.007। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


MotionWienerFilterOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| लंबाई | int | लंबाई। |
| स्मूद | double | स्मूद। |
| angle | double | ग्रेडस में कोण। |

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
### getAngle() {#getAngle--}
```
public double getAngle()
```


कोण को ग्रेडस में प्राप्त या सेट करता है।

मान: कोण।

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


चमक को प्राप्त करता है या सेट करता है। अनुशंसित सीमा 1 - 1.5, डिफ़ॉल्ट मान = 1.15

मान: brightness।

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


इस [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) ग्रेस्केल है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। ग्रेस्केल मोड या RGB मोड लौटाता है।

मान: यदि ग्रेस्केल हो तो true; अन्यथा false।

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


लंबाई को प्राप्त या सेट करता है।

मान: लंबाई।

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


स्मूद को प्राप्त या सेट करता है।

मान: स्मूद।

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


SNR (signal-to-noise ratio) को प्राप्त या सेट करता है, अनुशंसित सीमा 0.002 - 0.009, डिफ़ॉल्ट मान = 0.007।

मान: SNR।

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस आंशिक रूप से लोड है या नहीं।

मान: यदि यह इंस्टेंस आंशिक रूप से लोड है तो true; अन्यथा false।

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


कोण को ग्रेडस में प्राप्त या सेट करता है।

मान: कोण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


चमक को प्राप्त करता है या सेट करता है। अनुशंसित सीमा 1 - 1.5, डिफ़ॉल्ट मान = 1.15

मान: brightness।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


इस [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) ग्रेस्केल है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। ग्रेस्केल मोड या RGB मोड लौटाता है।

मान: यदि ग्रेस्केल हो तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


लंबाई को प्राप्त या सेट करता है।

मान: लंबाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस आंशिक रूप से लोड है या नहीं।

मान: यदि यह इंस्टेंस आंशिक रूप से लोड है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


स्मूद को प्राप्त या सेट करता है।

मान: स्मूद।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


SNR (signal-to-noise ratio) को प्राप्त या सेट करता है, अनुशंसित सीमा 0.002 - 0.009, डिफ़ॉल्ट मान = 0.007।

मान: SNR।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

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

