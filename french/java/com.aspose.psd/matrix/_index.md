---
title: "Matrix"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Remplace la Matrix GDI."
type: docs
weight: 69
url: /fr/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Remplace la matrice GDI+.

La plupart des algorithmes proviennent de AffineTransform.java de Sun. Noms Java des éléments de matrice utilisés en interne. Correspondance des noms Java aux noms .net avec description : m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Matrix()](#Matrix--) | Initialise une nouvelle instance de la classe Matrix en tant que matrice identité. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initialise une nouvelle instance de la classe Matrix. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Crée une copie de la classe Matrix. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Initialise une nouvelle instance de la classe Aspose.Imaging.Matrix avec la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Initialise une nouvelle instance de la classe Aspose.Imaging.Matrix avec la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
## Champs

| Champ | Description |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue un retournement en miroir autour d'un axe, ce qui transforme le système de coordonnées normalement droit en un système gauche, en plus des conversions indiquées par les autres bits d'indicateur. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue une rotation d'un angle arbitraire, en plus des conversions indiquées par les autres bits d'indicateur. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Une mise à l'échelle générale multiplie la longueur des vecteurs par des valeurs différentes selon les directions x et y sans modifier l'angle entre les vecteurs perpendiculaires. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Cette constante indique que la transformation définie par cet objet effectue une conversion arbitraire des coordonnées d'entrée. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Une transformation identité est celle où les coordonnées de sortie sont toujours identiques aux coordonnées d'entrée. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Cette constante est un masque de bits pour n'importe quel bit d'indicateur de rotation. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Cette constante est un masque de bits pour n'importe quel bit d'indicateur d'échelle. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue une rotation de quadrant d'un multiple de 90 degrés, en plus des conversions indiquées par les autres bits d'indicateur. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Une translation déplace les coordonnées d'une quantité constante en x et y sans modifier la longueur ou l'angle des vecteurs. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Une mise à l'échelle uniforme multiplie la longueur des vecteurs par la même valeur dans les directions x et y sans changer l'angle entre les vecteurs. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet  System.Object  spécifié est égal à cette instance. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Obtient une copie des éléments de la matrice. |
| [getM11()](#getM11--) | Obtient l'élément de la matrice à la première ligne, première colonne. |
| [getM12()](#getM12--) | Obtient l'élément de la matrice à la première ligne, deuxième colonne. |
| [getM21()](#getM21--) | Obtient l'élément de la matrice à la deuxième ligne, première colonne. |
| [getM22()](#getM22--) | Obtient l'élément de la matrice à la deuxième ligne, deuxième colonne. |
| [getM31()](#getM31--) | Obtient l'élément de la matrice à la troisième ligne, première colonne. |
| [getM32()](#getM32--) | Obtient l'élément de la matrice à la troisième ligne, première colonne. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Détermine si deux matrices sont égales. |
| [isIdentity()](#isIdentity--) | Renvoie `true` si ce `AffineTransform` est une transformation identité. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre indiqué par le paramètre order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Réinitialise cette Matrix pour qu'elle contienne les éléments de la matrice identité. |
| [rotate(float angle)](#rotate-float-) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre par défaut (Prepend). |
| [rotate(float angle, int order)](#rotate-float-int-) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre spécifié. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre par défaut (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié. |
| [scale(float sx, float sy)](#scale-float-float-) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre (par défaut) Prepend. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre spécifié. |
| [toString()](#toString--) | Retourne une  System.String  qui représente cette instance. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Applique la transformation géométrique représentée par cette Matrix à un tableau de points spécifié. |
| [translate(float tx, float ty)](#translate-float-float-) | Applique le vecteur de translation spécifié à cette Matrix en utilisant l'ordre (par défaut) Prepend. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Applique le vecteur de translation spécifié à cette Matrix dans l'ordre spécifié. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialise une nouvelle instance de la classe Matrix en tant que matrice identité.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initialise une nouvelle instance de la classe Matrix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m11 | float | m00 M11 Échelle X |
| m12 | float | m10 M12 Cisaillement Y |
| m21 | float | m01 M21 Cisaillement X |
| m22 | float | m11 M22 Échelle Y |
| m31 | float | m02 M31 Translation X |
| m32 | float | m12 M32 Translation Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Crée une copie de la classe Matrix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | la matrice de base pour le recouvrement |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialise une nouvelle instance de la classe Aspose.Imaging.Matrix avec la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Une structure  Aspose.Imaging.RectangleF  qui représente le rectangle à transformer. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Un tableau de trois  Aspose.Imaging.PointF  structures qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialise une nouvelle instance de la classe Aspose.Imaging.Matrix avec la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Une structure  Aspose.Imaging.Rectangle  qui représente le rectangle à transformer. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Un tableau de trois  Aspose.Imaging.Point  structures qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Ce bit d'indicateur signale que la transformation définie par cet objet effectue un retournement en miroir autour d'un axe, ce qui transforme le système de coordonnées normalement droitier en un système gaucher, en plus des conversions indiquées par les autres bits d'indicateur. Un système de coordonnées droitier est celui où l'axe X positif tourne dans le sens antihoraire pour se superposer à l'axe Y positif, similaire à la direction dans laquelle les doigts de votre main droite se courbent lorsque vous regardez votre pouce de face. Un système de coordonnées gaucher est celui où l'axe X positif tourne dans le sens horaire pour se superposer à l'axe Y positif, similaire à la direction dans laquelle les doigts de votre main gauche se courbent. Il n'existe aucun moyen mathématique de déterminer l'angle du retournement ou du miroir d'origine, puisque tous les angles de retournement sont identiques lorsqu'une rotation d'ajustement appropriée est appliquée. NOTE : TypeFlip a été ajouté après que GENERAL\_TRANSFORM était en circulation publique et les bits d'indicateur ne pouvaient plus être renumérotés commodément sans introduire une incompatibilité binaire dans le code externe.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Ce bit d'indicateur signale que la transformation définie par cet objet effectue une rotation d'un angle arbitraire en plus des conversions indiquées par les autres bits d'indicateur. Une rotation modifie les angles des vecteurs du même montant, quel que soit le sens d'origine du vecteur, et sans changer la longueur du vecteur. Ce bit d'indicateur est mutuellement exclusif avec le

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Une échelle générale multiplie la longueur des vecteurs par des valeurs différentes selon les directions x et y sans changer l'angle entre des vecteurs perpendiculaires. Ce bit d'indicateur est mutuellement exclusif avec le drapeau TypeUniformScale.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Cette constante indique que la transformation définie par cet objet effectue une conversion arbitraire des coordonnées d'entrée. Si cette transformation peut être classée par l'une des constantes ci‑above, le type sera soit la constante TypeIdentity, soit une combinaison des bits d'indicateur appropriés pour les diverses conversions de coordonnées que cette transformation effectue.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Une transformation identité est celle où les coordonnées de sortie sont toujours identiques aux coordonnées d'entrée. Si cette transformation n'est pas la transformation identité, le type sera soit la constante GENERAL\_TRANSFORM, soit une combinaison des bits d'indicateur appropriés pour les diverses conversions de coordonnées que cette transformation effectue.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Cette constante est un masque de bits pour n'importe quel bit d'indicateur de rotation.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Cette constante est un masque de bits pour n'importe quel bit d'indicateur d'échelle.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Ce bit d'indicateur signale que la transformation définie par cet objet effectue une rotation de quadrant d'un multiple de 90 degrés en plus des conversions indiquées par les autres bits d'indicateur. Une rotation modifie les angles des vecteurs du même montant, quel que soit le sens d'origine du vecteur, et sans changer la longueur du vecteur. Ce bit d'indicateur est mutuellement exclusif avec le drapeau TypeGeneralRotation.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Une translation déplace les coordonnées d'une quantité constante en x et y sans modifier la longueur ou l'angle des vecteurs.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Une échelle uniforme multiplie la longueur des vecteurs par la même valeur dans les directions x et y sans changer l'angle entre les vecteurs. Ce bit d'indicateur est mutuellement exclusif avec le drapeau TypeGeneralScale.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet  System.Object  spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à comparer avec cette instance. |

**Returns:**
booléen -  true  si le  System.Object  spécifié est égal à cette instance ; sinon,  false .
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


Obtient une copie des éléments de la matrice.

**Returns:**
float[] - Une copie des éléments de la matrice.
### getM11() {#getM11--}
```
public float getM11()
```


Obtient l'élément de matrice à la première ligne, première colonne. Représente l'échelle le long de l'axe X.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Obtient l'élément de matrice à la première ligne, deuxième colonne. Représente le cisaillement le long de l'axe Y.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Obtient l'élément de la matrice à la deuxième ligne première colonne. Représente le cisaillement le long de l'axe X.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Obtient l'élément de la matrice à la deuxième ligne deuxième colonne. Représente l'échelle le long de l'axe Y.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Obtient l'élément de la matrice à la troisième ligne première colonne. Représente la translation le long de l'axe X.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Obtient l'élément de la matrice à la troisième ligne première colonne. Représente la translation le long de l'axe Y.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Détermine si deux matrices sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | La première matrice à comparer. |
| b | [Matrix](../../com.aspose.psd/matrix) | La deuxième matrice à comparer. |

**Returns:**
booléen - Vrai si les matrices sont égales.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Renvoie `true` si ce `AffineTransform` est une transformation identité.

**Returns:**
booléen - `true` si cet `AffineTransform` est une transformation identité ; `false` sinon.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | La matrice avec laquelle multiplier. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre indiqué par le paramètre order.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Le tx. Le tx. Le tx. |
| ordre | int | L'ordre. L'ordre. L'ordre. |

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


Réinitialise cette Matrix pour qu'elle contienne les éléments de la matrice identité.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre par défaut (Prepend).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| ordre | int | L'ordre de la matrice. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre par défaut (Prepend).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle. |
| point | [PointF](../../com.aspose.psd/pointf) | Le point. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle. |
| point | [PointF](../../com.aspose.psd/pointf) | Le point. |
| ordre | int | L'ordre. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le sx. Le sx. Le sx. |
| sy | float | Le sy. Le sy. Le sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | float | L'échelle X. |
| scaleY | float | L'échelle Y. |
| ordre | int | L'ordre. |

### toString() {#toString--}
```
public String toString()
```


Retourne une  System.String  qui représente cette instance.

**Returns:**
java.lang.String - Une System.String qui représente cette instance.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Applique la transformation géométrique représentée par cette Matrix à un tableau de points spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Les points. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Applique le vecteur de translation spécifié à cette Matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tx | float | Le tx. Le tx. Le tx. |
| ty | float | Le ty. Le ty. Le ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Applique le vecteur de translation spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| offsetX | float | Le décalage X. |
| offsetY | float | Le décalage Y. |
| ordre | int | L'ordre. |

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

