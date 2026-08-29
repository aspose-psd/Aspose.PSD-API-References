---
title: "ArtBResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Artboard‑informationsdata för Layer.Resources/."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtBResource extends BaseArtboardInfoResource
```

Artboard‑informationsdata för Layer.Resources ([Layer.getResources](../../com.aspose.psd.fileformats.psd.layers/layer\#getResources)/[Layer.setResources(LayerResource[])](../../com.aspose.psd.fileformats.psd.layers/layer\#setResources-LayerResource---)).
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ArtBResource()](#ArtBResource--) | Initierar en ny instans av klassen [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB‑huvudversionen |
| [PsbResourceSignature](#PsbResourceSignature) | Den PSB‑specifika resurs‑signaturen. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD‑huvudversionen. |
| [ResourceSignature](#ResourceSignature) | Den gemensamma resurs‑signaturen. |
| [TypeToolKey](#TypeToolKey) | Nyckeln för typverktygsinformation. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Venture‑licensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kontrollerar och sätter om resursen är PSB‑specifik. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtboardBackgroundType()](#getArtboardBackgroundType--) | Hämtar eller anger ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [getArtboardPresetName_internalized()](#getArtboardPresetName-internalized--) | Hämtar eller anger ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [getArtboardRect_internalized()](#getArtboardRect-internalized--) | Hämtar eller anger ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Hämtar eller anger resursklassens id. |
| [getClassName_internalized()](#getClassName-internalized--) | Hämtar eller anger resursklassens namn. |
| [getColor()](#getColor--) | Hämtar eller anger Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [getGuideIndeces_internalized()](#getGuideIndeces-internalized--) | Hämtar eller anger GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getItems()](#getItems--) | Hämtar eller anger [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)‑objekten. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLength()](#getLength--) |    |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getVersion_internalized()](#getVersion-internalized--) | Hämtar eller anger resursversionen. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setArtboardBackgroundType(int value)](#setArtboardBackgroundType-int-) | Hämtar eller anger ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [setArtboardPresetName_internalized(String value)](#setArtboardPresetName-internalized-java.lang.String-) | Hämtar eller anger ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [setArtboardRect_internalized(RectangleF value)](#setArtboardRect-internalized-com.aspose.psd.RectangleF-) | Hämtar eller anger ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Hämtar eller anger resursklassens id. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Hämtar eller anger resursklassens namn. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Hämtar eller anger Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)](#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Hämtar eller anger GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)‑objekten. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Hämtar eller anger resursversionen. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtBResource() {#ArtBResource--}
```
public ArtBResource()
```


Initierar en ny instans av klassen [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB‑huvudversionen

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Den PSB‑specifika resurs‑signaturen.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD‑huvudversionen.

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Den gemensamma resurs‑signaturen.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Nyckeln för typverktygsinformation.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Venture‑licensen.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kontrollerar och anger om resursen är PSB-specifik. Vissa resurser känns inte igen för närvarande, men vi har en fullständig lista över PSB-specifika resurser som ändrar deras beteende vid sparning. Så vi måste åtminstone kontrollera detta i UnknownResource.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Nyckeln. |

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
### getArtboardBackgroundType() {#getArtboardBackgroundType--}
```
public final int getArtboardBackgroundType()
```


Hämtar eller anger ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Returns:**
int
### getArtboardPresetName_internalized() {#getArtboardPresetName-internalized--}
```
public final String getArtboardPresetName_internalized()
```


Hämtar eller anger ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Returns:**
java.lang.String
### getArtboardRect_internalized() {#getArtboardRect-internalized--}
```
public final RectangleF getArtboardRect_internalized()
```


Hämtar eller anger ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Hämtar eller anger resursklassens id.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Hämtar eller anger resursklassens namn.

**Returns:**
java.lang.String
### getColor() {#getColor--}
```
public final Color getColor()
```


Hämtar eller anger Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Returns:**
[Color](../../com.aspose.psd/color)
### getGuideIndeces_internalized() {#getGuideIndeces-internalized--}
```
public final System.Collections.Generic.List<OSTypeStructure> getGuideIndeces_internalized()
```


Hämtar eller anger GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure>
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Hämtar eller anger rubriken.

Värde: Headern.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Hämtar eller anger [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)‑objekten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Hämtar lagrets resursnyckel.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


  

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Hämtar prefixlängden. Standardvärdet är 12 för 8BIM-resurser och 16 för 8B64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdVersion | int | PSD-versionen. |

**Returns:**
int - Prefixlängden.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Hämtar den minsta psd-version som krävs för lagerresursen. 0 indikerar inga begränsningar.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


Hämtar eller anger resursversionen.

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


Bestämmer om resursen är PSB‑specifik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Resursnyckeln. |

**Returns:**
boolean - true om resursen är PSB-specifik; annars false.
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs.

Värde: true om detta objekt är PSB-specifik resurs; annars false.

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


Sparar resursen till den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psdVersion | int | PSD-versionen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Sparar den anpassade resursrubriken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Sparar rubrikens signatur, identifierare och längd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |
| isLengthLong | boolean | Om satt till true är längden lång. |

### setArtboardBackgroundType(int value) {#setArtboardBackgroundType-int-}
```
public final void setArtboardBackgroundType(int value)
```


Hämtar eller anger ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setArtboardPresetName_internalized(String value) {#setArtboardPresetName-internalized-java.lang.String-}
```
public final void setArtboardPresetName_internalized(String value)
```


Hämtar eller anger ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setArtboardRect_internalized(RectangleF value) {#setArtboardRect-internalized-com.aspose.psd.RectangleF-}
```
public final void setArtboardRect_internalized(RectangleF value)
```


Hämtar eller anger ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Hämtar eller anger resursklassens id.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Hämtar eller anger resursklassens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Hämtar eller anger Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value) {#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public final void setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)
```


Hämtar eller anger GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Hämtar eller anger rubriken.

Värde: Headern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Hämtar eller anger [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)‑objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Hämtar eller anger resursversionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En String som representerar detta objekt.
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

