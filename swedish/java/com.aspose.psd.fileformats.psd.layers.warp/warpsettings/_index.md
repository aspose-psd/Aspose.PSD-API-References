---
title: "WarpSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Parametrar för lager med warp"
type: docs
weight: 11
url: /sv/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
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
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | Standardvärdet för ProcessingArea |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Hämtar eller anger gränser för warp-bild |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Photoshop-nätpunkter |
| [getProcessingArea()](#getProcessingArea--) | Hämtar eller anger värdet för storlek på bearbetningsområde. |
| [getRotate()](#getRotate--) | Hämtar eller anger rotationsvärde |
| [getStyle()](#getStyle--) | Hämtar eller anger stil för warp |
| [getValue()](#getValue--) | Hämtar eller anger värdet för warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Hämtar eller anger användarändring i MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Hämtar eller anger gränser för warp-bild |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Photoshop-nätpunkter |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Den returnerar nätpunkt från resursvektorer |
| [setProcessingArea(int value)](#setProcessingArea-int-) | Hämtar eller anger värdet för storlek på bearbetningsområde. |
| [setRotate(int value)](#setRotate-int-) | Hämtar eller anger rotationsvärde |
| [setStyle(int value)](#setStyle-int-) | Hämtar eller anger stil för warp |
| [setValue(double value)](#setValue-double-) | Hämtar eller anger värdet för warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Den sparar dessa warp-parametrar till PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Den sparar dessa warp-parametrar till PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | PS-objekt med warp-inställningar |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna för warp-bild |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initierar en ny instans av klassen [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Resursen med warp-inställningar |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
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
### getMeshPoints() {#getMeshPoints--}
```
public final Point[] getMeshPoints()
```


Photoshop-nätpunkter

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


Hämtar eller anger värdet för storlek på bearbetningsområde. Standardvärdet är 10. Intervallet är [2;40]

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

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Photoshop-nätpunkter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

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
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


Hämtar eller anger värdet för storlek på bearbetningsområde. Standardvärdet är 10. Intervallet är [2;40]

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

