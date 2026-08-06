---
title: "MotionWienerFilterOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Options du filtre de déconvolution     flou de mouvement"
type: docs
weight: 18
url: /fr/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Options de filtre de déconvolution deblur motion
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | Initialise une nouvelle instance de la classe  MotionWienerFilterOptions  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Obtient ou définit l'angle en gradus. |
| [getBrightness()](#getBrightness--) | Obtient ou définit la luminosité. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Obtient ou définit une valeur indiquant si ce [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) est en niveaux de gris. |
| [getLength()](#getLength--) | Obtient ou définit la longueur. |
| [getSmooth()](#getSmooth--) | Obtient ou définit la douceur. |
| [getSnr()](#getSnr--) | Obtient ou définit le SNR (rapport signal sur bruit) plage recommandée 0,002 - 0,009, valeur par défaut = 0,007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Obtient une valeur indiquant si cette instance est partiellement chargée. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | Obtient ou définit l'angle en gradus. |
| [setBrightness(double value)](#setBrightness-double-) | Obtient ou définit la luminosité. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Obtient ou définit une valeur indiquant si ce [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) est en niveaux de gris. |
| [setLength(int value)](#setLength-int-) | Obtient ou définit la longueur. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Obtient une valeur indiquant si cette instance est partiellement chargée. |
| [setSmooth(double value)](#setSmooth-double-) | Obtient ou définit la douceur. |
| [setSnr(double value)](#setSnr-double-) | Obtient ou définit le SNR (rapport signal sur bruit) plage recommandée 0,002 - 0,009, valeur par défaut = 0,007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


Initialise une nouvelle instance de la classe  MotionWienerFilterOptions  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| length | int | La longueur. |
| douceur | double | La douceur. |
| angle | double | L'angle en gradus. |

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
### getAngle() {#getAngle--}
```
public double getAngle()
```


Obtient ou définit l'angle en gradus.

Valeur : l'angle.

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Obtient ou définit la luminosité. plage recommandée 1 - 1,5 valeur par défaut = 1,15

Valeur: la luminosité.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Obtient ou définit une valeur indiquant si ce [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) est en niveaux de gris. Retourne le mode niveaux de gris ou le mode RVB.

Valeur :  true  si niveaux de gris ; sinon,  false .

**Returns:**
booléen
### getLength() {#getLength--}
```
public int getLength()
```


Obtient ou définit la longueur.

Valeur: La longueur.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Obtient ou définit la douceur.

Valeur : la douceur.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Obtient ou définit le SNR (rapport signal sur bruit) plage recommandée 0,002 - 0,009, valeur par défaut = 0,007

Valeur : le SNR.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


Obtient une valeur indiquant si cette instance est partiellement chargée.

Valeur :  true  si cette instance est partiellement chargée ; sinon,  false .

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


Obtient ou définit l'angle en gradus.

Valeur : l'angle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Obtient ou définit la luminosité. plage recommandée 1 - 1,5 valeur par défaut = 1,15

Valeur: la luminosité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Obtient ou définit une valeur indiquant si ce [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) est en niveaux de gris. Retourne le mode niveaux de gris ou le mode RVB.

Valeur :  true  si niveaux de gris ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Obtient ou définit la longueur.

Valeur: La longueur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Obtient une valeur indiquant si cette instance est partiellement chargée.

Valeur :  true  si cette instance est partiellement chargée ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Obtient ou définit la douceur.

Valeur : la douceur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Obtient ou définit le SNR (rapport signal sur bruit) plage recommandée 0,002 - 0,009, valeur par défaut = 0,007

Valeur : le SNR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

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

