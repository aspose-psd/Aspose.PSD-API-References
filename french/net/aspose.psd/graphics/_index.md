---
title: "Class Graphics"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.Graphics class. Représente les graphiques selon le moteur graphique utilisé dans l'assembly actuel."
type: docs
weight: 4780
url: /fr/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Représente les graphiques selon le moteur graphique utilisé dans l'assembly actuel.

```csharp
public sealed class Graphics
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Graphics](graphics/)(Image) | Initialise une nouvelle instance de la classe `Graphics`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Obtient ou définit la région de découpage. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Obtient ou définit la qualité de composition. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Obtient la résolution horizontale de cet Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Obtient la résolution verticale de cet Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Obtient l'image. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Obtient ou définit le mode d'interpolation. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Obtient une valeur indiquant si les graphiques sont dans l'état d'appel BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Obtient ou définit l'échelle entre les unités du monde et les unités de page pour cet Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans cet Aspose.PSD.Graphics. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Obtient ou définit les options d'image, utilisées pour créer des images vectorielles peintables à dessiner. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Obtient ou définit le mode d'anticrénelage. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Obtient ou définit l'indice de rendu du texte. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Obtient ou définit une copie de la transformation géométrique du monde pour ce `Graphics`. |

## Méthodes

| Nom | Description |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Démarre la mise en cache des opérations graphiques suivantes. Les effets graphiques appliqués ensuite ne seront pas appliqués immédiatement ; à la place, l'EndUpdate provoquera l'application de tous les effets en une fois. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Efface la surface graphique en utilisant la couleur spécifiée. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [`Rectangle`](../rectangle/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [`RectangleF`](../rectanglef/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Dessine une spline de Bézier définie par quatre structures [`Point`](../point/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Dessine une spline de Bézier définie par quatre structures [`PointF`](../pointf/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Dessine une série de splines de Bézier à partir d'un tableau de structures [`PointF`](../pointf/). |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Dessine une série de splines de Bézier à partir d'un tableau de structures [`Point`](../point/). |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Dessine une spline cardinal fermée définie par un tableau de structures [`PointF`](../pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage Alternatif. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Dessine une spline cardinal fermée définie par un tableau de structures [`Point`](../point/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage Alternatif. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Dessine une spline cardinal fermée définie par un tableau de structures [`PointF`](../pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage Alternatif par défaut. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Dessine une spline cardinal fermée définie par un tableau de structures [`Point`](../point/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage Alternatif par défaut. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Dessine une spline cardinal à travers un tableau spécifié de structures [`PointF`](../pointf/). Cette méthode utilise une tension par défaut de 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Dessine une spline cardinal à travers un tableau spécifié de structures [`Point`](../point/). |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Dessine une spline cardinal à travers un tableau spécifié de structures [`PointF`](../pointf/) en utilisant une tension spécifiée. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Dessine une spline cardinal à travers un tableau spécifié de structures [`Point`](../point/) en utilisant une tension spécifiée. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Dessine une spline cardinal à travers un tableau spécifié de structures [`PointF`](../pointf/). Le dessin commence avec un décalage par rapport au début du tableau. Cette méthode utilise une tension par défaut de 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Dessine une spline cardinal à travers un tableau spécifié de structures [`PointF`](../pointf/) en utilisant une tension spécifiée. Le dessin commence avec un décalage par rapport au début du tableau. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Dessine une spline cardinal à travers un tableau spécifié de structures [`Point`](../point/) en utilisant une tension spécifiée. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Dessine une ellipse spécifiée par une structure de [`Rectangle`](../rectangle/) englobante. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Dessine une ellipse définie par un [`RectangleF`](../rectanglef/) englobant. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Dessine l'[`Image`](./image/) spécifiée, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Dessine l'[`Image`](./image/) spécifiée, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Dessine l'[`Image`](./image/) spécifiée, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Dessine l'image spécifiée, en utilisant sa taille physique originale, à l'emplacement spécifié par une paire de coordonnées. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Dessine la partie spécifiée de l'*image* spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Dessine l'[`Image`](./image/) spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Dessine l'image spécifiée en utilisant sa taille physique originale à l'emplacement spécifié par une paire de coordonnées. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour l'adapter au rectangle spécifié. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Dessine une ligne reliant deux structures [`Point`](../point/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Dessine une ligne reliant deux structures [`PointF`](../pointf/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Dessine une série de segments de ligne qui relient un tableau de structures [`PointF`](../pointf/). |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Dessine une série de segments de ligne qui relient un tableau de structures [`Point`](../point/). |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Dessine un [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [`Rectangle`](../rectangle/) et deux lignes radiales. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [`RectangleF`](../rectanglef/) et deux lignes radiales. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Dessine un polygone défini par un tableau de structures [`PointF`](../pointf/). |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Dessine un polygone défini par un tableau de structures [`Point`](../point/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Dessine un rectangle spécifié par une structure [`Rectangle`](../rectangle/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Dessine un rectangle spécifié par une structure [`RectangleF`](../rectanglef/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Dessine une série de rectangles spécifiés par des structures [`RectangleF`](../rectanglef/). |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Dessine une série de rectangles spécifiés par des structures [`Rectangle`](../rectangle/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../brush/) et [`Font`](../font/) spécifiés. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [`Brush`](../brush/) et [`Font`](../font/) spécifiés. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../brush/) et [`Font`](../font/) spécifiés. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../brush/) et [`Font`](../font/) spécifiés en utilisant les attributs de formatage du [`StringFormat`](../stringformat/) spécifié. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [`Brush`](../brush/) et [`Font`](../font/) spécifiés en utilisant les attributs de formatage du [`StringFormat`](../stringformat/) spécifié. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../brush/) et [`Font`](../font/) spécifiés en utilisant les attributs de formatage du [`StringFormat`](../stringformat/) spécifié. |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Termine la mise en cache des opérations graphiques démarrées après l'appel de BeginUpdate. Les opérations graphiques précédentes seront appliquées d'un coup lors de l'appel de cette méthode. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [`PointF`](../pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage Alternatif. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [`Point`](../point/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage Alternatif. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [`PointF`](../pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [`Point`](../point/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [`PointF`](../pointf/) en utilisant le mode de remplissage et la tension spécifiés. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [`Point`](../point/) en utilisant le mode de remplissage et la tension spécifiés. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [`Rectangle`](../rectangle/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [`RectangleF`](../rectanglef/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Remplit l'intérieur d'un [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [`RectangleF`](../rectanglef/) et deux lignes radiales. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [`RectangleF`](../rectanglef/) et deux lignes radiales. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [`PointF`](../pointf/) et Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [`Point`](../point/) et Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [`PointF`](../pointf/) en utilisant le mode de remplissage spécifié. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [`Point`](../point/) en utilisant le mode de remplissage spécifié. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Remplit l'intérieur d'un rectangle spécifié par une structure [`Rectangle`](../rectangle/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Remplit l'intérieur d'un rectangle spécifié par une structure [`RectangleF`](../rectanglef/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Remplit l'intérieur d'une série de rectangles spécifiés par des structures [`RectangleF`](../rectanglef/). |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Remplit l'intérieur d'une série de rectangles spécifiés par des structures [`Rectangle`](../rectangle/). |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Remplit l'intérieur d'une [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Multiplie la [`Matrix`](../matrix/) qui représente la transformation géométrique locale de ce `Graphics` par la [`Matrix`](../matrix/) spécifiée en préfixant la [`Matrix`](../matrix/) spécifiée. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplie la [`Matrix`](../matrix/) qui représente la transformation géométrique locale de ce `Graphics` par la [`Matrix`](../matrix/) spécifiée dans l'ordre spécifié. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Réinitialise la propriété [`Transform`](./transform/) à l'identité. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Redimensionne la transformation géométrique locale des valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Redimensionne la transformation géométrique locale des valeurs spécifiées dans l'ordre indiqué. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Déplace la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |

## Exemples

Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface de l'Image. Pour démontrer l'opération, l'exemple crée une nouvelle Image au format PSD et dessine des formes primitives sur la surface de l'Image en utilisant les méthodes Draw exposées par la classe Graphics, puis l'exporte au format de fichier PSD.

```csharp
[C#]

//Créez une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez et initialisez une instance de la classe Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics.
    graphics.Clear(Color.Wheat);

    //Dessinez un arc en spécifiant l'objet Pen de couleur noire, 
    //un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Dessinez une courbe de Bézier en spécifiant l'objet Pen de couleur bleue et les points de coordonnées.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Dessinez une courbe en spécifiant l'objet Pen de couleur verte et un tableau de points
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Dessinez une ellipse en utilisant l'objet Pen et un rectangle entourant
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dessinez une ligne 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Dessinez un segment de secteur
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Dessinez un polygone en spécifiant l'objet Pen de couleur rouge et un tableau de points
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dessinez un rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Créez un objet SolidBrush et définissez ses différentes propriétés
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Dessinez une chaîne en utilisant l'objet SolidBrush et la police, à un point spécifique
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Créez une instance de PngOptions et définissez ses différentes propriétés
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Enregistrez toutes les modifications.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


