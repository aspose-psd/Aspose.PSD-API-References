---
title: "AddNoiseSmartFilter"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El filtro inteligente AddNoise."
type: docs
weight: 10
url: /es/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

El filtro inteligente AddNoise.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Inicializa una nueva instancia de la clase [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter). |
## Campos

| Campo | Descripción |
| --- | --- |
| [FilterType](#FilterType) | El identificador del filtro inteligente actual. |
## Métodos

| Método | Descripción |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Aplica el filtro actual a la imagen de entrada RasterImage. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Aplica el filtro actual a los datos de máscara de entrada [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Crea la clonación miembro a miembro de la instancia actual del tipo. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Obtiene o establece la cantidad del valor de ruido. |
| [getBlendMode()](#getBlendMode--) | Obtiene o establece el modo de fusión. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Obtiene o establece la distribución del filtro de ruido. |
| [getFilterId()](#getFilterId--) | Obtiene el identificador de tipo del filtro inteligente. |
| [getName()](#getName--) | Obtiene el nombre del filtro inteligente. |
| [getOpacity()](#getOpacity--) | Obtiene o establece el valor de opacidad del filtro inteligente. |
| [getSourceDescriptor()](#getSourceDescriptor--) | La estructura de descriptor de origen con datos del filtro inteligente. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Obtiene o establece el estado habilitado del filtro inteligente. |
| [isMonochromatic()](#isMonochromatic--) | Obtiene o establece el valor de monocromático. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Obtiene o establece la cantidad del valor de ruido. |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtiene o establece el modo de fusión. |
| [setDistribution(int value)](#setDistribution-int-) | Obtiene o establece la distribución del filtro de ruido. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Obtiene o establece el estado habilitado del filtro inteligente. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Obtiene o establece el valor de monocromático. |
| [setOpacity(double value)](#setOpacity-double-) | Obtiene o establece el valor de opacidad del filtro inteligente. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Guarda la información del filtro inteligente en los datos [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) y devuelve. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Inicializa una nueva instancia de la clase [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter).

### FilterType {#FilterType}
```
public static final int FilterType
```


El identificador del filtro inteligente actual.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Aplica el filtro actual a la imagen de entrada RasterImage.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen raster. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Aplica el filtro actual a los datos de máscara de entrada [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | La capa con datos de máscara. |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Crea la clonación miembro a miembro de la instancia actual del tipo.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Obtiene o establece la cantidad del valor de ruido.

**Returns:**
double
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Obtiene o establece el modo de fusión.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDistribution() {#getDistribution--}
```
public final int getDistribution()
```


Obtiene o establece la distribución del filtro de ruido.

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Obtiene el identificador de tipo del filtro inteligente.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre del filtro inteligente.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Obtiene o establece el valor de opacidad del filtro inteligente.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


La estructura de descriptor de origen con datos del filtro inteligente.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Obtiene o establece el estado habilitado del filtro inteligente.

**Returns:**
boolean
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Obtiene o establece el valor de monocromático.

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




### setAmountNoise(double value) {#setAmountNoise-double-}
```
public final void setAmountNoise(double value)
```


Obtiene o establece la cantidad del valor de ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Obtiene o establece el modo de fusión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Obtiene o establece la distribución del filtro de ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Obtiene o establece el estado habilitado del filtro inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Obtiene o establece el valor de monocromático.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Obtiene o establece el valor de opacidad del filtro inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Guarda la información del filtro inteligente en los datos [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) y devuelve.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
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

