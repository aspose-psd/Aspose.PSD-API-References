---
title: Class Region
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Region classe. Décrit lintérieur dune forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.
type: docs
weight: 5360
url: /fr/net/aspose.psd/region/
---
## Region class

Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.

```csharp
public sealed class Region
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Region](region/#constructor)() | Initialise un nouveau`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | Initialise un nouveau`Region` avec le spécifié[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | Initialise un nouveau`Region` à partir du spécifié[`Rectangle`](../rectangle/)structure. |
| [Region](region/#constructor_3)(RectangleF) | Initialise un nouveau`Region` à partir du spécifié[`RectangleF`](../rectanglef/)structure. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Met à jour ceci`Region` pour contenir la partie du spécifié[`GraphicsPath`](../graphicspath/) qui ne se croise pas avec ça`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Met à jour ceci`Region` pour contenir la partie du spécifié[`Rectangle`](../rectangle/) structure qui ne se croise pas avec cette`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Met à jour ceci`Region` pour contenir la partie du spécifié[`RectangleF`](../rectanglef/) structure qui ne se croise pas avec cette`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Met à jour ceci`Region` pour contenir la partie du spécifié`Region` qui ne se croise pas avec ça`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Crée une copie profonde exacte de ceci`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Teste si le spécifié`Region` est identique à celui-ci`Region` sur la surface de dessin spécifiée. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Met à jour ceci`Region` ne contenir que la partie de son intérieur qui ne croise pas le spécifié[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Met à jour ceci`Region` ne contenir que la partie de son intérieur qui ne croise pas le spécifié[`Rectangle`](../rectangle/)structure. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Met à jour ceci`Region` ne contenir que la partie de son intérieur qui ne croise pas le spécifié[`RectangleF`](../rectanglef/)structure. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Met à jour ceci`Region` ne contenir que la partie de son intérieur qui ne croise pas le spécifié`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Met à jour ceci`Region` à l'intersection de lui-même avec le spécifié[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Met à jour ceci`Region` à l'intersection de lui-même avec le spécifié[`Rectangle`](../rectangle/)structure. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Met à jour ceci`Region` à l'intersection de lui-même avec le spécifié[`RectangleF`](../rectanglef/)structure. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Met à jour ceci`Region` à l'intersection de lui-même avec le spécifié`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Teste si cela`Region` a un intérieur vide sur la surface de dessin spécifiée. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Teste si cela`Region` a un intérieur infini sur la surface de dessin spécifiée. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Teste si le spécifié[`Point`](../point/) structure est contenue dans ce`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Teste si le spécifié[`PointF`](../pointf/) structure est contenue dans ce`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Teste si une partie de la valeur spécifiée[`Rectangle`](../rectangle/) structure est contenue dans ce`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Teste si une partie de la valeur spécifiée[`RectangleF`](../rectanglef/) structure est contenue dans ce`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Teste si le point spécifié est contenu dans ce`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Teste si le spécifié[`Point`](../point/) structure est contenue dans ce`Region` lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Teste si le spécifié[`PointF`](../pointf/) structure est contenue dans ce`Region` lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Teste si une partie de la valeur spécifiée[`Rectangle`](../rectangle/) structure est contenue dans ce`Region` lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Teste si une partie de la valeur spécifiée[`RectangleF`](../rectanglef/) structure est contenue dans ce`Region` lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Teste si le point spécifié est contenu dans ce`Region` lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Teste si le point spécifié est contenu dans ce`Region` objet lorsqu'il est dessiné à l'aide de l'objet spécifié[`Graphics`](../graphics/) objet. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Teste si une partie du rectangle spécifié est contenue dans ce`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Teste si une partie du rectangle spécifié est contenue dans ce`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Teste si une partie du rectangle spécifié est contenue dans ce`Region` lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Teste si une partie du rectangle spécifié est contenue dans ce`Region` lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Initialise ceci`Region` à un intérieur vide. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Initialise ceci`Region` objet à un intérieur infini. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Transforme ceci`Region` par le spécifié[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Décale les coordonnées de ce`Region`par le montant spécifié. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Décale les coordonnées de ce`Region`par le montant spécifié. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Met à jour ceci`Region` à l'union de lui-même et du spécifié[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Met à jour ceci`Region` à l'union de lui-même et du spécifié[`Rectangle`](../rectangle/)structure. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Met à jour ceci`Region` à l'union de lui-même et du spécifié[`RectangleF`](../rectanglef/)structure. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Met à jour ceci`Region` à l'union de lui-même et du spécifié`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Met à jour ceci`Region` à l'union moins l'intersection de lui-même avec le spécifié[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Met à jour ceci`Region` à l'union moins l'intersection de lui-même avec le spécifié[`Rectangle`](../rectangle/)structure. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Met à jour ceci`Region` à l'union moins l'intersection de lui-même avec le spécifié[`RectangleF`](../rectanglef/)structure. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Met à jour ceci`Region` à l'union moins l'intersection de lui-même avec le spécifié`Region` . |

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


