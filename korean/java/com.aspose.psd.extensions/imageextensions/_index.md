---
title: "ImageExtensions"
second_title: "Java용 Aspose.PSD API 참조"
description: "java.awt.Image와  를 기반으로 하는 변환을 위한 확장 메서드를 포함합니다."
type: docs
weight: 19
url: /ko/java/com.aspose.psd.extensions/imageextensions/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

java.awt.Image와 [Image](../../com.aspose.psd/image)를 기반으로 하는 변환을 위한 확장 메서드를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromJava_internalized(BufferedImage image, Rectangle rect)](#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiImage(Image image)](#toGdiImage-com.aspose.psd.Image-) | [Image](../../com.aspose.psd/image) 를 java.awt.Image 로 변환합니다. |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromJava_internalized(BufferedImage image, Rectangle rect) {#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-}
```
public static RasterImage fromJava_internalized(BufferedImage image, Rectangle rect)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이미지 | java.awt.image.BufferedImage |  |
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


[Image](../../com.aspose.psd/image) 를 java.awt.Image 로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | image | [Image](../../com.aspose.psd/image) | 변환할 [Image](../../com.aspose.psd/image). |

--------------------

경고, GDI 이미지가 이미지보다 낮은 경계를 가질 수 있습니다. 이미지의 모든 부분을 가져오려면 더 안전한 확장 메서드 ToGdiImageFull을 사용하십시오. |

**Returns:**
[Image](../../java.awt/image) - The converted java.awt.Image.
### toGdiImage_internalized(Image image) {#toGdiImage-internalized-com.aspose.psd.Image-}
```
public static System.Drawing.Image toGdiImage_internalized(Image image)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

