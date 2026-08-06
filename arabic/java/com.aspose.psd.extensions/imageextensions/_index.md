---
title: "ImageExtensions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحتوي على طرق امتداد للتحويلات المستندة إلى java.awt.Image و ."
type: docs
weight: 19
url: /ar/java/com.aspose.psd.extensions/imageextensions/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

يحتوي على طرق امتداد للتحويلات المستندة إلى java.awt.Image و [Image](../../com.aspose.psd/image).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromJava_internalized(BufferedImage image, Rectangle rect)](#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiImage(Image image)](#toGdiImage-com.aspose.psd.Image-) | يحوّل [Image](../../com.aspose.psd/image) إلى java.awt.Image. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromJava_internalized(BufferedImage image, Rectangle rect) {#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-}
```
public static RasterImage fromJava_internalized(BufferedImage image, Rectangle rect)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | java.awt.image.BufferedImage |  |
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


يحوّل [Image](../../com.aspose.psd/image) إلى java.awt.Image.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | image | [Image](../../com.aspose.psd/image) | الـ [Image](../../com.aspose.psd/image) للتحويل. |

--------------------

تحذير، قد تحصل صورة GDI على حدود أقل مما تمتلكه  image . للحصول على جميع أجزاء الصورة استخدم طريقة الامتداد الأكثر أمانًا ToGdiImageFull. |

**Returns:**
[Image](../../java.awt/image) - The converted java.awt.Image.
### toGdiImage_internalized(Image image) {#toGdiImage-internalized-com.aspose.psd.Image-}
```
public static System.Drawing.Image toGdiImage_internalized(Image image)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

