---
title: "GdFlResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe GdFlResource."
type: docs
weight: 33
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class GdFlResource extends FillLayerResource
```

Classe GdFlResource. Cette ressource contient des informations sur le mélange de l'élément découpé.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GdFlResource()](#GdFlResource--) | Initialise une nouvelle instance de la classe [.GdFlResource](../../null/\#GdFlResource). |
## Champs

| Champ | Description |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | L'échelle par défaut. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La version d'en-tête PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La signature de ressource spécifique à PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La version d'en-tête PSD |
| [ResourceSignature](#ResourceSignature) | La signature de ressource commune. |
| [TypeToolKey](#TypeToolKey) | La clé d'information de l'outil de type. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licence de l'entreprise. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addUnknownStructure_internalized(OSTypeStructure structure)](#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Ajoute la structure inconnue. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Vérifie et définit si la ressource est spécifique PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateDefaultControlPoints_internalized()](#generateDefaultControlPoints-internalized--) | Génère les points de contrôle par défaut. |
| [generateDefaultTransparencyPoints_internalized()](#generateDefaultTransparencyPoints-internalized--) | Génère les points de transparence par défaut. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [getAngle()](#getAngle--) | Obtient ou définit l’angle. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtient la couleur du RVB. |
| [getColorModel()](#getColorModel--) | Modèle de couleur - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| [getColorPoints()](#getColorPoints--) | Obtient les points de couleur. |
| [getDither()](#getDither--) | Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est dither. |
| [getGradientInterval()](#getGradientInterval--) | Obtient ou définit l'intervalle du dégradé. |
| [getGradientMode()](#getGradientMode--) | Mode pour ce dégradé. |
| [getGradientName()](#getGradientName--) | Obtient ou définit le nom du dégradé. |
| [getGradientType()](#getGradientType--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtient ou définit le décalage horizontal. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Obtient ou définit la méthode d'interpolation du dégradé. |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLength()](#getLength--) | Obtient la longueur de la ressource de calque en octets. |
| [getMaximumColor()](#getMaximumColor--) | Couleur maximale du PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Couleur minimale du PixelDataFormat. |
| [getOffset_internalized()](#getOffset-internalized--) | Obtient ou définit le décalage. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getReverse()](#getReverse--) | Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est inversé. |
| [getRndNumberSeed()](#getRndNumberSeed--) | La graine du nombre aléatoire utilisée pour générer les couleurs du dégradé de bruit. |
| [getRoughness()](#getRoughness--) | Facteur de rugosité. |
| [getScale()](#getScale--) | Obtient ou définit l'échelle. |
| [getShowTransparency()](#getShowTransparency--) | Indicateur d'affichage de la transparence. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Obtient les points de transparence. |
| [getUseVectorColor()](#getUseVectorColor--) | Indicateur d'utilisation de la couleur vectorielle. |
| [getVerticalOffset()](#getVerticalOffset--) | Obtient ou définit le décalage vertical. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtient la couleur du RVB. |
| [setColorModel(String value)](#setColorModel-java.lang.String-) | Modèle de couleur - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Obtient les points de couleur. |
| [setDither(boolean value)](#setDither-boolean-) | Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est dither. |
| [setGradientInterval(double value)](#setGradientInterval-double-) | Obtient ou définit l'intervalle du dégradé. |
| [setGradientMode(String value)](#setGradientMode-java.lang.String-) | Mode pour ce dégradé. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Obtient ou définit le nom du dégradé. |
| [setGradientType(int value)](#setGradientType-int-) |  |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) |  |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Obtient ou définit la méthode d'interpolation du dégradé. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Couleur maximale du PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Couleur minimale du PixelDataFormat. |
| [setOffset_internalized(OffsetEntity value)](#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Obtient ou définit le décalage. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est inversé. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | La graine du nombre aléatoire utilisée pour générer les couleurs du dégradé de bruit. |
| [setRoughness(int value)](#setRoughness-int-) | Facteur de rugosité. |
| [setScale(double value)](#setScale-double-) | Obtient ou définit l'échelle. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Indicateur d'affichage de la transparence. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Obtient les points de transparence. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Indicateur d'utilisation de la couleur vectorielle. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) |  |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdFlResource() {#GdFlResource--}
```
public GdFlResource()
```


Initialise une nouvelle instance de la classe [.GdFlResource](../../null/\#GdFlResource).

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


L'échelle par défaut.

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

### addUnknownStructure_internalized(OSTypeStructure structure) {#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public void addUnknownStructure_internalized(OSTypeStructure structure)
```


Ajoute la structure inconnue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La structure. |

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
### generateDefaultControlPoints_internalized() {#generateDefaultControlPoints-internalized--}
```
public static IGradientColorPoint[] generateDefaultControlPoints_internalized()
```


