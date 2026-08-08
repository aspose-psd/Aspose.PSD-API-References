---
title: "WarpSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Parametrar för lager med warp"
type: docs
weight: 12
url: /sv/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Parametrar för lager med warp
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | Standardvärdet för ProcessingArea |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Hämtar eller anger gränser för warp-bild |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Hämtar eller anger storleken på warp‑rutnätet. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Hämtar eller anger storleken på mesh‑linjerna. |
| [getMeshPoints()](#getMeshPoints--) | Photoshop-nätpunkter |
| [getRenderQuality()](#getRenderQuality--) | Hämtar eller anger värdet för warp‑renderingskvalitet – mellan hastighet och kvalitet. |
| [getRotate()](#getRotate--) | Hämtar eller anger rotationsvärde |
| [getStyle()](#getStyle--) | Hämtar eller anger stil för warp |
| [getValue()](#getValue--) | Hämtar eller anger värdet för warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Hämtar eller anger användarändring i MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Hämtar eller anger gränser för warp-bild |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Hämtar eller anger storleken på warp‑rutnätet. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Hämtar eller anger storleken på mesh‑linjerna. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Photoshop-nätpunkter |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Den returnerar nätpunkt från resursvektorer |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Hämtar eller anger värdet för warp‑renderingskvalitet – mellan hastighet och kvalitet. |
| [setRotate(int value)](#setRotate-int-) | Hämtar eller anger rotationsvärde |
| [setStyle(int value)](#setStyle-int-) | Hämtar eller anger stil för warp |
| [setValue(double value)](#setValue-double-) | Hämtar eller anger värdet för warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Den sparar dessa warp-parametrar till PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Den sparar dessa warp-parametrar till PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Mesh‑punkterna för warp. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna för warp-bild |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Mesh‑punkterna för warp. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna för warp-bild |
| style | int | Stilen för warp. |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | PS-objekt med warp-inställningar |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna för warp-bild |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Resursen med warp-inställningar |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


Standardvärdet för ProcessingArea

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Hämtar eller anger gränser för warp-bild

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGridSize() {#getGridSize--}
```
public final Size getGridSize()
```


Hämtar eller anger storleken på warp‑rutnätet. Standardvärdet är 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Hämtar eller anger storleken på mesh‑linjerna. GridSize är en definition från PS som klienten kan välja. Varje GridSize har 4 mesh‑linjer. Om antalet GridSize är större än 1, så blir den sista mesh‑linjen i det första rutnätet och den första i det andra rutnätet en och samma mesh‑linje.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Photoshop-nätpunkter

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Hämtar eller anger värdet för warp‑renderingskvalitet – mellan hastighet och kvalitet.

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Hämtar eller anger rotationsvärde

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Hämtar eller anger stil för warp

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Hämtar eller anger värdet för warp

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


Hämtar eller anger användarändring i MeshPoints

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Hämtar eller anger gränser för warp-bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Hämtar eller anger storleken på warp‑rutnätet. Standardvärdet är 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Hämtar eller anger storleken på mesh‑linjerna. GridSize är en definition från PS som klienten kan välja. Varje GridSize har 4 mesh‑linjer. Om antalet GridSize är större än 1, så blir den sista mesh‑linjen i det första rutnätet och den första i det andra rutnätet en och samma mesh‑linje.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Photoshop-nätpunkter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Den returnerar nätpunkt från resursvektorer

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Resursen med warp-inställningar |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Hämtar eller anger värdet för warp‑renderingskvalitet – mellan hastighet och kvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Hämtar eller anger rotationsvärde

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Hämtar eller anger stil för warp

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Hämtar eller anger värdet för warp

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Den sparar dessa warp-parametrar till PlacedResource

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Resursen med warp-inställningar |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Resurs med warp-parametrar från denna WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Den sparar dessa warp-parametrar till PlacedResource

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Resursen med warp-inställningar |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

