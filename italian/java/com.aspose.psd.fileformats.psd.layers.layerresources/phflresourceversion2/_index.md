---
title: "PhflResourceVersion2"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe PhflResource."
type: docs
weight: 69
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.PhflResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresource)
```
public class PhflResourceVersion2 extends PhflResource
```

Class PhflResource. Risorsa del Livello di Regolazione dell'Esposizione 2 Versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per il colore XYZ (Solo nella Versione 3) 10 2 byte spazio colore seguito da 4 \* 2 byte componente colore (Solo nella Versione 2) 4 Densità 1 Preserva Luminosità
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PhflResourceVersion2()](#PhflResourceVersion2--) | Inizializza una nuova istanza della classe [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2). |
| [PhflResourceVersion2(byte[] data)](#PhflResourceVersion2-byte---) | Inizializza una nuova istanza della classe [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2). |
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
| [getColorSpace()](#getColorSpace--) | Ottiene lo spazio colore. |
| [getComponentA()](#getComponentA--) | Ottiene o imposta il componente A del colore |
| [getComponentB()](#getComponentB--) | Ottiene o imposta il componente B |
| [getComponentL()](#getComponentL--) | Ottiene o imposta il componente L del colore |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [getDensity()](#getDensity--) | Ottiene o imposta la densità. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Ottiene o imposta un valore che indica se [preserve luminosity]. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getRgbColor()](#getRgbColor--) | Ottiene il colore. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getVersion()](#getVersion--) | Ottiene la versione. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setColorSpace(short value)](#setColorSpace-short-) | Ottiene lo spazio colore. |
| [setComponentA(short value)](#setComponentA-short-) | Ottiene o imposta il componente A del colore |
| [setComponentB(short value)](#setComponentB-short-) | Ottiene o imposta il componente B |
| [setComponentL(short value)](#setComponentL-short-) | Ottiene o imposta il componente L del colore |
| [setDensity(int value)](#setDensity-int-) | Ottiene o imposta la densità. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Ottiene o imposta un valore che indica se [preserve luminosity]. |
| [setRgbColor(Color color)](#setRgbColor-com.aspose.psd.Color-) | Imposta il colore RGB. |
| [setVersion(short value)](#setVersion-short-) | Ottiene la versione. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhflResourceVersion2() {#PhflResourceVersion2--}
```
public PhflResourceVersion2()
```


Inizializza una nuova istanza della classe [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2).

### PhflResourceVersion2(byte[] data) {#PhflResourceVersion2-byte---}
```
public PhflResourceVersion2(byte[] data)
```


Inizializza una nuova istanza della classe [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati della risorsa. |

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
### getColorSpace() {#getColorSpace--}
```
public final short getColorSpace()
```


Ottiene lo spazio colore.

Valore: Lo spazio colore.

**Returns:**
short
### getComponentA() {#getComponentA--}
```
public final short getComponentA()
```


Ottiene o imposta il componente A del colore

**Returns:**
short
### getComponentB() {#getComponentB--}
```
public final short getComponentB()
```


Ottiene o imposta il componente B

**Returns:**
short
### getComponentL() {#getComponentL--}
```
public final short getComponentL()
```


Ottiene o imposta il componente L del colore

**Returns:**
short
### getData() {#getData--}
```
public final byte[] getData()
```


Ottiene o imposta i dati.

Valore: I dati.

**Returns:**
byte[]
### getDensity() {#getDensity--}
```
public final int getDensity()
```


Ottiene o imposta la densità.

Valore: La densità.

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


Ottiene o imposta un valore che indica se [preserve luminosity].

Valore:  true  se [preserve luminosity]; altrimenti,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ottiene la versione minima di psd richiesta per la risorsa di livello. 0 indica nessuna restrizione.

**Returns:**
int
### getRgbColor() {#getRgbColor--}
```
public Color getRgbColor()
```


Ottiene il colore.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB color
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

**Returns:**
int
### getVersion() {#getVersion--}
```
public short getVersion()
```


Ottiene la versione.

**Returns:**
short
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

### setColorSpace(short value) {#setColorSpace-short-}
```
public void setColorSpace(short value)
```


Ottiene lo spazio colore.

Valore: Lo spazio colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setComponentA(short value) {#setComponentA-short-}
```
public final void setComponentA(short value)
```


Ottiene o imposta il componente A del colore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setComponentB(short value) {#setComponentB-short-}
```
public final void setComponentB(short value)
```


Ottiene o imposta il componente B

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setComponentL(short value) {#setComponentL-short-}
```
public final void setComponentL(short value)
```


Ottiene o imposta il componente L del colore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setDensity(int value) {#setDensity-int-}
```
public final void setDensity(int value)
```


Ottiene o imposta la densità.

Valore: La densità.

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

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Ottiene o imposta un valore che indica se [preserve luminosity].

Valore:  true  se [preserve luminosity]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRgbColor(Color color) {#setRgbColor-com.aspose.psd.Color-}
```
public void setRgbColor(Color color)
```


Imposta il colore RGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Il colore. |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Ottiene la versione.

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

