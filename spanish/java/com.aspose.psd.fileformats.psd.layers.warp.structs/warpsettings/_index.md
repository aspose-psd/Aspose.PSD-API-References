---
title: "WarpSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Parámetros de capa con deformación"
type: docs
weight: 12
url: /es/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
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
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
## Campos

| Campo | Descripción |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | El valor predeterminado de ProcessingArea |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtiene o establece los límites de la imagen warp |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Obtiene o establece el tamaño de la cuadrícula de deformación. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Obtiene o establece el tamaño de las líneas de malla. |
| [getMeshPoints()](#getMeshPoints--) | Puntos de malla de Photoshop |
| [getRenderQuality()](#getRenderQuality--) | Obtiene o establece el valor de la calidad de renderizado de deformación - entre velocidad y calidad |
| [getRotate()](#getRotate--) | Obtiene o establece el valor de rotación |
| [getStyle()](#getStyle--) | Obtiene o establece el estilo de warp |
| [getValue()](#getValue--) | Obtiene o establece el valor de warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Obtiene o establece el cambio del usuario en MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtiene o establece los límites de la imagen warp |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Obtiene o establece el tamaño de la cuadrícula de deformación. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Obtiene o establece el tamaño de las líneas de malla. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Puntos de malla de Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Devuelve el punto de malla de los vectores de recurso |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Obtiene o establece el valor de la calidad de renderizado de deformación - entre velocidad y calidad |
| [setRotate(int value)](#setRotate-int-) | Obtiene o establece el valor de rotación |
| [setStyle(int value)](#setStyle-int-) | Obtiene o establece el estilo de warp |
| [setValue(double value)](#setValue-double-) | Obtiene o establece el valor de warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Guarda estos parámetros de warp en PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Guarda estos parámetros de warp en PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Los puntos de malla de la deformación |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la imagen warp |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Los puntos de malla de la deformación |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la imagen warp |
| style | int | El estilo de la deformación |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Elementos PS con configuraciones de warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la imagen warp |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Inicializa una nueva instancia de la clase [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | El recurso con configuraciones de warp |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
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
### getGridSize() {#getGridSize--}
```
public final Size getGridSize()
```


Obtiene o establece el tamaño de la cuadrícula de deformación. El valor predeterminado es 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Obtiene o establece el tamaño de las líneas de malla. GridSize es una definición de PS que el cliente puede seleccionar. Cada GridSize tiene 4 líneas de malla. Si el número de GridSize es mayor que 1, entonces la última línea de malla del primer Grid y la primera del segundo Grid son una sola línea de malla.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Puntos de malla de Photoshop

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Obtiene o establece el valor de la calidad de renderizado de deformación - entre velocidad y calidad

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

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Obtiene o establece el tamaño de la cuadrícula de deformación. El valor predeterminado es 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Obtiene o establece el tamaño de las líneas de malla. GridSize es una definición de PS que el cliente puede seleccionar. Cada GridSize tiene 4 líneas de malla. Si el número de GridSize es mayor que 1, entonces la última línea de malla del primer Grid y la primera del segundo Grid son una sola línea de malla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Puntos de malla de Photoshop

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

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
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Obtiene o establece el valor de la calidad de renderizado de deformación - entre velocidad y calidad

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

