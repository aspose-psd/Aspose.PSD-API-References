---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "स्वचालित मास्किंग विधियों के लिए निर्दिष्ट तर्कों को दर्शाता है।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

स्वचालित मास्किंग विधियों के लिए निर्दिष्ट तर्कों को दर्शाता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | अधिकतम पुनरावृत्तियों की संख्या प्राप्त करता है। |
| [getNumberOfObjects()](#getNumberOfObjects--) | प्रारंभिक छवि को अलग करने के लिए वस्तुओं की संख्या प्राप्त करता है (वैकल्पिक), डिफ़ॉल्ट मान 2 है (वस्तु और पृष्ठभूमि)। |
| [getObjectsPoints()](#getObjectsPoints--) | अलग की गई वस्तुओं से संबंधित बिंदुओं को प्राप्त करता है (वैकल्पिक) NumberOfObjects निर्देशांक जो प्रारंभिक छवि की NumberOfObjects वस्तुओं से संबंधित हैं। |
| [getObjectsRectangles()](#getObjectsRectangles--) | अलग की गई वस्तुओं से संबंधित वस्तु आयतें प्राप्त करता है (वैकल्पिक)। |
| [getOrphanedPoints()](#getOrphanedPoints--) | ऐसे बिंदु प्राप्त करता है जो अब किसी भी वस्तु से संबंधित नहीं हैं (वैकल्पिक)। |
| [getPrecision()](#getPrecision--) | विभाजन विधि की सटीकता प्राप्त करता है (वैकल्पिक)। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | अधिकतम पुनरावृत्तियों की संख्या सेट करता है। |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | प्रारंभिक छवि को अलग करने के लिए वस्तुओं की संख्या सेट करता है (वैकल्पिक), डिफ़ॉल्ट मान 2 है (वस्तु और पृष्ठभूमि)। |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | अलग की गई वस्तुओं से संबंधित बिंदुओं को सेट करता है (वैकल्पिक) NumberOfObjects निर्देशांक जो प्रारंभिक छवि की NumberOfObjects वस्तुओं से संबंधित हैं। |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | अलग की गई वस्तुओं से संबंधित वस्तु आयतें सेट करता है (वैकल्पिक)। |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | ऐसे बिंदु सेट करता है जो अब किसी भी वस्तु से संबंधित नहीं हैं (वैकल्पिक)। |
| [setPrecision(double value)](#setPrecision-double-) | विभाजन विधि की सटीकता सेट करता है (वैकल्पिक)। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
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
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


अधिकतम पुनरावृत्तियों की संख्या प्राप्त करता है।

मान: अधिकतम अधिकतम पुनरावृत्तियों की संख्या।

**Returns:**
int - अधिकतम पुनरावृत्तियों की संख्या।
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


प्रारंभिक छवि को अलग करने के लिए वस्तुओं की संख्या प्राप्त करता है (वैकल्पिक), डिफ़ॉल्ट मान 2 है (वस्तु और पृष्ठभूमि)।

मान: वस्तुओं की संख्या।

**Returns:**
int - प्रारंभिक छवि को अलग करने के लिए वस्तुओं की संख्या (वैकल्पिक), डिफ़ॉल्ट मान 2 है (वस्तु और पृष्ठभूमि)।
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


अलग की गई वस्तुओं से संबंधित बिंदुओं को प्राप्त करता है (वैकल्पिक) NumberOfObjects निर्देशांक जो प्रारंभिक छवि की NumberOfObjects वस्तुओं से संबंधित हैं। यह पैरामीटर विभाजन विधि की सटीकता बढ़ाने के लिए उपयोग किया जाता है।

मान: वस्तुओं के बिंदु।

**Returns:**
com.aspose.psd.Point[][] - अलग-अलग वस्तुओं से संबंधित बिंदु (वैकल्पिक) NumberOfObjects निर्देशांक जो प्रारंभिक छवि के NumberOfObjects वस्तुओं से संबंधित हैं।
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


अलग-अलग वस्तुओं से संबंधित वस्तुओं के आयत प्राप्त करता है (वैकल्पिक)। इस पैरामीटर का उपयोग विभाजन विधि की सटीकता बढ़ाने के लिए किया जाता है।

मान: वस्तुओं के आयत।

**Returns:**
com.aspose.psd.Rectangle[] - अलग-अलग वस्तुओं से संबंधित वस्तुओं के आयत (वैकल्पिक)।
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


किसी भी वस्तु से अब संबंधित न रहने वाले बिंदु प्राप्त करता है (वैकल्पिक)। यह पैरामीटर केवल पुनः-विभाजन के मामले में उपयोग किया जाता है।

मान: अनाथ बिंदु।

**Returns:**
com.aspose.psd.Point[] - वह बिंदु जो अब किसी भी वस्तु से संबंधित नहीं हैं (वैकल्पिक)।
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


विभाजन विधि की सटीकता प्राप्त करता है (वैकल्पिक)।

मान: विभाजन विधि की सटीकता (वैकल्पिक)।

**Returns:**
double - विभाजन विधि की सटीकता (वैकल्पिक)।
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


अधिकतम पुनरावृत्तियों की संख्या सेट करता है।

मान: अधिकतम अधिकतम पुनरावृत्तियों की संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | अधिकतम पुनरावृत्तियों की संख्या। |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


प्रारंभिक छवि को अलग करने के लिए वस्तुओं की संख्या सेट करता है (वैकल्पिक), डिफ़ॉल्ट मान 2 है (वस्तु और पृष्ठभूमि)।

मान: वस्तुओं की संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | प्रारंभिक छवि को विभाजित करने के लिए वस्तुओं की संख्या (वैकल्पिक), डिफ़ॉल्ट मान 2 है (वस्तु और पृष्ठभूमि)। |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


अलग-अलग वस्तुओं से संबंधित बिंदुओं को सेट करता है (वैकल्पिक) NumberOfObjects निर्देशांक जो प्रारंभिक छवि के NumberOfObjects वस्तुओं से संबंधित हैं। इस पैरामीटर का उपयोग विभाजन विधि की सटीकता बढ़ाने के लिए किया जाता है।

मान: वस्तुओं के बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | अलग-अलग वस्तुओं से संबंधित बिंदु (वैकल्पिक) NumberOfObjects निर्देशांक जो प्रारंभिक छवि के NumberOfObjects वस्तुओं से संबंधित हैं। |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


अलग-अलग वस्तुओं से संबंधित वस्तुओं के आयत को सेट करता है (वैकल्पिक)। इस पैरामीटर का उपयोग विभाजन विधि की सटीकता बढ़ाने के लिए किया जाता है।

मान: वस्तुओं के आयत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | अलग-अलग वस्तुओं से संबंधित वस्तुओं के आयत (वैकल्पिक)। |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


किसी भी वस्तु से अब संबंधित न रहने वाले बिंदुओं को सेट करता है (वैकल्पिक)। यह पैरामीटर केवल पुनः-विभाजन के मामले में उपयोग किया जाता है।

मान: अनाथ बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | वह बिंदु जो अब किसी भी वस्तु से संबंधित नहीं हैं (वैकल्पिक)। |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


विभाजन विधि की सटीकता सेट करता है (वैकल्पिक)।

मान: विभाजन विधि की सटीकता (वैकल्पिक)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | विभाजन विधि की सटीकता (वैकल्पिक)। |

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

