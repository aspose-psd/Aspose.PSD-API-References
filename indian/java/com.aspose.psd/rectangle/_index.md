---
title: "आयत"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक आयत के स्थान और आकार को दर्शाने वाले चार पूर्णांक का सेट संग्रहीत करता है।"
type: docs
weight: 88
url: /hi/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

एक आयत के स्थान और आकार को दर्शाने वाले चार पूर्णांक का सेट संग्रहीत करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | निर्दिष्ट स्थान और आकार के साथ com.aspose.psd.Rectangle संरचना का नया उदाहरण आरंभ करता है। |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | निर्दिष्ट स्थान और आकार के साथ com.aspose.psd.Rectangle संरचना का नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | निर्दिष्ट com.aspose.psd.RectangleF संरचना को com.aspose.psd.Rectangle संरचना में परिवर्तित करता है, जिसमें com.aspose.psd.RectangleF मानों को अगले बड़े पूर्णांक मान तक गोल किया जाता है। |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस com.aspose.psd.Rectangle संरचना के भीतर सम्मिलित है। |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | निर्धारित करता है कि क्या rect द्वारा दर्शाया गया आयताकार क्षेत्र पूरी तरह से इस com.aspose.psd.Rectangle संरचना के भीतर सम्मिलित है। |
| [contains(int x, int y)](#contains-int-int-) | निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस com.aspose.psd.Rectangle संरचना के भीतर सम्मिलित है। |
| [equals(Object obj)](#equals-java.lang.Object-) | परीक्षण करता है कि क्या obj इस com.aspose.psd.Rectangle संरचना के समान स्थान और आकार वाला com.aspose.psd.Rectangle संरचना है। |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | निर्दिष्ट किनारा स्थानों के साथ एक com.aspose.psd.Rectangle संरचना बनाता है। |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | निर्दिष्ट दो बिंदुओं से एक नया  Rectangle  बनाता है। |
| [getBottom()](#getBottom--) | इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.Y और com.aspose.psd.Rectangle.Height गुण मानों का योग होने वाला y-निर्देशांक प्राप्त करता या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | एक नया com.aspose.psd.Rectangle संरचना का उदाहरण प्राप्त करता है, जिसमें com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width और com.aspose.psd.Rectangle.Height मान शून्य पर सेट होते हैं। |
| [getHeight()](#getHeight--) | इस com.aspose.psd.Rectangle संरचना की ऊँचाई प्राप्त करता या सेट करता है। |
| [getLeft()](#getLeft--) | इस com.aspose.psd.Rectangle संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता या सेट करता है। |
| [getLocation()](#getLocation--) | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने के निर्देशांक प्राप्त करता या सेट करता है। |
| [getRight()](#getRight--) | इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.X और com.aspose.psd.Rectangle.Width गुण मानों का योग होने वाला x-निर्देशांक प्राप्त करता या सेट करता है। |
| [getSize()](#getSize--) | इस com.aspose.psd.Rectangle का आकार प्राप्त करता या सेट करता है। |
| [getTop()](#getTop--) | इस com.aspose.psd.Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता या सेट करता है। |
| [getWidth()](#getWidth--) | इस com.aspose.psd.Rectangle संरचना की चौड़ाई प्राप्त करता है। |
| [getX()](#getX--) | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता या सेट करता है। |
| [getY()](#getY--) | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता या सेट करता है। |
| [hashCode()](#hashCode--) | इस com.aspose.psd.Rectangle संरचना के लिए हैश कोड लौटाता है। |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | निर्दिष्ट com.aspose.psd.Rectangle संरचना की फुली हुई प्रति बनाता और लौटाता है। |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | इस com.aspose.psd.Rectangle को निर्दिष्ट मात्रा से फुलाता है। |
| [inflate(int width, int height)](#inflate-int-int-) | इस com.aspose.psd.Rectangle को निर्दिष्ट मात्रा से फुलाता है। |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | इस com.aspose.psd.Rectangle को स्वयं और निर्दिष्ट com.aspose.psd.Rectangle के प्रतिच्छेदन से बदलता है। |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | एक तीसरा com.aspose.psd.Rectangle संरचना लौटाता है जो दो अन्य com.aspose.psd.Rectangle संरचनाओं के प्रतिच्छेदन को दर्शाता है। |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | निर्धारित करता है कि यह आयत rect के साथ प्रतिच्छेद करती है या नहीं। |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि इस com.aspose.psd.Rectangle की सभी संख्यात्मक गुणों के मान शून्य हैं या नहीं। |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह Rectangle कम से कम आंशिक रूप से दृश्यमान है या नहीं |
| [normalize()](#normalize--) | आयत को सामान्यीकृत करता है, इसकी चौड़ाई और ऊँचाई को सकारात्मक बनाकर, बायें को दायें से कम और ऊपर को नीचे से कम करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है। |
| [offset(int x, int y)](#offset-int-int-) | इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है। |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | परीक्षण करता है कि क्या दो com.aspose.psd.Rectangle संरचनाओं का स्थान और आकार समान है। |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | जाँचता है कि दो com.aspose.psd.Rectangle संरचनाएँ स्थान या आकार में अलग हैं या नहीं। |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | निर्दिष्ट com.aspose.psd.RectangleF को निकटतम पूर्णांक मानों तक गोल करके एक com.aspose.psd.Rectangle में परिवर्तित करता है। |
| [setBottom(int value)](#setBottom-int-) | इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.Y और com.aspose.psd.Rectangle.Height गुण मानों का योग होने वाला y-निर्देशांक प्राप्त करता या सेट करता है। |
| [setHeight(int value)](#setHeight-int-) | इस com.aspose.psd.Rectangle संरचना की ऊँचाई प्राप्त करता या सेट करता है। |
| [setLeft(int value)](#setLeft-int-) | इस com.aspose.psd.Rectangle संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता या सेट करता है। |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने के निर्देशांक प्राप्त करता या सेट करता है। |
| [setRight(int value)](#setRight-int-) | इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.X और com.aspose.psd.Rectangle.Width गुण मानों का योग होने वाला x-निर्देशांक प्राप्त करता या सेट करता है। |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | इस com.aspose.psd.Rectangle का आकार प्राप्त करता या सेट करता है। |
| [setTop(int value)](#setTop-int-) | इस com.aspose.psd.Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता या सेट करता है। |
| [setWidth(int value)](#setWidth-int-) | इस com.aspose.psd.Rectangle संरचना की चौड़ाई सेट करता है। |
| [setX(int value)](#setX-int-) | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता या सेट करता है। |
| [setY(int value)](#setY-int-) | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता या सेट करता है। |
| [toString()](#toString--) | इस com.aspose.psd.Rectangle के गुणों को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | निर्दिष्ट com.aspose.psd.RectangleF मानों को काटकर एक com.aspose.psd.Rectangle में परिवर्तित करता है। |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | दो com.aspose.psd.Rectangle संरचनाओं के संघ को सम्मिलित करने वाली एक com.aspose.psd.Rectangle संरचना प्राप्त करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


निर्दिष्ट स्थान और आकार के साथ com.aspose.psd.Rectangle संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | आयत की चौड़ाई। |
| height | int | आयत की ऊँचाई। |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


निर्दिष्ट स्थान और आकार के साथ com.aspose.psd.Rectangle संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | एक com.aspose.psd.Point जो आयताकार क्षेत्र के ऊपर-बाएँ कोने का प्रतिनिधित्व करता है। |
| size | [Size](../../com.aspose.psd/size) | एक com.aspose.psd.Size जो आयताकार क्षेत्र की चौड़ाई और ऊँचाई का प्रतिनिधित्व करता है। |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


निर्दिष्ट com.aspose.psd.RectangleF संरचना को com.aspose.psd.Rectangle संरचना में परिवर्तित करता है, जिसमें com.aspose.psd.RectangleF मानों को अगले बड़े पूर्णांक मान तक गोल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | परिवर्तित की जाने वाली com.aspose.psd.RectangleF संरचना। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस com.aspose.psd.Rectangle संरचना के भीतर सम्मिलित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | परीक्षण के लिए com.aspose.psd.Point। |

**Returns:**
boolean - यह विधि true लौटाती है यदि point द्वारा प्रतिनिधित्व किया गया बिंदु इस com.aspose.psd.Rectangle संरचना के भीतर स्थित है; अन्यथा false।
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


निर्धारित करता है कि क्या rect द्वारा दर्शाया गया आयताकार क्षेत्र पूरी तरह से इस com.aspose.psd.Rectangle संरचना के भीतर सम्मिलित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | परीक्षण के लिए com.aspose.psd.Rectangle। |

**Returns:**
boolean - यह विधि true लौटाती है यदि rect द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र पूरी तरह से इस com.aspose.psd.Rectangle संरचना के भीतर स्थित है; अन्यथा false।
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस com.aspose.psd.Rectangle संरचना के भीतर सम्मिलित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |

**Returns:**
boolean - यह विधि true लौटाती है यदि x और y द्वारा परिभाषित बिंदु इस com.aspose.psd.Rectangle संरचना के भीतर स्थित है; अन्यथा false।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


परीक्षण करता है कि क्या obj इस com.aspose.psd.Rectangle संरचना के समान स्थान और आकार वाला com.aspose.psd.Rectangle संरचना है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण के लिए  System.Object । |

**Returns:**
boolean - यह विधि true लौटाती है यदि obj एक com.aspose.psd.Rectangle संरचना है और उसके com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width, और com.aspose.psd.Rectangle.Height गुण इस com.aspose.psd.Rectangle संरचना के संबंधित गुणों के बराबर हैं; अन्यथा false।
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


निर्दिष्ट किनारा स्थानों के साथ एक com.aspose.psd.Rectangle संरचना बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बायाँ | int | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का x-निर्देशांक। |
| ऊपर | int | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का y-निर्देशांक। |
| दाएँ | int | इस com.aspose.psd.Rectangle संरचना के नीचे-दाएँ कोने का x-निर्देशांक। |
| नीचे | int | इस com.aspose.psd.Rectangle संरचना के नीचे-दाएँ कोने का y-निर्देशांक। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


निर्दिष्ट दो बिंदुओं से एक नया Rectangle बनाता है। बनाए गए Rectangle की दो लंबवत रेखाएँ पास किए गए point1 और point2 के बराबर होंगी। ये आमतौर पर विपरीत शीर्ष बिंदु होते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | नए rectangle के लिए पहला Point। |
| point2 | [Point](../../com.aspose.psd/point) | नए rectangle के लिए दूसरा Point। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.Y और com.aspose.psd.Rectangle.Height गुण मानों का योग होने वाला y-निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
int - यह y-निर्देशांक है जो इस com.aspose.psd.Rectangle के com.aspose.psd.Rectangle.Y और com.aspose.psd.Rectangle.Height का योग है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


एक नया com.aspose.psd.Rectangle संरचना का उदाहरण प्राप्त करता है, जिसमें com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width और com.aspose.psd.Rectangle.Height मान शून्य पर सेट होते हैं।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


इस com.aspose.psd.Rectangle संरचना की ऊँचाई प्राप्त करता या सेट करता है।

**Returns:**
int - इस com.aspose.psd.Rectangle संरचना की ऊँचाई।
### getLeft() {#getLeft--}
```
public int getLeft()
```


इस com.aspose.psd.Rectangle संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
int - इस com.aspose.psd.Rectangle संरचना के बाएँ किनारे का x-निर्देशांक।
### getLocation() {#getLocation--}
```
public Point getLocation()
```


इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने के निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.X और com.aspose.psd.Rectangle.Width गुण मानों का योग होने वाला x-निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
int - यह x-निर्देशांक है जो इस com.aspose.psd.Rectangle के com.aspose.psd.Rectangle.X और com.aspose.psd.Rectangle.Width का योग है।
### getSize() {#getSize--}
```
public Size getSize()
```


इस com.aspose.psd.Rectangle का आकार प्राप्त करता या सेट करता है।

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


इस com.aspose.psd.Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
int - इस com.aspose.psd.Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक।
### getWidth() {#getWidth--}
```
public int getWidth()
```


इस com.aspose.psd.Rectangle संरचना की चौड़ाई प्राप्त करता है।

**Returns:**
int - इस  com.aspose.psd.Rectangle  संरचना की चौड़ाई।
### getX() {#getX--}
```
public int getX()
```


इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
int - इस  com.aspose.psd.Rectangle  संरचना के ऊपर-बाएँ कोने का x-निर्देशांक।
### getY() {#getY--}
```
public int getY()
```


इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
int - इस  com.aspose.psd.Rectangle  संरचना के ऊपर-बाएँ कोने का y-निर्देशांक।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस com.aspose.psd.Rectangle संरचना के लिए हैश कोड लौटाता है।

**Returns:**
int - एक पूर्णांक जो इस आयत के हैश कोड का प्रतिनिधित्व करता है।
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


निर्दिष्ट  com.aspose.psd.Rectangle  संरचना की फुलाई हुई प्रति बनाता है और लौटाता है। प्रति को निर्दिष्ट मात्रा से फुलाया जाता है। मूल  com.aspose.psd.Rectangle  संरचना अपरिवर्तित रहती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | शुरू करने के लिए  com.aspose.psd.Rectangle  । यह आयत संशोधित नहीं की जाती। |
| x | int | इस  com.aspose.psd.Rectangle  को क्षैतिज रूप से फुलाने की मात्रा। |
| y | int | इस  com.aspose.psd.Rectangle  को लंबवत रूप से फुलाने की मात्रा। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


इस com.aspose.psd.Rectangle को निर्दिष्ट मात्रा से फुलाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | इस rectangle को विस्तारित करने की मात्रा। |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


इस com.aspose.psd.Rectangle को निर्दिष्ट मात्रा से फुलाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | इस  com.aspose.psd.Rectangle  को क्षैतिज रूप से फुलाने की मात्रा। |
| height | int | इस  com.aspose.psd.Rectangle  को लंबवत रूप से फुलाने की मात्रा। |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


इस com.aspose.psd.Rectangle को स्वयं और निर्दिष्ट com.aspose.psd.Rectangle के प्रतिच्छेदन से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | जिसके साथ प्रतिच्छेदन करना है वह  com.aspose.psd.Rectangle  । |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


दो अन्य  com.aspose.psd.Rectangle  संरचनाओं के प्रतिच्छेदन को दर्शाने वाली तीसरी  com.aspose.psd.Rectangle  संरचना लौटाता है। यदि कोई प्रतिच्छेदन नहीं है, तो एक खाली  com.aspose.psd.Rectangle  लौटाया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | इंटरसेक्ट करने के लिए पहला rectangle। |
| b | [Rectangle](../../com.aspose.psd/rectangle) | इंटरसेक्ट करने के लिए दूसरा rectangle। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


निर्धारित करता है कि यह आयत rect के साथ प्रतिच्छेद करती है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | परीक्षण करने के लिए rectangle। |

**Returns:**
boolean - यह विधि true लौटाती है यदि कोई प्रतिच्छेदन हो, अन्यथा false।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि इस com.aspose.psd.Rectangle की सभी संख्यात्मक गुणों के मान शून्य हैं या नहीं।

**Returns:**
boolean - यह गुण true लौटाता है यदि इस  com.aspose.psd.Rectangle  के  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X , और  com.aspose.psd.Rectangle.Y  गुणों के सभी मान शून्य हैं; अन्यथा false।
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह Rectangle कम से कम आंशिक रूप से दृश्यमान है या नहीं

**Returns:**
boolean -  true  यदि यह  Rectangle  कम से कम आंशिक रूप से दिखाई देता है; अन्यथा  false .
### normalize() {#normalize--}
```
public void normalize()
```


आयत को सामान्यीकृत करता है, इसकी चौड़ाई और ऊँचाई को सकारात्मक बनाकर, बायें को दायें से कम और ऊपर को नीचे से कम करता है।

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | स्थान को ऑफसेट करने की मात्रा। |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | क्षैतिज ऑफसेट। |
| y | int | लंबवत ऑफसेट। |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


परीक्षण करता है कि क्या दो com.aspose.psd.Rectangle संरचनाओं का स्थान और आकार समान है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | समानता ऑपरेटर के बाएँ स्थित  com.aspose.psd.Rectangle  संरचना। |
| right | [Rectangle](../../com.aspose.psd/rectangle) | समानता ऑपरेटर के दाएँ स्थित  com.aspose.psd.Rectangle  संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि दो  com.aspose.psd.Rectangle  संरचनाओं के  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , और  com.aspose.psd.Rectangle.Height  गुण समान हों।
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


जाँचता है कि दो com.aspose.psd.Rectangle संरचनाएँ स्थान या आकार में अलग हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | असमानता ऑपरेटर के बाएँ स्थित  com.aspose.psd.Rectangle  संरचना। |
| right | [Rectangle](../../com.aspose.psd/rectangle) | असमानता ऑपरेटर के दाएँ स्थित  com.aspose.psd.Rectangle  संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि दो  com.aspose.psd.Rectangle  संरचनाओं के  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  या  com.aspose.psd.Rectangle.Height  गुणों में से कोई भी असमान हो; अन्यथा false।
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


निर्दिष्ट com.aspose.psd.RectangleF को निकटतम पूर्णांक मानों तक गोल करके एक com.aspose.psd.Rectangle में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | परिवर्तित करने के लिए  com.aspose.psd.RectangleF  । |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.Y और com.aspose.psd.Rectangle.Height गुण मानों का योग होने वाला y-निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | यह y-निर्देशांक है जो इस  com.aspose.psd.Rectangle  के  com.aspose.psd.Rectangle.Y  और  com.aspose.psd.Rectangle.Height  का योग है। |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


इस com.aspose.psd.Rectangle संरचना की ऊँचाई प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस  com.aspose.psd.Rectangle  संरचना की ऊँचाई। |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


इस com.aspose.psd.Rectangle संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस com.aspose.psd.Rectangle संरचना के बाएँ किनारे का x-निर्देशांक। |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने के निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | एक Point जो इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने को दर्शाता है। |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


इस com.aspose.psd.Rectangle संरचना के com.aspose.psd.Rectangle.X और com.aspose.psd.Rectangle.Width गुण मानों का योग होने वाला x-निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस com.aspose.psd.Rectangle का x-निर्देशांक जो com.aspose.psd.Rectangle.X और com.aspose.psd.Rectangle.Width का योग है। |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


इस com.aspose.psd.Rectangle का आकार प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | एक com.aspose.psd.Size जो इस com.aspose.psd.Rectangle संरचना की चौड़ाई और ऊँचाई को दर्शाता है। |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


इस com.aspose.psd.Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस com.aspose.psd.Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक। |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


इस com.aspose.psd.Rectangle संरचना की चौड़ाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस com.aspose.psd.Rectangle संरचना की चौड़ाई। |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का x-निर्देशांक। |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस com.aspose.psd.Rectangle संरचना के ऊपर-बाएँ कोने का y-निर्देशांक। |

### toString() {#toString--}
```
public String toString()
```


इस com.aspose.psd.Rectangle के गुणों को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस com.aspose.psd.Rectangle संरचना की स्थिति, चौड़ाई और ऊँचाई को शामिल करती है।
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


निर्दिष्ट com.aspose.psd.RectangleF मानों को काटकर एक com.aspose.psd.Rectangle में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | परिवर्तित करने के लिए  com.aspose.psd.RectangleF  । |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


दो com.aspose.psd.Rectangle संरचनाओं के संघ को सम्मिलित करने वाली एक com.aspose.psd.Rectangle संरचना प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | संघ करने के लिए पहला आयत। |
| b | [Rectangle](../../com.aspose.psd/rectangle) | संघ करने के लिए दूसरा आयत। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

