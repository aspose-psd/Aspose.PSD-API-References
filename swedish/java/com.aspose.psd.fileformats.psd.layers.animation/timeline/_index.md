---
title: "Tidslinje"
second_title: "Aspose.PSD för Java API-referens"
description: "Modellen för tidslinjealternativ."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

Modellen för tidslinjealternativ.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Timeline()](#Timeline--) | Initierar en ny instans av klassen [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Applicera aktuella tidslinjevärden på inmatnings‑PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | Hämtar eller anger AFSt‑värdet. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Hämtar eller anger det aktiva ram‑indexet. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Hämtar ram efter ID. |
| [getFrames()](#getFrames--) | Hämtar listan över ramar. |
| [getFramesList()](#getFramesList--) | Hämtar listan över ramar. |
| [getFsID()](#getFsID--) | Hämtar eller anger FsID‑värdet. |
| [getLoopesCount()](#getLoopesCount--) | Hämtar eller anger antalet slingor. |
| [getPsdImage()](#getPsdImage--) | Hämtar eller anger PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) för denna [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | Sparar PsdImage‑data och Timeline‑data till den angivna strömmen i det angivna formatet enligt sparalternativ. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Sparar PsdImage‑data och Timeline‑data till den angivna filplatsen i det angivna formatet enligt sparalternativ. |
| [setAFSt(int value)](#setAFSt-int-) | Hämtar eller anger AFSt‑värdet. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Hämtar eller anger det aktiva ram‑indexet. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Hämtar listan över ramar. |
| [setFsID(int value)](#setFsID-int-) | Hämtar eller anger FsID‑värdet. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Hämtar eller anger antalet slingor. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Hämtar eller anger PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) för denna [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Byter den aktiva ramen till den önskade. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Applicera aktuella tidslinjevärden på inmatnings‑PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Initierar en ny instans av klassen [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Applicera aktuella tidslinjevärden på inmatnings‑PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Den psd‑bilden. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


Hämtar eller anger AFSt‑värdet.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Hämtar eller anger det aktiva ram‑indexet.

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


Hämtar ram efter ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frameId | int | Ram‑id. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Hämtar listan över ramar.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Hämtar listan över ramar.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


Hämtar eller anger FsID‑värdet.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Hämtar eller anger antalet slingor.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Hämtar eller anger PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) för denna [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

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


Sparar PsdImage‑data och Timeline‑data till den angivna strömmen i det angivna formatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | Utdata‑strömmen. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Sparar PsdImage‑data och Timeline‑data till den angivna filplatsen i det angivna formatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


Hämtar eller anger AFSt‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Hämtar eller anger det aktiva ram‑indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Hämtar listan över ramar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


Hämtar eller anger FsID‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Hämtar eller anger antalet slingor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Hämtar eller anger PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) för denna [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Byter den aktiva ramen till den önskade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetActiveFrameIndex | int | Målrams‑index. |

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


Applicera aktuella tidslinjevärden på inmatnings‑PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frameIndex | int | Ram‑index för att uppdatera lager‑tillstånd. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

