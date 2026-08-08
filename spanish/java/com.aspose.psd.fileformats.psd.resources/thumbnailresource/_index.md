---
title: "ThumbnailResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El bloque de recurso de miniatura."
type: docs
weight: 36
url: /es/java/com.aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class ThumbnailResource extends ResourceBlock
```

El bloque de recurso de miniatura.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ThumbnailResource()](#ThumbnailResource--) | Inicializa una nueva instancia de la clase [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | La firma del recurso de ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | La firma regular del recurso de Photoshop. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Obtiene o establece los bits del píxel. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Obtiene el tamaño de los datos del recurso en bytes. |
| [getFormat()](#getFormat--) | Obtiene o establece el formato de datos de la miniatura. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura de la miniatura en píxeles. |
| [getID()](#getID--) | Obtiene o establece el identificador único del recurso. |
| [getJpegOptions()](#getJpegOptions--) | Obtiene o establece las opciones JPEG. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtiene la versión mínima requerida de PSD. |
| [getName()](#getName--) | Obtiene o establece el nombre del recurso. |
| [getPlanesCount()](#getPlanesCount--) | Obtiene o establece el recuento de planos. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso. |
| [getSize()](#getSize--) | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Obtiene o establece el tamaño después de la compresión. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Obtiene o establece los datos de la miniatura ARGB de 32 bits. |
| [getThumbnailData()](#getThumbnailData--) | Obtiene o establece los datos de la miniatura. |
| [getTotalSize()](#getTotalSize--) | Obtiene el tamaño total de los datos. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho de la miniatura en píxeles. |
| [getWidthBytes()](#getWidthBytes--) | Obtiene el ancho de fila en bytes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Guarda el bloque de recurso en el flujo especificado. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Obtiene o establece los bits del píxel. |
| [setFormat(int value)](#setFormat-int-) | Obtiene o establece el formato de datos de la miniatura. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece la altura de la miniatura en píxeles. |
| [setID(short value)](#setID-short-) | Obtiene o establece el identificador único del recurso. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Obtiene o establece las opciones JPEG. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtiene o establece la información de capa y máscara. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre del recurso. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Obtiene o establece el recuento de planos. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtiene o establece el estado del bloque de recurso. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Obtiene o establece los datos de la miniatura ARGB de 32 bits. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Obtiene o establece los datos de la miniatura. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece el ancho de la miniatura en píxeles. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valida los valores del recurso. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ThumbnailResource() {#ThumbnailResource--}
```
public ThumbnailResource()
```


Inicializa una nueva instancia de la clase [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


La firma del recurso de ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


La firma regular del recurso de Photoshop.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Obtiene o establece los bits del píxel.

Valor: Los bits del píxel de la miniatura.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtiene el tamaño de los datos del recurso en bytes.

Valor: El tamaño de los datos del recurso.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Obtiene o establece el formato de datos de la miniatura.

Valor: El formato de datos de la miniatura.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene o establece la altura de la miniatura en píxeles.

Valor: La altura de la miniatura.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Obtiene o establece el identificador único del recurso.

Valor: El identificador único del recurso.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Obtiene o establece las opciones JPEG. Adecuado cuando el recurso de miniatura se guarda solo en formato de archivo JPEG. Esta opción no tiene efecto cuando se define el formato RAW.

Valor: Las opciones JPEG.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Obtiene la versión mínima requerida de PSD.

Valor: La versión mínima de psd.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0).

Valor: El nombre del recurso.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Obtiene o establece el recuento de planos.

Valor: El recuento de planos de la miniatura.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Obtiene la firma del recurso. Debe ser siempre '8BIM'.

Valor: La firma del recurso.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos.

Valor: El tamaño del bloque de recurso.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Obtiene o establece el tamaño después de la compresión. Utilizado para la verificación de consistencia.

Valor: El tamaño después de la compresión.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Obtiene o establece los datos de la miniatura ARGB de 32 bits.

Valor: Los datos de la miniatura ARGB de 32 bits.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Obtiene o establece los datos de la miniatura.

Valor: Los datos de la miniatura.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Obtiene el tamaño total de los datos.

Valor: El tamaño total de los datos.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene o establece el ancho de la miniatura en píxeles.

Valor: El ancho de la miniatura.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Obtiene el ancho de fila en bytes.

Valor: El ancho de fila en bytes.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Guarda el bloque de recurso en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | El flujo donde guardar el bloque de recurso. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Obtiene o establece los bits del píxel.

Valor: Los bits del píxel de la miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Obtiene o establece el formato de datos de la miniatura.

Valor: El formato de datos de la miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Obtiene o establece la altura de la miniatura en píxeles.

Valor: La altura de la miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Obtiene o establece el identificador único del recurso.

Valor: El identificador único del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Obtiene o establece las opciones JPEG. Adecuado cuando el recurso de miniatura se guarda solo en formato de archivo JPEG. Esta opción no tiene efecto cuando se define el formato RAW.

Valor: Las opciones JPEG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Obtiene o establece la información de capa y máscara.

Valor: La información de capa y máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0).

Valor: El nombre del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Obtiene o establece el recuento de planos.

Valor: El recuento de planos de la miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firma | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Obtiene o establece el estado del bloque de recurso.

Valor: El estado del bloque de recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Obtiene o establece los datos de la miniatura ARGB de 32 bits.

Valor: Los datos de la miniatura ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Obtiene o establece los datos de la miniatura.

Valor: Los datos de la miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Obtiene o establece el ancho de la miniatura en píxeles.

Valor: El ancho de la miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Valida los valores del recurso.

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

