---
title: "GraphicsPath"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "जुड़ी हुई लाइनों और कर्व्स की एक श्रृंखला का प्रतिनिधित्व करता है।"
type: docs
weight: 50
url: /hi/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

जुड़ी हुई रेखाओं और वक्रों की एक श्रृंखला का प्रतिनिधित्व करता है। इस क्लास को विरासत में नहीं लिया जा सकता।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | एक नया आकृति जोड़ता है। |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | नए आकृतियों को जोड़ता है। |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | निर्दिष्ट com.aspose.psd.GraphicsPath को इस पथ में जोड़ता है। |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | निर्दिष्ट com.aspose.psd.GraphicsPath को इस पथ में जोड़ता है। |
| [deepClone()](#deepClone--) | इस ग्राफ़िक्स पथ की गहरी क्लोन बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | इस पथ में प्रत्येक वक्र को जुड़ी हुई रेखा खंडों की श्रृंखला में परिवर्तित करता है। |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | निर्दिष्ट ट्रांसफ़ॉर्म लागू करता है और फिर इस com.aspose.psd.GraphicsPath में प्रत्येक वक्र को जुड़ी हुई रेखा खंडों की श्रृंखला में परिवर्तित करता है। |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | इस com.aspose.psd.GraphicsPath में प्रत्येक वक्र को जुड़ी हुई रेखा खंडों की श्रृंखला में परिवर्तित करता है। |
| [getBounds()](#getBounds--) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है या सेट करता है। |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | पथ आकृतियों को प्राप्त करता है। |
| [getFillMode()](#getFillMode--) | com.aspose.psd.FillMode एन्यूमरेशन प्राप्त करता है जो निर्धारित करता है कि इस com.aspose.psd.GraphicsPath में आकृतियों के अंदरूनी भाग कैसे भरे जाते हैं। |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है। |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है। |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है। |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है। |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है। |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है। |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है। |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है। |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है। |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है। |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है। |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है। |
| [isVisible(float x, float y)](#isVisible-float-float-) | निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है। |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर, निर्दिष्ट  com.aspose.psd.graphics  के दृश्यमान क्लिप क्षेत्र में स्थित है या नहीं, दर्शाता है। |
| [isVisible(int x, int y)](#isVisible-int-int-) | निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है। |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर, निर्दिष्ट  com.aspose.psd.graphics  का उपयोग करके, स्थित है या नहीं, दर्शाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | एक आकृति को हटाता है। |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | आकृतियों को हटाता है। |
| [reset()](#reset--) | ग्राफ़िक्स पाथ को खाली करता है और  com.aspose.psd.FillMode  को  F:com.aspose.psd.fillMode.alternate  पर सेट करता है। |
| [reverse()](#reverse--) | इस  com.aspose.psd.graphicsPath  के प्रत्येक आकार में आकृतियों, शैलियों और बिंदुओं का क्रम उलट देता है। |
| [setFillMode(int value)](#setFillMode-int-) | एक  com.aspose.psd.FillMode  एन्यूमरेशन सेट करता है जो निर्धारित करता है कि इस  com.aspose.psd.GraphicsPath  में आकारों के अंदरूनी भाग कैसे भरे जाते हैं। |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है। |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है। |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है। |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है। |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | पाथ में एक अतिरिक्त रूपरेखा जोड़ता है। |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) |   com.aspose.psd.graphicsPath  में एक अतिरिक्त रूपरेखा जोड़ता है। |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | इस  com.aspose.psd.GraphicsPath  को उन वक्रों से बदलता है जो उस क्षेत्र को घेरते हैं जो निर्दिष्ट पेन द्वारा इस पाथ को खींचे जाने पर भरा जाता है। |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है।

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | आरंभ करने के लिए आकृतियाँ। |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | आरंभ करने के लिए आकृतियाँ। |
| fillMode | int | भरण मोड। |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


GraphicsPath क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillMode | int | भरण मोड। |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


एक नया आकृति जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | जोड़ने के लिए आकृति। |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


नए आकृतियों को जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | जोड़ने के लिए आकृतियाँ। |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


निर्दिष्ट com.aspose.psd.GraphicsPath को इस पथ में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | जोड़ने के लिए  com.aspose.psd.GraphicsPath । |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


निर्दिष्ट com.aspose.psd.GraphicsPath को इस पथ में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | जोड़ने के लिए  com.aspose.psd.GraphicsPath । |
| connect | boolean | एक बूलियन मान जो निर्दिष्ट करता है कि जोड़े गए पाथ में पहली आकृति इस पाथ की अंतिम आकृति का हिस्सा है या नहीं। true मान यह दर्शाता है कि जोड़े गए पाथ में पहली आकृति इस पाथ की अंतिम आकृति का हिस्सा है। false मान यह दर्शाता है कि जोड़े गए पाथ में पहली आकृति इस पाथ की अंतिम आकृति से अलग है। |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


इस ग्राफ़िक्स पथ की गहरी क्लोन बनाता है।

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


इस पथ में प्रत्येक वक्र को जुड़ी हुई रेखा खंडों की श्रृंखला में परिवर्तित करता है।

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


निर्दिष्ट ट्रांसफ़ॉर्म लागू करता है और फिर इस com.aspose.psd.GraphicsPath में प्रत्येक वक्र को जुड़ी हुई रेखा खंडों की श्रृंखला में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | एक  com.aspose.psd.Matrix  जिसके द्वारा इस  com.aspose.psd.GraphicsPath  को फ्लैटनिंग से पहले ट्रांसफ़ॉर्म किया जाता है। |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


इस com.aspose.psd.GraphicsPath में प्रत्येक वक्र को जुड़ी हुई रेखा खंडों की श्रृंखला में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | एक  com.aspose.psd.Matrix  जिसके द्वारा इस  com.aspose.psd.GraphicsPath  को फ्लैटनिंग से पहले ट्रांसफ़ॉर्म किया जाता है। |
| flatness | float | वक्र और उसके फ्लैटन किए गए अनुमान के बीच अधिकतम अनुमत त्रुटि को निर्दिष्ट करता है। डिफ़ॉल्ट मान 0.25 है। फ्लैटनस मान को कम करने से अनुमान में रेखा खंडों की संख्या बढ़ जाएगी। |

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
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


पथ आकृतियों को प्राप्त करता है।

**Returns:**
com.aspose.psd.Figure[] - पाथ आकृतियाँ।
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


com.aspose.psd.FillMode एन्यूमरेशन प्राप्त करता है जो निर्धारित करता है कि इस com.aspose.psd.GraphicsPath में आकृतियों के अंदरूनी भाग कैसे भरे जाते हैं।

**Returns:**
int - भरण मोड। एक  com.aspose.psd.FillMode  एन्यूमरेशन जो निर्धारित करता है कि इस  com.aspose.psd.GraphicsPath  में आकारों के अंदरूनी भाग कैसे भरे जाते हैं।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | एक  com.aspose.psd.Point  जो परीक्षण के लिए स्थान निर्दिष्ट करता है। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर हो, जब निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | एक  com.aspose.psd.Point  जो परीक्षण के लिए स्थान निर्दिष्ट करता है। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर हो, जैसा कि निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  जो परीक्षण के लिए स्थान निर्दिष्ट करता है। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर हो, जब निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  जो परीक्षण के लिए स्थान निर्दिष्ट करता है। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर (के नीचे) हो, जैसा कि निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर हो, जब निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर (के नीचे) हो, जैसा कि निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.pen के साथ खींचा जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर हो, जब निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


निर्दिष्ट बिंदु इस com.aspose.psd.GraphicsPath की रूपरेखा के भीतर (नीचे) है या नहीं, जब इसे निर्दिष्ट com.aspose.psd.Pen के साथ खींचा जाता है और निर्दिष्ट com.aspose.psd.graphics का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](../../com.aspose.psd/pen) | परीक्षण के लिए यह  com.aspose.psd.Pen  है। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  की रूपरेखा के भीतर हो, जैसा कि निर्दिष्ट  com.aspose.psd.Pen  से खींचा गया हो; अन्यथा, false।
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | एक  com.aspose.psd.Point  जो परीक्षण के बिंदु को दर्शाता है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर हो; अन्यथा, false।
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | एक  com.aspose.psd.Point  जो परीक्षण के बिंदु को दर्शाता है। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर हो; अन्यथा, false।
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  जो परीक्षण के बिंदु को दर्शाता है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर हो; अन्यथा, false।
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  जो परीक्षण के बिंदु को दर्शाता है। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस के भीतर हो; अन्यथा, false।
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर हो; अन्यथा, false।
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर, निर्दिष्ट  com.aspose.psd.graphics  के दृश्यमान क्लिप क्षेत्र में स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर हो; अन्यथा, false।
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.graphicsPath  के भीतर स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर हो; अन्यथा, false।
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर, निर्दिष्ट  com.aspose.psd.graphics  का उपयोग करके, स्थित है या नहीं, दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |
| graphics | [Graphics](../../com.aspose.psd/graphics) | जिस  com.aspose.psd.Graphics  की दृश्यता का परीक्षण करना है। |

**Returns:**
boolean - यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस  com.aspose.psd.GraphicsPath  के भीतर हो; अन्यथा, false।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


एक आकृति को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | हटाने के लिए आकृति। |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


आकृतियों को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | हटाने के लिए आकृतियाँ। |

### reset() {#reset--}
```
public void reset()
```


ग्राफ़िक्स पाथ को खाली करता है और  com.aspose.psd.FillMode  को  F:com.aspose.psd.fillMode.alternate  पर सेट करता है।

### reverse() {#reverse--}
```
public void reverse()
```


इस  com.aspose.psd.graphicsPath  के प्रत्येक आकार में आकृतियों, शैलियों और बिंदुओं का क्रम उलट देता है।

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


एक  com.aspose.psd.FillMode  एन्यूमरेशन सेट करता है जो निर्धारित करता है कि इस  com.aspose.psd.GraphicsPath  में आकारों के अंदरूनी भाग कैसे भरे जाते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | भरण मोड। |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें srcRect द्वारा परिभाषित आयत को रूपांतरित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायां कोना पहले तीन बिंदुओं द्वारा निर्धारित होता है। |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  com.aspose.psd.RectangleF  जो उस आयत को दर्शाता है जिसे destPoints द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें srcRect द्वारा परिभाषित आयत को रूपांतरित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायां कोना पहले तीन बिंदुओं द्वारा निर्धारित होता है। |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  com.aspose.psd.RectangleF  जो उस आयत को दर्शाता है जिसे destPoints द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |
| matrix | [Matrix](../../com.aspose.psd/matrix) | एक  com.aspose.psd.Matrix  जो पथ पर लागू करने के लिए ज्यामितीय रूपांतरण निर्दिष्ट करता है। |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें srcRect द्वारा परिभाषित आयत को रूपांतरित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायां कोना पहले तीन बिंदुओं द्वारा निर्धारित होता है। |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  com.aspose.psd.RectangleF  जो उस आयत को दर्शाता है जिसे destPoints द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |
| matrix | [Matrix](../../com.aspose.psd/matrix) | एक  com.aspose.psd.Matrix  जो पथ पर लागू करने के लिए ज्यामितीय रूपांतरण निर्दिष्ट करता है। |
| warpMode | int | एक  com.aspose.psd.WarpMode  enumeration जो निर्दिष्ट करता है कि यह warp ऑपरेशन परिप्रेक्ष्य मोड या द्विरैखिक मोड का उपयोग करता है। |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस  com.aspose.psd.graphicsPath  पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें srcRect द्वारा परिभाषित आयत को रूपांतरित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायां कोना पहले तीन बिंदुओं द्वारा निर्धारित होता है। |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  com.aspose.psd.RectangleF  जो उस आयत को दर्शाता है जिसे destPoints द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |
| matrix | [Matrix](../../com.aspose.psd/matrix) | एक  com.aspose.psd.Matrix  जो पथ पर लागू करने के लिए ज्यामितीय रूपांतरण निर्दिष्ट करता है। |
| warpMode | int | एक  com.aspose.psd.WarpMode  enumeration जो निर्दिष्ट करता है कि यह warp ऑपरेशन परिप्रेक्ष्य मोड या द्विरैखिक मोड का उपयोग करता है। |
| flatness | float | 0 से 1 तक का मान जो निर्धारित करता है कि परिणामी पथ कितना सपाट है। अधिक जानकारी के लिए,  com.aspose.psd.GraphicsPath.flatten  विधियों को देखें। |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


पाथ में एक अतिरिक्त रूपरेखा जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | एक  com.aspose.psd.Pen  जो पथ की मूल रूपरेखा और इस विधि द्वारा निर्मित नई रूपरेखा के बीच की चौड़ाई निर्दिष्ट करता है। |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


  com.aspose.psd.graphicsPath  में एक अतिरिक्त रूपरेखा जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | एक  com.aspose.psd.Pen  जो पथ की मूल रूपरेखा और इस विधि द्वारा निर्मित नई रूपरेखा के बीच की चौड़ाई निर्दिष्ट करता है। |
| matrix | [Matrix](../../com.aspose.psd/matrix) | एक  com.aspose.psd.Matrix  जो पथ को चौड़ा करने से पहले लागू करने के लिए रूपांतरण निर्दिष्ट करता है। |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


इस  com.aspose.psd.GraphicsPath  को उन वक्रों से बदलता है जो उस क्षेत्र को घेरते हैं जो निर्दिष्ट पेन द्वारा इस पाथ को खींचे जाने पर भरा जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | एक  com.aspose.psd.Pen  जो पथ की मूल रूपरेखा और इस विधि द्वारा निर्मित नई रूपरेखा के बीच की चौड़ाई निर्दिष्ट करता है। |
| matrix | [Matrix](../../com.aspose.psd/matrix) | एक  com.aspose.psd.Matrix  जो पथ को चौड़ा करने से पहले लागू करने के लिए रूपांतरण निर्दिष्ट करता है। |
| flatness | float | एक मान जो वक्रों की सपाटता निर्दिष्ट करता है। |

