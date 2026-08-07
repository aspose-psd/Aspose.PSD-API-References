---
title: "BlncResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe BlncResource è una risorsa del livello di regolazione colore."
type: docs
weight: 14
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlncResource extends AdjustmentLayerResource
```

La classe BlncResource è una risorsa del livello di regolazione colore.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BlncResource()](#BlncResource--) | Inizializza una nuova istanza della classe [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DataLength_internalized](#DataLength-internalized) | La lunghezza dei dati prevista. |
| [HighlightsCyanRedBalanceExceptionMessage_internalized](#HighlightsCyanRedBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento ciano-rosso delle alte luci fuori intervallo. |
| [HighlightsMagentaGreenBalanceExceptionMessage_internalized](#HighlightsMagentaGreenBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento magenta-verde delle alte luci fuori intervallo. |
| [HighlightsYellowBlueBalanceExceptionMessage_internalized](#HighlightsYellowBlueBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento giallo-blu delle alte luci fuori intervallo. |
| [MidtonesCyanRedBalanceExceptionMessage_internalized](#MidtonesCyanRedBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento ciano-rosso dei mezzitoni fuori intervallo. |
| [MidtonesMagentaGreenBalanceExceptionMessage_internalized](#MidtonesMagentaGreenBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento magenta-verde dei mezzitoni fuori intervallo. |
| [MidtonesYellowBlueBalanceExceptionMessage_internalized](#MidtonesYellowBlueBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento giallo-blu dei mezzitoni fuori intervallo. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versione dell'intestazione PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma della risorsa specifica per PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versione dell'intestazione PSD |
| [ResourceSignature](#ResourceSignature) | La firma della risorsa comune. |
| [ShadowsCyanRedBalanceExceptionMessage_internalized](#ShadowsCyanRedBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento ciano-rosso delle ombre fuori intervallo. |
| [ShadowsMagentaGreenBalanceExceptionMessage_internalized](#ShadowsMagentaGreenBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento magenta-verde delle ombre fuori intervallo. |
| [ShadowsYellowBlueBalanceExceptionMessage_internalized](#ShadowsYellowBlueBalanceExceptionMessage-internalized) | Messaggio di eccezione per il bilanciamento giallo-blu delle ombre fuori intervallo. |
| [TypeToolKey](#TypeToolKey) | La chiave delle informazioni dello strumento di tipo. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licenza venture. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Verifica e imposta se la risorsa è specifica per PSB. |
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getHighlightsCyanRedBalance()](#getHighlightsCyanRedBalance--) | Ottiene o imposta il bilanciamento Cyan Red delle Highlights. |
| [getHighlightsMagentaGreenBalance()](#getHighlightsMagentaGreenBalance--) | Ottiene o imposta il bilanciamento Magenta Green delle Highlights. |
| [getHighlightsYellowBlueBalance()](#getHighlightsYellowBlueBalance--) | Ottiene o imposta il bilanciamento Yellow Blue delle Highlights. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getMidtonesCyanRedBalance()](#getMidtonesCyanRedBalance--) | Ottiene o imposta il bilanciamento Cyan Red dei mezzitoni. |
| [getMidtonesMagentaGreenBalance()](#getMidtonesMagentaGreenBalance--) | Ottiene o imposta il bilanciamento Magenta Green dei mezzitoni. |
| [getMidtonesYellowBlueBalance()](#getMidtonesYellowBlueBalance--) | Ottiene o imposta il bilanciamento Yellow Blue dei mezzitoni. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Ottiene o imposta un valore che indica se questo [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosità. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getShadowsCyanRedBalance()](#getShadowsCyanRedBalance--) | Ottiene o imposta il bilanciamento Cyan Red delle ombre. |
| [getShadowsMagentaGreenBalance()](#getShadowsMagentaGreenBalance--) | Ottiene o imposta il bilanciamento Magenta Green delle ombre. |
| [getShadowsYellowBlueBalance()](#getShadowsYellowBlueBalance--) | Ottiene o imposta il bilanciamento giallo-blu delle ombre. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setHighlightsCyanRedBalance(short value)](#setHighlightsCyanRedBalance-short-) | Ottiene o imposta il bilanciamento Cyan Red delle Highlights. |
| [setHighlightsMagentaGreenBalance(short value)](#setHighlightsMagentaGreenBalance-short-) | Ottiene o imposta il bilanciamento Magenta Green delle Highlights. |
| [setHighlightsYellowBlueBalance(short value)](#setHighlightsYellowBlueBalance-short-) | Ottiene o imposta il bilanciamento Yellow Blue delle Highlights. |
| [setMidtonesCyanRedBalance(short value)](#setMidtonesCyanRedBalance-short-) | Ottiene o imposta il bilanciamento Cyan Red dei mezzitoni. |
| [setMidtonesMagentaGreenBalance(short value)](#setMidtonesMagentaGreenBalance-short-) | Ottiene o imposta il bilanciamento Magenta Green dei mezzitoni. |
| [setMidtonesYellowBlueBalance(short value)](#setMidtonesYellowBlueBalance-short-) | Ottiene o imposta il bilanciamento Yellow Blue dei mezzitoni. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Ottiene o imposta un valore che indica se questo [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosità. |
| [setShadowsCyanRedBalance(short value)](#setShadowsCyanRedBalance-short-) | Ottiene o imposta il bilanciamento Cyan Red delle ombre. |
| [setShadowsMagentaGreenBalance(short value)](#setShadowsMagentaGreenBalance-short-) | Ottiene o imposta il bilanciamento Magenta Green delle ombre. |
| [setShadowsYellowBlueBalance(short value)](#setShadowsYellowBlueBalance-short-) | Ottiene o imposta il bilanciamento giallo-blu delle ombre. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlncResource() {#BlncResource--}
```
public BlncResource()
```


Inizializza una nuova istanza della classe [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource).

### DataLength_internalized {#DataLength-internalized}
```
public static final int DataLength_internalized
```


La lunghezza dei dati prevista.

### HighlightsCyanRedBalanceExceptionMessage_internalized {#HighlightsCyanRedBalanceExceptionMessage-internalized}
```
public static final String HighlightsCyanRedBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento ciano-rosso delle alte luci fuori intervallo.

