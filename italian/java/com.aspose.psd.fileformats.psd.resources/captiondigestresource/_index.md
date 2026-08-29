---
title: "CaptionDigestResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Risorsa CaptionDigest"
type: docs
weight: 13
url: /it/java/com.aspose.psd.fileformats.psd.resources/captiondigestresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class CaptionDigestResource extends ResourceBlock
```

Risorsa CaptionDigest
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CaptionDigestResource()](#CaptionDigestResource--) | Inizializza una nuova istanza della classe [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | La firma della risorsa di ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | La firma della risorsa Photoshop standard. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione dei dati della risorsa in byte. |
| [getDigest()](#getDigest--) | Ottiene o imposta il digest. |
| [getID()](#getID--) | Ottiene o imposta l'identificatore univoco per la risorsa. |
| [getMinimalVersion()](#getMinimalVersion--) | Ottiene la versione PSD minima richiesta. |
| [getName()](#getName--) | Ottiene o imposta il nome della risorsa. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa. |
| [getSize()](#getSize--) | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Salva il blocco risorsa nello stream specificato. |
| [setDigest(byte[] value)](#setDigest-byte---) | Ottiene o imposta il digest. |
| [setID(short value)](#setID-short-) | Ottiene o imposta l'identificatore univoco per la risorsa. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Ottiene o imposta le informazioni del livello e della maschera. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome della risorsa. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Ottiene o imposta lo stato del blocco risorsa. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Convalida i valori della risorsa. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CaptionDigestResource() {#CaptionDigestResource--}
```
public CaptionDigestResource()
```


Inizializza una nuova istanza della classe [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


La firma della risorsa di ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


La firma della risorsa Photoshop standard.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Ottiene la dimensione dei dati della risorsa in byte.

Valore: La dimensione dei dati della risorsa.

**Returns:**
int
### getDigest() {#getDigest--}
```
public final byte[] getDigest()
```


Ottiene o imposta il digest.

Valore: il digest.

**Returns:**
byte[]
### getID() {#getID--}
```
public final short getID()
```


Ottiene o imposta l'identificatore univoco per la risorsa.

Valore: L'identificatore univoco della risorsa.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Ottiene la versione PSD minima richiesta.

Valore: La versione minima di PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0).

Valore: Il nome della risorsa.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'.

Valore: La firma della risorsa.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene la dimensione del blocco risorsa in byte, inclusi i dati.

Valore: La dimensione del blocco della risorsa.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Salva il blocco risorsa nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso su cui salvare il blocco della risorsa. |

### setDigest(byte[] value) {#setDigest-byte---}
```
public final void setDigest(byte[] value)
```


Ottiene o imposta il digest.

Valore: il digest.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Ottiene o imposta l'identificatore univoco per la risorsa.

Valore: L'identificatore univoco della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Ottiene o imposta le informazioni del livello e della maschera.

Valore: Le informazioni di livello e maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0).

Valore: Il nome della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firma | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Ottiene o imposta lo stato del blocco risorsa.

Valore: Lo stato del blocco della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Convalida i valori della risorsa.

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

