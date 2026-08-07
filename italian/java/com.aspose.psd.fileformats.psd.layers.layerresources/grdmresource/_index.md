---
title: "GrdmResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe GrdmResource."
type: docs
weight: 35
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

Classe GrdmResource. Contiene informazioni sul livello Gradient-Map.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Inizializza una nuova istanza della classe [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | La scala predefinita. |
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
| [getColorModel()](#getColorModel--) | Modello di colore. |
| [getColorPoints()](#getColorPoints--) | Ottiene o imposta i punti di colore. |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [getDither()](#getDither--) | Il gradiente è dithertizzato. |
| [getExpansionCount()](#getExpansionCount--) | Conteggio di espansione ( = 2 per Photoshop 6.0). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Lunghezza(= 32 per Photoshop 6.0) Nessuna informazione su a cosa serve. |
| [getGradientMode()](#getGradientMode--) | Modalità per questo gradiente Determina 'Gradient Type' = 'Solid/Noise' (0/1). |
| [getGradientName()](#getGradientName--) | Nome del gradiente: stringa Unicode, riempita. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getInterpolation()](#getInterpolation--) | Interpolazione. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getMaximumColor()](#getMaximumColor--) | Colore massimo del formato PixelDataFormat.Rgba64Bpp. |
| [getMinimumColor()](#getMinimumColor--) | Colore minimo del formato PixelDataFormat.Rgba64Bpp. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per questa risorsa. |
| [getReverse()](#getReverse--) | Il gradiente è invertito. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Il seme del numero casuale usato per generare i colori per il gradiente di rumore. |
| [getRoughness()](#getRoughness--) | Fattore di rugosità Quando 'Gradient type' = 'Noise', possiamo assegnare 'Roughness' (0 - 2048). |
| [getShowTransparency()](#getShowTransparency--) | Flag per mostrare la trasparenza Quando 'Gradient type' = 'Noise', possiamo impostare 'Add transparency' su true. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Ottiene o imposta i punti di trasparenza. |
| [getUseVectorColor()](#getUseVectorColor--) | Flag per l'uso del colore vettoriale. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Inizializza la lunghezza del gradiente. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva i dati della risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setColorModel(short value)](#setColorModel-short-) | Modello di colore. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Ottiene o imposta i punti di colore. |
| [setDither(boolean value)](#setDither-boolean-) | Il gradiente è dithertizzato. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Conteggio di espansione ( = 2 per Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Modalità per questo gradiente Determina 'Gradient Type' = 'Solid/Noise' (0/1). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Nome del gradiente: stringa Unicode, riempita. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolazione. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Colore massimo del formato PixelDataFormat.Rgba64Bpp. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Colore minimo del formato PixelDataFormat.Rgba64Bpp. |
| [setReverse(boolean value)](#setReverse-boolean-) | Il gradiente è invertito. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Il seme del numero casuale usato per generare i colori per il gradiente di rumore. |
| [setRoughness(int value)](#setRoughness-int-) | Fattore di rugosità Quando 'Gradient type' = 'Noise', possiamo assegnare 'Roughness' (0 - 2048). |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Flag per mostrare la trasparenza Quando 'Gradient type' = 'Noise', possiamo impostare 'Add transparency' su true. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Ottiene o imposta i punti di trasparenza. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Flag per l'uso del colore vettoriale. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


Inizializza una nuova istanza della classe [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| psdVersion | int | La versione PSD della risorsa. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


La scala predefinita.

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Modello di colore. Quando 'Gradient type' = 'Noise', possiamo assegnare 'Color Model' a RGB/SHB/LAB (3/4/6).

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Ottiene o imposta i punti di colore.

Valore: i punti di colore.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Ottiene o imposta i dati.

Valore: I dati.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Il gradiente è dithertizzato.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Conteggio di espansione ( = 2 per Photoshop 6.0).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Lunghezza(= 32 per Photoshop 6.0) Nessuna informazione su a cosa serve.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Modalità per questo gradiente Determina 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Nome del gradiente: stringa Unicode, riempita.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolazione. Determina la fluidità, quando 'Gradient Type' = 'Solid' (GradientMode = 0).

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Ottiene o imposta il metodo di interpolazione per il gradiente.

**Returns:**
long
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Colore massimo del formato PixelDataFormat.Rgba64Bpp. Il colore ha canali ARGB, ogni canale è a 16 bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Colore minimo del formato PixelDataFormat.Rgba64Bpp. Il colore ha canali ARGB, ogni canale è a 16 bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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


Ottiene la versione minima di PSD richiesta per questa risorsa. È necessaria la versione 3 quando il metodo di interpolazione è memorizzato esplicitamente.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Il gradiente è invertito.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Il seme del numero casuale usato per generare i colori per il gradiente di rumore.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Fattore di rugosità Quando 'Gradient type' = 'Noise', possiamo assegnare 'Roughness' (0 - 2048).

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Flag per mostrare la trasparenza Quando 'Gradient type' = 'Noise', possiamo impostare 'Add transparency' su true.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Ottiene o imposta i punti di trasparenza.

Valore: i punti di trasparenza.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Flag per l'uso del colore vettoriale.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


Inizializza la lunghezza del gradiente. GradientLength è di sola lettura, quindi può essere assegnato una sola volta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | Il valore. |

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


Salva i dati della risorsa nel contenitore di stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Modello di colore. Quando 'Gradient type' = 'Noise', possiamo assegnare 'Color Model' a RGB/SHB/LAB (3/4/6).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Ottiene o imposta i punti di colore.

Valore: i punti di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Il gradiente è dithertizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Conteggio di espansione ( = 2 per Photoshop 6.0).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Modalità per questo gradiente Determina 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Nome del gradiente: stringa Unicode, riempita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolazione. Determina la fluidità, quando 'Gradient Type' = 'Solid' (GradientMode = 0).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Ottiene o imposta il metodo di interpolazione per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Colore massimo del formato PixelDataFormat.Rgba64Bpp. Il colore ha canali ARGB, ogni canale è a 16 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Colore minimo del formato PixelDataFormat.Rgba64Bpp. Il colore ha canali ARGB, ogni canale è a 16 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Il gradiente è invertito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Il seme del numero casuale usato per generare i colori per il gradiente di rumore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Fattore di rugosità Quando 'Gradient type' = 'Noise', possiamo assegnare 'Roughness' (0 - 2048).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Flag per mostrare la trasparenza Quando 'Gradient type' = 'Noise', possiamo impostare 'Add transparency' su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Ottiene o imposta i punti di trasparenza.

Valore: i punti di trasparenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Flag per l'uso del colore vettoriale.

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

