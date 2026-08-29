---
title: "Classe Region"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Region. Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée."
type: docs
weight: 5860
url: /fr/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

Décrit l’intérieur d’une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.

```csharp
public sealed class Region
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Region](region/#constructor)() | Initialise un nouveau `Region`. |
| [Region](region/#constructor_1)(GraphicsPath) | Initialise un nouveau `Region` avec le [`GraphicsPath`](../graphicspath/) spécifié. |
| [Region](region/#constructor_2)(Rectangle) | Initialise un nouveau `Region` à partir de la structure [`Rectangle`](../rectangle/) spécifiée. |
| [Region](region/#constructor_3)(RectangleF) | Initialise une nouvelle `Region` à partir de la structure [`RectangleF`](../rectanglef/) spécifiée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Met à jour cette `Region` pour contenir la partie du [`GraphicsPath`](../graphicspath/) spécifié qui n’intersecte pas cette `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Met à jour cette `Region` pour contenir la partie de la structure [`Rectangle`](../rectangle/) spécifiée qui n’intersecte pas cette `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Met à jour cette `Region` pour contenir la partie de la structure [`RectangleF`](../rectanglef/) spécifiée qui n’intersecte pas cette `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Met à jour cette `Region` pour contenir la partie de la `Region` spécifiée qui n’intersecte pas cette `Region`. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Crée une copie profonde exacte de cette `Region`. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | Vérifie si les objets sont égaux. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Teste si la `Region` spécifiée est identique à cette `Region` sur la surface de dessin spécifiée. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Met à jour cette `Region` pour ne contenir que la partie de son intérieur qui n’intersecte pas le [`GraphicsPath`](../graphicspath/) spécifié. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Met à jour cette `Region` pour ne contenir que la partie de son intérieur qui n’intersecte pas la structure [`Rectangle`](../rectangle/) spécifiée. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Met à jour cette `Region` pour ne contenir que la partie de son intérieur qui n’intersecte pas la structure [`RectangleF`](../rectanglef/) spécifiée. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Met à jour cette `Region` pour ne contenir que la partie de son intérieur qui n’intersecte pas la `Region` spécifiée. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | Obtient le code de hachage de l'objet actuel. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Met à jour cette `Region` à l’intersection d’elle‑même avec le [`GraphicsPath`](../graphicspath/) spécifié. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Met à jour cette `Region` à l’intersection d’elle‑même avec la structure [`Rectangle`](../rectangle/) spécifiée. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Met à jour cette `Region` à l’intersection d’elle‑même avec la structure [`RectangleF`](../rectanglef/) spécifiée. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Met à jour cette `Region` à l’intersection d’elle‑même avec la `Region` spécifiée. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Teste si cette `Region` a un intérieur vide sur la surface de dessin spécifiée. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Teste si cette `Region` a un intérieur infini sur la surface de dessin spécifiée. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Teste si la structure [`Point`](../point/) spécifiée est contenue dans cette `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Teste si la structure [`PointF`](../pointf/) spécifiée est contenue dans cette `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Teste si une partie de la structure [`Rectangle`](../rectangle/) spécifiée est contenue dans cette `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Teste si une partie de la structure [`RectangleF`](../rectanglef/) spécifiée est contenue dans cette `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Teste si le point spécifié est contenu dans cette `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Teste si la structure [`Point`](../point/) spécifiée est contenue dans cette `Region` lorsqu’elle est dessinée avec le [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Teste si la structure [`PointF`](../pointf/) spécifiée est contenue dans cette `Region` lorsqu’elle est dessinée avec le [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Teste si une partie de la structure [`Rectangle`](../rectangle/) spécifiée est contenue dans cette `Region` lorsqu’elle est dessinée avec le [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Teste si une partie quelconque de la structure [`RectangleF`](../rectanglef/) spécifiée est contenue dans cette `Region` lorsqu'elle est dessinée à l'aide du [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Teste si le point spécifié est contenu dans cette `Region` lorsqu'elle est dessinée à l'aide du [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Teste si le point spécifié est contenu dans cet objet `Region` lorsqu'il est dessiné à l'aide de l'objet [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Teste si une partie quelconque du rectangle spécifié est contenue dans cette `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Teste si une partie quelconque du rectangle spécifié est contenue dans cette `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Teste si une partie quelconque du rectangle spécifié est contenue dans cette `Region` lorsqu'elle est dessinée à l'aide du [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Teste si une partie quelconque du rectangle spécifié est contenue dans cette `Region` lorsqu'elle est dessinée à l'aide du [`Graphics`](../graphics/) spécifié. |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Initialise cette `Region` avec un intérieur vide. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Initialise cet objet `Region` avec un intérieur infini. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Transforme cette `Region` à l'aide de la [`Matrix`](../matrix/) spécifiée. |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Décale les coordonnées de cette `Region` du montant spécifié. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Décale les coordonnées de cette `Region` du montant spécifié. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Met à jour cette `Region` pour qu'elle soit l'union d'elle-même et du [`GraphicsPath`](../graphicspath/) spécifié. |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Met à jour cette `Region` pour qu'elle soit l'union d'elle-même et de la structure [`Rectangle`](../rectangle/) spécifiée. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Met à jour cette `Region` pour qu'elle soit l'union d'elle-même et de la structure [`RectangleF`](../rectanglef/) spécifiée. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Met à jour cette `Region` pour qu'elle soit l'union d'elle-même et de la `Region` spécifiée. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Met à jour cette `Region` pour qu'elle soit l'union moins l'intersection d'elle-même avec le [`GraphicsPath`](../graphicspath/) spécifié. |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Met à jour cette `Region` pour qu'elle soit l'union moins l'intersection d'elle-même avec la structure [`Rectangle`](../rectangle/) spécifiée. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Met à jour cette `Region` pour qu'elle soit l'union moins l'intersection d'elle-même avec la structure [`RectangleF`](../rectanglef/) spécifiée. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Met à jour cette `Region` pour qu'elle soit l'union moins l'intersection d'elle-même avec la `Region` spécifiée. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


