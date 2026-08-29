---
title: "ImageExtensions"
second_title: "Java için Aspose.PSD API Referansı"
description: "java.awt.Image ve . tabanlı dönüşümler için uzantı yöntemlerini içerir."
type: docs
weight: 19
url: /tr/java/com.aspose.psd.extensions/imageextensions/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

java.awt.Image ve [Image](../../com.aspose.psd/image) tabanlı dönüşümler için uzantı yöntemlerini içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromJava_internalized(BufferedImage image, Rectangle rect)](#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiImage(Image image)](#toGdiImage-com.aspose.psd.Image-) | [Image](../../com.aspose.psd/image) öğesini java.awt.Image öğesine dönüştürür. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromJava_internalized(BufferedImage image, Rectangle rect) {#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-}
```
public static RasterImage fromJava_internalized(BufferedImage image, Rectangle rect)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | java.awt.image.BufferedImage |  |
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


[Image](../../com.aspose.psd/image) öğesini java.awt.Image öğesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | image | [Image](../../com.aspose.psd/image) | Dönüştürülecek [Image](../../com.aspose.psd/image). |

--------------------

Uyarı, GDI görüntüsü,  image  sahip olduğundan daha düşük sınırlara sahip olabilir. Görüntünün tüm bölümlerini elde etmek için daha güvenli uzantı yöntemi ToGdiImageFull'ı kullanın. |

**Returns:**
[Image](../../java.awt/image) - The converted java.awt.Image.
### toGdiImage_internalized(Image image) {#toGdiImage-internalized-com.aspose.psd.Image-}
```
public static System.Drawing.Image toGdiImage_internalized(Image image)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

