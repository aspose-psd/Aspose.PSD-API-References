---
title: "TiffDataType"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il tipo di dati TIFF."
type: docs
weight: 10
url: /it/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Il tipo di dati TIFF.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto. |
| [deepClone()](#deepClone--) | Esegue una clonazione profonda di questa istanza. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Ottiene la dimensione dei dati aggiuntivi in byte (nel caso i 12 byte non siano sufficienti per contenere i dati del tag). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Ottiene il conteggio degli elementi. |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione dei dati aggiuntivi in byte (nel caso i 12 byte non siano sufficienti per contenere i dati del tag). |
| [getId()](#getId--) | Ottiene la rappresentazione intera dell'ID del tag. |
| [getTagId()](#getTagId--) | Ottiene l'ID del tag. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene il valore contenuto da questo tipo di dati. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Ottiene un valore che indica se il tag è privato. |
| [isValid()](#isValid--) | Ottiene un valore che indica se i dati del tag sono validi. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Legge i dati del tag. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Imposta il valore contenuto da questo tipo di dati. |
| [toString()](#toString--) | Restituisce un  System.String  che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Scrive i dati del tag. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Un oggetto da confrontare con questa istanza. |

**Returns:**
int - Un intero a 32 bit con segno che indica l'ordine relativo degli oggetti confrontati. Il valore restituito ha questi significati: Valore Significato Meno di zero Questa istanza è minore di obj. Zero Questa istanza è uguale a obj. Maggiore di zero Questa istanza è maggiore di obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Esegue una clonazione profonda di questa istanza.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Ottiene la dimensione dei dati aggiuntivi in byte (nel caso i 12 byte non siano sufficienti per contenere i dati del tag).

**Returns:**
long - La dimensione dei dati aggiuntivi in byte.

Questo è il conteggio dei byte dei dati allineato al confine della parola.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Ottiene il conteggio degli elementi.

**Returns:**
long - Il conteggio degli elementi.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Ottiene la dimensione dei dati aggiuntivi in byte (nel caso i 12 byte non siano sufficienti per contenere i dati del tag).

**Returns:**
long - La dimensione dei dati aggiuntivi in byte.

Questo è il conteggio esatto dei byte.
### getId() {#getId--}
```
public int getId()
```


Ottiene la rappresentazione intera dell'ID del tag.

**Returns:**
int - La rappresentazione intera dell'ID del tag
### getTagId() {#getTagId--}
```
public int getTagId()
```


Ottiene l'ID del tag.

**Returns:**
int - L'ID del tag.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Ottiene il tipo del tag.

**Returns:**
int - Il tipo di tag.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Ottiene il valore contenuto da questo tipo di dati.

**Returns:**
java.lang.Object - Il valore.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Restituisce un valore che indica se il tag è privato. I tag TIFF privati sono tag con ID superiore a 32768.

**Returns:**
boolean -  true  se i dati del tag sono validi; altrimenti,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Restituisce un valore che indica se i dati del tag sono validi. Il tag valido contiene dati che possono essere conservati. Il tag non valido non può essere memorizzato.

**Returns:**
boolean -  true  se i dati del tag sono validi; altrimenti,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Legge i dati del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Il flusso di dati. |
| position | long | La posizione del tag. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Imposta il valore contenuto da questo tipo di dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Il valore. |

### toString() {#toString--}
```
public String toString()
```


Restituisce un  System.String  che rappresenta questa istanza.

**Returns:**
java.lang.String - Un  System.String  che rappresenta questa istanza.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Scrive i dati aggiuntivi del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Il flusso di dati. |

**Returns:**
long - I byte effettivi scritti.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Scrive i dati del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Il flusso di dati. |
| additionalDataOffset | long | L'offset a cui scrivere i dati aggiuntivi. |

