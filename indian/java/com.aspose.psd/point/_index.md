---
title: "Point"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक क्रमबद्ध जोड़ी पूर्णांक x- और y-निर्देशांक को दर्शाता है जो दो-आयामी तल में एक बिंदु को परिभाषित करता है।"
type: docs
weight: 82
url: /hi/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

एक क्रमबद्ध जोड़ी पूर्णांक x- और y-निर्देशांक को दर्शाता है जो दो-आयामी तल में एक बिंदु को परिभाषित करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | निर्दिष्ट निर्देशांक के साथ Aspose.Imaging.Point संरचना का नया उदाहरण आरंभ करता है। |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Aspose.Imaging.Size संरचना से Aspose.Imaging.Point संरचना का नया उदाहरण आरंभ करता है। |
| [Point(int dw)](#Point-int-) | एक पूर्णांक मान द्वारा निर्दिष्ट निर्देशांक का उपयोग करके  Aspose.Imaging.Point  संरचना का नया उदाहरण आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | बिंदु प्रारूप का प्रतिनिधित्व करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | निर्दिष्ट  Aspose.Imaging.Size  को निर्दिष्ट  Aspose.Imaging.Point  में जोड़ता है। |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | निर्दिष्ट  Aspose.Imaging.PointF  को  Aspose.Imaging.Point  में परिवर्तित करता है, जिसमें  Aspose.Imaging.PointF  के मानों को अगले बड़े पूर्णांक मान तक गोल किया जाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट  System.Object  के समान निर्देशांक हैं या नहीं, यह निर्धारित करता है कि यह  Aspose.Imaging.Point  वही निर्देशांक रखता है। |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | एक नया  Aspose.Imaging.Point  संरचना का उदाहरण प्राप्त करता है, जिसमें  Aspose.Imaging.Point.X  और  Aspose.Imaging.Point.Y  मान शून्य पर सेट होते हैं। |
| [getX()](#getX--) | इस  Aspose.Imaging.Point  का x-निर्देशांक प्राप्त करता है या सेट करता है। |
| [getY()](#getY--) | इस  Aspose.Imaging.Point  का y-निर्देशांक प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) | इस  Aspose.Imaging.Point  के लिए एक हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि यह  Aspose.Imaging.Point  खाली है या नहीं। |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | इस  Aspose.Imaging.Point  को निर्दिष्ट  Aspose.Imaging.Point  द्वारा स्थानांतरित करता है। |
| [offset(int dx, int dy)](#offset-int-int-) | इस  Aspose.Imaging.Point  को निर्दिष्ट मात्रा द्वारा स्थानांतरित करता है। |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | एक  Aspose.Imaging.Point  को दिए गए  Aspose.Imaging.Size  द्वारा स्थानांतरित करता है। |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | दो  Aspose.Imaging.Point  वस्तुओं की तुलना करता है। |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | दो  Aspose.Imaging.Point  वस्तुओं की तुलना करता है। |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | एक  Aspose.Imaging.Point  को दिए गए  Aspose.Imaging.Size  के नकारात्मक द्वारा स्थानांतरित करता है। |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | निर्दिष्ट  Aspose.Imaging.PointF  को  Aspose.Imaging.Point  वस्तु में परिवर्तित करता है, जिसमें  Aspose.Imaging.Point  के मानों को निकटतम पूर्णांक तक गोल किया जाता है। |
| [setX(int value)](#setX-int-) | इस  Aspose.Imaging.Point  का x-निर्देशांक प्राप्त करता है या सेट करता है। |
| [setY(int value)](#setY-int-) | इस  Aspose.Imaging.Point  का y-निर्देशांक प्राप्त करता है या सेट करता है। |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | निर्दिष्ट  Aspose.Imaging.Point  से निर्दिष्ट  Aspose.Imaging.Size  घटाने का परिणाम लौटाता है। |
| [toString()](#toString--) | इस  Aspose.Imaging.Point  को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | निर्दिष्ट  Point  संरचना को  PointF  संरचना में परिवर्तित करता है। |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | निर्दिष्ट  Aspose.Imaging.Point  संरचना को  Aspose.Imaging.Size  संरचना में परिवर्तित करता है। |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | निर्दिष्ट  Aspose.Imaging.PointF  को  Aspose.Imaging.Point  में परिवर्तित करता है, जिसमें  Aspose.Imaging.Point  के मानों को काटकर (ट्रंकेट) किया जाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


निर्दिष्ट निर्देशांक के साथ Aspose.Imaging.Point संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | बिंदु की क्षैतिज स्थिति। |
| y | int | बिंदु की लंबवत स्थिति। |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Aspose.Imaging.Size संरचना से Aspose.Imaging.Point संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | नए बिंदु के निर्देशांक शामिल करता है। |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


एक पूर्णांक मान द्वारा निर्दिष्ट निर्देशांक का उपयोग करके  Aspose.Imaging.Point  संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dw | int | एक 32-बिट पूर्णांक जो नए बिंदु के लिए निर्देशांक निर्दिष्ट करता है। |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


बिंदु प्रारूप का प्रतिनिधित्व करता है।

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


निर्दिष्ट  Aspose.Imaging.Size  को निर्दिष्ट  Aspose.Imaging.Point  में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | जिसमें जोड़ना है वह  Aspose.Imaging.Point । |
| size | [Size](../../com.aspose.psd/size) | यह  Aspose.Imaging.Size  को बिंदु में जोड़ने के लिए। |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


निर्दिष्ट  Aspose.Imaging.PointF  को  Aspose.Imaging.Point  में परिवर्तित करता है, जिसमें  Aspose.Imaging.PointF  के मानों को अगले बड़े पूर्णांक मान तक गोल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | यह  Aspose.Imaging.PointF  को परिवर्तित करने के लिए। |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्दिष्ट  System.Object  के समान निर्देशांक हैं या नहीं, यह निर्धारित करता है कि यह  Aspose.Imaging.Point  वही निर्देशांक रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण के लिए  System.Object । |

**Returns:**
boolean - सत्य यदि  obj  एक  Aspose.Imaging.Point  है और इस  Aspose.Imaging.Point  के समान निर्देशांक रखता है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


एक नया  Aspose.Imaging.Point  संरचना का उदाहरण प्राप्त करता है, जिसमें  Aspose.Imaging.Point.X  और  Aspose.Imaging.Point.Y  मान शून्य पर सेट होते हैं।

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


इस  Aspose.Imaging.Point  का x-निर्देशांक प्राप्त करता है या सेट करता है।

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


इस  Aspose.Imaging.Point  का y-निर्देशांक प्राप्त करता है या सेट करता है।

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस  Aspose.Imaging.Point  के लिए एक हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह  Aspose.Imaging.Point  खाली है या नहीं।

**Returns:**
boolean - सत्य यदि दोनों  Aspose.Imaging.Point.X  और  Aspose.Imaging.Point.Y  0 हैं; अन्यथा, असत्य।
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

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




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


इस  Aspose.Imaging.Point  को निर्दिष्ट  Aspose.Imaging.Point  द्वारा स्थानांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह  Aspose.Imaging.Point  इस  Aspose.Imaging.Point  को ऑफसेट करने के लिए उपयोग किया जाता है। |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


इस  Aspose.Imaging.Point  को निर्दिष्ट मात्रा द्वारा स्थानांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | int | x-निर्देशांक को ऑफसेट करने की मात्रा। |
| dy | int | y-निर्देशांक को ऑफसेट करने की मात्रा। |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


एक  Aspose.Imaging.Point  को दिए गए  Aspose.Imaging.Size  द्वारा स्थानांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह  Aspose.Imaging.Point  को अनुवाद करने के लिए है। |
| size | [Size](../../com.aspose.psd/size) | एक  Aspose.Imaging.Size  जो बिंदु के निर्देशांक में जोड़ने के लिए संख्याओं की जोड़ी निर्दिष्ट करता है। |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


दो  Aspose.Imaging.Point  वस्तुओं की तुलना करता है। परिणाम निर्दिष्ट करता है कि दो  Aspose.Imaging.Point  वस्तुओं के  Aspose.Imaging.Point.X  और  Aspose.Imaging.Point.Y  गुणों के मान समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | पहला  Aspose.Imaging.Point  तुलना करने के लिए। |
| point2 | [Point](../../com.aspose.psd/point) | दूसरा  Aspose.Imaging.Point  तुलना करने के लिए। |

**Returns:**
boolean - सत्य यदि  Aspose.Imaging.Point.X  और  Aspose.Imaging.Point.Y  के मान point1 और point2 के समान हैं; अन्यथा, असत्य।
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


दो  Aspose.Imaging.Point  वस्तुओं की तुलना करता है। परिणाम निर्दिष्ट करता है कि दो  Aspose.Imaging.Point  वस्तुओं के  Aspose.Imaging.Point.X  या  Aspose.Imaging.Point.Y  गुणों के मान असमान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | पहला  Aspose.Imaging.Point  तुलना करने के लिए। |
| point2 | [Point](../../com.aspose.psd/point) | दूसरा  Aspose.Imaging.Point  तुलना करने के लिए। |

**Returns:**
boolean - सत्य यदि point1 और point2 के  Aspose.Imaging.Point.X  या  Aspose.Imaging.Point.Y  गुणों में से किसी का मान भिन्न है; अन्यथा, असत्य।
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


एक  Aspose.Imaging.Point  को दिए गए  Aspose.Imaging.Size  के नकारात्मक द्वारा स्थानांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह  Aspose.Imaging.Point  को अनुवाद करने के लिए है। |
| size | [Size](../../com.aspose.psd/size) | एक  Aspose.Imaging.Size  जो बिंदु के निर्देशांक से घटाने के लिए संख्याओं की जोड़ी निर्दिष्ट करता है। |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


निर्दिष्ट  Aspose.Imaging.PointF  को  Aspose.Imaging.Point  वस्तु में परिवर्तित करता है, जिसमें  Aspose.Imaging.Point  के मानों को निकटतम पूर्णांक तक गोल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | यह  Aspose.Imaging.PointF  को परिवर्तित करने के लिए। |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


इस  Aspose.Imaging.Point  का x-निर्देशांक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


इस  Aspose.Imaging.Point  का y-निर्देशांक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


निर्दिष्ट  Aspose.Imaging.Point  से निर्दिष्ट  Aspose.Imaging.Size  घटाने का परिणाम लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह  Aspose.Imaging.Point  जिससे घटाया जाएगा। |
| size | [Size](../../com.aspose.psd/size) | यह  Aspose.Imaging.Size  बिंदु से घटाने के लिए है। |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


इस  Aspose.Imaging.Point  को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है।

**Returns:**
java.lang.String - एक  System.String  जो इस उदाहरण का प्रतिनिधित्व करता है।
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


निर्दिष्ट  Point  संरचना को  PointF  संरचना में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह  Point  रूपांतरित किया जाना है। |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


निर्दिष्ट  Aspose.Imaging.Point  संरचना को  Aspose.Imaging.Size  संरचना में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह  Aspose.Imaging.Point  रूपांतरित किया जाना है। |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


निर्दिष्ट  Aspose.Imaging.PointF  को  Aspose.Imaging.Point  में परिवर्तित करता है, जिसमें  Aspose.Imaging.Point  के मानों को काटकर (ट्रंकेट) किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | यह  Aspose.Imaging.PointF  को परिवर्तित करने के लिए। |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

