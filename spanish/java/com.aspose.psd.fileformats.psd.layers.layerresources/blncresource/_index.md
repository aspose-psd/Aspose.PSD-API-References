---
title: "BlncResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La clase BlncResource es un recurso de capa de ajuste de color."
type: docs
weight: 14
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlncResource extends AdjustmentLayerResource
```

La clase BlncResource es un recurso de capa de ajuste de color.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BlncResource()](#BlncResource--) | Inicializa una nueva instancia de la clase [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [DataLength_internalized](#DataLength-internalized) | La longitud de datos esperada. |
| [HighlightsCyanRedBalanceExceptionMessage_internalized](#HighlightsCyanRedBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio cian rojo de resaltados fuera de rango. |
| [HighlightsMagentaGreenBalanceExceptionMessage_internalized](#HighlightsMagentaGreenBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio magenta verde de resaltados fuera de rango. |
| [HighlightsYellowBlueBalanceExceptionMessage_internalized](#HighlightsYellowBlueBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio amarillo azul de resaltados fuera de rango. |
| [MidtonesCyanRedBalanceExceptionMessage_internalized](#MidtonesCyanRedBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio cian rojo de tonos medios fuera de rango. |
| [MidtonesMagentaGreenBalanceExceptionMessage_internalized](#MidtonesMagentaGreenBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio magenta verde de tonos medios fuera de rango. |
| [MidtonesYellowBlueBalanceExceptionMessage_internalized](#MidtonesYellowBlueBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio amarillo azul de tonos medios fuera de rango. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versión del encabezado PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma de recurso específica de PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versión del encabezado PSD |
| [ResourceSignature](#ResourceSignature) | La firma de recurso común. |
| [ShadowsCyanRedBalanceExceptionMessage_internalized](#ShadowsCyanRedBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio cian rojo de sombras fuera de rango. |
| [ShadowsMagentaGreenBalanceExceptionMessage_internalized](#ShadowsMagentaGreenBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio magenta verde de sombras fuera de rango. |
| [ShadowsYellowBlueBalanceExceptionMessage_internalized](#ShadowsYellowBlueBalanceExceptionMessage-internalized) | El mensaje de excepción de equilibrio amarillo azul de sombras fuera de rango. |
| [TypeToolKey](#TypeToolKey) | La clave de información de la herramienta de tipo. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licencia venture. |
## Métodos

| Método | Descripción |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Comprueba y establece si el recurso es específico de PSB. |
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Obtiene o establece los datos. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getHighlightsCyanRedBalance()](#getHighlightsCyanRedBalance--) | Obtiene o establece el Balance Cian Rojo de los Highlights. |
| [getHighlightsMagentaGreenBalance()](#getHighlightsMagentaGreenBalance--) | Obtiene o establece el Balance Magenta Verde de los Highlights. |
| [getHighlightsYellowBlueBalance()](#getHighlightsYellowBlueBalance--) | Obtiene o establece el Balance Amarillo Azul de los Highlights. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de capa en bytes. |
| [getMidtonesCyanRedBalance()](#getMidtonesCyanRedBalance--) | Obtiene o establece el Balance Cian Rojo de los Midtones. |
| [getMidtonesMagentaGreenBalance()](#getMidtonesMagentaGreenBalance--) | Obtiene o establece el Balance Magenta Verde de los Midtones. |
| [getMidtonesYellowBlueBalance()](#getMidtonesYellowBlueBalance--) | Obtiene o establece el Balance Amarillo Azul de los Midtones. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Obtiene o establece un valor que indica si este [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosidad. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getShadowsCyanRedBalance()](#getShadowsCyanRedBalance--) | Obtiene o establece el Balance Cian Rojo de los Shadows. |
| [getShadowsMagentaGreenBalance()](#getShadowsMagentaGreenBalance--) | Obtiene o establece el Balance Magenta Verde de los Shadows. |
| [getShadowsYellowBlueBalance()](#getShadowsYellowBlueBalance--) | Obtiene o establece el equilibrio de sombras amarillo azul. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el recurso en el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setHighlightsCyanRedBalance(short value)](#setHighlightsCyanRedBalance-short-) | Obtiene o establece el Balance Cian Rojo de los Highlights. |
| [setHighlightsMagentaGreenBalance(short value)](#setHighlightsMagentaGreenBalance-short-) | Obtiene o establece el Balance Magenta Verde de los Highlights. |
| [setHighlightsYellowBlueBalance(short value)](#setHighlightsYellowBlueBalance-short-) | Obtiene o establece el Balance Amarillo Azul de los Highlights. |
| [setMidtonesCyanRedBalance(short value)](#setMidtonesCyanRedBalance-short-) | Obtiene o establece el Balance Cian Rojo de los Midtones. |
| [setMidtonesMagentaGreenBalance(short value)](#setMidtonesMagentaGreenBalance-short-) | Obtiene o establece el Balance Magenta Verde de los Midtones. |
| [setMidtonesYellowBlueBalance(short value)](#setMidtonesYellowBlueBalance-short-) | Obtiene o establece el Balance Amarillo Azul de los Midtones. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Obtiene o establece un valor que indica si este [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosidad. |
| [setShadowsCyanRedBalance(short value)](#setShadowsCyanRedBalance-short-) | Obtiene o establece el Balance Cian Rojo de los Shadows. |
| [setShadowsMagentaGreenBalance(short value)](#setShadowsMagentaGreenBalance-short-) | Obtiene o establece el Balance Magenta Verde de los Shadows. |
| [setShadowsYellowBlueBalance(short value)](#setShadowsYellowBlueBalance-short-) | Obtiene o establece el equilibrio de sombras amarillo azul. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlncResource() {#BlncResource--}
```
public BlncResource()
```


Inicializa una nueva instancia de la clase [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource).

### DataLength_internalized {#DataLength-internalized}
```
public static final int DataLength_internalized
```


La longitud de datos esperada.

### HighlightsCyanRedBalanceExceptionMessage_internalized {#HighlightsCyanRedBalanceExceptionMessage-internalized}
```
public static final String HighlightsCyanRedBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio cian rojo de resaltados fuera de rango.

