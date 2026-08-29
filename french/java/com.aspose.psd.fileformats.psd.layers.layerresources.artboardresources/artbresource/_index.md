---
title: "ArtBResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les données d'information de l'Artboard pour Layer.Resources/."
type: docs
weight: 11
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtBResource extends BaseArtboardInfoResource
```

Les données d'information de l'Artboard pour Layer.Resources ([Layer.getResources](../../com.aspose.psd.fileformats.psd.layers/layer\#getResources)/[Layer.setResources(LayerResource[])](../../com.aspose.psd.fileformats.psd.layers/layer\#setResources-LayerResource---)).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ArtBResource()](#ArtBResource--) | Initialise une nouvelle instance de la classe [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource). |
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
| [getArtboardBackgroundType()](#getArtboardBackgroundType--) | Obtient ou définit le ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [getArtboardPresetName_internalized()](#getArtboardPresetName-internalized--) | Obtient ou définit le ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [getArtboardRect_internalized()](#getArtboardRect-internalized--) | Obtient ou définit le ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Obtient ou définit l'identifiant de classe de la ressource. |
| [getClassName_internalized()](#getClassName-internalized--) | Obtient ou définit le nom de classe de la ressource. |
| [getColor()](#getColor--) | Obtient ou définit le Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [getGuideIndeces_internalized()](#getGuideIndeces-internalized--) | Obtient ou définit le GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getItems()](#getItems--) | Obtient ou définit les éléments [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLength()](#getLength--) |    |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getVersion_internalized()](#getVersion-internalized--) | Obtient ou définit la version de la ressource. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setArtboardBackgroundType(int value)](#setArtboardBackgroundType-int-) | Obtient ou définit le ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [setArtboardPresetName_internalized(String value)](#setArtboardPresetName-internalized-java.lang.String-) | Obtient ou définit le ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [setArtboardRect_internalized(RectangleF value)](#setArtboardRect-internalized-com.aspose.psd.RectangleF-) | Obtient ou définit le ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtient ou définit l'identifiant de classe de la ressource. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Obtient ou définit le nom de classe de la ressource. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtient ou définit le Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)](#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Obtient ou définit le GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtient ou définit les éléments [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Obtient ou définit la version de la ressource. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtBResource() {#ArtBResource--}
```
public ArtBResource()
```


Initialise une nouvelle instance de la classe [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource).

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
### getArtboardBackgroundType() {#getArtboardBackgroundType--}
```
public final int getArtboardBackgroundType()
```


Obtient ou définit le ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Returns:**
int
### getArtboardPresetName_internalized() {#getArtboardPresetName-internalized--}
```
public final String getArtboardPresetName_internalized()
```


Obtient ou définit le ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Returns:**
java.lang.String
### getArtboardRect_internalized() {#getArtboardRect-internalized--}
```
public final RectangleF getArtboardRect_internalized()
```


Obtient ou définit le ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

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
### getColor() {#getColor--}
```
public final Color getColor()
```


Obtient ou définit le Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Returns:**
[Color](../../com.aspose.psd/color)
### getGuideIndeces_internalized() {#getGuideIndeces-internalized--}
```
public final System.Collections.Generic.List<OSTypeStructure> getGuideIndeces_internalized()
```


Obtient ou définit le GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure>
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

### setArtboardBackgroundType(int value) {#setArtboardBackgroundType-int-}
```
public final void setArtboardBackgroundType(int value)
```


Obtient ou définit le ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setArtboardPresetName_internalized(String value) {#setArtboardPresetName-internalized-java.lang.String-}
```
public final void setArtboardPresetName_internalized(String value)
```


Obtient ou définit le ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setArtboardRect_internalized(RectangleF value) {#setArtboardRect-internalized-com.aspose.psd.RectangleF-}
```
public final void setArtboardRect_internalized(RectangleF value)
```


Obtient ou définit le ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Obtient ou définit le Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value) {#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public final void setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)
```


Obtient ou définit le GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

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

