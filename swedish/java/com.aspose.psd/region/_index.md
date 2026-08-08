---
title: "Region"
second_title: "Aspose.PSD för Java API-referens"
description: "Beskriver insidan av en grafisk form bestående av rektanglar och banor."
type: docs
weight: 90
url: /sv/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Beskriver insidan av en grafisk form bestående av rektanglar och banor. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Region()](#Region--) | Initierar en ny  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Initierar en ny  T:Aspose.Imaging.Region  från den angivna  T:Aspose.Imaging.RectangleF  strukturen. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Initierar en ny  T:Aspose.Imaging.Region  från den angivna  T:Aspose.Imaging.Rectangle  strukturen. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Initierar en ny  T:Aspose.Imaging.Region  med den angivna  T:Aspose.Imaging.GraphicsPath . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.GraphicsPath  som inte skär detta  com.aspose.psd.region . |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.Rectangle  strukturen som inte skär med detta  com.aspose.psd.region . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.RectangleF  strukturen som inte skär med detta  com.aspose.psd.region . |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.Region  som inte skär med detta  com.aspose.psd.region . |
| [deepClone()](#deepClone--) | Skapar en exakt djup kopia av detta  com.aspose.psd.region . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.graphicsPath . |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.Rectangle  strukturen. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.RectangleF  strukturen. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.region . |
| [getActions_internalized()](#getActions-internalized--) | Hämtar regionens åtgärder. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.graphicsPath . |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.Rectangle  strukturen. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.RectangleF  strukturen. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.region . |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Testar om detta  com.aspose.psd.Region  har ett tomt inre på den angivna ritytan. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Testar om den angivna  com.aspose.psd.Region  är identisk med detta  com.aspose.psd.Region  på den angivna ritytan. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Testar om detta  com.aspose.psd.Region  har ett oändligt inre på den angivna ritytan. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Testar om den angivna  com.aspose.psd.Point  strukturen finns inom detta  com.aspose.psd.region . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Testar om den angivna  com.aspose.psd.Point  strukturen finns inom detta  com.aspose.psd.Region  när den ritas med den angivna  com.aspose.psd.graphics . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Testar om den angivna  com.aspose.psd.PointF  strukturen finns inom detta  com.aspose.psd.region . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Testar om den angivna  com.aspose.psd.PointF  strukturen finns inom detta  com.aspose.psd.Region  när den ritas med den angivna  com.aspose.psd.graphics . |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Testar om någon del av den angivna  com.aspose.psd.Rectangle  strukturen finns inom detta  com.aspose.psd.region . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Testar om någon del av den angivna  com.aspose.psd.Rectangle  strukturen finns inom detta  com.aspose.psd.Region  när den ritas med den angivna  com.aspose.psd.graphics . |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Testar om någon del av den angivna  com.aspose.psd.RectangleF  strukturen finns inom detta  com.aspose.psd.region . |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Testar om någon del av den angivna com.aspose.psd.RectangleF strukturen finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Testar om den angivna punkten finns inom detta com.aspose.psd.region . |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Testar om den angivna punkten finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics . |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Testar om någon del av den angivna rektangeln finns inom detta com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Testar om någon del av den angivna rektangeln finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics . |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Testar om den angivna punkten finns inom detta com.aspose.psd.Region objekt när det ritas med det angivna com.aspose.psd.Graphics objektet. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Testar om någon del av den angivna rektangeln finns inom detta com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Testar om någon del av den angivna rektangeln finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics . |
| [makeEmpty()](#makeEmpty--) | Initierar detta com.aspose.psd.Region till ett tomt inre. |
| [makeInfinite()](#makeInfinite--) | Initierar detta com.aspose.psd.Region objekt till ett oändligt inre. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Hämtar eller anger regionen vid förändring. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Transformerar detta com.aspose.psd.Region med den angivna com.aspose.psd.matrix . |
| [translate(float dx, float dy)](#translate-float-float-) | Förskjuter koordinaterna för detta com.aspose.psd.Region med den angivna mängden. |
| [translate(int dx, int dy)](#translate-int-int-) | Förskjuter koordinaterna för detta com.aspose.psd.Region med den angivna mängden. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.graphicsPath . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.Rectangle strukturen. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.RectangleF strukturen. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.region . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.graphicsPath . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.Rectangle strukturen. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.RectangleF strukturen. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.region . |
### Region() {#Region--}
```
public Region()
```


Initierar en ny  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Initierar en ny  T:Aspose.Imaging.Region  från den angivna  T:Aspose.Imaging.RectangleF  strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | En T:Aspose.Imaging.RectangleF struktur som definierar det inre för den nya T:Aspose.Imaging.Region . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Initierar en ny  T:Aspose.Imaging.Region  från den angivna  T:Aspose.Imaging.Rectangle  strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | En T:Aspose.Imaging.Rectangle struktur som definierar det inre för den nya T:Aspose.Imaging.Region . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initierar en ny  T:Aspose.Imaging.Region  med den angivna  T:Aspose.Imaging.GraphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | En T:Aspose.Imaging.GraphicsPath som definierar den nya T:Aspose.Imaging.Region . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.GraphicsPath  som inte skär detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den com.aspose.psd.GraphicsPath för att komplettera detta com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.Rectangle  strukturen som inte skär med detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den com.aspose.psd.Rectangle strukturen för att komplettera detta com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.RectangleF  strukturen som inte skär med detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den com.aspose.psd.RectangleF strukturen för att komplettera detta com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Uppdaterar detta  com.aspose.psd.Region  så att det innehåller den del av den angivna  com.aspose.psd.Region  som inte skär med detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Den  com.aspose.psd.Region  objektet för att komplettera detta  com.aspose.psd.Region  objektet. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Skapar en exakt djup kopia av detta  com.aspose.psd.region .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den  com.aspose.psd.GraphicsPath  att utesluta från detta  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.Rectangle  strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  strukturen att utesluta från detta  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.RectangleF  strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  strukturen att utesluta från detta  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Uppdaterar detta  com.aspose.psd.Region  så att det endast innehåller den del av dess inre som inte skär med den angivna  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Den  com.aspose.psd.Region  att utesluta från detta  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Hämtar regionens åtgärder.

**Returns:**
com.aspose.internal.RegionAction[] - Regionåtgärderna.
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


Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den  com.aspose.psd.GraphicsPath  att intersektera med detta  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.Rectangle  strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  strukturen att intersektera med detta  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.RectangleF  strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  strukturen att intersektera med detta  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Uppdaterar detta  com.aspose.psd.Region  till skärningen med den angivna  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Den  com.aspose.psd.Region  att intersektera med detta  com.aspose.psd.region . |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Testar om detta  com.aspose.psd.Region  har ett tomt inre på den angivna ritytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en ritningsyta. |

**Returns:**
boolean - true om innanmätet av detta  com.aspose.psd.Region  är tomt när transformationen som är associerad med  g  tillämpas; annars false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Testar om den angivna  com.aspose.psd.Region  är identisk med detta  com.aspose.psd.Region  på den angivna ritytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Den  com.aspose.psd.Region  att testa. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en ritningsyta. |

**Returns:**
boolean - True om innanmätet av region är identiskt med innanmätet av detta region när transformationen som är associerad med  g  -parametern tillämpas; annars false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Testar om detta  com.aspose.psd.Region  har ett oändligt inre på den angivna ritytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en ritningsyta. |

**Returns:**
boolean - true om innanmätet av detta  com.aspose.psd.Region  är oändligt när transformationen som är associerad med  g  tillämpas; annars false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Testar om den angivna  com.aspose.psd.Point  strukturen finns inom detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  com.aspose.psd.Point  strukturen att testa. |

**Returns:**
boolean - true när  point  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Testar om den angivna  com.aspose.psd.Point  strukturen finns inom detta  com.aspose.psd.Region  när den ritas med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  com.aspose.psd.Point  strukturen att testa. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - true när  point  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Testar om den angivna  com.aspose.psd.PointF  strukturen finns inom detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Den  com.aspose.psd.PointF  strukturen att testa. |

**Returns:**
boolean - true när  point  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Testar om den angivna  com.aspose.psd.PointF  strukturen finns inom detta  com.aspose.psd.Region  när den ritas med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Den  com.aspose.psd.PointF  strukturen att testa. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - true när  point  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Testar om någon del av den angivna  com.aspose.psd.Rectangle  strukturen finns inom detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  strukturen att testa. |

**Returns:**
boolean - Denna metod returnerar true när någon del av  rect  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Testar om någon del av den angivna  com.aspose.psd.Rectangle  strukturen finns inom detta  com.aspose.psd.Region  när den ritas med den angivna  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  strukturen att testa. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - true när någon del av  rect  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Testar om någon del av den angivna  com.aspose.psd.RectangleF  strukturen finns inom detta  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  strukturen att testa. |

**Returns:**
boolean - true när någon del av  rect  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Testar om någon del av den angivna com.aspose.psd.RectangleF strukturen finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  strukturen att testa. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - true när  rect  finns inom detta  com.aspose.psd.Region ; annars false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Testar om den angivna punkten finns inom detta com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten att testa. |
| y | float | Y-koordinaten för punkten att testa. |

**Returns:**
boolean - Sant när den angivna punkten finns inom detta  com.aspose.psd.Region ; annars falskt.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Testar om den angivna punkten finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten att testa. |
| y | float | Y-koordinaten för punkten att testa. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - Sant när den angivna punkten finns inom detta  com.aspose.psd.Region ; annars falskt.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Testar om någon del av den angivna rektangeln finns inom detta com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | float | Bredden på rektangeln som ska testas. |
| höjd | float | Höjden på rektangeln som ska testas. |

**Returns:**
boolean - sant när någon del av den angivna rektangeln finns inom detta  com.aspose.psd.Region  objekt; annars falskt.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Testar om någon del av den angivna rektangeln finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | float | Bredden på rektangeln som ska testas. |
| höjd | float | Höjden på rektangeln som ska testas. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - sant när någon del av den angivna rektangeln finns inom detta  com.aspose.psd.Region ; annars falskt.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Testar om den angivna punkten finns inom detta com.aspose.psd.Region objekt när det ritas med det angivna com.aspose.psd.Graphics objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten att testa. |
| y | int | Y-koordinaten för punkten att testa. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - sant när den angivna punkten finns inom detta  com.aspose.psd.Region ; annars falskt.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Testar om någon del av den angivna rektangeln finns inom detta com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | int | Bredden på rektangeln som ska testas. |
| höjd | int | Höjden på rektangeln som ska testas. |

**Returns:**
boolean - sant när någon del av den angivna rektangeln finns inom detta  com.aspose.psd.Region ; annars falskt.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Testar om någon del av den angivna rektangeln finns inom denna com.aspose.psd.Region när den ritas med den angivna com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| bredd | int | Bredden på rektangeln som ska testas. |
| höjd | int | Höjden på rektangeln som ska testas. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ett  com.aspose.psd.Graphics  som representerar en grafikkontext. |

**Returns:**
boolean - sant när någon del av den angivna rektangeln finns inom detta  com.aspose.psd.Region ; annars falskt.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initierar detta com.aspose.psd.Region till ett tomt inre.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initierar detta com.aspose.psd.Region objekt till ett oändligt inre.

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


Hämtar eller anger regionen vid förändring.

Värde: Regionen vid ändring.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.ChangeActionList |  |

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


Transformerar detta com.aspose.psd.Region med den angivna com.aspose.psd.matrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Den  com.aspose.psd.Matrix  som används för att transformera detta  com.aspose.psd.region . |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Förskjuter koordinaterna för detta com.aspose.psd.Region med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Mängden för att förskjuta detta  com.aspose.psd.Region  horisontellt. |
| dy | float | Mängden för att förskjuta detta  com.aspose.psd.Region  vertikalt. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Förskjuter koordinaterna för detta com.aspose.psd.Region med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | int | Mängden för att förskjuta detta  com.aspose.psd.Region  horisontellt. |
| dy | int | Mängden för att förskjuta detta  com.aspose.psd.Region  vertikalt. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den  com.aspose.psd.GraphicsPath  att förena med detta  com.aspose.psd.region . |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.Rectangle strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  strukturen att förena med detta  com.aspose.psd.region . |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.RectangleF strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  strukturen att förena med detta  com.aspose.psd.region . |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Uppdaterar detta com.aspose.psd.Region till unionen av sig själv och den angivna com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Den  com.aspose.psd.Region  att förena med detta  com.aspose.psd.region . |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den  com.aspose.psd.GraphicsPath  att xor:a med detta  com.aspose.psd.region . |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.Rectangle strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  strukturen att xor:a med detta  com.aspose.psd.region . |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.RectangleF strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  strukturen att xor:a med detta  com.aspose.psd.region . |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Uppdaterar detta com.aspose.psd.Region till unionen minus skärningen av sig själv med den angivna com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Den  com.aspose.psd.Region  att xor:a med detta  com.aspose.psd.region . |

