---
title: "GifOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les options de création du format de fichier gif."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Les options de création du format de fichier gif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialise une nouvelle instance de la classe  GifOptions. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Initialise une nouvelle instance de la classe  GifOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Clone cette instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Obtient ou définit l'index de couleur d'arrière-plan GIF. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Obtient ou définit la résolution de couleur GIF. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [getFullFrame()](#getFullFrame--) | Obtient une valeur indiquant si [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [getInterlaced()](#getInterlaced--) | Vrai si l'image doit être entrelacée. |
| [getMaxDiff()](#getMaxDiff--) | Obtient ou définit la différence maximale de pixels autorisée. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Les options multipages |
| [getPalette()](#getPalette--) | Obtient ou définit la palette de couleurs. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Obtient ou définit le rapport d'aspect des pixels GIF. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient ou définit le gestionnaire d'événement de progression. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtient ou définit les paramètres de résolution. |
| [getSource()](#getSource--) | Obtient ou définit la source dans laquelle créer l'image. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtient ou définit les options de rasterisation vectorielle. |
| [getXmpData()](#getXmpData--) | Obtient ou définit le conteneur de métadonnées XMP. |
| [hasTrailer()](#hasTrailer--) | Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Obtient ou définit une valeur indiquant si les entrées de la palette sont triées. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Obtient ou définit l'index de couleur d'arrière-plan GIF. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Obtient ou définit la résolution de couleur GIF. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Définit une valeur indiquant si [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Vrai si l'image doit être entrelacée. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Obtient ou définit la différence maximale de pixels autorisée. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Les options multipages |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtient ou définit la palette de couleurs. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtient ou définit une valeur indiquant si les entrées de la palette sont triées. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Obtient ou définit le rapport d'aspect des pixels GIF. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtient ou définit le gestionnaire d'événement de progression. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtient ou définit les paramètres de résolution. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtient ou définit la source dans laquelle créer l'image. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtient ou définit les options de rasterisation vectorielle. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtient ou définit le conteneur de métadonnées XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initialise une nouvelle instance de la classe  GifOptions.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initialise une nouvelle instance de la classe  GifOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | Les options GIF. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Obtient ou définit l'index de couleur d'arrière-plan GIF.

**Returns:**
byte - L'index de couleur d'arrière-plan GIF.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Obtient ou définit la résolution de couleur GIF.

**Returns:**
byte - La résolution de couleur.

Color Resolution - Nombre de bits par couleur primaire disponible dans l'image originale, moins 1. Cette valeur représente la taille de l'ensemble complet de la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image originale disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette originale, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Obtient ou définit une valeur indiquant si la correction de palette est appliquée.

**Returns:**
boolean -  vrai  si la correction de palette est appliquée ; sinon,  faux .

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source seront analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend du temps, cependant l'image de sortie aura la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Vrai si l'image doit être entrelacée.

**Returns:**
booléen
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Obtient ou définit la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée. La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde. Elle fonctionne mieux lorsqu'une perte minime est introduite, et en raison des limites de l'algorithme de compression, des niveaux de perte très élevés n'apporteront pas autant de gain. L'intervalle des valeurs autorisées est [0, 1000].

**Returns:**
int - L'intervalle des valeurs autorisées.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Les options multipages

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient ou définit la palette de couleurs.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Obtient ou définit le rapport d'aspect des pixels GIF.

Pixel Aspect Ratio - Facteur utilisé pour calculer une approximation du rapport d'aspect du pixel dans l'image originale. Si la valeur du champ n'est pas 0, cette approximation du rapport d'aspect est calculée selon la formule : Rapport d'aspect = (Pixel Aspect Ratio + 15) / 64 Le Pixel Aspect Ratio est défini comme le quotient de la largeur du pixel sur sa hauteur. La plage de valeurs dans ce champ permet de spécifier le pixel le plus large de 4:1 au pixel le plus haut de 1:4 par incréments de 1/64. Valeurs : 0 - Aucun renseignement sur le rapport d'aspect n'est fourni. 1..255 - Valeur utilisée dans le calcul.

**Returns:**
byte - Le rapport d'aspect du pixel GIF.
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
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtient ou définit la source dans laquelle créer l'image.

Valeur : la source dans laquelle créer l'image.

**Returns:**
[Source](../../com.aspose.psd/source)
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce.

**Returns:**
boolean -  true  si le GIF possède un trailer ; sinon,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtient ou définit une valeur indiquant si les entrées de la palette sont triées.

**Returns:**
boolean -  true  si les entrées de palette sont triées ; sinon,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Obtient ou définit l'index de couleur d'arrière-plan GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | L'index de couleur d'arrière-plan du GIF. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Obtient ou définit la résolution de couleur GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte | La résolution des couleurs. |

Color Resolution - Nombre de bits par couleur primaire disponibles dans l'image originale, moins 1. Cette valeur représente la taille de l'ensemble complet de la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image originale disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette originale, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Obtient ou définit une valeur indiquant si la correction de palette est appliquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | booléen | true  si la correction de palette est appliquée ; sinon,  false . |

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source seront analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend du temps, cependant l'image de sortie aura la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Vrai si l'image doit être entrelacée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Obtient ou définit la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée. La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde. Elle fonctionne mieux lorsqu'une perte minime est introduite, et en raison des limites de l'algorithme de compression, des niveaux de perte très élevés n'apporteront pas autant de gain. L'intervalle des valeurs autorisées est [0, 1000].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'intervalle des valeurs autorisées. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Les options multipages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtient ou définit la palette de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtient ou définit une valeur indiquant si les entrées de la palette sont triées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true  si les entrées de palette sont triées ; sinon,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Obtient ou définit le rapport d'aspect des pixels GIF.

Pixel Aspect Ratio - Facteur utilisé pour calculer une approximation du rapport d'aspect du pixel dans l'image originale. Si la valeur du champ n'est pas 0, cette approximation du rapport d'aspect est calculée selon la formule : Rapport d'aspect = (Pixel Aspect Ratio + 15) / 64 Le Pixel Aspect Ratio est défini comme le quotient de la largeur du pixel sur sa hauteur. La plage de valeurs dans ce champ permet de spécifier le pixel le plus large de 4:1 au pixel le plus haut de 1:4 par incréments de 1/64. Valeurs : 0 - Aucun renseignement sur le rapport d'aspect n'est fourni. 1..255 - Valeur utilisée dans le calcul.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | Le rapport d'aspect du pixel GIF. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true  si le GIF possède un trailer ; sinon,  false . |

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

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Le conteneur de données XMP. |

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

