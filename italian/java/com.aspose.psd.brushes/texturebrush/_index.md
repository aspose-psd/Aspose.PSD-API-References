---
title: "TextureBrush"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Ogni proprietà della classe Aspose.Imaging.Brushes.TextureBrush è un oggetto Aspose.Imaging.Brush che utilizza un'immagine per riempire l'interno di una forma."
type: docs
weight: 18
url: /it/java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Ogni proprietà della  Aspose.Imaging.Brushes.TextureBrush  classe è un  Aspose.Imaging.Brush  oggetto che utilizza un'immagine per riempire l'interno di una forma. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | Inizializza una nuova istanza della classe  Aspose.Imaging.Brushes.TextureBrush  che utilizza l'immagine specificata. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | Inizializza una nuova istanza della classe  Aspose.Imaging.Brushes.TextureBrush  che utilizza l'immagine specificata e la modalità di avvolgimento. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nuova copia profonda del corrente  Brush . |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getImage()](#getImage--) | Ottiene l'oggetto com.aspose.psd.Image associato a questo oggetto com.aspose.psd.brushes.TextureBrush. |
| [getImageAttributes()](#getImageAttributes--) | Ottiene gli ImageAttributes associati a questo TextureBrush. |
| [getImageRectangle()](#getImageRectangle--) | Ottiene il Rectangle associato a questo TextureBrush. |
| [getOpacity()](#getOpacity--) | Restituisce l'opacità del pennello. |
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
| [setOpacity(float value)](#setOpacity-float-) | Imposta l'opacità del pennello. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Ottiene o imposta una copia di  Aspose.Imaging.Matrix  che definisce una trasformazione geometrica locale per questo  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta una enumerazione  Aspose.Imaging.WrapMode  che indica la modalità di avvolgimento per questo  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


Inizializza una nuova istanza della classe  Aspose.Imaging.Brushes.TextureBrush  che utilizza l'immagine specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Inizializza una nuova istanza della classe  Aspose.Imaging.Brushes.TextureBrush  che utilizza l'immagine specificata e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |
| wrapMode | int | Una enumerazione Aspose.Imaging.WrapMode che specifica come questo oggetto Aspose.Imaging.Brushes.TextureBrush è tessellato. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |
| wrapMode | int | Una enumerazione Aspose.Imaging.WrapMode che specifica come questo oggetto Aspose.Imaging.Brushes.TextureBrush è tessellato. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura Aspose.Imaging.RectangleF che rappresenta il rettangolo di delimitazione per questo oggetto Aspose.Imaging.Brushes.TextureBrush. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |
| wrapMode | int | Una enumerazione Aspose.Imaging.WrapMode che specifica come questo oggetto Aspose.Imaging.Brushes.TextureBrush è tessellato. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura Aspose.Imaging.Rectangle che rappresenta il rettangolo di delimitazione per questo oggetto Aspose.Imaging.Brushes.TextureBrush. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura Aspose.Imaging.RectangleF che rappresenta il rettangolo di delimitazione per questo oggetto Aspose.Imaging.Brushes.TextureBrush. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura Aspose.Imaging.RectangleF che rappresenta il rettangolo di delimitazione per questo oggetto Aspose.Imaging.Brushes.TextureBrush. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Un oggetto com.aspose.psd.ImageAttributes che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto Aspose.Imaging.Brushes.TextureBrush. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura Aspose.Imaging.Rectangle che rappresenta il rettangolo di delimitazione per questo oggetto Aspose.Imaging.Brushes.TextureBrush. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Inizializza una nuova istanza della classe Aspose.Imaging.Brushes.TextureBrush che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'oggetto Aspose.Imaging.Image con cui questo oggetto Aspose.Imaging.Brushes.TextureBrush riempie gli interni. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura Aspose.Imaging.Rectangle che rappresenta il rettangolo di delimitazione per questo oggetto Aspose.Imaging.Brushes.TextureBrush. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Un oggetto com.aspose.psd.ImageAttributes che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto Aspose.Imaging.Brushes.TextureBrush. |

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
### getImage() {#getImage--}
```
public Image getImage()
```


Ottiene l'oggetto com.aspose.psd.Image associato a questo oggetto com.aspose.psd.brushes.TextureBrush.

Valore: Un oggetto com.aspose.psd.Image che rappresenta l'immagine con cui questo oggetto com.aspose.psd.brushes.TextureBrush riempie le forme.

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Ottiene gli ImageAttributes associati a questo TextureBrush.

Valore: Gli ImageAttributes.

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Ottiene il Rectangle associato a questo TextureBrush.

Valore: Il Rectangle.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Ottiene l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**Returns:**
float - Il valore di opacità del pennello.
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

