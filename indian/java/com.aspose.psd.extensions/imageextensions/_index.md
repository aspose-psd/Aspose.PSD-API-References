---
title: "ImageExtensions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "java.awt.Image और . पर आधारित रूपांतरणों के लिए एक्सटेंशन मेथड्स शामिल हैं।"
type: docs
weight: 19
url: /hi/java/com.aspose.psd.extensions/imageextensions/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

java.awt.Image और [Image](../../com.aspose.psd/image) पर आधारित रूपांतरणों के लिए एक्सटेंशन मेथड्स शामिल हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromJava_internalized(BufferedImage image, Rectangle rect)](#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiImage(Image image)](#toGdiImage-com.aspose.psd.Image-) | [Image](../../com.aspose.psd/image) को java.awt.Image में परिवर्तित करता है। |
| [toGdiImage_internalized(Image image)](#toGdiImage-internalized-com.aspose.psd.Image-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### fromJava_internalized(BufferedImage image, Rectangle rect) {#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-}
```
public static RasterImage fromJava_internalized(BufferedImage image, Rectangle rect)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | java.awt.image.BufferedImage |  |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### toGdiImage(Image image) {#toGdiImage-com.aspose.psd.Image-}
```
public static Image toGdiImage(Image image)
```


[Image](../../com.aspose.psd/image) को java.awt.Image में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | image | [Image](../../com.aspose.psd/image) | परिवर्तित करने के लिए [Image](../../com.aspose.psd/image)। |

--------------------

चेतावनी, GDI छवि के सीमाएँ मूल छवि से कम हो सकती हैं। छवि के सभी भाग प्राप्त करने के लिए अधिक सुरक्षित एक्सटेंशन मेथड ToGdiImageFull का उपयोग करें। |

**Returns:**
[Image](../../java.awt/image) - The converted java.awt.Image.
### toGdiImage_internalized(Image image) {#toGdiImage-internalized-com.aspose.psd.Image-}
```
public static System.Drawing.Image toGdiImage_internalized(Image image)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) |  |

**Returns:**
[Image](../../com.aspose.ms.system.drawing/image)
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

