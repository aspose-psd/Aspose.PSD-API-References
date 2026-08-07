---
title: "TypeToolInfo6Resource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le informazioni dello strumento di tipo."
type: docs
weight: 78
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfo6Resource extends LayerResource
```

Le informazioni dello strumento tipo. Per la versione PSD superiore o uguale alla 6.0.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)](#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Inizializza una nuova istanza della classe [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource). |
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
| [getBottom()](#getBottom--) | Ottiene o imposta la posizione inferiore. |
| [getBoundingBox_internalized()](#getBoundingBox-internalized--) | Ottiene o imposta i limiti del testo nella casella di testo. |
| [getBounds_internalized()](#getBounds-internalized--) | Ottiene o imposta i limiti della casella di testo. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Ottiene o imposta l'ID della classe. |
| [getClassName()](#getClassName--) | Ottiene o imposta il nome della classe. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Ottiene o imposta la versione del descrittore. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getItems()](#getItems--) | Ottiene o imposta gli elementi. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa del livello in byte. |
| [getParsedTyShModel_internalized()](#getParsedTyShModel-internalized--) | Analizza i dati grezzi in un'istanza della classe TyShRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getRawDataStructure_internalized()](#getRawDataStructure-internalized--) | Ottiene l'elemento [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) se esiste. |
| [getRight()](#getRight--) | Ottiene o imposta la posizione destra. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getTextIndex_internalized()](#getTextIndex-internalized--) | Ottiene l'indice del testo in questa risorsa. |
| [getTextVersion()](#getTextVersion--) | Ottiene o imposta la versione del testo. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore. |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta la matrice di trasformazione. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione dello strumento tipo. |
| [getWarpClassID()](#getWarpClassID--) | Ottiene o imposta l'ID della classe. |
| [getWarpClassName()](#getWarpClassName--) | Ottiene o imposta il nome della classe di deformazione. |
| [getWarpDescriptorVersion()](#getWarpDescriptorVersion--) | Ottiene o imposta la versione del descrittore di deformazione. |
| [getWarpItems()](#getWarpItems--) | Ottiene o imposta gli elementi del warp. |
| [getWarpVersion()](#getWarpVersion--) | Ottiene o imposta la versione della deformazione. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta la posizione inferiore. |
| [setBoundingBox_internalized(RectangleF value)](#setBoundingBox-internalized-com.aspose.psd.RectangleF-) | Ottiene o imposta i limiti del testo nella casella di testo. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Ottiene o imposta l'ID della classe. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Ottiene o imposta il nome della classe. |
| [setDescriptorVersion(int value)](#setDescriptorVersion-int-) | Ottiene o imposta la versione del descrittore. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Ottiene o imposta gli elementi. |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta la posizione sinistra. |
| [setRight(int value)](#setRight-int-) | Ottiene o imposta la posizione destra. |
| [setTextVersion(short value)](#setTextVersion-short-) | Ottiene o imposta la versione del testo. |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la posizione superiore. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Ottiene o imposta la matrice di trasformazione. |
| [setVersion(short value)](#setVersion-short-) | Ottiene o imposta la versione dello strumento tipo. |
| [setWarpClassID(ClassID value)](#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Ottiene o imposta l'ID della classe. |
| [setWarpClassName(String value)](#setWarpClassName-java.lang.String-) | Ottiene o imposta il nome della classe di deformazione. |
| [setWarpDescriptorVersion(int value)](#setWarpDescriptorVersion-int-) | Ottiene o imposta la versione del descrittore di deformazione. |
| [setWarpItems(OSTypeStructure[] value)](#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Ottiene o imposta gli elementi del warp. |
| [setWarpVersion(short value)](#setWarpVersion-short-) | Ottiene o imposta la versione della deformazione. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [updateFromTyShModel_internalized(TyShRoot dataModel)](#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-) | Serializza i dati TyShRoot in formato raw. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfo6Resource(ClassID classID, ClassID warpClassID) {#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)
```


