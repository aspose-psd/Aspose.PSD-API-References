---
title: "TextShape"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una forma di testo."
type: docs
weight: 18
url: /it/java/com.aspose.psd.shapes/textshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Rappresenta una forma di testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextShape()](#TextShape--) | Inizializza una nuova istanza della classe  TextShape . |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-) | Inizializza una nuova istanza della classe  TextShape . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Ottiene i limiti dell'oggetto. |
| [getCenter()](#getCenter--) | Restituisce il centro della forma. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Ottiene o imposta il carattere usato per disegnare il testo. |
| [getLeftBottom()](#getLeftBottom--) | Ottiene il punto in basso a sinistra del rettangolo. |
| [getLeftTop()](#getLeftTop--) | Ottiene il punto in alto a sinistra del rettangolo. |
| [getRectangleHeight()](#getRectangleHeight--) | Ottiene l'altezza del rettangolo. |
| [getRectangleWidth()](#getRectangleWidth--) | Ottiene la larghezza del rettangolo. |
| [getRightBottom()](#getRightBottom--) | Ottiene il punto in basso a destra del rettangolo. |
| [getRightTop()](#getRightTop--) | Ottiene il punto in alto a destra del rettangolo. |
| [getSegments()](#getSegments--) | Restituisce i segmenti della forma. |
| [getText()](#getText--) | Ottiene o imposta il testo disegnato. |
| [getTextFormat()](#getTextFormat--) | Ottiene o imposta il formato del testo. |
| [hasSegments()](#hasSegments--) | Restituisce un valore che indica se la forma ha segmenti. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFont(Font value)](#setFont-com.aspose.psd.Font-) | Ottiene o imposta il carattere usato per disegnare il testo. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo disegnato. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.psd.StringFormat-) | Ottiene o imposta il formato del testo. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applica la trasformazione specificata alla forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextShape() {#TextShape--}
```
public TextShape()
```


Inizializza una nuova istanza della classe  TextShape .

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Inizializza una nuova istanza della classe  TextShape .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Il testo da disegnare. |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo del testo. |
| font | [Font](../../com.aspose.psd/font) | Il carattere da utilizzare. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Il formato stringa. |

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


Ottiene i limiti dell'oggetto.

Valore: i limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
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
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Restituisce il centro della forma.

Valore: il centro della forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFont() {#getFont--}
```
public Font getFont()
```


Ottiene o imposta il carattere usato per disegnare il testo.

Valore: Il carattere usato per disegnare il testo.

**Returns:**
[Font](../../com.aspose.psd/font)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Ottiene il punto in basso a sinistra del rettangolo.

Valore: il punto in basso a sinistra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Ottiene il punto in alto a sinistra del rettangolo.

Valore: il punto in alto a sinistra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Ottiene l'altezza del rettangolo.

Valore: l'altezza del rettangolo.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Ottiene la larghezza del rettangolo.

Valore: La larghezza del rettangolo.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Ottiene il punto in basso a destra del rettangolo.

Valore: Il punto in basso a destra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Ottiene il punto in alto a destra del rettangolo.

Valore: Il punto in alto a destra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Restituisce i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getText() {#getText--}
```
public String getText()
```


Ottiene o imposta il testo disegnato.

Valore: Il testo disegnato.

**Returns:**
java.lang.String
### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Ottiene o imposta il formato del testo.

Valore: Il formato del testo.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Restituisce un valore che indica se la forma ha segmenti.

Valore:  True  se la forma ha segmenti; altrimenti,  false .

**Returns:**
boolean
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




### setFont(Font value) {#setFont-com.aspose.psd.Font-}
```
public void setFont(Font value)
```


Ottiene o imposta il carattere usato per disegnare il testo.

Valore: Il carattere usato per disegnare il testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Font](../../com.aspose.psd/font) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ottiene o imposta il testo disegnato.

Valore: Il testo disegnato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.psd.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Ottiene o imposta il formato del testo.

Valore: Il formato del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.psd/stringformat) |  |

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

