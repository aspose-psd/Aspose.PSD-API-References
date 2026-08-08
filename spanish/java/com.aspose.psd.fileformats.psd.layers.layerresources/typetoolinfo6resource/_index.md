---
title: "TypeToolInfo6Resource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La información de la herramienta de texto."
type: docs
weight: 78
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfo6Resource extends LayerResource
```

La información de la herramienta de tipo. Para versiones de PSD mayores o iguales a la 6.0.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)](#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Inicializa una nueva instancia de la clase [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versión del encabezado PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma de recurso específica de PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versión del encabezado PSD |
| [ResourceSignature](#ResourceSignature) | La firma de recurso común. |
| [TypeToolKey](#TypeToolKey) | La clave de información de la herramienta de tipo. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licencia venture. |
## Métodos

| Método | Descripción |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Comprueba y establece si el recurso es específico de PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Obtiene o establece la ubicación inferior. |
| [getBoundingBox_internalized()](#getBoundingBox-internalized--) | Obtiene o establece los límites del texto en el cuadro de texto. |
| [getBounds_internalized()](#getBounds-internalized--) | Obtiene o establece los límites del cuadro de texto. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Obtiene o establece el ID de clase. |
| [getClassName()](#getClassName--) | Obtiene o establece el nombre de la clase. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Obtiene o establece la versión del descriptor. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getItems()](#getItems--) | Obtiene o establece los elementos. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLeft()](#getLeft--) | Obtiene o establece la ubicación izquierda. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de capa en bytes. |
| [getParsedTyShModel_internalized()](#getParsedTyShModel-internalized--) | Analiza los datos sin procesar a una instancia de la clase TyShRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getRawDataStructure_internalized()](#getRawDataStructure-internalized--) | Obtiene el elemento [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) si existe. |
| [getRight()](#getRight--) | Obtiene o establece la ubicación derecha. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [getTextIndex_internalized()](#getTextIndex-internalized--) | Obtiene el índice de texto en este recurso. |
| [getTextVersion()](#getTextVersion--) | Obtiene o establece la versión de texto. |
| [getTop()](#getTop--) | Obtiene o establece la ubicación superior. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece la matriz de transformación. |
| [getVersion()](#getVersion--) | Obtiene o establece la versión de la herramienta de tipo. |
| [getWarpClassID()](#getWarpClassID--) | Obtiene o establece el ID de clase. |
| [getWarpClassName()](#getWarpClassName--) | Obtiene o establece el nombre de clase de deformación. |
| [getWarpDescriptorVersion()](#getWarpDescriptorVersion--) | Obtiene o establece la versión del descriptor de deformación. |
| [getWarpItems()](#getWarpItems--) | Obtiene o establece los elementos de deformación. |
| [getWarpVersion()](#getWarpVersion--) | Obtiene o establece la versión de deformación. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el recurso en el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setBottom(int value)](#setBottom-int-) | Obtiene o establece la ubicación inferior. |
| [setBoundingBox_internalized(RectangleF value)](#setBoundingBox-internalized-com.aspose.psd.RectangleF-) | Obtiene o establece los límites del texto en el cuadro de texto. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtiene o establece el ID de clase. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Obtiene o establece el nombre de la clase. |
| [setDescriptorVersion(int value)](#setDescriptorVersion-int-) | Obtiene o establece la versión del descriptor. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtiene o establece los elementos. |
| [setLeft(int value)](#setLeft-int-) | Obtiene o establece la ubicación izquierda. |
| [setRight(int value)](#setRight-int-) | Obtiene o establece la ubicación derecha. |
| [setTextVersion(short value)](#setTextVersion-short-) | Obtiene o establece la versión de texto. |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la ubicación superior. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Obtiene o establece la matriz de transformación. |
| [setVersion(short value)](#setVersion-short-) | Obtiene o establece la versión de la herramienta de tipo. |
| [setWarpClassID(ClassID value)](#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtiene o establece el ID de clase. |
| [setWarpClassName(String value)](#setWarpClassName-java.lang.String-) | Obtiene o establece el nombre de clase de deformación. |
| [setWarpDescriptorVersion(int value)](#setWarpDescriptorVersion-int-) | Obtiene o establece la versión del descriptor de deformación. |
| [setWarpItems(OSTypeStructure[] value)](#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtiene o establece los elementos de deformación. |
| [setWarpVersion(short value)](#setWarpVersion-short-) | Obtiene o establece la versión de deformación. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [updateFromTyShModel_internalized(TyShRoot dataModel)](#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-) | Serializa los datos TyShRoot a crudo. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfo6Resource(ClassID classID, ClassID warpClassID) {#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)
```


