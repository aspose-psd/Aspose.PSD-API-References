---
title: "LinearGradientBrush"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Incapsula un Aspose.Imaging.Brush con un gradiente lineare."
type: docs
weight: 11
url: /it/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Incapsula un  Aspose.Imaging.Brush  con un gradiente lineare. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Inizializza una nuova istanza della  LinearGradientBrush  classe con parametri predefiniti. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Inizializza una nuova istanza della  LinearGradientBrush  classe con i punti e i colori specificati. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Inizializza una nuova istanza della  LinearGradientBrush  classe con i punti e i colori specificati. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nuova copia profonda del corrente  Brush . |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Restituisce l'angolo del gradiente. |
| [getBlend()](#getBlend--) | Ottiene un  Aspose.Imaging.Blend  che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getEndColor()](#getEndColor--) | Ottiene il colore finale del gradiente. |
| [getGammaCorrection()](#getGammaCorrection--) | Restituisce un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase . |
| [getInterpolationColors()](#getInterpolationColors--) | Restituisce un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore. |
| [getLinearColors()](#getLinearColors--) | Ottiene i colori di inizio e fine del gradiente. |
| [getOpacity()](#getOpacity--) | Restituisce l'opacità del pennello. |
| [getRectangle()](#getRectangle--) | Restituisce una regione rettangolare che definisce i punti di inizio e fine del gradiente. |
| [getStartColor()](#getStartColor--) | Ottiene il colore iniziale del gradiente. |
| [getTransform()](#getTransform--) | Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush . |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Restituisce un valore che indica se  LinearGradientBrushBase.Angle  viene modificato durante le trasformazioni con questo  LinearGradientBrushBase . |
| [isTransformChanged()](#isTransformChanged--) | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Moltiplica la  Aspose.Imaging.Matrix  che rappresenta la trasformazione geometrica locale di questo  LinearGradientBrush  per la  Aspose.Imaging.Matrix  specificata, anteponendo la  Aspose.Imaging.Matrix  specificata. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Moltiplica la  Aspose.Imaging.Matrix  che rappresenta la trasformazione geometrica locale di questo  LinearGradientBrush  per la  Aspose.Imaging.Matrix  specificata nell'ordine specificato. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Reimposta la proprietà  TransformBrush.Transform  a identità. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale dell'importo specificato. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale degli importi specificati. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato. |
| [setAngle(float value)](#setAngle-float-) | Imposta l'angolo del gradiente. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Imposta un valore che indica se  LinearGradientBrushBase.Angle  viene modificato durante le trasformazioni con questo  LinearGradientBrushBase . |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Imposta un  Aspose.Imaging.Blend  che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Imposta il colore finale del gradiente. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Imposta un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase . |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Imposta un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Imposta i colori di inizio e fine del gradiente. |
| [setOpacity(float value)](#setOpacity-float-) | Imposta l'opacità del pennello. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Imposta una regione rettangolare che definisce i punti di inizio e fine del gradiente. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea una caduta del gradiente basata su una curva a campana. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea una caduta del gradiente basata su una curva a campana. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Imposta il colore iniziale del gradiente. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Inizializza una nuova istanza della classe  LinearGradientBrush  con parametri predefiniti. Il colore iniziale è nero, il colore finale è bianco, l'angolo è 45 gradi e il rettangolo si trova in (0,0) con dimensioni (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Inizializza una nuova istanza della  LinearGradientBrush  classe con i punti e i colori specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Una struttura Aspose.Imaging.Point che rappresenta il punto iniziale del gradiente lineare. |
| point2 | [Point](../../com.aspose.psd/point) | Una struttura Aspose.Imaging.Point che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore finale del gradiente lineare. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Inizializza una nuova istanza della  LinearGradientBrush  classe con i punti e i colori specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Una struttura Aspose.Imaging.PointF che rappresenta il punto iniziale del gradiente lineare. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Una struttura Aspose.Imaging.PointF che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore finale del gradiente lineare. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura Aspose.Imaging.RectangleF che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore finale per il gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura Aspose.Imaging.RectangleF che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore finale per il gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura Aspose.Imaging.RectangleF che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore finale per il gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScalable | boolean | Se impostato su  true , l'angolo viene modificato durante le trasformazioni con questo  LinearGradientBrush . |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inizializza una nuova istanza della  LinearGradientBrush  classe basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura Aspose.Imaging.RectangleF che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.psd/color) | Una struttura  com.aspose.psd.Color  che rappresenta il colore finale per il gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScalable | boolean | Se impostato su  true , l'angolo viene modificato durante le trasformazioni con questo  LinearGradientBrush . |

### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crea una nuova copia profonda del corrente  Brush .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Restituisce l'angolo del gradiente.

**Returns:**
float - L'angolo del gradiente.
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Ottiene un  Aspose.Imaging.Blend  che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Ottiene il colore finale del gradiente.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Restituisce un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase .

**Returns:**
boolean - Il valore è true se la correzione gamma è abilitata per questo LinearGradientBrushBase; altrimenti, false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Restituisce un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Ottiene i colori di inizio e fine del gradiente.

**Returns:**
com.aspose.psd.Color[] - Un array di due strutture  Color  che rappresentano i colori iniziale e finale del gradiente.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Ottiene l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**Returns:**
float - Il valore di opacità del pennello.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Restituisce una regione rettangolare che definisce i punti di inizio e fine del gradiente.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Ottiene il colore iniziale del gradiente.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush .

**Returns:**
int - Un Aspose.Imaging.WrapMode che specifica come i riempimenti disegnati con questo TransformBrush vengono ripetuti.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Restituisce un valore che indica se  LinearGradientBrushBase.Angle  viene modificato durante le trasformazioni con questo  LinearGradientBrushBase .

**Returns:**
boolean - true se LinearGradientBrushBase.Angle viene modificato durante le trasformazioni con questo LinearGradientBrushBase; altrimenti, false.
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+.

Valore: True se la trasformazione è stata modificata; altrimenti, false.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica la  Aspose.Imaging.Matrix  che rappresenta la trasformazione geometrica locale di questo  LinearGradientBrush  per la  Aspose.Imaging.Matrix  specificata, anteponendo la  Aspose.Imaging.Matrix  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La Aspose.Imaging.Matrix con cui moltiplicare la trasformazione geometrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica la  Aspose.Imaging.Matrix  che rappresenta la trasformazione geometrica locale di questo  LinearGradientBrush  per la  Aspose.Imaging.Matrix  specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La Aspose.Imaging.Matrix con cui moltiplicare la trasformazione geometrica. |
| ordine | int | Un Aspose.Imaging.MatrixOrder che specifica in quale ordine moltiplicare le due matrici. |

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


Reimposta la proprietà  TransformBrush.Transform  a identità.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale dell'importo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |
| ordine | int | Un Aspose.Imaging.MatrixOrder che specifica se aggiungere o anteporre la matrice di rotazione. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale di quantità specificate. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità di scala da applicare alla trasformazione lungo l'asse x. |
| sy | float | La quantità di scala da applicare alla trasformazione lungo l'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità di scala da applicare alla trasformazione lungo l'asse x. |
| sy | float | La quantità di scala da applicare alla trasformazione lungo l'asse y. |
| ordine | int | Un  Aspose.Imaging.MatrixOrder  che specifica se aggiungere o anteporre la matrice di scala. |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Imposta l'angolo del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'angolo del gradiente. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Imposta un valore che indica se  LinearGradientBrushBase.Angle  viene modificato durante le trasformazioni con questo  LinearGradientBrushBase .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true se  LinearGradientBrushBase.Angle  viene modificato durante le trasformazioni con questo  LinearGradientBrushBase ; altrimenti, false. |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Imposta un  Aspose.Imaging.Blend  che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Un  Aspose.Imaging.Blend  che rappresenta una caduta personalizzata per il gradiente. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scale | float | Un valore da 0 a 1 che specifica la rapidità con cui i colori decadono dal colore iniziale al  focus  (colore finale) |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Imposta il colore finale del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Il colore finale del gradiente. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Imposta un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Il valore è true se la correzione gamma è abilitata per questo  LinearGradientBrushBase ; altrimenti, false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Imposta un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Imposta i colori di inizio e fine del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Un array di due strutture  Color  che rappresenta i colori iniziale e finale del gradiente. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore di opacità del pennello. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Imposta una regione rettangolare che definisce i punti di inizio e fine del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura  com.aspose.psd.RectangleF  che specifica i punti di inizio e fine del gradiente. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea una caduta del gradiente basata su una curva a campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il colore iniziale e quello finale sono mescolati in egual misura). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea una caduta del gradiente basata su una curva a campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scale | float | Un valore da 0 a 1 che specifica la rapidità con cui i colori decadono dal  focus . |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Imposta il colore iniziale del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Il colore iniziale del gradiente. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

