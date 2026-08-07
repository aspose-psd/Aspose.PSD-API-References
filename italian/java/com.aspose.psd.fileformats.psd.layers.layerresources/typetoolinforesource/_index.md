---
title: "TypeToolInfoResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le informazioni dello strumento di tipo."
type: docs
weight: 79
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

Le informazioni sullo strumento di tipo. Per versioni PSD inferiori a 6.0.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | Inizializza una nuova istanza della classe [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource). |
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
| [getAComponent()](#getAComponent--) | Ottiene o imposta un componente. |
| [getBComponent()](#getBComponent--) | Ottiene o imposta il componente b. |
| [getCharacterCount()](#getCharacterCount--) | Ottiene o imposta il conteggio dei caratteri. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | Ottiene o imposta il valore dello spazio colore. |
| [getFontVersion()](#getFontVersion--) | Ottiene o imposta la versione del font. |
| [getFonts()](#getFonts--) | Ottiene o imposta i font. |
| [getFontsCount()](#getFontsCount--) | Ottiene il conteggio dei font. |
| [getGComponent()](#getGComponent--) | Ottiene o imposta il componente g. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | Ottiene o imposta il posizionamento orizzontale. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getLineCount()](#getLineCount--) | Ottiene il conteggio delle linee. |
| [getLines()](#getLines--) | Ottiene o imposta le linee. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getRComponent()](#getRComponent--) | Ottiene o imposta il componente r. |
| [getScaleFactor()](#getScaleFactor--) | Ottiene o imposta il fattore di scala. |
| [getSelectionEnd()](#getSelectionEnd--) | Ottiene o imposta la fine della selezione. |
| [getSelectionStart()](#getSelectionStart--) | Ottiene o imposta l'inizio della selezione. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getStyles()](#getStyles--) | Ottiene o imposta gli stili del carattere. |
| [getStylesCount()](#getStylesCount--) | Ottiene il conteggio degli stili. |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta la matrice di trasformazione. |
| [getTypeValue()](#getTypeValue--) | Ottiene o imposta il valore del tipo. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione. |
| [getVerticalPlacement()](#getVerticalPlacement--) | Ottiene o imposta il posizionamento verticale. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva il contenitore di flusso specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setAComponent(short value)](#setAComponent-short-) | Ottiene o imposta un componente. |
| [setBComponent(short value)](#setBComponent-short-) | Ottiene o imposta il componente b. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | Ottiene o imposta il conteggio dei caratteri. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | Ottiene o imposta i dati di colore grezzi. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | Ottiene o imposta il valore dello spazio colore. |
| [setFontVersion(short value)](#setFontVersion-short-) | Ottiene o imposta la versione del font. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | Ottiene o imposta i font. |
| [setGComponent(short value)](#setGComponent-short-) | Ottiene o imposta il componente g. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | Ottiene o imposta il posizionamento orizzontale. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | Ottiene o imposta le linee. |
| [setRComponent(short value)](#setRComponent-short-) | Ottiene o imposta il componente r. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | Ottiene o imposta il fattore di scala. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | Ottiene o imposta la fine della selezione. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | Ottiene o imposta l'inizio della selezione. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | Ottiene o imposta gli stili del carattere. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Ottiene o imposta la matrice di trasformazione. |
| [setTypeValue(short value)](#setTypeValue-short-) | Ottiene o imposta il valore del tipo. |
| [setVersion(short value)](#setVersion-short-) | Ottiene o imposta la versione. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | Ottiene o imposta il posizionamento verticale. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


Inizializza una nuova istanza della classe [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource).

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


Ottiene o imposta un componente.

Valore: un componente.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


Ottiene o imposta il componente b.

Valore: il componente b.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


Ottiene o imposta il conteggio dei caratteri.

Valore: il conteggio dei caratteri.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


Ottiene o imposta il valore dello spazio colore.

Valore: il valore dello spazio colore.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


Ottiene o imposta la versione del font.

Valore: la versione del carattere.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


Ottiene o imposta i font.

Valore: i caratteri.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


Ottiene il conteggio dei font.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


Ottiene o imposta il componente g.

Valore: il componente g.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


Ottiene o imposta il posizionamento orizzontale.

Valore: il posizionamento orizzontale.

**Returns:**
int
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
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


Ottiene il conteggio delle linee.

Valore: il conteggio delle linee.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


Ottiene o imposta le linee.

Valore: le linee.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
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
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


Ottiene o imposta il componente r.

Valore: il componente r.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


Ottiene o imposta il fattore di scala.

Valore: il fattore di scala.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


Ottiene o imposta la fine della selezione.

Valore: la fine della selezione.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


Ottiene o imposta l'inizio della selezione.

Valore: l'inizio della selezione.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


Ottiene o imposta gli stili del carattere.

Valore: gli stili del carattere.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


Ottiene il conteggio degli stili.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Ottiene o imposta la matrice di trasformazione.

Valore: La matrice di trasformazione.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


Ottiene o imposta il valore del tipo.

Valore: Il valore del tipo.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Ottiene o imposta la versione.

Valore: La versione.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


Ottiene o imposta il posizionamento verticale.

Valore: La posizione verticale.

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


Salva il contenitore di flusso specificato.

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

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


Ottiene o imposta un componente.

Valore: un componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


Ottiene o imposta il componente b.

Valore: il componente b.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


Ottiene o imposta il conteggio dei caratteri.

Valore: il conteggio dei caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


Ottiene o imposta i dati di colore grezzi.

Valore: I dati di colore grezzi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


Ottiene o imposta il valore dello spazio colore.

Valore: il valore dello spazio colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


Ottiene o imposta la versione del font.

Valore: la versione del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


Ottiene o imposta i font.

Valore: i caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


Ottiene o imposta il componente g.

Valore: il componente g.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

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

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


Ottiene o imposta il posizionamento orizzontale.

Valore: il posizionamento orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


Ottiene o imposta le linee.

Valore: le linee.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


Ottiene o imposta il componente r.

Valore: il componente r.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


Ottiene o imposta il fattore di scala.

Valore: il fattore di scala.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


Ottiene o imposta la fine della selezione.

Valore: la fine della selezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


Ottiene o imposta l'inizio della selezione.

Valore: l'inizio della selezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


Ottiene o imposta gli stili del carattere.

Valore: gli stili del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Ottiene o imposta la matrice di trasformazione.

Valore: La matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


Ottiene o imposta il valore del tipo.

Valore: Il valore del tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Ottiene o imposta la versione.

Valore: La versione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


Ottiene o imposta il posizionamento verticale.

Valore: La posizione verticale.

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

