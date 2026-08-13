---
title: "Classe Matrix"
type: docs
weight: 3000
url: /fr/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Matrix()](#Matrix__1) | Initialise une nouvelle instance de la classe Matrix comme matrice identité. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Initialise une nouvelle instance de la classe [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Crée une copie de la classe [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Initialise une nouvelle instance de la classe [Matrix](/psd/python-net/aspose.psd/matrix/) selon la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Initialise une nouvelle instance de la classe [Matrix](/psd/python-net/aspose.psd/matrix/) selon la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Ce bit d'indicateur indique que la transformation définie par cet objet<br/>            effectue un retournement en miroir autour d'un axe qui transforme le<br/>            système de coordonnées normalement droit en un système gauche<br/>            en plus des conversions indiquées par les autres bits d'indicateur.<br/>            Un système de coordonnées droit est celui où l'axe X positif<br/>            tourne dans le sens antihoraire pour se superposer à l'axe Y positif<br/>            similaire à la direction dans laquelle les doigts de votre main droite<br/>            se courbent lorsque vous regardez votre pouce de face.<br/>            Un système de coordonnées gauche est celui où l'axe X positif<br/>            tourne dans le sens horaire pour se superposer à l'axe Y positif similaire<br/>            à la direction dans laquelle les doigts de votre main gauche se courbent.<br/>            Il n'existe aucune méthode mathématique pour déterminer l'angle de la<br/>            transformation de retournement ou de miroir d'origine, car tous les angles<br/>            de retournement sont identiques lorsqu'une rotation d'ajustement appropriée est appliquée.<br/>            NOTE : TypeFlip a été ajouté après que GENERAL_TRANSFORM était en circulation publique<br/>            et les bits d'indicateur ne pouvaient plus être renumérotés commodément<br/>            sans introduire une incompatibilité binaire dans le code externe. |
| TYPE_GENERAL_ROTATION [static] | int | r | Ce bit d'indicateur indique que la transformation définie par cet objet<br/>            effectue une rotation d'un angle arbitraire en plus des<br/>            conversions indiquées par les autres bits d'indicateur.<br/>            Une rotation modifie les angles des vecteurs du même montant<br/>            quel que soit le sens d'origine du vecteur et sans<br/>            changer la longueur du vecteur.<br/>            Ce bit d'indicateur est mutuellement exclusif avec le |
| TYPE_GENERAL_SCALE [static] | int | r | Une mise à l'échelle générale multiplie la longueur des vecteurs par des valeurs différentes<br/>            dans les directions x et y sans changer l'angle<br/>            entre les vecteurs perpendiculaires.<br/>            Ce bit d'indicateur est mutuellement exclusif avec le drapeau TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Cette constante indique que la transformation définie par cet objet<br/>            effectue une conversion arbitraire des coordonnées d'entrée.<br/>            Si cette transformation peut être classée par l'une des constantes ci‑dessus,<br/>            le type sera soit la constante TypeIdentity soit une<br/>            combinaison des bits d'indicateur appropriés pour les diverses conversions de coordonnées<br/>            que cette transformation effectue. |
| TYPE_IDENTITY [static] | int | r | Une transformation d'identité est celle dans laquelle les coordonnées de sortie sont<br/>            toujours les mêmes que les coordonnées d'entrée.<br/>            Si cette transformation n'est pas la transformation d'identité,<br/>            le type sera soit la constante GENERAL_TRANSFORM soit une<br/>            combinaison des bits d'indicateur appropriés pour les diverses conversions de coordonnées<br/>            que cette transformation effectue. |
| TYPE_MASK_ROTATION [static] | int | r | Cette constante est un masque de bits pour n'importe quel des bits d'indicateur de rotation. |
| TYPE_MASK_SCALE [static] | int | r | Cette constante est un masque de bits pour n'importe quel des bits d'indicateur d'échelle. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Ce bit d'indicateur indique que la transformation définie par cet objet<br/>            effectue une rotation de quadrant par un multiple de 90 degrés en<br/>            plus des conversions indiquées par les autres bits d'indicateur.<br/>            Une rotation modifie les angles des vecteurs du même montant<br/>            quel que soit le sens d'origine du vecteur et sans<br/>            changer la longueur du vecteur.<br/>            Ce bit d'indicateur est mutuellement exclusif avec le drapeau TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | Une translation déplace les coordonnées d'une quantité constante en x<br/>            et y sans changer la longueur ou l'angle des vecteurs. |
| TYPE_UNIFORM_SCALE [static] | int | r | Une échelle uniforme multiplie la longueur des vecteurs par la même quantité<br/>            dans les directions x et y sans changer l'angle entre<br/>            les vecteurs.<br/>            Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeGeneralScale. |
| elements | float | r | Obtient un tableau de valeurs à virgule flottante qui représente les éléments de cette [Matrix](/psd/python-net/aspose.psd/matrix/). |
| m11 | float | r | Obtient l'élément de matrice à la première ligne première colonne. Représente l'échelle le long de l'axe X. |
| m12 | float | r | Obtient l'élément de matrice à la première ligne deuxième colonne. Représente le cisaillement le long de l'axe Y. |
| m21 | float | r | Obtient l'élément de matrice à la deuxième ligne première colonne. Représente le cisaillement le long de l'axe X. |
| m22 | float | r | Obtient l'élément de matrice à la deuxième ligne deuxième colonne. Représente l'échelle le long de l'axe Y. |
| m31 | float | r | Obtient l'élément de matrice à la troisième ligne première colonne. Représente la translation le long de l'axe X. |
| m32 | float | r | Obtient l'élément de matrice à la troisième ligne première colonne. Représente la translation le long de l'axe Y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_elements()](#get_elements__1) | Obtient une copie des éléments de la matrice. |
| [multiply(tx)](#multiply_tx_2) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend. |
| [multiply(tx, order)](#multiply_tx_order_3) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order. |
| reset() | Réinitialise cette Matrix pour qu'elle contienne les éléments de la matrice identité. |
| [rotate(angle)](#rotate_angle_4) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre par défaut (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_5) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre spécifié. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre par défaut (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette [Matrix](/psd/python-net/aspose.psd/matrix/) en utilisant l'ordre spécifié. |
| [scale(sx, sy)](#scale_sx_sy_9) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre (par défaut) Prepend. |
| [transform_points(points)](#transform_points_points_10) | Applique la transformation géométrique représentée par cette [Matrix](/psd/python-net/aspose.psd/matrix/) à un tableau de points spécifié. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Applique le vecteur de translation spécifié à cette Matrice dans l'ordre spécifié. |
| [translate(tx, ty)](#translate_tx_ty_12) | Applique le vecteur de translation spécifié à cette [Matrix](/psd/python-net/aspose.psd/matrix/) en utilisant l'ordre Prepend (par défaut). |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Initialise une nouvelle instance de la classe Matrix comme matrice identité.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initialise une nouvelle instance de la classe [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| m11 | float | m00     M11     Échelle X |
| m12 | float | m10     M12     Cisaillement Y |
| m21 | float | m01     M21     Cisaillement X |
| m22 | float | m11     M22     Échelle Y |
| m31 | float | m02     M31     Translation X |
| m32 | float | m12     M32     Translation Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Crée une copie de la classe [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Une matrice de base pour le coping |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Initialise une nouvelle instance de la classe [Matrix](/psd/python-net/aspose.psd/matrix/) selon la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle à transformer. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de trois structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Initialise une nouvelle instance de la classe [Matrix](/psd/python-net/aspose.psd/matrix/) selon la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle à transformer. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Un tableau de trois structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Obtient une copie des éléments de la matrice.

**Returns**

| Type | Description |
| :- | :- |
| float | Une copie des éléments de la matrice. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice avec laquelle multiplier. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Le tx. Le tx. Le tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre. L'ordre. L'ordre. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre par défaut (Prepend).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre de la matrice. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre par défaut (Prepend).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Le point. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Le point. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette [Matrix](/psd/python-net/aspose.psd/matrix/) en utilisant l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scale_x | float | L'échelle X. |
| scale_y | float | L'échelle Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Le sx. Le sx. Le sx. |
| sy | float | Le sy. Le sy. Le sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Applique la transformation géométrique représentée par cette [Matrix](/psd/python-net/aspose.psd/matrix/) à un tableau de points spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Les points. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Applique le vecteur de translation spécifié à cette Matrice dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| offset_x | float | Le décalage X. |
| offset_y | float | Le décalage Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Applique le vecteur de translation spécifié à cette [Matrix](/psd/python-net/aspose.psd/matrix/) en utilisant l'ordre Prepend (par défaut).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tx | float | Le tx. Le tx. Le tx. |
| ty | float | Le ty. Le ty. Le ty. |