### HighlightsMagentaGreenBalanceExceptionMessage_internalized {#HighlightsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String HighlightsMagentaGreenBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio magenta verde de resaltados fuera de rango.

### HighlightsYellowBlueBalanceExceptionMessage_internalized {#HighlightsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String HighlightsYellowBlueBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio amarillo azul de resaltados fuera de rango.

### MidtonesCyanRedBalanceExceptionMessage_internalized {#MidtonesCyanRedBalanceExceptionMessage-internalized}
```
public static final String MidtonesCyanRedBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio cian rojo de tonos medios fuera de rango.

### MidtonesMagentaGreenBalanceExceptionMessage_internalized {#MidtonesMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String MidtonesMagentaGreenBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio magenta verde de tonos medios fuera de rango.

### MidtonesYellowBlueBalanceExceptionMessage_internalized {#MidtonesYellowBlueBalanceExceptionMessage-internalized}
```
public static final String MidtonesYellowBlueBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio amarillo azul de tonos medios fuera de rango.

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

### ShadowsCyanRedBalanceExceptionMessage_internalized {#ShadowsCyanRedBalanceExceptionMessage-internalized}
```
public static final String ShadowsCyanRedBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio cian rojo de sombras fuera de rango.

### ShadowsMagentaGreenBalanceExceptionMessage_internalized {#ShadowsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String ShadowsMagentaGreenBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio magenta verde de sombras fuera de rango.

### ShadowsYellowBlueBalanceExceptionMessage_internalized {#ShadowsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String ShadowsYellowBlueBalanceExceptionMessage_internalized
```


El mensaje de excepción de equilibrio amarillo azul de sombras fuera de rango.

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
public static BlncResource create_internalized(byte[] data)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] |  |

**Returns:**
[BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource)
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
### getData() {#getData--}
```
public final byte[] getData()
```


Obtiene o establece los datos.

