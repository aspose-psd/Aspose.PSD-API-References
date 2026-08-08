---
title: "IPlacedLayerResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define la interfaz IPlacedLayerResource que contiene información sobre una capa colocada en el archivo PSD."
type: docs
weight: 17
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Define la interfaz IPlacedLayerResource que contiene información sobre una capa colocada en el archivo PSD. Es una interfaz de marcado utilizada para designar recursos PlLd, Sold y Sole en las imágenes Adobe\\ufffd Photoshop\\ufffd. Se utiliza para admitir capas de objeto inteligente en las imágenes Adobe\\ufffd Photoshop\\ufffd.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Obtiene o establece la política de antialias de la capa colocada en la imagen PSD. |
| [getBottom()](#getBottom--) | Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD. |
| [getBounds()](#getBounds--) | Obtiene o establece los límites de la capa colocada en el archivo PSD. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Obtiene o establece la unidad de medida de los puntos de malla horizontal. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [getItems()](#getItems--) | Obtiene o establece los elementos de deformación. |
| [getLeft()](#getLeft--) | Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD. |
| [getPageNumber()](#getPageNumber--) | Obtiene o establece el número de página de la capa colocada en el archivo PSD. |
| [getPerspective()](#getPerspective--) | Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Obtiene o establece el tipo de la capa colocada en el archivo PSD. |
| [getRight()](#getRight--) | Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD. |
| [getTop()](#getTop--) | Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD. |
| [getTotalPages()](#getTotalPages--) | Obtiene o establece el total de páginas de la capa colocada en el archivo PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece la matriz de transformación de la capa colocada en el archivo PSD. |
| [getUOrder()](#getUOrder--) | Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD. |
| [getUniqueId()](#getUniqueId--) | Obtiene o establece el identificador único global de la capa colocada de objeto inteligente en la imagen PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD. |
| [getValue()](#getValue--) | Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD. |
| [getVersion()](#getVersion--) | Obtiene la versión de la capa colocada en el archivo PSD, usualmente 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Obtiene o establece la unidad de medida de los puntos de malla vertical. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [isCustom()](#isCustom--) | Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Obtiene o establece la política de antialias de la capa colocada en la imagen PSD. |
| [setBottom(double value)](#setBottom-double-) | Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtiene o establece los límites de la capa colocada en el archivo PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Obtiene o establece la unidad de medida de los puntos de malla horizontal. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtiene o establece los elementos de deformación. |
| [setLeft(double value)](#setLeft-double-) | Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Obtiene o establece el número de página de la capa colocada en el archivo PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Obtiene o establece el tipo de la capa colocada en el archivo PSD. |
| [setRight(double value)](#setRight-double-) | Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD. |
| [setTop(double value)](#setTop-double-) | Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Obtiene o establece el total de páginas de la capa colocada en el archivo PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Obtiene o establece la matriz de transformación de la capa colocada en el archivo PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Obtiene o establece el identificador único global de la capa colocada de objeto inteligente en la imagen PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD. |
| [setValue(double value)](#setValue-double-) | Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Obtiene o establece la unidad de medida de los puntos de malla vertical. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Obtiene o establece la política de antialias de la capa colocada en la imagen PSD.

Valor: La política de antialias de la capa colocada.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD.

Valor: La ubicación inferior de la capa colocada.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Obtiene o establece los límites de la capa colocada en el archivo PSD.

Valor: Los límites de la capa colocada.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Obtiene o establece la unidad de medida de los puntos de malla horizontal.

Valor: La unidad de medida de los puntos de malla horizontales.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Obtiene o establece los elementos de deformación.

Valor: Los elementos de deformación.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD.

Valor: La ubicación izquierda de la capa colocada.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Obtiene o establece el número de página de la capa colocada en el archivo PSD.

Valor: El número de página de la capa colocada.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El valor de perspectiva de la capa colocada.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El otro valor de perspectiva de la capa colocada.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Obtiene o establece el tipo de la capa colocada en el archivo PSD.

Valor: El tipo de la capa colocada.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD.

Valor: La ubicación derecha de la capa colocada.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD.

Valor: La ubicación superior de la capa colocada.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Obtiene o establece el total de páginas de la capa colocada en el archivo PSD.

Valor: El total de páginas de la capa colocada.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Obtiene o establece la matriz de transformación de la capa colocada en el archivo PSD.

Valor: La matriz de transformación de la capa colocada.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD.

Valor: El valor de orden U de la capa colocada.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Obtiene o establece el identificador único global de la capa colocada de objeto inteligente en la imagen PSD.

Valor: El identificador único de la capa colocada.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD.

Valor: El valor de orden V de la capa colocada.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD.

Valor: El valor de deformación de la capa colocada.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Obtiene la versión de la capa colocada en el archivo PSD, usualmente 3-5.

Valor: La versión de la capa colocada o de objeto inteligente.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Obtiene o establece la unidad de medida de los puntos de malla vertical.

Valor: La unidad de medida de los puntos de malla verticales.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. Si es verdadero, contiene puntos de malla. Si se establece en falso, elimina los puntos de malla.

Valor:  true  si el recurso de capa colocada o de objeto inteligente tiene estilo personalizado; de lo contrario,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Obtiene o establece la política de antialias de la capa colocada en la imagen PSD.

Valor: La política de antialias de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD.

Valor: La ubicación inferior de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Obtiene o establece los límites de la capa colocada en el archivo PSD.

Valor: Los límites de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. Si es verdadero, contiene puntos de malla. Si se establece en falso, elimina los puntos de malla.

Valor:  true  si el recurso de capa colocada o de objeto inteligente tiene estilo personalizado; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Obtiene o establece la unidad de medida de los puntos de malla horizontal.

Valor: La unidad de medida de los puntos de malla horizontales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Obtiene o establece los elementos de deformación.

Valor: Los elementos de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD.

Valor: La ubicación izquierda de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Obtiene o establece el número de página de la capa colocada en el archivo PSD.

Valor: El número de página de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El valor de perspectiva de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El otro valor de perspectiva de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Obtiene o establece el tipo de la capa colocada en el archivo PSD.

Valor: El tipo de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD.

Valor: La ubicación derecha de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD.

Valor: La ubicación superior de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Obtiene o establece el total de páginas de la capa colocada en el archivo PSD.

Valor: El total de páginas de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Obtiene o establece la matriz de transformación de la capa colocada en el archivo PSD.

Valor: La matriz de transformación de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD.

Valor: El valor de orden U de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Obtiene o establece el identificador único global de la capa colocada de objeto inteligente en la imagen PSD.

Valor: El identificador único de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD.

Valor: El valor de orden V de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD.

Valor: El valor de deformación de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Obtiene o establece la unidad de medida de los puntos de malla vertical.

Valor: La unidad de medida de los puntos de malla verticales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

