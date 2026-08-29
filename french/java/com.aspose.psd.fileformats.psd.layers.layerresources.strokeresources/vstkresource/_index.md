---
title: "VstkResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe de ressource VstkResource."
type: docs
weight: 14
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

Classe de ressource VstkResource. Contient des informations sur les données de contour vectoriel. La ressource doit être initialisée soit par la méthode AssignItems à partir de resourcedata, soit en affectant des valeurs aux propriétés de la classe.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VstkResource()](#VstkResource--) | Initialise une nouvelle instance de la classe [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource). |
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
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Assigne les structures d'éléments à partir de la ressource Vstk. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Vérifie et définit si la ressource est spécifique PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Obtient ou définit l'instance ClassID. |
| [getClassName_internalized()](#getClassName-internalized--) | Obtient ou définit le nom de la classe. |
| [getFillEnabled()](#getFillEnabled--) | Obtient ou définit une valeur indiquant si le remplissage de contour est activé. |
| [getFillSettings()](#getFillSettings--) | Obtient ou définit les paramètres de remplissage du Stroke. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLength()](#getLength--) | Obtient la longueur de la ressource de calque en octets. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getStrokeEnabled()](#getStrokeEnabled--) | Obtient ou définit une valeur indiquant si l'effet de contour est activé. |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | Obtient ou définit le mode de fusion du contour. |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | Obtient ou définit l'entité du contour. |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | Obtient ou définit l'alignement de ligne du style Stroke. |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | Obtient ou définit le type de terminaison de ligne du style de contour. |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | Obtient ou définit la largeur de la terminaison de ligne du contour. |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | Obtient ou définit le stroke style line dash offset. |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | Obtient ou définit le tableau de tirets de ligne. |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | Obtient ou définit le Stroke style line join type. |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | Obtient ou définit le Stroke line width. |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | Obtient ou définit la stroke style miter limit. |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | Obtient ou définit la Stroke style opacity (0-100%). |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | Obtient ou définit la Stroke style resolution. |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | Obtient ou définit le Stroke style scale lock. |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | Obtient ou définit le Stroke adjust. |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | Obtient ou définit la stroke style version. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtient ou définit l'instance ClassID. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Obtient ou définit le nom de la classe. |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | Obtient ou définit une valeur indiquant si le remplissage de contour est activé. |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Obtient ou définit les paramètres de remplissage du Stroke. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | Obtient ou définit une valeur indiquant si l'effet de contour est activé. |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | Obtient ou définit le mode de fusion du contour. |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | Obtient ou définit l'entité du contour. |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | Obtient ou définit l'alignement de ligne du style Stroke. |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | Obtient ou définit le type de terminaison de ligne du style de contour. |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | Obtient ou définit la largeur de la terminaison de ligne du contour. |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | Obtient ou définit le stroke style line dash offset. |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | Obtient ou définit le tableau de tirets de ligne. |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | Obtient ou définit le Stroke style line join type. |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | Obtient ou définit le Stroke line width. |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | Obtient ou définit la stroke style miter limit. |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | Obtient ou définit la Stroke stryle opacity (0-100%). |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | Obtient ou définit la Stroke style resolution. |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | Obtient ou définit le Stroke style scale lock. |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | Obtient ou définit le Stroke adjust. |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | Obtient ou définit la stroke style version. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


Initialise une nouvelle instance de la classe [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource).

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

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


Assigne les structures d'éléments à partir de la ressource Vstk.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Liste des instances OSTypeStructure. |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Obtient ou définit l'instance ClassID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Obtient ou définit le nom de la classe.

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


Obtient ou définit une valeur indiquant si le remplissage de contour est activé.

**Returns:**
booléen
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Obtient ou définit les paramètres de remplissage du Stroke.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
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


Obtient la longueur de la ressource de calque en octets.

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
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


Obtient ou définit une valeur indiquant si l'effet de contour est activé.

**Returns:**
booléen
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


Obtient ou définit le mode de fusion du contour.

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


Obtient ou définit l'entité Stroke. La propriété détermine les paramètres de remplissage du trait.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


Obtient ou définit l'alignement de ligne du style Stroke.

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


Obtient ou définit le type de terminaison de ligne du style de contour.

Valeur : Le type du stroke style line cap.

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


Obtient ou définit la largeur de la terminaison de ligne du contour.

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


Obtient ou définit le stroke style line dash offset.

Valeur : Le stroke style line dash offset.

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


Obtient ou définit le tableau de tirets de ligne.

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


Obtient ou définit le Stroke style line join type.

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


Obtient ou définit le Stroke line width.

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


Obtient ou définit la stroke style miter limit.

Valeur : La stroke style miter limit.

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


Obtient ou définit la Stroke style opacity (0-100%).

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


Obtient ou définit la Stroke style resolution.

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


Obtient ou définit le Stroke style scale lock.

**Returns:**
booléen
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


Obtient ou définit le Stroke adjust.

**Returns:**
booléen
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


Obtient ou définit la stroke style version.

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Obtient ou définit l'instance ClassID.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Obtient ou définit le nom de la classe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


Obtient ou définit une valeur indiquant si le remplissage de contour est activé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


Obtient ou définit les paramètres de remplissage du Stroke.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


Obtient ou définit une valeur indiquant si l'effet de contour est activé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


Obtient ou définit le mode de fusion du contour.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


Obtient ou définit l'entité Stroke. La propriété détermine les paramètres de remplissage du trait.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


Obtient ou définit l'alignement de ligne du style Stroke.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


Obtient ou définit le type de terminaison de ligne du style de contour.

Valeur : Le type du stroke style line cap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


Obtient ou définit la largeur de la terminaison de ligne du contour.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


Obtient ou définit le stroke style line dash offset.

Valeur : Le stroke style line dash offset.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


Obtient ou définit le tableau de tirets de ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


Obtient ou définit le Stroke style line join type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


Obtient ou définit le Stroke line width.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


Obtient ou définit la stroke style miter limit.

Valeur : La stroke style miter limit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


Obtient ou définit la Stroke stryle opacity (0-100%).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


Obtient ou définit la Stroke style resolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


Obtient ou définit le Stroke style scale lock.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


Obtient ou définit le Stroke adjust.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


Obtient ou définit la stroke style version.

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

