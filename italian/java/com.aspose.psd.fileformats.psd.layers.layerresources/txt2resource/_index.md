---
title: "Txt2Resource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe risorsa Txt2"
type: docs
weight: 76
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class Txt2Resource extends LayerResource
```

Classe risorsa Txt2
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Txt2Resource()](#Txt2Resource--) | Inizializza una nuova istanza della classe [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource). |
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
| [addTextRecord(String text, RectangleF bounds)](#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-) | Aggiunge il record di testo a Resource e restituisce l'ID del record di testo. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Verifica e imposta se la risorsa è specifica per PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Ottiene se la risorsa è compressa. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getParsedTxt2Model_internalized()](#getParsedTxt2Model-internalized--) | Analizza i dati txt2 in un'istanza della classe Txt2DataRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getTextData()](#getTextData--) | Ottiene il record di testo dai dati della risorsa. |
| [getText_internalized()](#getText-internalized--) | Ottiene o imposta il nome. |
| [getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Ottiene il TXT2 dall'albero analizzato. |
| [getTxt2ParsedTree_internalized()](#getTxt2ParsedTree-internalized--) | Ottiene l'albero analizzato del TXT2. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTextRecord_internalized(int textIndex)](#removeTextRecord-internalized-int-) | Rimuove il record di testo da Resource. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva il contenitore di flusso specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta i dati. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setText_internalized(String value)](#setText-internalized-java.lang.String-) | Ottiene o imposta il nome. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)](#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-) | Aggiorna il record di testo per indice di testo con nuovi dati di testo predefiniti e nuovo testo, dimensione del carattere e colore. |
| [updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)](#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-) | Aggiorna i dati txt2 dal modello Txt2DataRoot. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Txt2Resource() {#Txt2Resource--}
```
public Txt2Resource()
```


Inizializza una nuova istanza della classe [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource).

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

### addTextRecord(String text, RectangleF bounds) {#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-}
```
public final int addTextRecord(String text, RectangleF bounds)
```


Aggiunge il record di testo a Resource e restituisce l'ID del record di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Il testo del record. |
| bounds | [RectangleF](../../com.aspose.psd/rectanglef) | I limiti. |

**Returns:**
int - Restituisce l'ID del record di testo per la risorsa
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
### getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public static ITextEngineKeys getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Ottiene se la risorsa è compressa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| albero | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | L'albero. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.ITextEngineKeys - Restituisce un oggetto con le chiavi.
### getLength() {#getLength--}
```
public int getLength()
```


Ottiene la lunghezza della risorsa del livello in byte.

**Returns:**
int
### getParsedTxt2Model_internalized() {#getParsedTxt2Model-internalized--}
```
public final Txt2DataRoot getParsedTxt2Model_internalized()
```


Analizza i dati txt2 in un'istanza della classe Txt2DataRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot - I dati txt2 come istanza della classe Txt2DataRoot.
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
### getTextData() {#getTextData--}
```
public final String[] getTextData()
```


Ottiene il record di testo dai dati della risorsa.

**Returns:**
java.lang.String[] - Array di record di testo
### getText_internalized() {#getText-internalized--}
```
public final String getText_internalized()
```


Ottiene o imposta il nome.

Valore: Il nome.

**Returns:**
java.lang.String
### getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public final String getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Ottiene il TXT2 dall'albero analizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| albero | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | L'albero dei dati. |

**Returns:**
java.lang.String - I dati Txt2.
### getTxt2ParsedTree_internalized() {#getTxt2ParsedTree-internalized--}
```
public final System.Collections.Generic.Dictionary<String,Object> getTxt2ParsedTree_internalized()
```


Ottiene l'albero analizzato del TXT2.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> - Albero analizzato
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




### removeTextRecord_internalized(int textIndex) {#removeTextRecord-internalized-int-}
```
public final void removeTextRecord_internalized(int textIndex)
```


Rimuove il record di testo da Resource.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textIndex | int | L'indice del record di testo da rimuovere. |

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

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Ottiene o imposta i dati.

Valore: I dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

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

### setText_internalized(String value) {#setText-internalized-java.lang.String-}
```
public final void setText_internalized(String value)
```


Ottiene o imposta il nome.

Valore: Il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una String che rappresenta questa istanza.

**Returns:**
java.lang.String - Una String che rappresenta questa istanza.
### updateTextData_internalized(int textIndex, String newText, double fontSize, Color color) {#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-}
```
public final void updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)
```


Aggiorna il record di testo per indice di testo con nuovi dati di testo predefiniti e nuovo testo, dimensione del carattere e colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textIndex | int | L'indice del record di testo nei dati della risorsa txt2. |
| newText | java.lang.String | Il nuovo testo. |
| fontSize | double | la nuova dimensione del carattere. |
| color | [Color](../../com.aspose.psd/color) | Il nuovo colore del testo. |

### updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot) {#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-}
```
public final void updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)
```


Aggiorna i dati txt2 dal modello Txt2DataRoot.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| txt2DataRoot | com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot | Il modello di dati txt2. |

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

