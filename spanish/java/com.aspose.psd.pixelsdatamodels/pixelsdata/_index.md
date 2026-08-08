---
title: "PixelsData"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La clase para almacenar datos de píxeles de imagen y sus límites."
type: docs
weight: 10
url: /es/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

La clase para almacenar datos de píxeles de imagen y sus límites.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PixelsData()](#PixelsData--) | Inicializa una nueva instancia de la clase [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
## Métodos

| Método | Descripción |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | Crea la instancia PixelsDataLoader para la instancia actual de [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [createSaver_internalized()](#createSaver-internalized--) | Crea la instancia PixelsDataSaver para la instancia actual de [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [deepClone()](#deepClone--) | Crea una copia completa de la instancia |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtiene o establece los límites de los datos de píxeles. |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | Obtiene o establece los datos de píxeles. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtiene o establece los límites de los datos de píxeles. |
| [setPixels(int[] value)](#setPixels-int---) | Obtiene o establece los datos de píxeles. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


Inicializa una nueva instancia de la clase [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


Inicializa una nueva instancia de la clase [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los datos de píxeles. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de límites de los píxeles. |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


Crea la instancia PixelsDataLoader para la instancia actual de [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


Crea la instancia PixelsDataSaver para la instancia actual de [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
com.aspose.internal.IPixelsSaver - La nueva instancia de PixelsDataSaver basada en la instancia actual de [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea una copia completa de la instancia

**Returns:**
java.lang.Object - La copia de la instancia
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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtiene o establece los límites de los datos de píxeles.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


Obtiene o establece los datos de píxeles.

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Obtiene o establece los límites de los datos de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


Obtiene o establece los datos de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

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