Inicializa una nueva instancia de la clase [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | El ID de la clase. |
| warpClassID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | El ID de la clase warp. |

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


La versión del encabezado PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


La firma de recurso específica de PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


La versión del encabezado PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


La firma de recurso común.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


La clave de información de la herramienta de tipo.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


La licencia venture.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Comprueba y establece si el recurso es específico de PSB. Algunos recursos no se reconocen por ahora, pero tenemos una lista completa de recursos específicos de PSB que cambian su comportamiento al guardar. Por lo tanto, debemos comprobar esto al menos en UnknownResource.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | int | La clave. |

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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Obtiene o establece la ubicación inferior.

Valor: La ubicación inferior.

**Returns:**
int
### getBoundingBox_internalized() {#getBoundingBox-internalized--}
```
public final RectangleF getBoundingBox_internalized()
```


Obtiene o establece los límites del texto en el cuadro de texto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds_internalized() {#getBounds-internalized--}
```
public final RectangleF getBounds_internalized()
```


Obtiene o establece los límites del cuadro de texto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassID() {#getClassID--}
```
public final ClassID getClassID()
```


Obtiene o establece el ID de clase.

Valor: El ID de clase.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


Obtiene o establece el nombre de la clase.

Valor: El nombre de la clase.

**Returns:**
java.lang.String
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Obtiene o establece la versión del descriptor.

Valor: La versión del descriptor.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Obtiene o establece los elementos.

Valor: los elementos.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Obtiene la clave del recurso de capa.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtiene o establece la ubicación izquierda.

Valor: La ubicación izquierda.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Obtiene la longitud del recurso de capa en bytes.

**Returns:**
int
### getParsedTyShModel_internalized() {#getParsedTyShModel-internalized--}
```
public final TyShRoot getParsedTyShModel_internalized()
```


Analiza los datos sin procesar a una instancia de la clase TyShRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot - Los datos crudos como instancia de la clase TyShRoot.
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Obtiene la longitud del prefijo. El valor predeterminado es 12 para recursos 8BIM y 16 para 8B64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| psdVersion | int | La versión PSD. |

**Returns:**
int - La longitud del prefijo.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones.

**Returns:**
int
### getRawDataStructure_internalized() {#getRawDataStructure-internalized--}
```
public final RawDataStructure getRawDataStructure_internalized()
```


Obtiene el elemento [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) si existe.

**Returns:**
[RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) - The raw data structure.
### getRight() {#getRight--}
```
public final int getRight()
```


Obtiene o establece la ubicación derecha.

Valor: La ubicación derecha.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene la firma del recurso de capa.

**Returns:**
int
### getTextIndex_internalized() {#getTextIndex-internalized--}
```
public final int getTextIndex_internalized()
```


Obtiene el índice de texto en este recurso.

**Returns:**
int - Devuelve el índice de texto en este recurso.
### getTextVersion() {#getTextVersion--}
```
public final short getTextVersion()
```


Obtiene o establece la versión de texto.

Valor: La versión de texto.

**Returns:**
short
### getTop() {#getTop--}
```
public final int getTop()
```


Obtiene o establece la ubicación superior.

Valor: La ubicación superior.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Obtiene o establece la matriz de transformación.

Valor: La matriz de transformación.

**Returns:**
double[]
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Obtiene o establece la versión de la herramienta de tipo.

Valor: La versión de la herramienta de tipo.

**Returns:**
short
### getWarpClassID() {#getWarpClassID--}
```
public final ClassID getWarpClassID()
```


Obtiene o establece el ID de clase.

Valor: El ID de clase.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName() {#getWarpClassName--}
```
public final String getWarpClassName()
```


Obtiene o establece el nombre de clase de deformación.

Valor: El nombre de clase de deformación.

**Returns:**
java.lang.String
### getWarpDescriptorVersion() {#getWarpDescriptorVersion--}
```
public final int getWarpDescriptorVersion()
```


Obtiene o establece la versión del descriptor de deformación.

Valor: La versión del descriptor de deformación.

**Returns:**
int
### getWarpItems() {#getWarpItems--}
```
public final OSTypeStructure[] getWarpItems()
```


Obtiene o establece los elementos de deformación.

Valor: Los elementos de deformación.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion() {#getWarpVersion--}
```
public final short getWarpVersion()
```


Obtiene o establece la versión de deformación.

Valor: La versión de deformación.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determina si el recurso es específico de PSB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | int | La clave del recurso. |

**Returns:**
boolean -  true  si el recurso es específico de PSB; de lo contrario,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Obtiene un valor que indica si esta instancia es un recurso específico de PSB.

Valor:  true  si esta instancia es un recurso específico de PSB; de lo contrario,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psdVersion | int | La versión PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Guarda el encabezado del recurso personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| firma | int | La firma. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Guarda la firma del encabezado, el identificador y la longitud.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| firma | int | La firma. |
| isLengthLong | boolean | si se establece en  true  la longitud es larga. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Obtiene o establece la ubicación inferior.

Valor: La ubicación inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setBoundingBox_internalized(RectangleF value) {#setBoundingBox-internalized-com.aspose.psd.RectangleF-}
```
public final void setBoundingBox_internalized(RectangleF value)
```


Obtiene o establece los límites del texto en el cuadro de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


Obtiene o establece el ID de clase.

Valor: El ID de clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


Obtiene o establece el nombre de la clase.

Valor: El nombre de la clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDescriptorVersion(int value) {#setDescriptorVersion-int-}
```
public final void setDescriptorVersion(int value)
```


Obtiene o establece la versión del descriptor.

Valor: La versión del descriptor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Obtiene o establece los elementos.

Valor: los elementos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Obtiene o establece la ubicación izquierda.

Valor: La ubicación izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Obtiene o establece la ubicación derecha.

Valor: La ubicación derecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTextVersion(short value) {#setTextVersion-short-}
```
public final void setTextVersion(short value)
```


Obtiene o establece la versión de texto.

Valor: La versión de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obtiene o establece la ubicación superior.

Valor: La ubicación superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Obtiene o establece la matriz de transformación.

Valor: La matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Obtiene o establece la versión de la herramienta de tipo.

Valor: La versión de la herramienta de tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setWarpClassID(ClassID value) {#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID(ClassID value)
```


Obtiene o establece el ID de clase.

Valor: El ID de clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName(String value) {#setWarpClassName-java.lang.String-}
```
public final void setWarpClassName(String value)
```


Obtiene o establece el nombre de clase de deformación.

Valor: El nombre de clase de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setWarpDescriptorVersion(int value) {#setWarpDescriptorVersion-int-}
```
public final void setWarpDescriptorVersion(int value)
```


Obtiene o establece la versión del descriptor de deformación.

Valor: La versión del descriptor de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWarpItems(OSTypeStructure[] value) {#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setWarpItems(OSTypeStructure[] value)
```


Obtiene o establece los elementos de deformación.

Valor: Los elementos de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setWarpVersion(short value) {#setWarpVersion-short-}
```
public final void setWarpVersion(short value)
```


Obtiene o establece la versión de deformación.

Valor: La versión de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una String que representa esta instancia.

**Returns:**
java.lang.String - Una String que representa esta instancia.
### updateFromTyShModel_internalized(TyShRoot dataModel) {#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-}
```
public final void updateFromTyShModel_internalized(TyShRoot dataModel)
```


Serializa los datos TyShRoot a crudo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataModel | com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot |  |

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

