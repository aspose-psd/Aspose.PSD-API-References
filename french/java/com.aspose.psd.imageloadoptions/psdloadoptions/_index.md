---
title: "PsdLoadOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Options de chargement Psd"
type: docs
weight: 12
url: /fr/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Options de chargement Psd
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Initialise une nouvelle instance de la classe [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Champs

| Champ | Description |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Les sources de polices personnalisées |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Obtient ou définit si les pixels d'origine du calque doivent être conservés lors du rendu si le calque n'a pas été modifié. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation de déformation. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Obtient la couleur d'arrière-plan de l'image. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Obtient le mode de récupération des données. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Obtient une valeur indiquant si [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Obtient ou définit une valeur indiquant si [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Obtient ou définit une valeur indiquant si la largeur fixe du calque de texte PSD sera ignorée lors de l'exécution de l'opération UpdateText. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Obtient ou définit une valeur indiquant si [load effects resource] (par défaut la ressource n'est pas chargée). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient le gestionnaire d'événement de progression. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Obtient ou définit une valeur indiquant si [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Obtient ou définit le mode lecture seule utilisé lors du chargement d'une image PSD. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Obtient ou définit une valeur indiquant si [use disk for load effects resource] (par défaut le disque est utilisé pour charger la ressource d'effets, mais la mémoire peut être utilisée si elle est suffisante en réglant cette valeur sur false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Obtient une valeur indiquant si la conversion du profil ICC doit être appliquée. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Ceci fait partie du modèle de licence venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Obtient ou définit si les pixels d'origine du calque doivent être conservés lors du rendu si le calque n'a pas été modifié. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation de déformation. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Définit la couleur d'arrière-plan de l'image. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Définit le mode de récupération des données. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Définit une valeur indiquant si [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Obtient ou définit une valeur indiquant si [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Obtient ou définit une valeur indiquant si la largeur fixe du calque de texte PSD sera ignorée lors de l'exécution de l'opération UpdateText. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Obtient ou définit une valeur indiquant si [load effects resource] (par défaut la ressource n'est pas chargée). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Obtient ou définit le gestionnaire de mémoire MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Définit le gestionnaire d'événement de progression. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Obtient ou définit une valeur indiquant si [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Obtient ou définit le mode lecture seule utilisé lors du chargement d'une image PSD. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Obtient ou définit une valeur indiquant si [use disk for load effects resource] (par défaut le disque est utilisé pour charger la ressource d'effets, mais la mémoire peut être utilisée si elle est suffisante en réglant cette valeur sur false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Définit une valeur indiquant si la conversion du profil ICC doit être appliquée. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Ceci fait partie du modèle de licence venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Initialise une nouvelle instance de la classe [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Les sources de polices personnalisées

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Obtient ou définit si les pixels d'origine du calque doivent être conservés lors du rendu si le calque n'a pas été modifié.

Valeur :  true  pour conserver les pixels d'origine des calques non modifiés ; sinon,  false .

**Returns:**
booléen
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation de déformation.

Valeur :  true  rend l'image avec transformation de déformation ;  false .

**Returns:**
booléen
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Returns:**
int - l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Obtient la couleur d'arrière-plan de l'image.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Typiquement, la couleur d'arrière-plan est définie chaque fois que la valeur du pixel ne peut pas être récupérée en raison d'une corruption des données.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Obtient le mode de récupération des données.

**Returns:**
int - Le mode de récupération des données.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Obtient une valeur indiquant si [ignore after load].

**Returns:**
boolean -  true  si [ignore after load] ; sinon,  false .
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Obtient ou définit une valeur indiquant si [ignore alpha channel].

Valeur :  true  si [ignore alpha channel] ; sinon,  false .

**Returns:**
booléen
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Obtient ou définit une valeur indiquant si la largeur fixe du calque de texte PSD sera ignorée lors de l'exécution de l'opération UpdateText.

Valeur :  true  si [ignore text layer width] ; sinon,  false .

**Returns:**
booléen
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Obtient ou définit une valeur indiquant si [load effects resource] (par défaut la ressource n'est pas chargée). Lorsqu'elle est définie, seuls les effets pris en charge seront rendus dans l'image fusionnée finale.

Valeur :  true  si [load effects resource] ; sinon,  false .

**Returns:**
booléen
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Obtient le gestionnaire d'événement de progression.

Valeur : Le gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Obtient ou définit une valeur indiquant si [use read only mode]. Il s'agit du mode lecture seule, pris en charge pour une compatibilité identique avec Adobe Photoshop. Lorsque cette option est activée, toutes les modifications appliquées aux calques ne seront pas enregistrées dans l'image finale. Toutes les données proviennent de la section ImageData, ce qui la rend identique à Photoshop. Par défaut, toutes les images chargées ne sont pas compatibles identiques avec Adobe Photoshop.

Valeur :  true  si [use photoshop compatibility mode] ; sinon,  false .

**Returns:**
booléen
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Obtient ou définit le mode lecture seule utilisé lors du chargement d'une image PSD.

Valeur : l'une des valeurs de ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) :

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Obtient ou définit une valeur indiquant si [use disk for load effects resource] (par défaut le disque est utilisé pour charger la ressource d'effets, mais la mémoire peut être utilisée si elle est suffisante en réglant cette valeur sur false).

Valeur :  true  si [use disk for load effects resource] ; sinon,  false .

**Returns:**
booléen
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Obtient une valeur indiquant si la conversion du profil ICC doit être appliquée.

**Returns:**
booléen
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Ceci fait partie du modèle de licence venture. Cette valeur sera définie par VentureLicenser si le venture nous fournit un objet LoadOptions.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Obtient ou définit si les pixels d'origine du calque doivent être conservés lors du rendu si le calque n'a pas été modifié.

Valeur :  true  pour conserver les pixels d'origine des calques non modifiés ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation de déformation.

Valeur :  true  rend l'image avec transformation de déformation ;  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Définit la couleur d'arrière-plan de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | La couleur d'arrière-plan. |

Typiquement, la couleur d'arrière-plan est définie chaque fois que la valeur du pixel ne peut pas être récupérée en raison d'une corruption des données. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Définit le mode de récupération des données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de récupération des données. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Définit une valeur indiquant si [ignore after load].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true  si [ignore after load] ; sinon,  false . |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Obtient ou définit une valeur indiquant si [ignore alpha channel].

Valeur :  true  si [ignore alpha channel] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Obtient ou définit une valeur indiquant si la largeur fixe du calque de texte PSD sera ignorée lors de l'exécution de l'opération UpdateText.

Valeur :  true  si [ignore text layer width] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Obtient ou définit une valeur indiquant si [load effects resource] (par défaut la ressource n'est pas chargée). Lorsqu'elle est définie, seuls les effets pris en charge seront rendus dans l'image fusionnée finale.

Valeur :  true  si [load effects resource] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Obtient ou définit le gestionnaire de mémoire MGR.

Valeur : Le gestionnaire de mémoire MGR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Définit le gestionnaire d'événement de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | le gestionnaire d'événement de progression. |

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Obtient ou définit une valeur indiquant si [use read only mode]. Il s'agit du mode lecture seule, pris en charge pour une compatibilité identique avec Adobe Photoshop. Lorsque cette option est activée, toutes les modifications appliquées aux calques ne seront pas enregistrées dans l'image finale. Toutes les données proviennent de la section ImageData, ce qui la rend identique à Photoshop. Par défaut, toutes les images chargées ne sont pas compatibles identiques avec Adobe Photoshop.

Valeur :  true  si [use photoshop compatibility mode] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Obtient ou définit le mode lecture seule utilisé lors du chargement d'une image PSD.

Valeur : l'une des valeurs de ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) :

 *  
 *  
 *  

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Obtient ou définit une valeur indiquant si [use disk for load effects resource] (par défaut le disque est utilisé pour charger la ressource d'effets, mais la mémoire peut être utilisée si elle est suffisante en réglant cette valeur sur false).

Valeur :  true  si [use disk for load effects resource] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Définit une valeur indiquant si la conversion du profil ICC doit être appliquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Ceci fait partie du modèle de licence venture. Cette valeur sera définie par VentureLicenser si le venture nous fournit un objet LoadOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

