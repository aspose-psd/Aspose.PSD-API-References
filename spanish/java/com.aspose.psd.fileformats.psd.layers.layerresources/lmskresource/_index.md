---
title: "LmskResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El recurso LMsk."
type: docs
weight: 50
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LmskResource extends LayerResource
```

El recurso LMsk.

--------------------

Este recurso contiene el ID del espacio de color, que se refiere a un tipo específico de espacio de color, y 4 componentes de color. Dependiendo del ID, los componentes de color tienen diferentes significados. Si el tipo de espacio de color no requiere cuatro valores, los componentes adicionales son indefinidos y siempre se escriben como ceros. Componentes de color por tipos de espacio de color: RGB - los tres primeros componentes son rojo, verde y azul. HSB - los tres primeros componentes son tono, saturación y brillo. CMYK - los cuatro componentes son cian, magenta, amarillo y negro. Lab - los tres primeros componentes son luminosidad, crominancia a y crominancia b. Grayscale - el primer componente es el valor de gris, de 0...10000.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LmskResource()](#LmskResource--) | Inicializa una nueva instancia de la clase [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource). |
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
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorComponent1()](#getColorComponent1--) | Obtiene el componente de color 1. |
| [getColorComponent2()](#getColorComponent2--) | Obtiene el componente de color 2. |
| [getColorComponent3()](#getColorComponent3--) | Obtiene el componente de color 3. |
| [getColorComponent4()](#getColorComponent4--) | Obtiene el componente de color 4. |
| [getColorSpace()](#getColorSpace--) | Obtiene el espacio de color. |
| [getFlag()](#getFlag--) | Obtiene la bandera. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de capa en bytes. |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el recurso en el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setColorComponent1(int value)](#setColorComponent1-int-) | Obtiene el componente de color 1. |
| [setColorComponent2(int value)](#setColorComponent2-int-) | Obtiene el componente de color 2. |
| [setColorComponent3(int value)](#setColorComponent3-int-) | Obtiene el componente de color 3. |
| [setColorComponent4(int value)](#setColorComponent4-int-) | Obtiene el componente de color 4. |
| [setColorSpace(int value)](#setColorSpace-int-) | Obtiene el espacio de color. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setOpacity(short value)](#setOpacity-short-) | Obtiene la opacidad. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LmskResource() {#LmskResource--}
```
public LmskResource()
```


Inicializa una nueva instancia de la clase [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource).

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static LmskResource create_internalized(byte[] data)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] |  |

**Returns:**
[LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource)
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
### getColorComponent1() {#getColorComponent1--}
```
public final int getColorComponent1()
```


Obtiene el componente de color 1.

Valor: El componente de color 1.

**Returns:**
int
### getColorComponent2() {#getColorComponent2--}
```
public final int getColorComponent2()
```


Obtiene el componente de color 2.

Valor: El componente de color 2.

**Returns:**
int
### getColorComponent3() {#getColorComponent3--}
```
public final int getColorComponent3()
```


Obtiene el componente de color 3.

Valor: El componente de color 3.

**Returns:**
int
### getColorComponent4() {#getColorComponent4--}
```
public final int getColorComponent4()
```


Obtiene el componente de color 4.

Valor: El componente de color 4.

**Returns:**
int
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


Obtiene el espacio de color.

Valor: El espacio de color.

**Returns:**
int
### getFlag() {#getFlag--}
```
public final byte getFlag()
```


Obtiene la bandera.

Valor: La bandera.

**Returns:**
byte
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
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


Obtiene la opacidad.

Valor: La opacidad.

**Returns:**
short
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

### setColorComponent1(int value) {#setColorComponent1-int-}
```
public final void setColorComponent1(int value)
```


Obtiene el componente de color 1.

Valor: El componente de color 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorComponent2(int value) {#setColorComponent2-int-}
```
public final void setColorComponent2(int value)
```


Obtiene el componente de color 2.

Valor: El componente de color 2.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorComponent3(int value) {#setColorComponent3-int-}
```
public final void setColorComponent3(int value)
```


Obtiene el componente de color 3.

Valor: El componente de color 3.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorComponent4(int value) {#setColorComponent4-int-}
```
public final void setColorComponent4(int value)
```


Obtiene el componente de color 4.

Valor: El componente de color 4.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


Obtiene el espacio de color.

Valor: El espacio de color.

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

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


Obtiene la opacidad.

Valor: La opacidad.

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

