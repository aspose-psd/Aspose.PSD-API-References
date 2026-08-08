---
title: "PsdLoadOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Opciones de carga PSD"
type: docs
weight: 12
url: /es/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Opciones de carga PSD
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Inicializa una nueva instancia de la clase [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Campos

| Campo | Descripción |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Las fuentes tipográficas personalizadas |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Obtiene o establece si se deben conservar los píxeles originales de la capa durante el renderizado si la capa no ha sido modificada. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Obtiene o establece si se debe guardar con la imagen renderizada, con o sin una transformación de deformación. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Obtiene el Color de fondo de la Imagen. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Obtiene el modo de recuperación de datos. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Obtiene un valor que indica si [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Obtiene o establece un valor que indica si [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Obtiene o establece un valor que indica si se ignorará el ancho fijo de la capa de texto PSD al ejecutar la operación UpdateText. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Obtiene o establece un valor que indica si [load effects resource] (por defecto el recurso no se carga). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene el controlador del evento de progreso. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Obtiene o establece un valor que indica si [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Obtiene o establece el modo de solo lectura usado al cargar una imagen PSD. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Obtiene o establece un valor que indica si [use disk for load effects resource] (por defecto se usa el disco para cargar el recurso de efectos, pero se puede usar memoria si es suficiente estableciendo este valor a false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Obtiene un valor que indica si se debe aplicar la conversión del perfil ICC. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Esto es parte del patrón de licencia de venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Obtiene o establece si se deben conservar los píxeles originales de la capa durante el renderizado si la capa no ha sido modificada. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Obtiene o establece si se debe guardar con la imagen renderizada, con o sin una transformación de deformación. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Establece el Color de fondo de la Imagen. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Establece el modo de recuperación de datos. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Establece un valor que indica si [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Obtiene o establece un valor que indica si [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Obtiene o establece un valor que indica si se ignorará el ancho fijo de la capa de texto PSD al ejecutar la operación UpdateText. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Obtiene o establece un valor que indica si [load effects resource] (por defecto el recurso no se carga). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Obtiene o establece el MGR de memoria. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Establece el controlador del evento de progreso. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Obtiene o establece un valor que indica si [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Obtiene o establece el modo de solo lectura usado al cargar una imagen PSD. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Obtiene o establece un valor que indica si [use disk for load effects resource] (por defecto se usa el disco para cargar el recurso de efectos, pero se puede usar memoria si es suficiente estableciendo este valor a false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Establece un valor que indica si se debe aplicar la conversión del perfil ICC. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Esto es parte del patrón de licencia de venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Inicializa una nueva instancia de la clase [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Las fuentes tipográficas personalizadas

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Obtiene o establece si se deben conservar los píxeles originales de la capa durante el renderizado si la capa no ha sido modificada.

Valor: true para conservar los píxeles originales de las capas sin cambios; de lo contrario, false.

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Obtiene o establece si se debe guardar con la imagen renderizada, con o sin una transformación de deformación.

Valor: true renderizar imagen con transformación de deformación; false.

**Returns:**
boolean
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int - la sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Obtiene el Color de fondo de la Imagen.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Normalmente el color de fondo se establece siempre que el valor del píxel no pueda recuperarse debido a corrupción de datos.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Obtiene el modo de recuperación de datos.

**Returns:**
int - El modo de recuperación de datos.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Obtiene un valor que indica si [ignore after load].

**Returns:**
boolean -  true  si [ignore after load]; de lo contrario,  false .
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Obtiene o establece un valor que indica si [ignore alpha channel].

Valor: true si [ignore alpha channel]; de lo contrario, false.

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Obtiene o establece un valor que indica si se ignorará el ancho fijo de la capa de texto PSD al ejecutar la operación UpdateText.

Valor: true si [ignore text layer width]; de lo contrario, false.

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Obtiene o establece un valor que indica si [load effects resource] (por defecto el recurso no se carga). Cuando se establece, solo los efectos compatibles se renderizarán en la imagen final combinada.

Valor: true si [load effects resource]; de lo contrario, false.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Obtiene el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Obtiene o establece un valor que indica si [use read only mode]. Este es el modo de solo lectura, compatible para una compatibilidad idéntica con Adobe Photoshop. Cuando esta opción está activada, todos los cambios aplicados a las capas no se guardarán en la imagen final. Todos los datos se usan de la sección ImageData, por lo que es idéntico a Photoshop. Por defecto, todas las imágenes cargadas no son compatibles idénticamente con Adobe Photoshop.

Valor: true si [use photoshop compatibility mode]; de lo contrario, false.

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Obtiene o establece el modo de solo lectura usado al cargar una imagen PSD.

Valor: Uno de los valores de ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Obtiene o establece un valor que indica si [use disk for load effects resource] (por defecto se usa el disco para cargar el recurso de efectos, pero se puede usar memoria si es suficiente estableciendo este valor a false).

Valor: true si [use disk for load effects resource]; de lo contrario, false.

**Returns:**
boolean
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Obtiene un valor que indica si se debe aplicar la conversión del perfil ICC.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Esto es parte del patrón de licencia de venture. Este valor será establecido por VentureLicenser si el venture nos pasa un objeto LoadOptions.

**Returns:**
java.lang.Object
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Obtiene o establece si se deben conservar los píxeles originales de la capa durante el renderizado si la capa no ha sido modificada.

Valor: true para conservar los píxeles originales de las capas sin cambios; de lo contrario, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Obtiene o establece si se debe guardar con la imagen renderizada, con o sin una transformación de deformación.

Valor: true renderizar imagen con transformación de deformación; false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Establece el Color de fondo de la Imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | El color de fondo. |

Normalmente el color de fondo se establece siempre que el valor del píxel no pueda recuperarse debido a corrupción de datos. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Establece el modo de recuperación de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de recuperación de datos. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Establece un valor que indica si [ignore after load].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true si [ignore after load]; de lo contrario, false. |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Obtiene o establece un valor que indica si [ignore alpha channel].

Valor: true si [ignore alpha channel]; de lo contrario, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Obtiene o establece un valor que indica si se ignorará el ancho fijo de la capa de texto PSD al ejecutar la operación UpdateText.

Valor: true si [ignore text layer width]; de lo contrario, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Obtiene o establece un valor que indica si [load effects resource] (por defecto el recurso no se carga). Cuando se establece, solo los efectos compatibles se renderizarán en la imagen final combinada.

Valor: true si [load effects resource]; de lo contrario, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Obtiene o establece el MGR de memoria.

Valor: La memoria MGR.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Establece el controlador del evento de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | el controlador de eventos de progreso. |

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Obtiene o establece un valor que indica si [use read only mode]. Este es el modo de solo lectura, compatible para una compatibilidad idéntica con Adobe Photoshop. Cuando esta opción está activada, todos los cambios aplicados a las capas no se guardarán en la imagen final. Todos los datos se usan de la sección ImageData, por lo que es idéntico a Photoshop. Por defecto, todas las imágenes cargadas no son compatibles idénticamente con Adobe Photoshop.

Valor: true si [use photoshop compatibility mode]; de lo contrario, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Obtiene o establece el modo de solo lectura usado al cargar una imagen PSD.

Valor: Uno de los valores de ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Obtiene o establece un valor que indica si [use disk for load effects resource] (por defecto se usa el disco para cargar el recurso de efectos, pero se puede usar memoria si es suficiente estableciendo este valor a false).

Valor: true si [use disk for load effects resource]; de lo contrario, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Establece un valor que indica si se debe aplicar la conversión del perfil ICC.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Esto es parte del patrón de licencia de venture. Este valor será establecido por VentureLicenser si el venture nos pasa un objeto LoadOptions.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

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

