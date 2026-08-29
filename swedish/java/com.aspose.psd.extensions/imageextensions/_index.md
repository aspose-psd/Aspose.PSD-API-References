---
title: "ImageExtensions"
second_title: "Aspose.PSD för Java API-referens"
description: "Innehåller utökningsmetoder för konverteringar baserade på java.awt.Image och."
type: docs
weight: 19
url: /sv/java/com.aspose.psd.extensions/imageextensions/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Innehåller förlängningsmetoder för konverteringar baserade på java.awt.Image och [Image](../../com.aspose.psd/image).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromJava_internalized(BufferedImage image, Rectangle rect)](#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiImage(Image image)](#toGdiImage-com.aspose.psd.Image-) | Konverterar [Image](../../com.aspose.psd/image) till java.awt.Image. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromJava_internalized(BufferedImage image, Rectangle rect) {#fromJava-internalized-java.awt.image.BufferedImage-com.aspose.psd.Rectangle-}
```
public static RasterImage fromJava_internalized(BufferedImage image, Rectangle rect)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | java.awt.image.BufferedImage |  |
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


Konverterar [Image](../../com.aspose.psd/image) till java.awt.Image.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | image | [Image](../../com.aspose.psd/image) | Den [Image](../../com.aspose.psd/image) att konvertera. |

--------------------

Varning, GDI-bilden kan få lägre gränser än bilden har. För att få alla delar av bilden använd den säkrare förlängningsmetoden ToGdiImageFull. |

**Returns:**
[Image](../../java.awt/image) - The converted java.awt.Image.
### toGdiImage_internalized(Image image) {#toGdiImage-internalized-com.aspose.psd.Image-}
```
public static System.Drawing.Image toGdiImage_internalized(Image image)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

