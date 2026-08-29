---
title: "TiffOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De TIFF‑bestandsformaatopties."
type: docs
weight: 25
url: /nl/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

De tiff‑bestandsformaatopties. Merk op dat breedte‑ en hoogte‑tags worden overschreven bij het maken van de afbeelding door de breedte‑ en hoogte‑parameters, zodat het niet nodig is ze direct op te geven. Merk ook op dat veel opties een standaardwaarde retourneren, maar dat betekent niet dat deze optie expliciet als een tag‑waarde is ingesteld. Om te controleren of de tag aanwezig is, gebruik de Tags‑eigenschap of de bijbehorende IsTagPresent‑methode.

WAARSCHUWING! wijzig tiff‑opties nooit tijdens het opslaan, omdat dit bijwerkingen kan veroorzaken en moeilijk te vinden bugs. De volgende regel is speciaal gecommentarieerd omdat deze een onjuiste bepaling van het begin van de gegevens veroorzaakte. De meegegeven opties bevatten geen spp (hoewel de opties in zo'n geval niet correct zijn, veroorzaakt dit scenario toch fouten) en de volgende regel voegde de +spp‑tag en +bpp‑tag toe, en wanneer de opties werden geschreven nadat de gegevens volledig waren geschreven, hebben ze het begin van de gegevens voor de ongecomprimeerde codec overschreven!!! Zie TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initialiseert een nieuw exemplaar van de  TiffOptions  klasse. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initialiseert een nieuw exemplaar van de  TiffOptions  klasse. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Initialiseert een nieuw exemplaar van de  TiffOptions  klasse. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialiseert een nieuw exemplaar van de  TiffOptions  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Voegt een nieuwe tag toe. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Voegt de tags toe. |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Kloont deze instantie. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Haalt op of stelt de alfa‑opslagoptie in. |
| [getArtist()](#getArtist--) | Haalt op of stelt de artiest in. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Haalt op of stelt de kleur van de achtergrond in. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Haalt het aantal bits per pixel op. |
| [getBitsPerSample()](#getBitsPerSample--) | Haalt het aantal bits per monster op. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getByteOrder()](#getByteOrder--) | Haalt op of stelt een waarde in die de tiff‑bytevolgorde aangeeft. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Haalt de cache op. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Haalt de kleurenkaart op of stelt deze in. |
| [getCompressedQuality()](#getCompressedQuality--) | Haalt de kwaliteit van de gecomprimeerde afbeelding op. |
| [getCompression()](#getCompression--) | Haalt de compressie op. |
| [getCopyright()](#getCopyright--) | Haalt het copyright op. |
| [getDateTime()](#getDateTime--) | Haalt de datum en tijd op of stelt deze in. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Haalt de standaard geheugenallocatielimiet op of stelt deze in. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getDocumentName()](#getDocumentName--) | Haalt de naam van het document op of stelt deze in. |
| [getExifIfd()](#getExifIfd--) | Haalt de pointer naar EXIF IFD op of stelt deze in. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Haalt het aantal extra monsters op. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Haalt de waarden van extra monsters op. |
| [getFaxT4Options()](#getFaxT4Options--) | Haalt de fax t4-opties op of stelt deze in. |
| [getFileStandard()](#getFileStandard--) | Haalt de TIFF-bestandsstandaard op of stelt deze in. |
| [getFillOrder()](#getFillOrder--) | Haalt de vulvolgorde van bytebits op of stelt deze in. |
| [getFullFrame()](#getFullFrame--) | Haalt een waarde op die aangeeft of [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Haalt de halftoonhints op of stelt deze in. |
| [getIccProfile()](#getIccProfile--) | Haalt de ICC-profielstroom op. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [getImageDescription()](#getImageDescription--) | Haalt op of stelt de afbeeldingsbeschrijving in. |
| [getImageLength()](#getImageLength--) | Haalt op of stelt de afbeeldingslengte in. |
| [getImageWidth()](#getImageWidth--) | Haalt op of stelt de afbeeldingsbreedte in. |
| [getInkNames()](#getInkNames--) | Haalt de inkt namen op of stelt deze in. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Haalt de maximale monsterwaarde op of stelt deze in. |
| [getMinSampleValue()](#getMinSampleValue--) | Haalt de minimale monsterwaarde op of stelt deze in. |
| [getMultiPageOptions()](#getMultiPageOptions--) | De multipage-opties |
| [getOrientation()](#getOrientation--) | Haalt op of stelt de oriëntatie in. |
| [getPageName()](#getPageName--) | Haalt de paginanaam op of stelt deze in. |
| [getPageNumber()](#getPageNumber--) | Haalt de paginanummer-tag op of stelt deze in. |
| [getPalette()](#getPalette--) | Haalt of stelt het kleurenpalet in. |
| [getPhotometric()](#getPhotometric--) | Haalt de fotometrie op of stelt deze in. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Haalt op of stelt de planar configuratie in. |
| [getPredictor()](#getPredictor--) | Haalt de predictor voor LZW-compressie op of stelt deze in. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Haalt een waarde op die aangeeft of componenten voorvermenigvuldigd moeten worden, of stelt deze in. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt of stelt de voortgang‑eventhandler in. |
| [getResolutionSettings()](#getResolutionSettings--) | Haalt of stelt de resolutie‑instellingen in. |
| [getResolutionUnit()](#getResolutionUnit--) | Haalt op of stelt de resolutie-eenheid in. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Haalt het aantal rijen per strook op of stelt dit in. |
| [getSampleFormat()](#getSampleFormat--) | Haalt het monsterformaat op of stelt dit in. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Haalt de monsters per pixel op. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Haalt de scannerfabrikant op of stelt deze in. |
| [getScannerModel()](#getScannerModel--) | Haalt het scannermodel op of stelt dit in. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Haalt de maximale monsterwaarde op of stelt deze in. |
| [getSminSampleValue()](#getSminSampleValue--) | Haalt de minimale monsterwaarde op of stelt deze in. |
| [getSoftwareType()](#getSoftwareType--) | Haalt het softwaretype op of stelt dit in. |
| [getSource()](#getSource--) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [getStripByteCounts()](#getStripByteCounts--) | Haalt de strip-byte-aantallen op of stelt deze in. |
| [getStripOffsets()](#getStripOffsets--) | Haalt de stripoffsets op of stelt deze in. |
| [getSubFileType()](#getSubFileType--) | Haalt een algemene indicatie van het type gegevens dat in dit subbestand zit op of stelt deze in. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Haalt de instantie van de tag op basis van type. |
| [getTags()](#getTags--) | Haalt de tags op of stelt ze in. |
| [getTargetPrinter()](#getTargetPrinter--) | Haalt de doelprinter op of stelt deze in. |
| [getThreshholding()](#getThreshholding--) | Haalt de drempelwaarde op of stelt deze in. |
| [getTileByteCounts()](#getTileByteCounts--) | Haalt de tegel-byte-aantallen op of stelt deze in. |
| [getTileLength()](#getTileLength--) | Haalt de tegellengte op of stelt deze in. |
| [getTileOffsets()](#getTileOffsets--) | Haalt de tegeloffsets op of stelt deze in. |
| [getTileWidth()](#getTileWidth--) | Haalt de tegelbreedte op of stelt deze in. |
| [getTotalPages()](#getTotalPages--) | Haalt het totale aantal pagina's op. |
| [getValidTagCount()](#getValidTagCount--) | Haalt het geldige tag-aantal op. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Haalt het aantal geldige tags op. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [getXPAuthor()](#getXPAuthor--) | Haalt de afbeeldingsauteur op, die wordt gebruikt door Windows Verkenner. |
| [getXPComment()](#getXPComment--) | Haalt de opmerking bij de afbeelding op, die wordt gebruikt door Windows Verkenner. |
| [getXPKeywords()](#getXPKeywords--) | Haalt het onderwerp van de afbeelding op, die wordt gebruikt door Windows Verkenner. |
| [getXPSubject()](#getXPSubject--) | Haalt informatie over de afbeelding op, die wordt gebruikt door Windows Verkenner. |
| [getXPTitle()](#getXPTitle--) | Haalt informatie over de afbeelding op, die wordt gebruikt door Windows Verkenner. |
| [getXmpData()](#getXmpData--) | Haalt of stelt de XMP‑metadatacontainer in. |
| [getXposition()](#getXposition--) | Haalt de x-positie op of stelt deze in. |
| [getXresolution()](#getXresolution--) | Haalt op of stelt de x-resolutie in. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Haalt de YCbCrCoefficients op of stelt deze in. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Haalt de subsamplingfactoren voor YCbCr-fotometrisch op of stelt deze in. |
| [getYposition()](#getYposition--) | Haalt de y-positie op of stelt deze in. |
| [getYresolution()](#getYresolution--) | Haalt of stelt de y-resolutie in. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Haalt een waarde op die aangeeft of de extra samples aanwezig is. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Bepaalt of de tag al dan niet aanwezig is in de opties. |
| [isTiled()](#isTiled--) | Haalt een waarde op die aangeeft of de afbeelding getegeld is. |
| [isValid()](#isValid--) | Haalt een waarde op die aangeeft of de TiffOptions correct zijn geconfigureerd. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Verwijdert de tag. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Haalt op of stelt de alfa‑opslagoptie in. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Haalt op of stelt de artiest in. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Haalt op of stelt de kleur van de achtergrond in. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Stelt het aantal bits per sample in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setByteOrder(int value)](#setByteOrder-int-) | Haalt op of stelt een waarde in die de tiff‑bytevolgorde aangeeft. |
| [setColorMap(int[] value)](#setColorMap-int---) | Haalt de kleurenkaart op of stelt deze in. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Stelt de kwaliteit van de gecomprimeerde afbeelding in. |
| [setCompression(int value)](#setCompression-int-) | Stelt de compressie in. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Stelt het copyright in. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Haalt de datum en tijd op of stelt deze in. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Haalt de standaard geheugenallocatielimiet op of stelt deze in. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Haalt de naam van het document op of stelt deze in. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Stelt de waarden van de extra samples in. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Haalt de fax t4-opties op of stelt deze in. |
| [setFileStandard(int value)](#setFileStandard-int-) | Haalt de TIFF-bestandsstandaard op of stelt deze in. |
| [setFillOrder(int value)](#setFillOrder-int-) | Haalt de vulvolgorde van bytebits op of stelt deze in. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Stelt een waarde in die aangeeft of [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Haalt de halftoonhints op of stelt deze in. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Stelt de ICC-profielstroom in. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Haalt op of stelt de afbeeldingsbeschrijving in. |
| [setImageLength(long value)](#setImageLength-long-) | Haalt op of stelt de afbeeldingslengte in. |
| [setImageWidth(long value)](#setImageWidth-long-) | Haalt op of stelt de afbeeldingsbreedte in. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Haalt de inkt namen op of stelt deze in. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Haalt de maximale monsterwaarde op of stelt deze in. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Haalt de minimale monsterwaarde op of stelt deze in. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | De multipage-opties |
| [setOrientation(int value)](#setOrientation-int-) | Haalt op of stelt de oriëntatie in. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Haalt de paginanaam op of stelt deze in. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Haalt de paginanummer-tag op of stelt deze in. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Haalt of stelt het kleurenpalet in. |
| [setPhotometric(int value)](#setPhotometric-int-) | Haalt de fotometrie op of stelt deze in. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Haalt op of stelt de planar configuratie in. |
| [setPredictor(int value)](#setPredictor-int-) | Haalt de predictor voor LZW-compressie op of stelt deze in. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Haalt een waarde op die aangeeft of componenten voorvermenigvuldigd moeten worden, of stelt deze in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Haalt of stelt de voortgang‑eventhandler in. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Haalt of stelt de resolutie‑instellingen in. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Haalt op of stelt de resolutie-eenheid in. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Haalt het aantal rijen per strook op of stelt dit in. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Haalt het monsterformaat op of stelt dit in. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Haalt de scannerfabrikant op of stelt deze in. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Haalt het scannermodel op of stelt dit in. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Haalt de maximale monsterwaarde op of stelt deze in. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Haalt de minimale monsterwaarde op of stelt deze in. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Haalt het softwaretype op of stelt dit in. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Haalt de strip-byte-aantallen op of stelt deze in. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Haalt de stripoffsets op of stelt deze in. |
| [setSubFileType(long value)](#setSubFileType-long-) | Haalt een algemene indicatie van het type gegevens dat in dit subbestand zit op of stelt deze in. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Haalt de tags op of stelt ze in. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Haalt de doelprinter op of stelt deze in. |
| [setThreshholding(int value)](#setThreshholding-int-) | Haalt de drempelwaarde op of stelt deze in. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Haalt de tegel-byte-aantallen op of stelt deze in. |
| [setTileLength(long value)](#setTileLength-long-) | Haalt de tegellengte op of stelt deze in. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Haalt de tegeloffsets op of stelt deze in. |
| [setTileWidth(long value)](#setTileWidth-long-) | Haalt de tegelbreedte op of stelt deze in. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Stelt de auteur van de afbeelding in, die door Windows Verkenner wordt gebruikt. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Stelt een opmerking op de afbeelding in, die door Windows Verkenner wordt gebruikt. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Stelt het onderwerp van de afbeelding in, die door Windows Verkenner wordt gebruikt. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Stelt informatie over de afbeelding in, die door Windows Verkenner wordt gebruikt. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Stelt informatie over de afbeelding in, die door Windows Verkenner wordt gebruikt. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haalt of stelt de XMP‑metadatacontainer in. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt de x-positie op of stelt deze in. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt op of stelt de x-resolutie in. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Haalt de YCbCrCoefficients op of stelt deze in. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Haalt de subsamplingfactoren voor YCbCr-fotometrisch op of stelt deze in. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt de y-positie op of stelt deze in. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Haalt of stelt de y-resolutie in. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Valideert of de opties een geldige combinatie van tags hebben |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Initialiseert een nieuw exemplaar van de  TiffOptions  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expectedFormat | int | Het verwachte tiff-bestandsformaat. |
| byteOrder | int | De bytevolgorde van het TIFF-bestandsformaat die moet worden gebruikt. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initialiseert een nieuw exemplaar van de TiffOptions-klasse. Standaard wordt de little-endian conventie gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expectedFormat | int | Het verwachte tiff-bestandsformaat. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initialiseert een nieuw exemplaar van de  TiffOptions  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | De opties waaruit gekopieerd moet worden. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initialiseert een nieuw exemplaar van de  TiffOptions  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De tags waarmee de opties geïnitialiseerd worden. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Voegt een nieuwe tag toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De toe te voegen tag. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Voegt de tags toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De toe te voegen tags. |

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Haalt de alpha-opslagoptie op of stelt deze in. Opties anders dan TiffAlphaStorage.Unspecified worden gebruikt wanneer er meer dan 3 SamplesPerPixel zijn gedefinieerd.

**Returns:**
int - De alpha opslagoptie.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Haalt op of stelt de artiest in.

**Returns:**
java.lang.String - De artiest.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Haalt of stelt de kleur van de achtergrond in. Wordt voor interne doeleinden gebruikt om de achtergrondkleur van de afbeelding op te slaan.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Haalt het aantal bits per pixel op.

**Returns:**
int - Het aantal bits per pixel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Haalt het aantal bits per monster op.

**Returns:**
int[] - De bits per monsterwaarde.

Bij het instellen van deze waarde moet u rekening houden met het feit dat ook de SamplesPerPixel-waarde op de arraylengte wordt gezet. Deze twee eigenschappen zijn zeer nauw met elkaar gekoppeld, dus kunnen alleen samen worden ingesteld.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Haalt op of stelt een waarde in die de tiff‑bytevolgorde aangeeft.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Haalt de cache op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tag | int | De tag (die een arraytype is). |

**Returns:**
long[] - De tagwaarde.
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


Haalt de kleurenkaart op of stelt deze in.

**Returns:**
int[] - De kleurenkaart.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Haalt de gecomprimeerde beeldkwaliteit op. Wordt gebruikt met de Jpeg-compressie.

**Returns:**
int - Gecomprimeerde beeldkwaliteit.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Haalt de compressie op.

**Returns:**
int - De compressie.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Haalt het copyright op.

**Returns:**
java.lang.String - Het copyright.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Haalt de datum en tijd op of stelt deze in.

**Returns:**
java.lang.String - De datum en tijd.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Haalt de standaard geheugenallocatielimiet op of stelt deze in.

**Returns:**
int - De standaard geheugenallocatielimiet.
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
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Haalt de naam van het document op of stelt deze in.

**Returns:**
java.lang.String - De naam van het document.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Haalt de pointer naar EXIF IFD op of stelt deze in.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Haalt het aantal extra monsters op.

Waarde: Het extra monsteraantal.

**Returns:**
long - Het extra monsteraantal.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Haalt de waarden van extra monsters op.

Waarde: De extra monsterswaarde.

**Returns:**
int[] - De extra monsterswaarden.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Haalt de fax t4-opties op of stelt deze in.

**Returns:**
long - De fax t4-opties.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Haalt de TIFF-bestandsstandaard op of stelt deze in.

**Returns:**
int - De TIFF-bestandsstandaard.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Haalt de vulvolgorde van bytebits op of stelt deze in.

**Returns:**
int - De volgorde van bytebits.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Haalt een waarde op die aangeeft of [full frame].

Waarde:  true  als [full frame]; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Haalt de halftoonhints op of stelt deze in.

**Returns:**
int[] - De halftoonhints.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Haalt de ICC-profielstroom op.

**Returns:**
byte[] - Het icc-profiel.
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


Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event.

Waarde:  true  als negeren na het aanmaken‑event; anders,  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Haalt op of stelt de afbeeldingsbeschrijving in.

**Returns:**
java.lang.String - De afbeeldingbeschrijving.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Haalt op of stelt de afbeeldingslengte in.

**Returns:**
long - De afbeeldingslengte.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Haalt op of stelt de afbeeldingsbreedte in.

**Returns:**
long - De afbeeldingsbreedte.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Haalt de inkt namen op of stelt deze in.

**Returns:**
java.lang.String - De inktnamen.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Haalt de maximale monsterwaarde op of stelt deze in.

**Returns:**
int[] - De maximale monsterwaarde.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Haalt de minimale monsterwaarde op of stelt deze in.

**Returns:**
int[] - De minimale monsterwaarde.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


De multipage-opties

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Haalt op of stelt de oriëntatie in.

**Returns:**
int - De oriëntatie.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Haalt de paginanaam op of stelt deze in.

**Returns:**
java.lang.String - De paginanaam.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Haalt de paginanummer-tag op of stelt deze in.

**Returns:**
int[] - Het paginanummer tag.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Haalt of stelt het kleurenpalet in.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Haalt de fotometrie op of stelt deze in.

**Returns:**
int - De fotometrische.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Haalt op of stelt de planar configuratie in.

**Returns:**
int - De planaire configuratie.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Haalt de predictor voor LZW-compressie op of stelt deze in.

**Returns:**
int - Het voorspeller type.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Haalt een waarde op die aangeeft of componenten voorvermenigvuldigd moeten worden, of stelt deze in.

**Returns:**
boolean -  true  als componenten moeten worden voorvermenigvuldigd; anders,  false .
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
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Haalt op of stelt de resolutie-eenheid in.

**Returns:**
int - De resolutie-eenheid.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Haalt het aantal rijen per strook op of stelt dit in.

**Returns:**
long - Het aantal rijen per strook.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Haalt het monsterformaat op of stelt dit in.

**Returns:**
int[] - Het monsterformaat.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Haalt de monsters per pixel op. Om deze eigenschapswaarde te wijzigen, gebruik de  BitsPerSample  eigenschapsetter.

**Returns:**
int - De monsters per pixel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Haalt de scannerfabrikant op of stelt deze in.

**Returns:**
java.lang.String - De scannerfabrikant.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Haalt het scannermodel op of stelt dit in.

**Returns:**
java.lang.String - Het scanner model.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Haalt of stelt de maximale monsterwaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de monstergegevens (Byte, Short of Long type).

**Returns:**
long[] - De maximale monsterwaarde.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Haalt of stelt de minimale monsterwaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de monstergegevens (Byte, Short of Long type).

**Returns:**
long[] - De minimale monsterwaarde.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Haalt het softwaretype op of stelt dit in.

**Returns:**
java.lang.String - Het softwaretype.
### getSource() {#getSource--}
```
public final Source getSource()
```


Haalt of stelt de bron in waarin de afbeelding wordt gemaakt.

Waarde: De bron waarin de afbeelding wordt gemaakt.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Haalt de strip-byte-aantallen op of stelt deze in.

**Returns:**
long[] - De strook byte tellingen.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Haalt de stripoffsets op of stelt deze in.

**Returns:**
long[] - De stripoffsets.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Haalt een algemene indicatie van het type gegevens dat in dit subbestand zit op of stelt deze in.

**Returns:**
long - De algemene indicatie van het type gegevens dat in dit subbestand zit.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Haalt de instantie van de tag op basis van type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tagKey | int | De tag‑sleutel. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Haalt de tags op of stelt ze in.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - De tags.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Haalt de doelprinter op of stelt deze in.

**Returns:**
java.lang.String - De doelprinter.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Haalt de drempelwaarde op of stelt deze in.

**Returns:**
int - De drempelwaarde.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Haalt de tegel-byte-aantallen op of stelt deze in.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Haalt de tegellengte op of stelt deze in.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Haalt de tegeloffsets op of stelt deze in.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Haalt de tegelbreedte op of stelt deze in.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Haalt het totale aantal pagina's op.

**Returns:**
int - Het totale aantal pagina's.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Haalt het geldige tag‑aantal op. Dit is niet het totale aantal tags, maar het aantal tags dat bewaard kan worden.

**Returns:**
int - Het geldige tag‑aantal.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Haalt het aantal geldige tags op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De tags om te valideren. |

**Returns:**
int - Het aantal geldige tags.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Haalt de afbeeldingsauteur op, die wordt gebruikt door Windows Verkenner.

Waarde: Afbeeldingsauteur, gebruikt door Windows Verkenner. De  XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) wordt genegeerd door Windows Verkenner als de  Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) tag bestaat.

**Returns:**
java.lang.String - afbeeldingsauteur, die wordt gebruikt door Windows Verkenner.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Haalt de opmerking bij de afbeelding op, die wordt gebruikt door Windows Verkenner.

Waarde: Opmerking bij afbeelding, gebruikt door Windows Verkenner.

**Returns:**
java.lang.String - opmerking bij afbeelding, die wordt gebruikt door Windows Verkenner.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Haalt het onderwerp van de afbeelding op, die wordt gebruikt door Windows Verkenner.

Waarde: Onderwerp van afbeelding, gebruikt door Windows Verkenner.

**Returns:**
java.lang.String - onderwerp van afbeelding, die wordt gebruikt door Windows Verkenner.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Haalt informatie over de afbeelding op, die wordt gebruikt door Windows Verkenner.

Waarde: Informatie over afbeelding, gebruikt door Windows Verkenner.

**Returns:**
java.lang.String - informatie over afbeelding, die wordt gebruikt door Windows Verkenner.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Haalt informatie over de afbeelding op, die wordt gebruikt door Windows Verkenner.

Waarde: Informatie over afbeelding, gebruikt door Windows Verkenner. De  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) wordt genegeerd door Windows Verkenner als de  ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) tag bestaat.

**Returns:**
java.lang.String - informatie over afbeelding, die wordt gebruikt door Windows Verkenner.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Haalt of stelt de XMP‑metadatacontainer in.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Haalt de x-positie op of stelt deze in.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Haalt op of stelt de x-resolutie in.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Haalt de YCbCrCoefficients op of stelt deze in.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - De YCbCr‑coëfficiënten.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Haalt de subsamplingfactoren voor YCbCr-fotometrisch op of stelt deze in.

**Returns:**
int[] - De subsampling‑factoren voor YCbCr‑fotometrisch.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Haalt de y-positie op of stelt deze in.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Haalt of stelt de y-resolutie in.

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


Haalt een waarde op die aangeeft of de extra samples aanwezig is.

**Returns:**
boolean -  true  als de extra monsters aanwezig zijn; anders,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Bepaalt of de tag al dan niet aanwezig is in de opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tag | int | De tag‑id om te controleren. |

**Returns:**
boolean -  true  als de tag aanwezig is; anders,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Haalt een waarde op die aangeeft of de afbeelding getegeld is.

**Returns:**
boolean -  true  als de afbeelding getegeld is; anders,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Haalt een waarde op die aangeeft of de TiffOptions correct zijn geconfigureerd. Gebruik de Validate-methode om de foutreden te vinden.

**Returns:**
boolean - true als TiffOptions correct zijn geconfigureerd; anders false.
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


Verwijdert de tag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tag | int | De tag die moet worden verwijderd. |

**Returns:**
boolean - true als succesvol verwijderd
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Haalt de alpha-opslagoptie op of stelt deze in. Opties anders dan TiffAlphaStorage.Unspecified worden gebruikt wanneer er meer dan 3 SamplesPerPixel zijn gedefinieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De alpha-opslagoptie. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Haalt op of stelt de artiest in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De artiest. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Haalt of stelt de kleur van de achtergrond in. Wordt voor interne doeleinden gebruikt om de achtergrondkleur van de afbeelding op te slaan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | De kleur van de achtergrond. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Stelt het aantal bits per sample in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int[] | De bits per monsterwaarde. |

Bij het instellen van deze waarde moet u rekening houden met het feit dat ook de SamplesPerPixel-waarde op de arraylengte wordt gezet. Deze 2 eigenschappen zijn zeer nauw met elkaar gekoppeld, dus kunnen alleen samen worden ingesteld. |

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

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Haalt op of stelt een waarde in die de tiff‑bytevolgorde aangeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Haalt de kleurenkaart op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | De kleurenkaart. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Stelt de kwaliteit van gecomprimeerde afbeeldingen in. Wordt gebruikt met de Jpeg-compressie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | kwaliteit van gecomprimeerde afbeelding. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Stelt de compressie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De compressie. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Stelt het copyright in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Het auteursrecht. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Haalt de datum en tijd op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De datum en tijd. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Haalt de standaard geheugenallocatielimiet op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De standaard geheugenallocatielimiet. |

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

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Haalt de naam van het document op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De naam van het document. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Stelt de waarden van de extra samples in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | De extra monsterswaarde. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Haalt de fax t4-opties op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De fax t4-opties. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Haalt de TIFF-bestandsstandaard op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De TIFF-bestandsstandaard. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Haalt de vulvolgorde van bytebits op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De volgorde van bytebitsvulling. |

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

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Haalt de halftoonhints op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | De halftoonhints. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Stelt de ICC-profielstroom in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] | Het icc-profiel. |

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

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Haalt op of stelt de afbeeldingsbeschrijving in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De afbeeldingsbeschrijving. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Haalt op of stelt de afbeeldingslengte in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De afbeeldingslengte. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Haalt op of stelt de afbeeldingsbreedte in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De breedte van de afbeelding. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Haalt de inkt namen op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De inkt namen. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Haalt de maximale monsterwaarde op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | De maximale monsterwaarde. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Haalt de minimale monsterwaarde op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | De minimale monsterwaarde. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


De multipage-opties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Haalt op of stelt de oriëntatie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De oriëntatie. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Haalt de paginanaam op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De paginanaam. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Haalt de paginanummer-tag op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | De paginanummer-tag. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Haalt of stelt het kleurenpalet in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Haalt de fotometrie op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De fotometrische. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Haalt op of stelt de planar configuratie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De planaire configuratie. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Haalt de predictor voor LZW-compressie op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Het voorspellertype. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Haalt een waarde op die aangeeft of componenten voorvermenigvuldigd moeten worden, of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als componenten moeten worden voorvermenigvuldigd; anders,  false . |

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

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Haalt op of stelt de resolutie-eenheid in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De resolutie-eenheid. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Haalt het aantal rijen per strook op of stelt dit in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De rijen per strook. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Haalt het monsterformaat op of stelt dit in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | Het monsterformaat. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Haalt de scannerfabrikant op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De fabrikant van de scanner. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Haalt het scannermodel op of stelt dit in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Het scanermodel. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Haalt of stelt de maximale monsterwaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de monstergegevens (Byte, Short of Long type).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long[] | De maximale monsterwaarde. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Haalt of stelt de minimale monsterwaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de monstergegevens (Byte, Short of Long type).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long[] | De minimale monsterwaarde. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Haalt het softwaretype op of stelt dit in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Het softwaretype. |

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

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Haalt de strip-byte-aantallen op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long[] | De strip byte-aantallen. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Haalt de stripoffsets op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long[] | De strip offsets. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Haalt een algemene indicatie van het type gegevens dat in dit subbestand zit op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De algemene indicatie van het type gegevens dat in dit subbestand is opgenomen. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Haalt de tags op of stelt ze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | De tags. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Haalt de doelprinter op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De doelprinter. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Haalt de drempelwaarde op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De drempelbepaling. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Haalt de tegel-byte-aantallen op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Haalt de tegellengte op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Haalt de tegeloffsets op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Haalt de tegelbreedte op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Stelt de auteur van de afbeelding in, die door Windows Verkenner wordt gebruikt.

Waarde: Image Author, gebruikt door Windows Explorer. De  XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) wordt genegeerd door Windows Explorer als de  Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) tag bestaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | afbeeldingsauteur, die wordt gebruikt door Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Stelt een opmerking op de afbeelding in, die door Windows Verkenner wordt gebruikt.

Waarde: Opmerking bij afbeelding, gebruikt door Windows Verkenner.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | opmerking bij afbeelding, die wordt gebruikt door Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Stelt het onderwerp van de afbeelding in, die door Windows Verkenner wordt gebruikt.

Waarde: Onderwerp van afbeelding, gebruikt door Windows Verkenner.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | onderwerpafbeelding, die wordt gebruikt door Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Stelt informatie over de afbeelding in, die door Windows Verkenner wordt gebruikt.

Waarde: Informatie over afbeelding, gebruikt door Windows Verkenner.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | informatie over afbeelding, die wordt gebruikt door Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Stelt informatie over de afbeelding in, die door Windows Verkenner wordt gebruikt.

Waarde: Informatie over afbeelding, gebruikt door Windows Explorer. De  XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) wordt genegeerd door Windows Explorer als de  ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) tag bestaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | informatie over afbeelding, die wordt gebruikt door Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Haalt of stelt de XMP‑metadatacontainer in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | De XMP-gegevenscontainer. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Haalt de x-positie op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | De x-positie. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Haalt op of stelt de x-resolutie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | De x-resolutie. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Haalt de YCbCrCoefficients op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | De YCbCr-coëfficiënten. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Haalt de subsamplingfactoren voor YCbCr-fotometrisch op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] | De subsamplingfactoren voor YCbCr-fotometrisch. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Haalt de y-positie op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | De y-positie. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Haalt of stelt de y-resolutie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | De y-resolutie. |

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


Valideert of de opties een geldige combinatie van tags hebben

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

