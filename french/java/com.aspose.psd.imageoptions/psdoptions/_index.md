---
title: "PsdOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les options de création du format de fichier psd."
type: docs
weight: 21
url: /fr/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Les options de création du format de fichier psd.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Initialise une nouvelle instance de la classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Initialise une nouvelle instance de la classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Initialise une nouvelle instance de la classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Clone cette instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Obtient ou définit la couleur d'arrière-plan. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Obtient ou définit le nombre de bits par canal de couleur. |
| [getChannelsCount()](#getChannelsCount--) | Obtient ou définit le nombre de canaux de couleur. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Obtient ou définit le mode couleur PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | Obtient ou définit la méthode de compression PSD. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getFullFrame()](#getFullFrame--) | Obtient une valeur indiquant si [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Les options multipages |
| [getPalette()](#getPalette--) | Obtient ou définit la palette de couleurs. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient ou définit le gestionnaire d'événement de progression. |
| [getPsdVersion()](#getPsdVersion--) | Obtient ou définit la version du format de fichier. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Obtient ou définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après le traitement (principalement lié aux calques de texte avec polices manquantes). |
| [getResolutionSettings()](#getResolutionSettings--) | Obtient ou définit les paramètres de résolution. |
| [getResources()](#getResources--) | Obtient ou définit les ressources PSD. |
| [getSource()](#getSource--) | Obtient ou définit la source dans laquelle créer l'image. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Obtient ou définit une valeur indiquant si [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtient ou définit les options de rasterisation vectorielle. |
| [getVersion()](#getVersion--) | Obtient ou définit la version du fichier PSD. |
| [getXmpData()](#getXmpData--) | Obtenir ou définir le conteneur de données XMP |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Indique si la propriété ColorMode a été assignée. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Obtient ou définit la couleur d'arrière-plan. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Obtient ou définit le nombre de bits par canal de couleur. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Obtient ou définit le nombre de canaux de couleur. |
| [setColorMode(short value)](#setColorMode-short-) | Obtient ou définit le mode couleur PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Obtient ou définit la méthode de compression PSD. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Définit une valeur indiquant si [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Les options multipages |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtient ou définit la palette de couleurs. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtient ou définit le gestionnaire d'événement de progression. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Obtient ou définit la version du format de fichier. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Obtient ou définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après le traitement (principalement lié aux calques de texte avec polices manquantes). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtient ou définit les paramètres de résolution. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Obtient ou définit les ressources PSD. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtient ou définit la source dans laquelle créer l'image. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Obtient ou définit une valeur indiquant si [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtient ou définit les options de rasterisation vectorielle. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit la version du fichier PSD. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtenir ou définir le conteneur de données XMP |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Initialise une nouvelle instance de la classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Initialise une nouvelle instance de la classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Les options. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Initialise une nouvelle instance de la classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | L'image. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Obtient ou définit la couleur d'arrière-plan. Elle peut être vue sous les objets transparents.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Obtient ou définit le nombre de bits par canal de couleur.

Valeur : Le nombre de bits par canal de couleur.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Obtient ou définit le nombre de canaux de couleur.

Valeur : Le nombre de canaux de couleur.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Obtient ou définit le mode couleur PSD.

Valeur : le mode couleur.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Obtient ou définit la méthode de compression PSD.

Valeur: La méthode de compression.

**Returns:**
short
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
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient ou définit la palette de couleurs.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtient ou définit le gestionnaire d'événement de progression.

Valeur : Le gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Obtient ou définit la version du format de fichier. Elle peut être PSD ou PSB.

Valeur : La version du format de fichier.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Obtient ou définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD. Veuillez noter que le rendu des calques de texte dans la mise en page finale n'est pas pris en charge sur la plateforme Compact Framework.

Valeur :  true  si [refresh image preview data] ; sinon,  false .

**Returns:**
booléen
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après le traitement (principalement lié aux calques de texte avec polices manquantes). Après avoir utilisé cette option, l'utilisateur doit effectuer les étapes suivantes dans le fichier ouvert avec Photoshop : Menu \"Texte\" → \"Traiter les polices manquantes\". Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner des modifications de la mise en page finale.

Valeur :  true  si [remove global text engine resource] ; sinon,  false .

**Returns:**
booléen
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtient ou définit les paramètres de résolution.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Obtient ou définit les ressources PSD. Si la valeur : NULL - alors enregistrer les ImageResources d'origine (comportement par défaut) Non vide - alors enregistrer les ressources passées à cette propriété + [required resources] Vide - alors seules les [required resources] seront enregistrées. Ressources requises : ResolutionInfoResource, XmpResource.

Valeur : Les ressources PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtient ou définit la source dans laquelle créer l'image.

Valeur : la source dans laquelle créer l'image.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Obtient ou définit une valeur indiquant si [update metadata]. Si la valeur est vraie, les métadonnées seront mises à jour lors de l'enregistrement de l'image.

Valeur :  true  si [update metadata] ; sinon,  false .

**Returns:**
booléen
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtient ou définit les options de rasterisation vectorielle.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtient ou définit la version du fichier PSD.

Valeur : La version du fichier PSD.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtenir ou définir le conteneur de données XMP

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


Indique si la propriété ColorMode a été assignée.

**Returns:**
booléen
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


Obtient ou définit la couleur d'arrière-plan. Elle peut être vue sous les objets transparents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Obtient ou définit le nombre de bits par canal de couleur.

Valeur : Le nombre de bits par canal de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Obtient ou définit le nombre de canaux de couleur.

Valeur : Le nombre de canaux de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Obtient ou définit le mode couleur PSD.

Valeur : le mode couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Obtient ou définit la méthode de compression PSD.

Valeur: La méthode de compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtient ou définit la palette de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Obtient ou définit la version du format de fichier. Elle peut être PSD ou PSB.

Valeur : La version du format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Obtient ou définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD. Veuillez noter que le rendu des calques de texte dans la mise en page finale n'est pas pris en charge sur la plateforme Compact Framework.

Valeur :  true  si [refresh image preview data] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après le traitement (principalement lié aux calques de texte avec polices manquantes). Après avoir utilisé cette option, l'utilisateur doit effectuer les étapes suivantes dans le fichier ouvert avec Photoshop : Menu \"Texte\" → \"Traiter les polices manquantes\". Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner des modifications de la mise en page finale.

Valeur :  true  si [remove global text engine resource] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtient ou définit les paramètres de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Obtient ou définit les ressources PSD. Si la valeur : NULL - alors enregistrer les ImageResources d'origine (comportement par défaut) Non vide - alors enregistrer les ressources passées à cette propriété + [required resources] Vide - alors seules les [required resources] seront enregistrées. Ressources requises : ResolutionInfoResource, XmpResource.

Valeur : Les ressources PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Obtient ou définit une valeur indiquant si [update metadata]. Si la valeur est vraie, les métadonnées seront mises à jour lors de l'enregistrement de l'image.

Valeur :  true  si [update metadata] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Obtient ou définit les options de rasterisation vectorielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Obtient ou définit la version du fichier PSD.

Valeur : La version du fichier PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtenir ou définir le conteneur de données XMP

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

