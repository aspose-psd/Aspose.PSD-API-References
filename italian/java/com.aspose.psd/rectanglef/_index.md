---
title: "RectangleF"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Memorizza un insieme di quattro numeri a virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo."
type: docs
weight: 89
url: /it/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Memorizza un insieme di quattro numeri a virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Inizializza una nuova istanza della struttura  com.aspose.psd.RectangleF  con la posizione e le dimensioni specificate. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Inizializza una nuova istanza della struttura  com.aspose.psd.RectangleF  con la posizione e le dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Determina se il punto specificato è contenuto all'interno di questa struttura  com.aspose.psd.RectangleF . |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Determina se la regione rettangolare rappresentata da  rect  è interamente contenuta all'interno di questa struttura  com.aspose.psd.RectangleF . |
| [contains(float x, float y)](#contains-float-float-) | Determina se il punto specificato è contenuto all'interno di questa struttura  com.aspose.psd.RectangleF . |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Divide i valori del rettangolo corrente per trasformare i valori di scala verticale e orizzontale della matrice e restituisce una nuova istanza di [RectangleF](../../com.aspose.psd/rectanglef) con i valori risultanti. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se  obj  è un  com.aspose.psd.RectangleF  con la stessa posizione e dimensione di questo  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Crea una struttura  com.aspose.psd.RectangleF  con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Crea un nuovo  Rectangle  da due punti specificati. |
| [getBottom()](#getBottom--) | Ottiene o imposta la coordinata y che è la somma di  com.aspose.psd.RectangleF.Y  e  com.aspose.psd.RectangleF.Height  di questa struttura  com.aspose.psd.RectangleF . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura  com.aspose.psd.RectangleF  che ha i valori di  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  e  com.aspose.psd.RectangleF.Height  impostati a zero. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.RectangleF . |
| [getLeft()](#getLeft--) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.RectangleF . |
| [getLocation()](#getLocation--) | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura  com.aspose.psd.RectangleF . |
| [getRight()](#getRight--) | Ottiene o imposta la coordinata x che è la somma di  com.aspose.psd.RectangleF.X  e  com.aspose.psd.RectangleF.Width  di questa struttura  com.aspose.psd.RectangleF . |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione di questa  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.RectangleF . |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza di questa struttura  com.aspose.psd.RectangleF . |
| [getX()](#getX--) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF . |
| [getY()](#getY--) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF . |
| [hashCode()](#hashCode--) | Ottiene il codice hash per questa struttura  com.aspose.psd.RectangleF . |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Crea e restituisce una copia gonfiata della struttura  com.aspose.psd.RectangleF  specificata. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Gonfia questa  com.aspose.psd.RectangleF  dell'importo specificato. |
| [inflate(float x, float y)](#inflate-float-float-) | Gonfia questa struttura  com.aspose.psd.RectangleF  dell'importo specificato. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Sostituisce questa struttura  com.aspose.psd.RectangleF  con l'intersezione di sé stessa e della struttura  com.aspose.psd.RectangleF  specificata. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Restituisce una struttura  com.aspose.psd.RectangleF  che rappresenta l'intersezione di due rettangoli. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Determina se questo rettangolo interseca con  rect . |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se la proprietà  com.aspose.psd.RectangleF.Width  o  com.aspose.psd.RectangleF.Height  di questo  com.aspose.psd.RectangleF  ha un valore zero. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Moltiplica i valori attuali del rettangolo per trasformare i valori di scala verticale e orizzontale della matrice e restituisce una nuova istanza di [RectangleF](../../com.aspose.psd/rectanglef) con i valori risultanti. |
| [normalize()](#normalize--) | Normalizza il rettangolo rendendo la sua larghezza e altezza positive, sinistra minore di destra e superiore minore di inferiore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(float x, float y)](#offset-float-float-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Implementa l'operatore /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Verifica se due strutture  com.aspose.psd.RectangleF  hanno la stessa posizione e dimensione. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Verifica se due strutture  com.aspose.psd.RectangleF  differiscono per posizione o dimensione. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Implementa l'operatore \*. |
| [setBottom(float value)](#setBottom-float-) | Ottiene o imposta la coordinata y che è la somma di  com.aspose.psd.RectangleF.Y  e  com.aspose.psd.RectangleF.Height  di questa struttura  com.aspose.psd.RectangleF . |
| [setHeight(float value)](#setHeight-float-) | Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.RectangleF . |
| [setLeft(float value)](#setLeft-float-) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.RectangleF . |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura  com.aspose.psd.RectangleF . |
| [setRight(float value)](#setRight-float-) | Ottiene o imposta la coordinata x che è la somma di  com.aspose.psd.RectangleF.X  e  com.aspose.psd.RectangleF.Width  di questa struttura  com.aspose.psd.RectangleF . |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Ottiene o imposta la dimensione di questa  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.RectangleF . |
| [setWidth(float value)](#setWidth-float-) | Ottiene o imposta la larghezza di questa struttura  com.aspose.psd.RectangleF . |
| [setX(float value)](#setX-float-) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF . |
| [setY(float value)](#setY-float-) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF . |
| [toRectangle_internalized()](#toRectangle-internalized--) | Converte un [RectangleF](../../com.aspose.psd/rectanglef) in una struttura [Rectangle](../../com.aspose.psd/rectangle) con valori di rettangolo troncati. |
| [toString()](#toString--) | Converte gli attributi di questo  com.aspose.psd.RectangleF  in una stringa leggibile dall'uomo. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Converte la struttura  com.aspose.psd.Rectangle  specificata in una struttura  com.aspose.psd.RectangleF . |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Inizializza una nuova istanza della struttura  com.aspose.psd.RectangleF  con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| larghezza | float | La larghezza del rettangolo. |
| altezza | float | L'altezza del rettangolo. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Inizializza una nuova istanza della struttura  com.aspose.psd.RectangleF  con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  che rappresenta l'angolo superiore sinistro della regione rettangolare. |
| size | [SizeF](../../com.aspose.psd/sizef) | Un  com.aspose.psd.SizeF  che rappresenta la larghezza e l'altezza della regione rettangolare. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Determina se il punto specificato è contenuto all'interno di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Il  com.aspose.psd.PointF  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto rappresentato dal parametro  point  è contenuto all'interno di questa struttura  com.aspose.psd.RectangleF ; altrimenti false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Determina se la regione rettangolare rappresentata da  rect  è interamente contenuta all'interno di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Il  com.aspose.psd.RectangleF  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se la regione rettangolare rappresentata da  rect  è interamente contenuta nella regione rettangolare rappresentata da questa  com.aspose.psd.RectangleF ; altrimenti false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Determina se il punto specificato è contenuto all'interno di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto definito da  x  e  y  è contenuto all'interno di questa struttura  com.aspose.psd.RectangleF ; altrimenti false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Divide i valori del rettangolo corrente per trasformare i valori di scala verticale e orizzontale della matrice e restituisce una nuova istanza di [RectangleF](../../com.aspose.psd/rectanglef) con i valori risultanti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transformMatrix | double[] | La matrice di trasformazione del livello. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se  obj  è un  com.aspose.psd.RectangleF  con la stessa posizione e dimensione di questo  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  System.Object  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se  obj  è un  com.aspose.psd.RectangleF  e le sue proprietà X, Y, Width e Height sono uguali alle corrispondenti proprietà di questo  com.aspose.psd.RectangleF ; altrimenti, false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Crea una struttura  com.aspose.psd.RectangleF  con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | float | La coordinata x dell'angolo superiore sinistro della regione rettangolare. |
| top | float | La coordinata y dell'angolo superiore sinistro della regione rettangolare. |
| right | float | La coordinata x dell'angolo inferiore destro della regione rettangolare. |
| bottom | float | La coordinata y dell'angolo inferiore destro della regione rettangolare. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crea un nuovo  Rectangle  da due punti specificati. I due vertici del Rectangle creato saranno uguali ai punti  point1  e  point2 . Tipicamente questi saranno i vertici opposti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Il primo  Point  per il nuovo rettangolo. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Il secondo  Point  per il nuovo rettangolo. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Ottiene o imposta la coordinata y che è la somma di  com.aspose.psd.RectangleF.Y  e  com.aspose.psd.RectangleF.Height  di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordinata y che è la somma di  com.aspose.psd.RectangleF.Y  e  com.aspose.psd.RectangleF.Height  di questa struttura  com.aspose.psd.RectangleF .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Ottiene una nuova istanza della struttura  com.aspose.psd.RectangleF  che ha i valori di  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  e  com.aspose.psd.RectangleF.Height  impostati a zero.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - L'altezza di questa struttura  com.aspose.psd.RectangleF .
### getLeft() {#getLeft--}
```
public float getLeft()
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordinata x del bordo sinistro di questa struttura  com.aspose.psd.RectangleF .
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Ottiene o imposta la coordinata x che è la somma di  com.aspose.psd.RectangleF.X  e  com.aspose.psd.RectangleF.Width  di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordinata x che è la somma di  com.aspose.psd.RectangleF.X  e  com.aspose.psd.RectangleF.Width  di questa struttura  com.aspose.psd.RectangleF .
### getSize() {#getSize--}
```
public SizeF getSize()
```


Ottiene o imposta la dimensione di questa  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordinata y del bordo superiore di questa struttura  com.aspose.psd.RectangleF .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Ottiene o imposta la larghezza di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - La larghezza di questa struttura  com.aspose.psd.RectangleF .
### getX() {#getX--}
```
public float getX()
```


Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF .
### getY() {#getY--}
```
public float getY()
```


Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene il codice hash per questa struttura  com.aspose.psd.RectangleF .

**Returns:**
int - Il codice hash per questo  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crea e restituisce una copia ingrandita della struttura  com.aspose.psd.RectangleF  specificata. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Il  com.aspose.psd.RectangleF  da copiare. Questo rettangolo non viene modificato. |
| x | float | L'importo per ingrandire orizzontalmente la copia del rettangolo. |
| y | float | L'importo per ingrandire verticalmente la copia del rettangolo. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Gonfia questa  com.aspose.psd.RectangleF  dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | L'importo per ingrandire questo rettangolo. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Gonfia questa struttura  com.aspose.psd.RectangleF  dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | L'importo per ingrandire orizzontalmente questa struttura  com.aspose.psd.RectangleF . |
| y | float | L'importo per ingrandire verticalmente questa struttura  com.aspose.psd.RectangleF . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Sostituisce questa struttura  com.aspose.psd.RectangleF  con l'intersezione di sé stessa e della struttura  com.aspose.psd.RectangleF  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo da intersecare. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Restituisce una struttura  com.aspose.psd.RectangleF  che rappresenta l'intersezione di due rettangoli. Se non c'è alcuna intersezione, viene restituito un  com.aspose.psd.RectangleF  vuoto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Un primo rettangolo da intersecare. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Un secondo rettangolo da intersecare. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Determina se questo rettangolo interseca con  rect .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo da testare. |

**Returns:**
boolean - Questo metodo restituisce true se esiste qualche intersezione.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se la proprietà  com.aspose.psd.RectangleF.Width  o  com.aspose.psd.RectangleF.Height  di questo  com.aspose.psd.RectangleF  ha un valore zero.

**Returns:**
boolean - Questa proprietà restituisce true se la proprietà  com.aspose.psd.RectangleF.Width  o  com.aspose.psd.RectangleF.Height  di questo  com.aspose.psd.RectangleF  ha un valore zero; altrimenti, false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Moltiplica i valori attuali del rettangolo per trasformare i valori di scala verticale e orizzontale della matrice e restituisce una nuova istanza di [RectangleF](../../com.aspose.psd/rectanglef) con i valori risultanti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transformMatrix | double[] | La matrice di trasformazione del livello. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


Normalizza il rettangolo rendendo la sua larghezza e altezza positive, sinistra minore di destra e superiore minore di inferiore.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | La quantità di spostamento della posizione. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La quantità di spostamento della posizione orizzontalmente. |
| y | float | La quantità di spostamento della posizione verticalmente. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementa l'operatore /.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo. |
| divisore | float | Il divisore. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Verifica se due strutture  com.aspose.psd.RectangleF  hanno la stessa posizione e dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura  com.aspose.psd.RectangleF  che si trova a sinistra dell'operatore di uguaglianza. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura  com.aspose.psd.RectangleF  che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se le due strutture  com.aspose.psd.RectangleF  specificate hanno le proprietà  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  e  com.aspose.psd.RectangleF.Height  uguali.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Verifica se due strutture  com.aspose.psd.RectangleF  differiscono per posizione o dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura  com.aspose.psd.RectangleF  che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura  com.aspose.psd.RectangleF  che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se una qualsiasi delle proprietà  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  o  com.aspose.psd.RectangleF.Height  delle due strutture  com.aspose.psd.RectangleF  è diversa; altrimenti false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementa l'operatore \*.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo. |
| moltiplicatore | float | Il moltiplicatore. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Ottiene o imposta la coordinata y che è la somma di  com.aspose.psd.RectangleF.Y  e  com.aspose.psd.RectangleF.Height  di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Ottiene o imposta le coordinate dell'angolo superiore sinistro di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Ottiene o imposta la coordinata x che è la somma di  com.aspose.psd.RectangleF.X  e  com.aspose.psd.RectangleF.Width  di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Ottiene o imposta la dimensione di questa  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Ottiene o imposta la larghezza di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Converte un [RectangleF](../../com.aspose.psd/rectanglef) in una struttura [Rectangle](../../com.aspose.psd/rectangle) con valori di rettangolo troncati.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Converte gli attributi di questo  com.aspose.psd.RectangleF  in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Una stringa che contiene la posizione, la larghezza e l'altezza di questa struttura  com.aspose.psd.RectangleF .
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Converte la struttura  com.aspose.psd.Rectangle  specificata in una struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura  com.aspose.psd.Rectangle  da convertire. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Il primo rettangolo da unire. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Il secondo rettangolo da unire. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

