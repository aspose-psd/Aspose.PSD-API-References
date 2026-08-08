---
title: "Figur"
second_title: "Aspose.PSD för Java API-referens"
description: "Figuren."
type: docs
weight: 42
url: /sv/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Figuren. En behållare för former.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Figure()](#Figure--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Lägger till en form i figuren. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Lägger till ett intervall av former i figuren. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Hämtar eller anger objektets gränser. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Hämtar objektets gränser. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Hämtar hela figurens segment. |
| [getShapes()](#getShapes--) | Hämtar figurens former. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Hämtar ett värde som indikerar om denna figur är sluten. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Tar bort en form från figuren. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Tar bort ett intervall av former från figuren. |
| [reverse()](#reverse--) | Vänder på figurens formordning och formernas punktordning. |
| [setClosed(boolean value)](#setClosed-boolean-) | Anger ett värde som indikerar om denna figur är sluten. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Tillämpar den angivna transformationen på formen. |
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


Lägger till en form i figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Formen att lägga till. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Lägger till ett intervall av former i figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Formerna att lägga till. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar eller anger objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrisen att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrisen att tillämpa innan gränser beräknas. |
| pen | [Pen](../../com.aspose.psd/pen) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

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


Hämtar hela figurens segment.

**Returns:**
com.aspose.psd.ShapeSegment[] - Figurens segment.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Hämtar figurens former.

**Returns:**
com.aspose.psd.Shape[] - Figurens former.
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


Hämtar ett värde som indikerar om denna figur är sluten. En sluten figur gör bara någon skillnad i fall där den första och den sista figurens former är kontinuerliga former. I sådant fall kommer den första punkten i den första formen att kopplas ihop med en rak linje från den sista punkten i den sista formen.

**Returns:**
boolean -  True  if this figure is closed; otherwise,  false .
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


Tar bort en form från figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Formen att ta bort. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Tar bort ett intervall av former från figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Formintervallet att ta bort. |

### reverse() {#reverse--}
```
public void reverse()
```


Vänder på figurens formordning och formernas punktordning.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Ställer in ett värde som anger om denna figur är sluten. En sluten figur gör bara någon skillnad i fall där den första och den sista figurens former är kontinuerliga former. I sådant fall kommer den första punkten i den första formen att kopplas ihop med en rak linje från den sista punkten i den sista formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Sant om denna figur är sluten; annars falskt. |

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


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Transformationen att tillämpa. |

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

