---
title: "CgEdResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe CgEdResource."
type: docs
weight: 18
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CgEdResource extends AdjustmentLayerResource
```

Classe CgEdResource. Dati extra del generatore di contenuti (Photoshop CS5)
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CgEdResource()](#CgEdResource--) | Inizializza una nuova istanza della classe [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). |
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
| [getAuto()](#getAuto--) | Ottiene o imposta un valore che indica se questo [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) è automatico. |
| [getBrightness()](#getBrightness--) | Ottiene o imposta la luminosità. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Ottiene o imposta il contrasto. |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLabColor()](#getLabColor--) | Ottiene o imposta un valore che indica se [lab color] è usato. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Ottiene o imposta il valore medio per luminosità e contrasto. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPropertyValueByTypeStructure_internalized(String structureName)](#getPropertyValueByTypeStructure-internalized-java.lang.String-) | Ottiene il valore della proprietà per struttura di tipo. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getUseLegacy()](#getUseLegacy--) | Ottiene o imposta un valore che indica se [use legacy] è utilizzato. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setAuto(boolean value)](#setAuto-boolean-) | Ottiene o imposta un valore che indica se questo [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) è automatico. |
| [setBrightness(int value)](#setBrightness-int-) | Ottiene o imposta la luminosità. |
| [setContrast(int value)](#setContrast-int-) | Ottiene o imposta il contrasto. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Ottiene o imposta un valore che indica se [lab color] è usato. |
| [setMeanValueForBrightnessAndContrast(int value)](#setMeanValueForBrightnessAndContrast-int-) | Ottiene o imposta il valore medio per luminosità e contrasto. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Imposta il valore della proprietà per struttura di tipo. |
| [setUseLegacy(boolean value)](#setUseLegacy-boolean-) | Ottiene o imposta un valore che indica se [use legacy] è utilizzato. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta la versione. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgEdResource() {#CgEdResource--}
```
public CgEdResource()
```


Inizializza una nuova istanza della classe [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). La specifica del formato PSD contiene la seguente descrizione: 4 Descriptor Version (= 16) Descriptor a lunghezza variabile dei dati extra. Suggerimento: potrebbe non essere utilizzata nelle versioni precedenti di PS (prima di CS5).

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
### getAuto() {#getAuto--}
```
public final boolean getAuto()
```


Ottiene o imposta un valore che indica se questo [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) è automatico.

Valore:  true  se automatico; altrimenti,  false .

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Ottiene o imposta la luminosità.

Valore: La luminosità.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final int getContrast()
```


Ottiene o imposta il contrasto.

Valore: Il contrasto.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Ottiene o imposta i dati.

Valore: I dati.

**Returns:**
byte[]
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
### getLabColor() {#getLabColor--}
```
public final boolean getLabColor()
```


Ottiene o imposta un valore che indica se [lab color] è usato.

Valore:  true  se usato [lab color]; altrimenti,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Ottiene la lunghezza della risorsa del livello in byte.

**Returns:**
int
### getMeanValueForBrightnessAndContrast() {#getMeanValueForBrightnessAndContrast--}
```
public final int getMeanValueForBrightnessAndContrast()
```


Ottiene o imposta il valore medio per luminosità e contrasto.

Valore: Il valore medio per luminosità e contrasto.

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
### getPropertyValueByTypeStructure_internalized(String structureName) {#getPropertyValueByTypeStructure-internalized-java.lang.String-}
```
public final Object getPropertyValueByTypeStructure_internalized(String structureName)
```


Ottiene il valore della proprietà per tipo di struttura. Usato solo per UnitTests.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| structureName | java.lang.String | Nome della struttura. |

**Returns:**
java.lang.Object - struttura OSType per unit-testing facile
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
### getUseLegacy() {#getUseLegacy--}
```
public final boolean getUseLegacy()
```


Ottiene o imposta un valore che indica se [use legacy] è utilizzato.

Valore:  true  se [use legacy]; altrimenti,  false .

**Returns:**
boolean
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

### setAuto(boolean value) {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```


Ottiene o imposta un valore che indica se questo [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) è automatico.

Valore:  true  se automatico; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Ottiene o imposta la luminosità.

Valore: La luminosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Ottiene o imposta il contrasto.

Valore: Il contrasto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setLabColor(boolean value) {#setLabColor-boolean-}
```
public final void setLabColor(boolean value)
```


Ottiene o imposta un valore che indica se [lab color] è usato.

Valore:  true  se usato [lab color]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMeanValueForBrightnessAndContrast(int value) {#setMeanValueForBrightnessAndContrast-int-}
```
public final void setMeanValueForBrightnessAndContrast(int value)
```


Ottiene o imposta il valore medio per luminosità e contrasto.

Valore: Il valore medio per luminosità e contrasto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Imposta il valore della proprietà per struttura di tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La struttura. |

### setUseLegacy(boolean value) {#setUseLegacy-boolean-}
```
public final void setUseLegacy(boolean value)
```


Ottiene o imposta un valore che indica se [use legacy] è utilizzato.

Valore:  true  se [use legacy]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

