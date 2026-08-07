---
title: "VectorPathDataResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe VectorPathDataResource."
type: docs
weight: 19
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdataresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public abstract class VectorPathDataResource extends LayerResource implements IVectorPathData
```

Classe VectorPathDataResource. Questa risorsa contiene informazioni sulla maschera del livello vettoriale
## Campi

| Campo | Descrizione |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versione dell'intestazione PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma della risorsa specifica per PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versione dell'intestazione PSD |
| [ResourceSignature](#ResourceSignature) | La firma della risorsa comune. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licenza venture. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Verifica e imposta se la risorsa è specifica per PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getPaths()](#getPaths--) | Ottiene o imposta i record del percorso. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Determina se questa istanza è modificata. |
| [isDisabled()](#isDisabled--) | Ottiene o imposta un valore che indica se questa istanza è disabilitata. |
| [isInverted()](#isInverted--) | Ottiene o imposta un valore che indica se questa istanza è invertita. |
| [isNotLinked()](#isNotLinked--) | Ottiene o imposta un valore che indica se questa istanza non è collegata. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Ottiene o imposta un valore che indica se questa istanza è disabilitata. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setInverted(boolean value)](#setInverted-boolean-) | Ottiene o imposta un valore che indica se questa istanza è invertita. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Ottiene o imposta un valore che indica se questa istanza non è collegata. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Ottiene o imposta i record del percorso. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta la versione. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [updateDataToCurrent_internalized()](#updateDataToCurrent-internalized--) | Aggiorna i dati originali memorizzati nella cache allo stato corrente |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Ottiene la lunghezza della risorsa del livello in byte.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Ottiene o imposta i record del percorso.

Valore: i percorsi.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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


Ottiene o imposta la versione.

Valore: La versione.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


Determina se questa istanza è modificata.

**Returns:**
boolean -  true  se questa istanza è modificata; altrimenti,  false .
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Ottiene o imposta un valore che indica se questa istanza è disabilitata.

Valore:  true  se questa istanza è disabilitata; altrimenti,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Ottiene o imposta un valore che indica se questa istanza è invertita.

Valore:  true  se questa istanza è invertita; altrimenti,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Ottiene o imposta un valore che indica se questa istanza non è collegata.

Valore:  true  se questa istanza non è collegata; altrimenti,  false .

**Returns:**
boolean
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

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è disabilitata.

Valore:  true  se questa istanza è disabilitata; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è invertita.

Valore:  true  se questa istanza è invertita; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza non è collegata.

Valore:  true  se questa istanza non è collegata; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Ottiene o imposta i record del percorso.

Valore: i percorsi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Ottiene o imposta la versione.

Valore: La versione.

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
### updateDataToCurrent_internalized() {#updateDataToCurrent-internalized--}
```
public final void updateDataToCurrent_internalized()
```


Aggiorna i dati originali memorizzati nella cache allo stato corrente

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

