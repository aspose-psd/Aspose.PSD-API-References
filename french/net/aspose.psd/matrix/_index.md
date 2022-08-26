---
title: Matrix
second_title: Référence de l'API Aspose.PSD pour .NET
description: Remplace la matrice GDI.
type: docs
weight: 5020
url: /fr/net/aspose.psd/matrix/
---
## Matrix class

Remplace la matrice GDI+.

```csharp
public class Matrix
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Matrix](matrix#constructor)() | Initialise une nouvelle instance de la classe Matrix en tant que matrice d'identité. |
| [Matrix](matrix#constructor_1)(Matrix) | Effectue une copie du[`Matrix`](../matrix) classe. |
| [Matrix](matrix#constructor_2)(Rectangle, Point[]) | Initialise une nouvelle instance du[`Matrix`](../matrix) class à la transformation géométrique définie par le rectangle et le tableau de points spécifiés. |
| [Matrix](matrix#constructor_3)(RectangleF, PointF[]) | Initialise une nouvelle instance du[`Matrix`](../matrix) class à la transformation géométrique définie par le rectangle et le tableau de points spécifiés. |
| [Matrix](matrix#constructor_4)(float, float, float, float, float, float) | Initialise une nouvelle instance du[`Matrix`](../matrix) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements) { get; } | Obtient un tableau de valeurs à virgule flottante qui représente les éléments de ce[`Matrix`](../matrix) . |
| [M11](../../aspose.psd/matrix/m11) { get; } | Obtient l'élément de matrice à la première ligne de la première colonne. Représente l'échelle le long de l'axe X. |
| [M12](../../aspose.psd/matrix/m12) { get; } | Obtient l'élément de matrice à la première ligne de la deuxième colonne. Représente le cisaillement le long de l'axe Y. |
| [M21](../../aspose.psd/matrix/m21) { get; } | Obtient l'élément de matrice à la deuxième ligne, première colonne. Représente le cisaillement le long de l'axe X. |
| [M22](../../aspose.psd/matrix/m22) { get; } | Obtient l'élément de matrice à la deuxième ligne de la deuxième colonne. Représente l'échelle le long de l'axe Y. |
| [M31](../../aspose.psd/matrix/m31) { get; } | Obtient l'élément de matrice à la troisième ligne de la première colonne. Représente la translation le long de l'axe X. |
| [M32](../../aspose.psd/matrix/m32) { get; } | Obtient l'élément de matrice à la troisième ligne de la première colonne. Représente la translation le long de l'axe Y. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals)(object) | Détermine si la valeur spécifiéeObject est égal à cette instance. |
| [GetElements](../../aspose.psd/matrix/getelements)() | Obtient la copie des éléments de la matrice. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode)() | Renvoie un code de hachage pour cette instance. |
| [Multiply](../../aspose.psd/matrix/multiply#multiply)(Matrix) | Multiplie cette matrice par la matrice spécifiée dans le paramètre de matrice en utilisant (par défaut) l'ordre de préfixe. |
| [Multiply](../../aspose.psd/matrix/multiply#multiply_1)(Matrix, MatrixOrder) | Multiplie cette matrice par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order. |
| [Reset](../../aspose.psd/matrix/reset)() | Réinitialise cette matrice pour avoir les éléments de la matrice d'identité. |
| [Rotate](../../aspose.psd/matrix/rotate#rotate)(float) | Applique une rotation dans le sens des aiguilles d'une montre d'une quantité spécifiée dans le paramètre d'angle, autour de l'origine (zéro coordonnées x et y) pour cette matrice dans l'ordre par défaut (Prepend). |
| [Rotate](../../aspose.psd/matrix/rotate#rotate_1)(float, MatrixOrder) | Applique une rotation dans le sens des aiguilles d'une montre d'une quantité spécifiée dans le paramètre d'angle, autour de l'origine (zéro coordonnées x et y) pour cette matrice dans l'ordre spécifié. |
| [RotateAt](../../aspose.psd/matrix/rotateat#rotateat)(float, PointF) | Applique une rotation dans le sens des aiguilles d'une montre autour du point spécifié à cette matrice dans l'ordre par défaut (préfixe). |
| [RotateAt](../../aspose.psd/matrix/rotateat#rotateat_1)(float, PointF, MatrixOrder) | Applique une rotation dans le sens des aiguilles d'une montre autour du point spécifié à cette matrice dans l'ordre spécifié. |
| [Scale](../../aspose.psd/matrix/scale#scale)(float, float) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette matrice en utilisant (par défaut) l'ordre de préfixe. |
| [Scale](../../aspose.psd/matrix/scale#scale_1)(float, float, MatrixOrder) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à ce[`Matrix`](../matrix) en utilisant l'ordre spécifié. |
| override [ToString](../../aspose.psd/matrix/tostring)() | Renvoie unString qui représente cette instance. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints)(PointF[]) | Applique la transformation géométrique représentée par ce[`Matrix`](../matrix) à un tableau de points spécifié. |
| [Translate](../../aspose.psd/matrix/translate#translate)(float, float) | Applique le vecteur de translation spécifié à ce[`Matrix`](../matrix) en utilisant (par défaut) Préfixer la commande. |
| [Translate](../../aspose.psd/matrix/translate#translate_1)(float, float, MatrixOrder) | Applique le vecteur de translation spécifié à cette matrice dans l'ordre spécifié. |
| static [Equals](../../aspose.psd/matrix/equals)(Matrix, Matrix) | Détermine si deux matrices sont égales. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue un retournement d'image miroir autour d'un axe qui change le système de coordonnées normalement droitier en un système gaucher en plus des conversions indiquées par d'autres bits d'indicateur. Un système de coordonnées droitier est celui où l'axe X positif tourne dans le sens antihoraire pour recouvrir l'axe Y positif similaire à la direction dans laquelle les doigts de votre main droite s'enroulent lorsque vous regardez votre pouce. Un système de coordonnées pour gaucher est celui dans lequel l'axe X positif tourne dans le sens des aiguilles d'une montre pour superposer l'axe Y positif similaire à la direction dans laquelle les doigts de votre main gauche se courbent. Il n'y a aucun moyen mathématique de déterminer l'angle de la transformation de retournement ou de mise en miroir d'origine puisque tous les angles de retournement sont identiques avec une rotation de réglage appropriée. REMARQUE : TypeFlip a été ajouté après GENERAL_TRANSFORM était en circulation publique et les bits d'indicateur ne pouvaient plus être renumérotés commodément sans introduire une incompatibilité binaire dans le code outside . |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue une rotation d'un angle arbitraire en plus des conversions indiquées par d'autres bits d'indicateur. Une rotation modifie les angles des vecteurs de la même quantité quelle que soit la direction d'origine du vecteur et sans changer la longueur du vecteur. Ce bit d'indicateur est mutuellement exclusif avec the |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale) | Une échelle générale multiplie la longueur des vecteurs par différents montants dans les directions x et y sans modifier l'angle entre les vecteurs perpendiculaires. Ce bit d'indicateur est mutuellement exclusif avec l'indicateur TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform) | Cette constante indique que la transformation définie par cet objet effectue une conversion arbitraire des coordonnées d'entrée. Si cette transformation peut être classée par l'une des constantes ci-dessus, le type sera soit la constante TypeIdentity soit une combinaison de l'indicateur approprié bits pour les différentes conversions de coordonnées effectuées par cette transformation. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity) | Une transformation d'identité est une transformation dans laquelle les coordonnées de sortie sont toujours les mêmes que les coordonnées d'entrée. Si cette transformation est autre que la transformation d'identité, le type sera soit la constante GENERAL_TRANSFORM, soit une combinaison des bits d'indicateur appropriés pour les différentes conversions de coordonnées effectuées par cette transformation. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation) | Cette constante est un masque de bits pour l'un des bits de l'indicateur de rotation. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale) | Cette constante est un masque de bits pour l'un des bits d'indicateur d'échelle. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue une rotation de quadrant d'un certain multiple de 90 degrés en en plus des conversions indiquées par d'autres bits d'indicateur. Une rotation modifie les angles des vecteurs de la même quantité quelle que soit la direction d'origine du vecteur et sans modifier la longueur du vecteur. Ce bit d'indicateur est mutuellement exclusif avec l'indicateur TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation) | Une translation déplace les coordonnées d'une quantité constante en x et y sans changer la longueur ou l'angle des vecteurs. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale) | Une échelle uniforme multiplie la longueur des vecteurs par la même quantité dans les directions x et y sans modifier l'angle entre vecteurs. Ce bit d'indicateur est mutuellement exclusif avec l'indicateur TypeGeneralScale. |

### Remarques

La plupart des algorithmes tirés de AffineTransform.java de Sun. Noms Java pour les éléments de matrice utilisés en interne. Mappage des noms java vers ceux .net à la description : m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m02 M22 Scaled Y_x00d Traduire X m12 M32 Traduire Y

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
