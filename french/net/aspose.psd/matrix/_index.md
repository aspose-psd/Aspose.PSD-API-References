---
title: "Class Matrix"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Matrix. Remplace la matrice GDI"
type: docs
weight: 5580
url: /fr/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

Remplace la matrice GDI+.

```csharp
public class Matrix
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Matrix](matrix/#constructor)() | Initialise une nouvelle instance de la classe Matrix comme matrice identité. |
| [Matrix](matrix/#constructor_1)(Matrix) | Crée une copie de la classe `Matrix`. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Initialise une nouvelle instance de la classe `Matrix` avec la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Initialise une nouvelle instance de la classe `Matrix` avec la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Initialise une nouvelle instance de la classe `Matrix`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Obtient un tableau de valeurs à virgule flottante qui représente les éléments de ce `Matrix`. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Obtient l'élément de la matrice à la première ligne, première colonne. Représente l'échelle le long de l'axe X. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Obtient l'élément de la matrice à la première ligne, deuxième colonne. Représente le cisaillement le long de l'axe Y. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Obtient l'élément de la matrice à la deuxième ligne, première colonne. Représente le cisaillement le long de l'axe X. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Obtient l'élément de la matrice à la deuxième ligne, deuxième colonne. Représente l'échelle le long de l'axe Y. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Obtient l'élément de la matrice à la troisième ligne, première colonne. Représente la translation le long de l'axe X. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Obtient l'élément de la matrice à la troisième ligne, première colonne. Représente la translation le long de l'axe Y. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Détermine si l'Objet spécifié est égal à cette instance. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Obtient la copie des éléments de la matrice. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order. |
| [Reset](../../aspose.psd/matrix/reset/)() | Réinitialise cette Matrix pour qu'elle contienne les éléments de la matrice identité. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre par défaut (Prepend). |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre spécifié. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre par défaut (Prepend). |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre (par défaut) Prepend. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à ce `Matrix` en utilisant l'ordre spécifié. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Renvoie une chaîne qui représente cette instance. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Applique la transformation géométrique représentée par ce `Matrix` à un tableau de points spécifié. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Applique le vecteur de translation spécifié à ce `Matrix` en utilisant l'ordre (par défaut) Prepend. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Applique le vecteur de translation spécifié à cette Matrix dans l'ordre spécifié. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Détermine si deux matrices sont égales. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Ce bit de drapeau indique que la transformation définie par cet objet effectue un retournement en miroir autour d'un axe qui transforme le système de coordonnées normalement droitier en un système gaucher, en plus des conversions indiquées par les autres bits de drapeau. Un système de coordonnées droitier est celui où l'axe X positif tourne dans le sens antihoraire pour se superposer à l'axe Y positif, similaire à la direction dans laquelle les doigts de votre main droite se courbent lorsque vous regardez votre pouce de face. Un système de coordonnées gaucher est celui où l'axe X positif tourne dans le sens horaire pour se superposer à l'axe Y positif, similaire à la direction dans laquelle les doigts de votre main gauche se courbent. Il n'existe aucun moyen mathématique de déterminer l'angle du retournement ou de la transformation en miroir d'origine, puisque tous les angles de retournement sont identiques lorsqu'une rotation d'ajustement appropriée est appliquée. NOTE : TypeFlip a été ajouté après que GENERAL_TRANSFORM était en circulation publique et les bits de drapeau ne pouvaient plus être renumérotés commodément sans introduire une incompatibilité binaire dans le code externe. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Ce bit de drapeau indique que la transformation définie par cet objet effectue une rotation d'un angle arbitraire en plus des conversions indiquées par les autres bits de drapeau. Une rotation modifie les angles des vecteurs du même montant, quel que soit le sens d'origine du vecteur, et sans changer la longueur du vecteur. Ce bit de drapeau est mutuellement exclusif avec le |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Une échelle générale multiplie la longueur des vecteurs par des valeurs différentes dans les directions x et y sans changer l'angle entre les vecteurs perpendiculaires. Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Cette constante indique que la transformation définie par cet objet effectue une conversion arbitraire des coordonnées d'entrée. Si cette transformation peut être classée par l'une des constantes ci‑dessus, le type sera soit la constante TypeIdentity, soit une combinaison des bits de drapeau appropriés pour les différentes conversions de coordonnées que cette transformation effectue. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Une transformation identité est celle dans laquelle les coordonnées de sortie sont toujours identiques aux coordonnées d'entrée. Si cette transformation n'est pas la transformation identité, le type sera soit la constante GENERAL_TRANSFORM, soit une combinaison des bits de drapeau appropriés pour les différentes conversions de coordonnées que cette transformation effectue. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Cette constante est un masque de bits pour n'importe lequel des bits de drapeau de rotation. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Cette constante est un masque de bits pour n'importe lequel des bits de drapeau d'échelle. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Ce bit de drapeau indique que la transformation définie par cet objet effectue une rotation quadrante d'un multiple de 90 degrés en plus des conversions indiquées par les autres bits de drapeau. Une rotation change les angles des vecteurs de la même quantité, quel que soit le sens initial du vecteur, et sans modifier la longueur du vecteur. Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Une translation déplace les coordonnées d'une quantité constante en x et y sans modifier la longueur ou l'angle des vecteurs. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Une mise à l'échelle uniforme multiplie la longueur des vecteurs par la même quantité dans les directions x et y sans changer l'angle entre les vecteurs. Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeGeneralScale. |

## Remarques

La plupart des algorithmes proviennent de AffineTransform.java de Sun. Noms Java des éléments de matrice utilisés en interne. Carte des noms Java vers ceux .net avec description : m00 M11 Échelle X m10 M12 Cisaillement Y m01 M21 Cisaillement X m11 M22 Échelle Y m02 M31 Translation X m12 M32 Translation Y

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


