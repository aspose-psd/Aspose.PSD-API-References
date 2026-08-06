---
title: "Pen"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit un objet utilisé pour dessiner des lignes, des courbes et des figures."
type: docs
weight: 77
url: /fr/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Définit un objet utilisé pour dessiner des lignes, des courbes et des figures.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Initialise une nouvelle instance de la classe  Pen  avec la couleur spécifiée. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Initialise une nouvelle instance de la classe  Pen  avec les propriétés  Color  et  Pen.Width  spécifiées. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Initialise une nouvelle instance de la classe  Pen  avec le  Brush  spécifié. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Initialise une nouvelle instance de la classe  Pen  avec le  Brush  et le  Pen.Width  spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Obtient l'alignement de ce  Pen . |
| [getBrush()](#getBrush--) | Obtient le  Brush  qui détermine les attributs de ce  Pen . |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtient la couleur de ce  Pen . |
| [getCompoundArray()](#getCompoundArray--) | Obtient un tableau de valeurs qui spécifie un Pen composé. |
| [getCustomEndCap()](#getCustomEndCap--) | Obtient un cap personnalisé à utiliser à la fin des lignes tracées avec ce  Pen . |
| [getCustomStartCap()](#getCustomStartCap--) | Obtient un cap personnalisé à utiliser au début des lignes tracées avec ce  Pen . |
| [getDashCap()](#getDashCap--) | Obtient le style de cap utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce  Pen . |
| [getDashOffset()](#getDashOffset--) | Obtient la distance du début d'une ligne au commencement d'un motif de tirets. |
| [getDashPattern()](#getDashPattern--) | Obtient un tableau de tirets et d'espaces personnalisés. |
| [getDashStyle()](#getDashStyle--) | Obtient le style utilisé pour les lignes pointillées tracées avec ce  Pen . |
| [getEndCap()](#getEndCap--) | Obtient le style de cap utilisé à la fin des lignes tracées avec ce  Pen . |
| [getLineJoin()](#getLineJoin--) | Obtient le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce  Pen . |
| [getMiterLimit()](#getMiterLimit--) | Obtient la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [getOpacity()](#getOpacity--) | Obtient l'opacité de l'objet. |
| [getPenType()](#getPenType--) | Obtient le style des lignes tracées avec ce  Pen . |
| [getStartCap()](#getStartCap--) | Obtient le style de cap utilisé au début des lignes tracées avec ce  Pen . |
| [getTransform()](#getTransform--) | Obtient une copie de la transformation géométrique de ce  Pen . |
| [getWidth()](#getWidth--) | Obtient la largeur de ce  Pen , en unités de l'objet Graphics utilisé pour le dessin. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplie la matrice de transformation de ce  Pen  par la  Matrix  spécifiée. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplie la matrice de transformation de ce  Pen  par la  Matrix  spécifiée dans l'ordre spécifié. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Réinitialise la matrice de transformation géométrique de ce  Pen  à l'identité. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale de l'angle spécifié. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre spécifié. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié. |
| [setAlignment(int value)](#setAlignment-int-) | Définit l'alignement pour ce  Pen . |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Définit le  Brush  qui détermine les attributs de ce  Pen . |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Définit la couleur de ce  Pen . |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Définit un tableau de valeurs qui spécifie un  Pen  composé. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Définit une coiffe personnalisée à utiliser à la fin des lignes tracées avec ce  Pen . |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Définit une coiffe personnalisée à utiliser au début des lignes tracées avec ce  Pen . |
| [setDashCap(int value)](#setDashCap-int-) | Définit le style de coiffe utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce  Pen . |
| [setDashOffset(float value)](#setDashOffset-float-) | Définit la distance du début d'une ligne au commencement d'un motif de tirets. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Définit un tableau de tirets et d'espaces personnalisés. |
| [setDashStyle(int value)](#setDashStyle-int-) | Définit le style utilisé pour les lignes pointillées tracées avec ce  Pen . |
| [setEndCap(int value)](#setEndCap-int-) | Définit le style de coiffe utilisé à la fin des lignes tracées avec ce  Pen . |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Définit les valeurs qui déterminent le style de coiffe utilisé pour terminer les lignes tracées par ce  Pen . |
| [setLineJoin(int value)](#setLineJoin-int-) | Définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce  Pen . |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [setOpacity(float value)](#setOpacity-float-) | Définit l'opacité de l'objet. |
| [setStartCap(int value)](#setStartCap-int-) | Définit le style de coiffe utilisé au début des lignes tracées avec ce  Pen . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Définit une copie de la transformation géométrique pour ce  Pen . |
| [setWidth(float value)](#setWidth-float-) | Définit la largeur de ce  Pen , en unités de l'objet Graphics utilisé pour le dessin. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translater la transformation géométrique locale par les dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Initialise une nouvelle instance de la classe  Pen  avec la couleur spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Une structure  Color  qui indique la couleur de ce  Pen . |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Initialise une nouvelle instance de la classe  Pen  avec les propriétés  Color  et  Pen.Width  spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Une structure  Color  qui indique la couleur de ce  Pen . |
| largeur | float | Une valeur indiquant la largeur de ce  Pen . |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Initialise une nouvelle instance de la classe  Pen  avec le  Brush  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un  Brush  qui détermine les propriétés de remplissage de ce  Pen . |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialise une nouvelle instance de la classe  Pen  avec le  Brush  et le  Pen.Width  spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un  Brush  qui détermine les caractéristiques de ce  Pen . |
| largeur | float | La largeur du nouveau  Pen . |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtient l'alignement de ce  Pen .

**Returns:**
int - Un  PenAlignment  qui représente l'alignement pour ce  Pen .
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Obtient le  Brush  qui détermine les attributs de ce  Pen .

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


Obtient la couleur de ce  Pen .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Obtient un tableau de valeurs qui spécifie un Pen composé. Un Pen composé trace une ligne composée de lignes parallèles et d'espaces.

**Returns:**
float[] - Un tableau de nombres réels qui spécifie le tableau composé. Les éléments du tableau doivent être en ordre croissant, pas moins que 0, et pas plus que 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Obtient un cap personnalisé à utiliser à la fin des lignes tracées avec ce  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Obtient un cap personnalisé à utiliser au début des lignes tracées avec ce  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Obtient le style de cap utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce  Pen .

**Returns:**
int - L'une des valeurs  DashCap  qui représente le style de capuchon utilisé au début et à la fin des tirets qui composent les lignes en pointillés dessinées avec ce  Pen .
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Obtient la distance du début d'une ligne au commencement d'un motif de tirets.

**Returns:**
float - La distance du début d'une ligne au commencement d'un motif de tirets.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Obtient un tableau de tirets et d'espaces personnalisés.

**Returns:**
float[] - Un tableau de nombres réels qui spécifie les longueurs des tirets et espaces alternés dans les lignes en pointillés.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Obtient le style utilisé pour les lignes pointillées tracées avec ce  Pen .

**Returns:**
int - Un  DashStyle  qui représente le style utilisé pour les lignes en pointillés dessinées avec ce  Pen .
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Obtient le style de cap utilisé à la fin des lignes tracées avec ce  Pen .

**Returns:**
int - L'une des valeurs  LineCap  qui représente le style de capuchon utilisé à la fin des lignes dessinées avec ce  Pen .
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Obtient le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce  Pen .

**Returns:**
int - Un  LineJoin  qui représente le style de jointure pour les extrémités de deux lignes consécutives dessinées avec ce  Pen .
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Obtient la limite de l'épaisseur de la jointure sur un coin en onglet.

**Returns:**
float - La limite de l'épaisseur de la jointure sur un coin en onglet.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtient l'opacité de l'objet. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que l'objet est entièrement visible, une valeur de 1 signifie que l'objet est entièrement opaque.

**Returns:**
float - La valeur d'opacité.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Obtient le style des lignes tracées avec ce  Pen .

**Returns:**
int - Une énumération  PenType  qui spécifie le style des lignes dessinées avec ce  Pen .
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Obtient le style de cap utilisé au début des lignes tracées avec ce  Pen .

**Returns:**
int - L'une des valeurs  LineCap  qui représente le style de capuchon utilisé au début des lignes dessinées avec ce  Pen .
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient une copie de la transformation géométrique de ce  Pen .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtient la largeur de ce  Pen , en unités de l'objet Graphics utilisé pour le dessin.

**Returns:**
float - La largeur de ce  Pen .
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


Multiplie la matrice de transformation de ce  Pen  par la  Matrix  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | L'objet  Matrix  par lequel multiplier la matrice de transformation. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie la matrice de transformation de ce  Pen  par la  Matrix  spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Le  Matrix  par lequel multiplier la matrice de transformation. |
| ordre | int | L'ordre dans lequel effectuer l'opération de multiplication. |

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


Réinitialise la matrice de transformation géométrique de ce  Pen  à l'identité.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Fait pivoter la transformation géométrique locale de l'angle spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| ordre | int | Un  MatrixOrder  qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Met à l'échelle la transformation géométrique locale des facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |
| ordre | int | Un  MatrixOrder  qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Définit l'alignement pour ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Un  PenAlignment  qui représente l'alignement pour ce  Pen . |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Définit le  Brush  qui détermine les attributs de ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Un  Brush  qui détermine les attributs de ce  Pen . |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Définit la couleur de ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Une structure  Color  qui représente la couleur de ce  Pen . |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée constituée de lignes parallèles et d'espaces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Un tableau de nombres réels qui spécifie le tableau composé. Les éléments du tableau doivent être en ordre croissant, ne pas être inférieurs à 0 et ne pas être supérieurs à 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Définit une coiffe personnalisée à utiliser à la fin des lignes tracées avec ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Un  CustomLineCap  qui représente le cap utilisé à la fin des lignes tracées avec ce  Pen . |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Définit une coiffe personnalisée à utiliser au début des lignes tracées avec ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Un  CustomLineCap  qui représente le cap utilisé au début des lignes tracées avec ce  Pen . |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Définit le style de coiffe utilisé à la fin des tirets qui composent les lignes pointillées tracées avec ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'une des valeurs de  DashCap  qui représente le style de cap utilisé au début et à la fin des tirets qui composent les lignes pointillées tracées avec ce  Pen . |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Définit la distance du début d'une ligne au commencement d'un motif de tirets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La distance du début d'une ligne au commencement d'un motif de tirets. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Définit un tableau de tirets et d'espaces personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Un tableau de nombres réels qui spécifie les longueurs des tirets et espaces alternés dans les lignes pointillées. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Définit le style utilisé pour les lignes pointillées tracées avec ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Un  DashStyle  qui représente le style utilisé pour les lignes pointillées tracées avec ce  Pen . |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Définit le style de coiffe utilisé à la fin des lignes tracées avec ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'une des valeurs de  LineCap  qui représente le style de cap utilisé à la fin des lignes tracées avec ce  Pen . |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Définit les valeurs qui déterminent le style de coiffe utilisé pour terminer les lignes tracées par ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int | Un  LineCap  qui représente le style de cap à utiliser au début des lignes tracées avec ce  Pen . |
| endCap | int | Un  LineCap  qui représente le style de cap à utiliser à la fin des lignes tracées avec ce  Pen . |
| dashCap | int | Un  LineCap  qui représente le style de cap à utiliser au début ou à la fin des lignes pointillées tracées avec ce  Pen . |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Un  LineJoin  qui représente le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce  Pen . |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Définit la limite de l'épaisseur de la jointure sur un coin en onglet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La limite de l'épaisseur de la jointure sur un coin en onglet. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Définit l'opacité de l'objet. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que l'objet est entièrement visible, une valeur de 1 signifie que l'objet est entièrement opaque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur d'opacité. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Définit le style de coiffe utilisé au début des lignes tracées avec ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'une des valeurs de  LineCap  qui représente le style de cap utilisé au début des lignes tracées avec ce  Pen . |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Définit une copie de la transformation géométrique pour ce  Pen .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Une copie de la  Matrix  qui représente la transformation géométrique pour ce  Pen . |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Définit la largeur de ce  Pen , en unités de l'objet Graphics utilisé pour le dessin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La largeur de ce  Pen . |

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


Effectue une translation de la transformation géométrique locale selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié.

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

