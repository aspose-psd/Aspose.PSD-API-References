---
title: "WarpSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Parametri del livello con warp"
type: docs
weight: 12
url: /it/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Parametri del livello con warp
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | Il valore predefinito di ProcessingArea |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti dell'immagine deformata |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Ottiene o imposta la dimensione della griglia di deformazione. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Ottiene o imposta la dimensione delle linee della mesh. |
| [getMeshPoints()](#getMeshPoints--) | Punti mesh di Photoshop |
| [getRenderQuality()](#getRenderQuality--) | Ottiene o imposta il valore della qualità di rendering della deformazione - tra velocità e qualità |
| [getRotate()](#getRotate--) | Ottiene o imposta il valore di rotazione |
| [getStyle()](#getStyle--) | Ottiene o imposta lo stile della deformazione |
| [getValue()](#getValue--) | Ottiene o imposta il valore della deformazione |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Ottiene o imposta la modifica dell'utente nei MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Ottiene o imposta i limiti dell'immagine deformata |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Ottiene o imposta la dimensione della griglia di deformazione. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Ottiene o imposta la dimensione delle linee della mesh. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Punti mesh di Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Restituisce il punto mesh dai vettori della risorsa |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Ottiene o imposta il valore della qualità di rendering della deformazione - tra velocità e qualità |
| [setRotate(int value)](#setRotate-int-) | Ottiene o imposta il valore di rotazione |
| [setStyle(int value)](#setStyle-int-) | Ottiene o imposta lo stile della deformazione |
| [setValue(double value)](#setValue-double-) | Ottiene o imposta il valore della deformazione |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Salva questi parametri di deformazione in PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Salva questi parametri di deformazione in PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | I punti della mesh della deformazione |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dell'immagine deformata |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | I punti della mesh della deformazione |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dell'immagine deformata |
| style | int | Lo stile della deformazione |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Elementi PS con impostazioni di deformazione |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dell'immagine deformata |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La risorsa con impostazioni di deformazione |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


Il valore predefinito di ProcessingArea

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Ottiene o imposta i limiti dell'immagine deformata

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


Ottiene o imposta la dimensione della griglia di deformazione. Il valore predefinito è 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Ottiene o imposta la dimensione delle linee della mesh. GridSize è una definizione di PS che il client può selezionare. Ogni GridSize ha 4 linee della mesh. Se il numero di GridSize è maggiore di 1, allora l'ultima mesh Line della prima Grid e la prima della seconda Grid sono una Mesh Line.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Punti mesh di Photoshop

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Ottiene o imposta il valore della qualità di rendering della deformazione - tra velocità e qualità

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Ottiene o imposta il valore di rotazione

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Ottiene o imposta lo stile della deformazione

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Ottiene o imposta il valore della deformazione

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


Ottiene o imposta la modifica dell'utente nei MeshPoints

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


Ottiene o imposta i limiti dell'immagine deformata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Ottiene o imposta la dimensione della griglia di deformazione. Il valore predefinito è 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Ottiene o imposta la dimensione delle linee della mesh. GridSize è una definizione di PS che il client può selezionare. Ogni GridSize ha 4 linee della mesh. Se il numero di GridSize è maggiore di 1, allora l'ultima mesh Line della prima Grid e la prima della seconda Grid sono una Mesh Line.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Punti mesh di Photoshop

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Restituisce il punto mesh dai vettori della risorsa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La risorsa con impostazioni di deformazione |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Ottiene o imposta il valore della qualità di rendering della deformazione - tra velocità e qualità

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Ottiene o imposta il valore di rotazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Ottiene o imposta lo stile della deformazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Ottiene o imposta il valore della deformazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Salva questi parametri di deformazione in PlacedResource

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La risorsa con impostazioni di deformazione |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Risorsa con parametri di deformazione da questo WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Salva questi parametri di deformazione in PlacedResource

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La risorsa con impostazioni di deformazione |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

