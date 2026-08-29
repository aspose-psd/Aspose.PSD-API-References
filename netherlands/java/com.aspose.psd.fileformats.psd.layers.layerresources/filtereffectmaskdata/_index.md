---
title: "FilterEffectMaskData"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De filtermaskergegevensklasse."
type: docs
weight: 31
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Inheritance:**
java.lang.Object
```
public final class FilterEffectMaskData
```

De filtermaskergegevensklasse.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)](#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-) | Initialiseert een nieuw exemplaar van de [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannels()](#getChannels--) | Haalt de kanalen op. |
| [getClass()](#getClass--) |  |
| [getGUID()](#getGUID--) | Haalt de GUID op. |
| [getLength()](#getLength--) | Haalt de lengte van de filtermaskergegevens in bytes op. |
| [getMaskRectangle()](#getMaskRectangle--) | Haalt de rechthoek van het sheet‑masker op. |
| [getMaxChannels()](#getMaxChannels--) | Haalt het maximum van het aantal kanalen op. |
| [getPixelsDepth()](#getPixelsDepth--) | Haalt de diepte van de pixels op. |
| [getRectangle()](#getRectangle--) | Haalt de rechthoek van de kanalen op. |
| [getSheetMask()](#getSheetMask--) | Haalt het sheet‑masker op. |
| [getUserMask()](#getUserMask--) | Haalt het gebruikersmasker op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveData(StreamContainer streamContainer)](#saveData-com.aspose.psd.StreamContainer-) | Slaat de resource op in de opgegeven streamcontainer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask) {#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-}
```
public FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)
```


Initialiseert een nieuw exemplaar van de [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| guid | java.lang.String | De resource‑guid. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek van de kanalen. |
| pixelsDepth | int | De diepte van de pixels. |
| maxChannels | int | De maximale kanaalwaarde. |
| channels | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | De kanalen. |
| userMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Het gebruikersmasker. |
| maskRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek van het bladmasker. |
| sheetMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Het bladmasker. |

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
### getChannels() {#getChannels--}
```
public final ChannelInformation[] getChannels()
```


Haalt de kanalen op.

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


Haalt de GUID op.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public final long getLength()
```


Haalt de lengte van de filtermaskergegevens in bytes op.

**Returns:**
long
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Haalt de rechthoek van het sheet‑masker op.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMaxChannels() {#getMaxChannels--}
```
public final int getMaxChannels()
```


Haalt het maximum van het aantal kanalen op.

**Returns:**
int
### getPixelsDepth() {#getPixelsDepth--}
```
public final int getPixelsDepth()
```


Haalt de diepte van de pixels op.

**Returns:**
int
### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Haalt de rechthoek van de kanalen op.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getSheetMask() {#getSheetMask--}
```
public final ChannelInformation getSheetMask()
```


Haalt het sheet‑masker op.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### getUserMask() {#getUserMask--}
```
public final ChannelInformation getUserMask()
```


Haalt het gebruikersmasker op.

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


Slaat de resource op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om naar op te slaan. |

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

