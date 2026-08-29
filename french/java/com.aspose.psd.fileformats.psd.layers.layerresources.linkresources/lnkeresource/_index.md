---
title: "LnkeResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe LnkeResource qui contient des informations sur les fichiers liés externes ou les actifs dans l'image au format PSD."
type: docs
weight: 17
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkresource)
```
public class LnkeResource extends LinkResource
```

Définit la classe LnkeResource qui contient des informations sur les fichiers ou actifs liés externes dans l'image au format PSD. La ressource de lien peut contenir plusieurs instances de [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) qui peuvent être accessibles via l'indexeur. Ceci fait partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop® programmatiquement
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LnkeResource()](#LnkeResource--) | Initialise une nouvelle instance de la classe [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) class. |
| [LnkeResource(LinkDataSource[] dataSources)](#LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource---) | Initialise une nouvelle instance de la classe [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) class. |
## Champs

| Champ | Description |
| --- | --- |
| [CannotAddTheDataSourceMessage_internalized](#CannotAddTheDataSourceMessage-internalized) | Le message « cannot add the data source » |
| [DataSourceTypeIsWrongMessage_internalized](#DataSourceTypeIsWrongMessage-internalized) | Le message « The data source type is wrong » |
| [LengthOSourceLengthField](#LengthOSourceLengthField) | La longueur du champ de longueur de la source de données. |
| [LengthOfResourceLengthField](#LengthOfResourceLengthField) | La longueur du champ de longueur totale de la ressource. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La version d'en-tête PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La signature de ressource spécifique à PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La version d'en-tête PSD |
| [ResourceSignature](#ResourceSignature) | La signature de ressource commune. |
| [TypeToolKey](#TypeToolKey) | La clé d'information de l'outil de type. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licence de l'entreprise. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addDataSource_internalized(LinkDataSource dataSource)](#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Ajoute la source de données. |
| [addOrReplaceDataSource_internalized(LinkDataSource dataSource)](#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Ajoute ou remplace la source de données. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Vérifie et définit si la ressource est spécifique PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSourceCount()](#getDataSourceCount--) | Obtient le nombre de sources de données de lien qui peuvent être accessibles via l'indexeur. |
| [getDataSources_internalized()](#getDataSources-internalized--) | Obtient le tableau LinkDataSource[] des sources de données. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLength()](#getLength--) | Obtient la longueur en octets de la ressource de lien globale PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getType_internalized()](#getType-internalized--) | Obtient ou définit le type de ressource de lien globale PSD qui peut être l'un des suivants ou aucun : le fichier lié intégré liFD qui correspond aux ressources Lnk2Resource et Lnk3Resource, le fichier lié externe liFE qui correspond à la ressource LnkeResource, l'alias de fichier lié liFA. |
| [get_Item(int index)](#get-Item-int-) | Obtient le [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) à l'index spécifié. |
| [get_Item(UUID index)](#get-Item-java.util.UUID-) | Obtient le [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) à l'index spécifié, qui est l'identifiant unique de la source de données de lien. |
| [get_Item_internalized(System.Guid index)](#get-Item-internalized-com.aspose.ms.System.Guid-) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si cette instance de ressource de lien est vide. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDataSource_internalized(System.Guid uniqueId)](#removeDataSource-internalized-com.aspose.ms.System.Guid-) | Supprime la source de données de lien. |
| [replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Remplace la source de données. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre les données du bloc de ressource. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LnkeResource() {#LnkeResource--}
```
public LnkeResource()
```


Initialise une nouvelle instance de la classe [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) class.

### LnkeResource(LinkDataSource[] dataSources) {#LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource---}
```
public LnkeResource(LinkDataSource[] dataSources)
```


Initialise une nouvelle instance de la classe [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) class.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataSources | [LinkDataSource\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Les sources de données. |

### CannotAddTheDataSourceMessage_internalized {#CannotAddTheDataSourceMessage-internalized}
```
public static final String CannotAddTheDataSourceMessage_internalized
```


Le message « cannot add the data source »

### DataSourceTypeIsWrongMessage_internalized {#DataSourceTypeIsWrongMessage-internalized}
```
public static final String DataSourceTypeIsWrongMessage_internalized
```


Le message « The data source type is wrong »

### LengthOSourceLengthField {#LengthOSourceLengthField}
```
public static final int LengthOSourceLengthField
```


La longueur du champ de longueur de la source de données.

### LengthOfResourceLengthField {#LengthOfResourceLengthField}
```
public static final int LengthOfResourceLengthField
```


La longueur du champ de longueur totale de la ressource.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


La version d'en-tête PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


La signature de ressource spécifique à PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


La version d'en-tête PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


La signature de ressource commune.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


La clé d'information de l'outil de type.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


La licence de l'entreprise.

### addDataSource_internalized(LinkDataSource dataSource) {#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addDataSource_internalized(LinkDataSource dataSource)
```


Ajoute la source de données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | La source de données du lien. |

### addOrReplaceDataSource_internalized(LinkDataSource dataSource) {#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addOrReplaceDataSource_internalized(LinkDataSource dataSource)
```


Ajoute ou remplace la source de données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | La source de données. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Vérifie et définit si la ressource est spécifique PSB. Certaines ressources ne sont pas reconnues pour le moment, mais nous disposons d'une liste complète des ressources spécifiques PSB qui modifient leur comportement lors de l'enregistrement. Nous devons donc vérifier cela dans UnknownResource au moins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | int | La clé. |

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
### getDataSourceCount() {#getDataSourceCount--}
```
public final int getDataSourceCount()
```


Obtient le nombre de sources de données de lien qui peuvent être accessibles via l'indexeur.

Valeur : le nombre de sources de données.

**Returns:**
int
### getDataSources_internalized() {#getDataSources-internalized--}
```
public final LinkDataSource[] getDataSources_internalized()
```


Obtient le tableau LinkDataSource[] des sources de données.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Obtient la clé de la ressource de calque.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Obtient la longueur en octets de la ressource de lien globale PSD.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Obtient la longueur du préfixe. La valeur par défaut est 12 pour les ressources 8BIM et 16 pour les 8B64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| psdVersion | int | La version PSD. |

**Returns:**
int - La longueur du préfixe.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Obtient la version minimale de PSD requise pour la ressource de calque. 0 indique aucune restriction.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient la signature de la ressource de calque.

**Returns:**
int
### getType_internalized() {#getType-internalized--}
```
public final int getType_internalized()
```


Obtient ou définit le type de ressource de lien globale PSD qui peut être l'un des suivants ou aucun : le fichier lié intégré liFD qui correspond aux ressources Lnk2Resource et Lnk3Resource, le fichier lié externe liFE qui correspond à la ressource LnkeResource, l'alias de fichier lié liFA.

Valeur : le type de ressource de lien PSD.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final LiFeDataSource get_Item(int index)
```


Obtient le [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. Valeur : Le [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) - The [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) instance.
### get_Item(UUID index) {#get-Item-java.util.UUID-}
```
public final LinkDataSource get_Item(UUID index)
```


Obtient le [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) à l'index spécifié, qui est l'identifiant unique de la source de données de lien.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | java.util.UUID | L'index en tant qu'identifiant unique de source de données de lien. Valeur : Le [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource). |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item_internalized(System.Guid index) {#get-Item-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource get_Item_internalized(System.Guid index)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient une valeur indiquant si cette instance de ressource de lien est vide.

Valeur :  true  si cette ressource de lien est vide ; sinon,  false .

**Returns:**
booléen
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Détermine si la ressource est spécifique PSB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | int | La clé de la ressource. |

**Returns:**
boolean -  true  si la ressource est spécifique PSB ; sinon,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Obtient une valeur indiquant si cette instance est une ressource spécifique PSB.

Valeur :  true  si cette instance est une ressource spécifique PSB ; sinon,  false .

**Returns:**
booléen
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


Supprime la source de données de lien.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identifiant unique. |

### replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)
```


Remplace la source de données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | L'identifiant unique. |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | La source de données du lien. |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Enregistre les données du bloc de ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux où enregistrer. |
| psdVersion | int | La version PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Enregistre l'en-tête de ressource personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |
| signature | int | La signature. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Enregistre la signature, l'identifiant et la longueur de l'en-tête.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |
| signature | int | La signature. |
| isLengthLong | booléen | si réglé sur  true  la longueur est longue. |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente cette instance.

**Returns:**
java.lang.String - Une chaîne qui représente cette instance.
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

