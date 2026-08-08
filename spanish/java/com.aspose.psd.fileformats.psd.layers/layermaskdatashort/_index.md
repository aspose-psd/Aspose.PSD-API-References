---
title: "LayerMaskDataShort"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene solo una máscara raster o vectorial, pero no ambas."
type: docs
weight: 23
url: /es/java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene solo una máscara raster o vector, pero no ambas. De lo contrario, se utiliza un [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). Si la capa tiene solo una máscara raster, ImageData contiene los bytes de datos de la máscara raster. Si la capa tiene solo una máscara vector, ImageData contiene los bytes de datos rasterizados (en caché) de la máscara vector. Los bytes de LayerMaskData.ImageData ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) deben tener una longitud igual a Ancho \* Altura de LayerMaskData.MaskRectangle ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) propiedades.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | Inicializa una nueva instancia de la clase [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). |
## Métodos

| Método | Descripción |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clona la máscara de capa. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Obtiene o establece la posición inferior de la máscara de capa. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Obtiene el tamaño de los datos de la máscara de capa. |
| [getDefaultColor()](#getDefaultColor--) | Obtiene o establece el color predeterminado. |
| [getFlags()](#getFlags--) | Obtiene o establece los indicadores de la máscara de capa. |
| [getHeight_internalized()](#getHeight-internalized--) | Obtiene la altura de la máscara. |
| [getImageData()](#getImageData--) | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD. |
| [getLeft()](#getLeft--) | Obtiene o establece la posición izquierda de la máscara de capa. |
| [getMaskRectangle()](#getMaskRectangle--) | Obtiene o establece el Rectangle de la máscara de la capa en el archivo PSD. |
| [getPadding()](#getPadding--) | Obtiene o establece el relleno de la máscara de capa. |
| [getRight()](#getRight--) | Obtiene o establece la posición derecha de la máscara de capa. |
| [getTop()](#getTop--) | Obtiene o establece la posición superior de la máscara de capa. |
| [getWidth_internalized()](#getWidth-internalized--) | Obtiene el ancho de la máscara. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Guarda [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) en el StreamContainer especificado. |
| [setBottom(int value)](#setBottom-int-) | Obtiene o establece la posición inferior de la máscara de capa. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Obtiene o establece el color predeterminado. |
| [setFlags(byte value)](#setFlags-byte-) | Obtiene o establece los indicadores de la máscara de capa. |
| [setImageData(byte[] value)](#setImageData-byte---) | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD. |
| [setLeft(int value)](#setLeft-int-) | Obtiene o establece la posición izquierda de la máscara de capa. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Obtiene o establece el Rectangle de la máscara de la capa en el archivo PSD. |
| [setPadding(short value)](#setPadding-short-) | Obtiene o establece el relleno de la máscara de capa. |
| [setRight(int value)](#setRight-int-) | Obtiene o establece la posición derecha de la máscara de capa. |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la posición superior de la máscara de capa. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


Inicializa una nueva instancia de la clase [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort).

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Clona esta instancia.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Clona la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | La máscara. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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


Obtiene o establece la posición inferior de la máscara de capa.

Valor: La posición inferior de la máscara de capa.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Obtiene el tamaño de los datos de la máscara de capa.

Valor: El tamaño de los datos de máscara de capa.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Obtiene o establece el color predeterminado.

Valor: El color predeterminado.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Obtiene o establece los indicadores de la máscara de capa.

Valor: Las banderas de la máscara de capa.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Obtiene la altura de la máscara.

Valor: La altura.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD.

Valor: Los datos de la imagen.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtiene o establece la posición izquierda de la máscara de capa.

Valor: La posición izquierda de la máscara de capa.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Obtiene o establece el Rectangle de la máscara de capa en el archivo PSD. Toma las propiedades izquierda, derecha, superior e inferior y crea un Rectangle.

Valor: El rectángulo de la máscara.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getPadding() {#getPadding--}
```
public final short getPadding()
```


Obtiene o establece el relleno de la máscara de capa.

Valor: El relleno de la máscara de capa.

**Returns:**
short
### getRight() {#getRight--}
```
public final int getRight()
```


Obtiene o establece la posición derecha de la máscara de capa.

Valor: La posición derecha de la máscara de capa.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Obtiene o establece la posición superior de la máscara de capa.

Valor: La posición superior de la máscara de capa.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Obtiene el ancho de la máscara.

Valor: El ancho.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public void save_internalized(StreamContainer streamContainer)
```


Guarda [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) en el StreamContainer especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo para guardar los datos. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Obtiene o establece la posición inferior de la máscara de capa.

Valor: La posición inferior de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Obtiene o establece el color predeterminado.

Valor: El color predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Obtiene o establece los indicadores de la máscara de capa.

Valor: Las banderas de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD.

Valor: Los datos de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Obtiene o establece la posición izquierda de la máscara de capa.

Valor: La posición izquierda de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Obtiene o establece el Rectangle de la máscara de capa en el archivo PSD. Toma las propiedades izquierda, derecha, superior e inferior y crea un Rectangle.

Valor: El rectángulo de la máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


Obtiene o establece el relleno de la máscara de capa.

Valor: El relleno de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Obtiene o establece la posición derecha de la máscara de capa.

Valor: La posición derecha de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obtiene o establece la posición superior de la máscara de capa.

Valor: La posición superior de la máscara de capa.

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

