---
title: "PngLoadOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones de carga PNG."
type: docs
weight: 11
url: /es/java/com.aspose.psd.imageloadoptions/pngloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Las opciones de carga PNG.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Inicializa una nueva instancia de la clase PngLoadOptions. |
## Campos

| Campo | Descripción |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Las fuentes tipográficas personalizadas |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Obtiene el Color de fondo de la Imagen. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Obtiene el modo de recuperación de datos. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Obtiene un valor que indica si [ignore after load]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene el controlador del evento de progreso. |
| [getStrictMode()](#getStrictMode--) | Obtiene o establece un valor que indica si [strict mode]. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Obtiene un valor que indica si se debe aplicar la conversión del perfil ICC. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Esto es parte del patrón de licencia de venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Establece el Color de fondo de la Imagen. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Establece el modo de recuperación de datos. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Establece un valor que indica si [ignore after load]. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Obtiene o establece el MGR de memoria. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Establece el controlador del evento de progreso. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Obtiene o establece un valor que indica si [strict mode]. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Establece un valor que indica si se debe aplicar la conversión del perfil ICC. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Esto es parte del patrón de licencia de venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Inicializa una nueva instancia de la clase PngLoadOptions.

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
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Obtiene el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Obtiene o establece un valor que indica si [strict mode].

**Returns:**
boolean - un valor que indica si [strict mode].
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

### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Obtiene o establece un valor que indica si [strict mode].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [strict mode]. |

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

