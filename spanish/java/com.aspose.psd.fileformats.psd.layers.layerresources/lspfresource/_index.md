---
title: "LspfResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Configuraciones protegidas de capa"
type: docs
weight: 57
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LspfResource extends LayerResource
```

Configuraciones protegidas de capa
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LspfResource(byte[] data)](#LspfResource-byte---) | Inicializa una nueva instancia de la clase [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
| [LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)](#LspfResource-boolean-boolean-boolean-) | Inicializa una nueva instancia de la clase [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
| [LspfResource()](#LspfResource--) | Inicializa una nueva instancia de la clase [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versión del encabezado PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma de recurso específica de PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versión del encabezado PSD |
| [ResourceSignature](#ResourceSignature) | La firma de recurso común. |
| [TypeToolKey](#TypeToolKey) | La clave de información del tipo de herramienta 1819504742 |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licencia venture. |
## Métodos

| Método | Descripción |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Comprueba y establece si el recurso es específico de PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de capa en bytes. |
| [getLockType()](#getLockType--) | Obtiene o establece el tipo de bloqueo. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [hashCode()](#hashCode--) |  |
| [isCompositeProtected()](#isCompositeProtected--) | Obtiene o establece un valor que indica si esta instancia está protegida de forma compuesta. |
| [isPositionProtected()](#isPositionProtected--) | Obtiene o establece un valor que indica si esta instancia está protegida de posición. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [isTransparencyProtected()](#isTransparencyProtected--) | Obtiene o establece un valor que indica si esta instancia está protegida de transparencia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el recurso en el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setCompositeProtected(boolean value)](#setCompositeProtected-boolean-) | Obtiene o establece un valor que indica si esta instancia está protegida de forma compuesta. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setLockType(int value)](#setLockType-int-) | Obtiene o establece el tipo de bloqueo. |
| [setPositionProtected(boolean value)](#setPositionProtected-boolean-) | Obtiene o establece un valor que indica si esta instancia está protegida de posición. |
| [setTransparencyProtected(boolean value)](#setTransparencyProtected-boolean-) | Obtiene o establece un valor que indica si esta instancia está protegida de transparencia. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LspfResource(byte[] data) {#LspfResource-byte---}
```
public LspfResource(byte[] data)
```


Inicializa una nueva instancia de la clase [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). Con valor personalizado o desconocido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos del recurso. |

### LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected) {#LspfResource-boolean-boolean-boolean-}
```
public LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)
```


Inicializa una nueva instancia de la clase [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isTransparencyProtected | boolean | si se establece en  true  [está protegido de transparencia]. |
| isCompositeProtected | boolean | si se establece en  true  [está protegido de forma compuesta]. |
| isPositionProtected | boolean | si se establece a  true  [is position protected]. |

### LspfResource() {#LspfResource--}
```
public LspfResource()
```


Inicializa una nueva instancia de la clase [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource).

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


La clave de información del tipo de herramienta 1819504742

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
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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


Obtiene la longitud del recurso de capa en bytes.

**Returns:**
int
### getLockType() {#getLockType--}
```
public final int getLockType()
```


Obtiene o establece el tipo de bloqueo.

Valor: El tipo de la cerradura.

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompositeProtected() {#isCompositeProtected--}
```
public final boolean isCompositeProtected()
```


Obtiene o establece un valor que indica si esta instancia está protegida de forma compuesta.

Valor:  true  si esta instancia está protegida de forma compuesta; de lo contrario,  false .

**Returns:**
boolean
### isPositionProtected() {#isPositionProtected--}
```
public final boolean isPositionProtected()
```


Obtiene o establece un valor que indica si esta instancia está protegida de posición.

Valor:  true  si esta instancia está protegida por posición; de lo contrario,  false .

**Returns:**
boolean
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
### isTransparencyProtected() {#isTransparencyProtected--}
```
public final boolean isTransparencyProtected()
```


Obtiene o establece un valor que indica si esta instancia está protegida de transparencia.

Valor:  true  si esta instancia está protegida por transparencia; de lo contrario,  false .

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

### setCompositeProtected(boolean value) {#setCompositeProtected-boolean-}
```
public final void setCompositeProtected(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está protegida de forma compuesta.

Valor:  true  si esta instancia está protegida de forma compuesta; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Obtiene o establece el tipo de bloqueo.

Valor: El tipo de la cerradura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPositionProtected(boolean value) {#setPositionProtected-boolean-}
```
public final void setPositionProtected(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está protegida de posición.

Valor:  true  si esta instancia está protegida por posición; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setTransparencyProtected(boolean value) {#setTransparencyProtected-boolean-}
```
public final void setTransparencyProtected(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está protegida de transparencia.

Valor:  true  si esta instancia está protegida por transparencia; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

