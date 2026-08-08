---
title: "Region"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Beschrijft het interieur van een grafische vorm die bestaat uit rechthoeken en paden."
type: docs
weight: 90
url: /nl/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Beschrijft het binnenste van een grafische vorm samengesteld uit rechthoeken en paden. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Region()](#Region--) | Initialiseert een nieuwe  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Initialiseert een nieuwe  T:Aspose.Imaging.Region  vanuit de opgegeven  T:Aspose.Imaging.RectangleF  structuur. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Initialiseert een nieuwe  T:Aspose.Imaging.Region  vanuit de opgegeven  T:Aspose.Imaging.Rectangle  structuur. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Initialiseert een nieuwe  T:Aspose.Imaging.Region  met het opgegeven  T:Aspose.Imaging.GraphicsPath . |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Werk dit  com.aspose.psd.Region  bij zodat het het gedeelte bevat van de opgegeven  com.aspose.psd.GraphicsPath  dat niet overlapt met dit  com.aspose.psd.region . |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Werk dit  com.aspose.psd.Region  bij zodat het het gedeelte bevat van de opgegeven  com.aspose.psd.Rectangle  structuur die niet overlapt met dit  com.aspose.psd.region . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Werkt dit  com.aspose.psd.Region  bij om het gedeelte van de opgegeven  com.aspose.psd.RectangleF  structuur te bevatten dat niet intersecteert met dit  com.aspose.psd.region . |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Werkt dit  com.aspose.psd.Region  bij om het gedeelte van de opgegeven  com.aspose.psd.Region  dat niet intersecteert met dit  com.aspose.psd.region  te bevatten. |
| [deepClone()](#deepClone--) | Maakt een exacte diepe kopie van dit  com.aspose.psd.region . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met het opgegeven  com.aspose.psd.graphicsPath . |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met de opgegeven  com.aspose.psd.Rectangle  structuur. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met de opgegeven  com.aspose.psd.RectangleF  structuur. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met de opgegeven  com.aspose.psd.region . |
| [getActions_internalized()](#getActions-internalized--) | Haalt de regio-acties op. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met het opgegeven  com.aspose.psd.graphicsPath . |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met de opgegeven  com.aspose.psd.Rectangle  structuur. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met de opgegeven  com.aspose.psd.RectangleF  structuur. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met de opgegeven  com.aspose.psd.region . |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Test of dit  com.aspose.psd.Region  een lege binnenkant heeft op het opgegeven tekenoppervlak. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Test of de opgegeven  com.aspose.psd.Region  identiek is aan dit  com.aspose.psd.Region  op het opgegeven tekenoppervlak. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Test of dit  com.aspose.psd.Region  een oneindige binnenkant heeft op het opgegeven tekenoppervlak. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Test of de opgegeven  com.aspose.psd.Point  structuur zich bevindt binnen dit  com.aspose.psd.region . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Test of de opgegeven  com.aspose.psd.Point  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Test of de opgegeven  com.aspose.psd.PointF  structuur zich bevindt binnen dit  com.aspose.psd.region . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Test of de opgegeven  com.aspose.psd.PointF  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics . |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Test of een deel van de opgegeven  com.aspose.psd.Rectangle  structuur zich bevindt binnen dit  com.aspose.psd.region . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Test of een deel van de opgegeven  com.aspose.psd.Rectangle  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics . |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Test of een deel van de opgegeven  com.aspose.psd.RectangleF  structuur zich bevindt binnen dit  com.aspose.psd.region . |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Test of een deel van de opgegeven  com.aspose.psd.RectangleF  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Test of het opgegeven punt zich bevindt binnen dit  com.aspose.psd.region . |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Test of het opgegeven punt zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics . |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics . |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Test of het opgegeven punt zich bevindt binnen dit  com.aspose.psd.Region  object wanneer getekend met het opgegeven  com.aspose.psd.Graphics  object. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics . |
| [makeEmpty()](#makeEmpty--) | Initialiseert dit  com.aspose.psd.Region  met een lege binnenkant. |
| [makeInfinite()](#makeInfinite--) | Initialiseert dit  com.aspose.psd.Region  object met een oneindige binnenkant. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Haalt op of stelt de regio bij wijziging in. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Transformeert dit  com.aspose.psd.Region  met de opgegeven  com.aspose.psd.matrix . |
| [translate(float dx, float dy)](#translate-float-float-) | Verschuift de coördinaten van dit  com.aspose.psd.Region  met de opgegeven hoeveelheid. |
| [translate(int dx, int dy)](#translate-int-int-) | Verschuift de coördinaten van dit  com.aspose.psd.Region  met de opgegeven hoeveelheid. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en het opgegeven  com.aspose.psd.graphicsPath . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en de opgegeven  com.aspose.psd.Rectangle  structuur. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en de opgegeven  com.aspose.psd.RectangleF  structuur. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en de opgegeven  com.aspose.psd.region . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met het opgegeven  com.aspose.psd.graphicsPath . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met de opgegeven  com.aspose.psd.Rectangle  structuur. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met de opgegeven  com.aspose.psd.RectangleF  structuur. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met de opgegeven  com.aspose.psd.region . |
### Region() {#Region--}
```
public Region()
```


Initialiseert een nieuwe  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Initialiseert een nieuwe  T:Aspose.Imaging.Region  vanuit de opgegeven  T:Aspose.Imaging.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Een  T:Aspose.Imaging.RectangleF  structuur die de binnenkant van de nieuwe  T:Aspose.Imaging.Region  definieert. |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Initialiseert een nieuwe  T:Aspose.Imaging.Region  vanuit de opgegeven  T:Aspose.Imaging.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Een  T:Aspose.Imaging.Rectangle  structuur die de binnenkant van de nieuwe  T:Aspose.Imaging.Region  definieert. |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialiseert een nieuwe  T:Aspose.Imaging.Region  met het opgegeven  T:Aspose.Imaging.GraphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Een  T:Aspose.Imaging.GraphicsPath  die de nieuwe  T:Aspose.Imaging.Region  definieert. |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Werk dit  com.aspose.psd.Region  bij zodat het het gedeelte bevat van de opgegeven  com.aspose.psd.GraphicsPath  dat niet overlapt met dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | De  com.aspose.psd.GraphicsPath  om dit  com.aspose.psd.region  aan te vullen. |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Werk dit  com.aspose.psd.Region  bij zodat het het gedeelte bevat van de opgegeven  com.aspose.psd.Rectangle  structuur die niet overlapt met dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur om dit  com.aspose.psd.region  aan te vullen. |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Werkt dit  com.aspose.psd.Region  bij om het gedeelte van de opgegeven  com.aspose.psd.RectangleF  structuur te bevatten dat niet intersecteert met dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur om dit  com.aspose.psd.region  aan te vullen. |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Werkt dit  com.aspose.psd.Region  bij om het gedeelte van de opgegeven  com.aspose.psd.Region  dat niet intersecteert met dit  com.aspose.psd.region  te bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Het  com.aspose.psd.Region  object om dit  com.aspose.psd.Region  object aan te vullen. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Maakt een exacte diepe kopie van dit  com.aspose.psd.region .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met het opgegeven  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | De  com.aspose.psd.GraphicsPath  om uit te sluiten van dit  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met de opgegeven  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur om uit te sluiten van dit  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met de opgegeven  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur om uit te sluiten van deze  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Werkt dit  com.aspose.psd.Region  bij om alleen het gedeelte van zijn binnenkant te bevatten dat niet intersecteert met de opgegeven  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | De  com.aspose.psd.Region  om uit te sluiten van deze  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Haalt de regio-acties op.

**Returns:**
com.aspose.internal.RegionAction[] - De regio‑acties.
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


Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met het opgegeven  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | De  com.aspose.psd.GraphicsPath  om te kruisen met deze  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met de opgegeven  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur om te kruisen met deze  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met de opgegeven  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur om te kruisen met deze  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Werkt dit  com.aspose.psd.Region  bij tot de doorsnede van zichzelf met de opgegeven  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | De  com.aspose.psd.Region  om te kruisen met deze  com.aspose.psd.region . |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Test of dit  com.aspose.psd.Region  een lege binnenkant heeft op het opgegeven tekenoppervlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een tekenoppervlak voorstelt. |

**Returns:**
boolean - true als de binnenkant van deze  com.aspose.psd.Region  leeg is wanneer de transformatie gekoppeld aan  g  wordt toegepast; anders false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Test of de opgegeven  com.aspose.psd.Region  identiek is aan dit  com.aspose.psd.Region  op het opgegeven tekenoppervlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | De  com.aspose.psd.Region  om te testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een tekenoppervlak voorstelt. |

**Returns:**
boolean - True als de binnenkant van de regio identiek is aan de binnenkant van deze regio wanneer de transformatie gekoppeld aan de  g  parameter wordt toegepast; anders false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Test of dit  com.aspose.psd.Region  een oneindige binnenkant heeft op het opgegeven tekenoppervlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een tekenoppervlak voorstelt. |

**Returns:**
boolean - true als de binnenkant van deze  com.aspose.psd.Region  oneindig is wanneer de transformatie gekoppeld aan  g  wordt toegepast; anders false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Test of de opgegeven  com.aspose.psd.Point  structuur zich bevindt binnen dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  com.aspose.psd.Point  structuur om te testen. |

**Returns:**
boolean - true wanneer  point  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Test of de opgegeven  com.aspose.psd.Point  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  com.aspose.psd.Point  structuur om te testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - true wanneer  point  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Test of de opgegeven  com.aspose.psd.PointF  structuur zich bevindt binnen dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | De  com.aspose.psd.PointF  structuur om te testen. |

**Returns:**
boolean - true wanneer  point  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Test of de opgegeven  com.aspose.psd.PointF  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | De  com.aspose.psd.PointF  structuur om te testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - true wanneer  point  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Test of een deel van de opgegeven  com.aspose.psd.Rectangle  structuur zich bevindt binnen dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur om te testen. |

**Returns:**
boolean - Deze methode retourneert true wanneer een deel van  rect  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Test of een deel van de opgegeven  com.aspose.psd.Rectangle  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur om te testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - true wanneer een deel van de  rect  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Test of een deel van de opgegeven  com.aspose.psd.RectangleF  structuur zich bevindt binnen dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur om te testen. |

**Returns:**
boolean - true wanneer een deel van  rect  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Test of een deel van de opgegeven  com.aspose.psd.RectangleF  structuur zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur om te testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - true wanneer  rect  zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Test of het opgegeven punt zich bevindt binnen dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - True wanneer het opgegeven punt zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Test of het opgegeven punt zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - True wanneer het opgegeven punt zich bevindt binnen deze  com.aspose.psd.Region ; anders false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | float | De breedte van de te testen rechthoek. |
| hoogte | float | De hoogte van de te testen rechthoek. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit  com.aspose.psd.Region  object bevindt; anders false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | float | De breedte van de te testen rechthoek. |
| hoogte | float | De hoogte van de te testen rechthoek. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit  com.aspose.psd.Region  bevindt; anders false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Test of het opgegeven punt zich bevindt binnen dit  com.aspose.psd.Region  object wanneer getekend met het opgegeven  com.aspose.psd.Graphics  object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het punt om te testen. |
| y | int | De y-coördinaat van het punt om te testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - true wanneer het opgegeven punt zich binnen dit  com.aspose.psd.Region  bevindt; anders false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | int | De breedte van de te testen rechthoek. |
| hoogte | int | De hoogte van de te testen rechthoek. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit  com.aspose.psd.Region  bevindt; anders false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Test of een deel van de opgegeven rechthoek zich bevindt binnen dit  com.aspose.psd.Region  wanneer getekend met de opgegeven  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| breedte | int | De breedte van de te testen rechthoek. |
| hoogte | int | De hoogte van de te testen rechthoek. |
| g | [Graphics](../../com.aspose.psd/graphics) | Een  com.aspose.psd.Graphics  die een grafische context voorstelt. |

**Returns:**
boolean - true wanneer een deel van de opgegeven rechthoek zich binnen dit  com.aspose.psd.Region  bevindt; anders false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialiseert dit  com.aspose.psd.Region  met een lege binnenkant.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialiseert dit  com.aspose.psd.Region  object met een oneindige binnenkant.

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


Haalt op of stelt de regio bij wijziging in.

Waarde: De regio bij wijziging.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.ChangeActionList |  |

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


Transformeert dit  com.aspose.psd.Region  met de opgegeven  com.aspose.psd.matrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De  com.aspose.psd.Matrix  waarmee deze  com.aspose.psd.region  getransformeerd wordt. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Verschuift de coördinaten van dit  com.aspose.psd.Region  met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De hoeveelheid om deze  com.aspose.psd.Region  horizontaal te verschuiven. |
| dy | float | De hoeveelheid om deze  com.aspose.psd.Region  verticaal te verschuiven. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Verschuift de coördinaten van dit  com.aspose.psd.Region  met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | int | De hoeveelheid om deze  com.aspose.psd.Region  horizontaal te verschuiven. |
| dy | int | De hoeveelheid om deze  com.aspose.psd.Region  verticaal te verschuiven. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en het opgegeven  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | De  com.aspose.psd.GraphicsPath  om te verenigen met deze  com.aspose.psd.region . |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en de opgegeven  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur om te verenigen met deze  com.aspose.psd.region . |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en de opgegeven  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur om te verenigen met deze  com.aspose.psd.region . |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Werk dit  com.aspose.psd.Region  bij naar de unie van zichzelf en de opgegeven  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | De  com.aspose.psd.Region  om te verenigen met deze  com.aspose.psd.region . |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met het opgegeven  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | De  com.aspose.psd.GraphicsPath  om te xor'en met deze  com.aspose.psd.region . |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met de opgegeven  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur om te xor'en met deze  com.aspose.psd.region . |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met de opgegeven  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur om te xor'en met deze  com.aspose.psd.region . |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Werk dit  com.aspose.psd.Region  bij naar de unie min de intersectie van zichzelf met de opgegeven  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | De  com.aspose.psd.Region  om te xor'en met deze  com.aspose.psd.region . |

