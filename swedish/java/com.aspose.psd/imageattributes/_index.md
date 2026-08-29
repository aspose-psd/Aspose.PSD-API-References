---
title: "ImageAttributes"
second_title: "Aspose.PSD för Java API-referens"
description: "Ett com.aspose.psd.ImageAttributes-objekt innehåller information om hur bitmap- och metafilfärger manipuleras under rendering."
type: docs
weight: 55
url: /sv/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Ett com.aspose.psd.ImageAttributes-objekt innehåller information om hur bitmap- och metafilfärger manipuleras under rendering. Ett com.aspose.psd.ImageAttributes-objekt upprätthåller flera färgjusteringsinställningar, inklusive färgjusteringsmatriser, gråskalejusteringsmatriser, gamma‑korrektionsvärden, färgkartutabeller och färgtröskelvärden. Under rendering kan färger korrigeras, mörknas, ljusas upp och tas bort. För att tillämpa sådana manipulationer, initiera ett com.aspose.psd.ImageAttributes-objekt och skicka sökvägen till det com.aspose.psd.ImageAttributes-objektet (tillsammans med sökvägen till en [Image](../../com.aspose.psd/image)) till drawImage‑metoden.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initierar en ny instans av klassen com.aspose.psd.ImageAttributes. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | GDI-bildattributen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Rensar penselns färg‑omkartläggningstabell för detta com.aspose.psd.ImageAttributes-objekt. |
| [clearColorKey()](#clearColorKey--) | Rensar färgnyckeln (transparentintervall) för standardkategorin. |
| [clearColorKey(int type)](#clearColorKey-int-) | Rensar färgnyckeln (transparentintervall) för en angiven kategori. |
| [clearColorMatrix()](#clearColorMatrix--) | Rensar färgjusteringsmatrisen för standardkategorin. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Rensar färgjusteringsmatrisen för en angiven kategori. |
| [clearGamma()](#clearGamma--) | Inaktiverar gamma‑korrektion för standardkategorin. |
| [clearGamma(int type)](#clearGamma-int-) | Inaktiverar gamma‑korrektion för en angiven kategori. |
| [clearNoOp()](#clearNoOp--) | Rensar NoOp‑inställningen för standardkategorin. |
| [clearNoOp(int type)](#clearNoOp-int-) | Rensar NoOp‑inställningen för en angiven kategori. |
| [clearOutputChannel()](#clearOutputChannel--) | Rensar CMYK (cyan‑magenta‑yellow‑black) utgångskanalsinställningen för standardkategorin. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Rensar (cyan‑magenta‑yellow‑black) utgångskanalsinställningen för en angiven kategori. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Rensar utgångskanals färgprofilinställning för standardkategorin. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Rensar utgångskanals färgprofilinställning för en angiven kategori. |
| [clearRemapTable()](#clearRemapTable--) | Rensar färg‑omkartläggningstabellen för standardkategorin. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Rensar färg‑omkartläggningstabellen för en angiven kategori. |
| [clearThreshold()](#clearThreshold--) | Rensar tröskelvärdet för standardkategorin. |
| [clearThreshold(int type)](#clearThreshold-int-) | Rensar tröskelvärdet för en specificerad kategori. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Ställer in färg‑omkartningstabellen för penselkategorin. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Ställer in färgnyckeln för standardkategorin. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Ställer in färgnyckeln (transparentintervall) för en specificerad kategori. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för en specificerad kategori. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Ställer in färgjusteringsmatrisen för en specificerad kategori. |
| [setGamma(float gamma)](#setGamma-float-) | Ställer in gamma‑värdet för standardkategorin. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Ställer in gamma‑värdet för en specificerad kategori. |
| [setNoOp()](#setNoOp--) | Stänger av färgjustering för standardkategorin. |
| [setNoOp(int type)](#setNoOp-int-) | Stänger av färgjustering för en specificerad kategori. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Ställer in CMYK‑ (cyan‑magenta‑gul‑svart) utgångskanal för standardkategorin. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Ställer in CMYK‑ (cyan‑magenta‑gul‑svart) utgångskanal för en specificerad kategori. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Ställer in färgprofilfilen för utgångskanalen för standardkategorin. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Ställer in färgprofilfilen för utgångskanalen för en specificerad kategori. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Ställer in färg‑omkartningstabellen för standardkategorin. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Ställer in färg‑omkartningstabellen för en specificerad kategori. |
| [setThreshold(float threshold)](#setThreshold-float-) | Ställer in tröskeln (transparentintervall) för standardkategorin. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Ställer in tröskeln (transparentintervall) för en specificerad kategori. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Ställer in wrap‑läget som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Ställer in wrap‑läget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Ställer in wrap‑läget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initierar en ny instans av klassen com.aspose.psd.ImageAttributes.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


GDI-bildattributen.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Rensar penselns färg‑omkartläggningstabell för detta com.aspose.psd.ImageAttributes-objekt.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Rensar färgnyckeln (transparentintervall) för standardkategorin.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Rensar färgnyckeln (transparentintervall) för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar den kategori för vilken färgnyckeln rensas. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Rensar färgjusteringsmatrisen för standardkategorin.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Rensar färgjusteringsmatrisen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar den kategori för vilken färgjusteringsmatrisen rensas. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Inaktiverar gamma‑korrektion för standardkategorin.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Inaktiverar gamma‑korrektion för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken gammakorrigering är inaktiverad. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Rensar NoOp‑inställningen för standardkategorin.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Rensar NoOp‑inställningen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken NoOp-inställningen rensas. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Rensar CMYK (cyan‑magenta‑yellow‑black) utgångskanalsinställningen för standardkategorin.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Rensar (cyan‑magenta‑yellow‑black) utgångskanalsinställningen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken utkanalinställningen rensas. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Rensar utgångskanals färgprofilinställning för standardkategorin.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Rensar utgångskanals färgprofilinställning för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken utkanalprofilsinställningen rensas. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Rensar färg‑omkartläggningstabellen för standardkategorin.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Rensar färg‑omkartläggningstabellen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken omkartläggningstabellen rensas. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Rensar tröskelvärdet för standardkategorin.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Rensar tröskelvärdet för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken tröskelvärdet rensas. |

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


Ställer in färg‑omkartningstabellen för penselkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | En array av  com.aspose.psd.ColorMap  objekt. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Ställer in färgnyckeln för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Det låga färgnyckelvärdet. |
| colorHigh | [Color](../../com.aspose.psd/color) | Det höga färgnyckelvärdet. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Ställer in färgnyckeln (transparentintervall) för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Det låga färgnyckelvärdet. |
| colorHigh | [Color](../../com.aspose.psd/color) | Det höga färgnyckelvärdet. |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken färgnyckeln sätts. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Gråskalajusteringsmatrisen. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Gråskalajusteringsmatrisen. |
| flaggor | int | Ett element av  Aspose.Imaging.ColorMatrixFlag  som specificerar typen av bild och färg som kommer att påverkas av färgjusterings- och gråskalajusteringsmatriserna. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Gråskalajusteringsmatrisen. |
| mode | int | Ett element av  Aspose.Imaging.ColorMatrixFlag  som specificerar typen av bild och färg som kommer att påverkas av färgjusterings- och gråskalajusteringsmatriserna. |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken färgjusterings- och gråskalajusteringsmatriserna sätts. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Färgjusteringsmatrisen. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Färgjusteringsmatrisen. |
| flaggor | int | Ett element av  Aspose.Imaging.ColorMatrixFlag  som specificerar typen av bild och färg som kommer att påverkas av färgjusteringsmatrisen. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Ställer in färgjusteringsmatrisen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Färgjusteringsmatrisen. |
| mode | int | Ett element av  Aspose.Imaging.ColorMatrixFlag  som specificerar typen av bild och färg som kommer att påverkas av färgjusteringsmatrisen. |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken färgjusteringsmatrisen sätts. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Ställer in gamma‑värdet för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gammakorrigeringsvärdet. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Ställer in gamma‑värdet för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gammakorrigeringsvärdet. |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType ‑enumerationen som specificerar kategorin för vilken gammavärdet sätts. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Stänger av färgjustering för standardkategorin.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Stänger av färgjustering för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken färgkorrigering är avstängd. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Ställer in CMYK‑ (cyan‑magenta‑gul‑svart) utgångskanal för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flaggor | int | Ett element av  Aspose.Imaging.ColorChannelFlag  som specificerar utkanalen. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Ställer in CMYK‑ (cyan‑magenta‑gul‑svart) utgångskanal för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flaggor | int | Ett element av  Aspose.Imaging.ColorChannelFlag  som specificerar utkanalen. |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken utkanalen sätts. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Ställer in färgprofilfilen för utgångskanalen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color, kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständigt kvalificerade sökvägsnamnet. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Ställer in färgprofilfilen för utgångskanalen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color, kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständigt kvalificerade sökvägsnamnet. |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken utkanalens färgprofilfil sätts. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Ställer in färg‑omkartningstabellen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | En array av färgpar av typen  com.aspose.psd.ColorMap . Varje färgpar innehåller en befintlig färg (det första värdet) och färgen som den kommer att mappas till (det andra värdet). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Ställer in färg‑omkartningstabellen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | En array av färgpar av typen  com.aspose.psd.ColorMap . Varje färgpar innehåller en befintlig färg (det första värdet) och färgen som den kommer att mappas till (det andra värdet). |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken färg‑omkartningstabellen är inställd. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Ställer in tröskeln (transparentintervall) för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Ett reellt tal som specificerar tröskelvärdet. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Ställer in tröskeln (transparentintervall) för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Ett tröskelvärde från 0.0 till 1.0 som används som en brytpunkt för att sortera färger som kommer att mappas till antingen ett maximalt eller ett minimalt värde. |
| type | int | Ett element av  Aspose.Imaging.ColorAdjustType  som specificerar kategorin för vilken färgtröskeln är inställd. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Ställer in omslagsläget som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | int | Ett element av  Aspose.Imaging.WrapMode  som specificerar hur upprepade kopior av en bild används för att tilea ett område. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | int | Ett element av  Aspose.Imaging.WrapMode  som specificerar hur upprepade kopior av en bild används för att tilea ett område. |
| color | [Color](../../com.aspose.psd/color) | Ett  com.aspose.psd.ImageAttributes  objekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är inställd på  WrapMode.Clamp  och källrektangeln som skickas till DrawImage är större än själva bilden. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | int | Ett element av  Aspose.Imaging.WrapMode  som specificerar hur upprepade kopior av en bild används för att tilea ett område. |
| color | [Color](../../com.aspose.psd/color) | Ett färgobjekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är inställd på  WrapMode.Clamp  och källrektangeln som skickas till DrawImage är större än själva bilden. |
| clamp | boolean | Denna parameter har ingen effekt. Sätt den till false. |

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

