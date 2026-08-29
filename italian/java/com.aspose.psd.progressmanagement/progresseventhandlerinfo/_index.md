---
title: "ProgressEventHandlerInfo"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Questa classe rappresenta le informazioni sul progresso delle operazioni di caricamento/salvataggio/esportazione delle immagini che possono essere utilizzate in un'applicazione esterna per mostrare il progresso della conversione all'utente finale."
type: docs
weight: 10
url: /it/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Questa classe rappresenta le informazioni sul progresso delle operazioni di caricamento/salvataggio/esportazione dell'immagine, che possono essere utilizzate in un'applicazione esterna per mostrare all'utente finale il progresso della conversione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Aggiunge il gestore dell'evento di progresso. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Ottiene la descrizione dell'evento |
| [getEventType()](#getEventType--) | Ottiene il tipo dell'evento. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Ottiene l'ultimo gestore dell'evento di progresso. |
| [getMaxValue()](#getMaxValue--) | Ottiene il limite superiore del valore di progresso. |
| [getValue()](#getValue--) | Ottiene il valore di progresso corrente. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica il progresso. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Indica il progresso. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | Il limite superiore del valore di progresso. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Valore di progresso corrente. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Aggiunge il gestore dell'evento di progresso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Il gestore dell'evento di progresso. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| totale | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene la descrizione dell'evento

Valore: La descrizione.

**Returns:**
java.lang.String - la descrizione dell'evento
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Ottiene il tipo dell'evento.

Valore: Il tipo dell'evento.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Ottiene l'ultimo gestore dell'evento di progresso.

Valore: L'ultimo gestore dell'evento di progresso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Ottiene il limite superiore del valore di progresso.

Valore: Il limite superiore del valore di progresso.

**Returns:**
int - il limite superiore del valore di progresso.
### getValue() {#getValue--}
```
public final int getValue()
```


Ottiene il valore di progresso corrente.

Valore: Il valore di progresso.

**Returns:**
int - valore di progresso corrente.
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


Indica il progresso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Tipo dell'evento. |

**Returns:**
boolean - true se riuscito, false altrimenti
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Indica il progresso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Tipo dell'evento. |
| valore | int | Il valore. |

**Returns:**
boolean - true se riuscito, false altrimenti
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


Il limite superiore del valore di progresso.

Valore: Il limite superiore del valore di progresso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il limite superiore del valore di avanzamento. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Valore di progresso corrente.

Valore: Il valore di progresso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | valore di avanzamento corrente. |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

