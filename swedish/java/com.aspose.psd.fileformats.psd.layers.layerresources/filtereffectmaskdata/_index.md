---
title: "FilterEffectMaskData"
second_title: "Aspose.PSD för Java API-referens"
description: "Filtermaskdataklassen."
type: docs
weight: 31
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Inheritance:**
java.lang.Object
```
public final class FilterEffectMaskData
```

Filtermaskdataklassen.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)](#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-) | Initierar en ny instans av klassen [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannels()](#getChannels--) | Hämtar kanalerna. |
| [getClass()](#getClass--) |  |
| [getGUID()](#getGUID--) | Hämtar GUID. |
| [getLength()](#getLength--) | Hämtar filtermaskdataens längd i byte. |
| [getMaskRectangle()](#getMaskRectangle--) | Hämtar arkmaskens rektangel. |
| [getMaxChannels()](#getMaxChannels--) | Hämtar maxantalet kanaler. |
| [getPixelsDepth()](#getPixelsDepth--) | Hämtar pixeldjupet. |
| [getRectangle()](#getRectangle--) | Hämtar kanalernas rektangel. |
| [getSheetMask()](#getSheetMask--) | Hämtar arkmasken. |
| [getUserMask()](#getUserMask--) | Hämtar användarmasken. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveData(StreamContainer streamContainer)](#saveData-com.aspose.psd.StreamContainer-) | Sparar resursen till den angivna strömbehållaren. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask) {#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-}
```
public FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)
```


Initierar en ny instans av klassen [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | java.lang.String | Resursens guid. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Kanalernas rektangel. |
| pixelsDepth | int | Pixeldjupet. |
| maxChannels | int | Det maximala kanalvärdet. |
| channels | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Kanalerna. |
| userMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Användarmasken. |
| maskRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Arkmaskens rektangel. |
| sheetMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Arkmasken. |

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
### getChannels() {#getChannels--}
```
public final ChannelInformation[] getChannels()
```


Hämtar kanalerna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGUID() {#getGUID--}
```
public final String getGUID()
```


Hämtar GUID.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public final long getLength()
```


Hämtar filtermaskdataens längd i byte.

**Returns:**
long
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Hämtar arkmaskens rektangel.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMaxChannels() {#getMaxChannels--}
```
public final int getMaxChannels()
```


Hämtar maxantalet kanaler.

**Returns:**
int
### getPixelsDepth() {#getPixelsDepth--}
```
public final int getPixelsDepth()
```


Hämtar pixeldjupet.

**Returns:**
int
### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Hämtar kanalernas rektangel.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getSheetMask() {#getSheetMask--}
```
public final ChannelInformation getSheetMask()
```


Hämtar arkmasken.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### getUserMask() {#getUserMask--}
```
public final ChannelInformation getUserMask()
```


Hämtar användarmasken.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
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




### saveData(StreamContainer streamContainer) {#saveData-com.aspose.psd.StreamContainer-}
```
public final void saveData(StreamContainer streamContainer)
```


Sparar resursen till den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara till. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

