---
title: "VstkResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe di risorsa VstkResource."
type: docs
weight: 14
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

Classe di risorsa VstkResource. Contiene informazioni sui dati del tratto vettoriale. La risorsa dovrebbe essere inizializzata o tramite il metodo AssignItems da resourcedata, o assegnando valori alle proprietà della classe.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VstkResource()](#VstkResource--) | Inizializza una nuova istanza della classe [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource). |
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
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Assegna le strutture degli elementi dalla risorsa Vstk. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Verifica e imposta se la risorsa è specifica per PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Ottiene o imposta l'istanza ClassID. |
| [getClassName_internalized()](#getClassName-internalized--) | Ottiene o imposta il nome della classe. |
| [getFillEnabled()](#getFillEnabled--) | Ottiene o imposta un valore che indica se il riempimento del tratto è abilitato. |
| [getFillSettings()](#getFillSettings--) | Ottiene o imposta le impostazioni di riempimento del tratto. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getStrokeEnabled()](#getStrokeEnabled--) | Ottiene o imposta un valore che indica se l'effetto del tratto è abilitato. |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | Ottiene o imposta la modalità di fusione Stroke. |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | Ottiene o imposta l'entità Stroke. |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | Ottiene o imposta l'allineamento della linea dello stile del tratto. |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | Ottiene o imposta il tipo di cappuccio di linea dello stile stroke. |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | Ottiene o imposta la larghezza del cappuccio di linea Stroke. |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | Ottiene o imposta l'offset di tratteggio della linea dello stile stroke. |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | Ottiene o imposta l'array di tratti di linea. |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | Ottiene o imposta il tipo di unione di linea dello stile Stroke. |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | Ottiene o imposta la larghezza della linea Stroke. |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | Ottiene o imposta il limite di spigolo dello stile stroke. |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | Ottiene o imposta l'opacità dello stile Stroke (0-100%). |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | Ottiene o imposta la risoluzione dello stile Stroke. |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | Ottiene o imposta il blocco di scala dello stile Stroke. |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | Ottiene o imposta la regolazione Stroke. |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | Ottiene o imposta la versione dello stile stroke. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Ottiene o imposta l'istanza ClassID. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Ottiene o imposta il nome della classe. |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | Ottiene o imposta un valore che indica se il riempimento del tratto è abilitato. |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Ottiene o imposta le impostazioni di riempimento del tratto. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | Ottiene o imposta un valore che indica se l'effetto del tratto è abilitato. |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | Ottiene o imposta la modalità di fusione Stroke. |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | Ottiene o imposta l'entità Stroke. |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | Ottiene o imposta l'allineamento della linea dello stile del tratto. |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | Ottiene o imposta il tipo di cappuccio di linea dello stile stroke. |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | Ottiene o imposta la larghezza del cappuccio di linea Stroke. |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | Ottiene o imposta l'offset di tratteggio della linea dello stile stroke. |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | Ottiene o imposta l'array di tratti di linea. |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | Ottiene o imposta il tipo di unione di linea dello stile Stroke. |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | Ottiene o imposta la larghezza della linea Stroke. |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | Ottiene o imposta il limite di spigolo dello stile stroke. |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | Ottiene o imposta l'opacità dello stile Stroke (0-100%). |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | Ottiene o imposta la risoluzione dello stile Stroke. |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | Ottiene o imposta il blocco di scala dello stile Stroke. |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | Ottiene o imposta la regolazione Stroke. |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | Ottiene o imposta la versione dello stile stroke. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


Inizializza una nuova istanza della classe [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource).

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

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


Assegna le strutture degli elementi dalla risorsa Vstk.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Elenco di istanze OSTypeStructure. |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Ottiene o imposta l'istanza ClassID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Ottiene o imposta il nome della classe.

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


Ottiene o imposta un valore che indica se il riempimento del tratto è abilitato.

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Ottiene o imposta le impostazioni di riempimento del tratto.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
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
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


Ottiene o imposta un valore che indica se l'effetto del tratto è abilitato.

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


Ottiene o imposta la modalità di fusione Stroke.

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


Ottiene o imposta l'entità Stroke. La proprietà determina le impostazioni di riempimento dello stroke.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


Ottiene o imposta l'allineamento della linea dello stile del tratto.

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


Ottiene o imposta il tipo di cappuccio di linea dello stile stroke.

Valore: Il tipo di cappuccio di linea dello stile stroke.

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


Ottiene o imposta la larghezza del cappuccio di linea Stroke.

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


Ottiene o imposta l'offset di tratteggio della linea dello stile stroke.

Valore: L'offset di tratteggio della linea dello stile stroke.

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


Ottiene o imposta l'array di tratti di linea.

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


Ottiene o imposta il tipo di unione di linea dello stile Stroke.

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


Ottiene o imposta la larghezza della linea Stroke.

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


Ottiene o imposta il limite di spigolo dello stile stroke.

Valore: Il limite di spigolo dello stile stroke.

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


Ottiene o imposta l'opacità dello stile Stroke (0-100%).

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


Ottiene o imposta la risoluzione dello stile Stroke.

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


Ottiene o imposta il blocco di scala dello stile Stroke.

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


Ottiene o imposta la regolazione Stroke.

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


Ottiene o imposta la versione dello stile stroke.

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Ottiene o imposta l'istanza ClassID.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Ottiene o imposta il nome della classe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


Ottiene o imposta un valore che indica se il riempimento del tratto è abilitato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


Ottiene o imposta le impostazioni di riempimento del tratto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


Ottiene o imposta un valore che indica se l'effetto del tratto è abilitato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


Ottiene o imposta la modalità di fusione Stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


Ottiene o imposta l'entità Stroke. La proprietà determina le impostazioni di riempimento dello stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


Ottiene o imposta l'allineamento della linea dello stile del tratto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


Ottiene o imposta il tipo di cappuccio di linea dello stile stroke.

Valore: Il tipo di cappuccio di linea dello stile stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


Ottiene o imposta la larghezza del cappuccio di linea Stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


Ottiene o imposta l'offset di tratteggio della linea dello stile stroke.

Valore: L'offset di tratteggio della linea dello stile stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


Ottiene o imposta l'array di tratti di linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


Ottiene o imposta il tipo di unione di linea dello stile Stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


Ottiene o imposta la larghezza della linea Stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


Ottiene o imposta il limite di spigolo dello stile stroke.

Valore: Il limite di spigolo dello stile stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


Ottiene o imposta l'opacità dello stile Stroke (0-100%).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


Ottiene o imposta la risoluzione dello stile Stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


Ottiene o imposta il blocco di scala dello stile Stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


Ottiene o imposta la regolazione Stroke.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


Ottiene o imposta la versione dello stile stroke.

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

