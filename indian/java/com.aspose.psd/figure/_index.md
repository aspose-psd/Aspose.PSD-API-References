---
title: "आकृति"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आकृति।"
type: docs
weight: 42
url: /hi/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

फ़िगर। आकारों के लिए कंटेनर।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Figure()](#Figure--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | फ़िगर में एक आकार जोड़ता है। |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | फ़िगर में आकारों की एक रेंज जोड़ता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है या सेट करता है। |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | पूरे फ़िगर के खंड प्राप्त करता है। |
| [getShapes()](#getShapes--) | फ़िगर के आकार प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | एक मान प्राप्त करता है जो दर्शाता है कि यह फ़िगर बंद है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | फ़िगर से एक आकार हटाता है। |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | फ़िगर से आकारों की एक रेंज हटाता है। |
| [reverse()](#reverse--) | फ़िगर के आकार क्रम और आकार बिंदु क्रम को उलटता है। |
| [setClosed(boolean value)](#setClosed-boolean-) | एक मान सेट करता है जो दर्शाता है कि यह फ़िगर बंद है या नहीं। |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


फ़िगर में एक आकार जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | जोड़ने के लिए आकार। |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


फ़िगर में आकारों की एक रेंज जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | जोड़ने के लिए आकार। |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


ऑब्जेक्ट की सीमाएँ प्राप्त करता है या सेट करता है।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | सीमाएँ गणना होने से पहले लागू करने के लिए मैट्रिक्स। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | सीमाएँ गणना होने से पहले लागू करने के लिए मैट्रिक्स। |
| pen | [Pen](../../com.aspose.psd/pen) | ऑब्जेक्ट के लिए उपयोग करने वाला पेन। यह ऑब्जेक्ट की सीमाओं के आकार को प्रभावित कर सकता है। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


पूरे फ़िगर के खंड प्राप्त करता है।

**Returns:**
com.aspose.psd.ShapeSegment[] - फ़िगर के खंड।
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


फ़िगर के आकार प्राप्त करता है।

**Returns:**
com.aspose.psd.Shape[] - फ़िगर के आकार।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह फ़िगर बंद है या नहीं। एक बंद फ़िगर केवल तब अंतर पैदा करेगा जब पहले और अंतिम फ़िगर के आकार निरंतर आकार हों। ऐसे मामले में पहले आकार के पहले बिंदु को अंतिम आकार के अंतिम बिंदु से एक सीधी रेखा द्वारा जोड़ा जाएगा।

**Returns:**
boolean -  True  यदि यह फ़िगर बंद है; अन्यथा,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


फ़िगर से एक आकार हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | हटाने के लिए आकार। |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


फ़िगर से आकारों की एक रेंज हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | हटाने के लिए आकारों की रेंज। |

### reverse() {#reverse--}
```
public void reverse()
```


फ़िगर के आकार क्रम और आकार बिंदु क्रम को उलटता है।

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि यह फ़िगर बंद है या नहीं। एक बंद फ़िगर केवल तब अंतर पैदा करेगा जब पहले और अंतिम फ़िगर के आकार निरंतर आकार हों। ऐसे मामले में पहले आकार के पहले बिंदु को अंतिम आकार के अंतिम बिंदु से एक सीधी रेखा द्वारा जोड़ा जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | सही यदि यह आकृति बंद है; अन्यथा, गलत। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


निर्दिष्ट परिवर्तन को आकार पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | लागू करने के लिए परिवर्तन। |

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

