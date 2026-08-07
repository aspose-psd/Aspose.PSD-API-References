---
title: "Pen"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce un oggetto utilizzato per disegnare linee, curve e figure."
type: docs
weight: 77
url: /it/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Definisce un oggetto usato per disegnare linee, curve e figure.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Inizializza una nuova istanza della classe Pen con il colore specificato. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Inizializza una nuova istanza della classe Pen con le proprietà Color e Pen.Width specificate. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Inizializza una nuova istanza della classe Pen con il Brush specificato. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Inizializza una nuova istanza della classe Pen con il Brush e Pen.Width specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Restituisce l'allineamento per questo Pen. |
| [getBrush()](#getBrush--) | Restituisce il Brush che determina gli attributi di questo Pen. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Restituisce il colore di questo Pen. |
| [getCompoundArray()](#getCompoundArray--) | Restituisce un array di valori che specifica una Pen composta. |
| [getCustomEndCap()](#getCustomEndCap--) | Restituisce un cap personalizzato da usare alla fine delle linee disegnate con questo Pen. |
| [getCustomStartCap()](#getCustomStartCap--) | Restituisce un cap personalizzato da usare all'inizio delle linee disegnate con questo Pen. |
| [getDashCap()](#getDashCap--) | Restituisce lo stile del cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo Pen. |
| [getDashOffset()](#getDashOffset--) | Restituisce la distanza dall'inizio di una linea all'inizio di un modello di trattino. |
| [getDashPattern()](#getDashPattern--) | Restituisce un array di trattini e spazi personalizzati. |
| [getDashStyle()](#getDashStyle--) | Restituisce lo stile usato per le linee tratteggiate disegnate con questo Pen. |
| [getEndCap()](#getEndCap--) | Restituisce lo stile del cap usato alla fine delle linee disegnate con questo Pen. |
| [getLineJoin()](#getLineJoin--) | Restituisce lo stile di unione per le estremità di due linee consecutive disegnate con questo Pen. |
| [getMiterLimit()](#getMiterLimit--) | Restituisce il limite dello spessore dell'unione su un angolo a spigolo. |
| [getOpacity()](#getOpacity--) | Restituisce l'opacità dell'oggetto. |
| [getPenType()](#getPenType--) | Restituisce lo stile delle linee disegnate con questo Pen. |
| [getStartCap()](#getStartCap--) | Restituisce lo stile del cap usato all'inizio delle linee disegnate con questo Pen. |
| [getTransform()](#getTransform--) | Restituisce una copia della trasformazione geometrica per questo Pen. |
| [getWidth()](#getWidth--) | Restituisce la larghezza di questo Pen, in unità dell'oggetto Graphics utilizzato per il disegno. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Moltiplica la matrice di trasformazione di questo Pen per la Matrix specificata. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Moltiplica la matrice di trasformazione di questo Pen per la Matrix specificata nell'ordine indicato. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Ripristina la matrice di trasformazione geometrica per questa Pen all'identità. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale dell'angolo specificato. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale dei fattori specificati. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato. |
| [setAlignment(int value)](#setAlignment-int-) | Imposta l'allineamento per questa Pen. |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Imposta il Brush che determina gli attributi di questa Pen. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Imposta il colore di questa Pen. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Imposta un array di valori che specifica una penna composta. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Imposta un cap personalizzato da usare alla fine delle linee disegnate con questa Pen. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Imposta un cap personalizzato da usare all'inizio delle linee disegnate con questa Pen. |
| [setDashCap(int value)](#setDashCap-int-) | Imposta lo stile del cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questa Pen. |
| [setDashOffset(float value)](#setDashOffset-float-) | Imposta la distanza dall'inizio di una linea all'inizio di un modello di trattino. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Imposta un array di trattini e spazi personalizzati. |
| [setDashStyle(int value)](#setDashStyle-int-) | Imposta lo stile usato per le linee tratteggiate disegnate con questa Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Imposta lo stile del cap usato alla fine delle linee disegnate con questa Pen. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Imposta i valori che determinano lo stile del cap usato per terminare le linee disegnate da questa Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Imposta lo stile di unione per le estremità di due linee consecutive disegnate con questa Pen. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Imposta il limite dello spessore dell'unione su un angolo a spigolo. |
| [setOpacity(float value)](#setOpacity-float-) | Imposta l'opacità dell'oggetto. |
| [setStartCap(int value)](#setStartCap-int-) | Imposta lo stile del cap usato all'inizio delle linee disegnate con questa Pen. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Imposta una copia della trasformazione geometrica per questa Pen. |
| [setWidth(float value)](#setWidth-float-) | Imposta la larghezza di questa Pen, in unità dell'oggetto Graphics utilizzato per il disegno. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Inizializza una nuova istanza della classe Pen con il colore specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Una struttura Color che indica il colore di questa Pen. |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Inizializza una nuova istanza della classe Pen con le proprietà Color e Pen.Width specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Una struttura Color che indica il colore di questa Pen. |
| larghezza | float | Un valore che indica la larghezza di questa Pen. |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Inizializza una nuova istanza della classe Pen con il Brush specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un Brush che determina le proprietà di riempimento di questa Pen. |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Inizializza una nuova istanza della classe Pen con il Brush e Pen.Width specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un Brush che determina le caratteristiche di questa Pen. |
| larghezza | float | La larghezza della nuova Pen. |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Restituisce l'allineamento per questo Pen.

**Returns:**
int - Un PenAlignment che rappresenta l'allineamento per questa Pen.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Restituisce il Brush che determina gli attributi di questo Pen.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Restituisce il colore di questo Pen.

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Restituisce un array di valori che specifica una penna composta. Una penna composta disegna una linea composta da linee parallele e spazi.

**Returns:**
float[] - Un array di numeri reali che specifica l'array composto. Gli elementi nell'array devono essere in ordine crescente, non inferiori a 0 e non superiori a 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Restituisce un cap personalizzato da usare alla fine delle linee disegnate con questo Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Restituisce un cap personalizzato da usare all'inizio delle linee disegnate con questo Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Restituisce lo stile del cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo Pen.

**Returns:**
int - Uno dei valori DashCap che rappresenta lo stile di cappuccio usato all'inizio e alla fine dei trattini che compongono le linee tratteggiate disegnate con questa Pen.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Restituisce la distanza dall'inizio di una linea all'inizio di un modello di trattino.

**Returns:**
float - La distanza dall'inizio di una linea all'inizio di un modello di trattino.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Restituisce un array di trattini e spazi personalizzati.

**Returns:**
float[] - Un array di numeri reali che specifica le lunghezze di trattini e spazi alternati nelle linee tratteggiate.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Restituisce lo stile usato per le linee tratteggiate disegnate con questo Pen.

**Returns:**
int - Un DashStyle che rappresenta lo stile usato per le linee tratteggiate disegnate con questa Pen.
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Restituisce lo stile del cap usato alla fine delle linee disegnate con questo Pen.

**Returns:**
int - Uno dei valori LineCap che rappresenta lo stile di cappuccio usato alla fine delle linee disegnate con questa Pen.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Restituisce lo stile di unione per le estremità di due linee consecutive disegnate con questo Pen.

**Returns:**
int - Un LineJoin che rappresenta lo stile di giunzione per le estremità di due linee consecutive disegnate con questa Pen.
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Restituisce il limite dello spessore dell'unione su un angolo a spigolo.

**Returns:**
float - Il limite dello spessore della giunzione su un angolo a spigolo.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Restituisce l'opacità dell'oggetto. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che l'oggetto è completamente visibile, un valore di 1 indica che l'oggetto è completamente opaco.

**Returns:**
float - Il valore di opacità.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Restituisce lo stile delle linee disegnate con questo Pen.

**Returns:**
int - Un'enumerazione PenType che specifica lo stile delle linee disegnate con questa Pen.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Restituisce lo stile del cap usato all'inizio delle linee disegnate con questo Pen.

**Returns:**
int - Uno dei valori LineCap che rappresenta lo stile di cappuccio usato all'inizio delle linee disegnate con questa Pen.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Restituisce una copia della trasformazione geometrica per questo Pen.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Restituisce la larghezza di questo Pen, in unità dell'oggetto Graphics utilizzato per il disegno.

**Returns:**
float - La larghezza di questa Pen.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica la matrice di trasformazione di questo Pen per la Matrix specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | L'oggetto Matrix con cui moltiplicare la matrice di trasformazione. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica la matrice di trasformazione di questo Pen per la Matrix specificata nell'ordine indicato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La Matrix con cui moltiplicare la matrice di trasformazione. |
| ordine | int | L'ordine in cui eseguire l'operazione di moltiplicazione. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Ripristina la matrice di trasformazione geometrica per questa Pen all'identità.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale di un angolo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |
| ordine | int | Un MatrixOrder che specifica se aggiungere o anteporre la matrice di rotazione. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale dei fattori specificati. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |
| ordine | int | Un  MatrixOrder  che specifica se aggiungere o anteporre la matrice di scala. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Imposta l'allineamento per questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un  PenAlignment  che rappresenta l'allineamento per questo  Pen . |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Imposta il Brush che determina gli attributi di questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Un  Brush  che determina gli attributi di questo  Pen . |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Imposta il colore di questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Una struttura  Color  che rappresenta il colore di questo  Pen . |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Imposta un array di valori che specifica una penna composta. Una penna composta disegna una linea composta formata da linee parallele e spazi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | Un array di numeri reali che specifica l'array composto. Gli elementi nell'array devono essere in ordine crescente, non inferiori a 0 e non superiori a 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Imposta un cap personalizzato da usare alla fine delle linee disegnate con questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Un  CustomLineCap  che rappresenta il cap usato alla fine delle linee disegnate con questo  Pen . |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Imposta un cap personalizzato da usare all'inizio delle linee disegnate con questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Un  CustomLineCap  che rappresenta il cap usato all'inizio delle linee disegnate con questo  Pen . |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Imposta lo stile del cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Uno dei valori  DashCap  che rappresenta lo stile del cap usato all'inizio e alla fine dei trattini che compongono le linee tratteggiate disegnate con questo  Pen . |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Imposta la distanza dall'inizio di una linea all'inizio di un modello di trattino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La distanza dall'inizio di una linea all'inizio di un modello di trattini. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Imposta un array di trattini e spazi personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | Un array di numeri reali che specifica le lunghezze dei trattini e degli spazi alternati nelle linee tratteggiate. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Imposta lo stile usato per le linee tratteggiate disegnate con questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un  DashStyle  che rappresenta lo stile usato per le linee tratteggiate disegnate con questo  Pen . |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Imposta lo stile del cap usato alla fine delle linee disegnate con questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Uno dei valori  LineCap  che rappresenta lo stile del cap usato alla fine delle linee disegnate con questo  Pen . |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Imposta i valori che determinano lo stile del cap usato per terminare le linee disegnate da questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int | Un  LineCap  che rappresenta lo stile del cap da usare all'inizio delle linee disegnate con questo  Pen . |
| endCap | int | Un  LineCap  che rappresenta lo stile del cap da usare alla fine delle linee disegnate con questo  Pen . |
| dashCap | int | Un  LineCap  che rappresenta lo stile del cap da usare all'inizio o alla fine delle linee tratteggiate disegnate con questo  Pen . |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Imposta lo stile di unione per le estremità di due linee consecutive disegnate con questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un  LineJoin  che rappresenta lo stile di giunzione per le estremità di due linee consecutive disegnate con questo  Pen . |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Imposta il limite dello spessore dell'unione su un angolo a spigolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il limite dello spessore della giunzione su un angolo a spigolo. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Imposta l'opacità dell'oggetto. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che l'oggetto è completamente visibile, un valore di 1 indica che l'oggetto è completamente opaco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore di opacità. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Imposta lo stile del cap usato all'inizio delle linee disegnate con questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Uno dei valori  LineCap  che rappresenta lo stile del cap usato all'inizio delle linee disegnate con questo  Pen . |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Imposta una copia della trasformazione geometrica per questa Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Una copia della  Matrix  che rappresenta la trasformazione geometrica per questo  Pen . |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Imposta la larghezza di questa Pen, in unità dell'oggetto Graphics utilizzato per il disegno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La larghezza di questo  Pen . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione lungo x. |
| dy | float | Il valore della traslazione lungo y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione lungo x. |
| dy | float | Il valore della traslazione lungo y. |
| ordine | int | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

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

