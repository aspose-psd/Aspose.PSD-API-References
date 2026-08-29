---
title: "LinearGradientBrushBase"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente un pinceau avec des capacités de dégradé et des propriétés appropriées."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.brushes/lineargradientbrushbase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Représente un  Brush  avec des capacités de dégradé et des propriétés appropriées.
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Crée un nouveau clone profond du Brush actuel. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Obtient l'angle du dégradé. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getGammaCorrection()](#getGammaCorrection--) | Obtient une valeur indiquant si la correction gamma est activée pour ce LinearGradientBrushBase. |
| [getOpacity()](#getOpacity--) | Obtient l'opacité du pinceau. |
| [getRectangle()](#getRectangle--) | Obtient une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [getTransform()](#getTransform--) | Obtient ou définit une copie  Aspose.Imaging.Matrix  qui définit une transformation géométrique locale pour ce  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit une énumération  Aspose.Imaging.WrapMode  qui indique le mode d'enroulement pour ce  TransformBrush . |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Obtient une valeur indiquant si  LinearGradientBrushBase.Angle  est modifié lors des transformations avec ce  LinearGradientBrushBase . |
| [isTransformChanged()](#isTransformChanged--) | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplie la  Aspose.Imaging.Matrix  qui représente la transformation géométrique locale de ce  LinearGradientBrush  par la  Aspose.Imaging.Matrix  spécifiée en préfixant la  Aspose.Imaging.Matrix  spécifiée. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplie la  Aspose.Imaging.Matrix  qui représente la transformation géométrique locale de ce  LinearGradientBrush  par la  Aspose.Imaging.Matrix  spécifiée dans l'ordre spécifié. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Réinitialise la propriété  TransformBrush.Transform  à l'identité. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre spécifié. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées dans l'ordre spécifié. |
| [setAngle(float value)](#setAngle-float-) | Définit l'angle du dégradé. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Définit une valeur indiquant si  LinearGradientBrushBase.Angle  est modifié lors des transformations avec ce  LinearGradientBrushBase . |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Définit une valeur indiquant si la correction gamma est activée pour ce  LinearGradientBrushBase . |
| [setOpacity(float value)](#setOpacity-float-) | Définit l'opacité du pinceau. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Obtient ou définit une copie  Aspose.Imaging.Matrix  qui définit une transformation géométrique locale pour ce  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit une énumération  Aspose.Imaging.WrapMode  qui indique le mode d'enroulement pour ce  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Déplace la transformation géométrique locale des dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crée un nouveau clone profond du Brush actuel.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAngle() {#getAngle--}
```
public float getAngle()
```


Obtient l'angle du dégradé.

**Returns:**
float - L'angle du dégradé.
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


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Obtient une valeur indiquant si la correction gamma est activée pour ce LinearGradientBrushBase.

**Returns:**
boolean - La valeur est true si la correction gamma est activée pour ce LinearGradientBrushBase ; sinon, false.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtient l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Returns:**
float - La valeur d'opacité du pinceau.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtient une région rectangulaire qui définit les points de départ et d'arrivée du dégradé.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient ou définit une copie  Aspose.Imaging.Matrix  qui définit une transformation géométrique locale pour ce  TransformBrush .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit une énumération  Aspose.Imaging.WrapMode  qui indique le mode d'enroulement pour ce  TransformBrush .

**Returns:**
int - Un Aspose.Imaging.WrapMode qui spécifie comment les remplissages dessinés avec ce TransformBrush sont disposés en mosaïque.
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


Obtient une valeur indiquant si  LinearGradientBrushBase.Angle  est modifié lors des transformations avec ce  LinearGradientBrushBase .

**Returns:**
boolean - true si LinearGradientBrushBase.Angle est modifié lors des transformations avec ce LinearGradientBrushBase ; sinon, false.
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple, définir la matrice de transformation ou appeler l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+.

Valeur : True si la transformation a été modifiée ; sinon, false.

**Returns:**
booléen
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplie la  Aspose.Imaging.Matrix  qui représente la transformation géométrique locale de ce  LinearGradientBrush  par la  Aspose.Imaging.Matrix  spécifiée en préfixant la  Aspose.Imaging.Matrix  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La Aspose.Imaging.Matrix par laquelle multiplier la transformation géométrique. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie la  Aspose.Imaging.Matrix  qui représente la transformation géométrique locale de ce  LinearGradientBrush  par la  Aspose.Imaging.Matrix  spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La Aspose.Imaging.Matrix par laquelle multiplier la transformation géométrique. |
| ordre | int | Un Aspose.Imaging.MatrixOrder qui spécifie dans quel ordre multiplier les deux matrices. |

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


Réinitialise la propriété  TransformBrush.Transform  à l'identité.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Fait pivoter la transformation géométrique locale du montant spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| ordre | int | Un Aspose.Imaging.MatrixOrder qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Met à l'échelle la transformation géométrique locale des montants spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Met à l'échelle la transformation géométrique locale des valeurs spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |
| ordre | int | Un Aspose.Imaging.MatrixOrder qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Définit l'angle du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'angle du dégradé. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Définit une valeur indiquant si  LinearGradientBrushBase.Angle  est modifié lors des transformations avec ce  LinearGradientBrushBase .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si LinearGradientBrushBase.Angle est modifié pendant les transformations avec ce LinearGradientBrushBase ; sinon, false. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Définit une valeur indiquant si la correction gamma est activée pour ce  LinearGradientBrushBase .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | La valeur est true si la correction gamma est activée pour ce LinearGradientBrushBase ; sinon, false. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur d'opacité du pinceau. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Une structure com.aspose.psd.RectangleF qui spécifie les points de départ et d'arrivée du dégradé. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Obtient ou définit une copie  Aspose.Imaging.Matrix  qui définit une transformation géométrique locale pour ce  TransformBrush .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit une énumération  Aspose.Imaging.WrapMode  qui indique le mode d'enroulement pour ce  TransformBrush .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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


Translater la transformation géométrique locale par les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| ordre | int | L'ordre (préfixe ou suffixe) dans lequel appliquer la translation. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

