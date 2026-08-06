---
title: "SmartObjectProvider"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit le fournisseur d'objet intelligent qui permet d'obtenir / de définir des sources de données à partir des ressources de lien global du fichier PSD et de leur contenu."
type: docs
weight: 17
url: /fr/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Définit le fournisseur d'objet intelligent qui permet d'obtenir / de définir des sources de données à partir des ressources de lien global du fichier PSD et de leur contenu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Convertit les couches en un objet intelligent intégré. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Convertit les couches en un objet intelligent intégré. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Initialise une nouvelle instance de la classe [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Intègre tous les objets intelligents liés dans l'image. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Obtient le type du contenu de la couche d'objet intelligent. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Obtient le contenu du fichier intégré ou lié. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Obtient la source de données du lien par identifiant unique. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Charge le contenu. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Crée une nouvelle couche d'objet intelligent en copiant celle source. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Supprime les sources de données des ressources intégrées et externes qui ne sont pas présentes dans la liste fournie de GUID valides. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Remplace la source de données dans les ressources globales par le contenu fourni à intégrer. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Remplace la source de données dans une ressource globale LinkResource par la nouvelle source de données créée à partir d'un fichier externe. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Définit le contenu du fichier intégré ou externe. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Définit (remplace ou ajoute) la source de données du lien dans la ressource de lien globale. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Met à jour le contenu de tous les objets intelligents modifiés dans l'image. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Met à jour toutes les couches d'objet intelligent dans le conteneur dont le  UniqueId  correspond à  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Convertit les couches en un objet intelligent intégré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Les calques. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Convertit les couches en un objet intelligent intégré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layerNumbers | int[] | Les numéros de couche. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Initialise une nouvelle instance de la classe [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Le conteneur. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Intègre tous les objets intelligents liés dans l'image.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient le type du contenu de la couche d'objet intelligent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identifiant unique. |

**Returns:**
int - Le type du contenu de la couche d'objet intelligent.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Obtient le contenu du fichier intégré ou lié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identifiant unique de la source de données du lien. |

**Returns:**
byte[] - Le  byte[]  contenu.
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Obtient la source de données du lien par identifiant unique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identifiant unique. |

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


Charge le contenu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identifiant unique. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Crée une nouvelle couche d'objet intelligent en copiant celle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | La couche source. |

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


Supprime les sources de données des ressources intégrées et externes qui ne sont pas présentes dans la liste fournie de GUID valides. Cette méthode nettoie les sources de données orphelines en les comparant aux identifiants de sources de données valides actuels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | La liste des GUID de sources de données valides à conserver. Les sources de données qui ne figurent pas dans cette liste seront supprimées. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Remplace la source de données dans les ressources globales par le contenu fourni à intégrer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | L'identifiant unique de la source de données existante. |
| contents | byte[] | Les données d'une nouvelle source de données. |

**Returns:**
com.aspose.ms.System.Guid - L'identifiant unique de la source de données intégrée créée.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Remplace la source de données dans une ressource globale LinkResource par la nouvelle source de données créée à partir d'un fichier externe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La ressource placée. |
| linkedPath | java.lang.String | Le chemin absolu du fichier lié. |
| isReplaceOnlyThis | booléen | Si vrai, alors ne supprimez pas la source de données dans les ressources globales. |

**Returns:**
com.aspose.ms.System.Guid - L'identifiant unique Guid de la source de données liée créée. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Définit le contenu du fichier intégré ou externe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identifiant unique de la source de données du lien. |
| données | byte[] | Les données. |
| fileType | java.lang.String | Le type de fichier de données. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Définit (remplace ou ajoute) la source de données du lien dans la ressource de lien globale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | La source de données du lien. |

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


Met à jour le contenu de tous les objets intelligents modifiés dans l'image.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Met à jour toutes les calques d'objet dynamique dans le conteneur dont le  UniqueId  correspond à  oldGuid . Les calques correspondants voient leur UniqueId réassigné à  newGuid  et leur contenu est rafraîchi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | L'identifiant unique de la source de données d'objet dynamique originale à remplacer. |
| newGuid | com.aspose.ms.System.Guid | L'identifiant unique de la nouvelle source de données d'objet dynamique à assigner. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Les paramètres de résolution à appliquer lors de la mise à jour du contenu. Si null, la résolution de l'image est utilisée. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

