---
title: "BlwhResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe BlwhResource è una risorsa del livello di regolazione in bianco e nero."
type: docs
weight: 15
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

La classe BlwhResource è una risorsa del livello di regolazione in bianco e nero.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Inizializza una nuova istanza della classe [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource). |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Ottiene o imposta il nome file del preset in bianco e nero. |
| [getBlues()](#getBlues--) | Ottiene o imposta il valore dei blu. |
| [getBwPresetKind()](#getBwPresetKind--) | Ottiene o imposta il valore del tipo di preset in bianco e nero. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Ottiene o imposta il valore dei ciano. |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [getGreens()](#getGreens--) | Ottiene o imposta il valore dei verdi. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getMagentas()](#getMagentas--) | Ottiene o imposta il valore dei magenta. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getReds()](#getReds--) | Ottiene o imposta il valore dei rossi. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getTintColor()](#getTintColor--) | Ottiene il colore tinta ARGB. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Ottiene o imposta il valore double del colore tinta blu. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Ottiene o imposta il valore double del colore tinta verde. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Ottiene o imposta il valore double del colore tinta rosso. |
| [getUseTint()](#getUseTint--) | Ottiene o imposta un valore che indica se [tint color] è usato. |
| [getYellows()](#getYellows--) | Ottiene o imposta il valore dei gialli. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Ottiene o imposta il nome file del preset in bianco e nero. |
| [setBlues(int value)](#setBlues-int-) | Ottiene o imposta il valore dei blu. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Ottiene o imposta il valore del tipo di preset in bianco e nero. |
| [setCyans(int value)](#setCyans-int-) | Ottiene o imposta il valore dei ciano. |
| [setGreens(int value)](#setGreens-int-) | Ottiene o imposta il valore dei verdi. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setMagentas(int value)](#setMagentas-int-) | Ottiene o imposta il valore dei magenta. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Imposta il valore della proprietà per struttura di tipo. |
| [setReds(int value)](#setReds-int-) | Ottiene o imposta il valore dei rossi. |
| [setTintColor(int value)](#setTintColor-int-) | Imposta il colore tinta. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Ottiene o imposta il valore double del colore tinta blu. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Ottiene o imposta il valore double del colore tinta verde. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Ottiene o imposta il valore double del colore tinta rosso. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Ottiene o imposta un valore che indica se [tint color] è usato. |
| [setYellows(int value)](#setYellows-int-) | Ottiene o imposta il valore dei gialli. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Inizializza una nuova istanza della classe [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource).

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Ottiene o imposta il nome file del preset in bianco e nero.

Valore: Il nome file del preset in bianco e nero.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Ottiene o imposta il valore dei blu.

Valore: Il valore dei blu.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Ottiene o imposta il valore del tipo di preset in bianco e nero.

Valore: Il valore del tipo di preset in bianco e nero.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Ottiene o imposta il valore dei ciano.

Valore: Il valore dei ciano.

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
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Ottiene o imposta il valore dei verdi.

Valore: Il valore dei verdi.

**Returns:**
int
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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Ottiene o imposta il valore dei magenta.

Valore: Il valore dei magenta.

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
### getReds() {#getReds--}
```
public final int getReds()
```


Ottiene o imposta il valore dei rossi.

Valore: Il valore dei rossi.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Ottiene il colore tinta ARGB.

**Returns:**
int - Il colore tinta ARGB.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Ottiene o imposta il valore double del colore tinta blu.

Valore: Il valore double del colore tinta blu.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Ottiene o imposta il valore double del colore tinta verde.

Valore: Il valore double del colore di tinta verde.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Ottiene o imposta il valore double del colore tinta rosso.

Valore: Il valore double del colore di tinta rosso.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Ottiene o imposta un valore che indica se [tint color] è usato.

Valore:  true  se usato [tint color]; altrimenti,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Ottiene o imposta il valore dei gialli.

Valore: Il valore dei gialli.

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Ottiene o imposta il nome file del preset in bianco e nero.

Valore: Il nome file del preset in bianco e nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Ottiene o imposta il valore dei blu.

Valore: Il valore dei blu.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Ottiene o imposta il valore del tipo di preset in bianco e nero.

Valore: Il valore del tipo di preset in bianco e nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Ottiene o imposta il valore dei ciano.

Valore: Il valore dei ciano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Ottiene o imposta il valore dei verdi.

Valore: Il valore dei verdi.

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Ottiene o imposta il valore dei magenta.

Valore: Il valore dei magenta.

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

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Ottiene o imposta il valore dei rossi.

Valore: Il valore dei rossi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Imposta il colore tinta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il valore. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Ottiene o imposta il valore double del colore tinta blu.

Valore: Il valore double del colore tinta blu.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Ottiene o imposta il valore double del colore tinta verde.

Valore: Il valore double del colore di tinta verde.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Ottiene o imposta il valore double del colore tinta rosso.

Valore: Il valore double del colore di tinta rosso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Ottiene o imposta un valore che indica se [tint color] è usato.

Valore:  true  se usato [tint color]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Ottiene o imposta il valore dei gialli.

Valore: Il valore dei gialli.

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

