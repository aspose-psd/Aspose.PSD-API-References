---
title: "SizeF"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आमतौर पर एक आयत की चौड़ाई और ऊँचाई को दर्शाने वाले फ्लोटिंग-पॉइंट संख्याओं की क्रमबद्ध जोड़ी को संग्रहीत करता है।"
type: docs
weight: 99
url: /hi/java/com.aspose.psd/sizef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

फ़्लोटिंग‑पॉइंट संख्याओं का क्रमबद्ध युग्म संग्रहीत करता है, आमतौर पर आयत की चौड़ाई और ऊँचाई।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.psd.SizeF-) | निर्दिष्ट Aspose.Imaging.SizeF से Aspose.Imaging.SizeF संरचना का नया उदाहरण आरंभ करता है। |
| [SizeF(PointF point)](#SizeF-com.aspose.psd.PointF-) | निर्दिष्ट Aspose.Imaging.PointF से Aspose.Imaging.SizeF संरचना का नया उदाहरण आरंभ करता है। |
| [SizeF(float width, float height)](#SizeF-float-float-) | निर्दिष्ट आयामों से Aspose.Imaging.SizeF संरचना का नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.psd.SizeF-) |  |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचता है कि क्या निर्दिष्ट वस्तु इस Aspose.Imaging.SizeF के समान आयामों वाला Aspose.Imaging.SizeF है। |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | एक नया Aspose.Imaging.SizeF संरचना प्राप्त करता है जिसकी Aspose.Imaging.SizeF.Width और Aspose.Imaging.SizeF.Height मान शून्य पर सेट हैं। |
| [getHeight()](#getHeight--) | इस Aspose.Imaging.SizeF का ऊर्ध्वाधर घटक प्राप्त करता है या सेट करता है। |
| [getWidth()](#getWidth--) | इस Aspose.Imaging.SizeF का क्षैतिज घटक प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) | इस  Aspose.Imaging.Size  संरचना के लिए एक हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि इस Aspose.Imaging.SizeF की चौड़ाई और ऊँचाई शून्य है या नहीं। |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | जाँचता है कि दो Aspose.Imaging.SizeF संरचनाएँ समान हैं या नहीं। |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | जाँचता है कि दो Aspose.Imaging.SizeF संरचनाएँ अलग हैं या नहीं। |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| [setHeight(float value)](#setHeight-float-) | इस Aspose.Imaging.SizeF का ऊर्ध्वाधर घटक प्राप्त करता है या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | इस Aspose.Imaging.SizeF का क्षैतिज घटक प्राप्त करता है या सेट करता है। |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| [toPointF()](#toPointF--) | एक Aspose.Imaging.SizeF को Aspose.Imaging.PointF में परिवर्तित करता है। |
| [toSize()](#toSize--) | एक Aspose.Imaging.SizeF को कटे हुए आकार मानों के साथ Aspose.Imaging.Size संरचना में परिवर्तित करता है। |
| [toString()](#toString--) | एक मानव-पठनीय स्ट्रिंग बनाता है जो इस Aspose.Imaging.SizeF को दर्शाती है। |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.psd.SizeF-) | निर्दिष्ट Aspose.Imaging.SizeF को Aspose.Imaging.PointF में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.psd.SizeF-}
```
public SizeF(SizeF size)
```


निर्दिष्ट Aspose.Imaging.SizeF से Aspose.Imaging.SizeF संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | वह Aspose.Imaging.SizeF जिससे नया Aspose.Imaging.SizeF बनाया जाता है। |

### SizeF(PointF point) {#SizeF-com.aspose.psd.PointF-}
```
public SizeF(PointF point)
```


निर्दिष्ट Aspose.Imaging.PointF से Aspose.Imaging.SizeF संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | वह Aspose.Imaging.PointF जिससे यह Aspose.Imaging.SizeF प्रारंभ किया जाता है। |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


निर्दिष्ट आयामों से Aspose.Imaging.SizeF संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | नए Aspose.Imaging.SizeF का चौड़ाई घटक। |
| height | float | नए Aspose.Imaging.SizeF का ऊँचाई घटक। |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.psd/sizef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(SizeF that) {#CloneTo-com.aspose.psd.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.psd/sizef) |  |

### add(SizeF size1, SizeF size2) {#add-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | पहला जोड़ने योग्य Aspose.Imaging.SizeF। |
| size2 | [SizeF](../../com.aspose.psd/sizef) | दूसरा जोड़ने योग्य Aspose.Imaging.SizeF। |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  Aspose.Imaging.SizeF  structure that is the result of the addition operation.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचता है कि क्या निर्दिष्ट वस्तु इस Aspose.Imaging.SizeF के समान आयामों वाला Aspose.Imaging.SizeF है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण के लिए  System.Object । |

**Returns:**
boolean - यह विधि true लौटाती है यदि obj एक Aspose.Imaging.SizeF है और इस Aspose.Imaging.SizeF के समान चौड़ाई और ऊँचाई रखता है; अन्यथा false।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


एक नया Aspose.Imaging.SizeF संरचना प्राप्त करता है जिसकी Aspose.Imaging.SizeF.Width और Aspose.Imaging.SizeF.Height मान शून्य पर सेट हैं।

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


इस Aspose.Imaging.SizeF का ऊर्ध्वाधर घटक प्राप्त करता है या सेट करता है।

**Returns:**
float - इस Aspose.Imaging.SizeF का ऊर्ध्वाधर घटक, सामान्यतः पिक्सेल में मापा जाता है।
### getWidth() {#getWidth--}
```
public float getWidth()
```


इस Aspose.Imaging.SizeF का क्षैतिज घटक प्राप्त करता है या सेट करता है।

**Returns:**
float - इस Aspose.Imaging.SizeF का क्षैतिज घटक, सामान्यतः पिक्सेल में मापा जाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस  Aspose.Imaging.Size  संरचना के लिए एक हैश कोड लौटाता है।

**Returns:**
int - एक पूर्णांक मान जो इस  Aspose.Imaging.Size  संरचना के लिए हैश मान निर्दिष्ट करता है।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि इस Aspose.Imaging.SizeF की चौड़ाई और ऊँचाई शून्य है या नहीं।

**Returns:**
boolean - यह गुण true लौटाता है जब इस Aspose.Imaging.SizeF की चौड़ाई और ऊँचाई दोनों शून्य हों; अन्यथा false।
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.psd/sizef) |  |
| obj2 | [SizeF](../../com.aspose.psd/sizef) |  |

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




### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | पहला जोड़ने योग्य Aspose.Imaging.SizeF। |
| size2 | [SizeF](../../com.aspose.psd/sizef) | दूसरा जोड़ने योग्य Aspose.Imaging.SizeF। |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  Aspose.Imaging.SizeF  structure that is the result of the addition operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


जाँचता है कि दो Aspose.Imaging.SizeF संरचनाएँ समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | समानता ऑपरेटर के बाएँ पक्ष में Aspose.Imaging.SizeF संरचना। |
| size2 | [SizeF](../../com.aspose.psd/sizef) | समानता ऑपरेटर के दाएँ पक्ष में Aspose.Imaging.SizeF संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि size1 और size2 की चौड़ाई और ऊँचाई समान हों; अन्यथा false।
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


जाँचता है कि दो Aspose.Imaging.SizeF संरचनाएँ अलग हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | असमानता ऑपरेटर के बाएँ पक्ष में Aspose.Imaging.SizeF संरचना। |
| size2 | [SizeF](../../com.aspose.psd/sizef) | असमानता ऑपरेटर के दाएँ पक्ष में Aspose.Imaging.SizeF संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि size1 और size2 में चौड़ाई या ऊँचाई में अंतर हो; यदि size1 और size2 समान हों तो false।
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | घटाव ऑपरेटर के बाएँ पक्ष में Aspose.Imaging.SizeF। |
| size2 | [SizeF](../../com.aspose.psd/sizef) | घटाव ऑपरेटर के दाएँ पक्ष में Aspose.Imaging.SizeF। |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  Aspose.Imaging.SizeF  that is the result of the subtraction operation.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


इस Aspose.Imaging.SizeF का ऊर्ध्वाधर घटक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


इस Aspose.Imaging.SizeF का क्षैतिज घटक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


एक Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.SizeF संरचना की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | घटाव ऑपरेटर के बाएँ पक्ष में Aspose.Imaging.SizeF संरचना। |
| size2 | [SizeF](../../com.aspose.psd/sizef) | घटाव ऑपरेटर के दाएँ पक्ष में Aspose.Imaging.SizeF संरचना। |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  that is a result of the subtraction operation.
### toPointF() {#toPointF--}
```
public PointF toPointF()
```


एक Aspose.Imaging.SizeF को Aspose.Imaging.PointF में परिवर्तित करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns a  Aspose.Imaging.PointF  structure.
### toSize() {#toSize--}
```
public Size toSize()
```


एक Aspose.Imaging.SizeF को कटे हुए आकार मानों के साथ Aspose.Imaging.Size संरचना में परिवर्तित करता है।

**Returns:**
[Size](../../com.aspose.psd/size) - Returns a  Aspose.Imaging.Size  structure.
### toString() {#toString--}
```
public String toString()
```


एक मानव-पठनीय स्ट्रिंग बनाता है जो इस Aspose.Imaging.SizeF को दर्शाती है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस Aspose.Imaging.SizeF का प्रतिनिधित्व करती है।
### to_PointF(SizeF size) {#to-PointF-com.aspose.psd.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


निर्दिष्ट Aspose.Imaging.SizeF को Aspose.Imaging.PointF में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | परिवर्तित करने के लिए Aspose.Imaging.SizeF संरचना। |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  Aspose.Imaging.PointF  structure to which this operator converts.
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

