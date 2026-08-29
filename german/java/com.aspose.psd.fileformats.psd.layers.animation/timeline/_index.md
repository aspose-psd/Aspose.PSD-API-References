---
title: "Timeline"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Das Modell der Zeitlinienoptionen."
type: docs
weight: 14
url: /de/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

Das Modell der Zeitlinienoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Timeline()](#Timeline--) | Initialisiert eine neue Instanz der [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Wendet aktuelle Zeitlinienwerte auf das Eingabe-PsdImage an ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | Liest oder setzt den AFSt-Wert. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Liest oder setzt den aktiven Frame-Index. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Liest das Frame anhand der ID. |
| [getFrames()](#getFrames--) | Liest die Liste der Frames. |
| [getFramesList()](#getFramesList--) | Liest die Liste der Frames. |
| [getFsID()](#getFsID--) | Liest oder setzt den FsID-Wert. |
| [getLoopesCount()](#getLoopesCount--) | Liest oder setzt die Anzahl der Schleifen. |
| [getPsdImage()](#getPsdImage--) | Liest oder setzt das PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dieses [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | Speichert die Daten von PsdImage und Timeline in den angegebenen Stream im angegebenen Format gemäß den Speicheroptionen. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Speichert die Daten von PsdImage und Timeline am angegebenen Dateipfad im angegebenen Format gemäß den Speicheroptionen. |
| [setAFSt(int value)](#setAFSt-int-) | Liest oder setzt den AFSt-Wert. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Liest oder setzt den aktiven Frame-Index. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Liest die Liste der Frames. |
| [setFsID(int value)](#setFsID-int-) | Liest oder setzt den FsID-Wert. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Liest oder setzt die Anzahl der Schleifen. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Liest oder setzt das PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dieses [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Wechselt das aktive Frame zum Ziel-Frame. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Wendet aktuelle Zeitlinienwerte auf das Eingabe-PsdImage an ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Initialisiert eine neue Instanz der [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)-Klasse.

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Wendet aktuelle Zeitlinienwerte auf das Eingabe-PsdImage an ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Das PSD-Bild. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


Liest oder setzt den AFSt-Wert.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Liest oder setzt den aktiven Frame-Index.

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


Liest das Frame anhand der ID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frameId | int | Die Frame-ID. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Liest die Liste der Frames.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Liest die Liste der Frames.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


Liest oder setzt den FsID-Wert.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Liest oder setzt die Anzahl der Schleifen.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Liest oder setzt das PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dieses [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

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


Speichert die Daten von PsdImage und Timeline in den angegebenen Stream im angegebenen Format gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | Der Ausgabestream. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionen. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Speichert die Daten von PsdImage und Timeline am angegebenen Dateipfad im angegebenen Format gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionen. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


Liest oder setzt den AFSt-Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Liest oder setzt den aktiven Frame-Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Liest die Liste der Frames.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


Liest oder setzt den FsID-Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Liest oder setzt die Anzahl der Schleifen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Liest oder setzt das PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dieses [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Wechselt das aktive Frame zum Ziel-Frame.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetActiveFrameIndex | int | Der Ziel-Frame-Index. |

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


Wendet aktuelle Zeitlinienwerte auf das Eingabe-PsdImage an ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frameIndex | int | Der Frame-Index zum Aktualisieren der Layer-Zustände. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

