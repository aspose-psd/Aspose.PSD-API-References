---
title: "LinearGradientBrushBase"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta un Brush con capacità di gradiente e proprietà appropriate."
type: docs
weight: 12
url: /it/java/com.aspose.psd.brushes/lineargradientbrushbase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Rappresenta un  Brush  con capacità di gradiente e proprietà appropriate.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nuova copia profonda del corrente  Brush . |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Restituisce l'angolo del gradiente. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getGammaCorrection()](#getGammaCorrection--) | Restituisce un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase . |
| [getOpacity()](#getOpacity--) | Restituisce l'opacità del pennello. |
| [getRectangle()](#getRectangle--) | Restituisce una regione rettangolare che definisce i punti di inizio e fine del gradiente. |
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
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Imposta un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase . |
| [setOpacity(float value)](#setOpacity-float-) | Imposta l'opacità del pennello. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Imposta una regione rettangolare che definisce i punti di inizio e fine del gradiente. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Restituisce un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase .

**Returns:**
boolean - Il valore è true se la correzione gamma è abilitata per questo LinearGradientBrushBase; altrimenti, false.
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

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Imposta un valore che indica se la correzione gamma è abilitata per questo  LinearGradientBrushBase .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Il valore è true se la correzione gamma è abilitata per questo  LinearGradientBrushBase ; altrimenti, false. |

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

