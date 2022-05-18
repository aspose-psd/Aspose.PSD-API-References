---
title: Region
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5210
url: /net/aspose.psd/region/
---
## Region class

Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

```csharp
public sealed class Region
```

## Constructors

| Name | Description |
| --- | --- |
| [Region](region)() | Initializes a new [`Region`](../region). |
| [Region](region)(GraphicsPath) | Initializes a new [`Region`](../region) with the specified [`GraphicsPath`](../graphicspath). |
| [Region](region)(Rectangle) | Initializes a new [`Region`](../region) from the specified [`Rectangle`](../rectangle) structure. |
| [Region](region)(RectangleF) | Initializes a new [`Region`](../region) from the specified [`RectangleF`](../rectanglef) structure. |

## Methods

| Name | Description |
| --- | --- |
| [Complement](../../aspose.psd/region/complement)(GraphicsPath) | Updates this [`Region`](../region) to contain the portion of the specified [`GraphicsPath`](../graphicspath) that does not intersect with this [`Region`](../region). |
| [Complement](../../aspose.psd/region/complement)(Rectangle) | Updates this [`Region`](../region) to contain the portion of the specified [`Rectangle`](../rectangle) structure that does not intersect with this [`Region`](../region). |
| [Complement](../../aspose.psd/region/complement)(RectangleF) | Updates this [`Region`](../region) to contain the portion of the specified [`RectangleF`](../rectanglef) structure that does not intersect with this [`Region`](../region). |
| [Complement](../../aspose.psd/region/complement)(Region) | Updates this [`Region`](../region) to contain the portion of the specified [`Region`](../region) that does not intersect with this [`Region`](../region). |
| [DeepClone](../../aspose.psd/region/deepclone)() | Creates an exact deep copy of this [`Region`](../region). |
| [Equals](../../aspose.psd/region/equals)(Region, Graphics) | Tests whether the specified [`Region`](../region) is identical to this [`Region`](../region) on the specified drawing surface. |
| [Exclude](../../aspose.psd/region/exclude)(GraphicsPath) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`GraphicsPath`](../graphicspath). |
| [Exclude](../../aspose.psd/region/exclude)(Rectangle) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`Rectangle`](../rectangle) structure. |
| [Exclude](../../aspose.psd/region/exclude)(RectangleF) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`RectangleF`](../rectanglef) structure. |
| [Exclude](../../aspose.psd/region/exclude)(Region) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`Region`](../region). |
| [Intersect](../../aspose.psd/region/intersect)(GraphicsPath) | Updates this [`Region`](../region) to the intersection of itself with the specified [`GraphicsPath`](../graphicspath). |
| [Intersect](../../aspose.psd/region/intersect)(Rectangle) | Updates this [`Region`](../region) to the intersection of itself with the specified [`Rectangle`](../rectangle) structure. |
| [Intersect](../../aspose.psd/region/intersect)(RectangleF) | Updates this [`Region`](../region) to the intersection of itself with the specified [`RectangleF`](../rectanglef) structure. |
| [Intersect](../../aspose.psd/region/intersect)(Region) | Updates this [`Region`](../region) to the intersection of itself with the specified [`Region`](../region). |
| [IsEmpty](../../aspose.psd/region/isempty)(Graphics) | Tests whether this [`Region`](../region) has an empty interior on the specified drawing surface. |
| [IsInfinite](../../aspose.psd/region/isinfinite)(Graphics) | Tests whether this [`Region`](../region) has an infinite interior on the specified drawing surface. |
| [IsVisible](../../aspose.psd/region/isvisible)(Point) | Tests whether the specified [`Point`](../point) structure is contained within this [`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible)(PointF) | Tests whether the specified [`PointF`](../pointf) structure is contained within this [`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible)(Rectangle) | Tests whether any portion of the specified [`Rectangle`](../rectangle) structure is contained within this [`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible)(RectangleF) | Tests whether any portion of the specified [`RectangleF`](../rectanglef) structure is contained within this [`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible)(float, float) | Tests whether the specified point is contained within this [`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible)(Point, Graphics) | Tests whether the specified [`Point`](../point) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible)(PointF, Graphics) | Tests whether the specified [`PointF`](../pointf) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible)(Rectangle, Graphics) | Tests whether any portion of the specified [`Rectangle`](../rectangle) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible)(RectangleF, Graphics) | Tests whether any portion of the specified [`RectangleF`](../rectanglef) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible)(float, float, Graphics) | Tests whether the specified point is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible)(int, int, Graphics) | Tests whether the specified point is contained within this [`Region`](../region) object when drawn using the specified [`Graphics`](../graphics) object. |
| [IsVisible](../../aspose.psd/region/isvisible)(float, float, float, float) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible)(int, int, int, int) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible)(float, float, float, float, Graphics) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible)(int, int, int, int, Graphics) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [MakeEmpty](../../aspose.psd/region/makeempty)() | Initializes this [`Region`](../region) to an empty interior. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite)() | Initializes this [`Region`](../region) object to an infinite interior. |
| [Transform](../../aspose.psd/region/transform)(Matrix) | Transforms this [`Region`](../region) by the specified [`Matrix`](../matrix). |
| [Translate](../../aspose.psd/region/translate)(float, float) | Offsets the coordinates of this [`Region`](../region) by the specified amount. |
| [Translate](../../aspose.psd/region/translate)(int, int) | Offsets the coordinates of this [`Region`](../region) by the specified amount. |
| [Union](../../aspose.psd/region/union)(GraphicsPath) | Updates this [`Region`](../region) to the union of itself and the specified [`GraphicsPath`](../graphicspath). |
| [Union](../../aspose.psd/region/union)(Rectangle) | Updates this [`Region`](../region) to the union of itself and the specified [`Rectangle`](../rectangle) structure. |
| [Union](../../aspose.psd/region/union)(RectangleF) | Updates this [`Region`](../region) to the union of itself and the specified [`RectangleF`](../rectanglef) structure. |
| [Union](../../aspose.psd/region/union)(Region) | Updates this [`Region`](../region) to the union of itself and the specified [`Region`](../region). |
| [Xor](../../aspose.psd/region/xor)(GraphicsPath) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`GraphicsPath`](../graphicspath). |
| [Xor](../../aspose.psd/region/xor)(Rectangle) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`Rectangle`](../rectangle) structure. |
| [Xor](../../aspose.psd/region/xor)(RectangleF) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`RectangleF`](../rectanglef) structure. |
| [Xor](../../aspose.psd/region/xor)(Region) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`Region`](../region). |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
