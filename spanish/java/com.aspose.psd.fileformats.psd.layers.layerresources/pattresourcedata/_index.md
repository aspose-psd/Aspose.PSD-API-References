---
title: "PattResourceData"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La clase para almacenar los datos de patrón para el recurso."
type: docs
weight: 67
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

La clase para almacenar los datos de patrón para el recurso [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Inicializa una nueva instancia de la clase [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## Métodos

| Método | Descripción |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Devuelve el código del método de compresión obtenido de los canales del patrón\\u2019s. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Crea los datos de patrón predeterminados. |
| [getHeight()](#getHeight--) | Obtiene la altura. |
| [getImageMode()](#getImageMode--) | Obtiene el modo de imagen. |
| [getLength()](#getLength--) | Obtiene la longitud del patrón. |
| [getName()](#getName--) | Obtiene o establece el nombre. |
| [getPatternData()](#getPatternData--) | Obtiene los datos del patrón. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | La lista de matriz de memoria. |
| [getPatternId()](#getPatternId--) | Obtiene o establece el identificador del patrón. |
| [getVersion()](#getVersion--) | Obtiene la versión. |
| [getWidth()](#getWidth--) | Obtiene el ancho. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Guarda los datos del patrón. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Obtiene la altura. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Obtiene el modo de imagen. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Obtiene o establece la tabla de colores de índice. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Establece el búfer de píxeles del patrón y el tamaño objetivo, actualiza  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), y almacena los datos para guardarlos usando el modo de compresión predeterminado (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | La lista de matriz de memoria. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Obtiene o establece el identificador del patrón. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Establece el búfer de píxeles del patrón y el tamaño objetivo, actualiza  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), y almacena los datos para guardarlos usando el modo de compresión especificado. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Obtiene la versión. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Obtiene el ancho. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Inicializa una nueva instancia de la clase [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Devuelve el código del método de compresión obtenido de los canales del patrón\\u2019s.

**Returns:**
byte - Código de compresión: 0 \\u2014 sin compresión; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


Crea los datos de patrón predeterminados.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Obtiene la altura.

Valor: La altura.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Obtiene el modo de imagen.

Valor: El modo de imagen.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Obtiene la longitud del patrón.

Valor: La longitud del patrón.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtiene o establece el nombre.

Valor: El nombre.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Obtiene los datos del patrón.

Valor: Los datos del patrón.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


La lista de matriz de memoria.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Obtiene o establece el identificador del patrón.

Valor: El identificador del patrón.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtiene la versión.

Valor: La versión.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Obtiene el ancho.

Valor: El ancho.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Guarda los datos del patrón.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Obtiene la altura.

Valor: La altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Obtiene el modo de imagen.

Valor: El modo de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Obtiene o establece la tabla de colores de índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtiene o establece el nombre.

Valor: El nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Establece el búfer de píxeles del patrón y el tamaño objetivo, actualiza  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), y almacena los datos para guardarlos usando el modo de compresión predeterminado (0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Píxeles de 32 bits en formato 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Límites de píxeles del patrón. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


La lista de matriz de memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Obtiene o establece el identificador del patrón.

Valor: El identificador del patrón.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Establece el búfer de píxeles del patrón y el tamaño objetivo, actualiza  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), y almacena los datos para guardarlos usando el modo de compresión especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Píxeles de 32 bits en formato 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Límites de píxeles del patrón. |
| compressionMode | byte | El modo de compresión utilizado para definir la compresión de los datos del patrón al guardar el archivo psd. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Obtiene la versión.

Valor: La versión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Obtiene el ancho.

Valor: El ancho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

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