Inizializza una nuova istanza della classe [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID della classe. |
| warpClassID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID della classe warp. |

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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Ottiene o imposta la posizione inferiore.

Valore: La posizione inferiore.

**Returns:**
int
### getBoundingBox_internalized() {#getBoundingBox-internalized--}
```
public final RectangleF getBoundingBox_internalized()
```


Ottiene o imposta i limiti del testo nella casella di testo.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds_internalized() {#getBounds-internalized--}
```
public final RectangleF getBounds_internalized()
```


Ottiene o imposta i limiti della casella di testo.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassID() {#getClassID--}
```
public final ClassID getClassID()
```


Ottiene o imposta l'ID della classe.

Valore: L'ID della classe.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


Ottiene o imposta il nome della classe.

Valore: Il nome della classe.

**Returns:**
java.lang.String
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Ottiene o imposta la versione del descrittore.

Valore: La versione del descrittore.

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
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Ottiene o imposta gli elementi.

Valore: gli elementi.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Ottiene la chiave della risorsa del livello.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ottiene o imposta la posizione sinistra.

Valore: La posizione sinistra.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Ottiene la lunghezza della risorsa del livello in byte.

**Returns:**
int
### getParsedTyShModel_internalized() {#getParsedTyShModel-internalized--}
```
public final TyShRoot getParsedTyShModel_internalized()
```


Analizza i dati grezzi in un'istanza della classe TyShRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot - I dati grezzi come istanza della classe TyShRoot.
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
### getRawDataStructure_internalized() {#getRawDataStructure-internalized--}
```
public final RawDataStructure getRawDataStructure_internalized()
```


Ottiene l'elemento [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) se esiste.

**Returns:**
[RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) - The raw data structure.
### getRight() {#getRight--}
```
public final int getRight()
```


Ottiene o imposta la posizione destra.

Valore: La posizione destra.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

**Returns:**
int
### getTextIndex_internalized() {#getTextIndex-internalized--}
```
public final int getTextIndex_internalized()
```


Ottiene l'indice del testo in questa risorsa.

**Returns:**
int - Restituisce l'indice del testo in questa risorsa.
### getTextVersion() {#getTextVersion--}
```
public final short getTextVersion()
```


Ottiene o imposta la versione del testo.

Valore: La versione del testo.

**Returns:**
short
### getTop() {#getTop--}
```
public final int getTop()
```


Ottiene o imposta la posizione superiore.

Valore: La posizione superiore.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Ottiene o imposta la matrice di trasformazione.

Valore: La matrice di trasformazione.

**Returns:**
double[]
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Ottiene o imposta la versione dello strumento tipo.

Valore: La versione dello strumento tipo.

**Returns:**
short
### getWarpClassID() {#getWarpClassID--}
```
public final ClassID getWarpClassID()
```


Ottiene o imposta l'ID della classe.

Valore: L'ID della classe.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName() {#getWarpClassName--}
```
public final String getWarpClassName()
```


Ottiene o imposta il nome della classe di deformazione.

Valore: Il nome della classe di deformazione.

**Returns:**
java.lang.String
### getWarpDescriptorVersion() {#getWarpDescriptorVersion--}
```
public final int getWarpDescriptorVersion()
```


Ottiene o imposta la versione del descrittore di deformazione.

Valore: La versione del descrittore di deformazione.

**Returns:**
int
### getWarpItems() {#getWarpItems--}
```
public final OSTypeStructure[] getWarpItems()
```


Ottiene o imposta gli elementi del warp.

Valore: Gli elementi di deformazione.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion() {#getWarpVersion--}
```
public final short getWarpVersion()
```


Ottiene o imposta la versione della deformazione.

Valore: La versione della deformazione.

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

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Ottiene o imposta la posizione inferiore.

Valore: La posizione inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBoundingBox_internalized(RectangleF value) {#setBoundingBox-internalized-com.aspose.psd.RectangleF-}
```
public final void setBoundingBox_internalized(RectangleF value)
```


Ottiene o imposta i limiti del testo nella casella di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


Ottiene o imposta l'ID della classe.

Valore: L'ID della classe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


Ottiene o imposta il nome della classe.

Valore: Il nome della classe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDescriptorVersion(int value) {#setDescriptorVersion-int-}
```
public final void setDescriptorVersion(int value)
```


Ottiene o imposta la versione del descrittore.

Valore: La versione del descrittore.

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Ottiene o imposta gli elementi.

Valore: gli elementi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ottiene o imposta la posizione sinistra.

Valore: La posizione sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Ottiene o imposta la posizione destra.

Valore: La posizione destra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTextVersion(short value) {#setTextVersion-short-}
```
public final void setTextVersion(short value)
```


Ottiene o imposta la versione del testo.

Valore: La versione del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ottiene o imposta la posizione superiore.

Valore: La posizione superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Ottiene o imposta la versione dello strumento tipo.

Valore: La versione dello strumento tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setWarpClassID(ClassID value) {#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID(ClassID value)
```


Ottiene o imposta l'ID della classe.

Valore: L'ID della classe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName(String value) {#setWarpClassName-java.lang.String-}
```
public final void setWarpClassName(String value)
```


Ottiene o imposta il nome della classe di deformazione.

Valore: Il nome della classe di deformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setWarpDescriptorVersion(int value) {#setWarpDescriptorVersion-int-}
```
public final void setWarpDescriptorVersion(int value)
```


Ottiene o imposta la versione del descrittore di deformazione.

Valore: La versione del descrittore di deformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWarpItems(OSTypeStructure[] value) {#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setWarpItems(OSTypeStructure[] value)
```


Ottiene o imposta gli elementi del warp.

Valore: Gli elementi di deformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setWarpVersion(short value) {#setWarpVersion-short-}
```
public final void setWarpVersion(short value)
```


Ottiene o imposta la versione della deformazione.

Valore: La versione della deformazione.

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
### updateFromTyShModel_internalized(TyShRoot dataModel) {#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-}
```
public final void updateFromTyShModel_internalized(TyShRoot dataModel)
```


Serializza i dati TyShRoot in formato raw.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataModel | com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot |  |

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

