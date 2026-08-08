---
title: "GraphicsPath"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en serie av sammanhängande linjer och kurvor."
type: docs
weight: 50
url: /sv/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Representerar en serie av sammanlänkade linjer och kurvor. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initierar en ny instans av  GraphicsPath  klassen. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Initierar en ny instans av  GraphicsPath  klassen. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Initierar en ny instans av  GraphicsPath  klassen. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initierar en ny instans av  GraphicsPath  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Lägger till en ny figur. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Lägger till nya figurer. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Lägger till den angivna  com.aspose.psd.GraphicsPath  till denna sökväg. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Lägger till den angivna  com.aspose.psd.GraphicsPath  till denna sökväg. |
| [deepClone()](#deepClone--) | Utför en djup kloning av denna grafikbana. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Konverterar varje kurva i denna bana till en sekvens av sammanlänkade linjesegment. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Tillämpar den angivna transformen och konverterar sedan varje kurva i denna  com.aspose.psd.GraphicsPath  till en sekvens av sammanlänkade linjesegment. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Konverterar varje kurva i denna  com.aspose.psd.GraphicsPath  till en sekvens av sammanlänkade linjesegment. |
| [getBounds()](#getBounds--) | Hämtar eller anger objektets gränser. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Hämtar objektets gränser. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Hämtar banafigurerna. |
| [getFillMode()](#getFillMode--) | Hämtar en  com.aspose.psd.FillMode  enumeration som bestämmer hur innanmålen av former i denna  com.aspose.psd.GraphicsPath  fylls. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen . |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics . |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen . |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics . |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen . |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics . |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen . |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics . |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.GraphicsPath  i den synliga klippregionen för den angivna  com.aspose.psd.graphics . |
| [isVisible(int x, int y)](#isVisible-int-int-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Anger om den angivna punkten ligger inom detta  com.aspose.psd.GraphicsPath , med den angivna  com.aspose.psd.graphics . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Tar bort en figur. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Tar bort figurer. |
| [reset()](#reset--) | Tömmer grafikvägen och sätter  com.aspose.psd.FillMode  till  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Vänder ordningen på figurer, former och punkter i varje form av detta  com.aspose.psd.graphicsPath . |
| [setFillMode(int value)](#setFillMode-int-) | Ställer in en  com.aspose.psd.FillMode ‑enumeration som bestämmer hur innanmålen av former i detta  com.aspose.psd.GraphicsPath  fylls. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Lägger till en extra kontur till vägen. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Lägger till en extra kontur till  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Ersätter detta  com.aspose.psd.GraphicsPath  med kurvor som omsluter området som fylls när denna väg ritas med den angivna pennan. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initierar en ny instans av  GraphicsPath  klassen.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initierar en ny instans av  GraphicsPath  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figurerna att initiera från. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initierar en ny instans av  GraphicsPath  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figurerna att initiera från. |
| fillMode | int | Fyllningsläget. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initierar en ny instans av  GraphicsPath  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillMode | int | Fyllningsläget. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Lägger till en ny figur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Figuren att lägga till. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Lägger till nya figurer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figurerna att lägga till. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Lägger till den angivna  com.aspose.psd.GraphicsPath  till denna sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den  com.aspose.psd.GraphicsPath  att lägga till. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Lägger till den angivna  com.aspose.psd.GraphicsPath  till denna sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den  com.aspose.psd.GraphicsPath  att lägga till. |
| connect | boolean | Ett Boolean‑värde som anger om den första figuren i den tillagda vägen är en del av den sista figuren i denna väg. Ett värde av true anger att den första figuren i den tillagda vägen är en del av den sista figuren i denna väg. Ett värde av false anger att den första figuren i den tillagda vägen är separat från den sista figuren i denna väg. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Utför en djup kloning av denna grafikbana.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Konverterar varje kurva i denna bana till en sekvens av sammanlänkade linjesegment.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Tillämpar den angivna transformen och konverterar sedan varje kurva i denna  com.aspose.psd.GraphicsPath  till en sekvens av sammanlänkade linjesegment.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | En  com.aspose.psd.Matrix  som används för att transformera detta  com.aspose.psd.GraphicsPath  före plattning. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Konverterar varje kurva i denna  com.aspose.psd.GraphicsPath  till en sekvens av sammanlänkade linjesegment.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | En  com.aspose.psd.Matrix  som används för att transformera detta  com.aspose.psd.GraphicsPath  före plattning. |
| flatness | float | Anger det maximalt tillåtna felet mellan kurvan och dess plattade approximation. Ett värde på 0.25 är standard. Att minska flatness‑värdet ökar antalet linjesegment i approximationen. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar eller anger objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrisen att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrisen att tillämpa innan gränser beräknas. |
| pen | [Pen](../../com.aspose.psd/pen) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

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


Hämtar banafigurerna.

**Returns:**
com.aspose.psd.Figure[] - Vägfigurerna.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Hämtar en  com.aspose.psd.FillMode  enumeration som bestämmer hur innanmålen av former i denna  com.aspose.psd.GraphicsPath  fylls.

**Returns:**
int - Fyllningsläget. En  com.aspose.psd.FillMode  enumeration som specificerar hur interiören av former i detta  com.aspose.psd.GraphicsPath  fylls.
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


Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | En  com.aspose.psd.Point  som specificerar platsen att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | En  com.aspose.psd.Point  som specificerar platsen att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta  com.aspose.psd.GraphicsPath  som ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | En  com.aspose.psd.PointF  som specificerar platsen att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | En  com.aspose.psd.PointF  som specificerar platsen att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom (under) konturen av detta  com.aspose.psd.GraphicsPath  som ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten att testa. |
| y | float | Y-koordinaten för punkten att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten att testa. |
| y | float | Y-koordinaten för punkten att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom (under) konturen av detta  com.aspose.psd.GraphicsPath  som ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Anger om den angivna punkten finns inom (under) konturen av denna  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten att testa. |
| y | int | Y-koordinaten för punkten att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Anger om den angivna punkten ligger inom (under) konturen av detta  com.aspose.psd.GraphicsPath  när den ritas med den angivna  com.aspose.psd.Pen  och med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten att testa. |
| y | int | Y-koordinaten för punkten att testa. |
| pen | [Pen](../../com.aspose.psd/pen) | Den  com.aspose.psd.Pen  att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta  com.aspose.psd.GraphicsPath  som ritas med den angivna  com.aspose.psd.Pen ; annars false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | En  com.aspose.psd.Point  som representerar punkten att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta  com.aspose.psd.GraphicsPath ; annars false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | En  com.aspose.psd.Point  som representerar punkten att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta  com.aspose.psd.GraphicsPath ; annars false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | En  com.aspose.psd.PointF  som representerar punkten att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta  com.aspose.psd.GraphicsPath ; annars false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | En  com.aspose.psd.PointF  som representerar punkten att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta; annars false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten att testa. |
| y | float | Y-koordinaten för punkten att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta  com.aspose.psd.GraphicsPath ; annars false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.GraphicsPath  i den synliga klippregionen för den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten att testa. |
| y | float | Y-koordinaten för punkten att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta  com.aspose.psd.GraphicsPath ; annars false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten att testa. |
| y | int | Y-koordinaten för punkten att testa. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta  com.aspose.psd.GraphicsPath ; annars false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Anger om den angivna punkten ligger inom detta  com.aspose.psd.GraphicsPath , med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten att testa. |
| y | int | Y-koordinaten för punkten att testa. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Den  com.aspose.psd.Graphics  för vilken synlighet ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta  com.aspose.psd.GraphicsPath ; annars false.
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


Tar bort en figur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Figuren att ta bort. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Tar bort figurer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figurerna att ta bort. |

### reset() {#reset--}
```
public void reset()
```


Tömmer grafikvägen och sätter  com.aspose.psd.FillMode  till  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Vänder ordningen på figurer, former och punkter i varje form av detta  com.aspose.psd.graphicsPath .

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Ställer in en  com.aspose.psd.FillMode ‑enumeration som bestämmer hur innanmålen av former i detta  com.aspose.psd.GraphicsPath  fylls.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Fyllningsläget. |

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


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Transformationen att tillämpa. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | En array av  com.aspose.psd.PointF  strukturer som definierar ett parallellogram till vilket rektangeln definierad av  srcRect  transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | En  com.aspose.psd.RectangleF  som representerar rektangeln som transformeras till parallellogrammet definierat av  destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | En array av  com.aspose.psd.PointF  strukturer som definierar ett parallellogram till vilket rektangeln definierad av  srcRect  transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | En  com.aspose.psd.RectangleF  som representerar rektangeln som transformeras till parallellogrammet definierat av  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | En  com.aspose.psd.Matrix  som specificerar en geometrisk transformation att tillämpa på vägen. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | En array av  com.aspose.psd.PointF  strukturer som definierar ett parallellogram till vilket rektangeln definierad av  srcRect  transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | En  com.aspose.psd.RectangleF  som representerar rektangeln som transformeras till parallellogrammet definierat av  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | En  com.aspose.psd.Matrix  som specificerar en geometrisk transformation att tillämpa på vägen. |
| warpMode | int | En  com.aspose.psd.WarpMode  enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilinjär‑läge. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | En array av  com.aspose.psd.PointF  strukturer som definierar ett parallellogram till vilket rektangeln definierad av  srcRect  transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | En  com.aspose.psd.RectangleF  som representerar rektangeln som transformeras till parallellogrammet definierat av  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | En  com.aspose.psd.Matrix  som specificerar en geometrisk transformation att tillämpa på vägen. |
| warpMode | int | En  com.aspose.psd.WarpMode  enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilinjär‑läge. |
| flatness | float | Ett värde från 0 till 1 som specificerar hur platt den resulterande vägen är. För mer information, se metoderna  com.aspose.psd.GraphicsPath.flatten . |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Lägger till en extra kontur till vägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | En  com.aspose.psd.Pen  som specificerar bredden mellan den ursprungliga konturen av vägen och den nya kontur som denna metod skapar. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Lägger till en extra kontur till  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | En  com.aspose.psd.Pen  som specificerar bredden mellan den ursprungliga konturen av vägen och den nya kontur som denna metod skapar. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | En  com.aspose.psd.Matrix  som specificerar en transformation att tillämpa på vägen innan den breddas. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Ersätter detta  com.aspose.psd.GraphicsPath  med kurvor som omsluter området som fylls när denna väg ritas med den angivna pennan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | En  com.aspose.psd.Pen  som specificerar bredden mellan den ursprungliga konturen av vägen och den nya kontur som denna metod skapar. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | En  com.aspose.psd.Matrix  som specificerar en transformation att tillämpa på vägen innan den breddas. |
| flatness | float | Ett värde som specificerar plattheten för kurvor. |

