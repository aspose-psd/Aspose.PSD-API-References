---
title: "AbddResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Los datos de información del tablero."
type: docs
weight: 10
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/abddresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class AbddResource extends BaseArtboardInfoResource
```

Los datos de información del tablero.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AbddResource()](#AbddResource--) | Inicializa una nueva instancia de la clase [AbddResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/abddresource). |
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
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Obtiene o establece el id de la clase de recurso. |
| [getClassName_internalized()](#getClassName-internalized--) | Obtiene o establece el nombre de la clase de recurso. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getItems()](#getItems--) | Obtiene o establece los elementos de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLength()](#getLength--) |    |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [getVersion_internalized()](#getVersion-internalized--) | Obtiene o establece la versión del recurso. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el recurso en el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtiene o establece el id de la clase de recurso. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Obtiene o establece el nombre de la clase de recurso. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtiene o establece los elementos de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Obtiene o establece la versión del recurso. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AbddResource() {#AbddResource--}
```
public AbddResource()
```


Inicializa una nueva instancia de la clase [AbddResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/abddresource).

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Obtiene o establece el id de la clase de recurso.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Obtiene o establece el nombre de la clase de recurso.

**Returns:**
java.lang.String
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


Obtiene o establece los elementos de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Obtiene la clave del recurso de capa.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


  

**Returns:**
int
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
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene la firma del recurso de capa.

**Returns:**
int
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


Obtiene o establece la versión del recurso.

**Returns:**
int
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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Obtiene o establece el id de la clase de recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Obtiene o establece el nombre de la clase de recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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


Obtiene o establece los elementos de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Obtiene o establece la versión del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una String que representa esta instancia.

**Returns:**
java.lang.String - Una String que representa esta instancia.
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

