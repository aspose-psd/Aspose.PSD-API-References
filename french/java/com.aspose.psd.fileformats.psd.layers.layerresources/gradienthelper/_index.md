---
title: "GradientHelper"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe d'aide qui implémente la conversion des données pour les propriétés de dégradé."
type: docs
weight: 34
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Classe d'aide qui implémente la conversion des données pour les propriétés de dégradé.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | Constante entière du modèle de couleur HSBL pour le dégradé de bruit. |
| [IntModelLAB](#IntModelLAB) | Constante entière du modèle de couleur LBCL pour le dégradé de bruit. |
| [IntModelRGB](#IntModelRGB) | Constante entière du modèle de couleur RGBC pour le dégradé de bruit. |
| [StrGradientNoise](#StrGradientNoise) | Constante de chaîne du dégradé de bruit. |
| [StrGradientSolid](#StrGradientSolid) | Constante de chaîne du dégradé solide. |
| [StrModelHSB](#StrModelHSB) | Constante de chaîne du modèle de couleur HSBL pour le dégradé de bruit. |
| [StrModelLAB](#StrModelLAB) | Constante de chaîne du modèle de couleur LBCL pour le dégradé de bruit. |
| [StrModelRGB](#StrModelRGB) | Constante de chaîne du modèle de couleur RGBC pour le dégradé Noise. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Convertir la valeur GradientKind en chaîne. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Convertit la valeur entière du modèle de couleur de bruit en NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Convertit l'instance NoiseColorModel en valeur entière du modèle de couleur de bruit. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Convertir la valeur NoiseColorModel en chaîne. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Convertir la valeur de chaîne en GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Convertir la valeur de chaîne en NoiseColorModel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientHelper() {#GradientHelper--}
```
public GradientHelper()
```


### IntModelHSB {#IntModelHSB}
```
public static final short IntModelHSB
```


Constante entière du modèle de couleur HSBL pour le dégradé de bruit.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


Constante entière du modèle de couleur LBCL pour le dégradé de bruit.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


Constante entière du modèle de couleur RGBC pour le dégradé de bruit.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Constante de chaîne du dégradé de bruit.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Constante de chaîne du dégradé solide.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Constante de chaîne du modèle de couleur HSBL pour le dégradé de bruit.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Constante de chaîne du modèle de couleur LBCL pour le dégradé de bruit.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Constante de chaîne du modèle de couleur RGBC pour le dégradé Noise.

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
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


Convertir la valeur GradientKind en chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gradientKind | int | Valeur GradientKind. |

**Returns:**
java.lang.String - valeur de chaîne.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToNoiseColorModel(short colorModel) {#intToNoiseColorModel-short-}
```
public static short intToNoiseColorModel(short colorModel)
```


Convertit la valeur entière du modèle de couleur de bruit en NoiseColorModel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorModel | short | Valeur entière du modèle de couleur de bruit. |

**Returns:**
short - instance NoiseColorModel.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Convertit l'instance NoiseColorModel en valeur entière du modèle de couleur de bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorModel | short | Instance NoiseColorModel. |

**Returns:**
short - Valeur entière du modèle de couleur du gradient Noise.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Convertir la valeur NoiseColorModel en chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorModel | short | Valeur NoiseColorModel. |

**Returns:**
java.lang.String - Valeur chaîne du modèle de couleur.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


Convertir la valeur de chaîne en GradientKind.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| str | java.lang.String | valeur de chaîne. |

**Returns:**
int - Valeur GradientKind.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Convertir la valeur de chaîne en NoiseColorModel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorModel | java.lang.String | valeur de chaîne. |

**Returns:**
short - Valeur NoiseColorModel.
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

