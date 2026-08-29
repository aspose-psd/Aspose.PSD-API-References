---
title: "Timeline"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Het tijdlijnoptiesmodel."
type: docs
weight: 14
url: /nl/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

Het tijdlijnoptiesmodel.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Timeline()](#Timeline--) | Initialiseert een nieuw exemplaar van de [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Pas de huidige tijdlijnwaarden toe op de invoer PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | Haalt of stelt de AFSt-waarde in. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Haalt of stelt de actieve frame-index in. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Haalt frame op op basis van id. |
| [getFrames()](#getFrames--) | Haalt de lijst met frames op. |
| [getFramesList()](#getFramesList--) | Haalt de lijst met frames op. |
| [getFsID()](#getFsID--) | Haalt of stelt de FsID-waarde in. |
| [getLoopesCount()](#getLoopesCount--) | Haalt of stelt het aantal lussen in. |
| [getPsdImage()](#getPsdImage--) | Haalt of stelt de PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) van deze [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van PsdImage en Timeline op naar de opgegeven stream in het opgegeven formaat volgens de opslagopties. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van PsdImage en Timeline op naar de opgegeven bestandslocatie in het opgegeven formaat volgens de opslagopties. |
| [setAFSt(int value)](#setAFSt-int-) | Haalt of stelt de AFSt-waarde in. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Haalt of stelt de actieve frame-index in. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Haalt de lijst met frames op. |
| [setFsID(int value)](#setFsID-int-) | Haalt of stelt de FsID-waarde in. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Haalt of stelt het aantal lussen in. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Haalt of stelt de PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) van deze [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) in. |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Schakelt het actieve frame naar het doelwit. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Pas de huidige tijdlijnwaarden toe op de invoer PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Initialiseert een nieuw exemplaar van de [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) klasse.

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Pas de huidige tijdlijnwaarden toe op de invoer PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | De psd-afbeelding. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


Haalt of stelt de AFSt-waarde in.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Haalt of stelt de actieve frame-index in.

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


Haalt frame op op basis van id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| frameId | int | De frame-id. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Haalt de lijst met frames op.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Haalt de lijst met frames op.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


Haalt of stelt de FsID-waarde in.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Haalt of stelt het aantal lussen in.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Haalt of stelt de PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) van deze [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) in.

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


Slaat de gegevens van PsdImage en Timeline op naar de opgegeven stream in het opgegeven formaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | De uitvoerstroom. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Slaat de gegevens van PsdImage en Timeline op naar de opgegeven bestandslocatie in het opgegeven formaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


Haalt of stelt de AFSt-waarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Haalt of stelt de actieve frame-index in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Haalt de lijst met frames op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


Haalt of stelt de FsID-waarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Haalt of stelt het aantal lussen in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Haalt of stelt de PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) van deze [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Schakelt het actieve frame naar het doelwit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetActiveFrameIndex | int | De doelframe-index. |

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


Pas de huidige tijdlijnwaarden toe op de invoer PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| frameIndex | int | De frame-index om laagtoestanden bij te werken. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

