---
title: "WarpSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Parametri del livello con warp"
type: docs
weight: 11
url: /it/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
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
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | Il valore predefinito di ProcessingArea |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti dell'immagine deformata |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Punti mesh di Photoshop |
| [getProcessingArea()](#getProcessingArea--) | Ottiene o imposta il valore della dimensione dell'area di elaborazione. |
| [getRotate()](#getRotate--) | Ottiene o imposta il valore di rotazione |
| [getStyle()](#getStyle--) | Ottiene o imposta lo stile della deformazione |
| [getValue()](#getValue--) | Ottiene o imposta il valore della deformazione |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Ottiene o imposta la modifica dell'utente nei MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Ottiene o imposta i limiti dell'immagine deformata |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Punti mesh di Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Restituisce il punto mesh dai vettori della risorsa |
| [setProcessingArea(int value)](#setProcessingArea-int-) | Ottiene o imposta il valore della dimensione dell'area di elaborazione. |
| [setRotate(int value)](#setRotate-int-) | Ottiene o imposta il valore di rotazione |
| [setStyle(int value)](#setStyle-int-) | Ottiene o imposta lo stile della deformazione |
| [setValue(double value)](#setValue-double-) | Ottiene o imposta il valore della deformazione |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Salva questi parametri di deformazione in PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Salva questi parametri di deformazione in PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Elementi PS con impostazioni di deformazione |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dell'immagine deformata |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Inizializza una nuova istanza della classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La risorsa con impostazioni di deformazione |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
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
### getMeshPoints() {#getMeshPoints--}
```
public final Point[] getMeshPoints()
```


Punti mesh di Photoshop

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


Ottiene o imposta il valore della dimensione dell'area di elaborazione. Il valore predefinito è 10. L'intervallo è [2;40]

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

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Punti mesh di Photoshop

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

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
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


Ottiene o imposta il valore della dimensione dell'area di elaborazione. Il valore predefinito è 10. L'intervallo è [2;40]

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

