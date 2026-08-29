---
title: "HatchBrush"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert een rechthoekige brush met een hatchstijl, een voorgrondkleur en een achtergrondkleur."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.brushes/hatchbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class HatchBrush extends Brush
```

Definieert een rechthoekige brush met een hatchstijl, een voorgrondkleur en een achtergrondkleur. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Maakt een nieuwe diepe kloon van de huidige Brush. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt de kleur op van de ruimtes tussen de hatchlijnen. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getForegroundColor()](#getForegroundColor--) | Haalt de kleur op van de hatchlijnen. |
| [getHatchStyle()](#getHatchStyle--) | Haalt de hatchstijl op van deze brush. |
| [getOpacity()](#getOpacity--) | Haalt de dekking van de brush op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Stelt de kleur in van de ruimtes tussen de hatchlijnen. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.psd.Color-) | Stelt de kleur in van de hatchlijnen. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Stelt de hatch-stijl van deze penseel in. |
| [setOpacity(float value)](#setOpacity-float-) | Stelt de dekking van de brush in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Maakt een nieuwe diepe kloon van de huidige Brush.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Haalt de kleur op van de ruimtes tussen de hatchlijnen.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of spaces between the hatch lines.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Haalt de kleur op van de hatchlijnen.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of hatch lines.
### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Haalt de hatchstijl op van deze brush.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Haalt de dekking van de penseel op. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is.

**Returns:**
float - De dekkingwaarde van de penseel.
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Stelt de kleur in van de ruimtes tussen de hatchlijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | De kleur van de ruimtes tussen de hatch-lijnen. |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.psd.Color-}
```
public void setForegroundColor(Color value)
```


Stelt de kleur in van de hatchlijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | De kleur van de hatch-lijnen. |

### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Stelt de hatch-stijl van deze penseel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Stelt de dekking van de penseel in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De dekkingwaarde van de penseel. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

