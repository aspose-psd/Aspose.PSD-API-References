---
title: "GdFlResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe GdFlResource."
type: docs
weight: 33
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class GdFlResource extends FillLayerResource
```

Classe GdFlResource. Questa risorsa contiene informazioni sul blending dell'elemento ritagliato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GdFlResource()](#GdFlResource--) | Inizializza una nuova istanza della classe [.GdFlResource](../../null/\#GdFlResource). |
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
| [addUnknownStructure_internalized(OSTypeStructure structure)](#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Aggiunge la struttura sconosciuta. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Verifica e imposta se la risorsa è specifica per PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateDefaultControlPoints_internalized()](#generateDefaultControlPoints-internalized--) | Genera i punti di controllo predefiniti. |
| [generateDefaultTransparencyPoints_internalized()](#generateDefaultTransparencyPoints-internalized--) | Genera i punti di trasparenza predefiniti. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Ottiene o imposta un valore che indica se [align with layer]. |
| [getAngle()](#getAngle--) | Ottiene o imposta l'angolo. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Ottiene il colore dell'RGB. |
| [getColorModel()](#getColorModel--) | Modello di colore - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [getColorPoints()](#getColorPoints--) | Ottiene i punti di colore. |
| [getDither()](#getDither--) | Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è dithering. |
| [getGradientInterval()](#getGradientInterval--) | Ottiene o imposta l'intervallo del gradiente. |
| [getGradientMode()](#getGradientMode--) | Modalità per questo gradiente. |
| [getGradientName()](#getGradientName--) | Ottiene o imposta il nome del gradiente. |
| [getGradientType()](#getGradientType--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Ottiene o imposta lo spostamento orizzontale. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getMaximumColor()](#getMaximumColor--) | Colore massimo di PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Colore minimo di PixelDataFormat. |
| [getOffset_internalized()](#getOffset-internalized--) | Ottiene o imposta lo spostamento. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getReverse()](#getReverse--) | Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è invertito. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Il seme del numero casuale usato per generare i colori per il gradiente di rumore. |
| [getRoughness()](#getRoughness--) | Fattore di rugosità. |
| [getScale()](#getScale--) | Ottiene o imposta la scala. |
| [getShowTransparency()](#getShowTransparency--) | Flag per mostrare la trasparenza. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Ottiene i punti di trasparenza. |
| [getUseVectorColor()](#getUseVectorColor--) | Flag per l'uso del colore vettoriale. |
| [getVerticalOffset()](#getVerticalOffset--) | Ottiene o imposta lo spostamento verticale. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Ottiene o imposta un valore che indica se [align with layer]. |
| [setAngle(double value)](#setAngle-double-) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Ottiene il colore dell'RGB. |
| [setColorModel(String value)](#setColorModel-java.lang.String-) | Modello di colore - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Ottiene i punti di colore. |
| [setDither(boolean value)](#setDither-boolean-) | Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è dithering. |
| [setGradientInterval(double value)](#setGradientInterval-double-) | Ottiene o imposta l'intervallo del gradiente. |
| [setGradientMode(String value)](#setGradientMode-java.lang.String-) | Modalità per questo gradiente. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Ottiene o imposta il nome del gradiente. |
| [setGradientType(int value)](#setGradientType-int-) |  |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) |  |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Colore massimo di PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Colore minimo di PixelDataFormat. |
| [setOffset_internalized(OffsetEntity value)](#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Ottiene o imposta lo spostamento. |
| [setReverse(boolean value)](#setReverse-boolean-) | Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è invertito. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Il seme del numero casuale usato per generare i colori per il gradiente di rumore. |
| [setRoughness(int value)](#setRoughness-int-) | Fattore di rugosità. |
| [setScale(double value)](#setScale-double-) | Ottiene o imposta la scala. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Flag per mostrare la trasparenza. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Ottiene i punti di trasparenza. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Flag per l'uso del colore vettoriale. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) |  |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdFlResource() {#GdFlResource--}
```
public GdFlResource()
```


Inizializza una nuova istanza della classe [.GdFlResource](../../null/\#GdFlResource).

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

### addUnknownStructure_internalized(OSTypeStructure structure) {#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public void addUnknownStructure_internalized(OSTypeStructure structure)
```


Aggiunge la struttura sconosciuta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La struttura. |

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
### generateDefaultControlPoints_internalized() {#generateDefaultControlPoints-internalized--}
```
public static IGradientColorPoint[] generateDefaultControlPoints_internalized()
```


