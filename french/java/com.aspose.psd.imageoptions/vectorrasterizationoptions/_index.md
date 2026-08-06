---
title: "VectorRasterizationOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les options de rasterisation vectorielle."
type: docs
weight: 29
url: /fr/java/com.aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class VectorRasterizationOptions extends ImageOptionsBase
```

Les options de rasterisation vectorielle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Copie vers. |
| [deepClone()](#deepClone--) | Clone cette instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient une couleur d'arrière-plan. |
| [getBorderX()](#getBorderX--) | Obtient ou définit la bordure X. |
| [getBorderY()](#getBorderY--) | Obtient ou définit la bordure Y. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [getCenterDrawing()](#getCenterDrawing--) | Obtient une valeur indiquant si le dessin est centré. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getDrawColor()](#getDrawColor--) | Obtient une couleur de premier plan. |
| [getFullFrame()](#getFullFrame--) | Obtient une valeur indiquant si [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Les options multipages |
| [getPageHeight()](#getPageHeight--) | Obtient la hauteur de la page. |
| [getPageSize()](#getPageSize--) | Obtient la taille de la page. |
| [getPageWidth()](#getPageWidth--) | Obtient la largeur de la page. |
| [getPalette()](#getPalette--) | Obtient ou définit la palette de couleurs. |
| [getPositioning()](#getPositioning--) | Obtient le positionnement. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient ou définit le gestionnaire d'événement de progression. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtient ou définit les paramètres de résolution. |
| [getSmoothingMode()](#getSmoothingMode--) | Obtient le mode de lissage. |
| [getSource()](#getSource--) | Obtient ou définit la source dans laquelle créer l'image. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Obtient l'indice de rendu du texte. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtient ou définit les options de rasterisation vectorielle. |
| [getXmpData()](#getXmpData--) | Obtient ou définit le conteneur de métadonnées XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Définit une couleur d'arrière-plan. |
| [setBorderX(float value)](#setBorderX-float-) | Obtient ou définit la bordure X. |
| [setBorderY(float value)](#setBorderY-float-) | Obtient ou définit la bordure Y. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Définit une valeur indiquant si le dessin est centré. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | Définit une couleur de premier plan. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Définit une valeur indiquant si [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Les options multipages |
| [setPageHeight(float value)](#setPageHeight-float-) | Définit la hauteur de la page. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | Définit la taille de la page. |
| [setPageWidth(float value)](#setPageWidth-float-) | Définit la largeur de la page. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtient ou définit la palette de couleurs. |
| [setPositioning(int value)](#setPositioning-int-) | Définit le positionnement. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtient ou définit le gestionnaire d'événement de progression. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtient ou définit les paramètres de résolution. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Définit le mode de lissage. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtient ou définit la source dans laquelle créer l'image. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Définit l'indice de rendu du texte. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtient ou définit les options de rasterisation vectorielle. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtient ou définit le conteneur de métadonnées XMP. |
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
| Paramètre | Type | Description |
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


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copie vers.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | Les options de rasterisation vectorielle. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clone cette instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Clone cette instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient une couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Obtient ou définit la bordure X.

**Returns:**
float - La bordure X.
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Obtient ou définit la bordure Y.

**Returns:**
float - La bordure Y.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Obtient une valeur indiquant si le dessin est centré.

**Returns:**
boolean - une valeur indiquant si le dessin est centré.
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


Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police de calque existante dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, on peut utiliser le fragment de code suivant : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valeur : la police de remplacement par défaut.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Obtient une couleur de premier plan.

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Obtient une valeur indiquant si [full frame].

Valeur :  true  si [full frame] ; sinon,  false .

**Returns:**
booléen - une valeur indiquant si [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création.

Valeur :  true  si ignorer après l'événement de création ; sinon,  false .

**Returns:**
booléen
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Les options multipages

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Obtient la hauteur de la page.

**Returns:**
float - la hauteur de la page.
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Obtient la taille de la page.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Obtient la largeur de la page.

**Returns:**
float - la largeur de la page.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient ou définit la palette de couleurs.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Obtient le positionnement.

Valeur : le positionnement.

**Returns:**
int - le positionnement.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtient ou définit le gestionnaire d'événement de progression.

Valeur : Le gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtient ou définit les paramètres de résolution.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Obtient le mode de lissage.

**Returns:**
int - le mode de lissage.
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtient ou définit la source dans laquelle créer l'image.

Valeur : la source dans laquelle créer l'image.

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Obtient l'indice de rendu du texte.

Valeur : l'indice de rendu du texte.

**Returns:**
int - l'indice de rendu du texte.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtient ou définit les options de rasterisation vectorielle.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtient ou définit le conteneur de métadonnées XMP.

Valeur : le conteneur de données XMP.

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


Définit une couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | une couleur d'arrière-plan. |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Obtient ou définit la bordure X.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La bordure X. |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Obtient ou définit la bordure Y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La bordure Y. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Définit une valeur indiquant si le dessin est centré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | une valeur indiquant si le dessin est centré. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police de calque existante dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, on peut utiliser le fragment de code suivant : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valeur : la police de remplacement par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


Définit une couleur de premier plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | une couleur de premier plan. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Définit une valeur indiquant si [full frame].

Valeur :  true  si [full frame] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | une valeur indiquant si [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création.

Valeur :  true  si ignorer après l'événement de création ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Les options multipages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Définit la hauteur de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | la hauteur de la page. |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


Définit la taille de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | la taille de la page. |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Définit la largeur de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | la largeur de la page. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtient ou définit la palette de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Définit le positionnement.

Valeur : le positionnement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le positionnement. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Obtient ou définit le gestionnaire d'événement de progression.

Valeur : Le gestionnaire d'événement de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtient ou définit les paramètres de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Définit le mode de lissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le mode d'anticrénelage. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Obtient ou définit la source dans laquelle créer l'image.

Valeur : la source dans laquelle créer l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Définit l'indice de rendu du texte.

Valeur : l'indice de rendu du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'indice de rendu du texte. |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Obtient ou définit les options de rasterisation vectorielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtient ou définit le conteneur de métadonnées XMP.

Valeur : le conteneur de données XMP.

**Parameters:**
| Paramètre | Type | Description |
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

