---
title: "VectorRasterizationOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De vectorrasterisatie-opties."
type: docs
weight: 29
url: /nl/java/com.aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class VectorRasterizationOptions extends ImageOptionsBase
```

De vectorrasterisatie-opties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Kopieert naar. |
| [deepClone()](#deepClone--) | Kloont deze instantie. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt een achtergrondkleur op. |
| [getBorderX()](#getBorderX--) | Haalt of stelt de rand X in. |
| [getBorderY()](#getBorderY--) | Haalt op of stelt de rand Y in. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getCenterDrawing()](#getCenterDrawing--) | Haalt een waarde op die aangeeft of centreren wordt getekend. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getDrawColor()](#getDrawColor--) | Haalt een voorgrondkleur op. |
| [getFullFrame()](#getFullFrame--) | Haalt een waarde op die aangeeft of [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [getMultiPageOptions()](#getMultiPageOptions--) | De multipage-opties |
| [getPageHeight()](#getPageHeight--) | Haalt de paginahoogte op. |
| [getPageSize()](#getPageSize--) | Haalt de paginagrootte op. |
| [getPageWidth()](#getPageWidth--) | Haalt de paginabreedte op. |
| [getPalette()](#getPalette--) | Haalt of stelt het kleurenpalet in. |
| [getPositioning()](#getPositioning--) | Haalt de positionering op. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt of stelt de voortgang‑eventhandler in. |
| [getResolutionSettings()](#getResolutionSettings--) | Haalt of stelt de resolutie‑instellingen in. |
| [getSmoothingMode()](#getSmoothingMode--) | Haalt de verzachtingsmodus op. |
| [getSource()](#getSource--) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Haalt de tekstrenderingshint op. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [getXmpData()](#getXmpData--) | Haalt of stelt de XMP‑metadatacontainer in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Stelt een achtergrondkleur in. |
| [setBorderX(float value)](#setBorderX-float-) | Haalt of stelt de rand X in. |
| [setBorderY(float value)](#setBorderY-float-) | Haalt op of stelt de rand Y in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Stelt een waarde in die aangeeft of centreren wordt getekend. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | Stelt een voorgrondkleur in. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Stelt een waarde in die aangeeft of [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | De multipage-opties |
| [setPageHeight(float value)](#setPageHeight-float-) | Stelt de paginahoogte in. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | Stelt de paginagrootte in. |
| [setPageWidth(float value)](#setPageWidth-float-) | Stelt de paginabreedte in. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Haalt of stelt het kleurenpalet in. |
| [setPositioning(int value)](#setPositioning-int-) | Stelt de positionering in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Haalt of stelt de voortgang‑eventhandler in. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Haalt of stelt de resolutie‑instellingen in. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Stelt de verzachtingsmodus in. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Stelt de tekstrenderingshint in. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haalt of stelt de XMP‑metadatacontainer in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Kopieert naar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | De vectorrasterisatie-opties. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Kloont deze instantie.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Kloont deze instantie.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
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


Haalt een achtergrondkleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Haalt of stelt de rand X in.

**Returns:**
float - De rand X.
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Haalt op of stelt de rand Y in.

**Returns:**
float - De rand Y.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Haalt een waarde op die aangeeft of centreren wordt getekend.

**Returns:**
boolean - een waarde die aangeeft of centreren wordt getekend.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Haalt of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laagnaamlettertype in het PSD‑bestand niet in het systeem aanwezig is). Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende code‑fragment worden gebruikt: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Waarde: Het standaard vervangingslettertype.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Haalt een voorgrondkleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Haalt een waarde op die aangeeft of [full frame].

Waarde:  true  als [full frame]; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event.

Waarde:  true  als negeren na het aanmaken‑event; anders,  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


De multipage-opties

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Haalt de paginahoogte op.

**Returns:**
float - de paginahoogte.
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Haalt de paginagrootte op.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Haalt de paginabreedte op.

**Returns:**
float - de paginabreedte.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Haalt of stelt het kleurenpalet in.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Haalt de positionering op.

Waarde: De positionering.

**Returns:**
int - de positionering.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Haalt of stelt de voortgang‑eventhandler in.

Waarde: De voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Haalt of stelt de resolutie‑instellingen in.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Haalt de verzachtingsmodus op.

**Returns:**
int - de anti-aliasingmodus.
### getSource() {#getSource--}
```
public final Source getSource()
```


Haalt of stelt de bron in waarin de afbeelding wordt gemaakt.

Waarde: De bron waarin de afbeelding wordt gemaakt.

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Haalt de tekstrenderingshint op.

Waarde: de hint voor tekstweergave.

**Returns:**
int - de hint voor tekstweergave.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Haalt of stelt de XMP‑metadatacontainer in.

Waarde: De XMP‑datacontainer.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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


Stelt een achtergrondkleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | een achtergrondkleur. |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Haalt of stelt de rand X in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De rand X. |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Haalt op of stelt de rand Y in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De rand Y. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Stelt een waarde in die aangeeft of centreren wordt getekend.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of centreren wordt getekend. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Haalt of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laagnaamlettertype in het PSD‑bestand niet in het systeem aanwezig is). Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende code‑fragment worden gebruikt: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Waarde: Het standaard vervangingslettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


Stelt een voorgrondkleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | een voorgrondkleur. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Stelt een waarde in die aangeeft of [full frame].

Waarde:  true  als [full frame]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event.

Waarde:  true  als negeren na het aanmaken‑event; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


De multipage-opties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Stelt de paginahoogte in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | de paginahoogte. |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


Stelt de paginagrootte in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | de paginagrootte. |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Stelt de paginabreedte in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | de paginabreedte. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Haalt of stelt het kleurenpalet in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Stelt de positionering in.

Waarde: De positionering.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de positionering. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Haalt of stelt de voortgang‑eventhandler in.

Waarde: De voortgangs‑eventhandler.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Haalt of stelt de resolutie‑instellingen in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Stelt de verzachtingsmodus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de anti-aliasingmodus. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Haalt of stelt de bron in waarin de afbeelding wordt gemaakt.

Waarde: De bron waarin de afbeelding wordt gemaakt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Stelt de tekstrenderingshint in.

Waarde: de hint voor tekstweergave.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de hint voor tekstweergave. |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Haalt of stelt de XMP‑metadatacontainer in.

Waarde: De XMP‑datacontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

