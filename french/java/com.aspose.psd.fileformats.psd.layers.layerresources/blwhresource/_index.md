---
title: "BlwhResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La classe BlwhResource est une ressource du calque d'ajustement noir et blanc."
type: docs
weight: 15
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

La classe BlwhResource est une ressource du calque d'ajustement noir et blanc.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Initialise une nouvelle instance de la classe [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource). |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Obtient ou définit le nom de fichier du préréglage noir et blanc. |
| [getBlues()](#getBlues--) | Obtient ou définit la valeur des bleus. |
| [getBwPresetKind()](#getBwPresetKind--) | Obtient ou définit la valeur du type de préréglage noir et blanc. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Obtient ou définit la valeur des cyans. |
| [getData()](#getData--) | Obtient ou définit les données. |
| [getGreens()](#getGreens--) | Obtient ou définit la valeur des verts. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLength()](#getLength--) | Obtient la longueur de la ressource de calque en octets. |
| [getMagentas()](#getMagentas--) | Obtient ou définit la valeur des magentas. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getReds()](#getReds--) | Obtient ou définit la valeur des rouges. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getTintColor()](#getTintColor--) | Obtient la couleur de teinte ARGB. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Obtient ou définit la valeur double de Blue Tint Color. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Obtient ou définit la valeur double de Green Tint Color. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Obtient ou définit la valeur double de Red Tint Color. |
| [getUseTint()](#getUseTint--) | Obtient ou définit une valeur indiquant si [tint color] est utilisé. |
| [getYellows()](#getYellows--) | Obtient ou définit la valeur des jaunes. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Obtient ou définit le nom de fichier du préréglage noir et blanc. |
| [setBlues(int value)](#setBlues-int-) | Obtient ou définit la valeur des bleus. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Obtient ou définit la valeur du type de préréglage noir et blanc. |
| [setCyans(int value)](#setCyans-int-) | Obtient ou définit la valeur des cyans. |
| [setGreens(int value)](#setGreens-int-) | Obtient ou définit la valeur des verts. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setMagentas(int value)](#setMagentas-int-) | Obtient ou définit la valeur des magentas. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Définit la valeur de la propriété par structure de type. |
| [setReds(int value)](#setReds-int-) | Obtient ou définit la valeur des rouges. |
| [setTintColor(int value)](#setTintColor-int-) | Définit la couleur de teinte. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Obtient ou définit la valeur double de Blue Tint Color. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Obtient ou définit la valeur double de Green Tint Color. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Obtient ou définit la valeur double de Red Tint Color. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Obtient ou définit une valeur indiquant si [tint color] est utilisé. |
| [setYellows(int value)](#setYellows-int-) | Obtient ou définit la valeur des jaunes. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Initialise une nouvelle instance de la classe [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource).

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Obtient ou définit le nom de fichier du préréglage noir et blanc.

Valeur : le nom de fichier du préréglage noir et blanc.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Obtient ou définit la valeur des bleus.

Valeur : la valeur des bleus.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Obtient ou définit la valeur du type de préréglage noir et blanc.

Valeur : la valeur du type de préréglage noir et blanc.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Obtient ou définit la valeur des cyans.

Valeur : la valeur des cyans.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Obtient ou définit les données.

Valeur: les données.

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Obtient ou définit la valeur des verts.

Valeur : la valeur des verts.

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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Obtient ou définit la valeur des magentas.

Valeur : la valeur des magentas.

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
### getReds() {#getReds--}
```
public final int getReds()
```


Obtient ou définit la valeur des rouges.

Valeur : la valeur des rouges.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient la signature de la ressource de calque.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Obtient la couleur de teinte ARGB.

**Returns:**
int - La couleur de teinte ARGB.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Obtient ou définit la valeur double de Blue Tint Color.

Valeur : la valeur double de Blue Tint Color.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Obtient ou définit la valeur double de Green Tint Color.

Valeur : la valeur double de Green Tint Color.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Obtient ou définit la valeur double de Red Tint Color.

Valeur : la valeur double de Red Tint Color.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Obtient ou définit une valeur indiquant si [tint color] est utilisé.

Valeur :  vrai  si [tint color] est utilisé ; sinon,  faux .

**Returns:**
booléen
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Obtient ou définit la valeur des jaunes.

Valeur : la valeur des jaunes.

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Obtient ou définit le nom de fichier du préréglage noir et blanc.

Valeur : le nom de fichier du préréglage noir et blanc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Obtient ou définit la valeur des bleus.

Valeur : la valeur des bleus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Obtient ou définit la valeur du type de préréglage noir et blanc.

Valeur : la valeur du type de préréglage noir et blanc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Obtient ou définit la valeur des cyans.

Valeur : la valeur des cyans.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Obtient ou définit la valeur des verts.

Valeur : la valeur des verts.

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Obtient ou définit la valeur des magentas.

Valeur : la valeur des magentas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Définit la valeur de la propriété par structure de type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La structure. |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Obtient ou définit la valeur des rouges.

Valeur : la valeur des rouges.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Définit la couleur de teinte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La valeur. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Obtient ou définit la valeur double de Blue Tint Color.

Valeur : la valeur double de Blue Tint Color.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Obtient ou définit la valeur double de Green Tint Color.

Valeur : la valeur double de Green Tint Color.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Obtient ou définit la valeur double de Red Tint Color.

Valeur : la valeur double de Red Tint Color.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Obtient ou définit une valeur indiquant si [tint color] est utilisé.

Valeur :  vrai  si [tint color] est utilisé ; sinon,  faux .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Obtient ou définit la valeur des jaunes.

Valeur : la valeur des jaunes.

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

