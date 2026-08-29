---
title: "LayerMaskDataFull"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define la clase LayerMaskDataFull que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene tanto máscaras de capa como vectoriales."
type: docs
weight: 22
url: /es/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Define la clase LayerMaskDataFull que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene tanto máscaras de capa como de vector. De lo contrario, se utiliza un [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). Los ImageData contienen la máscara raster y la máscara vectorial rasterizada combinadas. La longitud en bytes de ImageData debe ser igual a las propiedades MaskRectangle.Width \* MaskRectangle.Height.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Inicializa una nueva instancia de la clase [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clona la máscara de capa. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene o establece el color de fondo. |
| [getBottom()](#getBottom--) | Obtiene o establece la posición inferior de la máscara de capa. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Obtiene el tamaño de los datos de la máscara de capa. |
| [getDefaultColor()](#getDefaultColor--) | Obtiene o establece el color predeterminado. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Obtiene o establece la posición inferior de la máscara raster que encierra en la capa de imagen PSD. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Obtiene o establece la posición izquierda de la máscara raster que encierra en la capa del archivo PSD. |
| [getEnclosingRight()](#getEnclosingRight--) | Obtiene o establece la posición derecha de la máscara raster que encierra en la capa del archivo PSD. |
| [getEnclosingTop()](#getEnclosingTop--) | Obtiene o establece la posición superior de la máscara raster que encierra en la capa de imagen PSD. |
| [getFlags()](#getFlags--) | Obtiene o establece los indicadores de la máscara de capa. |
| [getHeight_internalized()](#getHeight-internalized--) | Obtiene la altura de la máscara. |
| [getImageData()](#getImageData--) | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD. |
| [getLeft()](#getLeft--) | Obtiene o establece la posición izquierda de la máscara de capa. |
| [getMaskRectangle()](#getMaskRectangle--) | Obtiene o establece el Rectangle de la máscara de la capa en el archivo PSD. |
| [getRealFlags()](#getRealFlags--) | Obtiene o establece los indicadores de máscara de capa que se usan para la máscara de usuario / raster. |
| [getRight()](#getRight--) | Obtiene o establece la posición derecha de la máscara de capa. |
| [getTop()](#getTop--) | Obtiene o establece la posición superior de la máscara de capa. |
| [getUserMaskData()](#getUserMaskData--) | Obtiene o establece los datos de la máscara de usuario (raster) de una capa en el archivo PSD. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Obtiene o establece el rectángulo de la máscara de usuario (envolvente) en la capa de imagen PSD. |
| [getWidth_internalized()](#getWidth-internalized--) | Obtiene el ancho de la máscara. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Guarda [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) en el StreamContainer especificado. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Obtiene o establece el color de fondo. |
| [setBottom(int value)](#setBottom-int-) | Obtiene o establece la posición inferior de la máscara de capa. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Obtiene o establece el color predeterminado. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Obtiene o establece la posición inferior de la máscara raster que encierra en la capa de imagen PSD. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Obtiene o establece la posición izquierda de la máscara raster que encierra en la capa del archivo PSD. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Obtiene o establece la posición derecha de la máscara raster que encierra en la capa del archivo PSD. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Obtiene o establece la posición superior de la máscara raster que encierra en la capa de imagen PSD. |
| [setFlags(byte value)](#setFlags-byte-) | Obtiene o establece los indicadores de la máscara de capa. |
| [setImageData(byte[] value)](#setImageData-byte---) | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD. |
| [setLeft(int value)](#setLeft-int-) | Obtiene o establece la posición izquierda de la máscara de capa. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Obtiene o establece el Rectangle de la máscara de la capa en el archivo PSD. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Obtiene o establece los indicadores de máscara de capa que se usan para la máscara de usuario / raster. |
| [setRight(int value)](#setRight-int-) | Obtiene o establece la posición derecha de la máscara de capa. |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la posición superior de la máscara de capa. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Obtiene o establece los datos de la máscara de usuario (raster) de una capa en el archivo PSD. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Obtiene o establece el rectángulo de la máscara de usuario (envolvente) en la capa de imagen PSD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Inicializa una nueva instancia de la clase [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Obtiene o establece el color de fondo.

Valor: El color de fondo.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Obtiene o establece la posición inferior de la máscara raster que encierra en la capa de imagen PSD.

Valor: La posición inferior de la máscara de capa.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Obtiene o establece la posición izquierda de la máscara raster que encierra en la capa del archivo PSD.

Valor: La posición izquierda de la máscara de capa.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Obtiene o establece la posición derecha de la máscara raster que encierra en la capa del archivo PSD.

Valor: La posición derecha de la máscara de capa.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Obtiene o establece la posición superior de la máscara raster que encierra en la capa de imagen PSD.

Valor: La posición superior de la máscara de capa.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Obtiene o establece los indicadores de máscara de capa que se usan para la máscara de usuario / raster. Para la máscara vectorial se usa la propiedad Flags.

Valor: Los indicadores reales de máscara de capa.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Obtiene o establece los datos de la máscara de usuario (raster) de una capa en el archivo PSD. (Hay una máscara vectorial rasterizada en la propiedad MaskData).

Valor: Los datos de imagen de la capa en la imagen PSD.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Obtiene o establece el rectángulo de la máscara de usuario (envolvente) en la capa de imagen PSD.

Valor: El rectángulo de la máscara de usuario.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Obtiene o establece el color de fondo.

Valor: El color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Obtiene o establece la posición inferior de la máscara raster que encierra en la capa de imagen PSD.

Valor: La posición inferior de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Obtiene o establece la posición izquierda de la máscara raster que encierra en la capa del archivo PSD.

Valor: La posición izquierda de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Obtiene o establece la posición derecha de la máscara raster que encierra en la capa del archivo PSD.

Valor: La posición derecha de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Obtiene o establece la posición superior de la máscara raster que encierra en la capa de imagen PSD.

Valor: La posición superior de la máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Obtiene o establece los indicadores de máscara de capa que se usan para la máscara de usuario / raster. Para la máscara vectorial se usa la propiedad Flags.

Valor: Los indicadores reales de máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Obtiene o establece los datos de la máscara de usuario (raster) de una capa en el archivo PSD. (Hay una máscara vectorial rasterizada en la propiedad MaskData).

Valor: Los datos de imagen de la capa en la imagen PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Obtiene o establece el rectángulo de la máscara de usuario (envolvente) en la capa de imagen PSD.

Valor: El rectángulo de la máscara de usuario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

