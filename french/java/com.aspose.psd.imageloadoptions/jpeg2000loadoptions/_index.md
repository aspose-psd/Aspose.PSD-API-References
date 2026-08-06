---
title: "Jpeg2000LoadOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Options de chargement JPEG2000"
type: docs
weight: 10
url: /fr/java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

Options de chargement JPEG2000
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Initialise une nouvelle instance de la classe  Jpeg2000LoadOptions . |
## Champs

| Champ | Description |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Les sources de polices personnalisées |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Obtient la couleur d'arrière-plan de l'image. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Obtient le mode de récupération des données. |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | Obtient le temps de décodage maximal par défaut. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Obtient une valeur indiquant si [ignore after load]. |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Obtient le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très grandes - résolution supérieure à 5500x6500 pixels). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Obtient le temps de décodage maximal pour les tuiles. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient le gestionnaire d'événement de progression. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Obtient une valeur indiquant si la conversion du profil ICC doit être appliquée. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Ceci fait partie du modèle de licence venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Définit la couleur d'arrière-plan de l'image. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Définit le mode de récupération des données. |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | Définit le temps de décodage maximal par défaut. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Définit une valeur indiquant si [ignore after load]. |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Définit le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très grandes - résolution supérieure à 5500x6500 pixels). |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Définit le temps de décodage maximal pour la tuile. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Obtient ou définit le gestionnaire de mémoire MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Définit le gestionnaire d'événement de progression. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Définit une valeur indiquant si la conversion du profil ICC doit être appliquée. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Ceci fait partie du modèle de licence venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Initialise une nouvelle instance de la classe  Jpeg2000LoadOptions .

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
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


Obtient le temps de décodage maximal par défaut.

**Returns:**
int - Le temps de décodage maximal par défaut.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Obtient une valeur indiquant si [ignore after load].

**Returns:**
boolean -  true  si [ignore after load] ; sinon,  false .
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Obtient le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très grandes - résolution supérieure à 5500x6500 pixels).

**Returns:**
int - Le temps de décodage maximal.
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Obtient le temps de décodage maximal pour les tuiles.

Valeur : Le temps de décodage maximal pour la tuile.

**Returns:**
int - le temps de décodage maximal pour la tuile.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Obtient le gestionnaire d'événement de progression.

Valeur : Le gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
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

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


Définit le temps de décodage maximal par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le temps de décodage maximal par défaut. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Définit une valeur indiquant si [ignore after load].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true  si [ignore after load] ; sinon,  false . |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Définit le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très grandes - résolution supérieure à 5500x6500 pixels).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le temps de décodage maximal. |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Définit le temps de décodage maximal pour la tuile.

Valeur : Le temps de décodage maximal pour la tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le temps de décodage maximal pour la tuile. |

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

