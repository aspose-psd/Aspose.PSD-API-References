---
title: "LyvrResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La risorsa che rappresenta la versione Photoshop del livello."
type: docs
weight: 60
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public final class LyvrResource extends LayerResource
```

La risorsa che rappresenta la versione Photoshop del livello.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LyvrResource()](#LyvrResource--) | Inizializza una nuova istanza della classe [LyvrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lyvrresource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versione dell'intestazione PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma della risorsa specifica per PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versione dell'intestazione PSD |
| [ResourceSignature](#ResourceSignature) | La firma della risorsa comune. |
| [TypeToolKey](#TypeToolKey) | La chiave delle informazioni dello strumento di tipo. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licenza venture. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Verifica e imposta se la risorsa è specifica per PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) |    |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione Photoshop del livello. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta la versione Photoshop del livello. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LyvrResource() {#LyvrResource--}
```
public LyvrResource()
```


Inizializza una nuova istanza della classe [LyvrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lyvrresource).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


La versione dell'intestazione PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


La firma della risorsa specifica per PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


La versione dell'intestazione PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


La firma della risorsa comune.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


La chiave delle informazioni dello strumento di tipo.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


La licenza venture.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Verifica e imposta se la risorsa è specifica PSB. Alcune risorse non sono ancora riconosciute, ma disponiamo di un elenco completo di risorse specifiche PSB che ne modificano il comportamento durante il salvataggio. Pertanto è necessario controllare questo in UnknownResource almeno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | int | La chiave. |

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
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Ottiene la chiave della risorsa del livello.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


  

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Ottiene la lunghezza del prefisso. Il valore predefinito è 12 per le risorse 8BIM e 16 per 8B64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| psdVersion | int | La versione PSD. |

**Returns:**
int - La lunghezza del prefisso.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ottiene la versione minima di psd richiesta per la risorsa di livello. 0 indica nessuna restrizione.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene o imposta la versione Photoshop del livello.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determina se la risorsa è specifica per PSB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | int | La chiave della risorsa. |

**Returns:**
boolean -  true  se la risorsa è specifica PSB; altrimenti,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB.

Valore:  true  se questa istanza è una risorsa specifica PSB; altrimenti,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Salva la risorsa nel contenitore di stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psdVersion | int | La versione PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Salva l'intestazione della risorsa personalizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
| firma | int | La firma. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Salva la firma, l'identificatore e la lunghezza dell'intestazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
| firma | int | La firma. |
| isLengthLong | boolean | se impostato su  true  la lunghezza è lunga. |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Ottiene o imposta la versione Photoshop del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una String che rappresenta questa istanza.

**Returns:**
java.lang.String - Una String che rappresenta questa istanza.
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

