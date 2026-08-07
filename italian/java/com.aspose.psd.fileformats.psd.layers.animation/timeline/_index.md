---
title: "Timeline"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il modello delle opzioni della timeline."
type: docs
weight: 14
url: /it/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

Il modello delle opzioni della timeline.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Timeline()](#Timeline--) | Inizializza una nuova istanza della classe [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Applica i valori della timeline corrente all'input PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | Ottiene o imposta il valore AFSt. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Ottiene o imposta l'indice del fotogramma attivo. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Ottiene il fotogramma per ID. |
| [getFrames()](#getFrames--) | Ottiene l'elenco dei fotogrammi. |
| [getFramesList()](#getFramesList--) | Ottiene l'elenco dei fotogrammi. |
| [getFsID()](#getFsID--) | Ottiene o imposta il valore FsID. |
| [getLoopesCount()](#getLoopesCount--) | Ottiene o imposta il conteggio dei cicli. |
| [getPsdImage()](#getPsdImage--) | Ottiene o imposta il PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) di questa [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | Salva i dati di PsdImage e Timeline nello stream specificato nel formato specificato secondo le opzioni di salvataggio. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Salva i dati di PsdImage e Timeline nella posizione di file specificata nel formato specificato secondo le opzioni di salvataggio. |
| [setAFSt(int value)](#setAFSt-int-) | Ottiene o imposta il valore AFSt. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Ottiene o imposta l'indice del fotogramma attivo. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Ottiene l'elenco dei fotogrammi. |
| [setFsID(int value)](#setFsID-int-) | Ottiene o imposta il valore FsID. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Ottiene o imposta il conteggio dei cicli. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Ottiene o imposta il PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) di questa [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Passa il fotogramma attivo a quello target. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Applica i valori della timeline corrente all'input PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Inizializza una nuova istanza della classe [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Applica i valori della timeline corrente all'input PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | L'immagine psd. |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


Ottiene o imposta il valore AFSt.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Ottiene o imposta l'indice del fotogramma attivo.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


Ottiene il fotogramma per ID.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frameId | int | L'ID del fotogramma. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Ottiene l'elenco dei fotogrammi.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Ottiene l'elenco dei fotogrammi.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


Ottiene o imposta il valore FsID.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Ottiene o imposta il conteggio dei cicli.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Ottiene o imposta il PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) di questa [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


Salva i dati di PsdImage e Timeline nello stream specificato nel formato specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | Lo stream di output. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Salva i dati di PsdImage e Timeline nella posizione di file specificata nel formato specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


Ottiene o imposta il valore AFSt.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Ottiene o imposta l'indice del fotogramma attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Ottiene l'elenco dei fotogrammi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


Ottiene o imposta il valore FsID.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Ottiene o imposta il conteggio dei cicli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Ottiene o imposta il PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) di questa [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Passa il fotogramma attivo a quello target.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetActiveFrameIndex | int | L'indice del fotogramma di destinazione. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


Applica i valori della timeline corrente all'input PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frameIndex | int | L'indice del fotogramma per aggiornare gli stati dei layer. |

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

