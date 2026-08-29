---
title: "LinearGradientBrushBase"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक ब्रश को दर्शाता है जिसमें ग्रेडिएंट क्षमताएँ और उपयुक्त गुण होते हैं।"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.brushes/lineargradientbrushbase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

एक Brush को ग्रेडिएंट क्षमताओं और उपयुक्त गुणों के साथ प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | वर्तमान Brush की एक नई गहरी क्लोन बनाता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | ग्रेडिएंट कोण प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getGammaCorrection()](#getGammaCorrection--) | यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं। |
| [getOpacity()](#getOpacity--) | ब्रश की अपारदर्शिता प्राप्त करता है। |
| [getRectangle()](#getRectangle--) | एक आयताकार क्षेत्र प्राप्त करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है। |
| [getTransform()](#getTransform--) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [getWrapMode()](#getWrapMode--) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं। |
| [isTransformChanged()](#isTransformChanged--) | यह दर्शाने वाला मान प्राप्त करता है कि रूपांतरण किसी न किसी तरह बदले गए थे या नहीं। |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | निर्दिष्ट Aspose.Imaging.Matrix को पहले जोड़कर, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | निर्दिष्ट क्रम में, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | TransformBrush.Transform गुण को पहचान (identity) पर रीसेट करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। |
| [setAngle(float value)](#setAngle-float-) | ग्रेडिएंट कोण सेट करता है। |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं। |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं। |
| [setOpacity(float value)](#setOpacity-float-) | ब्रश की अपारदर्शिता सेट करता है। |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | एक आयताकार क्षेत्र सेट करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [setWrapMode(int value)](#setWrapMode-int-) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


वर्तमान Brush की एक नई गहरी क्लोन बनाता है।

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

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
public float getAngle()
```


ग्रेडिएंट कोण प्राप्त करता है।

**Returns:**
float - ग्रेडिएंट का कोण।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं।

**Returns:**
boolean - मान true है यदि इस  LinearGradientBrushBase  के लिए गामा सुधार सक्षम है; अन्यथा false।
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


ब्रश की अपारदर्शिता प्राप्त करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Returns:**
float - ब्रश की अपारदर्शिता मान।
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


एक आयताकार क्षेत्र प्राप्त करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है।

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है।

**Returns:**
int - एक  Aspose.Imaging.WrapMode  जो निर्दिष्ट करता है कि इस  TransformBrush  से बने भराव कैसे टाइल किए जाते हैं।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं।

**Returns:**
boolean -  true  यदि  LinearGradientBrushBase.Angle  इस  LinearGradientBrushBase  के साथ रूपांतरणों के दौरान बदलता है; अन्यथा,  false ।
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


एक मान प्राप्त करता है जो दर्शाता है कि रूपांतरण किसी न किसी तरह बदले गए थे या नहीं। उदाहरण के लिए रूपांतरण मैट्रिक्स सेट करना या रूपांतरण मैट्रिक्स को बदलने वाली किसी भी विधि को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पिछली संगतता के लिए पेश की गई है।

मान:  True  यदि रूपांतरण बदला गया; अन्यथा,  false ।

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


निर्दिष्ट Aspose.Imaging.Matrix को पहले जोड़कर, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ज्यामितीय रूपांतरण को गुणा करने के लिए  Aspose.Imaging.Matrix । |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


निर्दिष्ट क्रम में, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ज्यामितीय रूपांतरण को गुणा करने के लिए  Aspose.Imaging.Matrix । |
| order | int | एक  Aspose.Imaging.MatrixOrder  जो निर्दिष्ट करता है कि दो मैट्रिक्स को किस क्रम में गुणा किया जाए। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


TransformBrush.Transform गुण को पहचान (identity) पर रीसेट करता है।

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। यह विधि घुमाव को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |
| order | int | एक  Aspose.Imaging.MatrixOrder  जो निर्दिष्ट करता है कि घुमाव मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। यह विधि स्केलिंग मैट्रिक्स को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| order | int | एक  Aspose.Imaging.MatrixOrder  जो निर्धारित करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


ग्रेडिएंट कोण सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | ग्रेडिएंट कोण। |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | सही यदि  LinearGradientBrushBase.Angle  इस  LinearGradientBrushBase  के साथ रूपांतरण के दौरान बदलता है; अन्यथा, गलत। |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | यह मान सही है यदि इस  LinearGradientBrushBase  के लिए गामा सुधार सक्षम है; अन्यथा, गलत। |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


ब्रश की अपारदर्शिता सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | ब्रश अपारदर्शिता मान। |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


एक आयताकार क्षेत्र सेट करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | एक  com.aspose.psd.RectangleF  संरचना जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को निर्दिष्ट करती है। |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। यह विधि अनुवाद को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | x में अनुवाद का मान। |
| dy | float | y में अनुवाद का मान। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | x में अनुवाद का मान। |
| dy | float | y में अनुवाद का मान। |
| order | int | अनुवाद लागू करने का क्रम (पहले जोड़ना या बाद में जोड़ना)। |

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