### HighlightsMagentaGreenBalanceExceptionMessage_internalized {#HighlightsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String HighlightsMagentaGreenBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento magenta-verde delle alte luci fuori intervallo.

### HighlightsYellowBlueBalanceExceptionMessage_internalized {#HighlightsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String HighlightsYellowBlueBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento giallo-blu delle alte luci fuori intervallo.

### MidtonesCyanRedBalanceExceptionMessage_internalized {#MidtonesCyanRedBalanceExceptionMessage-internalized}
```
public static final String MidtonesCyanRedBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento ciano-rosso dei mezzitoni fuori intervallo.

### MidtonesMagentaGreenBalanceExceptionMessage_internalized {#MidtonesMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String MidtonesMagentaGreenBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento magenta-verde dei mezzitoni fuori intervallo.

### MidtonesYellowBlueBalanceExceptionMessage_internalized {#MidtonesYellowBlueBalanceExceptionMessage-internalized}
```
public static final String MidtonesYellowBlueBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento giallo-blu dei mezzitoni fuori intervallo.

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

### ShadowsCyanRedBalanceExceptionMessage_internalized {#ShadowsCyanRedBalanceExceptionMessage-internalized}
```
public static final String ShadowsCyanRedBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento ciano-rosso delle ombre fuori intervallo.

### ShadowsMagentaGreenBalanceExceptionMessage_internalized {#ShadowsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String ShadowsMagentaGreenBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento magenta-verde delle ombre fuori intervallo.

### ShadowsYellowBlueBalanceExceptionMessage_internalized {#ShadowsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String ShadowsYellowBlueBalanceExceptionMessage_internalized
```


Messaggio di eccezione per il bilanciamento giallo-blu delle ombre fuori intervallo.

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static BlncResource create_internalized(byte[] data)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] |  |

**Returns:**
[BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource)
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
### getHighlightsCyanRedBalance() {#getHighlightsCyanRedBalance--}
```
public final short getHighlightsCyanRedBalance()
```


Ottiene o imposta il bilanciamento Cyan Red delle Highlights.

Valore: Il bilanciamento ciano-rosso delle alte luci.

**Returns:**
short
### getHighlightsMagentaGreenBalance() {#getHighlightsMagentaGreenBalance--}
```
public final short getHighlightsMagentaGreenBalance()
```


Ottiene o imposta il bilanciamento Magenta Green delle Highlights.

Valore: Il bilanciamento magenta-verde delle alte luci.

**Returns:**
short
### getHighlightsYellowBlueBalance() {#getHighlightsYellowBlueBalance--}
```
public final short getHighlightsYellowBlueBalance()
```


Ottiene o imposta il bilanciamento Yellow Blue delle Highlights.

Valore: Il bilanciamento giallo-blu delle alte luci.

**Returns:**
short
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
### getMidtonesCyanRedBalance() {#getMidtonesCyanRedBalance--}
```
public final short getMidtonesCyanRedBalance()
```


Ottiene o imposta il bilanciamento Cyan Red dei mezzitoni.

Valore: Il bilanciamento ciano-rosso dei mezzitoni.

