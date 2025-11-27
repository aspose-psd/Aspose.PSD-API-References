---
title: Region
second_title: Aspose.PSD for Java API Reference
description: Describes the interior of a graphics shape composed of rectangles and paths.
type: docs
weight: 90
url: /java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [Region()](#Region--) | Initializes a new  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Initializes a new  T:Aspose.Imaging.Region  from the specified  T:Aspose.Imaging.RectangleF  structure. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Initializes a new  T:Aspose.Imaging.Region  from the specified  T:Aspose.Imaging.Rectangle  structure. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Initializes a new  T:Aspose.Imaging.Region  with the specified  T:Aspose.Imaging.GraphicsPath . |
## Methods

| Method | Description |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.GraphicsPath  that does not intersect with this  com.aspose.psd.region . |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.Rectangle  structure that does not intersect with this  com.aspose.psd.region . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.RectangleF  structure that does not intersect with this  com.aspose.psd.region . |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.Region  that does not intersect with this  com.aspose.psd.region . |
| [deepClone()](#deepClone--) | Creates an exact deep copy of this  com.aspose.psd.region . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.graphicsPath . |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.Rectangle  structure. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.RectangleF  structure. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.region . |
| [getActions_internalized()](#getActions-internalized--) | Gets the region actions. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.graphicsPath . |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.Rectangle  structure. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.RectangleF  structure. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.region . |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Tests whether this  com.aspose.psd.Region  has an empty interior on the specified drawing surface. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Tests whether the specified  com.aspose.psd.Region  is identical to this  com.aspose.psd.Region  on the specified drawing surface. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Tests whether this  com.aspose.psd.Region  has an infinite interior on the specified drawing surface. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Tests whether the specified  com.aspose.psd.Point  structure is contained within this  com.aspose.psd.region . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Tests whether the specified  com.aspose.psd.Point  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Tests whether the specified  com.aspose.psd.PointF  structure is contained within this  com.aspose.psd.region . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Tests whether the specified  com.aspose.psd.PointF  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics . |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Tests whether any portion of the specified  com.aspose.psd.Rectangle  structure is contained within this  com.aspose.psd.region . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Tests whether any portion of the specified  com.aspose.psd.Rectangle  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics . |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Tests whether any portion of the specified  com.aspose.psd.RectangleF  structure is contained within this  com.aspose.psd.region . |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Tests whether any portion of the specified  com.aspose.psd.RectangleF  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Tests whether the specified point is contained within this  com.aspose.psd.region . |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Tests whether the specified point is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics . |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics . |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Tests whether the specified point is contained within this  com.aspose.psd.Region  object when drawn using the specified  com.aspose.psd.Graphics  object. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics . |
| [makeEmpty()](#makeEmpty--) | Initializes this  com.aspose.psd.Region  to an empty interior. |
| [makeInfinite()](#makeInfinite--) | Initializes this  com.aspose.psd.Region  object to an infinite interior. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Gets or sets the on change region. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Transforms this  com.aspose.psd.Region  by the specified  com.aspose.psd.matrix . |
| [translate(float dx, float dy)](#translate-float-float-) | Offsets the coordinates of this  com.aspose.psd.Region  by the specified amount. |
| [translate(int dx, int dy)](#translate-int-int-) | Offsets the coordinates of this  com.aspose.psd.Region  by the specified amount. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.graphicsPath . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.Rectangle  structure. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.RectangleF  structure. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.region . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.graphicsPath . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.Rectangle  structure. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.RectangleF  structure. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.region . |
### Region() {#Region--}
```
public Region()
```


Initializes a new  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Initializes a new  T:Aspose.Imaging.Region  from the specified  T:Aspose.Imaging.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | A  T:Aspose.Imaging.RectangleF  structure that defines the interior of the new  T:Aspose.Imaging.Region . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Initializes a new  T:Aspose.Imaging.Region  from the specified  T:Aspose.Imaging.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | A  T:Aspose.Imaging.Rectangle  structure that defines the interior of the new  T:Aspose.Imaging.Region . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initializes a new  T:Aspose.Imaging.Region  with the specified  T:Aspose.Imaging.GraphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | A  T:Aspose.Imaging.GraphicsPath  that defines the new  T:Aspose.Imaging.Region . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.GraphicsPath  that does not intersect with this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  com.aspose.psd.GraphicsPath  to complement this  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.Rectangle  structure that does not intersect with this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to complement this  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.RectangleF  structure that does not intersect with this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to complement this  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Updates this  com.aspose.psd.Region  to contain the portion of the specified  com.aspose.psd.Region  that does not intersect with this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | The  com.aspose.psd.Region  object to complement this  com.aspose.psd.Region  object. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Creates an exact deep copy of this  com.aspose.psd.region .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  com.aspose.psd.GraphicsPath  to exclude from this  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to exclude from this  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to exclude from this  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Updates this  com.aspose.psd.Region  to contain only the portion of its interior that does not intersect with the specified  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | The  com.aspose.psd.Region  to exclude from this  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Gets the region actions.

**Returns:**
com.aspose.internal.RegionAction[] - The region actions.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  com.aspose.psd.GraphicsPath  to intersect with this  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to intersect with this  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to intersect with this  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Updates this  com.aspose.psd.Region  to the intersection of itself with the specified  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | The  com.aspose.psd.Region  to intersect with this  com.aspose.psd.region . |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Tests whether this  com.aspose.psd.Region  has an empty interior on the specified drawing surface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a drawing surface. |

**Returns:**
boolean - true if the interior of this  com.aspose.psd.Region  is empty when the transformation associated with  g  is applied; otherwise, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Tests whether the specified  com.aspose.psd.Region  is identical to this  com.aspose.psd.Region  on the specified drawing surface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | The  com.aspose.psd.Region  to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a drawing surface. |

**Returns:**
boolean - True if the interior of region is identical to the interior of this region when the transformation associated with the  g  parameter is applied; otherwise, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Tests whether this  com.aspose.psd.Region  has an infinite interior on the specified drawing surface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a drawing surface. |

**Returns:**
boolean - true if the interior of this  com.aspose.psd.Region  is infinite when the transformation associated with  g  is applied; otherwise, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Tests whether the specified  com.aspose.psd.Point  structure is contained within this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  com.aspose.psd.Point  structure to test. |

**Returns:**
boolean - true when  point  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Tests whether the specified  com.aspose.psd.Point  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  com.aspose.psd.Point  structure to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - true when  point  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Tests whether the specified  com.aspose.psd.PointF  structure is contained within this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  structure to test. |

**Returns:**
boolean - true when  point  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Tests whether the specified  com.aspose.psd.PointF  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  structure to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - true when  point  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Tests whether any portion of the specified  com.aspose.psd.Rectangle  structure is contained within this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to test. |

**Returns:**
boolean - This method returns true when any portion of  rect  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Tests whether any portion of the specified  com.aspose.psd.Rectangle  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - true when any portion of the  rect  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Tests whether any portion of the specified  com.aspose.psd.RectangleF  structure is contained within this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to test. |

**Returns:**
boolean - true when any portion of  rect  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Tests whether any portion of the specified  com.aspose.psd.RectangleF  structure is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - true when  rect  is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Tests whether the specified point is contained within this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns:**
boolean - True when the specified point is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Tests whether the specified point is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - True when the specified point is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this  com.aspose.psd.Region  object; otherwise, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Tests whether the specified point is contained within this  com.aspose.psd.Region  object when drawn using the specified  com.aspose.psd.Graphics  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - true when the specified point is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this  com.aspose.psd.Region ; otherwise, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Tests whether any portion of the specified rectangle is contained within this  com.aspose.psd.Region  when drawn using the specified  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |
| g | [Graphics](../../com.aspose.psd/graphics) | A  com.aspose.psd.Graphics  that represents a graphics context. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this  com.aspose.psd.Region ; otherwise, false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initializes this  com.aspose.psd.Region  to an empty interior.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initializes this  com.aspose.psd.Region  object to an infinite interior.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


Gets or sets the on change region.

Value: The on change region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


Transforms this  com.aspose.psd.Region  by the specified  com.aspose.psd.matrix .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The  com.aspose.psd.Matrix  by which to transform this  com.aspose.psd.region . |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Offsets the coordinates of this  com.aspose.psd.Region  by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The amount to offset this  com.aspose.psd.Region  horizontally. |
| dy | float | The amount to offset this  com.aspose.psd.Region  vertically. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Offsets the coordinates of this  com.aspose.psd.Region  by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | int | The amount to offset this  com.aspose.psd.Region  horizontally. |
| dy | int | The amount to offset this  com.aspose.psd.Region  vertically. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  com.aspose.psd.GraphicsPath  to unite with this  com.aspose.psd.region . |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to unite with this  com.aspose.psd.region . |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to unite with this  com.aspose.psd.region . |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Updates this  com.aspose.psd.Region  to the union of itself and the specified  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | The  com.aspose.psd.Region  to unite with this  com.aspose.psd.region . |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  com.aspose.psd.GraphicsPath  to xor with this  com.aspose.psd.region . |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to xor with this  com.aspose.psd.region . |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to xor with this  com.aspose.psd.region . |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Updates this  com.aspose.psd.Region  to the union minus the intersection of itself with the specified  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | The  com.aspose.psd.Region  to xor with this  com.aspose.psd.region . |

