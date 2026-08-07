---
title: "DataStreamSupporter"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il contenitore del flusso di dati."
type: docs
weight: 38
url: /it/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Il contenitore del flusso di dati.
## Campi

| Campo | Descrizione |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Si verifica quando l'immagine è stata caricata o salvata |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Si verifica quando il credito è stato utilizzato |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati e garantisce che non vengano caricati dati aggiuntivi dal sottostante DataStreamSupporter.DataStreamContainer. |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Restituisce lo stream di dati dell'oggetto. |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Ottiene il percorso file dell'immagine sorgente se esiste. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Ottiene un valore che indica se l'oggetto utilizza una strategia di ottimizzazione della memoria |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Salva i dati dell'oggetto nel corrente DataStreamSupporter. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Salva i dati dell'oggetto nello stream specificato. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Salva i dati dell'oggetto nello stream specificato. |
| [save(String filePath)](#save-java.lang.String-) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Imposta lo stream dei dati dell'oggetto. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Imposta un valore che indica se [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Si verifica quando l'immagine è stata caricata o salvata

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Si verifica quando il credito è stato utilizzato

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Memorizza nella cache i dati e garantisce che non vengano caricati dati aggiuntivi dal sottostante DataStreamSupporter.DataStreamContainer.

### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Restituisce lo stream di dati dell'oggetto.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Restituisce il percorso del file dell'immagine sorgente se esiste. Restituisce una stringa vuota se non è possibile trovare il percorso sorgente.

**Returns:**
java.lang.String - Il percorso del file dell'immagine sorgente.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Ottiene un valore che indica se l'oggetto utilizza una strategia di ottimizzazione della memoria

Valore:  true  se l'oggetto utilizza la strategia di ottimizzazione della memoria; altrimenti,  false .

**Returns:**
boolean - un valore che indica se l'oggetto utilizza la strategia di ottimizzazione della memoria
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.

**Returns:**
boolean - un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Salva i dati dell'oggetto nel corrente DataStreamSupporter.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Salva i dati dell'oggetto nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Il flusso in cui salvare i dati dell'oggetto. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Salva i dati dell'oggetto nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il flusso in cui salvare i dati dell'oggetto. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dell'oggetto. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dell'oggetto. |
| overWrite | boolean | se impostato su true sovrascrive il contenuto del file, altrimenti verrà aggiunto. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Imposta lo stream dei dati dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso di dati dell'oggetto. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Imposta un valore che indica se [ignore after save].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true se [ignore after save]; altrimenti, false. |

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

