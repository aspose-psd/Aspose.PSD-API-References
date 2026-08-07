---
title: "GridAndGuidesResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta la risorsa della griglia e delle guide."
type: docs
weight: 20
url: /it/java/com.aspose.psd.fileformats.psd.resources/gridandguidesresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class GridAndGuidesResource extends ResourceBlock
```

Rappresenta la risorsa della griglia e delle guide.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GridAndGuidesResource()](#GridAndGuidesResource--) | Inizializza una nuova istanza della classe [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | La firma della risorsa di ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | La firma della risorsa Photoshop standard. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione dei dati della risorsa in byte. |
| [getGridCycleX()](#getGridCycleX--) | Ottiene o imposta il ciclo della griglia orizzontale. |
| [getGridCycleY()](#getGridCycleY--) | Ottiene o imposta il ciclo della griglia verticale. |
| [getGuideCount()](#getGuideCount--) | Ottiene il conteggio dei blocchi risorsa della guida. |
| [getGuides()](#getGuides--) | Ottiene o imposta le guide. |
| [getHeaderVersion()](#getHeaderVersion--) | Ottiene o imposta la versione dell'intestazione. |
| [getID()](#getID--) | Ottiene o imposta l'identificatore univoco per la risorsa. |
| [getMinimalVersion()](#getMinimalVersion--) | Ottiene la versione PSD minima richiesta. |
| [getName()](#getName--) | Ottiene o imposta il nome della risorsa. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa. |
| [getSize()](#getSize--) | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Salva il blocco risorsa nello stream specificato. |
| [setGridCycleX(int value)](#setGridCycleX-int-) | Ottiene o imposta il ciclo della griglia orizzontale. |
| [setGridCycleY(int value)](#setGridCycleY-int-) | Ottiene o imposta il ciclo della griglia verticale. |
| [setGuides(GuideResource[] value)](#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---) | Ottiene o imposta le guide. |
| [setHeaderVersion(int value)](#setHeaderVersion-int-) | Ottiene o imposta la versione dell'intestazione. |
| [setID(short value)](#setID-short-) | Ottiene o imposta l'identificatore univoco per la risorsa. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Ottiene o imposta le informazioni del livello e della maschera. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome della risorsa. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Ottiene o imposta lo stato del blocco risorsa. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Convalida i valori della risorsa. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GridAndGuidesResource() {#GridAndGuidesResource--}
```
public GridAndGuidesResource()
```


Inizializza una nuova istanza della classe [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


La firma della risorsa di ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


La firma della risorsa Photoshop standard.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Ottiene la dimensione dei dati della risorsa in byte.

Valore: La dimensione dei dati della risorsa.

**Returns:**
int
### getGridCycleX() {#getGridCycleX--}
```
public final int getGridCycleX()
```


Ottiene o imposta il ciclo della griglia orizzontale. Il valore predefinito è 576.

Valore: Il ciclo della griglia orizzontale.

**Returns:**
int
### getGridCycleY() {#getGridCycleY--}
```
public final int getGridCycleY()
```


Ottiene o imposta il ciclo della griglia verticale. Il valore predefinito è 576.

Valore: Il ciclo della griglia verticale.

**Returns:**
int
### getGuideCount() {#getGuideCount--}
```
public final int getGuideCount()
```


Ottiene il conteggio dei blocchi risorsa della guida.

Valore: Il conteggio dei blocchi risorsa della guida.

**Returns:**
int
### getGuides() {#getGuides--}
```
public final GuideResource[] getGuides()
```


Ottiene o imposta le guide.

Valore: Le guide.

**Returns:**
com.aspose.psd.fileformats.psd.resources.GuideResource[]
### getHeaderVersion() {#getHeaderVersion--}
```
public final int getHeaderVersion()
```


Ottiene o imposta la versione dell'intestazione. Questo valore dovrebbe essere sempre 1.

Valore: La versione dell'intestazione.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Ottiene o imposta l'identificatore univoco per la risorsa.

Valore: L'identificatore univoco della risorsa.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Ottiene la versione PSD minima richiesta.

Valore: La versione minima psd.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0).

Valore: Il nome della risorsa.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'.

Valore: La firma della risorsa.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene la dimensione del blocco risorsa in byte, inclusi i dati.

Valore: La dimensione del blocco della risorsa.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Salva il blocco risorsa nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso su cui salvare il blocco della risorsa. |

### setGridCycleX(int value) {#setGridCycleX-int-}
```
public final void setGridCycleX(int value)
```


Ottiene o imposta il ciclo della griglia orizzontale. Il valore predefinito è 576.

Valore: Il ciclo della griglia orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGridCycleY(int value) {#setGridCycleY-int-}
```
public final void setGridCycleY(int value)
```


Ottiene o imposta il ciclo della griglia verticale. Il valore predefinito è 576.

Valore: Il ciclo della griglia verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGuides(GuideResource[] value) {#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---}
```
public final void setGuides(GuideResource[] value)
```


Ottiene o imposta le guide.

Valore: Le guide.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GuideResource\[\]](../../com.aspose.psd.fileformats.psd.resources/guideresource) |  |

### setHeaderVersion(int value) {#setHeaderVersion-int-}
```
public final void setHeaderVersion(int value)
```


Ottiene o imposta la versione dell'intestazione. Questo valore dovrebbe essere sempre 1.

Valore: La versione dell'intestazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Ottiene o imposta l'identificatore univoco per la risorsa.

Valore: L'identificatore univoco della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Ottiene o imposta le informazioni del livello e della maschera.

Valore: Le informazioni di livello e maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0).

Valore: Il nome della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firma | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Ottiene o imposta lo stato del blocco risorsa.

Valore: Lo stato del blocco della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Convalida i valori della risorsa.

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

