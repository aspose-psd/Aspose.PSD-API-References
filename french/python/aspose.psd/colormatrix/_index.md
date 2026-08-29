---
title: "Classe ColorMatrix"
type: docs
weight: 770
url: /fr/python-net/aspose.psd/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorMatrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initialise une nouvelle instance de la classe [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initialise une nouvelle instance de la classe [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) en utilisant les éléments de la matrice spécifiée <paramref name="newColorMatrix" />. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Le nombre de dimensions de la matrice. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Le nombre d'éléments dans la dimension de la matrice. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Le nombre total d'éléments dans la matrice. |
| matrix00 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix01 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix02 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix03 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix04 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix10 | float | r/w | Obtient ou définit l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix11 | float | r/w | Obtient ou définit l'élément à la première ligne et à la première colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix12 | float | r/w | Obtient ou définit l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix13 | float | r/w | Obtient ou définit l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix14 | float | r/w | Obtient ou définit l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix20 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix21 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix22 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix23 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix24 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la quatrième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix30 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix31 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la première colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix32 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la deuxième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix33 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la troisième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix34 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la quatrième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix40 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix41 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et première colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix42 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et deuxième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix43 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et troisième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix44 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et quatrième colonne de ce [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_matrix()](#get_matrix__1) | Obtient les valeurs de la matrice. |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initialise une nouvelle instance de la classe [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/).

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initialise une nouvelle instance de la classe [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) en utilisant les éléments de la matrice spécifiée <paramref name="newColorMatrix" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | float[] | Les valeurs des éléments pour le nouveau [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |

### Method: get_matrix() {#get_matrix__1}


```
 get_matrix() 
```

Obtient les valeurs de la matrice.

**Returns**

| Type | Description |
| :- | :- |
| float[] | Le tableau des valeurs de la matrice. |


