---
title: "VectorShapeOriginSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Configuración de origen de forma vectorial."
type: docs
weight: 24
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

Configuración de origen de forma vectorial.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | Inicializa una nueva instancia de la clase [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings). |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | La clave del descriptor para guardar el índice de origen de la forma. |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | La clave del descriptor del radio del rectángulo de origen. |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | La clave del descriptor de la resolución de origen. |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | La clave del descriptor del cuadro delimitador de la forma de origen. |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | La clave del descriptor del tipo de origen. |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | La clave del descriptor para guardar el valor invalidado de la forma. |
| [KnownKeys_internalized](#KnownKeys-internalized) | Las claves de propiedad conocidas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | Obtiene el identificador único. |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | Obtiene o establece las esquinas de la caja de origen. |
| [getOriginIndex()](#getOriginIndex--) | Obtiene o establece el índice de la forma de origen. |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | Obtiene o establece el rectángulo de radios de origen. |
| [getOriginResolution()](#getOriginResolution--) | Obtiene o establece la resolución de origen. |
| [getOriginShapeBox()](#getOriginShapeBox--) | Obtiene o establece el cuadro delimitador de la forma de origen. |
| [getOriginType()](#getOriginType--) | Obtiene o establece el tipo de origen. |
| [getTransform()](#getTransform--) | Obtiene o establece la matriz de transformación. |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | Obtiene o establece un valor que indica si esta instancia tiene propiedades desconocidas. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Obtiene o establece un valor que indica si esta instancia ha sido modificada. |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | Obtiene un valor que indica si esta instancia tiene la propiedad de esquinas del cuadro de origen. |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | Obtiene un valor que indica si esta instancia tiene la propiedad de índice de origen. |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | Obtiene un valor que indica si el rectángulo de radios de origen está presente. |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | Obtiene un valor que indica si esta instancia tiene la propiedad de resolución de origen. |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | Obtiene un valor que indica si esta instancia tiene la propiedad de rectángulo. |
| [isOriginTypePresent()](#isOriginTypePresent--) | Obtiene un valor que indica si esta instancia tiene la propiedad de tipo de origen. |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | Determina si la propiedad con la clave especificada está presente. |
| [isShapeInvalidated()](#isShapeInvalidated--) | Obtiene o establece un valor que indica si la forma está invalidada. |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | Obtiene un valor que indica si esta instancia tiene un conjunto de propiedad de forma invalidada. |
| [isTransformPresent()](#isTransformPresent--) | Obtiene un valor que indica si esta instancia tiene la propiedad de transformación. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | Obtiene o establece un valor que indica si esta instancia ha sido modificada. |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | Obtiene o establece las esquinas de la caja de origen. |
| [setOriginIndex(int value)](#setOriginIndex-int-) | Obtiene o establece el índice de la forma de origen. |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | Obtiene o establece el rectángulo de radios de origen. |
| [setOriginResolution(double value)](#setOriginResolution-double-) | Obtiene o establece la resolución de origen. |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | Obtiene o establece el cuadro delimitador de la forma de origen. |
| [setOriginType(int value)](#setOriginType-int-) | Obtiene o establece el tipo de origen. |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | Obtiene o establece un valor que indica si la forma está invalidada. |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | Obtiene o establece la matriz de transformación. |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | Obtiene o establece un valor que indica si esta instancia tiene propiedades desconocidas. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


Inicializa una nueva instancia de la clase [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isShapeInvalidated | boolean | El valor de la forma invalidada. |
| originIndex | int | El índice de origen de la forma. |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


La clave del descriptor para guardar el índice de origen de la forma.

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


La clave del descriptor del radio del rectángulo de origen.

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


La clave del descriptor de la resolución de origen.

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


La clave del descriptor del cuadro delimitador de la forma de origen.

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


La clave del descriptor del tipo de origen.

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


La clave del descriptor para guardar el valor invalidado de la forma.

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


Las claves de propiedad conocidas.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getId_internalized() {#getId-internalized--}
```
public final System.Guid getId_internalized()
```


Obtiene el identificador único.

Valor: El identificador único.

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


Obtiene o establece las esquinas de la caja de origen.

Valor: Las esquinas del cuadro de origen.

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


Obtiene o establece el índice de la forma de origen.

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


Obtiene o establece el rectángulo de radios de origen.

Valor: El rectángulo de radios de origen.

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


Obtiene o establece la resolución de origen.

Valor: La resolución de origen.

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


Obtiene o establece el cuadro delimitador de la forma de origen.

Valor: El cuadro de forma de origen.

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


Obtiene o establece el tipo de origen.

Valor: El tipo de origen.

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


Obtiene o establece la matriz de transformación.

Valor: La matriz de transformación.

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


Obtiene o establece un valor que indica si esta instancia tiene propiedades desconocidas.

Valor:  true  si esta instancia tiene propiedades desconocidas; de lo contrario,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


Obtiene o establece un valor que indica si esta instancia ha sido modificada.

Valor:  true  si esta instancia ha sido modificada; de lo contrario,  false .

**Returns:**
boolean
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


Obtiene un valor que indica si esta instancia tiene la propiedad de esquinas del cuadro de origen.

Valor:  true  si esta instancia tiene la propiedad de esquinas de la caja de origen; de lo contrario,  false .

**Returns:**
boolean
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


Obtiene un valor que indica si esta instancia tiene la propiedad de índice de origen.

Valor:  true  si esta instancia tiene la propiedad de índice de origen; de lo contrario,  false .

**Returns:**
boolean
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


Obtiene un valor que indica si el rectángulo de radios de origen está presente.

Valor:  true  si esta instancia tiene la propiedad de rectángulo de radios de origen; de lo contrario,  false .

**Returns:**
boolean
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


Obtiene un valor que indica si esta instancia tiene la propiedad de resolución de origen.

Valor:  true  si esta instancia tiene la propiedad de resolución de origen; de lo contrario,  false .

**Returns:**
boolean
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


Obtiene un valor que indica si esta instancia tiene la propiedad de rectángulo.

Valor:  true  si esta instancia tiene la propiedad de rectángulo de forma de origen; de lo contrario,  false .

**Returns:**
boolean
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


Obtiene un valor que indica si esta instancia tiene la propiedad de tipo de origen.

Valor:  true  si esta instancia tiene la propiedad de tipo de origen; de lo contrario,  false .

**Returns:**
boolean
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


Determina si la propiedad con la clave especificada está presente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | La clave de la propiedad. |

**Returns:**
boolean -  true  si la propiedad con la clave especificada está presente; de lo contrario,  false .
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


Obtiene o establece un valor que indica si la forma está invalidada.

**Returns:**
boolean
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


Obtiene un valor que indica si esta instancia tiene un conjunto de propiedad de forma invalidada.

Valor:  true  si esta instancia tiene un conjunto de propiedad de forma invalidada; de lo contrario,  false .

**Returns:**
boolean
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


Obtiene un valor que indica si esta instancia tiene la propiedad de transformación.

Valor:  true  si esta instancia tiene la propiedad de transformación; de lo contrario,  false .

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




### setChanged_internalized(boolean value) {#setChanged-internalized-boolean-}
```
public final void setChanged_internalized(boolean value)
```


Obtiene o establece un valor que indica si esta instancia ha sido modificada.

Valor:  true  si esta instancia ha sido modificada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


Obtiene o establece las esquinas de la caja de origen.

Valor: Las esquinas del cuadro de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


Obtiene o establece el índice de la forma de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


Obtiene o establece el rectángulo de radios de origen.

Valor: El rectángulo de radios de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


Obtiene o establece la resolución de origen.

Valor: La resolución de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


Obtiene o establece el cuadro delimitador de la forma de origen.

Valor: El cuadro de forma de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


Obtiene o establece el tipo de origen.

Valor: El tipo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


Obtiene o establece un valor que indica si la forma está invalidada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


Obtiene o establece la matriz de transformación.

Valor: La matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


Obtiene o establece un valor que indica si esta instancia tiene propiedades desconocidas.

Valor:  true  si esta instancia tiene propiedades desconocidas; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

