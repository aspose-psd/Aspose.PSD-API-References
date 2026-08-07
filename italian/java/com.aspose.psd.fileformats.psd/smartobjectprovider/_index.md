---
title: "SmartObjectProvider"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce il provider di oggetti intelligenti che consente di ottenere / impostare le fonti dati dalle risorse di collegamento globali del file PSD e i loro contenuti."
type: docs
weight: 17
url: /it/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Definisce il provider di oggetti intelligenti che consente di ottenere / impostare le fonti dati dalle risorse di collegamento globali del file PSD e i loro contenuti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Converte i livelli in un oggetto smart incorporato. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Converte i livelli in un oggetto smart incorporato. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Inizializza una nuova istanza della classe [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Incorpora tutti gli oggetti smart collegati nell'immagine. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Ottiene il tipo del contenuto del livello dell'oggetto smart. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Ottiene i contenuti del file incorporato o collegato. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Ottiene la sorgente dati del collegamento per ID univoco. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Carica i contenuti. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Crea un nuovo livello di oggetto smart copiando quello di origine. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Rimuove le sorgenti dati dalle risorse incorporate ed esterne che non sono presenti nell'elenco fornito di GUID validi. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Sostituisce la sorgente dati nelle risorse globali con i contenuti forniti da incorporare. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Sostituisce la sorgente dati in una risorsa globale LinkResource con la nuova sorgente dati creata dal file esterno. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Imposta i contenuti del file incorporato o esterno. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Imposta (sostituisce o aggiunge) la sorgente dati del collegamento nella risorsa di collegamento globale. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Aggiorna il contenuto di tutti gli oggetti smart modificati nell'immagine. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Aggiorna tutti i livelli di oggetti smart nel contenitore il cui  UniqueId  corrisponde a  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Converte i livelli in un oggetto smart incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | I livelli. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Converte i livelli in un oggetto smart incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerNumbers | int[] | I numeri del livello. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Inizializza una nuova istanza della classe [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Il contenitore. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Incorpora tutti gli oggetti smart collegati nell'immagine.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene il tipo del contenuto del livello dell'oggetto smart.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identificatore unico. |

**Returns:**
int - Il tipo del contenuto del livello dell'oggetto intelligente.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Ottiene i contenuti del file incorporato o collegato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identificatore univoco della fonte dati collegata. |

**Returns:**
byte[] - I contenuti byte[].
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Ottiene la sorgente dati del collegamento per ID univoco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identificatore unico. |

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


Carica i contenuti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identificatore unico. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Crea un nuovo livello di oggetto smart copiando quello di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Il livello di origine. |

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


Rimuove le fonti dati da risorse incorporate ed esterne che non sono presenti nell'elenco fornito di GUID validi. Questo metodo pulisce le fonti dati orfane confrontandole con gli attuali identificatori di fonti dati validi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | L'elenco dei GUID delle fonti dati valide da conservare. Le fonti dati non presenti in questo elenco saranno rimosse. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Sostituisce la sorgente dati nelle risorse globali con i contenuti forniti da incorporare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | L'identificatore univoco della fonte dati esistente. |
| contents | byte[] | I dati per una nuova fonte dati. |

**Returns:**
com.aspose.ms.System.Guid - L'identificatore univoco della fonte dati incorporata creata.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Sostituisce la sorgente dati in una risorsa globale LinkResource con la nuova sorgente dati creata dal file esterno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La risorsa posizionata. |
| linkedPath | java.lang.String | Il percorso assoluto del file collegato. |
| isReplaceOnlyThis | boolean | Se vero, non rimuovere la fonte dati nelle risorse globali. |

**Returns:**
com.aspose.ms.System.Guid - L'identificatore univoco Guid della fonte dati collegata creata. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Imposta i contenuti del file incorporato o esterno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identificatore univoco della fonte dati collegata. |
| dati | byte[] | I dati. |
| fileType | java.lang.String | Il tipo di file dei dati. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Imposta (sostituisce o aggiunge) la sorgente dati del collegamento nella risorsa di collegamento globale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | La sorgente dati del collegamento. |

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


Aggiorna il contenuto di tutti gli oggetti smart modificati nell'immagine.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Aggiorna tutti i livelli di oggetto intelligente all'interno del contenitore il cui  UniqueId  corrisponde a  oldGuid . Gli UniqueId dei livelli corrispondenti vengono riassegnati a  newGuid  e il loro contenuto viene aggiornato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | L'identificatore univoco della sorgente dati dell'oggetto intelligente originale da sostituire. |
| newGuid | com.aspose.ms.System.Guid | L'identificatore univoco della nuova sorgente dati dell'oggetto intelligente da assegnare. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Le impostazioni di risoluzione da applicare durante l'aggiornamento del contenuto. Se  null , viene utilizzata la risoluzione dell'immagine. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

