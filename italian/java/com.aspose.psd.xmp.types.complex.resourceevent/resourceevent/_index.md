---
title: "ResourceEvent"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Contiene le dimensioni per un oggetto disegnato."
type: docs
weight: 10
url: /it/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Contiene le dimensioni per un oggetto disegnato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Inizializza una nuova istanza della classe  ResourceEvent  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Aggiunge la chiave specificata. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Ottiene l'azione. |
| [getActionDate()](#getActionDate--) | Ottiene o imposta la data dell'azione. |
| [getChanged()](#getChanged--) | Ottiene l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia dell'evento precedente. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Ottiene il valore di xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Ottiene l'URI dello spazio dei nomi predefinito. |
| [getParameters()](#getParameters--) | Ottiene o imposta la descrizione aggiuntiva dell'azione. |
| [getPrefix()](#getPrefix--) | Ottiene il prefisso. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Ottiene o imposta il nome dell'agente software. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore stringa contenuto in formato XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Imposta l'azione. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Ottiene o imposta la data dell'azione. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Imposta l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia dell'evento precedente. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Ottiene o imposta il valore di xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Ottiene o imposta la descrizione aggiuntiva dell'azione. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Ottiene o imposta il nome dell'agente software. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Inizializza una nuova istanza della classe  ResourceEvent  .

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Aggiunge la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | java.lang.Object | Il valore a cui aggiungere. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Ottiene l'azione.

I valori definiti sono: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. I nuovi valori dovrebbero essere verbi al passato.

**Returns:**
java.lang.String - L'azione.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Ottiene o imposta la data dell'azione.

**Returns:**
java.util.Date - La data dell'azione.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Ottiene l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia dell'evento precedente.

**Returns:**
java.lang.String - L'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia dell'evento precedente.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Ottiene il valore di xmpMM:InstanceId.

**Returns:**
java.util.UUID - Il valore di xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ottiene l'URI dello spazio dei nomi predefinito.

**Returns:**
java.lang.String - L'URI di spazio dei nomi predefinito.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Ottiene o imposta la descrizione aggiuntiva dell'azione.

Valore: La descrizione aggiuntiva dell'azione.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ottiene il prefisso.

**Returns:**
java.lang.String - Il prefisso.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Ottiene o imposta il nome dell'agente software.

**Returns:**
java.lang.String - Il nome dell'agente software.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Ottiene il valore stringa contenuto in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore stringa contenuto in formato XMP.
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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Imposta l'azione.

I valori definiti sono: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. I nuovi valori dovrebbero essere verbi al passato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | L'azione. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Ottiene o imposta la data dell'azione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date | La data dell'azione. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Imposta l'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia dell'evento precedente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | L'elenco delimitato da punti e virgola delle parti della risorsa che sono state modificate dalla cronologia degli eventi precedente. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Ottiene o imposta il valore di xmpMM:InstanceId.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID | Il valore di xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Ottiene o imposta la descrizione aggiuntiva dell'azione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La descrizione aggiuntiva dell'azione. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Ottiene o imposta il nome dell'agente software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il nome dell'agente software. |

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

