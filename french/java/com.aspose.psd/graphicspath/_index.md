---
title: "GraphicsPath"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente une série de lignes et de courbes connectées."
type: docs
weight: 50
url: /fr/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initialise une nouvelle instance de la classe  GraphicsPath . |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Initialise une nouvelle instance de la classe  GraphicsPath . |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Initialise une nouvelle instance de la classe  GraphicsPath . |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initialise une nouvelle instance de la classe  GraphicsPath . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Ajoute une nouvelle figure. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Ajoute de nouvelles figures. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Ajoute le  com.aspose.psd.GraphicsPath  spécifié à ce chemin. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Ajoute le  com.aspose.psd.GraphicsPath  spécifié à ce chemin. |
| [deepClone()](#deepClone--) | Effectue un clonage profond de ce chemin graphique. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Applique la transformation spécifiée puis convertit chaque courbe de ce  com.aspose.psd.GraphicsPath  en une séquence de segments de ligne connectés. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Convertit chaque courbe de ce  com.aspose.psd.GraphicsPath  en une séquence de segments de ligne connectés. |
| [getBounds()](#getBounds--) | Obtient ou définit les limites de l'objet. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtient les limites de l'objet. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Obtient les figures du chemin. |
| [getFillMode()](#getFillMode--) | Obtient une énumération  com.aspose.psd.FillMode  qui détermine comment les intérieurs des formes de ce  com.aspose.psd.GraphicsPath  sont remplis. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.GraphicsPath  dans la région de découpe visible du  com.aspose.psd.graphics  spécifié. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.GraphicsPath , en utilisant le  com.aspose.psd.graphics  spécifié. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Supprime une figure. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Supprime des figures. |
| [reset()](#reset--) | Vide le chemin graphique et définit le  com.aspose.psd.FillMode  sur  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Inverse l'ordre des figures, formes et points dans chaque forme de ce com.aspose.psd.graphicsPath. |
| [setFillMode(int value)](#setFillMode-int-) | Définit une énumération com.aspose.psd.FillMode qui détermine comment les intérieurs des formes de ce com.aspose.psd.GraphicsPath sont remplis. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applique la transformation spécifiée à la forme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath. |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Ajoute un contour supplémentaire au chemin. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Ajoute un contour supplémentaire au com.aspose.psd.graphicsPath. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Remplace ce com.aspose.psd.GraphicsPath par des courbes qui entourent la zone remplie lorsque ce chemin est tracé avec le stylo spécifié. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initialise une nouvelle instance de la classe  GraphicsPath .

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initialise une nouvelle instance de la classe  GraphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Les figures à initialiser. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initialise une nouvelle instance de la classe  GraphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Les figures à initialiser. |
| fillMode | int | Le mode de remplissage. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initialise une nouvelle instance de la classe  GraphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillMode | int | Le mode de remplissage. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Ajoute une nouvelle figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | La figure à ajouter. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Ajoute de nouvelles figures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Les figures à ajouter. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Ajoute le  com.aspose.psd.GraphicsPath  spécifié à ce chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le com.aspose.psd.GraphicsPath à ajouter. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Ajoute le  com.aspose.psd.GraphicsPath  spécifié à ce chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le com.aspose.psd.GraphicsPath à ajouter. |
| connect | booléen | Une valeur booléenne qui indique si la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur true indique que la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur false indique que la première figure du chemin ajouté est distincte de la dernière figure de ce chemin. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Effectue un clonage profond de ce chemin graphique.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Applique la transformation spécifiée puis convertit chaque courbe de ce  com.aspose.psd.GraphicsPath  en une séquence de segments de ligne connectés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Une com.aspose.psd.Matrix permettant de transformer ce com.aspose.psd.GraphicsPath avant l'aplatissement. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Convertit chaque courbe de ce  com.aspose.psd.GraphicsPath  en une séquence de segments de ligne connectés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Une com.aspose.psd.Matrix permettant de transformer ce com.aspose.psd.GraphicsPath avant l'aplatissement. |
| flatness | float | Spécifie l'erreur maximale autorisée entre la courbe et son approximation aplatie. Une valeur de 0,25 est la valeur par défaut. Réduire la valeur de flatness augmentera le nombre de segments de ligne dans l'approximation. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtient ou définit les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |
| pen | [Pen](../../com.aspose.psd/pen) | Le crayon à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Obtient les figures du chemin.

**Returns:**
com.aspose.psd.Figure[] - Les figures du chemin.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Obtient une énumération  com.aspose.psd.FillMode  qui détermine comment les intérieurs des formes de ce  com.aspose.psd.GraphicsPath  sont remplis.

**Returns:**
int - Le mode de remplissage. Une énumération com.aspose.psd.FillMode qui spécifie comment les intérieurs des formes de ce com.aspose.psd.GraphicsPath sont remplis.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Un com.aspose.psd.Point qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce com.aspose.psd.GraphicsPath lorsqu'il est tracé avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Un com.aspose.psd.Point qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce com.aspose.psd.GraphicsPath tel que tracé avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Un com.aspose.psd.PointF qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce com.aspose.psd.GraphicsPath lorsqu'il est tracé avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Un com.aspose.psd.PointF qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur (ou sous) le contour de ce com.aspose.psd.GraphicsPath tel que dessiné avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce com.aspose.psd.GraphicsPath lorsqu'il est tracé avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur (ou sous) le contour de ce com.aspose.psd.GraphicsPath tel que dessiné avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.pen  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce com.aspose.psd.GraphicsPath lorsqu'il est tracé avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce  com.aspose.psd.GraphicsPath  lorsqu'il est dessiné avec le  com.aspose.psd.Pen  spécifié et en utilisant le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.psd/pen) | Le com.aspose.psd.Pen à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce com.aspose.psd.GraphicsPath tel que tracé avec le com.aspose.psd.Pen spécifié ; sinon, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Un com.aspose.psd.Point qui représente le point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de ce com.aspose.psd.GraphicsPath ; sinon, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Un com.aspose.psd.Point qui représente le point à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de ce com.aspose.psd.GraphicsPath ; sinon, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Un com.aspose.psd.PointF qui représente le point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de ce com.aspose.psd.GraphicsPath ; sinon, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Un com.aspose.psd.PointF qui représente le point à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de cet objet ; sinon, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de ce com.aspose.psd.GraphicsPath ; sinon, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.GraphicsPath  dans la région de découpe visible du  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de ce com.aspose.psd.GraphicsPath ; sinon, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.graphicsPath .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de ce com.aspose.psd.GraphicsPath ; sinon, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indique si le point spécifié est contenu à l'intérieur de ce  com.aspose.psd.GraphicsPath , en utilisant le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Le com.aspose.psd.Graphics pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu à l'intérieur de ce com.aspose.psd.GraphicsPath ; sinon, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


Supprime une figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | La figure à supprimer. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Supprime des figures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Les figures à supprimer. |

### reset() {#reset--}
```
public void reset()
```


Vide le chemin graphique et définit le  com.aspose.psd.FillMode  sur  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Inverse l'ordre des figures, formes et points dans chaque forme de ce com.aspose.psd.graphicsPath.

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Définit une énumération com.aspose.psd.FillMode qui détermine comment les intérieurs des formes de ce com.aspose.psd.GraphicsPath sont remplis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de remplissage. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Applique la transformation spécifiée à la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | La transformation à appliquer. |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un tableau de structures com.aspose.psd.PointF qui définissent un parallélogramme vers lequel le rectangle défini par srcRect est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un com.aspose.psd.RectangleF qui représente le rectangle qui est transformé en le parallélogramme défini par destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un tableau de structures com.aspose.psd.PointF qui définissent un parallélogramme vers lequel le rectangle défini par srcRect est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un com.aspose.psd.RectangleF qui représente le rectangle qui est transformé en le parallélogramme défini par destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Une com.aspose.psd.Matrix qui spécifie une transformation géométrique à appliquer au chemin. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un tableau de structures com.aspose.psd.PointF qui définissent un parallélogramme vers lequel le rectangle défini par srcRect est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un com.aspose.psd.RectangleF qui représente le rectangle qui est transformé en le parallélogramme défini par destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Une com.aspose.psd.Matrix qui spécifie une transformation géométrique à appliquer au chemin. |
| warpMode | int | Une énumération com.aspose.psd.WarpMode qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce com.aspose.psd.graphicsPath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un tableau de structures com.aspose.psd.PointF qui définissent un parallélogramme vers lequel le rectangle défini par srcRect est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un com.aspose.psd.RectangleF qui représente le rectangle qui est transformé en le parallélogramme défini par destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Une com.aspose.psd.Matrix qui spécifie une transformation géométrique à appliquer au chemin. |
| warpMode | int | Une énumération com.aspose.psd.WarpMode qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |
| flatness | float | Une valeur comprise entre 0 et 1 qui spécifie le degré d'aplatissement du chemin résultant. Pour plus d'informations, voir les méthodes com.aspose.psd.GraphicsPath.flatten . |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Ajoute un contour supplémentaire au chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un com.aspose.psd.Pen qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Ajoute un contour supplémentaire au com.aspose.psd.graphicsPath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un com.aspose.psd.Pen qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Une com.aspose.psd.Matrix qui spécifie une transformation à appliquer au chemin avant l'élargissement. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Remplace ce com.aspose.psd.GraphicsPath par des courbes qui entourent la zone remplie lorsque ce chemin est tracé avec le stylo spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un com.aspose.psd.Pen qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Une com.aspose.psd.Matrix qui spécifie une transformation à appliquer au chemin avant l'élargissement. |
| flatness | float | Une valeur qui spécifie l'aplatissement des courbes. |

