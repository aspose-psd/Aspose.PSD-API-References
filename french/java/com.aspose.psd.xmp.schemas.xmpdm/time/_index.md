---
title: "Time"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représentation d'une valeur de temps en secondes."
type: docs
weight: 13
url: /fr/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Représentation d'une valeur de temps en secondes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Initialise une nouvelle instance de la classe  Time . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | Obtient ou définit l'échelle de la valeur temporelle. |
| [getValue()](#getValue--) | Obtient ou définit la valeur temporelle dans l'échelle spécifiée. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur de chaîne contenue au format XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | Obtient ou définit l'échelle de la valeur temporelle. |
| [setValue(int value)](#setValue-int-) | Obtient ou définit la valeur temporelle dans l'échelle spécifiée. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initialise une nouvelle instance de la classe  Time .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | L'échelle. |
| valeur | int | La valeur. |

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
### getScale() {#getScale--}
```
public Rational getScale()
```


Obtient ou définit l'échelle de la valeur temporelle.

Pour NTSC, utilisez 1001/30000, ou le moins précis 100/2997. Pour PAL, utilisez 1/25. Valeur : L'échelle de la valeur temporelle.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


Obtient ou définit la valeur temporelle dans l'échelle spécifiée.

Valeur : La valeur temporelle dans l'échelle spécifiée.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtient la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Obtient ou définit l'échelle de la valeur temporelle.

Pour NTSC, utilisez 1001/30000, ou le moins précis 100/2997. Pour PAL, utilisez 1/25. Valeur : L'échelle de la valeur temporelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Obtient ou définit la valeur temporelle dans l'échelle spécifiée.

Valeur : La valeur temporelle dans l'échelle spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