Génère les points de contrôle par défaut.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[] - Les points de contrôle par défaut.
### generateDefaultTransparencyPoints_internalized() {#generateDefaultTransparencyPoints-internalized--}
```
public static IGradientTransparencyPoint[] generateDefaultTransparencyPoints_internalized()
```


Génère les points de transparence par défaut.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[] - Les points de transparence par défaut.
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Obtient ou définit une valeur indiquant si [align with layer].

Valeur :  true  si [align with layer] ; sinon,  false .

**Returns:**
booléen
### getAngle() {#getAngle--}
```
public double getAngle()
```


Obtient ou définit l’angle.

L'angle.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Obtient la couleur du RVB.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB Color
### getColorModel() {#getColorModel--}
```
public final String getColorModel()
```


Modèle de couleur - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\").

**Returns:**
java.lang.String
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Obtient les points de couleur.

Valeur : les points de couleur.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est dither.

Valeur :  true  si tramage ; sinon,  false .

**Returns:**
booléen
### getGradientInterval() {#getGradientInterval--}
```
public final double getGradientInterval()
```


Obtient ou définit l'intervalle du dégradé.

Valeur: l'intervalle du dégradé.

**Returns:**
double
### getGradientMode() {#getGradientMode--}
```
public final String getGradientMode()
```


Mode pour ce dégradé. Détermine le 'Type de dégradé' = 'Solide/Bruit' = \"CstS\"/\"ClNs\".

**Returns:**
java.lang.String
### getGradientName() {#getGradientName--}
```
public String getGradientName()
```


Obtient ou définit le nom du dégradé.

Valeur: le nom du dégradé.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public int getGradientType()
```




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
### getHorizontalOffset() {#getHorizontalOffset--}
```
public double getHorizontalOffset()
```


Obtient ou définit le décalage horizontal.

Le décalage horizontal.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Obtient ou définit la méthode d'interpolation du dégradé.

**Returns:**
long
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Couleur maximale du PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Couleur minimale du PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getOffset_internalized() {#getOffset-internalized--}
```
public final OffsetEntity getOffset_internalized()
```


Obtient ou définit le décalage.

Valeur: le décalage.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Returns:**
booléen
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


La graine du nombre aléatoire utilisée pour générer les couleurs du dégradé de bruit.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Facteur de rugosité.

**Returns:**
int
### getScale() {#getScale--}
```
public final double getScale()
```


Obtient ou définit l'échelle.

**Returns:**
double
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Indicateur d'affichage de la transparence.

**Returns:**
booléen
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient la signature de la ressource de calque.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Obtient les points de transparence.

Valeur : les points de transparence.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Indicateur d'utilisation de la couleur vectorielle.

**Returns:**
booléen
### getVerticalOffset() {#getVerticalOffset--}
```
public double getVerticalOffset()
```


Obtient ou définit le décalage vertical.

Le décalage vertical.

**Returns:**
double
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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Obtient ou définit une valeur indiquant si [align with layer].

Valeur :  true  si [align with layer] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Obtient la couleur du RVB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setColorModel(String value) {#setColorModel-java.lang.String-}
```
public final void setColorModel(String value)
```


Modèle de couleur - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\").

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Obtient les points de couleur.

Valeur : les points de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est dither.

Valeur :  true  si tramage ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setGradientInterval(double value) {#setGradientInterval-double-}
```
public final void setGradientInterval(double value)
```


Obtient ou définit l'intervalle du dégradé.

Valeur: l'intervalle du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setGradientMode(String value) {#setGradientMode-java.lang.String-}
```
public final void setGradientMode(String value)
```


Mode pour ce dégradé. Détermine le 'Type de dégradé' = 'Solide/Bruit' = \"CstS\"/\"ClNs\".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public void setGradientName(String value)
```


Obtient ou définit le nom du dégradé.

Valeur: le nom du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public void setGradientType(int value)
```




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

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public void setHorizontalOffset(double value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Obtient ou définit la méthode d'interpolation du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Couleur maximale du PixelDataFormat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Couleur minimale du PixelDataFormat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setOffset_internalized(OffsetEntity value) {#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setOffset_internalized(OffsetEntity value)
```


Obtient ou définit le décalage.

Valeur: le décalage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Obtient ou définit une valeur indiquant si ce [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


La graine du nombre aléatoire utilisée pour générer les couleurs du dégradé de bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Facteur de rugosité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Obtient ou définit l'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Indicateur d'affichage de la transparence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Obtient les points de transparence.

Valeur : les points de transparence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Indicateur d'utilisation de la couleur vectorielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public void setVerticalOffset(double value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

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

