---
title: "SmartResourceCreator"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar SmartResourceCreator-klassen som kan skapa PlLd SoLd och SoLe-resurser."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator/
---

**Inheritance:**
java.lang.Object
```
public class SmartResourceCreator
```

Definierar SmartResourceCreator-klassen som kan skapa PlLd, SoLd och SoLe-resurser. Den används för att stödja smarta objektlager i Adobe\\ufffd Photoshop\\ufffd-bilder.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SmartResourceCreator()](#SmartResourceCreator--) | Initierar en ny instans av klassen [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator). |
| [SmartResourceCreator(boolean isCustom, boolean hasCompInfo)](#SmartResourceCreator-boolean-boolean-) | Initierar en ny instans av klassen [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator). |
| [SmartResourceCreator(PlacedResource template)](#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initierar en ny instans av klassen [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) med den angivna mallen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generatePlacedResource()](#generatePlacedResource--) | Genererar den placerade resursen. |
| [generateSmartEmbeddedResource()](#generateSmartEmbeddedResource--) | Genererar den inbäddade smarta objektresursen. |
| [generateSmartExternalResource()](#generateSmartExternalResource--) | Genererar den externa smarta objektresursen. |
| [getClass()](#getClass--) |  |
| [getTemplate_internalized()](#getTemplate-internalized--) | Hämtar eller anger mallen för smarta objektresursen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartResourceCreator() {#SmartResourceCreator--}
```
public SmartResourceCreator()
```


Initierar en ny instans av klassen [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator).

### SmartResourceCreator(boolean isCustom, boolean hasCompInfo) {#SmartResourceCreator-boolean-boolean-}
```
public SmartResourceCreator(boolean isCustom, boolean hasCompInfo)
```


Initierar en ny instans av klassen [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isCustom | boolean | om den är satt till  true  [är anpassad]. |
| hasCompInfo | boolean | om den är satt till  true  [har kompositionsinformation]. |

### SmartResourceCreator(PlacedResource template) {#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public SmartResourceCreator(PlacedResource template)
```


Initierar en ny instans av klassen [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) med den angivna mallen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| template | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Mallen för smarta objektresursen. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generatePlacedResource() {#generatePlacedResource--}
```
public final PlLdResource generatePlacedResource()
```


Genererar den placerade resursen.

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) - The generated [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) instance.
### generateSmartEmbeddedResource() {#generateSmartEmbeddedResource--}
```
public final SoLdResource generateSmartEmbeddedResource()
```


Genererar den inbäddade smarta objektresursen.

**Returns:**
[SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) - The generated [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) instance.
### generateSmartExternalResource() {#generateSmartExternalResource--}
```
public final SoLeResource generateSmartExternalResource()
```


Genererar den externa smarta objektresursen.

**Returns:**
[SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) - The generated [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) instance.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTemplate_internalized() {#getTemplate-internalized--}
```
public final SmartObjectResource getTemplate_internalized()
```


Hämtar eller anger mallen för smarta objektresursen.

Värde: Mallen för smarta objektresursen.

**Returns:**
[SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

