---
title: "TiffOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les options du format de fichier tiff."
type: docs
weight: 25
url: /fr/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Les options du format de fichier tiff. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de l'image par les paramètres de largeur et de hauteur, il n'est donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut, mais cela ne signifie pas que cette option est définie explicitement comme valeur de balise. Pour vérifier que la balise est présente, utilisez la propriété Tags ou la méthode correspondante IsTagPresent.

AVERTISSEMENT ! ne modifiez jamais les options tiff lors de l'enregistrement, car cela peut entraîner des effets secondaires et des bugs difficiles à détecter. La ligne suivante a été spécialement laissée commentée car elle provoquait une détermination incorrecte du début des données. Les options transmises ne contenaient pas spp (bien que les options ne soient pas correctes dans ce cas, ce scénario provoque néanmoins des erreurs) et la ligne suivante a ajouté les balises +spp et +bpp, et lorsque les options ont été écrites après que les données ont été complètement écrites, elles ont écrasé le début des données pour le codec non compressé !!! Voir TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initialise une nouvelle instance de la classe  TiffOptions. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initialise une nouvelle instance de la classe  TiffOptions. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Initialise une nouvelle instance de la classe  TiffOptions. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la classe  TiffOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Ajoute une nouvelle balise. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Ajoute les balises. |
| [clone()](#clone--) |  |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Clone cette instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Obtient ou définit l'option de stockage alpha. |
| [getArtist()](#getArtist--) | Obtient ou définit l'artiste. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Obtient ou définit la couleur de l'arrière-plan. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient les bits par pixel. |
| [getBitsPerSample()](#getBitsPerSample--) | Obtient les bits par échantillon. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [getByteOrder()](#getByteOrder--) | Obtient ou définit une valeur indiquant l'ordre des octets tiff. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Obtient le cache. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Obtient ou définit la table de couleurs. |
| [getCompressedQuality()](#getCompressedQuality--) | Obtient la qualité de l'image compressée. |
| [getCompression()](#getCompression--) | Obtient la compression. |
| [getCopyright()](#getCopyright--) | Obtient le droit d'auteur. |
| [getDateTime()](#getDateTime--) | Obtient ou définit la date et l'heure. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Obtient ou définit la limite d'allocation mémoire par défaut. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getDocumentName()](#getDocumentName--) | Obtient ou définit le nom du document. |
| [getExifIfd()](#getExifIfd--) | Obtient ou définit le pointeur vers EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Obtient le nombre d'échantillons supplémentaires. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Obtient les valeurs des échantillons supplémentaires. |
| [getFaxT4Options()](#getFaxT4Options--) | Obtient ou définit les options fax t4. |
| [getFileStandard()](#getFileStandard--) | Obtient ou définit la norme du fichier TIFF. |
| [getFillOrder()](#getFillOrder--) | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| [getFullFrame()](#getFullFrame--) | Obtient une valeur indiquant si [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Obtient ou définit les indications de demi-teinte. |
| [getIccProfile()](#getIccProfile--) | Obtient le flux du profil icc. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [getImageDescription()](#getImageDescription--) | Obtient ou définit la description de l'image. |
| [getImageLength()](#getImageLength--) | Obtient ou définit la longueur de l'image. |
| [getImageWidth()](#getImageWidth--) | Obtient ou définit la largeur de l'image. |
| [getInkNames()](#getInkNames--) | Obtient ou définit les noms d'encre. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Obtient ou définit la valeur maximale d'échantillon. |
| [getMinSampleValue()](#getMinSampleValue--) | Obtient ou définit la valeur minimale d'échantillon. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Les options multipages |
| [getOrientation()](#getOrientation--) | Obtient ou définit l'orientation. |
| [getPageName()](#getPageName--) | Obtient ou définit le nom de la page. |
| [getPageNumber()](#getPageNumber--) | Obtient ou définit l'étiquette du numéro de page. |
| [getPalette()](#getPalette--) | Obtient ou définit la palette de couleurs. |
| [getPhotometric()](#getPhotometric--) | Obtient ou définit le photométrique. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtient ou définit la configuration planaire. |
| [getPredictor()](#getPredictor--) | Obtient ou définit le prédicteur pour la compression LZW. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient ou définit le gestionnaire d'événement de progression. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtient ou définit les paramètres de résolution. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtient ou définit l'unité de résolution. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Obtient ou définit le nombre de lignes par bande. |
| [getSampleFormat()](#getSampleFormat--) | Obtient ou définit le format d'échantillon. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtient les échantillons par pixel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Obtient ou définit le fabricant du scanner. |
| [getScannerModel()](#getScannerModel--) | Obtient ou définit le modèle du scanner. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Obtient ou définit la valeur maximale d'échantillon. |
| [getSminSampleValue()](#getSminSampleValue--) | Obtient ou définit la valeur minimale d'échantillon. |
| [getSoftwareType()](#getSoftwareType--) | Obtient ou définit le type de logiciel. |
| [getSource()](#getSource--) | Obtient ou définit la source dans laquelle créer l'image. |
| [getStripByteCounts()](#getStripByteCounts--) | Obtient ou définit le nombre d'octets de bande. |
| [getStripOffsets()](#getStripOffsets--) | Obtient ou définit les décalages de bande. |
| [getSubFileType()](#getSubFileType--) | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Obtient l'instance de la balise par type. |
| [getTags()](#getTags--) | Obtient ou définit les balises. |
| [getTargetPrinter()](#getTargetPrinter--) | Obtient ou définit l'imprimante cible. |
| [getThreshholding()](#getThreshholding--) | Obtient ou définit le seuillage. |
| [getTileByteCounts()](#getTileByteCounts--) | Obtient ou définit le nombre d'octets de tuile. |
| [getTileLength()](#getTileLength--) | Obtient ou définit la longueur de la tuile. |
| [getTileOffsets()](#getTileOffsets--) | Obtient ou définit les décalages de tuile. |
| [getTileWidth()](#getTileWidth--) | Obtient ou définit la largeur de la tuile. |
| [getTotalPages()](#getTotalPages--) | Obtient le nombre total de pages. |
| [getValidTagCount()](#getValidTagCount--) | Obtient le nombre de balises valides. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtient le nombre d'étiquettes valides. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtient ou définit les options de rasterisation vectorielle. |
| [getXPAuthor()](#getXPAuthor--) | Obtient l'auteur de l'image, utilisé par l'Explorateur Windows. |
| [getXPComment()](#getXPComment--) | Obtient le commentaire de l'image, utilisé par l'Explorateur Windows. |
| [getXPKeywords()](#getXPKeywords--) | Obtient le sujet de l'image, utilisé par l'Explorateur Windows. |
| [getXPSubject()](#getXPSubject--) | Obtient les informations sur l'image, utilisées par l'Explorateur Windows. |
| [getXPTitle()](#getXPTitle--) | Obtient les informations sur l'image, utilisées par l'Explorateur Windows. |
| [getXmpData()](#getXmpData--) | Obtient ou définit le conteneur de métadonnées XMP. |
| [getXposition()](#getXposition--) | Obtient ou définit la position x. |
| [getXresolution()](#getXresolution--) | Obtient ou définit la résolution x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Obtient ou définit les YCbCrCoefficients. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Obtient ou définit les facteurs de sous-échantillonnage pour le photométrique YCbCr. |
| [getYposition()](#getYposition--) | Obtient ou définit la position y. |
| [getYresolution()](#getYresolution--) | Obtient ou définit la résolution y. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Obtient une valeur indiquant si les échantillons supplémentaires sont présents. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Détermine si la balise est présente dans les options ou non. |
| [isTiled()](#isTiled--) | Obtient une valeur indiquant si l'image est découpée en tuiles. |
| [isValid()](#isValid--) | Obtient une valeur indiquant si les  TiffOptions  ont été correctement configurés. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Supprime le tag. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Obtient ou définit l'option de stockage alpha. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Obtient ou définit l'artiste. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Obtient ou définit la couleur de l'arrière-plan. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Définit les bits par échantillon. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setByteOrder(int value)](#setByteOrder-int-) | Obtient ou définit une valeur indiquant l'ordre des octets tiff. |
| [setColorMap(int[] value)](#setColorMap-int---) | Obtient ou définit la table de couleurs. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Définit la qualité de l'image compressée. |
| [setCompression(int value)](#setCompression-int-) | Définit la compression. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Définit le droit d'auteur. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Obtient ou définit la date et l'heure. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Obtient ou définit la limite d'allocation mémoire par défaut. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Obtient ou définit le nom du document. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Définit les valeurs des échantillons supplémentaires. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Obtient ou définit les options fax t4. |
| [setFileStandard(int value)](#setFileStandard-int-) | Obtient ou définit la norme du fichier TIFF. |
| [setFillOrder(int value)](#setFillOrder-int-) | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Définit une valeur indiquant si [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Obtient ou définit les indications de demi-teinte. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Définit le flux du profil icc. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Obtient ou définit la description de l'image. |
| [setImageLength(long value)](#setImageLength-long-) | Obtient ou définit la longueur de l'image. |
| [setImageWidth(long value)](#setImageWidth-long-) | Obtient ou définit la largeur de l'image. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Obtient ou définit les noms d'encre. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Obtient ou définit la valeur maximale d'échantillon. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Obtient ou définit la valeur minimale d'échantillon. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Les options multipages |
| [setOrientation(int value)](#setOrientation-int-) | Obtient ou définit l'orientation. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Obtient ou définit le nom de la page. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Obtient ou définit l'étiquette du numéro de page. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtient ou définit la palette de couleurs. |
| [setPhotometric(int value)](#setPhotometric-int-) | Obtient ou définit le photométrique. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Obtient ou définit la configuration planaire. |
| [setPredictor(int value)](#setPredictor-int-) | Obtient ou définit le prédicteur pour la compression LZW. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtient ou définit le gestionnaire d'événement de progression. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtient ou définit les paramètres de résolution. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtient ou définit l'unité de résolution. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Obtient ou définit le nombre de lignes par bande. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Obtient ou définit le format d'échantillon. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Obtient ou définit le fabricant du scanner. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Obtient ou définit le modèle du scanner. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Obtient ou définit la valeur maximale d'échantillon. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Obtient ou définit la valeur minimale d'échantillon. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Obtient ou définit le type de logiciel. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtient ou définit la source dans laquelle créer l'image. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Obtient ou définit le nombre d'octets de bande. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Obtient ou définit les décalages de bande. |
| [setSubFileType(long value)](#setSubFileType-long-) | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Obtient ou définit l'imprimante cible. |
| [setThreshholding(int value)](#setThreshholding-int-) | Obtient ou définit le seuillage. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Obtient ou définit le nombre d'octets de tuile. |
| [setTileLength(long value)](#setTileLength-long-) | Obtient ou définit la longueur de la tuile. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Obtient ou définit les décalages de tuile. |
| [setTileWidth(long value)](#setTileWidth-long-) | Obtient ou définit la largeur de la tuile. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtient ou définit les options de rasterisation vectorielle. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Définit l'auteur de l'image, utilisé par l'Explorateur Windows. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Définit le commentaire sur l'image, utilisé par l'Explorateur Windows. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Définit le sujet de l'image, utilisé par l'Explorateur Windows. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtient ou définit le conteneur de métadonnées XMP. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la position x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtient ou définit les YCbCrCoefficients. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Obtient ou définit les facteurs de sous-échantillonnage pour le photométrique YCbCr. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la position y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution y. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Valide si les options ont une combinaison valide de tags |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Initialise une nouvelle instance de la classe  TiffOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| expectedFormat | int | Le format de fichier TIFF attendu. |
| byteOrder | int | L'ordre des octets du format de fichier tiff à utiliser. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initialise une nouvelle instance de la classe  TiffOptions  . Par défaut, la convention little endian est utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| expectedFormat | int | Le format de fichier TIFF attendu. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initialise une nouvelle instance de la classe  TiffOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Les options à copier. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initialise une nouvelle instance de la classe  TiffOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Les tags avec lesquels initialiser les options. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Ajoute une nouvelle balise.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Le tag à ajouter. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Ajoute les balises.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Les tags à ajouter. |

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Obtient ou définit l'option de stockage alpha. Les options autres que  TiffAlphaStorage.Unspecified  sont utilisées lorsqu'il y a plus de 3  SamplesPerPixel  définis.

**Returns:**
int - L'option de stockage alpha.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtient ou définit l'artiste.

**Returns:**
java.lang.String - L'artiste.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Obtient ou définit la couleur de l'arrière-plan. Utilisé à des fins internes pour stocker la couleur d'arrière-plan de l'image.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient les bits par pixel.

**Returns:**
int - Le nombre de bits par pixel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Obtient les bits par échantillon.

**Returns:**
int[] - La valeur des bits par échantillon.

Lors de la définition de cette valeur, gardez à l'esprit qu'elle définira également la valeur SamplesPerPixel à la longueur du tableau. Ces 2 propriétés sont très étroitement liées, il ne faut donc les définir qu'ensemble uniquement.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Obtient ou définit une valeur indiquant l'ordre des octets tiff.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Obtient le cache.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| balise | int | La balise (qui est de type tableau). |

**Returns:**
long[] - La valeur de la balise.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Obtient ou définit la table de couleurs.

**Returns:**
int[] - La table de couleurs.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Obtient la qualité de l'image compressée. Utilisé avec la compression Jpeg.

**Returns:**
int - qualité de l'image compressée.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtient la compression.

**Returns:**
int - La compression.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtient le droit d'auteur.

**Returns:**
java.lang.String - Le droit d'auteur.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Obtient ou définit la date et l'heure.

**Returns:**
java.lang.String - La date et l'heure.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Obtient ou définit la limite d'allocation mémoire par défaut.

**Returns:**
int - La limite d'allocation mémoire par défaut.
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
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Obtient ou définit le nom du document.

**Returns:**
java.lang.String - Le nom du document.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Obtient ou définit le pointeur vers EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Obtient le nombre d'échantillons supplémentaires.

Valeur : Le nombre d'échantillons supplémentaires.

**Returns:**
long - le nombre d'échantillons supplémentaires.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Obtient les valeurs des échantillons supplémentaires.

Valeur : La valeur des échantillons supplémentaires.

**Returns:**
int[] - les valeurs des échantillons supplémentaires.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Obtient ou définit les options fax t4.

**Returns:**
long - Les options fax t4.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Obtient ou définit la norme du fichier TIFF.

**Returns:**
int - La norme du fichier TIFF.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Obtient ou définit l'ordre de remplissage des bits d'octet.

**Returns:**
int - L'ordre de remplissage des bits d'octet.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Obtient une valeur indiquant si [full frame].

Valeur :  true  si [full frame] ; sinon,  false .

**Returns:**
booléen - une valeur indiquant si [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Obtient ou définit les indications de demi-teinte.

**Returns:**
int[] - Les indications de demi-teinte.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Obtient le flux du profil icc.

**Returns:**
byte[] - Le profil icc.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Obtient ou définit une valeur indiquant s'il faut ignorer après l'événement de création.

Valeur :  true  si ignorer après l'événement de création ; sinon,  false .

**Returns:**
booléen
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Obtient ou définit la description de l'image.

**Returns:**
java.lang.String - La description de l'image.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Obtient ou définit la longueur de l'image.

**Returns:**
long - La longueur de l'image.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Obtient ou définit la largeur de l'image.

**Returns:**
long - La largeur de l'image.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Obtient ou définit les noms d'encre.

**Returns:**
java.lang.String - Les noms d'encre.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Obtient ou définit la valeur maximale d'échantillon.

**Returns:**
int[] - La valeur maximale d'échantillon.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Obtient ou définit la valeur minimale d'échantillon.

**Returns:**
int[] - La valeur d'échantillon minimale.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Les options multipages

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtient ou définit l'orientation.

**Returns:**
int - L'orientation.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Obtient ou définit le nom de la page.

**Returns:**
java.lang.String - Le nom de la page.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Obtient ou définit l'étiquette du numéro de page.

**Returns:**
int[] - L'étiquette du numéro de page.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient ou définit la palette de couleurs.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Obtient ou définit le photométrique.

**Returns:**
int - Le photométrique.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtient ou définit la configuration planaire.

**Returns:**
int - La configuration planaire.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Obtient ou définit le prédicteur pour la compression LZW.

**Returns:**
int - Le type de prédicteur.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés.

**Returns:**
boolean -  true  si les composants doivent être prémultipliés ; sinon,  false .
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
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Obtient ou définit l'unité de résolution.

**Returns:**
int - L'unité de résolution.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Obtient ou définit le nombre de lignes par bande.

**Returns:**
long - Le nombre de lignes par bande.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Obtient ou définit le format d'échantillon.

**Returns:**
int[] - Le format d'échantillon.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtient les échantillons par pixel. Pour modifier la valeur de cette propriété, utilisez le définisseur de propriété  BitsPerSample .

**Returns:**
int - Les échantillons par pixel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Obtient ou définit le fabricant du scanner.

**Returns:**
java.lang.String - Le fabricant du scanner.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Obtient ou définit le modèle du scanner.

**Returns:**
java.lang.String - Le modèle du scanner.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Obtient ou définit la valeur d'échantillon maximale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Returns:**
long[] - La valeur d'échantillon maximale.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Obtient ou définit la valeur d'échantillon minimale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Returns:**
long[] - La valeur d'échantillon minimale.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Obtient ou définit le type de logiciel.

**Returns:**
java.lang.String - Le type de logiciel.
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtient ou définit la source dans laquelle créer l'image.

Valeur : la source dans laquelle créer l'image.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Obtient ou définit le nombre d'octets de bande.

**Returns:**
long[] - Le nombre d'octets de bande.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Obtient ou définit les décalages de bande.

**Returns:**
long[] - Les décalages de bande.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier.

**Returns:**
long - L'indication générale du type de données contenues dans ce sous-fichier.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Obtient l'instance de la balise par type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagKey | int | La clé d'étiquette. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Obtient ou définit les balises.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Les balises.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Obtient ou définit l'imprimante cible.

**Returns:**
java.lang.String - L'imprimante cible.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Obtient ou définit le seuillage.

**Returns:**
int - Le seuillage.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Obtient ou définit le nombre d'octets de tuile.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Obtient ou définit la longueur de la tuile.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Obtient ou définit les décalages de tuile.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Obtient ou définit la largeur de la tuile.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Obtient le nombre total de pages.

**Returns:**
int - Le nombre total de pages.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Obtient le nombre de balises valides. Ce n'est pas le nombre total de balises mais le nombre de balises qui peuvent être conservées.

**Returns:**
int - Le nombre de balises valides.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Obtient le nombre d'étiquettes valides.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Les étiquettes à valider. |

**Returns:**
int - Le nombre d'étiquettes valides.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtient ou définit les options de rasterisation vectorielle.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Obtient l'auteur de l'image, utilisé par l'Explorateur Windows.

Valeur : Auteur de l'image, utilisé par Windows Explorer. Le  XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) est ignoré par Windows Explorer si la balise Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) existe.

**Returns:**
java.lang.String - auteur de l'image, utilisé par Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Obtient le commentaire de l'image, utilisé par l'Explorateur Windows.

Valeur : Commentaire sur l'image, utilisé par Windows Explorer.

**Returns:**
java.lang.String - commentaire sur l'image, utilisé par Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Obtient le sujet de l'image, utilisé par l'Explorateur Windows.

Valeur : Sujet de l'image, utilisé par Windows Explorer.

**Returns:**
java.lang.String - sujet de l'image, utilisé par Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Obtient les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Informations sur l'image, utilisé par Windows Explorer.

**Returns:**
java.lang.String - informations sur l'image, utilisé par Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Obtient les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Informations sur l'image, utilisé par Windows Explorer. Le  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) est ignoré par Windows Explorer si la balise ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) existe.

**Returns:**
java.lang.String - informations sur l'image, utilisé par Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtient ou définit le conteneur de métadonnées XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Obtient ou définit la position x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Obtient ou définit la résolution x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Obtient ou définit les YCbCrCoefficients.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Les coefficients YCbCr.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Obtient ou définit les facteurs de sous-échantillonnage pour le photométrique YCbCr.

**Returns:**
int[] - Les facteurs de sous-échantillonnage pour la photométrie YCbCr.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Obtient ou définit la position y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Obtient ou définit la résolution y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Obtient une valeur indiquant si les échantillons supplémentaires sont présents.

**Returns:**
boolean -  vrai  si les échantillons supplémentaires sont présents ; sinon,  faux .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Détermine si la balise est présente dans les options ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| balise | int | L'identifiant de la balise à vérifier. |

**Returns:**
boolean -  vrai  si la balise est présente ; sinon,  faux .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Obtient une valeur indiquant si l'image est découpée en tuiles.

**Returns:**
boolean -  vrai  si l'image est découpée en tuiles ; sinon,  faux .
### isValid() {#isValid--}
```
public boolean isValid()
```


Obtient une valeur indiquant si les  TiffOptions  ont été correctement configurés. Utilisez la méthode Validate pour trouver la raison de l'échec.

**Returns:**
boolean -  vrai  si les TiffOptions sont correctement configurés ; sinon,  faux .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Supprime le tag.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| balise | int | La balise à supprimer. |

**Returns:**
boolean - vrai si supprimé avec succès
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Obtient ou définit l'option de stockage alpha. Les options autres que  TiffAlphaStorage.Unspecified  sont utilisées lorsqu'il y a plus de 3  SamplesPerPixel  définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'option de stockage alpha. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Obtient ou définit l'artiste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | L'artiste. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Obtient ou définit la couleur de l'arrière-plan. Utilisé à des fins internes pour stocker la couleur d'arrière-plan de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | La couleur de l'arrière-plan. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Définit les bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | La valeur des bits par échantillon. |

Lors de la définition de cette valeur, gardez à l'esprit qu'elle définira également la valeur SamplesPerPixel à la longueur du tableau. Ces 2 propriétés sont très étroitement liées, elles ne peuvent donc être définies qu'ensemble. |

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

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Obtient ou définit une valeur indiquant l'ordre des octets tiff.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Obtient ou définit la table de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La table de couleurs. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Définit la qualité de l'image compressée. Utilisé avec la compression Jpeg.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | qualité de l'image compressée. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Définit la compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La compression. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Définit le droit d'auteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le droit d'auteur. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Obtient ou définit la date et l'heure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La date et l'heure. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Obtient ou définit la limite d'allocation mémoire par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La limite d'allocation mémoire par défaut. |

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

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Obtient ou définit le nom du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le nom du document. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Définit les valeurs des échantillons supplémentaires.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La valeur des échantillons supplémentaires. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Obtient ou définit les options fax t4.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Les options fax t4. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Obtient ou définit la norme du fichier TIFF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La norme de fichier TIFF. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Obtient ou définit l'ordre de remplissage des bits d'octet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'ordre de remplissage des bits d'octet. |

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

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Obtient ou définit les indications de demi-teinte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | Les indications de demi-teinte. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Définit le flux du profil icc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] | Le profil icc. |

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

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Obtient ou définit la description de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La description de l'image. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Obtient ou définit la longueur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La longueur de l'image. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Obtient ou définit la largeur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La largeur de l'image. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Obtient ou définit les noms d'encre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Les noms d'encre. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Obtient ou définit la valeur maximale d'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La valeur maximale de l'échantillon. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Obtient ou définit la valeur minimale d'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La valeur minimale de l'échantillon. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Les options multipages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Obtient ou définit l'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'orientation. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Obtient ou définit le nom de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le nom de la page. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Obtient ou définit l'étiquette du numéro de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La balise du numéro de page. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtient ou définit la palette de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Obtient ou définit le photométrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le photométrique. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Obtient ou définit la configuration planaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La configuration planaire. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Obtient ou définit le prédicteur pour la compression LZW.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le type de prédicteur. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si les composants doivent être prémultipliés ; sinon, false. |

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

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Obtient ou définit l'unité de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'unité de résolution. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Obtient ou définit le nombre de lignes par bande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Le nombre de lignes par bande. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Obtient ou définit le format d'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | Le format d'échantillon. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Obtient ou définit le fabricant du scanner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le fabricant du scanner. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Obtient ou définit le modèle du scanner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le modèle du scanner. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Obtient ou définit la valeur d'échantillon maximale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | La valeur maximale de l'échantillon. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Obtient ou définit la valeur d'échantillon minimale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | La valeur minimale de l'échantillon. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Obtient ou définit le type de logiciel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le type de logiciel. |

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

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Obtient ou définit le nombre d'octets de bande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | Le nombre d'octets par bande. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Obtient ou définit les décalages de bande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | Les décalages de bande. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | L'indication générale du type de données contenues dans ce sous-fichier. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Obtient ou définit les balises.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Les balises. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Obtient ou définit l'imprimante cible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | L'imprimante cible. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Obtient ou définit le seuillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le seuillage. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Obtient ou définit le nombre d'octets de tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Obtient ou définit la longueur de la tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Obtient ou définit les décalages de tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Obtient ou définit la largeur de la tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Obtient ou définit les options de rasterisation vectorielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Définit l'auteur de l'image, utilisé par l'Explorateur Windows.

Valeur : Auteur de l'image, utilisé par Windows Explorer. Le  XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) est ignoré par Windows Explorer si la balise Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) existe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | auteur de l'image, utilisé par Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Définit le commentaire sur l'image, utilisé par l'Explorateur Windows.

Valeur : Commentaire sur l'image, utilisé par Windows Explorer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | commentaire sur l'image, utilisé par Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Définit le sujet de l'image, utilisé par l'Explorateur Windows.

Valeur : Sujet de l'image, utilisé par Windows Explorer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | sujet de l'image, utilisé par Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Définit les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Informations sur l'image, utilisé par Windows Explorer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | information sur l'image, utilisée par Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Définit les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Information sur l'image, utilisée par Windows Explorer. Le  XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) est ignoré par Windows Explorer si la balise ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) existe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | information sur l'image, utilisée par Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtient ou définit le conteneur de métadonnées XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Le conteneur de données XMP. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Obtient ou définit la position x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La position x. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Obtient ou définit la résolution x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La résolution x. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Obtient ou définit les YCbCrCoefficients.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Les coefficients YCbCr. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Obtient ou définit les facteurs de sous-échantillonnage pour le photométrique YCbCr.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | Les facteurs de sous-échantillonnage pour le photométrique YCbCr. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Obtient ou définit la position y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La position y. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Obtient ou définit la résolution y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La résolution y. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


Valide si les options ont une combinaison valide de tags

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