**Returns:**
short
### getMidtonesMagentaGreenBalance() {#getMidtonesMagentaGreenBalance--}
```
public final short getMidtonesMagentaGreenBalance()
```


Ottiene o imposta il bilanciamento Magenta Green dei mezzitoni.

Valore: Il bilanciamento magenta-verde dei mezzitoni.

**Returns:**
short
### getMidtonesYellowBlueBalance() {#getMidtonesYellowBlueBalance--}
```
public final short getMidtonesYellowBlueBalance()
```


Ottiene o imposta il bilanciamento Yellow Blue dei mezzitoni.

Valore: Il bilanciamento giallo-blu dei mezzitoni.

**Returns:**
short
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
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Ottiene o imposta un valore che indica se questo [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosità.

Valore:  true  se preserva la luminosità; altrimenti,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ottiene la versione minima di psd richiesta per la risorsa di livello. 0 indica nessuna restrizione.

**Returns:**
int
### getShadowsCyanRedBalance() {#getShadowsCyanRedBalance--}
```
public final short getShadowsCyanRedBalance()
```


Ottiene o imposta il bilanciamento Cyan Red delle ombre.

Valore: Il bilanciamento ciano-rosso delle ombre.

**Returns:**
short
### getShadowsMagentaGreenBalance() {#getShadowsMagentaGreenBalance--}
```
public final short getShadowsMagentaGreenBalance()
```


Ottiene o imposta il bilanciamento Magenta Green delle ombre.

Valore: Il bilanciamento magenta-verde delle ombre.

**Returns:**
short
### getShadowsYellowBlueBalance() {#getShadowsYellowBlueBalance--}
```
public final short getShadowsYellowBlueBalance()
```


Ottiene o imposta il bilanciamento giallo-blu delle ombre.

Valore: Il bilanciamento giallo-blu delle ombre.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

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

### setHighlightsCyanRedBalance(short value) {#setHighlightsCyanRedBalance-short-}
```
public final void setHighlightsCyanRedBalance(short value)
```


Ottiene o imposta il bilanciamento Cyan Red delle Highlights.

Valore: Il bilanciamento ciano-rosso delle alte luci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setHighlightsMagentaGreenBalance(short value) {#setHighlightsMagentaGreenBalance-short-}
```
public final void setHighlightsMagentaGreenBalance(short value)
```


Ottiene o imposta il bilanciamento Magenta Green delle Highlights.

Valore: Il bilanciamento magenta-verde delle alte luci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setHighlightsYellowBlueBalance(short value) {#setHighlightsYellowBlueBalance-short-}
```
public final void setHighlightsYellowBlueBalance(short value)
```


Ottiene o imposta il bilanciamento Yellow Blue delle Highlights.

Valore: Il bilanciamento giallo-blu delle alte luci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setMidtonesCyanRedBalance(short value) {#setMidtonesCyanRedBalance-short-}
```
public final void setMidtonesCyanRedBalance(short value)
```


Ottiene o imposta il bilanciamento Cyan Red dei mezzitoni.

Valore: Il bilanciamento ciano-rosso dei mezzitoni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setMidtonesMagentaGreenBalance(short value) {#setMidtonesMagentaGreenBalance-short-}
```
public final void setMidtonesMagentaGreenBalance(short value)
```


Ottiene o imposta il bilanciamento Magenta Green dei mezzitoni.

Valore: Il bilanciamento magenta-verde dei mezzitoni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setMidtonesYellowBlueBalance(short value) {#setMidtonesYellowBlueBalance-short-}
```
public final void setMidtonesYellowBlueBalance(short value)
```


Ottiene o imposta il bilanciamento Yellow Blue dei mezzitoni.

Valore: Il bilanciamento giallo-blu dei mezzitoni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Ottiene o imposta un valore che indica se questo [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserva la luminosità.

Valore:  true  se preserva la luminosità; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setShadowsCyanRedBalance(short value) {#setShadowsCyanRedBalance-short-}
```
public final void setShadowsCyanRedBalance(short value)
```


Ottiene o imposta il bilanciamento Cyan Red delle ombre.

Valore: Il bilanciamento ciano-rosso delle ombre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setShadowsMagentaGreenBalance(short value) {#setShadowsMagentaGreenBalance-short-}
```
public final void setShadowsMagentaGreenBalance(short value)
```


Ottiene o imposta il bilanciamento Magenta Green delle ombre.

Valore: Il bilanciamento magenta-verde delle ombre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setShadowsYellowBlueBalance(short value) {#setShadowsYellowBlueBalance-short-}
```
public final void setShadowsYellowBlueBalance(short value)
```


Ottiene o imposta il bilanciamento giallo-blu delle ombre.

Valore: Il bilanciamento giallo-blu delle ombre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

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

