---
title: "GraphicsPath"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een reeks verbonden lijnen en curven voor."
type: docs
weight: 50
url: /nl/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Stelt een reeks verbonden lijnen en krommen voor. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Voegt een nieuwe figuur toe. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Voegt nieuwe figuren toe. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Voegt de opgegeven  com.aspose.psd.GraphicsPath  toe aan dit pad. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Voegt de opgegeven  com.aspose.psd.GraphicsPath  toe aan dit pad. |
| [deepClone()](#deepClone--) | Voert een diepe kloon uit van dit grafische pad. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Converteert elke kromme in dit pad naar een reeks verbonden lijnsegmenten. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Past de opgegeven transformatie toe en converteert vervolgens elke kromme in deze  com.aspose.psd.GraphicsPath  naar een reeks verbonden lijnsegmenten. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Converteert elke kromme in deze  com.aspose.psd.GraphicsPath  naar een reeks verbonden lijnsegmenten. |
| [getBounds()](#getBounds--) | Haalt de grenzen van het object op of stelt ze in. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Haalt de grenzen van het object op. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Haalt de padfiguren op. |
| [getFillMode()](#getFillMode--) | Haalt een  com.aspose.psd.FillMode  enumeratie op die bepaalt hoe de binnenkanten van vormen in deze  com.aspose.psd.GraphicsPath  worden gevuld. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen . |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics . |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen . |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics . |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen . |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics . |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen . |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics . |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.GraphicsPath  bevindt in de zichtbare knipregio van de opgegeven  com.aspose.psd.graphics . |
| [isVisible(int x, int y)](#isVisible-int-int-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.GraphicsPath  bevindt, met gebruik van de opgegeven  com.aspose.psd.graphics . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Verwijdert een figuur. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Verwijdert figuren. |
| [reset()](#reset--) | Leegt het grafische pad en stelt de  com.aspose.psd.FillMode  in op  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Keert de volgorde van figuren, vormen en punten in elke vorm van dit  com.aspose.psd.graphicsPath  om. |
| [setFillMode(int value)](#setFillMode-int-) | Stelt een  com.aspose.psd.FillMode  enumeratie in die bepaalt hoe de binnenkanten van vormen in dit  com.aspose.psd.GraphicsPath  worden gevuld. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Past de opgegeven transformatie toe op de vorm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Voegt een extra omtrek toe aan het pad. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Voegt een extra omtrek toe aan de  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Vervangt dit  com.aspose.psd.GraphicsPath  door curven die het gebied omsluiten dat wordt gevuld wanneer dit pad wordt getekend met de opgegeven pen. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | De figuren om van te initialiseren. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | De figuren om van te initialiseren. |
| fillMode | int | De vulmodus. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initialiseert een nieuw exemplaar van de  GraphicsPath  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillMode | int | De vulmodus. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Voegt een nieuwe figuur toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | De toe te voegen figuur. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Voegt nieuwe figuren toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | De toe te voegen figuren. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Voegt de opgegeven  com.aspose.psd.GraphicsPath  toe aan dit pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Het  com.aspose.psd.GraphicsPath  om toe te voegen. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Voegt de opgegeven  com.aspose.psd.GraphicsPath  toe aan dit pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Het  com.aspose.psd.GraphicsPath  om toe te voegen. |
| connect | boolean | Een Booleaanse waarde die aangeeft of de eerste figuur in het toegevoegde pad deel uitmaakt van de laatste figuur in dit pad. Een waarde van true geeft aan dat de eerste figuur in het toegevoegde pad deel uitmaakt van de laatste figuur in dit pad. Een waarde van false geeft aan dat de eerste figuur in het toegevoegde pad gescheiden is van de laatste figuur in dit pad. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Voert een diepe kloon uit van dit grafische pad.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Converteert elke kromme in dit pad naar een reeks verbonden lijnsegmenten.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Past de opgegeven transformatie toe en converteert vervolgens elke kromme in deze  com.aspose.psd.GraphicsPath  naar een reeks verbonden lijnsegmenten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Een  com.aspose.psd.Matrix  waarmee dit  com.aspose.psd.GraphicsPath  wordt getransformeerd vóór het afvlakken. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Converteert elke kromme in deze  com.aspose.psd.GraphicsPath  naar een reeks verbonden lijnsegmenten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Een  com.aspose.psd.Matrix  waarmee dit  com.aspose.psd.GraphicsPath  wordt getransformeerd vóór het afvlakken. |
| flatness | float | Specificeert de maximaal toegestane fout tussen de curve en zijn afgevlakte benadering. Een waarde van 0.25 is de standaard. Het verlagen van de flatness-waarde zal het aantal lijnsegmenten in de benadering verhogen. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Haalt de grenzen van het object op of stelt ze in.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Haalt de grenzen van het object op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Haalt de grenzen van het object op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |
| pen | [Pen](../../com.aspose.psd/pen) | De pen die voor het object moet worden gebruikt. Dit kan de grootte van de grenzen van het object beïnvloeden. |

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


Haalt de padfiguren op.

**Returns:**
com.aspose.psd.Figure[] - De padfiguren.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Haalt een  com.aspose.psd.FillMode  enumeratie op die bepaalt hoe de binnenkanten van vormen in deze  com.aspose.psd.GraphicsPath  worden gevuld.

**Returns:**
int - De vulmodus. Een  com.aspose.psd.FillMode  enumeratie die specificeert hoe de binnenkanten van vormen in dit  com.aspose.psd.GraphicsPath  worden gevuld.
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


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Een  com.aspose.psd.Point  die de locatie specificeert om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt wanneer getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Een  com.aspose.psd.Point  die de locatie specificeert om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt zoals getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Een  com.aspose.psd.PointF  die de locatie specificeert om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt wanneer getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Een  com.aspose.psd.PointF  die de locatie specificeert om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt zoals getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt wanneer getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt zoals getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het punt om te testen. |
| y | int | De y-coördinaat van het punt om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt wanneer getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van deze  com.aspose.psd.GraphicsPath  wanneer getekend met de opgegeven  com.aspose.psd.Pen  en met gebruik van de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het punt om te testen. |
| y | int | De y-coördinaat van het punt om te testen. |
| pen | [Pen](../../com.aspose.psd/pen) | De  com.aspose.psd.Pen  om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van deze  com.aspose.psd.GraphicsPath  bevindt zoals getekend met de opgegeven  com.aspose.psd.Pen ; anders, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Een  com.aspose.psd.Point  die het punt vertegenwoordigt om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen deze  com.aspose.psd.GraphicsPath  bevindt; anders, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Een  com.aspose.psd.Point  die het punt vertegenwoordigt om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen deze  com.aspose.psd.GraphicsPath  bevindt; anders, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Een  com.aspose.psd.PointF  die het punt vertegenwoordigt om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen deze  com.aspose.psd.GraphicsPath  bevindt; anders, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Een  com.aspose.psd.PointF  die het punt vertegenwoordigt om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen dit bevindt; anders, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen deze  com.aspose.psd.GraphicsPath  bevindt; anders, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.GraphicsPath  bevindt in de zichtbare knipregio van de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen deze  com.aspose.psd.GraphicsPath  bevindt; anders, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.graphicsPath  bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het punt om te testen. |
| y | int | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen deze  com.aspose.psd.GraphicsPath  bevindt; anders, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Geeft aan of het opgegeven punt zich binnen dit  com.aspose.psd.GraphicsPath  bevindt, met gebruik van de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het punt om te testen. |
| y | int | De y-coördinaat van het punt om te testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | De  com.aspose.psd.Graphics  waarvoor de zichtbaarheid moet worden getest. |

**Returns:**
boolean - Deze methode retourneert true als het opgegeven punt zich binnen deze  com.aspose.psd.GraphicsPath  bevindt; anders, false.
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


Verwijdert een figuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | De figuur om te verwijderen. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Verwijdert figuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | De figuren om te verwijderen. |

### reset() {#reset--}
```
public void reset()
```


Leegt het grafische pad en stelt de  com.aspose.psd.FillMode  in op  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Keert de volgorde van figuren, vormen en punten in elke vorm van dit  com.aspose.psd.graphicsPath  om.

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Stelt een  com.aspose.psd.FillMode  enumeratie in die bepaalt hoe de binnenkanten van vormen in dit  com.aspose.psd.GraphicsPath  worden gevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De vulmodus. |

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


Past de opgegeven transformatie toe op de vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | De transformatie die moet worden toegepast. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Een array van  com.aspose.psd.PointF  structuren die een parallellogram definiëren waaraan het door  srcRect  gedefinieerde rechthoek wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Een  com.aspose.psd.RectangleF  die het rechthoek vertegenwoordigt dat wordt getransformeerd naar het parallellogram gedefinieerd door  destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Een array van  com.aspose.psd.PointF  structuren die een parallellogram definiëren waaraan het door  srcRect  gedefinieerde rechthoek wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Een  com.aspose.psd.RectangleF  die het rechthoek vertegenwoordigt dat wordt getransformeerd naar het parallellogram gedefinieerd door  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Een  com.aspose.psd.Matrix  die een geometrische transformatie specificeert die op het pad moet worden toegepast. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Een array van  com.aspose.psd.PointF  structuren die een parallellogram definiëren waaraan het door  srcRect  gedefinieerde rechthoek wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Een  com.aspose.psd.RectangleF  die het rechthoek vertegenwoordigt dat wordt getransformeerd naar het parallellogram gedefinieerd door  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Een  com.aspose.psd.Matrix  die een geometrische transformatie specificeert die op het pad moet worden toegepast. |
| warpMode | int | Een  com.aspose.psd.WarpMode  enumeratie die specificeert of deze warp-bewerking perspectief- of bilineaire modus gebruikt. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Een array van  com.aspose.psd.PointF  structuren die een parallellogram definiëren waaraan het door  srcRect  gedefinieerde rechthoek wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Een  com.aspose.psd.RectangleF  die het rechthoek vertegenwoordigt dat wordt getransformeerd naar het parallellogram gedefinieerd door  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Een  com.aspose.psd.Matrix  die een geometrische transformatie specificeert die op het pad moet worden toegepast. |
| warpMode | int | Een  com.aspose.psd.WarpMode  enumeratie die specificeert of deze warp-bewerking perspectief- of bilineaire modus gebruikt. |
| flatness | float | Een waarde van 0 tot 1 die specificeert hoe vlak het resulterende pad is. Voor meer informatie, zie de  com.aspose.psd.GraphicsPath.flatten  methoden. |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Voegt een extra omtrek toe aan het pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Een  com.aspose.psd.Pen  die de breedte specificeert tussen de oorspronkelijke omtrek van het pad en de nieuwe omtrek die deze methode creëert. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Voegt een extra omtrek toe aan de  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Een  com.aspose.psd.Pen  die de breedte specificeert tussen de oorspronkelijke omtrek van het pad en de nieuwe omtrek die deze methode creëert. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Een  com.aspose.psd.Matrix  die een transformatie specificeert die op het pad moet worden toegepast vóór het verbreden. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Vervangt dit  com.aspose.psd.GraphicsPath  door curven die het gebied omsluiten dat wordt gevuld wanneer dit pad wordt getekend met de opgegeven pen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Een  com.aspose.psd.Pen  die de breedte specificeert tussen de oorspronkelijke omtrek van het pad en de nieuwe omtrek die deze methode creëert. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Een  com.aspose.psd.Matrix  die een transformatie specificeert die op het pad moet worden toegepast vóór het verbreden. |
| flatness | float | Een waarde die de vlakheid voor krommen specificeert. |

