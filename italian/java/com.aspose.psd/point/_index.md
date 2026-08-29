---
title: "Point"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale."
type: docs
weight: 82
url: /it/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Inizializza una nuova istanza della struttura Aspose.Imaging.Point con le coordinate specificate. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Inizializza una nuova istanza della struttura Aspose.Imaging.Point dalla struttura Aspose.Imaging.Size. |
| [Point(int dw)](#Point-int-) | Inizializza una nuova istanza della  Aspose.Imaging.Point  struttura utilizzando coordinate specificate da un valore intero. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Rappresenta il formato del punto. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Aggiunge il  Aspose.Imaging.Size  specificato al  Aspose.Imaging.Point  specificato. |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Converte il  Aspose.Imaging.PointF  specificato in un  Aspose.Imaging.Point  arrotondando i valori del  Aspose.Imaging.PointF  al successivo valore intero più alto. |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifica se questo  Aspose.Imaging.Point  contiene le stesse coordinate dell'oggetto  System.Object  specificato. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Ottiene una nuova istanza della  Aspose.Imaging.Point  struttura che ha i valori  Aspose.Imaging.Point.X  e  Aspose.Imaging.Point.Y  impostati a zero. |
| [getX()](#getX--) | Ottiene o imposta la coordinata x di questo  Aspose.Imaging.Point . |
| [getY()](#getY--) | Ottiene o imposta la coordinata y di questo  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questo  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Ottiene un valore che indica se questo  Aspose.Imaging.Point  è vuoto. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Trasla questo  Aspose.Imaging.Point  del  Aspose.Imaging.Point  specificato. |
| [offset(int dx, int dy)](#offset-int-int-) | Trasla questo  Aspose.Imaging.Point  dell'importo specificato. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Trasla un  Aspose.Imaging.Point  di una data  Aspose.Imaging.Size . |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Confronta due oggetti  Aspose.Imaging.Point . |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Confronta due oggetti  Aspose.Imaging.Point . |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Trasla un  Aspose.Imaging.Point  del negativo di una data  Aspose.Imaging.Size . |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Converte il  Aspose.Imaging.PointF  specificato in un oggetto  Aspose.Imaging.Point  arrotondando i valori del  Aspose.Imaging.Point  al numero intero più vicino. |
| [setX(int value)](#setX-int-) | Ottiene o imposta la coordinata x di questo  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Ottiene o imposta la coordinata y di questo  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Restituisce il risultato della sottrazione della  Aspose.Imaging.Size  specificata dal  Aspose.Imaging.Point  specificato. |
| [toString()](#toString--) | Converte questo  Aspose.Imaging.Point  in una stringa leggibile dall'uomo. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Converte la struttura  Point  specificata nella struttura  PointF . |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Converte la struttura  Aspose.Imaging.Point  specificata in una struttura  Aspose.Imaging.Size . |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Converte il  Aspose.Imaging.PointF  specificato in un  Aspose.Imaging.Point  troncando i valori del  Aspose.Imaging.Point . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Inizializza una nuova istanza della struttura Aspose.Imaging.Point con le coordinate specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione orizzontale del punto. |
| y | int | La posizione verticale del punto. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Inizializza una nuova istanza della struttura Aspose.Imaging.Point dalla struttura Aspose.Imaging.Size.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Contiene le nuove coordinate del punto. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Inizializza una nuova istanza della  Aspose.Imaging.Point  struttura utilizzando coordinate specificate da un valore intero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dw | int | Un intero a 32 bit che specifica le coordinate per il nuovo punto. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Rappresenta il formato del punto.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Aggiunge il  Aspose.Imaging.Size  specificato al  Aspose.Imaging.Point  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il  Aspose.Imaging.Point  a cui aggiungere. |
| size | [Size](../../com.aspose.psd/size) | La Aspose.Imaging.Size da aggiungere al punto. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Converte il  Aspose.Imaging.PointF  specificato in un  Aspose.Imaging.Point  arrotondando i valori del  Aspose.Imaging.PointF  al successivo valore intero più alto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Il Aspose.Imaging.PointF da convertire. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specifica se questo  Aspose.Imaging.Point  contiene le stesse coordinate dell'oggetto  System.Object  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  System.Object  da testare. |

**Returns:**
boolean - True se obj è un Aspose.Imaging.Point e ha le stesse coordinate di questo Aspose.Imaging.Point.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Ottiene una nuova istanza della  Aspose.Imaging.Point  struttura che ha i valori  Aspose.Imaging.Point.X  e  Aspose.Imaging.Point.Y  impostati a zero.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Ottiene o imposta la coordinata x di questo  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Ottiene o imposta la coordinata y di questo  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questo  Aspose.Imaging.Point .

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ottiene un valore che indica se questo  Aspose.Imaging.Point  è vuoto.

**Returns:**
boolean - True se sia Aspose.Imaging.Point.X sia Aspose.Imaging.Point.Y sono 0; altrimenti, false.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Trasla questo  Aspose.Imaging.Point  del  Aspose.Imaging.Point  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il Aspose.Imaging.Point usato per offsettare questo Aspose.Imaging.Point. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Trasla questo  Aspose.Imaging.Point  dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | int | La quantità per offsettare la coordinata x. |
| dy | int | La quantità per offsettare la coordinata y. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Trasla un  Aspose.Imaging.Point  di una data  Aspose.Imaging.Size .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il Aspose.Imaging.Point da traslare. |
| size | [Size](../../com.aspose.psd/size) | Una Aspose.Imaging.Size che specifica la coppia di numeri da aggiungere alle coordinate del punto. |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Confronta due oggetti Aspose.Imaging.Point. Il risultato specifica se i valori delle proprietà Aspose.Imaging.Point.X e Aspose.Imaging.Point.Y dei due oggetti Aspose.Imaging.Point sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Un primo Aspose.Imaging.Point da confrontare. |
| point2 | [Point](../../com.aspose.psd/point) | Un secondo Aspose.Imaging.Point da confrontare. |

**Returns:**
boolean - True se i valori Aspose.Imaging.Point.X e Aspose.Imaging.Point.Y di point1 e point2 sono uguali; altrimenti, false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Confronta due oggetti Aspose.Imaging.Point. Il risultato specifica se i valori delle proprietà Aspose.Imaging.Point.X o Aspose.Imaging.Point.Y dei due oggetti Aspose.Imaging.Point sono diversi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Un primo Aspose.Imaging.Point da confrontare. |
| point2 | [Point](../../com.aspose.psd/point) | Un secondo Aspose.Imaging.Point da confrontare. |

**Returns:**
boolean - True se i valori di una delle proprietà Aspose.Imaging.Point.X o delle proprietà Aspose.Imaging.Point.Y di point1 e point2 differiscono; altrimenti, false.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Trasla un  Aspose.Imaging.Point  del negativo di una data  Aspose.Imaging.Size .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il Aspose.Imaging.Point da traslare. |
| size | [Size](../../com.aspose.psd/size) | Una Aspose.Imaging.Size che specifica la coppia di numeri da sottrarre dalle coordinate del punto. |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Converte il  Aspose.Imaging.PointF  specificato in un oggetto  Aspose.Imaging.Point  arrotondando i valori del  Aspose.Imaging.Point  al numero intero più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Il Aspose.Imaging.PointF da convertire. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Ottiene o imposta la coordinata x di questo  Aspose.Imaging.Point .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Ottiene o imposta la coordinata y di questo  Aspose.Imaging.Point .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Restituisce il risultato della sottrazione della  Aspose.Imaging.Size  specificata dal  Aspose.Imaging.Point  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il Aspose.Imaging.Point da cui sottrarre. |
| size | [Size](../../com.aspose.psd/size) | La Aspose.Imaging.Size da sottrarre dal punto. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Converte questo  Aspose.Imaging.Point  in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Un  System.String  che rappresenta questa istanza.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Converte la struttura  Point  specificata nella struttura  PointF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il Point da convertire. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Converte la struttura  Aspose.Imaging.Point  specificata in una struttura  Aspose.Imaging.Size .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Il Aspose.Imaging.Point da convertire. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Converte il  Aspose.Imaging.PointF  specificato in un  Aspose.Imaging.Point  troncando i valori del  Aspose.Imaging.Point .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Il Aspose.Imaging.PointF da convertire. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

