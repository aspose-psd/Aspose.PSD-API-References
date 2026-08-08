---
title: "ImageAttributes"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Een com.aspose.psd.ImageAttributes object bevat informatie over hoe bitmap- en metafilekleuren worden gemanipuleerd tijdens het renderen."
type: docs
weight: 55
url: /nl/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Een  com.aspose.psd.ImageAttributes  object bevat informatie over hoe bitmap- en metafilekleuren worden gemanipuleerd tijdens het renderen. Een  com.aspose.psd.ImageAttributes  object onderhoudt verschillende kleurcorrectie-instellingen, waaronder kleurcorrectiematrices, grijstintcorrectiematrices, gamma-correctiewaarden, kleurkaarttabellen en kleurdrempelwaarden. Tijdens het renderen kunnen kleuren worden gecorrigeerd, verduisterd, opgehelderd en verwijderd. Om dergelijke manipulaties toe te passen, initialiseert u een  com.aspose.psd.ImageAttributes  object en geeft u het pad van dat  com.aspose.psd.ImageAttributes  object (samen met het pad van een [Image](../../com.aspose.psd/image)) door aan de drawImage-methode.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initialiseert een nieuw exemplaar van de  com.aspose.psd.ImageAttributes  klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | De GDI-afbeeldingsattributen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Wist de kwastkleur-herkaarttabel van dit  com.aspose.psd.ImageAttributes  object. |
| [clearColorKey()](#clearColorKey--) | Wist de kleurensleutel (transparantiebereik) voor de standaardcategorie. |
| [clearColorKey(int type)](#clearColorKey-int-) | Wist de kleurensleutel (transparantiebereik) voor een opgegeven categorie. |
| [clearColorMatrix()](#clearColorMatrix--) | Wist de kleurcorrectiematrix voor de standaardcategorie. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Wist de kleurcorrectiematrix voor een opgegeven categorie. |
| [clearGamma()](#clearGamma--) | Schakelt gamma-correctie uit voor de standaardcategorie. |
| [clearGamma(int type)](#clearGamma-int-) | Schakelt gamma-correctie uit voor een opgegeven categorie. |
| [clearNoOp()](#clearNoOp--) | Wist de NoOp-instelling voor de standaardcategorie. |
| [clearNoOp(int type)](#clearNoOp-int-) | Wist de NoOp-instelling voor een opgegeven categorie. |
| [clearOutputChannel()](#clearOutputChannel--) | Wist de CMYK (cyaan-magenta-geel-zwart) uitgangskanaalinstelling voor de standaardcategorie. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Wist de (cyaan-magenta-geel-zwart) uitgangskanaalinstelling voor een opgegeven categorie. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Wist de uitgangskanaalkleurprofielinstelling voor de standaardcategorie. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Wist de uitgangskanaalkleurprofielinstelling voor een opgegeven categorie. |
| [clearRemapTable()](#clearRemapTable--) | Wist de kleur-herkaarttabel voor de standaardcategorie. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Wist de kleur-herkaarttabel voor een opgegeven categorie. |
| [clearThreshold()](#clearThreshold--) | Wist de drempelwaarde voor de standaardcategorie. |
| [clearThreshold(int type)](#clearThreshold-int-) | Wis de drempelwaarde voor een opgegeven categorie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Stelt de kleur-herkaarttabel in voor de penseelcategorie. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Stelt de kleurensleutel in voor de standaardcategorie. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Stelt de kleurensleutel (transparantiebereik) in voor een opgegeven categorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor een opgegeven categorie. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Stelt de kleurcorrectiematrix in voor de standaardcategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Stelt de kleurcorrectiematrix in voor de standaardcategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Stelt de kleurcorrectiematrix in voor een opgegeven categorie. |
| [setGamma(float gamma)](#setGamma-float-) | Stelt de gammawaarde in voor de standaardcategorie. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Stelt de gammawaarde in voor een opgegeven categorie. |
| [setNoOp()](#setNoOp--) | Schakelt de kleurcorrectie uit voor de standaardcategorie. |
| [setNoOp(int type)](#setNoOp-int-) | Schakelt de kleurcorrectie uit voor een opgegeven categorie. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor de standaardcategorie. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor een opgegeven categorie. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor de standaardcategorie. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor een opgegeven categorie. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Stelt de kleur-herkaarttabel in voor de standaardcategorie. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Stelt de kleur-herkaarttabel in voor een opgegeven categorie. |
| [setThreshold(float threshold)](#setThreshold-float-) | Stelt de drempel (transparantiebereik) in voor de standaardcategorie. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Stelt de drempel (transparantiebereik) in voor een opgegeven categorie. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Stelt de wrap-modus in die wordt gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of bij vormranden. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of bij vormranden. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of bij vormranden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initialiseert een nieuw exemplaar van de  com.aspose.psd.ImageAttributes  klasse.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


De GDI-afbeeldingsattributen.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Wist de kwastkleur-herkaarttabel van dit  com.aspose.psd.ImageAttributes  object.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Wist de kleurensleutel (transparantiebereik) voor de standaardcategorie.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Wist de kleurensleutel (transparantiebereik) voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van **Aspose.Imaging.ColorAdjustType** dat de categorie specificeert waarvoor de kleurensleutel wordt gewist. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Wist de kleurcorrectiematrix voor de standaardcategorie.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Wist de kleurcorrectiematrix voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van **Aspose.Imaging.ColorAdjustType** dat de categorie specificeert waarvoor de kleurcorrectiematrix wordt gewist. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Schakelt gamma-correctie uit voor de standaardcategorie.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Schakelt gamma-correctie uit voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van **Aspose.Imaging.ColorAdjustType** dat de categorie specificeert waarvoor gamma-correctie is uitgeschakeld. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Wist de NoOp-instelling voor de standaardcategorie.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Wist de NoOp-instelling voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de NoOp-instelling wordt gewist. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Wist de CMYK (cyaan-magenta-geel-zwart) uitgangskanaalinstelling voor de standaardcategorie.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Wist de (cyaan-magenta-geel-zwart) uitgangskanaalinstelling voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de outputkanaalinstelling wordt gewist. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Wist de uitgangskanaalkleurprofielinstelling voor de standaardcategorie.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Wist de uitgangskanaalkleurprofielinstelling voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de outputkanaalprofielinstelling wordt gewist. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Wist de kleur-herkaarttabel voor de standaardcategorie.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Wist de kleur-herkaarttabel voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de remap-tabel wordt gewist. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Wist de drempelwaarde voor de standaardcategorie.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Wis de drempelwaarde voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de drempelwaarde wordt gewist. |

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


Stelt de kleur-herkaarttabel in voor de penseelcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Een array van  com.aspose.psd.ColorMap  objecten. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Stelt de kleurensleutel in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | De lage kleurtoetswaarde. |
| colorHigh | [Color](../../com.aspose.psd/color) | De hoge kleurtoetswaarde. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Stelt de kleurensleutel (transparantiebereik) in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | De lage kleurtoetswaarde. |
| colorHigh | [Color](../../com.aspose.psd/color) | De hoge kleurtoetswaarde. |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de kleurtoets wordt ingesteld. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De kleurcorrectiematrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De grijstintcorrectiematrix. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De kleurcorrectiematrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De grijstintcorrectiematrix. |
| vlaggen | int | Een element van  Aspose.Imaging.ColorMatrixFlag  dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleurcorrectie- en grijstintcorrectiematrices. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De kleurcorrectiematrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De grijstintcorrectiematrix. |
| mode | int | Een element van  Aspose.Imaging.ColorMatrixFlag  dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleurcorrectie- en grijstintcorrectiematrices. |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de kleurcorrectie- en grijstintcorrectiematrices worden ingesteld. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Stelt de kleurcorrectiematrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De kleurcorrectiematrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Stelt de kleurcorrectiematrix in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De kleurcorrectiematrix. |
| vlaggen | int | Een element van  Aspose.Imaging.ColorMatrixFlag  dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleurcorrectiematrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Stelt de kleurcorrectiematrix in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | De kleurcorrectiematrix. |
| mode | int | Een element van  Aspose.Imaging.ColorMatrixFlag  dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleurcorrectiematrix. |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor de kleurcorrectiematrix wordt ingesteld. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Stelt de gammawaarde in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gamma | float | De gamma-correctiewaarde. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Stelt de gammawaarde in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gamma | float | De gamma-correctiewaarde. |
| type | int | Een element van de  Aspose.Imaging.ColorAdjustType  enumeratie dat de categorie specificeert waarvoor de gamma-waarde wordt ingesteld. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Schakelt de kleurcorrectie uit voor de standaardcategorie.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Schakelt de kleurcorrectie uit voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor kleurcorrectie wordt uitgeschakeld. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vlaggen | int | Een element van  Aspose.Imaging.ColorChannelFlag  dat het outputkanaal specificeert. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vlaggen | int | Een element van  Aspose.Imaging.ColorChannelFlag  dat het outputkanaal specificeert. |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor het outputkanaal wordt ingesteld. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Stelt het kleurprofielbestand van het uitvoerkanaal in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | De padnaam van een kleurprofielbestand. Als het kleurprofielbestand zich bevindt in de %SystemRoot%\\System32\\Spool\\Drivers\\Color map, kan deze parameter de bestandsnaam zijn. Anders moet deze parameter de volledig gekwalificeerde padnaam zijn. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Stelt het kleurprofielbestand van het uitvoerkanaal in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | De padnaam van een kleurprofielbestand. Als het kleurprofielbestand zich bevindt in de %SystemRoot%\\System32\\Spool\\Drivers\\Color map, kan deze parameter de bestandsnaam zijn. Anders moet deze parameter de volledig gekwalificeerde padnaam zijn. |
| type | int | Een element van  Aspose.Imaging.ColorAdjustType  dat de categorie specificeert waarvoor het outputkanaal kleurprofielbestand wordt ingesteld. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Stelt de kleur-herkaarttabel in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Een array van kleurparen van het type  com.aspose.psd.ColorMap . Elk kleurpaar bevat een bestaande kleur (de eerste waarde) en de kleur waarnaar deze wordt gemapt (de tweede waarde). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Stelt de kleur-herkaarttabel in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Een array van kleurparen van het type  com.aspose.psd.ColorMap . Elk kleurpaar bevat een bestaande kleur (de eerste waarde) en de kleur waarnaar deze wordt gemapt (de tweede waarde). |
| type | int | Een element van Aspose.Imaging.ColorAdjustType dat de categorie specificeert waarvoor de kleur-herkaarttabel is ingesteld. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Stelt de drempel (transparantiebereik) in voor de standaardcategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Een reëel getal dat de drempelwaarde specificeert. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Stelt de drempel (transparantiebereik) in voor een opgegeven categorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Een drempelwaarde van 0.0 tot 1.0 die wordt gebruikt als een breekpunt om kleuren te sorteren die worden toegewezen aan een maximale of een minimale waarde. |
| type | int | Een element van Aspose.Imaging.ColorAdjustType dat de categorie specificeert waarvoor de kleur-drempel is ingesteld. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Stelt de wrap-modus in die wordt gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of op de randen van de vorm. Een textuur wordt over een vorm getegeld om deze op te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | int | Een element van Aspose.Imaging.WrapMode dat specificeert hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te betegelen. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of op de randen van de vorm. Een textuur wordt over een vorm getegeld om deze op te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | int | Een element van Aspose.Imaging.WrapMode dat specificeert hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te betegelen. |
| color | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.ImageAttributes-object dat de kleur van pixels buiten een gerenderde afbeelding specificeert. Deze kleur is zichtbaar als de mode-parameter is ingesteld op WrapMode.Clamp en de bronrechthoek die aan DrawImage wordt doorgegeven groter is dan de afbeelding zelf. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Stelt de wrap-modus en kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm wordt getegeld, of op de randen van de vorm. Een textuur wordt over een vorm getegeld om deze op te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | int | Een element van Aspose.Imaging.WrapMode dat specificeert hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te betegelen. |
| color | [Color](../../com.aspose.psd/color) | Een kleurobject dat de kleur van pixels buiten een gerenderde afbeelding specificeert. Deze kleur is zichtbaar als de mode-parameter is ingesteld op WrapMode.Clamp en de bronrechthoek die aan DrawImage wordt doorgegeven groter is dan de afbeelding zelf. |
| klem | boolean | Deze parameter heeft geen effect. Stel deze in op false. |

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

