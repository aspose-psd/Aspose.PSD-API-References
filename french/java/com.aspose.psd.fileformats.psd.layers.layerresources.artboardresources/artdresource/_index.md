---
title: "ArtDResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les données d'information du Artboard pour PsdImage.GlobalLayerResources/."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtDResource extends BaseArtboardInfoResource
```

Les données d'information du Artboard pour PsdImage.GlobalLayerResources ([PsdImage.getGlobalLayerResources](../../com.aspose.psd.fileformats.psd/psdimage\#getGlobalLayerResources)/[PsdImage.setGlobalLayerResources(LayerResource[])](../../com.aspose.psd.fileformats.psd/psdimage\#setGlobalLayerResources-LayerResource---)).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ArtDResource()](#ArtDResource--) | Initialise une nouvelle instance de la classe [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource). |
## Champs

| Champ | Description |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La version d'en-tête PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La signature de ressource spécifique à PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La version d'en-tête PSD |
| [ResourceSignature](#ResourceSignature) | La signature de ressource commune. |
| [TypeToolKey](#TypeToolKey) | La clé d'information de l'outil de type. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licence de l'entreprise. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Vérifie et définit si la ressource est spécifique PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtboardCount_internalized()](#getArtboardCount-internalized--) | Obtient ou définit le nombre d'Art-boards. |
| [getAutoExpandOffset_internalized()](#getAutoExpandOffset-internalized--) | Obtient ou définit le décalage d'expansion automatique. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Obtient ou définit l'identifiant de classe de la ressource. |
| [getClassName_internalized()](#getClassName-internalized--) | Obtient ou définit le nom de classe de la ressource. |
| [getDocDefaultNewArtboardBackgroundColor_internalized()](#getDocDefaultNewArtboardBackgroundColor-internalized--) | Obtient ou définit le DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [getDocDefaultNewArtboardBackgroundType_internalized()](#getDocDefaultNewArtboardBackgroundType-internalized--) | Obtient ou définit le DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType\_internalized-int-)). |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getItems()](#getItems--) | Obtient ou définit les éléments [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLength()](#getLength--) |    |
| [getOriginPoint_internalized()](#getOriginPoint-internalized--) | Obtient ou définit le point d'origine. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getVersion_internalized()](#getVersion-internalized--) | Obtient ou définit la version de la ressource. |
| [hashCode()](#hashCode--) |  |
| [isAutoExpandEnabled_internalized()](#isAutoExpandEnabled-internalized--) | Obtient ou définit le IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [isAutoNestEnabled_internalized()](#isAutoNestEnabled-internalized--) | Obtient ou définit le IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [isAutoPositionEnabled_internalized()](#isAutoPositionEnabled-internalized--) | Obtient ou définit le IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [isShrinkwrapOnSaveEnabled_internalized()](#isShrinkwrapOnSaveEnabled-internalized--) | Obtient ou définit le IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setArtboardCount_internalized(int value)](#setArtboardCount-internalized-int-) | Obtient ou définit le nombre d'Art-boards. |
| [setAutoExpandEnabled_internalized(boolean value)](#setAutoExpandEnabled-internalized-boolean-) | Obtient ou définit le IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [setAutoExpandOffset_internalized(PointF value)](#setAutoExpandOffset-internalized-com.aspose.psd.PointF-) | Obtient ou définit le décalage d'expansion automatique. |
| [setAutoNestEnabled_internalized(boolean value)](#setAutoNestEnabled-internalized-boolean-) | Obtient ou définit le IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [setAutoPositionEnabled_internalized(boolean value)](#setAutoPositionEnabled-internalized-boolean-) | Obtient ou définit le IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtient ou définit l'identifiant de classe de la ressource. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Obtient ou définit le nom de classe de la ressource. |
| [setDocDefaultNewArtboardBackgroundColor_internalized(Color value)](#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-) | Obtient ou définit le DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [setDocDefaultNewArtboardBackgroundType_internalized(int value)](#setDocDefaultNewArtboardBackgroundType-internalized-int-) | Obtient ou définit le DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType\_internalized-int-)). |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtient ou définit les éléments [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [setOriginPoint_internalized(PointF value)](#setOriginPoint-internalized-com.aspose.psd.PointF-) | Obtient ou définit le point d'origine. |
| [setShrinkwrapOnSaveEnabled_internalized(boolean value)](#setShrinkwrapOnSaveEnabled-internalized-boolean-) | Obtient ou définit le IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Obtient ou définit la version de la ressource. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtDResource() {#ArtDResource--}
```
public ArtDResource()
```


Initialise une nouvelle instance de la classe [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource).

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
### getArtboardCount_internalized() {#getArtboardCount-internalized--}
```
public final int getArtboardCount_internalized()
```


Obtient ou définit le nombre d'Art-boards.

**Returns:**
int
### getAutoExpandOffset_internalized() {#getAutoExpandOffset-internalized--}
```
public final PointF getAutoExpandOffset_internalized()
```


Obtient ou définit le décalage d'expansion automatique.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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


Obtient ou définit l'identifiant de classe de la ressource.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Obtient ou définit le nom de classe de la ressource.

**Returns:**
java.lang.String
### getDocDefaultNewArtboardBackgroundColor_internalized() {#getDocDefaultNewArtboardBackgroundColor-internalized--}
```
public final Color getDocDefaultNewArtboardBackgroundColor_internalized()
```


Obtient ou définit le DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Returns:**
[Color](../../com.aspose.psd/color)
### getDocDefaultNewArtboardBackgroundType_internalized() {#getDocDefaultNewArtboardBackgroundType-internalized--}
```
public final int getDocDefaultNewArtboardBackgroundType_internalized()
```


Obtient ou définit le DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType\_internalized-int-)).

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Obtient ou définit les éléments [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
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


  

**Returns:**
int
### getOriginPoint_internalized() {#getOriginPoint-internalized--}
```
public final PointF getOriginPoint_internalized()
```


Obtient ou définit le point d'origine.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


Obtient ou définit la version de la ressource.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoExpandEnabled_internalized() {#isAutoExpandEnabled-internalized--}
```
public final boolean isAutoExpandEnabled_internalized()
```


Obtient ou définit le IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Returns:**
booléen
### isAutoNestEnabled_internalized() {#isAutoNestEnabled-internalized--}
```
public final boolean isAutoNestEnabled_internalized()
```


Obtient ou définit le IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Returns:**
booléen
### isAutoPositionEnabled_internalized() {#isAutoPositionEnabled-internalized--}
```
public final boolean isAutoPositionEnabled_internalized()
```


Obtient ou définit le IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

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
### isShrinkwrapOnSaveEnabled_internalized() {#isShrinkwrapOnSaveEnabled-internalized--}
```
public final boolean isShrinkwrapOnSaveEnabled_internalized()
```


Obtient ou définit le IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Enregistre la ressource dans le conteneur de flux spécifié.

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

### setArtboardCount_internalized(int value) {#setArtboardCount-internalized-int-}
```
public final void setArtboardCount_internalized(int value)
```


Obtient ou définit le nombre d'Art-boards.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setAutoExpandEnabled_internalized(boolean value) {#setAutoExpandEnabled-internalized-boolean-}
```
public final void setAutoExpandEnabled_internalized(boolean value)
```


Obtient ou définit le IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAutoExpandOffset_internalized(PointF value) {#setAutoExpandOffset-internalized-com.aspose.psd.PointF-}
```
public final void setAutoExpandOffset_internalized(PointF value)
```


Obtient ou définit le décalage d'expansion automatique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setAutoNestEnabled_internalized(boolean value) {#setAutoNestEnabled-internalized-boolean-}
```
public final void setAutoNestEnabled_internalized(boolean value)
```


Obtient ou définit le IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAutoPositionEnabled_internalized(boolean value) {#setAutoPositionEnabled-internalized-boolean-}
```
public final void setAutoPositionEnabled_internalized(boolean value)
```


Obtient ou définit le IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Obtient ou définit l'identifiant de classe de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Obtient ou définit le nom de classe de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDocDefaultNewArtboardBackgroundColor_internalized(Color value) {#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-}
```
public final void setDocDefaultNewArtboardBackgroundColor_internalized(Color value)
```


Obtient ou définit le DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDocDefaultNewArtboardBackgroundType_internalized(int value) {#setDocDefaultNewArtboardBackgroundType-internalized-int-}
```
public final void setDocDefaultNewArtboardBackgroundType_internalized(int value)
```


Obtient ou définit le DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType\_internalized-int-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Obtient ou définit les éléments [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setOriginPoint_internalized(PointF value) {#setOriginPoint-internalized-com.aspose.psd.PointF-}
```
public final void setOriginPoint_internalized(PointF value)
```


Obtient ou définit le point d'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setShrinkwrapOnSaveEnabled_internalized(boolean value) {#setShrinkwrapOnSaveEnabled-internalized-boolean-}
```
public final void setShrinkwrapOnSaveEnabled_internalized(boolean value)
```


Obtient ou définit le IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Obtient ou définit la version de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

