---
title: "AiLayerSection"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La sección de capa del formato Ai"
type: docs
weight: 15
url: /es/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

La sección de capa del formato Ai
## Métodos

| Método | Descripción |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Agrega la imagen raster. |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Obtiene o establece el componente de color azul. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Obtiene o establece el índice del color. |
| [getColorNumber()](#getColorNumber--) | Obtiene o establece el número de color. |
| [getData()](#getData--) | Obtiene los datos de cadena. |
| [getDimValue()](#getDimValue--) | Obtiene o establece el valor de atenuación como porcentaje. |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getGreen()](#getGreen--) | Obtiene o establece el componente de color verde. |
| [getName()](#getName--) | Obtiene o establece el nombre de la capa. |
| [getRasterImages()](#getRasterImages--) | Obtiene las imágenes raster. |
| [getRed()](#getRed--) | Obtiene o establece el componente de color rojo. |
| [getStream_internalized()](#getStream-internalized--) | Obtiene el flujo interno |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Obtiene o establece un valor que indica si esta instancia tiene máscaras multilayer. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Obtiene o establece un valor que indica si esta capa está atenuada. |
| [isLocked()](#isLocked--) | Obtiene o establece un valor que indica si esta capa está bloqueada. |
| [isPreview()](#isPreview--) | Obtiene o establece un valor que indica si esta capa está en vista previa. |
| [isPrinted()](#isPrinted--) | Obtiene o establece un valor que indica si esta capa está impresa. |
| [isShown()](#isShown--) | Obtiene o establece un valor que indica si esta capa se muestra. |
| [isTemplate()](#isTemplate--) | Obtiene o establece un valor que indica si esta capa es una capa de plantilla. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Obtiene o establece el componente de color azul. |
| [setColorIndex(int value)](#setColorIndex-int-) | Obtiene o establece el índice del color. |
| [setColorNumber(int value)](#setColorNumber-int-) | Obtiene o establece el número de color. |
| [setDimValue(int value)](#setDimValue-int-) | Obtiene o establece el valor de atenuación como porcentaje. |
| [setGreen(int value)](#setGreen-int-) | Obtiene o establece el componente de color verde. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Obtiene o establece un valor que indica si esta capa está atenuada. |
| [setLocked(boolean value)](#setLocked-boolean-) | Obtiene o establece un valor que indica si esta capa está bloqueada. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Obtiene o establece un valor que indica si esta instancia tiene máscaras multilayer. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre de la capa. |
| [setPreview(boolean value)](#setPreview-boolean-) | Obtiene o establece un valor que indica si esta capa está en vista previa. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Obtiene o establece un valor que indica si esta capa está impresa. |
| [setRed(int value)](#setRed-int-) | Obtiene o establece el componente de color rojo. |
| [setShown(boolean value)](#setShown-boolean-) | Obtiene o establece un valor que indica si esta capa se muestra. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Obtiene o establece un valor que indica si esta capa es una capa de plantilla. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Agrega la imagen raster.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | La imagen raster. |

### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |
| propiedades | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Obtiene o establece el componente de color azul.

Valor: El componente de color azul.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Obtiene o establece el índice del color. Este argumento puede tomar valores entre \\u20131 y 26. Cada entero representa un color que puede asignarse a la capa para propósitos de identificación del usuario.

Valor: El índice del color.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Obtiene o establece el número de color. -1 es el valor de color personalizado de las propiedades Rojo, Verde, Azul. Especifica la configuración de color de la capa\\u2019s.

Valor: El número de color.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Obtiene los datos de cadena.

**Returns:**
java.lang.String - Los datos de cadena de la sección
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Obtiene o establece el valor de atenuación como porcentaje. Reduce la intensidad de las imágenes vinculadas y de las imágenes bitmap contenidas en la capa al porcentaje especificado.

Valor: El valor de atenuación como porcentaje.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Obtiene o establece el componente de color verde.

Valor: El componente de color verde.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtiene o establece el nombre de la capa. Especifica el nombre del elemento tal como aparece en el panel Capas.

Valor: El nombre de la capa.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Obtiene las imágenes raster.

Valor: Las imágenes raster.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Obtiene o establece el componente de color rojo.

Valor: El componente de color rojo.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Obtiene el flujo interno

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Obtiene o establece un valor que indica si esta instancia tiene máscaras multilayer.

Valor:  true  si esta instancia tiene máscaras multilayer; de lo contrario,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Obtiene o establece un valor que indica si esta capa está atenuada. Reduce la intensidad de las imágenes vinculadas y de las imágenes bitmap contenidas en la capa.

Valor:  true  si esta capa está atenuada; de lo contrario,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtiene o establece un valor que indica si esta capa está bloqueada. Impide cambios en el elemento.

Valor:  true  si esta capa está bloqueada; de lo contrario,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Obtiene o establece un valor que indica si esta capa está en vista previa. Muestra el arte contenido en la capa en color en lugar de como contornos.

Valor:  true  si esta capa está en vista previa; de lo contrario,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Obtiene o establece un valor que indica si esta capa se imprimirá. Hace que el arte contenido en la capa sea imprimible si es true.

Valor:  true  si esta capa se imprimirá; de lo contrario,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Obtiene o establece un valor que indica si esta capa se muestra. Muestra todo el arte contenido en la capa en la mesa de trabajo si es true.

Valor:  true  si esta capa se muestra; de lo contrario,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Obtiene o establece un valor que indica si esta capa es una capa de plantilla.

Valor:  true  si esta capa es una plantilla; de lo contrario,  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Obtiene o establece el componente de color azul.

Valor: El componente de color azul.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Obtiene o establece el índice del color. Este argumento puede tomar valores entre \\u20131 y 26. Cada entero representa un color que puede asignarse a la capa para propósitos de identificación del usuario.

Valor: El índice del color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Obtiene o establece el número de color. -1 es el valor de color personalizado de las propiedades Rojo, Verde, Azul. Especifica la configuración de color de la capa\\u2019s.

Valor: El número de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Obtiene o establece el valor de atenuación como porcentaje. Reduce la intensidad de las imágenes vinculadas y de las imágenes bitmap contenidas en la capa al porcentaje especificado.

Valor: El valor de atenuación como porcentaje.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Obtiene o establece el componente de color verde.

Valor: El componente de color verde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Obtiene o establece un valor que indica si esta capa está atenuada. Reduce la intensidad de las imágenes vinculadas y de las imágenes bitmap contenidas en la capa.

Valor:  true  si esta capa está atenuada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Obtiene o establece un valor que indica si esta capa está bloqueada. Impide cambios en el elemento.

Valor:  true  si esta capa está bloqueada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Obtiene o establece un valor que indica si esta instancia tiene máscaras multilayer.

Valor:  true  si esta instancia tiene máscaras multilayer; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtiene o establece el nombre de la capa. Especifica el nombre del elemento tal como aparece en el panel Capas.

Valor: El nombre de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Obtiene o establece un valor que indica si esta capa está en vista previa. Muestra el arte contenido en la capa en color en lugar de como contornos.

Valor:  true  si esta capa está en vista previa; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Obtiene o establece un valor que indica si esta capa se imprimirá. Hace que el arte contenido en la capa sea imprimible si es true.

Valor:  true  si esta capa se imprimirá; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Obtiene o establece el componente de color rojo.

Valor: El componente de color rojo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Obtiene o establece un valor que indica si esta capa se muestra. Muestra todo el arte contenido en la capa en la mesa de trabajo si es true.

Valor:  true  si esta capa se muestra; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Obtiene o establece un valor que indica si esta capa es una capa de plantilla.

Valor:  true  si esta capa es una plantilla; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

