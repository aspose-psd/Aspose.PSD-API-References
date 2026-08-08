---
title: "Txt2Resource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase de recurso Txt2"
type: docs
weight: 76
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class Txt2Resource extends LayerResource
```

Clase de recurso Txt2
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Txt2Resource()](#Txt2Resource--) | Inicializa una nueva instancia de la clase [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource). |
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
| [addTextRecord(String text, RectangleF bounds)](#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-) | Agrega el registro de texto a Resource y devuelve el id del registro de texto. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Comprueba y establece si el recurso es específico de PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Obtiene o establece los datos. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Obtiene si el recurso está comprimido. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de capa en bytes. |
| [getParsedTxt2Model_internalized()](#getParsedTxt2Model-internalized--) | Analiza los datos txt2 a una instancia de la clase Txt2DataRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [getTextData()](#getTextData--) | Obtiene el registro de texto de los datos del recurso. |
| [getText_internalized()](#getText-internalized--) | Obtiene o establece el nombre. |
| [getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Obtiene el TXT2 del árbol analizado. |
| [getTxt2ParsedTree_internalized()](#getTxt2ParsedTree-internalized--) | Obtiene el árbol analizado del TXT2. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTextRecord_internalized(int textIndex)](#removeTextRecord-internalized-int-) | Elimina el registro de texto de Resource. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece los datos. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setText_internalized(String value)](#setText-internalized-java.lang.String-) | Obtiene o establece el nombre. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)](#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-) | Actualiza el registro de texto por índice de texto con nuevos datos de texto predeterminados y nuevo texto, tamaño de fuente y color. |
| [updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)](#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-) | Actualiza los datos txt2 desde el modelo Txt2DataRoot. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Txt2Resource() {#Txt2Resource--}
```
public Txt2Resource()
```


Inicializa una nueva instancia de la clase [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource).

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

### addTextRecord(String text, RectangleF bounds) {#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-}
```
public final int addTextRecord(String text, RectangleF bounds)
```


Agrega el registro de texto a Resource y devuelve el id del registro de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | java.lang.String | El texto del registro. |
| bounds | [RectangleF](../../com.aspose.psd/rectanglef) | Los límites. |

**Returns:**
int - Devuelve el Id del registro de texto para el recurso
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
### getKey() {#getKey--}
```
public final int getKey()
```


Obtiene la clave del recurso de capa.

**Returns:**
int
### getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public static ITextEngineKeys getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Obtiene si el recurso está comprimido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| árbol | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | El árbol. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.ITextEngineKeys - Devuelve el objeto con claves.
### getLength() {#getLength--}
```
public int getLength()
```


Obtiene la longitud del recurso de capa en bytes.

**Returns:**
int
### getParsedTxt2Model_internalized() {#getParsedTxt2Model-internalized--}
```
public final Txt2DataRoot getParsedTxt2Model_internalized()
```


Analiza los datos txt2 a una instancia de la clase Txt2DataRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot - Los datos txt2 como una instancia de la clase Txt2DataRoot.
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
### getTextData() {#getTextData--}
```
public final String[] getTextData()
```


Obtiene el registro de texto de los datos del recurso.

**Returns:**
java.lang.String[] - Matriz de registro de texto
### getText_internalized() {#getText-internalized--}
```
public final String getText_internalized()
```


Obtiene o establece el nombre.

Valor: El nombre.

**Returns:**
java.lang.String
### getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public final String getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Obtiene el TXT2 del árbol analizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| árbol | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | El árbol de datos. |

**Returns:**
java.lang.String - Los datos Txt2.
### getTxt2ParsedTree_internalized() {#getTxt2ParsedTree-internalized--}
```
public final System.Collections.Generic.Dictionary<String,Object> getTxt2ParsedTree_internalized()
```


Obtiene el árbol analizado del TXT2.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> - Árbol analizado
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




### removeTextRecord_internalized(int textIndex) {#removeTextRecord-internalized-int-}
```
public final void removeTextRecord_internalized(int textIndex)
```


Elimina el registro de texto de Resource.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textIndex | int | El índice del registro de texto a eliminar. |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Guarda el contenedor de flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
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

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Obtiene o establece los datos.

Valor: Los datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

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

### setText_internalized(String value) {#setText-internalized-java.lang.String-}
```
public final void setText_internalized(String value)
```


Obtiene o establece el nombre.

Valor: El nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una String que representa esta instancia.

**Returns:**
java.lang.String - Una String que representa esta instancia.
### updateTextData_internalized(int textIndex, String newText, double fontSize, Color color) {#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-}
```
public final void updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)
```


Actualiza el registro de texto por índice de texto con nuevos datos de texto predeterminados y nuevo texto, tamaño de fuente y color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textIndex | int | El índice del registro de texto en los datos de recurso txt2. |
| newText | java.lang.String | El nuevo texto. |
| fontSize | double | el nuevo tamaño de fuente. |
| color | [Color](../../com.aspose.psd/color) | El nuevo color de texto. |

### updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot) {#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-}
```
public final void updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)
```


Actualiza los datos txt2 desde el modelo Txt2DataRoot.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| txt2DataRoot | com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot | El modelo de datos txt2. |

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

