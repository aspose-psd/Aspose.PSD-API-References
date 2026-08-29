---
title: "TiffSRational"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "टिफ रैशनल टाइप।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.fileformats.tiff/tiffsrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

टिफ रैशनल टाइप।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | TiffSRational क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [TiffSRational(int value)](#TiffSRational-int-) | नया उदाहरण प्रारंभ करता है TiffRational क्लास का। |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | TiffSRational क्लास का नया इंस्टेंस प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Epsilon](#Epsilon) | भिन्न गणना के लिए एप्सिलॉन |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | प्रदान किए गए मान को एक भिन्न में लगभग करता है। |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | प्रदान किए गए मान को एक भिन्न में लगभग करता है। |
| [approximateFraction(float value)](#approximateFraction-float-) | प्रदान किए गए मान को एक भिन्न में लगभग करता है। |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | प्रदान किए गए मान को एक भिन्न में लगभग करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट Object इस इंस्टेंस के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Denominator प्राप्त करता है। |
| [getNominator()](#getNominator--) | Nominator प्राप्त करता है। |
| [getValue()](#getValue--) | फ़्लोट मान प्राप्त करता है। |
| [getValueD()](#getValueD--) | Double मान प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


TiffSRational क्लास का नया इंस्टेंस प्रारंभ करता है।

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


नया उदाहरण प्रारंभ करता है TiffRational क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | Nominator मान। |

Nominator को निर्दिष्ट मान के रूप में उपयोग किया जाएगा और denominator 1 के बराबर होगा। |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


TiffSRational क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nominator | int | Nominator। |
| हर | int | हर। |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


भिन्न गणना के लिए एप्सिलॉन

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


प्रदान किए गए मान को एक भिन्न में लगभग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | मान। |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


प्रदान किए गए मान को एक भिन्न में लगभग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | मान। |
| epsilon | double | अनुमत त्रुटि। |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


प्रदान किए गए मान को एक भिन्न में लगभग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | मान। |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


प्रदान किए गए मान को एक भिन्न में लगभग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | मान। |
| epsilon | double | अनुमत त्रुटि। |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट Object इस इंस्टेंस के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | Object इस इंस्टेंस से तुलना करने के लिए। |

**Returns:**
boolean - true यदि निर्दिष्ट Object इस इंस्टेंस के बराबर है; अन्यथा, false।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Denominator प्राप्त करता है।

मान: Denominator।

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Nominator प्राप्त करता है।

मान: Nominator।

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


फ़्लोट मान प्राप्त करता है।

मान: फ़्लोट मान।

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Double मान प्राप्त करता है।

मान: डबल मान।

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है।

**Returns:**
java.lang.String - एक  System.String  जो इस उदाहरण का प्रतिनिधित्व करता है।
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

