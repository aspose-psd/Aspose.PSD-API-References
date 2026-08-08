---
title: "AutoMaskingGraphCutOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones de enmascarado automático GraphCut."
type: docs
weight: 12
url: /es/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Las opciones de enmascarado automático GraphCut.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Inicializa una nueva instancia de la clase [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## Campos

| Campo | Descripción |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | El número de objeto de fondo |
## Métodos

| Método | Descripción |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Agregar argumentos de auto enmascarado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Rellenar los trazos predeterminados. |
| [getArgs()](#getArgs--) | Obtiene los argumentos para el algoritmo de segmentación. |
| [getAssumedObjects()](#getAssumedObjects--) | Obtiene los objetos asumidos. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Obtiene el color de reemplazo del fondo. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Obtiene un valor que indica si los trazos predeterminados deben calcularse. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Obtiene el rectángulo combinado de objetos. |
| [getDecompose()](#getDecompose--) | Obtiene un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Obtiene los trazos predeterminados de fondo. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Obtiene los trazos predeterminados de primer plano precalculados. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Obtiene los rectángulos predeterminados de objetos. |
| [getExportOptions()](#getExportOptions--) | Obtiene las opciones de exportación de imagen. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Obtiene el radio de difuminado. |
| [getMaskingArea()](#getMaskingArea--) | Obtiene el área de enmascaramiento. |
| [getMethod()](#getMethod--) | Obtiene el método de segmentación. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Obtiene el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Obtiene un valor que indica si la colección de objetos asumidos contiene objetos humanos. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Establece los argumentos para el algoritmo de segmentación. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Establece los objetos asumidos. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Establece el color de reemplazo del fondo. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Establece un valor que indica si los trazos predeterminados deben calcularse. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | El rectángulo combinado de objetos. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Establece un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Los trazos de fondo predeterminados. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | Los trazos de primer plano predeterminados precalculados. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Los rectángulos de objetos predeterminados. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Establece las opciones de exportación de imagen. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Establece el radio de difuminado. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Un valor que indica si la colección de objetos asumidos contiene objetos humanos. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Establece el área de enmascaramiento. |
| [setMethod(int value)](#setMethod-int-) | Establece el método de segmentación. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Establece el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Inicializa una nueva instancia de la clase [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


El número de objeto de fondo

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Agregar argumentos de auto enmascarado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Rellenar los trazos predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Obtiene los argumentos para el algoritmo de segmentación.

Valor: Los argumentos para el algoritmo de segmentación.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Obtiene los objetos asumidos.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - los objetos asumidos.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Obtiene el color de reemplazo del fondo.

Valor: El color de reemplazo del fondo. Este color se utilizará como color de fondo en las imágenes resultantes.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Obtiene un valor que indica si los trazos predeterminados deben calcularse.

**Returns:**
boolean - un valor que indica si los trazos predeterminados deben ser calculados.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Obtiene el rectángulo combinado de objetos.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Obtiene un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo.

Valor:  true  si se descompone; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si es innecesario separar cada Forma de la máscara como objeto individual o como objeto unido de la máscara separado del fondo.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Obtiene los trazos predeterminados de fondo.

**Returns:**
com.aspose.psd.Point[] - los trazos de fondo predeterminados.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Obtiene los trazos predeterminados de primer plano precalculados.

**Returns:**
com.aspose.psd.Point[] - los trazos de primer plano predeterminados precalculados.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Obtiene los rectángulos predeterminados de objetos.

**Returns:**
com.aspose.psd.Rectangle[] - los rectángulos de objetos predeterminados.
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
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Obtiene el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados.

Valor: El controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Obtiene un valor que indica si la colección de objetos asumidos contiene objetos humanos.

**Returns:**
boolean - un valor que indica si la colección de objetos asumidos contiene objetos humanos.
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

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Establece los objetos asumidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | los objetos asumidos. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

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

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Establece un valor que indica si los trazos predeterminados deben calcularse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si los trazos predeterminados deben ser calculados. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


El rectángulo combinado de objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | el rectángulo combinado de objetos. |

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

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Los trazos de fondo predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | los trazos de fondo predeterminados. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


Los trazos de primer plano predeterminados precalculados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | los trazos de primer plano predeterminados precalculados. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Los rectángulos de objetos predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | los rectángulos de objetos predeterminados. |

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

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Un valor que indica si la colección de objetos asumidos contiene objetos humanos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si la colección de objetos asumidos contiene objetos humanos. |

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

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Establece el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados.

Valor: El controlador del evento de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados. |

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

