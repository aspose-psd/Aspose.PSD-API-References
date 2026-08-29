---
title: "AiLayerSection"
second_title: "Aspose.PSD för Java API-referens"
description: "Ai-formatets lagersektion"
type: docs
weight: 15
url: /sv/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Ai-formatets lagersektion
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Lägger till rasterbilden. |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Hämtar eller anger den blå färgkomponenten. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Hämtar eller anger färgens index. |
| [getColorNumber()](#getColorNumber--) | Hämtar eller anger färgnumret. |
| [getData()](#getData--) | Hämtar strängdata. |
| [getDimValue()](#getDimValue--) | Hämtar eller anger dimningsvärdet som procent. |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getGreen()](#getGreen--) | Hämtar eller anger den gröna färgkomponenten. |
| [getName()](#getName--) | Hämtar eller anger lagrets namn. |
| [getRasterImages()](#getRasterImages--) | Hämtar rasterbilderna. |
| [getRed()](#getRed--) | Hämtar eller anger den röda färgkomponenten. |
| [getStream_internalized()](#getStream-internalized--) | Hämtar den inre strömmen |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Hämtar eller anger ett värde som indikerar om detta objekt har flerskiktsmasker. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Hämtar eller anger ett värde som indikerar om detta lager är dimmat. |
| [isLocked()](#isLocked--) | Hämtar eller anger ett värde som indikerar om detta lager är låst. |
| [isPreview()](#isPreview--) | Hämtar eller anger ett värde som indikerar om detta lager är i förhandsgranskning. |
| [isPrinted()](#isPrinted--) | Hämtar eller anger ett värde som indikerar om detta lager skrivs ut. |
| [isShown()](#isShown--) | Hämtar eller anger ett värde som indikerar om detta lager visas. |
| [isTemplate()](#isTemplate--) | Hämtar eller anger ett värde som indikerar om detta lager är ett mallager. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Hämtar eller anger den blå färgkomponenten. |
| [setColorIndex(int value)](#setColorIndex-int-) | Hämtar eller anger färgens index. |
| [setColorNumber(int value)](#setColorNumber-int-) | Hämtar eller anger färgnumret. |
| [setDimValue(int value)](#setDimValue-int-) | Hämtar eller anger dimningsvärdet som procent. |
| [setGreen(int value)](#setGreen-int-) | Hämtar eller anger den gröna färgkomponenten. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Hämtar eller anger ett värde som indikerar om detta lager är dimmat. |
| [setLocked(boolean value)](#setLocked-boolean-) | Hämtar eller anger ett värde som indikerar om detta lager är låst. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekt har flerskiktsmasker. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger lagrets namn. |
| [setPreview(boolean value)](#setPreview-boolean-) | Hämtar eller anger ett värde som indikerar om detta lager är i förhandsgranskning. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Hämtar eller anger ett värde som indikerar om detta lager skrivs ut. |
| [setRed(int value)](#setRed-int-) | Hämtar eller anger den röda färgkomponenten. |
| [setShown(boolean value)](#setShown-boolean-) | Hämtar eller anger ett värde som indikerar om detta lager visas. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Hämtar eller anger ett värde som indikerar om detta lager är ett mallager. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Lägger till rasterbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | Rasterbilden. |

### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| egenskaper | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Hämtar eller anger den blå färgkomponenten.

Värde: Den blå färgkomponenten.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Hämtar eller anger färgens index. Detta argument kan ha värden mellan \\u20131 och 26. Varje heltal representerar en färg som kan tilldelas lagret för användaridentifieringsändamål.

Värde: Färgens index.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Hämtar eller anger färgnumret. -1 är det anpassade färgvärdet från egenskaperna Röd, Grön, Blå. Anger lagrets färginställning.

Värde: Färgnumret.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Hämtar strängdata.

**Returns:**
java.lang.String - Strängdata för sektionen
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Hämtar eller anger dimningsvärdet i procent. Minskar intensiteten hos länkade bilder och bitmapbilder som finns i lagret till den angivna procentsatsen.

Värde: Dimningsvärdet i procent.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Hämtar eller anger den gröna färgkomponenten.

Värde: Den gröna färgkomponenten.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger lagrets namn. Anger namnet på objektet som det visas i lagerpanelen.

Värde: Lagernamnet.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Hämtar rasterbilderna.

Värde: Rasterbilderna.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Hämtar eller anger den röda färgkomponenten.

Värde: Den röda färgkomponenten.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Hämtar den inre strömmen

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Hämtar eller anger ett värde som indikerar om detta objekt har flerskiktsmasker.

Värde:  true  om detta objekt har flerskiktsmasker; annars,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Hämtar eller anger ett värde som indikerar om detta lager är dimmat. Minskar intensiteten hos länkade bilder och bitmapbilder som finns i lagret.

Värde:  true  om detta lager är dimmat; annars,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Hämtar eller anger ett värde som indikerar om detta lager är låst. Förhindrar ändringar av objektet.

Värde:  true  om detta lager är låst; annars,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Hämtar eller anger ett värde som indikerar om detta lager är förhandsgranskning. Visar konstverket i lagret i färg istället för som konturer.

Värde:  true  om detta lager är förhandsgranskning; annars,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Hämtar eller anger ett värde som indikerar om detta lager skrivs ut. Gör konstverket i lagret utskrivbart om sant.

Värde:  true  om detta lager skrivs ut; annars,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Hämtar eller anger ett värde som indikerar om detta lager visas. Visar allt konstverk i lagret på arbetsytan om sant.

Värde:  true  om detta lager visas; annars,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Hämtar eller anger ett värde som indikerar om detta lager är ett mallager.

Värde:  true  om detta lager är en mall; annars,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Hämtar eller anger den blå färgkomponenten.

Värde: Den blå färgkomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Hämtar eller anger färgens index. Detta argument kan ha värden mellan \\u20131 och 26. Varje heltal representerar en färg som kan tilldelas lagret för användaridentifieringsändamål.

Värde: Färgens index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Hämtar eller anger färgnumret. -1 är det anpassade färgvärdet från egenskaperna Röd, Grön, Blå. Anger lagrets färginställning.

Värde: Färgnumret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Hämtar eller anger dimningsvärdet i procent. Minskar intensiteten hos länkade bilder och bitmapbilder som finns i lagret till den angivna procentsatsen.

Värde: Dimningsvärdet i procent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Hämtar eller anger den gröna färgkomponenten.

Värde: Den gröna färgkomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta lager är dimmat. Minskar intensiteten hos länkade bilder och bitmapbilder som finns i lagret.

Värde:  true  om detta lager är dimmat; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta lager är låst. Förhindrar ändringar av objektet.

Värde:  true  om detta lager är låst; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekt har flerskiktsmasker.

Värde:  true  om detta objekt har flerskiktsmasker; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger lagrets namn. Anger namnet på objektet som det visas i lagerpanelen.

Värde: Lagernamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta lager är förhandsgranskning. Visar konstverket i lagret i färg istället för som konturer.

Värde:  true  om detta lager är förhandsgranskning; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta lager skrivs ut. Gör konstverket i lagret utskrivbart om sant.

Värde:  true  om detta lager skrivs ut; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Hämtar eller anger den röda färgkomponenten.

Värde: Den röda färgkomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta lager visas. Visar allt konstverk i lagret på arbetsytan om sant.

Värde:  true  om detta lager visas; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta lager är ett mallager.

Värde:  true  om detta lager är en mall; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

