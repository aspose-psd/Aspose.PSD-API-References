---
title: "Matrix"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Sostituisce la Matrix GDI."
type: docs
weight: 69
url: /it/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Sostituisce la matrice GDI+.

La maggior parte degli algoritmi è presa da AffineTransform.java di Sun. Nomi Java per gli elementi della matrice usati internamente. Mappa dei nomi Java a quelli .net con descrizione: m00 M11 Scala X m10 M12 Taglio Y m01 M21 Taglio X m11 M22 Scala Y m02 M31 Traslazione X m12 M32 Traslazione Y
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Matrix()](#Matrix--) | Inizializza una nuova istanza della classe Matrix come matrice identità. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Inizializza una nuova istanza della classe  Matrix  . |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Crea una copia della classe  Matrix  . |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Inizializza una nuova istanza della classe  Aspose.Imaging.Matrix  per la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Inizializza una nuova istanza della classe  Aspose.Imaging.Matrix  per la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Questo bit di flag indica che la trasformazione definita da questo oggetto esegue un ribaltamento dell'immagine speculare attorno a qualche asse, il che cambia il sistema di coordinate normalmente destro in un sistema sinistro, oltre alle conversioni indicate dagli altri bit di flag. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di un angolo arbitrario, oltre alle conversioni indicate dagli altri bit di flag. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Una scala generale moltiplica la lunghezza dei vettori di quantità diverse nelle direzioni x e y senza modificare l'angolo tra vettori perpendicolari. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Questa costante indica che la trasformazione definita da questo oggetto esegue una conversione arbitraria delle coordinate di input. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Una trasformazione identità è quella in cui le coordinate di output sono sempre le stesse delle coordinate di input. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Questa costante è una maschera di bit per qualsiasi dei bit di flag di rotazione. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Questa costante è una maschera di bit per qualsiasi dei bit di flag di scala. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di quadrante di un multiplo di 90 gradi oltre alle conversioni indicate dagli altri bit di flag. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Una traslazione sposta le coordinate di una quantità costante in x e y senza modificare la lunghezza o l'angolo dei vettori. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Una scala uniforme moltiplica la lunghezza dei vettori della stessa quantità sia nella direzione x che y senza cambiare l'angolo tra i vettori. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'oggetto  System.Object  specificato è uguale a questa istanza. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Ottiene una copia degli elementi della matrice. |
| [getM11()](#getM11--) | Ottiene l'elemento della matrice nella prima riga, prima colonna. |
| [getM12()](#getM12--) | Ottiene l'elemento della matrice nella prima riga, seconda colonna. |
| [getM21()](#getM21--) | Ottiene l'elemento della matrice nella seconda riga, prima colonna. |
| [getM22()](#getM22--) | Ottiene l'elemento della matrice nella seconda riga, seconda colonna. |
| [getM31()](#getM31--) | Ottiene l'elemento della matrice nella terza riga, prima colonna. |
| [getM32()](#getM32--) | Ottiene l'elemento della matrice nella terza riga, prima colonna. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Determina se due matrici sono uguali. |
| [isIdentity()](#isIdentity--) | Restituisce `true` se questo `AffineTransform` è una trasformazione identità. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Moltiplica questa Matrix per la matrice specificata nel parametro matrix usando l'ordine (predefinito) Prepend. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Moltiplica questa Matrix per la matrice specificata nel parametro matrix, e nell'ordine specificato nel parametro order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Reimposta questa Matrix per avere gli elementi della matrice identità. |
| [rotate(float angle)](#rotate-float-) | Applica una rotazione in senso orario di una quantità specificata nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine predefinito (Prepend). |
| [rotate(float angle, int order)](#rotate-float-int-) | Applica una rotazione in senso orario di una quantità specificata nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine specificato. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine predefinito (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine specificato. |
| [scale(float sx, float sy)](#scale-float-float-) | Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine (predefinito) Prepend. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Applica il vettore di scala specificato (scaleX e scaleY) a questa  Matrix  usando l'ordine specificato. |
| [toString()](#toString--) | Restituisce un  System.String  che rappresenta questa istanza. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Applica la trasformazione geometrica rappresentata da questa  Matrix  a un array specificato di punti. |
| [translate(float tx, float ty)](#translate-float-float-) | Applica il vettore di traslazione specificato a questa  Matrix  utilizzando l'ordine Prepend (predefinito). |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Applica il vettore di traslazione specificato a questa Matrix nell'ordine specificato. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Inizializza una nuova istanza della classe Matrix come matrice identità.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Inizializza una nuova istanza della classe  Matrix  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m11 | float | m00 M11 Scala X |
| m12 | float | m10 M12 Taglio Y |
| m21 | float | m01 M21 Taglio X |
| m22 | float | m11 M22 Scala Y |
| m31 | float | m02 M31 Trasla X |
| m32 | float | m12 M32 Trasla Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Crea una copia della classe  Matrix  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | la matrice base per l'adattamento |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Inizializza una nuova istanza della classe  Aspose.Imaging.Matrix  per la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura  Aspose.Imaging.RectangleF  che rappresenta il rettangolo da trasformare. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Un array di tre strutture  Aspose.Imaging.PointF  che rappresentano i punti di un parallelogramma verso il quale i vertici superiore sinistro, superiore destro e inferiore sinistro del rettangolo devono essere trasformati. Il vertice inferiore destro del parallelogramma è implicito nei primi tre vertici. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Inizializza una nuova istanza della classe  Aspose.Imaging.Matrix  per la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura  Aspose.Imaging.Rectangle  che rappresenta il rettangolo da trasformare. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Un array di tre strutture  Aspose.Imaging.Point  che rappresentano i punti di un parallelogramma verso il quale i vertici superiore sinistro, superiore destro e inferiore sinistro del rettangolo devono essere trasformati. Il vertice inferiore destro del parallelogramma è implicito nei primi tre vertici. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Questo bit di flag indica che la trasformazione definita da questo oggetto esegue un ribaltamento a specchio attorno a qualche asse, il quale cambia il normale sistema di coordinate destro in un sistema sinistro, oltre alle conversioni indicate dagli altri bit di flag. Un sistema di coordinate destro è quello in cui l'asse X positivo ruota in senso antiorario per sovrapporsi all'asse Y positivo, simile alla direzione in cui si curvano le dita della mano destra quando si guarda il pollice di profilo. Un sistema di coordinate sinistro è quello in cui l'asse X positivo ruota in senso orario per sovrapporsi all'asse Y positivo, simile alla direzione in cui si curvano le dita della mano sinistra. Non esiste un modo matematico per determinare l'angolo della trasformazione originale di ribaltamento o specchiatura, poiché tutti gli angoli di ribaltamento sono identici dato un'adeguata rotazione di compensazione. NOTA: TypeFlip è stato aggiunto dopo che GENERAL\_TRANSFORM era in circolazione pubblica e i bit di flag non potevano più essere rinumerati comodamente senza introdurre incompatibilità binarie nel codice esterno.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di un angolo arbitrario, oltre alle conversioni indicate dagli altri bit di flag. Una rotazione cambia gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza modificare la lunghezza del vettore. Questo bit di flag è mutualmente esclusivo con il

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Una scala generale moltiplica la lunghezza dei vettori di quantità diverse nelle direzioni x e y senza cambiare l'angolo tra vettori perpendicolari. Questo bit di flag è mutualmente esclusivo con il flag TypeUniformScale.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Questa costante indica che la trasformazione definita da questo oggetto esegue una conversione arbitraria delle coordinate di input. Se questa trasformazione può essere classificata da una delle costanti sopra, il tipo sarà o la costante TypeIdentity o una combinazione dei bit di flag appropriati per le varie conversioni di coordinate che questa trasformazione esegue.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Una trasformazione identità è quella in cui le coordinate di output sono sempre le stesse delle coordinate di input. Se questa trasformazione è diversa dalla trasformazione identità, il tipo sarà o la costante GENERAL\_TRANSFORM o una combinazione dei bit di flag appropriati per le varie conversioni di coordinate che questa trasformazione esegue.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Questa costante è una maschera di bit per qualsiasi dei bit di flag di rotazione.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Questa costante è una maschera di bit per qualsiasi dei bit di flag di scala.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di quadrante di un multiplo di 90 gradi, oltre alle conversioni indicate dagli altri bit di flag. Una rotazione cambia gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza modificare la lunghezza del vettore. Questo bit di flag è mutualmente esclusivo con il flag TypeGeneralRotation.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Una traslazione sposta le coordinate di una quantità costante in x e y senza modificare la lunghezza o l'angolo dei vettori.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Una scala uniforme moltiplica la lunghezza dei vettori della stessa quantità sia nelle direzioni x che y senza modificare l'angolo tra i vettori. Questo bit di flag è mutuamente esclusivo con il flag TypeGeneralScale.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'oggetto  System.Object  specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  System.Object  da confrontare con questa istanza. |

**Returns:**
boolean - true se l'oggetto System.Object specificato è uguale a questa istanza; altrimenti, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Ottiene una copia degli elementi della matrice.

**Returns:**
float[] - Una copia degli elementi della matrice.
### getM11() {#getM11--}
```
public float getM11()
```


Restituisce l'elemento della matrice alla prima riga prima colonna. Rappresenta la scala lungo l'asse X.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Restituisce l'elemento della matrice alla prima riga seconda colonna. Rappresenta lo shear lungo l'asse Y.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Restituisce l'elemento della matrice alla seconda riga prima colonna. Rappresenta lo shear lungo l'asse X.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Restituisce l'elemento della matrice alla seconda riga seconda colonna. Rappresenta la scala lungo l'asse Y.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Restituisce l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse X.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Restituisce l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse Y.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Determina se due matrici sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | La prima matrice da confrontare. |
| b | [Matrix](../../com.aspose.psd/matrix) | La seconda matrice da confrontare. |

**Returns:**
boolean - True se le matrici sono uguali.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Restituisce `true` se questo `AffineTransform` è una trasformazione identità.

**Returns:**
boolean - `true` se questo `AffineTransform` è una trasformazione identità; `false` altrimenti.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Moltiplica questa Matrix per la matrice specificata nel parametro matrix usando l'ordine (predefinito) Prepend.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | La matrice con cui moltiplicare. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Moltiplica questa Matrix per la matrice specificata nel parametro matrix, e nell'ordine specificato nel parametro order.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Il tx. Il tx. Il tx. |
| ordine | int | L'ordine. L'ordine. L'ordine. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Reimposta questa Matrix per avere gli elementi della matrice identità.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Applica una rotazione in senso orario di una quantità specificata nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine predefinito (Prepend).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Applica una rotazione in senso orario di una quantità specificata nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |
| ordine | int | L'ordine della matrice. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine predefinito (Prepend).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo. |
| point | [PointF](../../com.aspose.psd/pointf) | Il punto. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo. |
| point | [PointF](../../com.aspose.psd/pointf) | Il punto. |
| ordine | int | L'ordine. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine (predefinito) Prepend.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il sx. Il sx. Il sx. |
| sy | float | Il sy. Il sy. Il sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Applica il vettore di scala specificato (scaleX e scaleY) a questa  Matrix  usando l'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | float | La scala X. |
| scaleY | float | La scala Y. |
| ordine | int | L'ordine. |

### toString() {#toString--}
```
public String toString()
```


Restituisce un  System.String  che rappresenta questa istanza.

**Returns:**
java.lang.String - Un  System.String  che rappresenta questa istanza.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Applica la trasformazione geometrica rappresentata da questa  Matrix  a un array specificato di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | I punti. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Applica il vettore di traslazione specificato a questa  Matrix  utilizzando l'ordine Prepend (predefinito).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tx | float | Il tx. Il tx. Il tx. |
| ty | float | Il ty. Il ty. Il ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Applica il vettore di traslazione specificato a questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offsetX | float | L'offset X. |
| offsetY | float | L'offset Y. |
| ordine | int | L'ordine. |

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

