---
title: "SmartObjectProvider"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert de smart object-provider die het ophalen / instellen van gegevensbronnen uit globale linkbronnen van het PSD-bestand en hun inhoud mogelijk maakt."
type: docs
weight: 17
url: /nl/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Definieert de smart object-provider die het ophalen / instellen van gegevensbronnen uit globale linkbronnen van het PSD-bestand en hun inhoud mogelijk maakt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Converteert lagen naar een ingesloten smart object. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Converteert lagen naar een ingesloten smart object. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Initialiseert een nieuwe instantie van de [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) klasse. |
| [embedAllLinked()](#embedAllLinked--) | Insluit alle gekoppelde smart objects in de afbeelding. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Haalt het type op van de inhoud van de smart object‑laag. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Haalt de ingesloten of gekoppelde bestandsinhoud op. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Haalt de link‑databron op via unieke id. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Laadt de inhoud. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Maakt een nieuwe smart object‑laag aan door de bronlaag te kopiëren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Verwijdert databronnen uit ingesloten en externe resources die niet aanwezig zijn in de opgegeven lijst met geldige GUID's. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Vervangt de databron in de globale resources door de opgegeven inhoud om in te sluiten. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Vervangt de databron in een globale LinkResource‑resource door de nieuw aangemaakte databron uit een extern bestand. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Stelt de ingesloten of externe bestandsinhoud in. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Stelt (vervangt of voegt toe) de link‑databron in de globale linkresource in. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Werkt de inhoud bij van alle gewijzigde smart objects in de afbeelding. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Werkt alle smart object‑lagen binnen de container bij waarvan de  UniqueId  overeenkomt met  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Converteert lagen naar een ingesloten smart object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | De lagen. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Converteert lagen naar een ingesloten smart object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerNumbers | int[] | De laagnummers. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Initialiseert een nieuwe instantie van de [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | De container. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Insluit alle gekoppelde smart objects in de afbeelding.

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


Haalt het type op van de inhoud van de smart object‑laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | De unieke identificatie. |

**Returns:**
int - Het type van de inhoud van de slimme objectlaag.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Haalt de ingesloten of gekoppelde bestandsinhoud op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | De unieke identificatie van de gekoppelde gegevensbron. |

**Returns:**
byte[] - De  byte[]  inhoud.
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Haalt de link‑databron op via unieke id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | De unieke identificatie. |

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


Laadt de inhoud.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | De unieke identificatie. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Maakt een nieuwe smart object‑laag aan door de bronlaag te kopiëren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | De bronlaag. |

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


Verwijdert gegevensbronnen uit ingesloten en externe bronnen die niet aanwezig zijn in de opgegeven lijst met geldige GUID's. Deze methode ruimt verweesde gegevensbronnen op door te vergelijken met de huidige geldige gegevensbronidentifiers.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | De lijst met geldige gegevensbron-GUID's om te behouden. Gegevensbronnen die niet in deze lijst staan, worden verwijderd. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Vervangt de databron in de globale resources door de opgegeven inhoud om in te sluiten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | De unieke identificatie van de bestaande gegevensbron. |
| contents | byte[] | De gegevens voor een nieuwe gegevensbron. |

**Returns:**
com.aspose.ms.System.Guid - De unieke identificatie van de aangemaakte ingesloten gegevensbron.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Vervangt de databron in een globale LinkResource‑resource door de nieuw aangemaakte databron uit een extern bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | De geplaatste bron. |
| linkedPath | java.lang.String | Het absolute pad naar het gekoppelde bestand. |
| isReplaceOnlyThis | boolean | Indien true, verwijder dan geen gegevensbron in globale bronnen. |

**Returns:**
com.aspose.ms.System.Guid - De unieke identificatie Guid van de aangemaakte gekoppelde gegevensbron. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Stelt de ingesloten of externe bestandsinhoud in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | De unieke identificatie van de gekoppelde gegevensbron. |
| gegevens | byte[] | De gegevens. |
| fileType | java.lang.String | Het type gegevensbestand. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Stelt (vervangt of voegt toe) de link‑databron in de globale linkresource in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | De linkgegevensbron. |

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


Werkt de inhoud bij van alle gewijzigde smart objects in de afbeelding.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Werkt alle smart object-lagen binnen de container bij waarvan de  UniqueId  overeenkomt met  oldGuid . De UniqueId van de overeenkomende lagen wordt opnieuw toegewezen aan  newGuid  en hun inhoud wordt vernieuwd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | De unieke identificatie van de oorspronkelijke smart object-gegevensbron die moet worden vervangen. |
| newGuid | com.aspose.ms.System.Guid | De unieke identificatie van de nieuwe smart object-gegevensbron om toe te wijzen. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | De resolutie-instellingen die moeten worden toegepast bij het bijwerken van de inhoud. Als  null , wordt de beeldresolutie gebruikt. |

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

