---
title: "PathMulticolorGradientBrush"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Incapsula un oggetto Aspose.Imaging.Brush con un gradiente."
type: docs
weight: 16
url: /it/java/com.aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Incapsula un oggetto  Aspose.Imaging.Brush  con un gradiente. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] points)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---) | Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati. |
| [PathMulticolorGradientBrush(PointF[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-) | Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati e la modalità di avvolgimento. |
| [PathMulticolorGradientBrush(Point[] points)](#PathMulticolorGradientBrush-com.aspose.psd.Point---) | Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati. |
| [PathMulticolorGradientBrush(Point[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.Point---int-) | Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati e la modalità di avvolgimento. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-) | Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con il percorso specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nuova copia profonda del corrente  Brush . |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | Ottiene o imposta il punto centrale del gradiente di percorso. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFocusScales()](#getFocusScales--) | Ottiene il punto di messa a fuoco per la caduta del gradiente. |
| [getGraphicsPath()](#getGraphicsPath--) | Ottiene il percorso grafico su cui è stato costruito questo pennello. |
| [getInterpolationColors()](#getInterpolationColors--) | Ottiene o imposta un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore. |
| [getOpacity()](#getOpacity--) | Restituisce l'opacità del pennello. |
| [getPathPoints()](#getPathPoints--) | Ottiene i punti del percorso su cui è stato costruito questo pennello. |
| [getTransform()](#getTransform--) | Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush . |
| [hashCode()](#hashCode--) |  |
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
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Ottiene o imposta il punto centrale del gradiente di percorso. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Ottiene o imposta il punto focale per la caduta del gradiente. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Ottiene o imposta un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore. |
| [setOpacity(float value)](#setOpacity-float-) | Imposta l'opacità del pennello. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathMulticolorGradientBrush(PointF[] points) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---}
```
public PathMulticolorGradientBrush(PointF[] points)
```


Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Un array di strutture  Aspose.Imaging.PointF  che rappresentano i punti che costituiscono i vertici del percorso. |

### PathMulticolorGradientBrush(PointF[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] points, int wrapMode)
```


Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Un array di strutture  Aspose.Imaging.PointF  che rappresentano i punti che costituiscono i vertici del percorso. |
| wrapMode | int | Un  Aspose.Imaging.WrapMode  che specifica come vengono affiancati i riempimenti disegnati con questo  PathMulticolorGradientBrush . |

### PathMulticolorGradientBrush(Point[] points) {#PathMulticolorGradientBrush-com.aspose.psd.Point---}
```
public PathMulticolorGradientBrush(Point[] points)
```


Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Un array di strutture  Aspose.Imaging.Point  che rappresentano i punti che costituiscono i vertici del percorso. |

### PathMulticolorGradientBrush(Point[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.Point---int-}
```
public PathMulticolorGradientBrush(Point[] points, int wrapMode)
```


Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con i punti specificati e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Un array di strutture  Aspose.Imaging.Point  che rappresentano i punti che costituiscono i vertici del percorso. |
| wrapMode | int | Un  Aspose.Imaging.WrapMode  che specifica come vengono affiancati i riempimenti disegnati con questo  PathMulticolorGradientBrush . |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Inizializza una nuova istanza della classe  PathMulticolorGradientBrush  con il percorso specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il  GraphicsPath  che definisce l'area riempita da questo  PathMulticolorGradientBrush . |

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
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Ottiene o imposta il punto centrale del gradiente di percorso.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Ottiene il punto di messa a fuoco per la caduta del gradiente.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Ottiene il percorso grafico su cui è stato costruito questo pennello.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Ottiene o imposta un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore.

Valore: Un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Ottiene l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**Returns:**
float - Il valore di opacità del pennello.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Ottiene i punti del percorso su cui è stato costruito questo pennello.

**Returns:**
com.aspose.psd.PointF[] - I punti del percorso.
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

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Ottiene o imposta il punto centrale del gradiente di percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Un  Aspose.Imaging.PointF  che rappresenta il punto centrale del gradiente del percorso. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Ottiene o imposta il punto focale per la caduta del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Un  Aspose.Imaging.PointF  che rappresenta il punto focale per la caduta del gradiente. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Ottiene o imposta un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore.

Valore: Un  com.aspose.psd.ColorBlend  che definisce un gradiente lineare multicolore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore di opacità del pennello. |

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

