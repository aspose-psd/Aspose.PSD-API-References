---
title: "TextureBrush"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Aspose.Imaging.Brushes.TextureBrush क्लास की प्रत्येक प्रॉपर्टी एक Aspose.Imaging.Brush ऑब्जेक्ट है जो किसी आकार के अंदरूनी भाग को भरने के लिए छवि का उपयोग करता है।"
type: docs
weight: 18
url: /hi/java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Aspose.Imaging.Brushes.TextureBrush क्लास की प्रत्येक प्रॉपर्टी एक Aspose.Imaging.Brush ऑब्जेक्ट है जो किसी आकार के अंदरूनी भाग को भरने के लिए छवि का उपयोग करता है। इस क्लास को विरासत में नहीं लिया जा सकता।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | निर्दिष्ट छवि का उपयोग करने वाले Aspose.Imaging.Brushes.TextureBrush क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | निर्दिष्ट छवि और रैप मोड का उपयोग करने वाले Aspose.Imaging.Brushes.TextureBrush क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | निर्दिष्ट छवि, रैप मोड और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | निर्दिष्ट छवि, रैप मोड और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | निर्दिष्ट छवि, बाउंडिंग आयत और छवि विशेषताओं का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | निर्दिष्ट छवि, बाउंडिंग आयत और छवि विशेषताओं का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | वर्तमान Brush की एक नई गहरी क्लोन बनाता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getImage()](#getImage--) | इस  com.aspose.psd.brushes.TextureBrush  ऑब्जेक्ट से जुड़ा  com.aspose.psd.Image  ऑब्जेक्ट प्राप्त करता है। |
| [getImageAttributes()](#getImageAttributes--) | इस  TextureBrush  से जुड़ी  ImageAttributes  प्राप्त करता है। |
| [getImageRectangle()](#getImageRectangle--) | इस  TextureBrush  से जुड़ा  Rectangle  प्राप्त करता है। |
| [getOpacity()](#getOpacity--) | ब्रश की अपारदर्शिता प्राप्त करता है। |
| [getTransform()](#getTransform--) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [getWrapMode()](#getWrapMode--) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
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
| [setOpacity(float value)](#setOpacity-float-) | ब्रश की अपारदर्शिता सेट करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [setWrapMode(int value)](#setWrapMode-int-) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


निर्दिष्ट छवि का उपयोग करने वाले Aspose.Imaging.Brushes.TextureBrush क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


निर्दिष्ट छवि और रैप मोड का उपयोग करने वाले Aspose.Imaging.Brushes.TextureBrush क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |
| wrapMode | int | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट कैसे टाइल किया जाता है, यह निर्दिष्ट करने वाली  Aspose.Imaging.WrapMode  एन्यूमरेशन है। |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


निर्दिष्ट छवि, रैप मोड और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |
| wrapMode | int | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट कैसे टाइल किया जाता है, यह निर्दिष्ट करने वाली  Aspose.Imaging.WrapMode  एन्यूमरेशन है। |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट के बाउंडिंग आयत को दर्शाने वाली  Aspose.Imaging.RectangleF  संरचना है। |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


निर्दिष्ट छवि, रैप मोड और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |
| wrapMode | int | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट कैसे टाइल किया जाता है, यह निर्दिष्ट करने वाली  Aspose.Imaging.WrapMode  एन्यूमरेशन है। |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट के बाउंडिंग आयत को दर्शाने वाली  Aspose.Imaging.Rectangle  संरचना है। |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट के बाउंडिंग आयत को दर्शाने वाली  Aspose.Imaging.RectangleF  संरचना है। |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


निर्दिष्ट छवि, बाउंडिंग आयत और छवि विशेषताओं का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट के बाउंडिंग आयत को दर्शाने वाली  Aspose.Imaging.RectangleF  संरचना है। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट द्वारा उपयोग की गई छवि के बारे में अतिरिक्त जानकारी रखने वाला  com.aspose.psd.ImageAttributes  ऑब्जेक्ट है। |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट के बाउंडिंग आयत को दर्शाने वाली  Aspose.Imaging.Rectangle  संरचना है। |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


निर्दिष्ट छवि, बाउंडिंग आयत और छवि विशेषताओं का उपयोग करने वाली  Aspose.Imaging.Brushes.TextureBrush  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट जिन अंतरों को भरता है, वह  Aspose.Imaging.Image  ऑब्जेक्ट है। |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट के बाउंडिंग आयत को दर्शाने वाली  Aspose.Imaging.Rectangle  संरचना है। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | यह  Aspose.Imaging.Brushes.TextureBrush  ऑब्जेक्ट द्वारा उपयोग की गई छवि के बारे में अतिरिक्त जानकारी रखने वाला  com.aspose.psd.ImageAttributes  ऑब्जेक्ट है। |

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
### getImage() {#getImage--}
```
public Image getImage()
```


इस  com.aspose.psd.brushes.TextureBrush  ऑब्जेक्ट से जुड़ा  com.aspose.psd.Image  ऑब्जेक्ट प्राप्त करता है।

मान: वह  com.aspose.psd.Image  ऑब्जेक्ट जो इस  com.aspose.psd.brushes.TextureBrush  ऑब्जेक्ट द्वारा आकारों को भरने के लिए उपयोग की गई छवि को दर्शाता है।

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


इस  TextureBrush  से जुड़ी  ImageAttributes  प्राप्त करता है।

मान: यह  ImageAttributes  ।

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


इस  TextureBrush  से जुड़ा  Rectangle  प्राप्त करता है।

मान: यह  Rectangle  ।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


ब्रश की अपारदर्शिता प्राप्त करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Returns:**
float - ब्रश की अपारदर्शिता मान।
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

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


ब्रश की अपारदर्शिता सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | ब्रश अपारदर्शिता मान। |

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

