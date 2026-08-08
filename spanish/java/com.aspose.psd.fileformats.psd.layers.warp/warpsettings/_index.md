---
title: "WarpSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Parámetros de capa con deformación"
type: docs
weight: 11
url: /es/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Parámetros de capa con deformación
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
## Campos

| Campo | Descripción |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | El valor predeterminado de ProcessingArea |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtiene o establece los límites de la imagen warp |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Puntos de malla de Photoshop |
| [getProcessingArea()](#getProcessingArea--) | Obtiene o establece el valor del tamaño del área de procesamiento. |
| [getRotate()](#getRotate--) | Obtiene o establece el valor de rotación |
| [getStyle()](#getStyle--) | Obtiene o establece el estilo de warp |
| [getValue()](#getValue--) | Obtiene o establece el valor de warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Obtiene o establece el cambio del usuario en MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtiene o establece los límites de la imagen warp |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Puntos de malla de Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Devuelve el punto de malla de los vectores de recurso |
| [setProcessingArea(int value)](#setProcessingArea-int-) | Obtiene o establece el valor del tamaño del área de procesamiento. |
| [setRotate(int value)](#setRotate-int-) | Obtiene o establece el valor de rotación |
| [setStyle(int value)](#setStyle-int-) | Obtiene o establece el estilo de warp |
| [setValue(double value)](#setValue-double-) | Obtiene o establece el valor de warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Guarda estos parámetros de warp en PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Guarda estos parámetros de warp en PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Elementos PS con configuraciones de warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la imagen warp |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | El recurso con configuraciones de warp |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
```


El valor predeterminado de ProcessingArea

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtiene o establece los límites de la imagen warp

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


Puntos de malla de Photoshop

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


Obtiene o establece el valor del tamaño del área de procesamiento. El valor predeterminado es 10. El rango es [2;40]

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Obtiene o establece el valor de rotación

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Obtiene o establece el estilo de warp

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Obtiene o establece el valor de warp

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


Obtiene o establece el cambio del usuario en MeshPoints

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


Obtiene o establece los límites de la imagen warp

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Puntos de malla de Photoshop

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Devuelve el punto de malla de los vectores de recurso

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | El recurso con configuraciones de warp |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


Obtiene o establece el valor del tamaño del área de procesamiento. El valor predeterminado es 10. El rango es [2;40]

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Obtiene o establece el valor de rotación

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Obtiene o establece el estilo de warp

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Obtiene o establece el valor de warp

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Guarda estos parámetros de warp en PlacedResource

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | El recurso con configuraciones de warp |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Recurso con parámetros de warp de este WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Guarda estos parámetros de warp en PlacedResource

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | El recurso con configuraciones de warp |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

