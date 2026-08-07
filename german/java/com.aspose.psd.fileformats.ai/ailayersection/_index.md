---
title: "AiLayerSection"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Ebenenabschnitt des Ai-Formats"
type: docs
weight: 15
url: /de/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Der Ebenenabschnitt des Ai-Formats
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Fügt das Rasterbild hinzu. |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Liest oder setzt die blaue Farbkomponente. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Liest oder setzt den Index der Farbe. |
| [getColorNumber()](#getColorNumber--) | Liest oder setzt die Farbnummer. |
| [getData()](#getData--) | Liefert die Zeichenkettendaten. |
| [getDimValue()](#getDimValue--) | Liest oder setzt den Dim-Wert als Prozentsatz. |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getGreen()](#getGreen--) | Liest oder setzt die grüne Farbkomponente. |
| [getName()](#getName--) | Liefert oder setzt den Ebenennamen. |
| [getRasterImages()](#getRasterImages--) | Liefert die Rasterbilder. |
| [getRed()](#getRed--) | Liest oder setzt die rote Farbkomponente. |
| [getStream_internalized()](#getStream-internalized--) | Liefert den inneren Stream |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz Mehrschichtmasken hat. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Liest oder setzt einen Wert, der angibt, ob diese Ebene abgedunkelt ist. |
| [isLocked()](#isLocked--) | Liest oder setzt einen Wert, der angibt, ob diese Ebene gesperrt ist. |
| [isPreview()](#isPreview--) | Liest oder setzt einen Wert, der angibt, ob diese Ebene in der Vorschau ist. |
| [isPrinted()](#isPrinted--) | Liest oder setzt einen Wert, der angibt, ob diese Ebene gedruckt wird. |
| [isShown()](#isShown--) | Liest oder setzt einen Wert, der angibt, ob diese Ebene angezeigt wird. |
| [isTemplate()](#isTemplate--) | Liest oder setzt einen Wert, der angibt, ob diese Ebene eine Vorlagenebene ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Liest oder setzt die blaue Farbkomponente. |
| [setColorIndex(int value)](#setColorIndex-int-) | Liest oder setzt den Index der Farbe. |
| [setColorNumber(int value)](#setColorNumber-int-) | Liest oder setzt die Farbnummer. |
| [setDimValue(int value)](#setDimValue-int-) | Liest oder setzt den Dim-Wert als Prozentsatz. |
| [setGreen(int value)](#setGreen-int-) | Liest oder setzt die grüne Farbkomponente. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Ebene abgedunkelt ist. |
| [setLocked(boolean value)](#setLocked-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Ebene gesperrt ist. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz Mehrschichtmasken hat. |
| [setName(String value)](#setName-java.lang.String-) | Liefert oder setzt den Ebenennamen. |
| [setPreview(boolean value)](#setPreview-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Ebene in der Vorschau ist. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Ebene gedruckt wird. |
| [setRed(int value)](#setRed-int-) | Liest oder setzt die rote Farbkomponente. |
| [setShown(boolean value)](#setShown-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Ebene angezeigt wird. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Ebene eine Vorlagenebene ist. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Fügt das Rasterbild hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | Das Rasterbild. |

### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |
| Eigenschaften | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Liest oder setzt die blaue Farbkomponente.

Wert: Die blaue Farbkomponente.

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


Liest oder setzt den Index der Farbe. Dieses Argument kann Werte zwischen \\u20131 und 26 annehmen. Jeder ganzzahlige Wert stellt eine Farbe dar, die der Ebene zur Benutzeridentifikation zugewiesen werden kann.

Wert: Der Index der Farbe.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Liest oder setzt die Farbnummer. -1 ist der benutzerdefinierte Farbwert aus den Eigenschaften Rot, Grün, Blau. Gibt die Farbeinstellung der Ebene\\u2019 an.

Wert: Die Farbnummer.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Liefert die Zeichenkettendaten.

**Returns:**
java.lang.String - Die Zeichenkettendaten des Abschnitts
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Liest oder setzt den Dimmwert als Prozentsatz. Reduziert die Intensität verknüpfter Bilder und Bitmap-Bilder in der Ebene auf den angegebenen Prozentsatz.

Wert: Der Dimmwert als Prozentsatz.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Liest oder setzt die grüne Farbkomponente.

Wert: Die grüne Farbkomponente.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Liest oder setzt den Ebenennamen. Gibt den Namen des Elements an, wie er im Ebenen‑Panel erscheint.

Wert: Der Ebenenname.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Liefert die Rasterbilder.

Wert: Die Rasterbilder.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Liest oder setzt die rote Farbkomponente.

Wert: Die rote Farbkomponente.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Liefert den inneren Stream

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz Mehrschichtmasken hat.

Wert:  true  wenn diese Instanz Mehrschichtmasken hat; andernfalls,  false .

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


Liest oder setzt einen Wert, der angibt, ob diese Ebene abgedunkelt ist. Reduziert die Intensität verknüpfter Bilder und Bitmap-Bilder in der Ebene.

Wert:  true  wenn diese Ebene abgedunkelt ist; andernfalls,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene gesperrt ist. Verhindert Änderungen am Element.

Wert:  true  wenn diese Ebene gesperrt ist; andernfalls,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene in der Vorschau ist. Zeigt die in der Ebene enthaltenen Kunstwerke in Farbe anstelle von Konturen.

Wert:  true  wenn diese Ebene in der Vorschau ist; andernfalls,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene gedruckt wird. Macht die in der Ebene enthaltene Grafik druckbar, wenn true.

Wert:  true  wenn diese Ebene gedruckt wird; andernfalls  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene angezeigt wird. Zeigt alle in der Ebene enthaltenen Grafiken auf dem Zeichenbrett an, wenn true.

Wert:  true  wenn diese Ebene angezeigt wird; andernfalls  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene eine Vorlagenebene ist.

Wert:  true  wenn diese Ebene eine Vorlage ist; andernfalls  false .

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


Liest oder setzt die blaue Farbkomponente.

Wert: Die blaue Farbkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Liest oder setzt den Index der Farbe. Dieses Argument kann Werte zwischen \\u20131 und 26 annehmen. Jeder ganzzahlige Wert stellt eine Farbe dar, die der Ebene zur Benutzeridentifikation zugewiesen werden kann.

Wert: Der Index der Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Liest oder setzt die Farbnummer. -1 ist der benutzerdefinierte Farbwert aus den Eigenschaften Rot, Grün, Blau. Gibt die Farbeinstellung der Ebene\\u2019 an.

Wert: Die Farbnummer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Liest oder setzt den Dimmwert als Prozentsatz. Reduziert die Intensität verknüpfter Bilder und Bitmap-Bilder in der Ebene auf den angegebenen Prozentsatz.

Wert: Der Dimmwert als Prozentsatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Liest oder setzt die grüne Farbkomponente.

Wert: Die grüne Farbkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene abgedunkelt ist. Reduziert die Intensität verknüpfter Bilder und Bitmap-Bilder in der Ebene.

Wert:  true  wenn diese Ebene abgedunkelt ist; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene gesperrt ist. Verhindert Änderungen am Element.

Wert:  true  wenn diese Ebene gesperrt ist; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz Mehrschichtmasken hat.

Wert:  true  wenn diese Instanz Mehrschichtmasken hat; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Liest oder setzt den Ebenennamen. Gibt den Namen des Elements an, wie er im Ebenen‑Panel erscheint.

Wert: Der Ebenenname.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene in der Vorschau ist. Zeigt die in der Ebene enthaltenen Kunstwerke in Farbe anstelle von Konturen.

Wert:  true  wenn diese Ebene in der Vorschau ist; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene gedruckt wird. Macht die in der Ebene enthaltene Grafik druckbar, wenn true.

Wert:  true  wenn diese Ebene gedruckt wird; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Liest oder setzt die rote Farbkomponente.

Wert: Die rote Farbkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene angezeigt wird. Zeigt alle in der Ebene enthaltenen Grafiken auf dem Zeichenbrett an, wenn true.

Wert:  true  wenn diese Ebene angezeigt wird; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Ebene eine Vorlagenebene ist.

Wert:  true  wenn diese Ebene eine Vorlage ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

