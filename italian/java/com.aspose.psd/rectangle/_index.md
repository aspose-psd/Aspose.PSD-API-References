---
title: "Rettangolo"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo."
type: docs
weight: 88
url: /it/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Inizializza una nuova istanza della  com.aspose.psd.Rectangle  struttura con la posizione e le dimensioni specificate. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Inizializza una nuova istanza della  com.aspose.psd.Rectangle  struttura con la posizione e le dimensioni specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Converte la struttura  com.aspose.psd.RectangleF  specificata in una struttura  com.aspose.psd.Rectangle  arrotondando i valori di  com.aspose.psd.RectangleF  al prossimo intero superiore. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Determina se il punto specificato è contenuto all'interno di questa  com.aspose.psd.Rectangle  struttura. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Determina se la regione rettangolare rappresentata da  rect  è interamente contenuta all'interno di questa  com.aspose.psd.Rectangle  struttura. |
| [contains(int x, int y)](#contains-int-int-) | Determina se il punto specificato è contenuto all'interno di questa  com.aspose.psd.Rectangle  struttura. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se  obj  è una struttura  com.aspose.psd.Rectangle  con la stessa posizione e dimensione di questa  com.aspose.psd.Rectangle  struttura. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Crea una struttura  com.aspose.psd.Rectangle  con le posizioni dei bordi specificate. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Crea un nuovo  Rectangle  da due punti specificati. |
| [getBottom()](#getBottom--) | Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.Y  e  com.aspose.psd.Rectangle.Height  di questa struttura  com.aspose.psd.Rectangle . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della struttura  com.aspose.psd.Rectangle  che ha i valori  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  e  com.aspose.psd.Rectangle.Height  impostati a zero. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.Rectangle . |
| [getLeft()](#getLeft--) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.Rectangle . |
| [getLocation()](#getLocation--) | Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle . |
| [getRight()](#getRight--) | Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.X  e  com.aspose.psd.Rectangle.Width  di questa struttura  com.aspose.psd.Rectangle . |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione di questa  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.Rectangle . |
| [getWidth()](#getWidth--) | Ottiene la larghezza di questa struttura  com.aspose.psd.Rectangle . |
| [getX()](#getX--) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle . |
| [getY()](#getY--) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle . |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa struttura  com.aspose.psd.Rectangle . |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Crea e restituisce una copia ingrandita della struttura  com.aspose.psd.Rectangle  specificata. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Ingrandisce questa  com.aspose.psd.Rectangle  dell'importo specificato. |
| [inflate(int width, int height)](#inflate-int-int-) | Ingrandisce questa  com.aspose.psd.Rectangle  dell'importo specificato. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Sostituisce questa  com.aspose.psd.Rectangle  con l'intersezione di sé stessa e della  com.aspose.psd.Rectangle  specificata. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Restituisce una terza struttura  com.aspose.psd.Rectangle  che rappresenta l'intersezione di due altre strutture  com.aspose.psd.Rectangle . |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Determina se questo rettangolo interseca con  rect . |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se tutte le proprietà numeriche di questa  com.aspose.psd.Rectangle  hanno valori zero. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Ottiene un valore che indica se questo  Rectangle  è almeno parzialmente visibile |
| [normalize()](#normalize--) | Normalizza il rettangolo rendendo la sua larghezza e altezza positive, sinistra minore di destra e superiore minore di inferiore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(int x, int y)](#offset-int-int-) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Verifica se due strutture  com.aspose.psd.Rectangle  hanno la stessa posizione e dimensione. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Verifica se due  com.aspose.psd.Rectangle  strutture differiscono per posizione o dimensione. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Converte il  com.aspose.psd.RectangleF  specificato in un  com.aspose.psd.Rectangle  arrotondando i valori del  com.aspose.psd.RectangleF  al numero intero più vicino. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.Y  e  com.aspose.psd.Rectangle.Height  di questa struttura  com.aspose.psd.Rectangle . |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.Rectangle . |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.Rectangle . |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle . |
| [setRight(int value)](#setRight-int-) | Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.X  e  com.aspose.psd.Rectangle.Width  di questa struttura  com.aspose.psd.Rectangle . |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Ottiene o imposta la dimensione di questa  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.Rectangle . |
| [setWidth(int value)](#setWidth-int-) | Imposta la larghezza di questa  com.aspose.psd.Rectangle  struttura. |
| [setX(int value)](#setX-int-) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle . |
| [setY(int value)](#setY-int-) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle . |
| [toString()](#toString--) | Converte gli attributi di questo  com.aspose.psd.Rectangle  in una stringa leggibile. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Converte il  com.aspose.psd.RectangleF  specificato in un  com.aspose.psd.Rectangle  troncando i valori del  com.aspose.psd.RectangleF . |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Ottiene una  com.aspose.psd.Rectangle  struttura che contiene l'unione di due  com.aspose.psd.Rectangle  strutture. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Inizializza una nuova istanza della  com.aspose.psd.Rectangle  struttura con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| larghezza | int | La larghezza del rettangolo. |
| altezza | int | L'altezza del rettangolo. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Inizializza una nuova istanza della  com.aspose.psd.Rectangle  struttura con la posizione e le dimensioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  che rappresenta l'angolo superiore sinistro della regione rettangolare. |
| size | [Size](../../com.aspose.psd/size) | Una  com.aspose.psd.Size  che rappresenta la larghezza e l'altezza della regione rettangolare. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Converte la struttura  com.aspose.psd.RectangleF  specificata in una struttura  com.aspose.psd.Rectangle  arrotondando i valori di  com.aspose.psd.RectangleF  al prossimo intero superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | La  com.aspose.psd.RectangleF  struttura da convertire. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Determina se il punto specificato è contenuto all'interno di questa  com.aspose.psd.Rectangle  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il  com.aspose.psd.Point  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto rappresentato da  point  è contenuto all'interno di questa  com.aspose.psd.Rectangle  struttura; altrimenti false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determina se la regione rettangolare rappresentata da  rect  è interamente contenuta all'interno di questa  com.aspose.psd.Rectangle  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Il  com.aspose.psd.Rectangle  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se la regione rettangolare rappresentata da  rect  è interamente contenuta all'interno di questa  com.aspose.psd.Rectangle  struttura; altrimenti false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina se il punto specificato è contenuto all'interno di questa  com.aspose.psd.Rectangle  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto definito da  x  e  y  è contenuto all'interno di questa  com.aspose.psd.Rectangle  struttura; altrimenti false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se  obj  è una struttura  com.aspose.psd.Rectangle  con la stessa posizione e dimensione di questa  com.aspose.psd.Rectangle  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  System.Object  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se  obj  è una  com.aspose.psd.Rectangle  struttura e le sue proprietà  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  e  com.aspose.psd.Rectangle.Height  sono uguali alle corrispondenti proprietà di questa  com.aspose.psd.Rectangle  struttura; altrimenti false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Crea una struttura  com.aspose.psd.Rectangle  con le posizioni dei bordi specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | int | La coordinata x dell'angolo superiore sinistro di questa  com.aspose.psd.Rectangle  struttura. |
| top | int | La coordinata y dell'angolo superiore sinistro di questa  com.aspose.psd.Rectangle  struttura. |
| right | int | La coordinata x dell'angolo inferiore destro di questa  com.aspose.psd.Rectangle  struttura. |
| bottom | int | La coordinata y dell'angolo inferiore destro di questa  com.aspose.psd.Rectangle  struttura. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crea un nuovo  Rectangle  a partire da due punti specificati. I due vertici verticali del  Rectangle  creato saranno uguali ai punti  point1  e  point2  forniti. Questi sono tipicamente i vertici opposti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Il primo  Point  per il nuovo rettangolo. |
| point2 | [Point](../../com.aspose.psd/point) | Il secondo  Point  per il nuovo rettangolo. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.Y  e  com.aspose.psd.Rectangle.Height  di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - La coordinata y che è la somma di  com.aspose.psd.Rectangle.Y  e  com.aspose.psd.Rectangle.Height  di questa  com.aspose.psd.Rectangle .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Ottiene una nuova istanza della struttura  com.aspose.psd.Rectangle  che ha i valori  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  e  com.aspose.psd.Rectangle.Height  impostati a zero.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - L'altezza di questa  com.aspose.psd.Rectangle  struttura.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - La coordinata x del bordo sinistro di questa  com.aspose.psd.Rectangle  struttura.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.X  e  com.aspose.psd.Rectangle.Width  di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - La coordinata x che è la somma di  com.aspose.psd.Rectangle.X  e  com.aspose.psd.Rectangle.Width  di questa  com.aspose.psd.Rectangle .
### getSize() {#getSize--}
```
public Size getSize()
```


Ottiene o imposta la dimensione di questa  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - La coordinata y del bordo superiore di questa  com.aspose.psd.Rectangle  struttura.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene la larghezza di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - La larghezza di questa struttura com.aspose.psd.Rectangle.
### getX() {#getX--}
```
public int getX()
```


Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - La coordinata x dell'angolo in alto a sinistra di questa struttura com.aspose.psd.Rectangle.
### getY() {#getY--}
```
public int getY()
```


Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - La coordinata y dell'angolo in alto a sinistra di questa struttura com.aspose.psd.Rectangle.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa struttura  com.aspose.psd.Rectangle .

**Returns:**
int - Un intero che rappresenta il codice hash per questo rettangolo.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Crea e restituisce una copia gonfiata della struttura com.aspose.psd.Rectangle specificata. La copia è gonfiata dell'importo specificato. La struttura com.aspose.psd.Rectangle originale rimane non modificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Il com.aspose.psd.Rectangle con cui iniziare. Questo rettangolo non viene modificato. |
| x | int | L'importo con cui gonfiare orizzontalmente questo com.aspose.psd.Rectangle. |
| y | int | L'importo con cui gonfiare verticalmente questo com.aspose.psd.Rectangle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Ingrandisce questa  com.aspose.psd.Rectangle  dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | L'importo per ingrandire questo rettangolo. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Ingrandisce questa  com.aspose.psd.Rectangle  dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int | L'importo con cui gonfiare orizzontalmente questo com.aspose.psd.Rectangle. |
| altezza | int | L'importo con cui gonfiare verticalmente questo com.aspose.psd.Rectangle. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Sostituisce questa  com.aspose.psd.Rectangle  con l'intersezione di sé stessa e della  com.aspose.psd.Rectangle  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Il com.aspose.psd.Rectangle con cui intersecare. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Restituisce una terza struttura com.aspose.psd.Rectangle che rappresenta l'intersezione di due altre strutture com.aspose.psd.Rectangle. Se non c'è intersezione, viene restituito un com.aspose.psd.Rectangle vuoto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Un primo rettangolo da intersecare. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Un secondo rettangolo da intersecare. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Determina se questo rettangolo interseca con  rect .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da testare. |

**Returns:**
boolean - Questo metodo restituisce true se esiste qualche intersezione, altrimenti false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se tutte le proprietà numeriche di questa  com.aspose.psd.Rectangle  hanno valori zero.

**Returns:**
boolean - Questa proprietà restituisce true se le proprietà com.aspose.psd.Rectangle.Width, com.aspose.psd.Rectangle.Height, com.aspose.psd.Rectangle.X e com.aspose.psd.Rectangle.Y di questo com.aspose.psd.Rectangle hanno tutti valore zero; altrimenti, false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Ottiene un valore che indica se questo  Rectangle  è almeno parzialmente visibile

**Returns:**
boolean - true se questo Rectangle è almeno parzialmente visibile; altrimenti, false.
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Quantità per spostare la posizione. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | Lo spostamento orizzontale. |
| y | int | Lo spostamento verticale. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Verifica se due strutture  com.aspose.psd.Rectangle  hanno la stessa posizione e dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | La struttura com.aspose.psd.Rectangle che si trova a sinistra dell'operatore di uguaglianza. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | La struttura com.aspose.psd.Rectangle che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se le due strutture com.aspose.psd.Rectangle hanno proprietà com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width e com.aspose.psd.Rectangle.Height uguali.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Verifica se due  com.aspose.psd.Rectangle  strutture differiscono per posizione o dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | La struttura com.aspose.psd.Rectangle che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | La struttura com.aspose.psd.Rectangle che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - Questo operatore restituisce true se una qualsiasi delle proprietà com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width o com.aspose.psd.Rectangle.Height delle due strutture com.aspose.psd.Rectangle è diversa; altrimenti false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Converte il  com.aspose.psd.RectangleF  specificato in un  com.aspose.psd.Rectangle  arrotondando i valori del  com.aspose.psd.RectangleF  al numero intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Il com.aspose.psd.RectangleF da convertire. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.Y  e  com.aspose.psd.Rectangle.Height  di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata y che è la somma di com.aspose.psd.Rectangle.Y e com.aspose.psd.Rectangle.Height di questo com.aspose.psd.Rectangle. |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta l'altezza di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'altezza di questa struttura com.aspose.psd.Rectangle. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Ottiene o imposta la coordinata x del bordo sinistro di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata x del bordo sinistro di questa  com.aspose.psd.Rectangle  struttura. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Un  Point  che rappresenta l'angolo superiore sinistro di questa  com.aspose.psd.Rectangle  struttura. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà  com.aspose.psd.Rectangle.X  e  com.aspose.psd.Rectangle.Width  di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata x che è la somma di  com.aspose.psd.Rectangle.X  e  com.aspose.psd.Rectangle.Width  di questa  com.aspose.psd.Rectangle . |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Ottiene o imposta la dimensione di questa  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Un  com.aspose.psd.Size  che rappresenta la larghezza e l'altezza di questa  com.aspose.psd.Rectangle  struttura. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Ottiene o imposta la coordinata y del bordo superiore di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata y del bordo superiore di questa  com.aspose.psd.Rectangle  struttura. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Imposta la larghezza di questa  com.aspose.psd.Rectangle  struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La larghezza di questa  com.aspose.psd.Rectangle  struttura. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata x dell'angolo superiore sinistro di questa  com.aspose.psd.Rectangle  struttura. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La coordinata y dell'angolo superiore sinistro di questa  com.aspose.psd.Rectangle  struttura. |

### toString() {#toString--}
```
public String toString()
```


Converte gli attributi di questo  com.aspose.psd.Rectangle  in una stringa leggibile.

**Returns:**
java.lang.String - Una stringa che contiene la posizione, la larghezza e l'altezza di questa  com.aspose.psd.Rectangle  struttura.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Converte il  com.aspose.psd.RectangleF  specificato in un  com.aspose.psd.Rectangle  troncando i valori del  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Il com.aspose.psd.RectangleF da convertire. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Ottiene una  com.aspose.psd.Rectangle  struttura che contiene l'unione di due  com.aspose.psd.Rectangle  strutture.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Il primo rettangolo da unire. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Il secondo rettangolo da unire. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

