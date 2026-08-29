---
title: "Hue2Resource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe Hue2Resource."
type: docs
weight: 36
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class Hue2Resource extends AdjustmentLayerResource
```

Classe Hue2Resource. Ressource du calque d'ajustement d'exposition
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Hue2Resource()](#Hue2Resource--) | Initialise une nouvelle instance de la classe [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource). |
| [Hue2Resource(byte[] data)](#Hue2Resource-byte---) | Initialise une nouvelle instance de la classe [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource). |
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
| [getClass()](#getClass--) |  |
| [getColorize()](#getColorize--) | Obtient ou définit une valeur indiquant si ce [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) est colorisé. |
| [getData()](#getData--) | Obtient ou définit les données. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getHue()](#getHue--) | Obtient ou définit la teinte principale. |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLength()](#getLength--) | Obtient la longueur de la ressource de calque en octets. |
| [getLightness()](#getLightness--) | Obtient ou définit la luminosité principale. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getRanges()](#getRanges--) | Obtient les plages du calque d'ajustement Teinte/Saturation. |
| [getSaturation()](#getSaturation--) | Obtient ou définit la saturation principale. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getVersion()](#getVersion--) | Obtient la version. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setColorize(boolean value)](#setColorize-boolean-) | Obtient ou définit une valeur indiquant si ce [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) est colorisé. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setHue(short value)](#setHue-short-) | Obtient ou définit la teinte principale. |
| [setLightness(short value)](#setLightness-short-) | Obtient ou définit la luminosité principale. |
| [setRanges(ColorRangeHsl[] value)](#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---) | Obtient les plages du calque d'ajustement Teinte/Saturation. |
| [setSaturation(short value)](#setSaturation-short-) | Obtient ou définit la saturation principale. |
| [setVersion(short value)](#setVersion-short-) | Obtient la version. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hue2Resource() {#Hue2Resource--}
```
public Hue2Resource()
```


Initialise une nouvelle instance de la classe [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource).

### Hue2Resource(byte[] data) {#Hue2Resource-byte---}
```
public Hue2Resource(byte[] data)
```


Initialise une nouvelle instance de la classe [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données de la ressource. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorize() {#getColorize--}
```
public final boolean getColorize()
```


Obtient ou définit une valeur indiquant si ce [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) est colorisé.

Valeur:  true  si colorisé ; sinon,  false .

**Returns:**
booléen
### getData() {#getData--}
```
public final byte[] getData()
```


Obtient ou définit les données.

Valeur: les données.

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHue() {#getHue--}
```
public final short getHue()
```


Obtient ou définit la teinte principale.

Valeur: la teinte principale.

**Returns:**
short
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
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Obtient ou définit la luminosité principale.

Valeur: la luminosité principale.

**Returns:**
short
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
### getRanges() {#getRanges--}
```
public final ColorRangeHsl[] getRanges()
```


Obtient les plages du calque d'ajustement Teinte/Saturation. Les plages dans PS peuvent changer de nom si la plage est modifiée, il faut donc travailler par indice.

Valeur: les plages.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl[]
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Obtient ou définit la saturation principale.

Valeur: la saturation principale.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient la signature de la ressource de calque.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Obtient la version. La valeur par défaut est 2.

Valeur : la version.

**Returns:**
short
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

### setColorize(boolean value) {#setColorize-boolean-}
```
public final void setColorize(boolean value)
```


Obtient ou définit une valeur indiquant si ce [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) est colorisé.

Valeur:  true  si colorisé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Obtient ou définit la teinte principale.

Valeur: la teinte principale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Obtient ou définit la luminosité principale.

Valeur: la luminosité principale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setRanges(ColorRangeHsl[] value) {#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---}
```
public void setRanges(ColorRangeHsl[] value)
```


Obtient les plages du calque d'ajustement Teinte/Saturation. Les plages dans PS peuvent changer de nom si la plage est modifiée, il faut donc travailler par indice.

Valeur: les plages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorRangeHsl\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Obtient ou définit la saturation principale.

Valeur: la saturation principale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Obtient la version. La valeur par défaut est 2.

Valeur : la version.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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

