---
title: "SmartObjectProvider"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar smartobjektleverantören som möjliggör hämtning/inställning av datakällor från globala länkre resurser i PSD-filen och deras innehåll."
type: docs
weight: 17
url: /sv/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Definierar smartobjektleverantören som möjliggör hämtning/inställning av datakällor från globala länkre resurser i PSD-filen och deras innehåll.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Konverterar lager till ett inbäddat smart objekt. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Konverterar lager till ett inbäddat smart objekt. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Initierar en ny instans av klassen [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Bäddar in alla länkade smarta objekt i bilden. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Hämtar typen av smartobjektlagrets innehåll. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Hämtar de inbäddade eller länkade filinnehållen. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Hämtar länkdatakällan via unikt id. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Laddar innehållet. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Skapar ett nytt smartobjektlager genom att kopiera källan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Tar bort datakällor från inbäddade och externa resurser som inte finns i den tillhandahållna listan med giltiga GUID:er. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Ersätter datakällan i de globala resurserna med det tillhandahållna innehållet för inbäddning. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Ersätter datakällan i en global LinkResource-resurs med den nyss skapade datakällan från en extern fil. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Ställer in de inbäddade eller externa filinnehållen. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Ställer in (ersätter eller lägger till) länkdatakällan i den globala länkresursen. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Uppdaterar innehållet i alla modifierade smarta objekt i bilden. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Uppdaterar alla smartobjektlager i containern vars  UniqueId  matchar  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Konverterar lager till ett inbäddat smart objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagren. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Konverterar lager till ett inbäddat smart objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerNumbers | int[] | Lagernumren. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Initierar en ny instans av klassen [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Behållaren. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Bäddar in alla länkade smarta objekt i bilden.

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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


Hämtar typen av smartobjektlagrets innehåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Den unika identifieraren. |

**Returns:**
int - Typen av smartobjektlagrets innehåll.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Hämtar de inbäddade eller länkade filinnehållen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Den unika identifieraren för länkdatakällan. |

**Returns:**
byte[] -  byte[]  innehållet.
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Hämtar länkdatakällan via unikt id.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Den unika identifieraren. |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


Laddar innehållet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Den unika identifieraren. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Skapar ett nytt smartobjektlager genom att kopiera källan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Källagret. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


Tar bort datakällor från inbäddade och externa resurser som inte finns i den angivna listan med giltiga GUID:er. Denna metod rensar bort föräldralösa datakällor genom att jämföra mot de aktuella giltiga datakällsidentifierarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | Listan med giltiga datakällas GUID:er att behålla. Datakällor som inte finns i denna lista kommer att tas bort. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Ersätter datakällan i de globala resurserna med det tillhandahållna innehållet för inbäddning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | Den unika identifieraren för den befintliga datakällan. |
| contents | byte[] | Data för en ny datakälla. |

**Returns:**
com.aspose.ms.System.Guid - Den unika identifieraren för den skapade inbäddade datakällan.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Ersätter datakällan i en global LinkResource-resurs med den nyss skapade datakällan från en extern fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Den placerade resursen. |
| linkedPath | java.lang.String | Den absoluta sökvägen till den länkade filen. |
| isReplaceOnlyThis | boolean | Om true, ta då inte bort datakällan i globala resurser. |

**Returns:**
com.aspose.ms.System.Guid - Den unika identifieraren Guid för den skapade länkade datakällan. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Ställer in de inbäddade eller externa filinnehållen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Den unika identifieraren för länkdatakällan. |
| data | byte[] | Data. |
| fileType | java.lang.String | Filtyp för data. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Ställer in (ersätter eller lägger till) länkdatakällan i den globala länkresursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Länkdatakällan. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


Uppdaterar innehållet i alla modifierade smarta objekt i bilden.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Uppdaterar alla smartobjektlager i behållaren vars  UniqueId  matchar  oldGuid . De matchande lagrens UniqueId tilldelas om till  newGuid  och deras innehåll uppdateras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | Den unika identifieraren för den ursprungliga smarta objektets datakälla som ska ersättas. |
| newGuid | com.aspose.ms.System.Guid | Den unika identifieraren för den nya smarta objektets datakälla att tilldela. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Upplösningsinställningarna som ska tillämpas när innehållet uppdateras. Om null används bildens upplösning. |

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

