---
title: "ImageAttributes"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Ein com.aspose.psd.ImageAttributes-Objekt enthält Informationen darüber, wie Bitmap- und Metadatei-Farben während des Renderns manipuliert werden."
type: docs
weight: 55
url: /de/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Ein com.aspose.psd.ImageAttributes-Objekt enthält Informationen darüber, wie Bitmap- und Metadatei-Farben während des Renderns manipuliert werden. Ein com.aspose.psd.ImageAttributes-Objekt verwaltet mehrere Farbkorrektureinstellungen, einschließlich Farbkorrektur‑Matrizen, Graustufen‑Korrekturmatrizen, Gamma‑Korrekturwerte, Farb‑Zuordnungstabellen und Farb‑Schwellenwerte. Beim Rendern können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie ein com.aspose.psd.ImageAttributes‑Objekt und übergeben den Pfad dieses com.aspose.psd.ImageAttributes‑Objekts (zusammen mit dem Pfad eines [Image](../../com.aspose.psd/image)) an die drawImage‑Methode.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initialisiert eine neue Instanz der com.aspose.psd.ImageAttributes-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | Die GDI-Bildattribute. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Löscht die Pinsel-Farbzuordnungstabelle dieses com.aspose.psd.ImageAttributes-Objekts. |
| [clearColorKey()](#clearColorKey--) | Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie. |
| [clearColorKey(int type)](#clearColorKey-int-) | Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [clearColorMatrix()](#clearColorMatrix--) | Löscht die Farbkorrekturmatrix für die Standardkategorie. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Löscht die Farbkorrekturmatrix für eine angegebene Kategorie. |
| [clearGamma()](#clearGamma--) | Deaktiviert die Gamma‑Korrektur für die Standardkategorie. |
| [clearGamma(int type)](#clearGamma-int-) | Deaktiviert die Gamma‑Korrektur für eine angegebene Kategorie. |
| [clearNoOp()](#clearNoOp--) | Löscht die NoOp‑Einstellung für die Standardkategorie. |
| [clearNoOp(int type)](#clearNoOp-int-) | Löscht die NoOp‑Einstellung für eine angegebene Kategorie. |
| [clearOutputChannel()](#clearOutputChannel--) | Löscht die CMYK (Cyan-Magenta-Gelb-Schwarz)-Ausgabekanal‑Einstellung für die Standardkategorie. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Löscht die (Cyan-Magenta-Gelb-Schwarz)-Ausgabekanal‑Einstellung für eine angegebene Kategorie. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Löscht die Ausgabekanal‑Farbprofil‑Einstellung für die Standardkategorie. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Löscht die Ausgabekanal‑Farbprofil‑Einstellung für eine angegebene Kategorie. |
| [clearRemapTable()](#clearRemapTable--) | Löscht die Farbzuordnungstabelle für die Standardkategorie. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Löscht die Farbzuordnungstabelle für eine angegebene Kategorie. |
| [clearThreshold()](#clearThreshold--) | Löscht den Schwellenwert für die Standardkategorie. |
| [clearThreshold(int type)](#clearThreshold-int-) | Löscht den Schwellenwert für eine angegebene Kategorie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Legt die Farb-Remap-Tabelle für die Pinselkategorie fest. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Legt den Farbenschlüssel für die Standardkategorie fest. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Legt den Farbenschlüssel (Transparenzbereich) für eine angegebene Kategorie fest. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für eine angegebene Kategorie fest. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Legt die Farbkorrekturmatrix für die Standardkategorie fest. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Legt die Farbkorrekturmatrix für die Standardkategorie fest. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Legt die Farbkorrekturmatrix für eine angegebene Kategorie fest. |
| [setGamma(float gamma)](#setGamma-float-) | Legt den Gammawert für die Standardkategorie fest. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Legt den Gammawert für eine angegebene Kategorie fest. |
| [setNoOp()](#setNoOp--) | Schaltet die Farbkorrektur für die Standardkategorie aus. |
| [setNoOp(int type)](#setNoOp-int-) | Schaltet die Farbkorrektur für eine angegebene Kategorie aus. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für die Standardkategorie fest. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für eine angegebene Kategorie fest. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Legt die Farbprofildatei des Ausgabekanals für die Standardkategorie fest. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Legt die Farbprofildatei des Ausgabekanals für eine angegebene Kategorie fest. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Legt die Farb-Remap-Tabelle für die Standardkategorie fest. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Legt die Farb-Remap-Tabelle für eine angegebene Kategorie fest. |
| [setThreshold(float threshold)](#setThreshold-float-) | Legt den Schwellenwert (Transparenzbereich) für die Standardkategorie fest. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Legt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie fest. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Legt den Wrap-Modus fest, der verwendet wird, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initialisiert eine neue Instanz der com.aspose.psd.ImageAttributes-Klasse.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


Die GDI-Bildattribute.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Löscht die Pinsel-Farbzuordnungstabelle dieses com.aspose.psd.ImageAttributes-Objekts.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die der Farbenschlüssel gelöscht wird. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Löscht die Farbkorrekturmatrix für die Standardkategorie.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Löscht die Farbkorrekturmatrix für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Farbkorrekturmatrix gelöscht wird. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Deaktiviert die Gamma‑Korrektur für die Standardkategorie.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Deaktiviert die Gamma‑Korrektur für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Gammakorrektur deaktiviert ist. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Löscht die NoOp‑Einstellung für die Standardkategorie.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Löscht die NoOp‑Einstellung für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die NoOp-Einstellung zurückgesetzt wird. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Löscht die CMYK (Cyan-Magenta-Gelb-Schwarz)-Ausgabekanal‑Einstellung für die Standardkategorie.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Löscht die (Cyan-Magenta-Gelb-Schwarz)-Ausgabekanal‑Einstellung für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Einstellung des Ausgabekanals zurückgesetzt wird. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Löscht die Ausgabekanal‑Farbprofil‑Einstellung für die Standardkategorie.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Löscht die Ausgabekanal‑Farbprofil‑Einstellung für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Einstellung des Ausgabekanalprofils zurückgesetzt wird. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Löscht die Farbzuordnungstabelle für die Standardkategorie.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Löscht die Farbzuordnungstabelle für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Remap-Tabelle zurückgesetzt wird. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Löscht den Schwellenwert für die Standardkategorie.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Löscht den Schwellenwert für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die der Schwellenwert zurückgesetzt wird. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Legt die Farb-Remap-Tabelle für die Pinselkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Ein Array von com.aspose.psd.ColorMap-Objekten. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Legt den Farbenschlüssel für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Der niedrige Farbschlüsselwert. |
| colorHigh | [Color](../../com.aspose.psd/color) | Der hohe Farbschlüsselwert. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Legt den Farbenschlüssel (Transparenzbereich) für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Der niedrige Farbschlüsselwert. |
| colorHigh | [Color](../../com.aspose.psd/color) | Der hohe Farbschlüsselwert. |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die der Farbschlüssel festgelegt wird. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Farbkorrekturmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Graustufen-Korrekturmatrix. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Farbkorrekturmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Graustufen-Korrekturmatrix. |
| Kennzeichen | int | Ein Element von Aspose.Imaging.ColorMatrixFlag, das den Bild- und Farbtyp angibt, der von den Farbkorrektur- und Graustufen-Korrekturmatrizen betroffen ist. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Farbkorrekturmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Graustufen-Korrekturmatrix. |
| Modus | int | Ein Element von Aspose.Imaging.ColorMatrixFlag, das den Bild- und Farbtyp angibt, der von den Farbkorrektur- und Graustufen-Korrekturmatrizen betroffen ist. |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Farbkorrektur- und Graustufen-Korrekturmatrizen festgelegt werden. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Legt die Farbkorrekturmatrix für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Farbkorrekturmatrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Legt die Farbkorrekturmatrix für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Farbkorrekturmatrix. |
| Kennzeichen | int | Ein Element von Aspose.Imaging.ColorMatrixFlag, das den Bild- und Farbtyp angibt, der von der Farbkorrekturmatrix betroffen ist. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Legt die Farbkorrekturmatrix für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Die Farbkorrekturmatrix. |
| Modus | int | Ein Element von Aspose.Imaging.ColorMatrixFlag, das den Bild- und Farbtyp angibt, der von der Farbkorrekturmatrix betroffen ist. |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Farbkorrekturmatrix festgelegt wird. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Legt den Gammawert für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Der Gammakorrekturwert. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Legt den Gammawert für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Der Gammakorrekturwert. |
| Typ | int | Ein Element der Aufzählung Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die der Gammawert festgelegt wird. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Schaltet die Farbkorrektur für die Standardkategorie aus.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Schaltet die Farbkorrektur für eine angegebene Kategorie aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Farbkorrektur deaktiviert ist. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kennzeichen | int | Ein Element von Aspose.Imaging.ColorChannelFlag, das den Ausgabekanal angibt. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kennzeichen | int | Ein Element von Aspose.Imaging.ColorChannelFlag, das den Ausgabekanal angibt. |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die der Ausgabekanal festgelegt wird. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Legt die Farbprofildatei des Ausgabekanals für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Der Pfadname einer Farbprofildatei. Wenn die Farbprofildatei im Verzeichnis %SystemRoot%\\System32\\Spool\\Drivers\\Color liegt, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter der vollständig qualifizierte Pfadname sein. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Legt die Farbprofildatei des Ausgabekanals für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Der Pfadname einer Farbprofildatei. Wenn die Farbprofildatei im Verzeichnis %SystemRoot%\\System32\\Spool\\Drivers\\Color liegt, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter der vollständig qualifizierte Pfadname sein. |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Farbprofildatei des Ausgabekanals festgelegt wird. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Legt die Farb-Remap-Tabelle für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Ein Array von Farbpaaren vom Typ com.aspose.psd.ColorMap. Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Legt die Farb-Remap-Tabelle für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Ein Array von Farbpaaren vom Typ com.aspose.psd.ColorMap. Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die die Farbzuordnungstabelle festgelegt wird. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Legt den Schwellenwert (Transparenzbereich) für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Eine reelle Zahl, die den Schwellenwert angibt. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Legt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Ein Schwellenwert von 0,0 bis 1,0, der als Trennpunkt verwendet wird, um Farben zu sortieren, die entweder einem Maximal- oder einem Minimalwert zugeordnet werden. |
| Typ | int | Ein Element von Aspose.Imaging.ColorAdjustType, das die Kategorie angibt, für die der Farbschwellenwert festgelegt wird. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Legt den Wrap-Modus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Modus | int | Ein Element von Aspose.Imaging.WrapMode, das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Modus | int | Ein Element von Aspose.Imaging.WrapMode, das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](../../com.aspose.psd/color) | Ein com.aspose.psd.ImageAttributes-Objekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf WrapMode.Clamp gesetzt ist und das an DrawImage übergebene Quellrechteck größer ist als das Bild selbst. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Modus | int | Ein Element von Aspose.Imaging.WrapMode, das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](../../com.aspose.psd/color) | Ein Farbobjekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf WrapMode.Clamp gesetzt ist und das an DrawImage übergebene Quellrechteck größer ist als das Bild selbst. |
| clamp | boolean | Dieser Parameter hat keine Wirkung. Setzen Sie ihn auf false. |

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

