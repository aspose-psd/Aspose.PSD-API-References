---
title: "GraphCutMaskingOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones de enmascarado automático GraphCut."
type: docs
weight: 14
url: /es/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

Las opciones de enmascarado automático GraphCut.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | El número de objeto de fondo |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Obtiene los argumentos para el algoritmo de segmentación. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Obtiene el color de reemplazo del fondo. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Obtiene un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo. |
| [getExportOptions()](#getExportOptions--) | Obtiene las opciones de exportación de imagen. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Obtiene el radio de difuminado. |
| [getMaskingArea()](#getMaskingArea--) | Obtiene el área de enmascaramiento. |
| [getMethod()](#getMethod--) | Obtiene el método de segmentación. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Establece los argumentos para el algoritmo de segmentación. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Establece el color de reemplazo del fondo. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Establece un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Establece las opciones de exportación de imagen. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Establece el radio de difuminado. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Establece el área de enmascaramiento. |
| [setMethod(int value)](#setMethod-int-) | Establece el método de segmentación. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


El número de objeto de fondo

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Obtiene los argumentos para el algoritmo de segmentación.

Valor: Los argumentos para el algoritmo de segmentación.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Obtiene el color de reemplazo del fondo.

Valor: El color de reemplazo del fondo. Este color se utilizará como color de fondo en las imágenes resultantes.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Obtiene un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo.

Valor:  true  si se descompone; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Obtiene las opciones de exportación de imagen.

Valor: Las opciones de exportación de imagen que se utilizarán para crear las imágenes resultantes.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Obtiene el radio de difuminado.

**Returns:**
int - el radio de difuminado.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Obtiene el área de enmascaramiento.

Valor: El área de enmascaramiento, que es una zona parcial de la imagen fuente. El valor Rectangle.Empty significa el área completa de la imagen fuente.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Obtiene el método de segmentación.

Valor: El método de segmentación.

**Returns:**
int - el método de segmentación.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Establece los argumentos para el algoritmo de segmentación.

Valor: Los argumentos para el algoritmo de segmentación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | los argumentos para el algoritmo de segmentación. |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Establece el color de reemplazo del fondo.

Valor: El color de reemplazo del fondo. Este color se utilizará como color de fondo en las imágenes resultantes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | el color de reemplazo del fondo. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Establece un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo.

Valor:  true  si se descompone; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si es innecesario separar cada Shape de la máscara como objeto individual o como objeto unido de la máscara separado del fondo. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Establece las opciones de exportación de imagen.

Valor: Las opciones de exportación de imagen que se utilizarán para crear las imágenes resultantes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | las opciones de exportación de imagen. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Establece el radio de difuminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el radio de difuminado. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Establece el área de enmascaramiento.

Valor: El área de enmascaramiento, que es una zona parcial de la imagen fuente. El valor Rectangle.Empty significa el área completa de la imagen fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | el área de enmascarado. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Establece el método de segmentación.

Valor: El método de segmentación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el método de segmentación. |

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

