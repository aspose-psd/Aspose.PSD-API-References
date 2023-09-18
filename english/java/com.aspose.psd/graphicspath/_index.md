---
title: GraphicsPath
second_title: Aspose.PSD for Java API Reference
description: Represents a series of connected lines and curves.
type: docs
weight: 50
url: /java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Represents a series of connected lines and curves. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initializes a new instance of the  GraphicsPath  class. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Initializes a new instance of the  GraphicsPath  class. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Initializes a new instance of the  GraphicsPath  class. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initializes a new instance of the  GraphicsPath  class. |
## Methods

| Method | Description |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Adds a new figure. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Adds new figures. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Appends the specified  com.aspose.psd.GraphicsPath  to this path. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Appends the specified  com.aspose.psd.GraphicsPath  to this path. |
| [deepClone()](#deepClone--) | Performs a deep clone of this graphics path. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Converts each curve in this path into a sequence of connected line segments. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Applies the specified transform and then converts each curve in this  com.aspose.psd.GraphicsPath  into a sequence of connected line segments. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Converts each curve in this  com.aspose.psd.GraphicsPath  into a sequence of connected line segments. |
| [getBounds()](#getBounds--) | Gets or sets the object's bounds. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Gets the object's bounds. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Gets the path figures. |
| [getFillMode()](#getFillMode--) | Gets a  com.aspose.psd.FillMode  enumeration that determines how the interiors of shapes in this  com.aspose.psd.GraphicsPath  are filled. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen . |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics . |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen . |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics . |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen . |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics . |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen . |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics . |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within this  com.aspose.psd.GraphicsPath  in the visible clip region of the specified  com.aspose.psd.graphics . |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Indicates whether the specified point is contained within this  com.aspose.psd.GraphicsPath , using the specified  com.aspose.psd.graphics . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Removes a figure. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Removes figures. |
| [reset()](#reset--) | Empties the graphics path and sets the  com.aspose.psd.FillMode  to  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Reverses the order of figures, shapes, and points in each shape of this  com.aspose.psd.graphicsPath . |
| [setFillMode(int value)](#setFillMode-int-) | Sets a  com.aspose.psd.FillMode  enumeration that determines how the interiors of shapes in this  com.aspose.psd.GraphicsPath  are filled. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applies the specified transformation to the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Adds an additional outline to the path. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Adds an additional outline to the  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Replaces this  com.aspose.psd.GraphicsPath  with curves that enclose the area that is filled when this path is drawn by the specified pen. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initializes a new instance of the  GraphicsPath  class.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initializes a new instance of the  GraphicsPath  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | The figures to initialize from. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initializes a new instance of the  GraphicsPath  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | The figures to initialize from. |
| fillMode | int | The fill mode. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initializes a new instance of the  GraphicsPath  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | int | The fill mode. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Adds a new figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | The figure to add. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Adds new figures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | The figures to add. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Appends the specified  com.aspose.psd.GraphicsPath  to this path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  com.aspose.psd.GraphicsPath  to add. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Appends the specified  com.aspose.psd.GraphicsPath  to this path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  com.aspose.psd.GraphicsPath  to add. |
| connect | boolean | A Boolean value that specifies whether the first figure in the added path is part of the last figure in this path. A value of true specifies that the first figure in the added path is part of the last figure in this path. A value of false specifies that the first figure in the added path is separate from the last figure in this path. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Performs a deep clone of this graphics path.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Converts each curve in this path into a sequence of connected line segments.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Applies the specified transform and then converts each curve in this  com.aspose.psd.GraphicsPath  into a sequence of connected line segments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | A  com.aspose.psd.Matrix  by which to transform this  com.aspose.psd.GraphicsPath  before flattening. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Converts each curve in this  com.aspose.psd.GraphicsPath  into a sequence of connected line segments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | A  com.aspose.psd.Matrix  by which to transform this  com.aspose.psd.GraphicsPath  before flattening. |
| flatness | float | Specifies the maximum permitted error between the curve and its flattened approximation. A value of 0.25 is the default. Reducing the flatness value will increase the number of line segments in the approximation. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets or sets the object's bounds.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](../../com.aspose.psd/pen) | The pen to use for object. This can influence the object's bounds size. |

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


Gets the path figures.

**Returns:**
com.aspose.psd.Figure[] - The path figures.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Gets a  com.aspose.psd.FillMode  enumeration that determines how the interiors of shapes in this  com.aspose.psd.GraphicsPath  are filled.

**Returns:**
int - The fill mode. A  com.aspose.psd.FillMode  enumeration that specifies how the interiors of shapes in this  com.aspose.psd.GraphicsPath  are filled.
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


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | A  com.aspose.psd.Point  that specifies the location to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | A  com.aspose.psd.Point  that specifies the location to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this  com.aspose.psd.GraphicsPath  as drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | A  com.aspose.psd.PointF  that specifies the location to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | A  com.aspose.psd.PointF  that specifies the location to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  as drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  as drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this  com.aspose.psd.GraphicsPath  when drawn with the specified  com.aspose.psd.Pen  and using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.psd/pen) | The  com.aspose.psd.Pen  to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this  com.aspose.psd.GraphicsPath  as drawn with the specified  com.aspose.psd.Pen ; otherwise, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | A  com.aspose.psd.Point  that represents the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this  com.aspose.psd.GraphicsPath ; otherwise, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | A  com.aspose.psd.Point  that represents the point to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this  com.aspose.psd.GraphicsPath ; otherwise, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | A  com.aspose.psd.PointF  that represents the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this  com.aspose.psd.GraphicsPath ; otherwise, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | A  com.aspose.psd.PointF  that represents the point to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this; otherwise, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this  com.aspose.psd.GraphicsPath ; otherwise, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indicates whether the specified point is contained within this  com.aspose.psd.GraphicsPath  in the visible clip region of the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this  com.aspose.psd.GraphicsPath ; otherwise, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indicates whether the specified point is contained within this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this  com.aspose.psd.GraphicsPath ; otherwise, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indicates whether the specified point is contained within this  com.aspose.psd.GraphicsPath , using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | The  com.aspose.psd.Graphics  for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this  com.aspose.psd.GraphicsPath ; otherwise, false.
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


Removes a figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | The figure to remove. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Removes figures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | The figures to remove. |

### reset() {#reset--}
```
public void reset()
```


Empties the graphics path and sets the  com.aspose.psd.FillMode  to  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Reverses the order of figures, shapes, and points in each shape of this  com.aspose.psd.graphicsPath .

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Sets a  com.aspose.psd.FillMode  enumeration that determines how the interiors of shapes in this  com.aspose.psd.GraphicsPath  are filled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The fill mode. |

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


Applies the specified transformation to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | The transformation to apply. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | An array of  com.aspose.psd.PointF  structures that define a parallelogram to which the rectangle defined by  srcRect  is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | A  com.aspose.psd.RectangleF  that represents the rectangle that is transformed to the parallelogram defined by  destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | An array of  com.aspose.psd.PointF  structures that define a parallelogram to which the rectangle defined by  srcRect  is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | A  com.aspose.psd.RectangleF  that represents the rectangle that is transformed to the parallelogram defined by  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | A  com.aspose.psd.Matrix  that specifies a geometric transform to apply to the path. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | An array of  com.aspose.psd.PointF  structures that defines a parallelogram to which the rectangle defined by  srcRect  is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | A  com.aspose.psd.RectangleF  that represents the rectangle that is transformed to the parallelogram defined by  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | A  com.aspose.psd.Matrix  that specifies a geometric transform to apply to the path. |
| warpMode | int | A  com.aspose.psd.WarpMode  enumeration that specifies whether this warp operation uses perspective or bilinear mode. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | An array of  com.aspose.psd.PointF  structures that define a parallelogram to which the rectangle defined by  srcRect  is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | A  com.aspose.psd.RectangleF  that represents the rectangle that is transformed to the parallelogram defined by  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | A  com.aspose.psd.Matrix  that specifies a geometric transform to apply to the path. |
| warpMode | int | A  com.aspose.psd.WarpMode  enumeration that specifies whether this warp operation uses perspective or bilinear mode. |
| flatness | float | A value from 0 through 1 that specifies how flat the resulting path is. For more information, see the  com.aspose.psd.GraphicsPath.flatten  methods. |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Adds an additional outline to the path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | A  com.aspose.psd.Pen  that specifies the width between the original outline of the path and the new outline this method creates. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Adds an additional outline to the  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | A  com.aspose.psd.Pen  that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | A  com.aspose.psd.Matrix  that specifies a transform to apply to the path before widening. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Replaces this  com.aspose.psd.GraphicsPath  with curves that enclose the area that is filled when this path is drawn by the specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | A  com.aspose.psd.Pen  that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | A  com.aspose.psd.Matrix  that specifies a transform to apply to the path before widening. |
| flatness | float | A value that specifies the flatness for curves. |