Valor: Los datos.

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHighlightsCyanRedBalance() {#getHighlightsCyanRedBalance--}
```
public final short getHighlightsCyanRedBalance()
```


Obtiene o establece el Balance Cian Rojo de los Highlights.

Valor: El equilibrio de resaltados cian rojo.

**Returns:**
short
### getHighlightsMagentaGreenBalance() {#getHighlightsMagentaGreenBalance--}
```
public final short getHighlightsMagentaGreenBalance()
```


Obtiene o establece el Balance Magenta Verde de los Highlights.

Valor: El equilibrio de resaltados magenta verde.

**Returns:**
short
### getHighlightsYellowBlueBalance() {#getHighlightsYellowBlueBalance--}
```
public final short getHighlightsYellowBlueBalance()
```


Obtiene o establece el Balance Amarillo Azul de los Highlights.

Valor: El equilibrio de resaltados amarillo azul.

**Returns:**
short
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
### getMidtonesCyanRedBalance() {#getMidtonesCyanRedBalance--}
```
public final short getMidtonesCyanRedBalance()
```


Obtiene o establece el Balance Cian Rojo de los Midtones.

Valor: El equilibrio de tonos medios cian rojo.

**Returns:**
short
### getMidtonesMagentaGreenBalance() {#getMidtonesMagentaGreenBalance--}
```
public final short getMidtonesMagentaGreenBalance()
```


Obtiene o establece el Balance Magenta Verde de los Midtones.

Valor: El equilibrio de tonos medios magenta verde.

**Returns:**
short
### getMidtonesYellowBlueBalance() {#getMidtonesYellowBlueBalance--}
```
public final short getMidtonesYellowBlueBalance()
```


Obtiene o establece el Balance Amarillo Azul de los Midtones.

Valor: El equilibrio de tonos medios amarillo azul.

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
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Obtiene o establece un valor que indica si este [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosidad.

Valor:  verdadero  si preserva la luminosidad; de lo contrario,  falso .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones.

**Returns:**
int
### getShadowsCyanRedBalance() {#getShadowsCyanRedBalance--}
```
public final short getShadowsCyanRedBalance()
```


Obtiene o establece el Balance Cian Rojo de los Shadows.

Valor: El equilibrio de sombras cian rojo.

**Returns:**
short
### getShadowsMagentaGreenBalance() {#getShadowsMagentaGreenBalance--}
```
public final short getShadowsMagentaGreenBalance()
```


Obtiene o establece el Balance Magenta Verde de los Shadows.

Valor: El equilibrio de sombras magenta verde.

**Returns:**
short
### getShadowsYellowBlueBalance() {#getShadowsYellowBlueBalance--}
```
public final short getShadowsYellowBlueBalance()
```


Obtiene o establece el equilibrio de sombras amarillo azul.

Valor: El equilibrio de sombras amarillo azul.

**Returns:**
short
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

### setHighlightsCyanRedBalance(short value) {#setHighlightsCyanRedBalance-short-}
```
public final void setHighlightsCyanRedBalance(short value)
```


Obtiene o establece el Balance Cian Rojo de los Highlights.

Valor: El equilibrio de resaltados cian rojo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setHighlightsMagentaGreenBalance(short value) {#setHighlightsMagentaGreenBalance-short-}
```
public final void setHighlightsMagentaGreenBalance(short value)
```


Obtiene o establece el Balance Magenta Verde de los Highlights.

Valor: El equilibrio de resaltados magenta verde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setHighlightsYellowBlueBalance(short value) {#setHighlightsYellowBlueBalance-short-}
```
public final void setHighlightsYellowBlueBalance(short value)
```


Obtiene o establece el Balance Amarillo Azul de los Highlights.

Valor: El equilibrio de resaltados amarillo azul.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setMidtonesCyanRedBalance(short value) {#setMidtonesCyanRedBalance-short-}
```
public final void setMidtonesCyanRedBalance(short value)
```


Obtiene o establece el Balance Cian Rojo de los Midtones.

Valor: El equilibrio de tonos medios cian rojo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setMidtonesMagentaGreenBalance(short value) {#setMidtonesMagentaGreenBalance-short-}
```
public final void setMidtonesMagentaGreenBalance(short value)
```


Obtiene o establece el Balance Magenta Verde de los Midtones.

Valor: El equilibrio de tonos medios magenta verde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setMidtonesYellowBlueBalance(short value) {#setMidtonesYellowBlueBalance-short-}
```
public final void setMidtonesYellowBlueBalance(short value)
```


Obtiene o establece el Balance Amarillo Azul de los Midtones.

Valor: El equilibrio de tonos medios amarillo azul.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Obtiene o establece un valor que indica si este [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosidad.

Valor:  verdadero  si preserva la luminosidad; de lo contrario,  falso .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setShadowsCyanRedBalance(short value) {#setShadowsCyanRedBalance-short-}
```
public final void setShadowsCyanRedBalance(short value)
```


Obtiene o establece el Balance Cian Rojo de los Shadows.

Valor: El equilibrio de sombras cian rojo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setShadowsMagentaGreenBalance(short value) {#setShadowsMagentaGreenBalance-short-}
```
public final void setShadowsMagentaGreenBalance(short value)
```


Obtiene o establece el Balance Magenta Verde de los Shadows.

Valor: El equilibrio de sombras magenta verde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setShadowsYellowBlueBalance(short value) {#setShadowsYellowBlueBalance-short-}
```
public final void setShadowsYellowBlueBalance(short value)
```


Obtiene o establece el equilibrio de sombras amarillo azul.

Valor: El equilibrio de sombras amarillo azul.

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

