---
title: "Figura"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La figura."
type: docs
weight: 42
url: /it/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

La figura. Un contenitore per forme.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Figure()](#Figure--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Aggiunge una forma alla figura. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Aggiunge un intervallo di forme alla figura. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti dell'oggetto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Ottiene i limiti dell'oggetto. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Ottiene tutti i segmenti della figura. |
| [getShapes()](#getShapes--) | Ottiene le forme della figura. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Ottiene un valore che indica se questa figura è chiusa. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Rimuove una forma dalla figura. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Rimuove un intervallo di forme dalla figura. |
| [reverse()](#reverse--) | Inverte l'ordine delle forme di questa figura e l'ordine dei punti delle forme. |
| [setClosed(boolean value)](#setClosed-boolean-) | Imposta un valore che indica se questa figura è chiusa. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applica la trasformazione specificata alla forma. |
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


Aggiunge una forma alla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | La forma da aggiungere. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Aggiunge un intervallo di forme alla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Le forme da aggiungere. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene o imposta i limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](../../com.aspose.psd/pen) | La penna da usare per l'oggetto. Questo può influenzare le dimensioni dei limiti dell'oggetto. |

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


Ottiene tutti i segmenti della figura.

**Returns:**
com.aspose.psd.ShapeSegment[] - I segmenti della figura.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Ottiene le forme della figura.

**Returns:**
com.aspose.psd.Shape[] - Le forme della figura.
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


Ottiene un valore che indica se questa figura è chiusa. Una figura chiusa farà differenza solo nel caso in cui le forme prima e ultima della figura siano forme continue. In tal caso, il primo punto della prima forma sarà collegato da una linea retta all'ultimo punto dell'ultima forma.

**Returns:**
boolean -  True  se questa figura è chiusa; altrimenti,  false .
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


Rimuove una forma dalla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | La forma da rimuovere. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Rimuove un intervallo di forme dalla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | L'intervallo di forme da rimuovere. |

### reverse() {#reverse--}
```
public void reverse()
```


Inverte l'ordine delle forme di questa figura e l'ordine dei punti delle forme.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Imposta un valore che indica se questa figura è chiusa. Una figura chiusa farà differenza solo nel caso in cui le forme prima e ultima della figura siano forme continue. In tal caso, il primo punto della prima forma sarà collegato da una linea retta all'ultimo punto dell'ultima forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | True se questa figura è chiusa; altrimenti, false. |

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


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | La trasformazione da applicare. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

