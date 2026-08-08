---
title: "LinkResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar LinkResource‑klassen som innehåller information om länkade eller inbäddade filer i PSD‑formatbilden."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public abstract class LinkResource extends LayerResource
```

Definierar klassen LinkResource som innehåller information om länkade eller inbäddade filer i PSD-formatets bild. Länkresursen kan innehålla flera [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instanser som kan nås via indexerare i alla avledda klasser.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CannotAddTheDataSourceMessage_internalized](#CannotAddTheDataSourceMessage-internalized) | Meddelandet 'cannot add the data source' |
| [DataSourceTypeIsWrongMessage_internalized](#DataSourceTypeIsWrongMessage-internalized) | Meddelandet 'The data source type is wrong' |
| [LengthOSourceLengthField](#LengthOSourceLengthField) | Längden på fältet för datakällans längd. |
| [LengthOfResourceLengthField](#LengthOfResourceLengthField) | Längden på fältet för total resurslängd. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB‑huvudversionen |
| [PsbResourceSignature](#PsbResourceSignature) | Den PSB‑specifika resurs‑signaturen. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD‑huvudversionen. |
| [ResourceSignature](#ResourceSignature) | Den gemensamma resurs‑signaturen. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Venture‑licensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addDataSource_internalized(LinkDataSource dataSource)](#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Lägger till datakällan. |
| [addOrReplaceDataSource_internalized(LinkDataSource dataSource)](#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Lägger till eller ersätter datakällan. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kontrollerar och sätter om resursen är PSB‑specifik. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSourceCount()](#getDataSourceCount--) | Hämtar antalet länkdatakällor som kan nås via indexeraren. |
| [getDataSources_internalized()](#getDataSources-internalized--) | Hämtar arrayen LinkDataSource[] med datakällorna. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLength()](#getLength--) | Hämtar den globala länkresurslängden för PSD i byte. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getType_internalized()](#getType-internalized--) | Hämtar eller anger PSD:s globala länkresurstyp som kan vara någon av följande eller ingen: Den inbäddade länkade filen liFD som motsvarar Lnk2Resource och Lnk3Resource, den externa länkade filen liFE som motsvarar LnkeResource, den länkade filaliasen liFA. |
| [get_Item(int index)](#get-Item-int-) | Hämtar [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) på det angivna indexet. |
| [get_Item(UUID index)](#get-Item-java.util.UUID-) | Hämtar [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) på det angivna indexet som är den unika identifieraren för länkdatakällan. |
| [get_Item_internalized(System.Guid index)](#get-Item-internalized-com.aspose.ms.System.Guid-) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna länkresursinstans är tom. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDataSource_internalized(System.Guid uniqueId)](#removeDataSource-internalized-com.aspose.ms.System.Guid-) | Tar bort länkdatakällan. |
| [replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Ersätter datakällan. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursblockets data. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CannotAddTheDataSourceMessage_internalized {#CannotAddTheDataSourceMessage-internalized}
```
public static final String CannotAddTheDataSourceMessage_internalized
```


Meddelandet 'cannot add the data source'

### DataSourceTypeIsWrongMessage_internalized {#DataSourceTypeIsWrongMessage-internalized}
```
public static final String DataSourceTypeIsWrongMessage_internalized
```


Meddelandet 'The data source type is wrong'

### LengthOSourceLengthField {#LengthOSourceLengthField}
```
public static final int LengthOSourceLengthField
```


Längden på fältet för datakällans längd.

### LengthOfResourceLengthField {#LengthOfResourceLengthField}
```
public static final int LengthOfResourceLengthField
```


Längden på fältet för total resurslängd.

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

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Venture‑licensen.

### addDataSource_internalized(LinkDataSource dataSource) {#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addDataSource_internalized(LinkDataSource dataSource)
```


Lägger till datakällan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Länkdatakällan. |

### addOrReplaceDataSource_internalized(LinkDataSource dataSource) {#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addOrReplaceDataSource_internalized(LinkDataSource dataSource)
```


Lägger till eller ersätter datakällan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Datakällan. |

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
### getDataSourceCount() {#getDataSourceCount--}
```
public final int getDataSourceCount()
```


Hämtar antalet länkdatakällor som kan nås via indexeraren.

Värde: datakällans antal.

**Returns:**
int
### getDataSources_internalized() {#getDataSources-internalized--}
```
public final LinkDataSource[] getDataSources_internalized()
```


Hämtar arrayen LinkDataSource[] med datakällorna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Hämtar eller anger rubriken.

Värde: Headern.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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


Hämtar den globala länkresurslängden för PSD i byte.

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
### getType_internalized() {#getType-internalized--}
```
public final int getType_internalized()
```


Hämtar eller anger PSD:s globala länkresurstyp som kan vara någon av följande eller ingen: Den inbäddade länkade filen liFD som motsvarar Lnk2Resource och Lnk3Resource, den externa länkade filen liFE som motsvarar LnkeResource, den länkade filaliasen liFA.

Värde: PSD-länkresurstypen.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public LinkDataSource get_Item(int index)
```


Hämtar [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det heltaliga indexet. Värde: [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource). |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item(UUID index) {#get-Item-java.util.UUID-}
```
public final LinkDataSource get_Item(UUID index)
```


Hämtar [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) på det angivna indexet som är den unika identifieraren för länkdatakällan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | java.util.UUID | Indexen som unik identifierare för länkdatas källa. Värde: [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource). |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item_internalized(System.Guid index) {#get-Item-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource get_Item_internalized(System.Guid index)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | com.aspose.ms.System.Guid |  |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Hämtar ett värde som indikerar om denna länkresursinstans är tom.

Värde: true om denna länkretsurs är tom; annars false.

**Returns:**
boolean
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




### removeDataSource_internalized(System.Guid uniqueId) {#removeDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final void removeDataSource_internalized(System.Guid uniqueId)
```


Tar bort länkdatakällan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Den unika identifieraren. |

### replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)
```


Ersätter datakällan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Den unika identifieraren. |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Länkdatakällan. |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Sparar resursblockets data.

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

