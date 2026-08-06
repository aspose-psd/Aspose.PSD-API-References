---
title: "Graphics"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente les graphiques selon le moteur graphique utilisé dans l'assembly actuel."
type: docs
weight: 49
url: /fr/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Représente les graphiques selon le moteur graphique utilisé dans l'assembly actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Initialise une nouvelle instance de la classe Graphics. |
## Champs

| Champ | Description |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Obtient le coefficient de taille du style de texte gras |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Obtient le coefficient de taille du style de texte italique |
## Méthodes

| Méthode | Description |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Applique l'effet. |
| [beginUpdate()](#beginUpdate--) | Démarre la mise en cache des opérations graphiques suivantes. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Efface la surface graphique en utilisant la couleur spécifiée. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure RectangleF. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Dessine une spline de Bézier définie par quatre structures Point. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Dessine une spline de Bézier définie par quatre structures PointF. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dessine une série de splines de Bézier à partir d'un tableau de structures PointF. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dessine une série de splines de Bézier à partir d'un tableau de structures Point. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dessine une spline cardinal fermée définie par un tableau de structures PointF. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Dessine une spline cardinale fermée définie par un tableau de structures  PointF  en utilisant une tension spécifiée. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dessine une spline cardinale fermée définie par un tableau de structures  Point  . |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Dessine une spline cardinale fermée définie par un tableau de structures  Point  en utilisant une tension spécifiée. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dessine une spline cardinale à travers un tableau spécifié de structures  PointF . |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Dessine une spline cardinale à travers un tableau spécifié de structures  PointF  en utilisant une tension spécifiée. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Dessine une spline cardinale à travers un tableau spécifié de structures  PointF . |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Dessine une spline cardinale à travers un tableau spécifié de structures  PointF  en utilisant une tension spécifiée. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dessine une spline cardinale à travers un tableau spécifié de structures  Point . |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Dessine une spline cardinale à travers un tableau spécifié de structures  Point  en utilisant une tension spécifiée. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Dessine une spline cardinale à travers un tableau spécifié de structures  Point  en utilisant une tension spécifiée. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Dessine une ellipse spécifiée par une structure de  Rectangle  englobante. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Dessine une ellipse définie par un  RectangleF  englobant. |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Dessine l' Image  spécifiée , en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Dessine l' Image  spécifiée , en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Dessine l' Image  spécifiée , en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Dessine l'image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié par une paire de coordonnées. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Dessine l'image spécifiée en utilisant sa taille physique d'origine à l'emplacement spécifié par une paire de coordonnées. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour l'adapter au rectangle spécifié. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Dessine une ligne reliant deux structures  Point . |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Dessine une ligne reliant deux structures  PointF . |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dessine une série de segments de ligne qui relient un tableau de structures  PointF . |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dessine une série de segments de ligne qui relient un tableau de structures  Point . |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Dessine un  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure de  Rectangle  et deux lignes radiales. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure de  RectangleF  et deux lignes radiales. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Dessine un polygone défini par un tableau de structures  PointF . |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Dessine un polygone défini par un tableau de structures  Point . |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Dessine un rectangle spécifié par une structure  Rectangle . |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Dessine un rectangle spécifié par une structure  RectangleF . |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Dessine une série de rectangles spécifiés par des structures  RectangleF . |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Dessine une série de rectangles spécifiés par des structures  Rectangle . |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié. |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Dessine la chaîne de texte spécifiée de manière compatible Adobe dans le rectangle spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Dessine la chaîne de texte spécifiée de manière compatible Adobe à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés. |
| [endUpdate()](#endUpdate--) | Termine la mise en cache des opérations graphiques démarrées après l'appel de BeginUpdate. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.PointF . |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.PointF  en utilisant le mode de remplissage spécifié. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.PointF  en utilisant le mode de remplissage et la tension spécifiés. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.Point . |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.Point  en utilisant le mode de remplissage spécifié. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.Point  en utilisant le mode de remplissage et la tension spécifiés. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure  com.aspose.psd.Rectangle . |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure  com.aspose.psd.RectangleF . |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Remplit l'intérieur d'un  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une structure com.aspose.psd.RectangleF et deux lignes radiales. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une structure com.aspose.psd.RectangleF et deux lignes radiales. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.PointF et FillMode.Alternate. |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.PointF en utilisant le mode de remplissage spécifié. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.Point et FillMode.Alternate. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.Point en utilisant le mode de remplissage spécifié. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Remplit l'intérieur d'un rectangle spécifié par une structure Rectangle. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Remplit l'intérieur d'un rectangle spécifié par une structure RectangleF. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Remplit l'intérieur d'une série de rectangles spécifiés par des structures RectangleF. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Remplit l'intérieur d'une série de rectangles spécifiés par des structures Rectangle. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Remplit l'intérieur d'une com.aspose.psd.region. |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Obtient ou définit la région de découpage. |
| [getCompositingQuality()](#getCompositingQuality--) | Obtient ou définit la qualité de composition. |
| [getDpiX()](#getDpiX--) | Obtient la résolution horizontale de ce com.aspose.psd.graphics. |
| [getDpiY()](#getDpiY--) | Obtient la résolution verticale de ce com.aspose.psd.graphics. |
| [getImage()](#getImage--) | Obtient l'image. |
| [getInterpolationMode()](#getInterpolationMode--) | Obtient ou définit le mode d'interpolation. |
| [getPageScale()](#getPageScale--) | Obtient ou définit l'échelle entre les unités du monde et les unités de page pour ce com.aspose.psd.graphics. |
| [getPageUnit()](#getPageUnit--) | Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans ce com.aspose.psd.graphics. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Obtient ou définit les options d'image, utilisées pour créer des images vectorielles peintables à dessiner. |
| [getSmoothingMode()](#getSmoothingMode--) | Obtient ou définit le mode d'anticrénelage. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Obtient ou définit l'indice de rendu du texte. |
| [getTransform()](#getTransform--) | Obtient ou définit une copie de la transformation géométrique du monde pour ce com.aspose.psd.graphics. |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Obtient une valeur indiquant si le graphique est dans l'état d'appel BeginUpdate. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Mesure la chaîne en utilisant la classe [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Mesure la chaîne. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Mesure la chaîne de texte spécifiée avec les paramètres spécifiés |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplie le  com.aspose.psd.Matrix  qui représente la transformation géométrique locale de ce  com.aspose.psd.Graphics  par le  com.aspose.psd.Matrix  spécifié en préfixant le  com.aspose.psd.matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplie le  com.aspose.psd.Matrix  qui représente la transformation géométrique locale de ce  com.aspose.psd.Graphics  par le  com.aspose.psd.Matrix  spécifié dans l'ordre spécifié. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Réinitialise la propriété  com.aspose.psd.graphics.Transform  à l'identité. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre spécifié. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées dans l'ordre spécifié. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Obtient ou définit la région de découpage. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Obtient ou définit la qualité de composition. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Obtient ou définit le mode d'interpolation. |
| [setPageScale(float value)](#setPageScale-float-) | Obtient ou définit l'échelle entre les unités du monde et les unités de page pour ce com.aspose.psd.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans ce com.aspose.psd.graphics. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Obtient ou définit les options d'image, utilisées pour créer des images vectorielles peintables à dessiner. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Obtient ou définit le mode d'anticrénelage. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Obtient ou définit l'indice de rendu du texte. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Obtient ou définit une copie de la transformation géométrique du monde pour ce com.aspose.psd.graphics. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Déplace la transformation géométrique locale des dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Déplace la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Initialise une nouvelle instance de la classe Graphics.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image source. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Obtient le coefficient de taille du style de texte gras

Utilisation de nombres magiques car GDI fournit toujours la mesure uniquement pour le style Régulier.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Obtient le coefficient de taille du style de texte italique

Utilisation de nombres magiques car GDI fournit toujours la mesure uniquement pour le style Régulier.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Applique l'effet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| effet | com.aspose.internal.IEffect | L'effet à appliquer. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Démarre la mise en cache des opérations graphiques suivantes. Les effets graphiques appliqués ensuite ne seront pas appliqués immédiatement ; à la place, EndUpdate provoquera l'application de tous les effets en une fois.

Notez que les effets après l'appel de BeginUpdate ne seront pas appliqués si EndUpdate n'est pas appelé.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Efface la surface graphique en utilisant la couleur spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | La couleur avec laquelle effacer la surface graphique. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Structure RectangleF  qui définit les limites de l'ellipse. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre  startAngle  jusqu'au point final de l'arc. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Dessine un arc représentant une partie d'une ellipse spécifiée par une structure RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Structure RectangleF  qui définit les limites de l'ellipse. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre  startAngle  jusqu'au point final de l'arc. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'arc. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| largeur | float | Largeur du rectangle qui définit l'ellipse. |
| hauteur | float | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre  startAngle  jusqu'au point final de l'arc. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'arc. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| largeur | int | Largeur du rectangle qui définit l'ellipse. |
| hauteur | int | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | int | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | int | Angle en degrés mesuré dans le sens horaire depuis le paramètre  startAngle  jusqu'au point final de l'arc. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Dessine une spline de Bézier définie par quatre structures Point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Structure Pen  qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [Point](../../com.aspose.psd/point) | Point  structure qui représente le point de départ de la courbe. |
| pt2 | [Point](../../com.aspose.psd/point) | Point  structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [Point](../../com.aspose.psd/point) | Point  structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [Point](../../com.aspose.psd/point) | Point  structure qui représente le point final de la courbe. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Dessine une spline de Bézier définie par quatre structures PointF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  structure qui représente le point de départ de la courbe. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  structure qui représente le point final de la courbe. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la courbe. |
| x1 | float | La coordonnée x du point de départ de la courbe. |
| y1 | float | La coordonnée y du point de départ de la courbe. |
| x2 | float | La coordonnée x du premier point de contrôle de la courbe. |
| y2 | float | La coordonnée y du premier point de contrôle de la courbe. |
| x3 | float | La coordonnée x du deuxième point de contrôle de la courbe. |
| y3 | float | La coordonnée y du deuxième point de contrôle de la courbe. |
| x4 | float | La coordonnée x du point final de la courbe. |
| y4 | float | La coordonnée y du point final de la courbe. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Dessine une série de splines de Bézier à partir d'un tableau de structures PointF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la courbe. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui représentent les points qui déterminent la courbe. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Dessine une série de splines de Bézier à partir d'un tableau de structures Point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la courbe. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures  Point  qui représentent les points qui déterminent la courbe. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Dessine une spline cardinal fermée définie par un tableau de structures  PointF . Cette méthode utilise une tension par défaut de 0.5 et  FillMode.Alternate  mode de remplissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui définissent la spline. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Dessine une spline cardinal fermée définie par un tableau de structures  PointF  en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage par défaut  FillMode.Alternate  mode de remplissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Dessine une spline cardinal fermée définie par un tableau de structures  Point . Cette méthode utilise une tension par défaut de 0.5 et  FillMode.Alternate  mode de remplissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures  Point  qui définissent la spline. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Dessine une spline cardinal fermée définie par un tableau de structures  Point  en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage par défaut  FillMode.Alternate  mode de remplissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures  Point  qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Dessine une spline cardinal à travers un tableau spécifié de structures  PointF . Cette méthode utilise une tension par défaut de 0.5.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui définissent la spline. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Dessine une spline cardinale à travers un tableau spécifié de structures  PointF  en utilisant une tension spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui représentent les points qui définissent la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Dessine une spline cardinal à travers un tableau spécifié de structures  PointF . Le dessin commence avec un décalage depuis le début du tableau. Cette méthode utilise une tension par défaut de 0.5.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui définissent la spline. |
| décalage | int | Décalage depuis le premier élément du tableau du paramètre  points  jusqu'au point de départ de la courbe. |
| numberOfSegments | int | Nombre de segments après le point de départ à inclure dans la courbe. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Dessine une spline cardinal à travers un tableau spécifié de structures  PointF  en utilisant une tension spécifiée. Le dessin commence avec un décalage depuis le début du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui définissent la spline. |
| décalage | int | Décalage depuis le premier élément du tableau du paramètre  points  jusqu'au point de départ de la courbe. |
| numberOfSegments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Dessine une spline cardinale à travers un tableau spécifié de structures  Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures  Point  qui définissent la spline. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Dessine une spline cardinale à travers un tableau spécifié de structures  Point  en utilisant une tension spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures  Point  qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Dessine une spline cardinale à travers un tableau spécifié de structures  Point  en utilisant une tension spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures  Point  qui définissent la spline. |
| décalage | int | Décalage depuis le premier élément du tableau du paramètre  points  jusqu'au point de départ de la courbe. |
| numberOfSegments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Dessine une ellipse spécifiée par une structure de  Rectangle  englobante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'ellipse. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Structure  Rectangle  qui définit les limites de l'ellipse. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Dessine une ellipse définie par un  RectangleF  englobant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'ellipse. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Structure RectangleF  qui définit les limites de l'ellipse. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| largeur | float | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stylo  qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| largeur | int | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Dessine l' Image  spécifiée , en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| point | [Point](../../com.aspose.psd/point) | Point  structure qui représente l'emplacement du coin supérieur gauche de l'image dessinée. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Dessine l' Image  spécifiée , en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| point | [PointF](../../com.aspose.psd/pointf) | Structure PointF qui représente le coin supérieur gauche de l'image dessinée. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle source. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle source. |
| srcUnit | int | Les unités de mesure. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle source. |
| srcUnit | int | Les unités de mesure. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Les attributs de l'image. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle source. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle source. |
| srcUnit | int | Les unités de mesure. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Dessine la portion spécifiée de l' image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à dessiner. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle source. |
| srcUnit | int | Les unités de mesure. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Les attributs de l'image. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Structure Rectangle qui spécifie l'emplacement et la taille de l'image dessinée. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Le rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Le rect destination. |
| graphicsUnit | int | L'unité graphique. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Le rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Le rect destination. |
| graphicsUnit | int | L'unité graphique. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Les attributs de l'image. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle de destination. |
| graphicsUnit | int | L'unité graphique. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle de destination. |
| graphicsUnit | int | L'unité graphique. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Les attributs de l'image. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Structure RectangleF qui spécifie l'emplacement et la taille de l'image dessinée. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Le rect source. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Le rect destination. |
| graphicsUnit | int | L'unité graphique. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle source. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle de destination. |
| graphicsUnit | int | L'unité graphique à utiliser. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Les attributs de l'image à utiliser. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle de destination. |
| graphicsUnit | int | L'unité graphique. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle de destination dans lequel dessiner. |
| graphicsUnit | int | L'unité graphique. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Les attributs de l'image. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Dessine l' Image  spécifiée , en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| largeur | float | Largeur de l'image dessinée. |
| hauteur | float | Hauteur de l'image dessinée. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Dessine l'image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié par une paire de coordonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Dessine l' Image  spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| largeur | int | Largeur de l'image dessinée. |
| hauteur | int | Hauteur de l'image dessinée. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| point | [Point](../../com.aspose.psd/point) | Structure Point qui spécifie le coin supérieur gauche de l'image dessinée. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle qui spécifie le coin supérieur gauche de l'image dessinée. Les propriétés X et Y du rectangle spécifient le coin supérieur gauche. Les propriétés Width et Height sont ignorées. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Dessine l'image spécifiée en utilisant sa taille physique d'origine à l'emplacement spécifié par une paire de coordonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| largeur | int | Le paramètre n'est pas utilisé. |
| hauteur | int | Le paramètre n'est pas utilisé. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour l'adapter au rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Le  Rectangle  dans lequel dessiner l'image. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Dessine une ligne reliant deux structures  Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | [Point](../../com.aspose.psd/point) | Point  structure qui représente le premier point à connecter. |
| point2 | [Point](../../com.aspose.psd/point) | Point  structure qui représente le deuxième point à connecter. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Dessine une ligne reliant deux structures  PointF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | [PointF](../../com.aspose.psd/pointf) | PointF  structure qui représente le premier point à connecter. |
| point2 | [PointF](../../com.aspose.psd/pointf) | PointF  structure qui représente le deuxième point à connecter. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | float | La coordonnée x du premier point. |
| y1 | float | La coordonnée y du premier point. |
| x2 | float | La coordonnée x du deuxième point. |
| y2 | float | La coordonnée y du deuxième point. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Dessine une série de segments de ligne qui relient un tableau de structures  PointF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de  PointF  structures qui représentent les points à connecter. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Dessine une série de segments de ligne qui relient un tableau de structures  Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de  Point  structures qui représentent les points à connecter. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Dessine un  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen  qui détermine la couleur, la largeur et le style du chemin. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath  à dessiner. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Dessine une forme de secteur définie par une ellipse spécifiée par une structure de  Rectangle  et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la forme de tarte. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Structure Rectangle  qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| startAngle | float | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de tarte. |
| sweepAngle | float | Angle mesuré en degrés dans le sens horaire depuis le paramètre  startAngle  jusqu'au deuxième côté de la forme de tarte. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Dessine une forme de secteur définie par une ellipse spécifiée par une structure de  RectangleF  et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la forme de tarte. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Structure RectangleF  qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| startAngle | float | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de tarte. |
| sweepAngle | float | Angle mesuré en degrés dans le sens horaire depuis le paramètre  startAngle  jusqu'au deuxième côté de la forme de tarte. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la forme de tarte. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| largeur | float | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| startAngle | float | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de tarte. |
| sweepAngle | float | Angle mesuré en degrés dans le sens horaire depuis le paramètre  startAngle  jusqu'au deuxième côté de la forme de tarte. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style de la forme de tarte. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| largeur | int | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| startAngle | int | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de tarte. |
| sweepAngle | int | Angle mesuré en degrés dans le sens horaire depuis le paramètre  startAngle  jusqu'au deuxième côté de la forme de tarte. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Dessine un polygone défini par un tableau de structures  PointF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style du polygone. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures  PointF  qui représentent les sommets du polygone. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Dessine un polygone défini par un tableau de structures  Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style du polygone. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures  Point  qui représentent les sommets du polygone. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Dessine un rectangle spécifié par une structure  Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  Pen  qui détermine la couleur, la largeur et le style du rectangle. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Une structure  Rectangle  qui représente le rectangle à dessiner. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Dessine un rectangle spécifié par une structure  RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  Pen  qui détermine la couleur, la largeur et le style du rectangle. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Une structure  RectangleF  qui représente le rectangle à dessiner. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  Pen  qui détermine la couleur, la largeur et le style du rectangle. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| largeur | float | La largeur du rectangle à dessiner. |
| hauteur | float | La hauteur du rectangle à dessiner. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style du rectangle. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| largeur | int | Largeur du rectangle à dessiner. |
| hauteur | int | Hauteur du rectangle à dessiner. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Dessine une série de rectangles spécifiés par des structures  RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Tableau de structures  RectangleF  qui représentent les rectangles à dessiner. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Dessine une série de rectangles spécifiés par des structures  Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Tableau de structures  Rectangle  qui représentent les rectangles à dessiner. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  structure qui spécifie le coin supérieur gauche du texte dessiné. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  structure qui spécifie le coin supérieur gauche du texte dessiné. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  qui spécifie les attributs de formatage, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  structure qui spécifie l'emplacement du texte dessiné. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  structure qui spécifie l'emplacement du texte dessiné. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  qui spécifie les attributs de formatage, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  qui spécifie les attributs de formatage, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Dessine la chaîne de texte spécifiée de manière compatible Adobe dans le rectangle spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés en utilisant les attributs de formatage du  com.aspose.psd.stringFormat  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  structure qui spécifie l'emplacement du texte dessiné. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  qui spécifie les attributs de formatage, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Dessine la chaîne de texte spécifiée de manière compatible Adobe à l'emplacement spécifié avec les objets  com.aspose.psd.Brush  et  com.aspose.psd.Font  spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | Chaîne à dessiner. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  qui définit le format du texte de la chaîne. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Termine la mise en cache des opérations graphiques démarrées après l'appel de BeginUpdate. Les opérations graphiques précédentes seront appliquées d'un coup lors de l'appel de cette méthode.

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
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures com.aspose.psd.PointF. Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage FillMode.Alternate.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures com.aspose.psd.PointF qui définissent la spline. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures com.aspose.psd.PointF en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures com.aspose.psd.PointF qui définissent la spline. |
| mode de remplissage | int | Membre de l'énumération com.aspose.psd.FillMode qui détermine comment la courbe est remplie. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.PointF  en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures com.aspose.psd.PointF qui définissent la spline. |
| mode de remplissage | int | Membre de l'énumération com.aspose.psd.FillMode qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures com.aspose.psd.Point. Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage FillMode.Alternate.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures com.aspose.psd.Point qui définissent la spline. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures com.aspose.psd.Point en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures com.aspose.psd.Point qui définissent la spline. |
| mode de remplissage | int | Membre de l'énumération com.aspose.psd.FillMode qui détermine comment la courbe est remplie. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures  com.aspose.psd.Point  en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures com.aspose.psd.Point qui définissent la spline. |
| mode de remplissage | int | Membre de l'énumération com.aspose.psd.FillMode qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Structure com.aspose.psd.Rectangle qui représente le rectangle englobant qui définit l'ellipse. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Structure com.aspose.psd.RectangleF qui représente le rectangle englobant qui définit l'ellipse. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| largeur | float | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| largeur | int | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Remplit l'intérieur d'un  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath qui représente le chemin à remplir. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une structure com.aspose.psd.RectangleF et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Structure com.aspose.psd.Rectangle qui représente le rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweepAngle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre startAngle jusqu'au deuxième côté de la section de tarte. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une structure com.aspose.psd.RectangleF et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Structure com.aspose.psd.RectangleF qui représente le rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweepAngle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre startAngle jusqu'au deuxième côté de la section de tarte. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| largeur | float | Largeur du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweepAngle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre startAngle jusqu'au deuxième côté de la section de tarte. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Remplit l'intérieur d'une section de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| largeur | int | Largeur du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse d'où provient la section de tarte. |
| startAngle | int | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweepAngle | int | Angle en degrés mesuré dans le sens horaire à partir du paramètre startAngle jusqu'au deuxième côté de la section de tarte. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.PointF et FillMode.Alternate.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures com.aspose.psd.PointF qui représentent les sommets du polygone à remplir. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.PointF en utilisant le mode de remplissage spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Tableau de structures com.aspose.psd.PointF qui représentent les sommets du polygone à remplir. |
| fillMode | int | Membre de l'énumération com.aspose.psd.FillMode qui détermine le style du remplissage. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.Point et FillMode.Alternate.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures com.aspose.psd.Point qui représentent les sommets du polygone à remplir. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures com.aspose.psd.Point en utilisant le mode de remplissage spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| points | [Point\[\]](../../com.aspose.psd/point) | Tableau de structures com.aspose.psd.Point qui représentent les sommets du polygone à remplir. |
| fillMode | int | Membre de l'énumération com.aspose.psd.FillMode qui détermine le style du remplissage. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Remplit l'intérieur d'un rectangle spécifié par une structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Structure Rectangle qui représente le rectangle à remplir. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Remplit l'intérieur d'un rectangle spécifié par une structure RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Structure RectangleF qui représente le rectangle à remplir. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| largeur | float | Largeur du rectangle à remplir. |
| hauteur | float | Hauteur du rectangle à remplir. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| largeur | int | Largeur du rectangle à remplir. |
| hauteur | int | Hauteur du rectangle à remplir. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Remplit l'intérieur d'une série de rectangles spécifiés par des structures RectangleF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush qui détermine les caractéristiques du remplissage. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Tableau de structures Rectangle qui représentent les rectangles à remplir. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Remplit l'intérieur d'une série de rectangles spécifiés par des structures Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush qui détermine les caractéristiques du remplissage. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Tableau de structures Rectangle qui représentent les rectangles à remplir. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Remplit l'intérieur d'une com.aspose.psd.region.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush qui détermine les caractéristiques du remplissage. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region qui représente la zone à remplir. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


Obtient ou définit la région de découpage.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Obtient ou définit la qualité de composition.

**Returns:**
int - La qualité de composition.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Obtient la résolution horizontale de ce com.aspose.psd.graphics.

**Returns:**
float - La valeur, en points par pouce, pour la résolution horizontale prise en charge par ce com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Obtient la résolution verticale de ce com.aspose.psd.graphics.

**Returns:**
float - La valeur, en points par pouce, pour la résolution verticale prise en charge par ce com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


Obtient l'image.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Obtient ou définit le mode d'interpolation.

**Returns:**
int - Le mode d'interpolation.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Obtient ou définit l'échelle entre les unités du monde et les unités de page pour ce com.aspose.psd.graphics.

**Returns:**
float - L'échelle entre les unités du monde et les unités de page pour ce com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans ce com.aspose.psd.graphics.

**Returns:**
int - L'unité de mesure utilisée pour les coordonnées de page dans ce com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Obtient ou définit les options d'image, utilisées pour créer des images vectorielles peintables à dessiner.

Valeur : Les options d'image, utilisées pour créer des images vectorielles peintes à dessiner.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Obtient ou définit le mode d'anticrénelage.

**Returns:**
int - Le mode d'anticrénelage.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Obtient ou définit l'indice de rendu du texte.

**Returns:**
int - L'indice de rendu du texte.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient ou définit une copie de la transformation géométrique du monde pour ce com.aspose.psd.graphics.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


Obtient une valeur indiquant si le graphique est dans l'état d'appel BeginUpdate.

**Returns:**
boolean -  True  si le graphique est dans l'état d'appel BeginUpdate ; sinon,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Mesure la chaîne en utilisant la classe [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | La police. |
| text | java.lang.String | Le texte. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Mesure la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | La police. |
|  | text | java.lang.String | Le texte. |

--------------------

Le résultat GDI est presque toujours invalide pour les styles Italic et souvent invalide pour les styles Bold. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Mesure la chaîne de texte spécifiée avec les paramètres spécifiés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à mesurer. |
| font | [Font](../../com.aspose.psd/font) | La police à mesurer. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | La zone de mise en page. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Le format de chaîne. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Le cache de police privé. |
| useMagicNumbersForStyles | booléen | si défini sur true [utiliser des nombres magiques pour les styles]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplie le  com.aspose.psd.Matrix  qui représente la transformation géométrique locale de ce  com.aspose.psd.Graphics  par le  com.aspose.psd.Matrix  spécifié en préfixant le  com.aspose.psd.matrix .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Le  com.aspose.psd.Matrix  par lequel multiplier la transformation géométrique. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie le  com.aspose.psd.Matrix  qui représente la transformation géométrique locale de ce  com.aspose.psd.Graphics  par le  com.aspose.psd.Matrix  spécifié dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Le  com.aspose.psd.Matrix  par lequel multiplier la transformation géométrique. |
| ordre | int | Un  com.aspose.psd.MatrixOrder  qui spécifie dans quel ordre multiplier les deux matrices. |

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


Réinitialise la propriété  com.aspose.psd.graphics.Transform  à l'identité.

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
| ordre | int | Un  com.aspose.psd.MatrixOrder  qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

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
| ordre | int | Un  com.aspose.psd.MatrixOrder  qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Obtient ou définit la région de découpage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | La région de découpage. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Obtient ou définit la qualité de composition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La qualité de composition. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Obtient ou définit le mode d'interpolation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode d'interpolation. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Obtient ou définit l'échelle entre les unités du monde et les unités de page pour ce com.aspose.psd.graphics.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'échelle entre les unités du monde et les unités de page pour ce com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans ce com.aspose.psd.graphics.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'unité de mesure utilisée pour les coordonnées de page dans ce com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Obtient ou définit les options d'image, utilisées pour créer des images vectorielles peintables à dessiner.

Valeur : Les options d'image, utilisées pour créer des images vectorielles peintes à dessiner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Obtient ou définit le mode d'anticrénelage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de lissage. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Obtient ou définit l'indice de rendu du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'indice de rendu du texte. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Obtient ou définit une copie de la transformation géométrique du monde pour ce com.aspose.psd.graphics.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Une copie du  com.aspose.psd.Matrix  qui représente la transformation géométrique du monde pour ce  com.aspose.psd.graphics . |

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

