---
title: "LinearGradientBrush"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Encapsule un Aspose.Imaging.Brush avec un dégradé linéaire."
type: docs
weight: 11
url: /fr/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Encapsule un  Aspose.Imaging.Brush  avec un dégradé linéaire. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initialise une nouvelle instance de la  LinearGradientBrush  classe avec les paramètres par défaut. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Initialise une nouvelle instance de la  LinearGradientBrush  classe avec les points et couleurs spécifiés. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Initialise une nouvelle instance de la  LinearGradientBrush  classe avec les points et couleurs spécifiés. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Crée un nouveau clone profond du Brush actuel. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Obtient l'angle du dégradé. |
| [getBlend()](#getBlend--) | Obtient un  Aspose.Imaging.Blend  qui spécifie les positions et les facteurs définissant une atténuation personnalisée pour le dégradé. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getEndColor()](#getEndColor--) | Obtient la couleur finale du dégradé. |
| [getGammaCorrection()](#getGammaCorrection--) | Obtient une valeur indiquant si la correction gamma est activée pour ce LinearGradientBrushBase. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient un com.aspose.psd.ColorBlend qui définit un dégradé linéaire multicolore. |
| [getLinearColors()](#getLinearColors--) | Obtient les couleurs de départ et d'arrivée du dégradé. |
| [getOpacity()](#getOpacity--) | Obtient l'opacité du pinceau. |
| [getRectangle()](#getRectangle--) | Obtient une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [getStartColor()](#getStartColor--) | Obtient la couleur de départ du dégradé. |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Définit un  Aspose.Imaging.Blend  qui spécifie les positions et les facteurs définissant une atténuation personnalisée pour le dégradé. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Définit la couleur finale du dégradé. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Définit une valeur indiquant si la correction gamma est activée pour ce  LinearGradientBrushBase . |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Définit un  com.aspose.psd.ColorBlend  qui définit un dégradé linéaire multicolore. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Définit les couleurs de départ et d'arrivée du dégradé. |
| [setOpacity(float value)](#setOpacity-float-) | Définit l'opacité du pinceau. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crée une atténuation du dégradé basée sur une courbe en forme de cloche. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crée une atténuation du dégradé basée sur une courbe en forme de cloche. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Définit la couleur de départ du dégradé. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Obtient ou définit une copie  Aspose.Imaging.Matrix  qui définit une transformation géométrique locale pour ce  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit une énumération  Aspose.Imaging.WrapMode  qui indique le mode d'enroulement pour ce  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Déplace la transformation géométrique locale des dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initialise une nouvelle instance de la  LinearGradientBrush  classe avec les paramètres par défaut. La couleur de départ est noire, la couleur finale est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialise une nouvelle instance de la  LinearGradientBrush  classe avec les points et couleurs spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Une structure  Aspose.Imaging.Point  qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](../../com.aspose.psd/point) | Une structure  Aspose.Imaging.Point  qui représente le point d'arrivée du dégradé linéaire. |
| color1 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur finale du dégradé linéaire. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialise une nouvelle instance de la  LinearGradientBrush  classe avec les points et couleurs spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Une structure  Aspose.Imaging.PointF  qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Une structure Aspose.Imaging.PointF qui représente le point final du dégradé linéaire. |
| color1 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur finale du dégradé linéaire. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Une structure Aspose.Imaging.RectangleF qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Une structure Aspose.Imaging.RectangleF qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Une structure Aspose.Imaging.RectangleF qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| isAngleScalable | booléen | si défini sur  true  l'angle est modifié lors des transformations avec ce  LinearGradientBrush . |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialise une nouvelle instance de la  LinearGradientBrush  classe basée sur un rectangle, les couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Une structure Aspose.Imaging.RectangleF qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur de départ du dégradé. |
| color2 | [Color](../../com.aspose.psd/color) | Une structure  com.aspose.psd.Color  qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| isAngleScalable | booléen | si défini sur  true  l'angle est modifié lors des transformations avec ce  LinearGradientBrush . |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Obtient un  Aspose.Imaging.Blend  qui spécifie les positions et les facteurs définissant une atténuation personnalisée pour le dégradé.

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


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Obtient la couleur finale du dégradé.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Obtient une valeur indiquant si la correction gamma est activée pour ce LinearGradientBrushBase.

**Returns:**
boolean - La valeur est true si la correction gamma est activée pour ce LinearGradientBrushBase ; sinon, false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtient un com.aspose.psd.ColorBlend qui définit un dégradé linéaire multicolore.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Obtient les couleurs de départ et d'arrivée du dégradé.

**Returns:**
com.aspose.psd.Color[] - Un tableau de deux structures  Color  qui représente les couleurs de départ et d'arrivée du dégradé.
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
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Obtient la couleur de départ du dégradé.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
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

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Définit un  Aspose.Imaging.Blend  qui spécifie les positions et les facteurs définissant une atténuation personnalisée pour le dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Un  Aspose.Imaging.Blend  qui représente une atténuation personnalisée pour le dégradé. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |
| échelle | float | Une valeur comprise entre 0 et 1 qui spécifie la vitesse à laquelle les couleurs diminuent de la couleur de départ vers le  focus  (couleur d'arrivée) |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Définit la couleur finale du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | La couleur d'arrivée du dégradé. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Définit une valeur indiquant si la correction gamma est activée pour ce  LinearGradientBrushBase .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | La valeur est true si la correction gamma est activée pour ce LinearGradientBrushBase ; sinon, false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Définit un  com.aspose.psd.ColorBlend  qui définit un dégradé linéaire multicolore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Un com.aspose.psd.ColorBlend qui définit un dégradé linéaire multicolore. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Définit les couleurs de départ et d'arrivée du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Un tableau de deux structures  Color  qui représente les couleurs de départ et d'arrivée du dégradé. |

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

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crée une atténuation du dégradé basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où la couleur de départ et la couleur d'arrivée sont mélangées à parts égales). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crée une atténuation du dégradé basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |
| échelle | float | Une valeur comprise entre 0 et 1 qui spécifie la rapidité avec laquelle les couleurs diminuent depuis le  focus . |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Définit la couleur de départ du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | La couleur de départ du dégradé. |

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

