---
title: "PathGradientBrush"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Encapsule un objet Aspose.Imaging.Brush avec un dégradé."
type: docs
weight: 14
url: /fr/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Encapsule un objet Aspose.Imaging.Brush avec un dégradé. Cette classe ne peut pas être héritée.

La couleur centrale est blanche par défaut. Un utilisateur peut modifier cette valeur à tout moment ultérieurement.

Le tableau des couleurs d'entourage est initialisé avec un seul élément contenant la couleur blanche par défaut. Les couleurs d'entourage peuvent être modifiées ultérieurement, cependant au moins un élément est requis lors de la configuration des couleurs d'entourage.

Voir le  Blend  pour plus de détails sur son initialisation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés et le mode d'enroulement. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés et le mode d'enroulement. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Initialise une nouvelle instance de la classe  PathGradientBrush  avec le chemin spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Crée un nouveau clone profond du Brush actuel. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Obtient un  Aspose.Imaging.Blend  qui spécifie les positions et les facteurs définissant une atténuation personnalisée pour le dégradé. |
| [getCenterColor()](#getCenterColor--) | Obtient la couleur au centre du dégradé de chemin. |
| [getCenterPoint()](#getCenterPoint--) | Obtient ou définit le point central du dégradé de chemin. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getFocusScales()](#getFocusScales--) | Obtient le point de focalisation pour la décroissance du dégradé. |
| [getGraphicsPath()](#getGraphicsPath--) | Obtient le chemin graphique sur lequel ce pinceau a été construit. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient un com.aspose.psd.ColorBlend qui définit un dégradé linéaire multicolore. |
| [getOpacity()](#getOpacity--) | Obtient l'opacité du pinceau. |
| [getPathPoints()](#getPathPoints--) | Obtient les points du chemin sur lequel ce pinceau a été construit. |
| [getSurroundColors()](#getSurroundColors--) | Obtient un tableau de couleurs correspondant aux points du chemin que ce  PathGradientBrush  remplit. |
| [getTransform()](#getTransform--) | Obtient ou définit une copie  Aspose.Imaging.Matrix  qui définit une transformation géométrique locale pour ce  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit une énumération  Aspose.Imaging.WrapMode  qui indique le mode d'enroulement pour ce  TransformBrush . |
| [hashCode()](#hashCode--) |  |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Définit un  Aspose.Imaging.Blend  qui spécifie les positions et les facteurs définissant une atténuation personnalisée pour le dégradé. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crée un dégradé avec une couleur centrale et une atténuation linéaire vers une couleur d'entourage. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crée un dégradé avec une couleur centrale et une atténuation linéaire vers chaque couleur d'entourage. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Définit la couleur au centre du dégradé de chemin. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Obtient ou définit le point central du dégradé de chemin. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Obtient ou définit le point de focalisation pour la décroissance du dégradé. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Définit un  com.aspose.psd.ColorBlend  qui définit un dégradé linéaire multicolore. |
| [setOpacity(float value)](#setOpacity-float-) | Définit l'opacité du pinceau. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crée un pinceau dégradé qui change de couleur en partant du centre du tracé vers la bordure du tracé. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crée un pinceau dégradé qui change de couleur en partant du centre du tracé vers la bordure du tracé. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Définit un tableau de couleurs correspondant aux points du tracé que ce  PathGradientBrush  remplit. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Obtient ou définit une copie  Aspose.Imaging.Matrix  qui définit une transformation géométrique locale pour ce  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit une énumération  Aspose.Imaging.WrapMode  qui indique le mode d'enroulement pour ce  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Déplace la transformation géométrique locale des dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Un tableau de structures Aspose.Imaging.PointF qui représente les points constituant les sommets du chemin. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés et le mode d'enroulement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Un tableau de structures Aspose.Imaging.PointF qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un  Aspose.Imaging.WrapMode  qui spécifie comment les remplissages dessinés avec ce  PathGradientBrush  sont mosaïqués. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Un tableau de structures Aspose.Imaging.Point qui représente les points constituant les sommets du chemin. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initialise une nouvelle instance de la classe  PathGradientBrush  avec les points spécifiés et le mode d'enroulement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Un tableau de structures Aspose.Imaging.Point qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un  Aspose.Imaging.WrapMode  qui spécifie comment les remplissages dessinés avec ce  PathGradientBrush  sont mosaïqués. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initialise une nouvelle instance de la classe  PathGradientBrush  avec le chemin spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le  GraphicsPath  qui définit la zone remplie par ce  PathGradientBrush . |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Obtient un  Aspose.Imaging.Blend  qui spécifie les positions et les facteurs définissant une atténuation personnalisée pour le dégradé.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Obtient la couleur au centre du dégradé de chemin.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Obtient ou définit le point central du dégradé de chemin.

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


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Obtient le point de focalisation pour la décroissance du dégradé.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Obtient le chemin graphique sur lequel ce pinceau a été construit.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtient un com.aspose.psd.ColorBlend qui définit un dégradé linéaire multicolore.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtient l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Returns:**
float - La valeur d'opacité du pinceau.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Obtient les points du chemin sur lequel ce pinceau a été construit.

**Returns:**
com.aspose.psd.PointF[] - Les points du chemin.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Obtient un tableau de couleurs correspondant aux points du chemin que ce  PathGradientBrush  remplit.

**Returns:**
com.aspose.psd.Color[] - Un tableau de structures  com.aspose.psd.Color  qui représente les couleurs associées à chaque point du tracé que ce  PathGradientBrush  remplit.
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


Crée un dégradé avec une couleur centrale et une atténuation linéaire vers une couleur d'entourage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de tout rayon du centre du tracé jusqu'à la bordure du tracé, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du tracé. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crée un dégradé avec une couleur centrale et une atténuation linéaire vers chaque couleur d'entourage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de tout rayon du centre du tracé jusqu'à la bordure du tracé, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du tracé. |
| échelle | float | Une valeur comprise entre 0 et 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de la bordure. Une valeur de 1 entraîne l'intensité la plus élevée possible de la couleur centrale, et c'est la valeur par défaut. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Définit la couleur au centre du dégradé de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Un  com.aspose.psd.Color  qui représente la couleur au centre du dégradé du tracé. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Obtient ou définit le point central du dégradé de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Un Aspose.Imaging.PointF qui représente le point central du dégradé de chemin. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Obtient ou définit le point de focalisation pour la décroissance du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Un Aspose.Imaging.PointF qui représente le point de focalisation pour la décroissance du dégradé. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Définit un  com.aspose.psd.ColorBlend  qui définit un dégradé linéaire multicolore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Un com.aspose.psd.ColorBlend qui définit un dégradé linéaire multicolore. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur d'opacité du pinceau. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crée un pinceau dégradé qui change de couleur en partant du centre du tracé vers la bordure du tracé. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de tout rayon du centre du tracé jusqu'à la bordure du tracé, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du tracé. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crée un pinceau dégradé qui change de couleur en partant du centre du tracé vers la bordure du tracé. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de tout rayon du centre du tracé jusqu'à la bordure du tracé, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du tracé. |
| échelle | float | Une valeur comprise entre 0 et 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de la bordure. Une valeur de 1 entraîne l'intensité la plus élevée possible de la couleur centrale, et c'est la valeur par défaut. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Définit un tableau de couleurs correspondant aux points du tracé que ce  PathGradientBrush  remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Un tableau de structures  com.aspose.psd.Color  qui représente les couleurs associées à chaque point du tracé que ce  PathGradientBrush  remplit. |

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

