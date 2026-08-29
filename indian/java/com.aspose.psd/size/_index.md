---
title: "Size"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आकार को दर्शाता है।"
type: docs
weight: 98
url: /hi/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

आकार को दर्शाता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | निर्दिष्ट Aspose.Imaging.Point से Aspose.Imaging.Size संरचना का नया उदाहरण प्रारंभ करता है। |
| [Size(int width, int height)](#Size-int-int-) | निर्दिष्ट आयामों से Aspose.Imaging.Size संरचना का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | एक Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | निर्दिष्ट Aspose.Imaging.SizeF संरचना को Aspose.Imaging.Size संरचना में परिवर्तित करता है, Aspose.Imaging.Size संरचना के मानों को अगले उच्च पूर्णांक मान तक गोल करके। |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचता है कि निर्दिष्ट वस्तु  Aspose.Imaging.Size  है या नहीं, जिसका आयाम इस  Aspose.Imaging.Size  के समान है। |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | एक नया  Aspose.Imaging.Size  संरचना का उदाहरण प्राप्त करता है, जिसकी  Aspose.Imaging.Size.Width  और  Aspose.Imaging.Size.Height  मान शून्य पर सेट होते हैं। |
| [getHeight()](#getHeight--) | इस  Aspose.Imaging.Size  का ऊर्ध्वाधर घटक प्राप्त करता या सेट करता है। |
| [getWidth()](#getWidth--) | इस  Aspose.Imaging.Size  का क्षैतिज घटक प्राप्त करता या सेट करता है। |
| [hashCode()](#hashCode--) | इस  Aspose.Imaging.Size  संरचना के लिए एक हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि इस  Aspose.Imaging.Size  की चौड़ाई और ऊँचाई 0 है या नहीं। |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | एक Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | जाँचता है कि दो  Aspose.Imaging.Size  संरचनाएँ समान हैं या नहीं। |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | जाँचता है कि दो  Aspose.Imaging.Size  संरचनाएँ अलग हैं या नहीं। |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | एक  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई को दूसरी  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | निर्दिष्ट  Aspose.Imaging.SizeF  संरचना को  Aspose.Imaging.Size  संरचना में बदलता है, जिसमें  Aspose.Imaging.SizeF  संरचना के मानों को निकटतम पूर्णांक तक गोल किया जाता है। |
| [setHeight(int value)](#setHeight-int-) | इस  Aspose.Imaging.Size  का ऊर्ध्वाधर घटक प्राप्त करता या सेट करता है। |
| [setWidth(int value)](#setWidth-int-) | इस  Aspose.Imaging.Size  का क्षैतिज घटक प्राप्त करता या सेट करता है। |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | एक  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई को दूसरी  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| [toString()](#toString--) | एक मानव-पठनीय स्ट्रिंग बनाता है जो इस  Aspose.Imaging.Size  को दर्शाती है। |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | निर्दिष्ट  Aspose.Imaging.Size  को  Aspose.Imaging.Point  में बदलता है। |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | निर्दिष्ट  Aspose.Imaging.Size  को  Aspose.Imaging.SizeF  में बदलता है। |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | निर्दिष्ट  Aspose.Imaging.SizeF  संरचना को  Aspose.Imaging.Size  संरचना में बदलता है, जिसमें  Aspose.Imaging.SizeF  संरचना के मानों को अगले निचले पूर्णांक तक काटा जाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


निर्दिष्ट Aspose.Imaging.Point से Aspose.Imaging.Size संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | वह  Aspose.Imaging.Point  जिससे इस  Aspose.Imaging.Size  को प्रारंभ किया जाता है। |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


निर्दिष्ट आयामों से Aspose.Imaging.Size संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | नए  Aspose.Imaging.Size  का चौड़ाई घटक। |
| height | int | नए  Aspose.Imaging.Size  का ऊँचाई घटक। |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


एक Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | पहला  Aspose.Imaging.Size  जिसे जोड़ा जाना है। |
| size2 | [Size](../../com.aspose.psd/size) | दूसरा  Aspose.Imaging.Size  जिसे जोड़ा जाना है। |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


निर्दिष्ट Aspose.Imaging.SizeF संरचना को Aspose.Imaging.Size संरचना में परिवर्तित करता है, Aspose.Imaging.Size संरचना के मानों को अगले उच्च पूर्णांक मान तक गोल करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | बदलने के लिए  Aspose.Imaging.SizeF  संरचना। |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचता है कि निर्दिष्ट वस्तु  Aspose.Imaging.Size  है या नहीं, जिसका आयाम इस  Aspose.Imaging.Size  के समान है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण के लिए  System.Object । |

**Returns:**
boolean - true यदि  obj  एक  Aspose.Imaging.Size  है और इसकी चौड़ाई व ऊँचाई इस  Aspose.Imaging.Size  के समान है; अन्यथा, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


एक नया  Aspose.Imaging.Size  संरचना का उदाहरण प्राप्त करता है, जिसकी  Aspose.Imaging.Size.Width  और  Aspose.Imaging.Size.Height  मान शून्य पर सेट होते हैं।

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


इस  Aspose.Imaging.Size  का ऊर्ध्वाधर घटक प्राप्त करता या सेट करता है।

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


इस  Aspose.Imaging.Size  का क्षैतिज घटक प्राप्त करता या सेट करता है।

**Returns:**
int
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


एक मान प्राप्त करता है जो दर्शाता है कि इस  Aspose.Imaging.Size  की चौड़ाई और ऊँचाई 0 है या नहीं।

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


एक Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई को दूसरी Aspose.Imaging.Size संरचना की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | पहला  Aspose.Imaging.Size  जिसे जोड़ा जाना है। |
| size2 | [Size](../../com.aspose.psd/size) | दूसरा  Aspose.Imaging.Size  जिसे जोड़ा जाना है। |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


जाँचता है कि दो  Aspose.Imaging.Size  संरचनाएँ समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | समानता ऑपरेटर के बाएँ पक्ष पर स्थित  Aspose.Imaging.Size  संरचना। |
| size2 | [Size](../../com.aspose.psd/size) | समानता ऑपरेटर के दाएँ पक्ष पर स्थित  Aspose.Imaging.Size  संरचना। |

**Returns:**
boolean - true यदि  size1  और  size2  की चौड़ाई और ऊँचाई समान हैं; अन्यथा, false.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


जाँचता है कि दो  Aspose.Imaging.Size  संरचनाएँ अलग हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | असमानता ऑपरेटर के बाएँ पक्ष में Aspose.Imaging.Size संरचना। |
| size2 | [Size](../../com.aspose.psd/size) | असमानता ऑपरेटर के दाएँ पक्ष में Aspose.Imaging.Size संरचना। |

**Returns:**
boolean - यदि size1 और size2 चौड़ाई या ऊँचाई में अलग हों तो True; यदि size1 और size2 बराबर हों तो false।
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


एक  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई को दूसरी  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | घटाव ऑपरेटर के बाएँ पक्ष में Aspose.Imaging.Size संरचना। |
| size2 | [Size](../../com.aspose.psd/size) | घटाव ऑपरेटर के दाएँ पक्ष में Aspose.Imaging.Size संरचना। |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


निर्दिष्ट  Aspose.Imaging.SizeF  संरचना को  Aspose.Imaging.Size  संरचना में बदलता है, जिसमें  Aspose.Imaging.SizeF  संरचना के मानों को निकटतम पूर्णांक तक गोल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | बदलने के लिए  Aspose.Imaging.SizeF  संरचना। |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


इस  Aspose.Imaging.Size  का ऊर्ध्वाधर घटक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


इस  Aspose.Imaging.Size  का क्षैतिज घटक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


एक  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई को दूसरी  Aspose.Imaging.Size  संरचना की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | घटाव ऑपरेटर के बाएँ पक्ष में Aspose.Imaging.Size संरचना। |
| size2 | [Size](../../com.aspose.psd/size) | घटाव ऑपरेटर के दाएँ पक्ष में Aspose.Imaging.Size संरचना। |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


एक मानव-पठनीय स्ट्रिंग बनाता है जो इस  Aspose.Imaging.Size  को दर्शाती है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस Aspose.Imaging.Size को दर्शाती है।
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


निर्दिष्ट  Aspose.Imaging.Size  को  Aspose.Imaging.Point  में बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | परिवर्तित करने के लिए Aspose.Imaging.Size। |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


निर्दिष्ट  Aspose.Imaging.Size  को  Aspose.Imaging.SizeF  में बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | परिवर्तित करने के लिए Aspose.Imaging.Size। |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


निर्दिष्ट  Aspose.Imaging.SizeF  संरचना को  Aspose.Imaging.Size  संरचना में बदलता है, जिसमें  Aspose.Imaging.SizeF  संरचना के मानों को अगले निचले पूर्णांक तक काटा जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | बदलने के लिए  Aspose.Imaging.SizeF  संरचना। |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

