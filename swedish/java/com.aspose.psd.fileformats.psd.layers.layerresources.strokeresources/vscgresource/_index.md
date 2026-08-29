---
title: "VscgResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Vektorstrecks‑innehållsdatat resurs."
type: docs
weight: 13
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VscgResource extends LayerResource
```

Vektorstrecks‑innehållsdatat resurs.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [VscgResource()](#VscgResource--) | Initierar en ny instans av klassen [VscgResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource). |
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
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Hämtar eller anger klassnamnet. |
| [getClassName_internalized()](#getClassName-internalized--) | Hämtar eller anger klassidentifieraren. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getItems()](#getItems--) | Hämtar eller anger strukturelementen. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getKeyForData()](#getKeyForData--) | Heltalsnyckel som definierar vilken typ av fyllningsinställningar som lagras i resursen: * Color - 0x536f436f - SoCoResource.TypeToolKey * Gradient - 0x4764466c - GdFlResource.TypeToolKey * Pattern - 0x5074466c - PtFlResource.TypeToolKey |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Hämtar eller anger klassnamnet. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Hämtar eller anger klassidentifieraren. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger strukturelementen. |
| [setKeyForData_Rename_Namesake_internalized(int value)](#setKeyForData-Rename-Namesake-internalized-int-) | Hämtar heltalsnyckel som definierar vilken typ av fyllningsinställningar som lagras i resursen: \* Color - 0x536f436f - SoCoResource.TypeToolKey \* Gradient - 0x4764466c - GdFlResource.TypeToolKey \* Pattern - 0x5074466c - PtFlResource.TypeToolKey Varning! Värdet på egenskapen KeyForData ska matcha typen av fyllningsinställningar som lagras i Items‑strukturer. |
| [setKeyForData_internalized(int value)](#setKeyForData-internalized-int-) | Intern metod som tillåter att tilldela den skrivskyddade egenskapen KeyForData. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VscgResource() {#VscgResource--}
```
public VscgResource()
```


Initierar en ny instans av klassen [VscgResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource).

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


Hämtar eller anger klassnamnet.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Hämtar eller anger klassidentifieraren.

**Returns:**
java.lang.String
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


Hämtar eller anger strukturelementen.

Värde: Strukturelementen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Hämtar lagrets resursnyckel.

**Returns:**
int
### getKeyForData() {#getKeyForData--}
```
public final int getKeyForData()
```


Heltalsnyckel som definierar vilken typ av fyllningsinställningar som lagras i resursen: * Color - 0x536f436f - SoCoResource.TypeToolKey * Gradient - 0x4764466c - GdFlResource.TypeToolKey * Pattern - 0x5074466c - PtFlResource.TypeToolKey

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Hämtar lagrets resurslängd i byte.

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Hämtar eller anger klassnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Hämtar eller anger klassidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Hämtar eller anger strukturelementen.

Värde: Strukturelementen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setKeyForData_Rename_Namesake_internalized(int value) {#setKeyForData-Rename-Namesake-internalized-int-}
```
public final void setKeyForData_Rename_Namesake_internalized(int value)
```


Hämtar heltalsnyckel som definierar vilken typ av fyllningsinställningar som lagras i resursen: \* Color - 0x536f436f - SoCoResource.TypeToolKey \* Gradient - 0x4764466c - GdFlResource.TypeToolKey \* Pattern - 0x5074466c - PtFlResource.TypeToolKey Varning! Värdet på egenskapen KeyForData ska matcha typen av fyllningsinställningar som lagras i Items‑strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setKeyForData_internalized(int value) {#setKeyForData-internalized-int-}
```
public final void setKeyForData_internalized(int value)
```


Intern metod som tillåter att tilldela den skrivskyddade egenskapen KeyForData. Bör endast användas i Vscg‑resursladdaren när resursegenskaper tilldelas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Heltalsvärde för egenskapen KeyForData. |

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

