---
title: "ProgressEventHandlerInfo"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Esta clase representa información sobre el progreso de las operaciones de carga/guardado/exportación de imágenes que puede ser utilizada en una aplicación externa para mostrar el progreso de la conversión al usuario final."
type: docs
weight: 10
url: /es/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Esta clase representa información sobre el progreso de las operaciones de carga/guardado/exportación de imágenes, que puede ser utilizada en una aplicación externa para mostrar el progreso de la conversión al usuario final
## Métodos

| Método | Descripción |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Agrega el controlador de eventos de progreso. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtiene la descripción del evento |
| [getEventType()](#getEventType--) | Obtiene el tipo del evento. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Obtiene el controlador de eventos de progreso más reciente. |
| [getMaxValue()](#getMaxValue--) | Obtiene el límite superior del valor de progreso. |
| [getValue()](#getValue--) | Obtiene el valor de progreso actual. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica el progreso. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Indica el progreso. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | El límite superior del valor de progreso. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Valor de progreso actual. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Agrega el controlador de eventos de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | El controlador de eventos de progreso. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| total | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Obtiene la descripción del evento

Valor: La descripción.

**Returns:**
java.lang.String - la descripción del evento
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Obtiene el tipo del evento.

Valor: El tipo del evento.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Obtiene el controlador de eventos de progreso más reciente.

Valor: El controlador de eventos de progreso más reciente.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Obtiene el límite superior del valor de progreso.

Valor: El límite superior del valor de progreso.

**Returns:**
int - el límite superior del valor de progreso.
### getValue() {#getValue--}
```
public final int getValue()
```


Obtiene el valor de progreso actual.

Valor: El valor de progreso.

**Returns:**
int - valor de progreso actual.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


Indica el progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Tipo del evento. |

**Returns:**
boolean - true si tiene éxito, false de lo contrario
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Indica el progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Tipo del evento. |
| valor | int | El valor. |

**Returns:**
boolean - true si tiene éxito, false de lo contrario
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


El límite superior del valor de progreso.

Valor: El límite superior del valor de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el límite superior del valor de progreso. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Valor de progreso actual.

Valor: El valor de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | valor de progreso actual. |

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