Genera i punti di controllo predefiniti.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[] - I punti di controllo predefiniti.
### generateDefaultTransparencyPoints_internalized() {#generateDefaultTransparencyPoints-internalized--}
```
public static IGradientTransparencyPoint[] generateDefaultTransparencyPoints_internalized()
```


Genera i punti di trasparenza predefiniti.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[] - I punti di trasparenza predefiniti.
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Ottiene o imposta un valore che indica se [align with layer].

Valore:  true  se [align with layer]; altrimenti,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public double getAngle()
```


Ottiene o imposta l'angolo.

L'angolo.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Ottiene il colore dell'RGB.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB Color
### getColorModel() {#getColorModel--}
```
public final String getColorModel()
```


Modello di colore - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Returns:**
java.lang.String
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Ottiene i punti di colore.

Valore: i punti di colore.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è dithering.

Valore:  true  se dither; altrimenti,  false .

**Returns:**
boolean
### getGradientInterval() {#getGradientInterval--}
```
public final double getGradientInterval()
```


Ottiene o imposta l'intervallo del gradiente.

Valore: l'intervallo del gradiente.

**Returns:**
double
### getGradientMode() {#getGradientMode--}
```
public final String getGradientMode()
```


Modalità per questo gradiente. Determina 'Tipo di gradiente' = 'Solido/Rumore' = "CstS"/"ClNs".

**Returns:**
java.lang.String
### getGradientName() {#getGradientName--}
```
public String getGradientName()
```


Ottiene o imposta il nome del gradiente.

Valore: Il nome del gradiente.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public int getGradientType()
```




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
### getHorizontalOffset() {#getHorizontalOffset--}
```
public double getHorizontalOffset()
```


Ottiene o imposta lo spostamento orizzontale.

Lo spostamento orizzontale.

**Returns:**
double
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


Colore massimo di PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Colore minimo di PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getOffset_internalized() {#getOffset-internalized--}
```
public final OffsetEntity getOffset_internalized()
```


Ottiene o imposta lo spostamento.

Valore: lo spostamento.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è invertito.

Valore:  true  se invertito; altrimenti,  false .

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


Fattore di rugosità.

**Returns:**
int
### getScale() {#getScale--}
```
public final double getScale()
```


Ottiene o imposta la scala.

**Returns:**
double
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Flag per mostrare la trasparenza.

**Returns:**
boolean
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


Ottiene i punti di trasparenza.

Valore: i punti di trasparenza.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Flag per l'uso del colore vettoriale.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public double getVerticalOffset()
```


Ottiene o imposta lo spostamento verticale.

Lo spostamento verticale.

**Returns:**
double
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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Ottiene o imposta un valore che indica se [align with layer].

Valore:  true  se [align with layer]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Ottiene il colore dell'RGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setColorModel(String value) {#setColorModel-java.lang.String-}
```
public final void setColorModel(String value)
```


Modello di colore - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Ottiene i punti di colore.

Valore: i punti di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è dithering.

Valore:  true  se dither; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setGradientInterval(double value) {#setGradientInterval-double-}
```
public final void setGradientInterval(double value)
```


Ottiene o imposta l'intervallo del gradiente.

Valore: l'intervallo del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setGradientMode(String value) {#setGradientMode-java.lang.String-}
```
public final void setGradientMode(String value)
```


Modalità per questo gradiente. Determina 'Tipo di gradiente' = 'Solido/Rumore' = "CstS"/"ClNs".

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public void setGradientName(String value)
```


Ottiene o imposta il nome del gradiente.

Valore: Il nome del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public void setGradientType(int value)
```




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

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public void setHorizontalOffset(double value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

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


Colore massimo di PixelDataFormat.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Colore minimo di PixelDataFormat.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setOffset_internalized(OffsetEntity value) {#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setOffset_internalized(OffsetEntity value)
```


Ottiene o imposta lo spostamento.

Valore: lo spostamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Ottiene o imposta un valore che indica se questo [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) è invertito.

Valore:  true  se invertito; altrimenti,  false .

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


Fattore di rugosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Ottiene o imposta la scala.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Flag per mostrare la trasparenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Ottiene i punti di trasparenza.

Valore: i punti di trasparenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Flag per l'uso del colore vettoriale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public void setVerticalOffset(double value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

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

