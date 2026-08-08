---
title: "TiffOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "TIFF-filformatets alternativ."
type: docs
weight: 25
url: /sv/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Tiff-filformatalternativen. Observera att bredd- och höjdmärkningar kommer att skrivas över vid bildskapande av bredd- och höjdpärametrar så det är inte nödvändigt att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att detta alternativ är satt explicit som ett taggvärde. För att verifiera att taggen finns, använd egenskapen Tags eller motsvarande metod IsTagPresent.

VARNING! ändra aldrig tiff-alternativ under sparning eftersom detta kan orsaka bieffekter och svåra att hitta buggar. Följande rad lämnades speciellt kommenterad eftersom den orsakade felaktig bestämning av datainledningen. De överförda alternativen innehöll inte spp (även om alternativen inte är korrekta i ett sådant fall men ändå orsakar detta scenario fel) och nästa rad orsakade att +spp‑tagg +bpp‑tagg lades till och när alternativen skrevs efter att data helt skrivits har de skrivit över datainledningen för okomprimerad codec!!! Se TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initierar en ny instans av klassen  TiffOptions  . |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initierar en ny instans av klassen  TiffOptions  . |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Initierar en ny instans av klassen  TiffOptions  . |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen  TiffOptions  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Lägger till en ny tagg. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Lägger till taggarna. |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Klonar den här instansen. |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Hämtar eller anger alfa lagringsalternativet. |
| [getArtist()](#getArtist--) | Hämtar eller anger artisten. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Hämtar eller anger bakgrundens färg. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar bitarna per pixel. |
| [getBitsPerSample()](#getBitsPerSample--) | Hämtar bitarna per prov. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [getByteOrder()](#getByteOrder--) | Hämtar eller anger ett värde som indikerar tiff-byteordning. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Hämtar cachen. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Hämtar eller anger färgkartan. |
| [getCompressedQuality()](#getCompressedQuality--) | Hämtar komprimerad bildkvalitet. |
| [getCompression()](#getCompression--) | Hämtar komprimeringen. |
| [getCopyright()](#getCopyright--) | Hämtar upphovsrätten. |
| [getDateTime()](#getDateTime--) | Hämtar eller anger datum och tid. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Hämtar eller anger standardgränsen för minnesallokering. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getDocumentName()](#getDocumentName--) | Hämtar eller anger dokumentets namn. |
| [getExifIfd()](#getExifIfd--) | Hämtar eller anger pekaren till EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Hämtar antalet extra prover. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Hämtar värdena för extra prover. |
| [getFaxT4Options()](#getFaxT4Options--) | Hämtar eller anger fax t4-alternativen. |
| [getFileStandard()](#getFileStandard--) | Hämtar eller anger TIFF-filstandarden. |
| [getFillOrder()](#getFillOrder--) | Hämtar eller anger fyllningsordning för bytebitar. |
| [getFullFrame()](#getFullFrame--) | Hämtar ett värde som anger om [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Hämtar eller anger halvtontips. |
| [getIccProfile()](#getIccProfile--) | Hämtar icc-profilströmmen. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [getImageDescription()](#getImageDescription--) | Hämtar eller anger bildbeskrivning. |
| [getImageLength()](#getImageLength--) | Hämtar eller anger bildlängd. |
| [getImageWidth()](#getImageWidth--) | Hämtar eller anger bildbredd. |
| [getInkNames()](#getInkNames--) | Hämtar eller anger bläcknamnen. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Hämtar eller anger maximalt provvärde. |
| [getMinSampleValue()](#getMinSampleValue--) | Hämtar eller anger minimalt provvärde. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Multipagesalternativen |
| [getOrientation()](#getOrientation--) | Hämtar eller anger orienteringen. |
| [getPageName()](#getPageName--) | Hämtar eller anger sidnamnet. |
| [getPageNumber()](#getPageNumber--) | Hämtar eller anger sidnummeretiketten. |
| [getPalette()](#getPalette--) | Hämtar eller anger färgpaletten. |
| [getPhotometric()](#getPhotometric--) | Hämtar eller anger fotometrisk information. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Hämtar eller anger planär konfiguration. |
| [getPredictor()](#getPredictor--) | Hämtar eller anger förutsägaren för LZW-komprimering. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [getResolutionSettings()](#getResolutionSettings--) | Hämtar eller anger upplösningsinställningarna. |
| [getResolutionUnit()](#getResolutionUnit--) | Hämtar eller anger upplösningsenhet. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Hämtar eller anger rader per remsa. |
| [getSampleFormat()](#getSampleFormat--) | Hämtar eller anger provformatet. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Hämtar prover per pixel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Hämtar eller anger skannertillverkaren. |
| [getScannerModel()](#getScannerModel--) | Hämtar eller anger skannermodellen. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Hämtar eller anger maximalt provvärde. |
| [getSminSampleValue()](#getSminSampleValue--) | Hämtar eller anger minimalt provvärde. |
| [getSoftwareType()](#getSoftwareType--) | Hämtar eller anger programvarutypen. |
| [getSource()](#getSource--) | Hämtar eller anger källan där bilden ska skapas. |
| [getStripByteCounts()](#getStripByteCounts--) | Hämtar eller anger antalet byte per remsa. |
| [getStripOffsets()](#getStripOffsets--) | Hämtar eller anger remsaförskjutningarna. |
| [getSubFileType()](#getSubFileType--) | Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Hämtar instansen av taggen efter typ. |
| [getTags()](#getTags--) | Hämtar eller anger taggarna. |
| [getTargetPrinter()](#getTargetPrinter--) | Hämtar eller anger målskrivaren. |
| [getThreshholding()](#getThreshholding--) | Hämtar eller anger tröskelvärdet. |
| [getTileByteCounts()](#getTileByteCounts--) | Hämtar eller anger antalet byte per tile. |
| [getTileLength()](#getTileLength--) | Hämtar eller anger tile-längden. |
| [getTileOffsets()](#getTileOffsets--) | Hämtar eller anger tile-förskjutningarna. |
| [getTileWidth()](#getTileWidth--) | Hämtar eller anger kakelbredd. |
| [getTotalPages()](#getTotalPages--) | Hämtar det totala antalet sidor. |
| [getValidTagCount()](#getValidTagCount--) | Hämtar antalet giltiga taggar. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Hämtar antalet giltiga taggar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [getXPAuthor()](#getXPAuthor--) | Hämtar bildens författare, som används av Windows Explorer. |
| [getXPComment()](#getXPComment--) | Hämtar kommentar på bilden, som används av Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Hämtar bildens ämne, som används av Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Hämtar information om bilden, som används av Windows Explorer. |
| [getXPTitle()](#getXPTitle--) | Hämtar information om bilden, som används av Windows Explorer. |
| [getXmpData()](#getXmpData--) | Hämtar eller anger XMP‑metadata‑behållaren. |
| [getXposition()](#getXposition--) | Hämtar eller anger x‑positionen. |
| [getXresolution()](#getXresolution--) | Hämtar eller anger x-upplösning. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Hämtar eller anger YCbCr‑koefficienterna. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Hämtar eller anger underprovsningsfaktorerna för YCbCr‑fotometrisk. |
| [getYposition()](#getYposition--) | Hämtar eller anger y‑positionen. |
| [getYresolution()](#getYresolution--) | Hämtar eller anger y-upplösning. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Hämtar ett värde som indikerar om extra prov är närvarande. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Bestämmer om taggen finns i alternativen eller inte. |
| [isTiled()](#isTiled--) | Hämtar ett värde som indikerar om bilden är kaklad. |
| [isValid()](#isValid--) | Hämtar ett värde som indikerar om  TiffOptions  har konfigurerats korrekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Tar bort taggen. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Hämtar eller anger alfa lagringsalternativet. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Hämtar eller anger artisten. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Hämtar eller anger bakgrundens färg. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Anger bitar per prov. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setByteOrder(int value)](#setByteOrder-int-) | Hämtar eller anger ett värde som indikerar tiff-byteordning. |
| [setColorMap(int[] value)](#setColorMap-int---) | Hämtar eller anger färgkartan. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Anger komprimerad bildkvalitet. |
| [setCompression(int value)](#setCompression-int-) | Anger komprimeringen. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Anger upphovsrätten. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Hämtar eller anger datum och tid. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Hämtar eller anger standardgränsen för minnesallokering. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Hämtar eller anger dokumentets namn. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Anger värden för extra prover. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Hämtar eller anger fax t4-alternativen. |
| [setFileStandard(int value)](#setFileStandard-int-) | Hämtar eller anger TIFF-filstandarden. |
| [setFillOrder(int value)](#setFillOrder-int-) | Hämtar eller anger fyllningsordning för bytebitar. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Anger ett värde som anger om [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Hämtar eller anger halvtontips. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Anger ICC‑profilströmmen. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Hämtar eller anger bildbeskrivning. |
| [setImageLength(long value)](#setImageLength-long-) | Hämtar eller anger bildlängd. |
| [setImageWidth(long value)](#setImageWidth-long-) | Hämtar eller anger bildbredd. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Hämtar eller anger bläcknamnen. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Hämtar eller anger maximalt provvärde. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Hämtar eller anger minimalt provvärde. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Multipagesalternativen |
| [setOrientation(int value)](#setOrientation-int-) | Hämtar eller anger orienteringen. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Hämtar eller anger sidnamnet. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Hämtar eller anger sidnummeretiketten. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Hämtar eller anger färgpaletten. |
| [setPhotometric(int value)](#setPhotometric-int-) | Hämtar eller anger fotometrisk information. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Hämtar eller anger planär konfiguration. |
| [setPredictor(int value)](#setPredictor-int-) | Hämtar eller anger förutsägaren för LZW-komprimering. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Hämtar eller anger upplösningsinställningarna. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Hämtar eller anger upplösningsenhet. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Hämtar eller anger rader per remsa. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Hämtar eller anger provformatet. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Hämtar eller anger skannertillverkaren. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Hämtar eller anger skannermodellen. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Hämtar eller anger maximalt provvärde. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Hämtar eller anger minimalt provvärde. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Hämtar eller anger programvarutypen. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Hämtar eller anger källan där bilden ska skapas. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Hämtar eller anger antalet byte per remsa. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Hämtar eller anger remsaförskjutningarna. |
| [setSubFileType(long value)](#setSubFileType-long-) | Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggarna. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Hämtar eller anger målskrivaren. |
| [setThreshholding(int value)](#setThreshholding-int-) | Hämtar eller anger tröskelvärdet. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Hämtar eller anger antalet byte per tile. |
| [setTileLength(long value)](#setTileLength-long-) | Hämtar eller anger tile-längden. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Hämtar eller anger tile-förskjutningarna. |
| [setTileWidth(long value)](#setTileWidth-long-) | Hämtar eller anger kakelbredd. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Anger bildens författare, som används av Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Anger kommentar på bilden, som används av Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Anger bildens ämne, som används av Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Ställer in information om bilden, som används av Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Ställer in information om bilden, som används av Windows Explorer. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Hämtar eller anger XMP‑metadata‑behållaren. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger x‑positionen. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger x-upplösning. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Hämtar eller anger YCbCr‑koefficienterna. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Hämtar eller anger underprovsningsfaktorerna för YCbCr‑fotometrisk. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger y‑positionen. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Hämtar eller anger y-upplösning. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Validerar om alternativ har en giltig kombination av taggar |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Initierar en ny instans av klassen  TiffOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | int | Det förväntade tiff-filformatet. |
| byteOrder | int | Byteordningen för TIFF-filformatet som ska användas. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initierar en ny instans av TiffOptions-klassen. Som standard används little endian-konventionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | int | Det förväntade tiff-filformatet. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initierar en ny instans av klassen  TiffOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Alternativen att kopiera från. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initierar en ny instans av klassen  TiffOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Taggarna att initiera alternativ med. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Lägger till en ny tagg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Taggen att lägga till. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Lägger till taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Taggarna att lägga till. |

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


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klonar den här instansen.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Klonar den här instansen.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Hämtar eller anger alfa lagringsalternativet. Alternativ andra än TiffAlphaStorage.Unspecified används när det finns mer än 3 SamplesPerPixel definierade.

**Returns:**
int - Alfa lagringsalternativet.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Hämtar eller anger artisten.

**Returns:**
java.lang.String - Konstnären.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Hämtar eller anger bakgrundens färg. Används för interna ändamål för att lagra bildens bakgrundsfärg.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar bitarna per pixel.

**Returns:**
int - Bitarna per pixel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Hämtar bitarna per prov.

**Returns:**
int[] - Bits per provvärde.

När du sätter detta värde, tänk på att det också kommer att sätta SamplesPerPixel till arrayens längd. Dessa två egenskaper är mycket tätt kopplade så de kan endast sättas tillsammans.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Hämtar eller anger ett värde som indikerar tiff-byteordning.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Hämtar cachen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagg | int | Taggen (som är av array-typ). |

**Returns:**
long[] - Taggvärdet.
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


Hämtar eller anger färgkartan.

**Returns:**
int[] - Färgkartan.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Hämtar komprimerad bildkvalitet. Används med JPEG-komprimering.

**Returns:**
int - komprimerad bildkvalitet.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Hämtar komprimeringen.

**Returns:**
int - Komprimeringen.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Hämtar upphovsrätten.

**Returns:**
java.lang.String - Copyright.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Hämtar eller anger datum och tid.

**Returns:**
java.lang.String - Datum och tid.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Hämtar eller anger standardgränsen för minnesallokering.

**Returns:**
int - Den standardmässiga gränsen för minnesallokering.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Värde: Standardersättningsfonten.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Hämtar eller anger dokumentets namn.

**Returns:**
java.lang.String - Namnet på dokumentet.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Hämtar eller anger pekaren till EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Hämtar antalet extra prover.

Värde: Det extra provantalet.

**Returns:**
long - det extra provantalet.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Hämtar värdena för extra prover.

Värde: Det extra provvärdet.

**Returns:**
int[] - de extra provvärdena.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Hämtar eller anger fax t4-alternativen.

**Returns:**
long - Fax t4-alternativen.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Hämtar eller anger TIFF-filstandarden.

**Returns:**
int - TIFF-filstandard.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Hämtar eller anger fyllningsordning för bytebitar.

**Returns:**
int - Bytebits fyllningsordning.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Hämtar ett värde som anger om [full frame].

Värde:  true  om [full frame]; annars  false .

**Returns:**
boolean - ett värde som anger om [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Hämtar eller anger halvtontips.

**Returns:**
int[] - Halvtonstipsen.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Hämtar icc-profilströmmen.

**Returns:**
byte[] - ICC-profilen.
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


Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse.

Värde:  true  om ignorera efter skapa‑händelse; annars  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Hämtar eller anger bildbeskrivning.

**Returns:**
java.lang.String - Bildbeskrivningen.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Hämtar eller anger bildlängd.

**Returns:**
long - Bildlängden.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Hämtar eller anger bildbredd.

**Returns:**
long - Bildbredden.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Hämtar eller anger bläcknamnen.

**Returns:**
java.lang.String - Bläcknamnen.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Hämtar eller anger maximalt provvärde.

**Returns:**
int[] - Maxprovvärdet.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Hämtar eller anger minimalt provvärde.

**Returns:**
int[] - Minprovvärdet.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Multipagesalternativen

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Hämtar eller anger orienteringen.

**Returns:**
int - Orienteringen.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Hämtar eller anger sidnamnet.

**Returns:**
java.lang.String - Sidnamnet.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Hämtar eller anger sidnummeretiketten.

**Returns:**
int[] - Sidnumreringstaggen.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Hämtar eller anger färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Hämtar eller anger fotometrisk information.

**Returns:**
int - Fotometrisk.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Hämtar eller anger planär konfiguration.

**Returns:**
int - Planär konfiguration.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Hämtar eller anger förutsägaren för LZW-komprimering.

**Returns:**
int - Prediktionstypen.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras.

**Returns:**
boolean -  true  om komponenter måste förmultipliceras; annars,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Hämtar eller anger hanteraren för förlopps‑händelsen.

Värde: hanteraren för progress‑händelsen.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Hämtar eller anger upplösningsinställningarna.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Hämtar eller anger upplösningsenhet.

**Returns:**
int - Upplösningsenheten.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Hämtar eller anger rader per remsa.

**Returns:**
long - Rader per remsa.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Hämtar eller anger provformatet.

**Returns:**
int[] - Sampleformatet.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Hämtar proverna per pixel. För att ändra detta egenskapsvärde, använd BitsPerSample‑egenskapsinställaren.

**Returns:**
int - Proverna per pixel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Hämtar eller anger skannertillverkaren.

**Returns:**
java.lang.String - Tillverkaren av skannern.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Hämtar eller anger skannermodellen.

**Returns:**
java.lang.String - Skannermodellen.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Hämtar eller anger det maximala provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long‑typ).

**Returns:**
long[] - Det maximala provvärdet.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Hämtar eller anger det minsta provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long‑typ).

**Returns:**
long[] - Det minsta provvärdet.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Hämtar eller anger programvarutypen.

**Returns:**
java.lang.String - Programvarutypen.
### getSource() {#getSource--}
```
public final Source getSource()
```


Hämtar eller anger källan där bilden ska skapas.

Värde: Källan där bilden ska skapas.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Hämtar eller anger antalet byte per remsa.

**Returns:**
long[] - Antalet byte per strip.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Hämtar eller anger remsaförskjutningarna.

**Returns:**
long[] - Strip‑offsetarna.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil.

**Returns:**
long - Den allmänna indikationen av vilken typ av data som finns i denna delfil.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Hämtar instansen av taggen efter typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagKey | int | Taggnyckeln. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Hämtar eller anger taggarna.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Taggarna.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Hämtar eller anger målskrivaren.

**Returns:**
java.lang.String - Målskrivaren.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Hämtar eller anger tröskelvärdet.

**Returns:**
int - Tröskelvärdet.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Hämtar eller anger antalet byte per tile.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Hämtar eller anger tile-längden.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Hämtar eller anger tile-förskjutningarna.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Hämtar eller anger kakelbredd.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Hämtar det totala antalet sidor.

**Returns:**
int - Totalt antal sidor.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Hämtar det giltiga antalet taggar. Detta är inte det totala antalet taggar utan antalet taggar som kan bevaras.

**Returns:**
int - Det giltiga antalet taggar.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Hämtar antalet giltiga taggar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Taggarna att validera. |

**Returns:**
int - Det giltiga antalet taggar.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Hämtar eller anger vektor‑rasteriseringsalternativen.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Hämtar bildens författare, som används av Windows Explorer.

Värde: Bildförfattare, används av Windows Explorer. XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) ignoreras av Windows Explorer om Artist‑taggen ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) finns.

**Returns:**
java.lang.String - bildförfattare, som används av Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Hämtar kommentar på bilden, som används av Windows Explorer.

Värde: Kommentar på bilden, används av Windows Explorer.

**Returns:**
java.lang.String - kommentar på bilden, som används av Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Hämtar bildens ämne, som används av Windows Explorer.

Värde: Ämnesbild, används av Windows Explorer.

**Returns:**
java.lang.String - ämnesbild, som används av Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Hämtar information om bilden, som används av Windows Explorer.

Värde: Information om bilden, används av Windows Explorer.

**Returns:**
java.lang.String - information om bilden, som används av Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Hämtar information om bilden, som används av Windows Explorer.

Värde: Information om bilden, används av Windows Explorer. Den  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) ignoreras av Windows Explorer om den  ImageDescription-taggen ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) finns.

**Returns:**
java.lang.String - information om bilden, som används av Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Hämtar eller anger XMP‑metadata‑behållaren.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Hämtar eller anger x‑positionen.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Hämtar eller anger x-upplösning.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Hämtar eller anger YCbCr‑koefficienterna.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - YCbCr-koefficienterna.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Hämtar eller anger underprovsningsfaktorerna för YCbCr‑fotometrisk.

**Returns:**
int[] - Undersamplingsfaktorerna för YCbCr-fotometrisk.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Hämtar eller anger y‑positionen.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Hämtar eller anger y-upplösning.

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


Hämtar ett värde som indikerar om extra prov är närvarande.

**Returns:**
boolean -  true  om extra prover finns; annars,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Bestämmer om taggen finns i alternativen eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagg | int | Tagg‑ID att kontrollera. |

**Returns:**
boolean -  true  om taggen finns; annars,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Hämtar ett värde som indikerar om bilden är kaklad.

**Returns:**
boolean -  true  om bilden är kaklad; annars,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Hämtar ett värde som indikerar om  TiffOptions  har konfigurerats korrekt. Använd Validate‑metoden för att hitta felorsaken.

**Returns:**
boolean -  true  om TiffOptions är korrekt konfigurerade; annars,  false .
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


Tar bort taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagg | int | Taggen att ta bort. |

**Returns:**
boolean - true om borttagning lyckades
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Hämtar eller anger alfa lagringsalternativet. Alternativ andra än TiffAlphaStorage.Unspecified används när det finns mer än 3 SamplesPerPixel definierade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Alfahanteringsalternativet. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Hämtar eller anger artisten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Konstnären. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Hämtar eller anger bakgrundens färg. Används för interna ändamål för att lagra bildens bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Bakgrundens färg. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Anger bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int[] | Bitar per provvärde. |

När du sätter detta värde, tänk på att det också kommer att sätta SamplesPerPixel‑värdet till arrayens längd. Dessa 2 egenskaper är mycket starkt kopplade så de kan bara sättas tillsammans. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Hämtar eller anger ett värde som indikerar tiff-byteordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Hämtar eller anger färgkartan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Färgkartan. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Ställer in komprimerad bildkvalitet. Används med JPEG-komprimering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | komprimerad bildkvalitet. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Anger komprimeringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Komprimeringen. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Anger upphovsrätten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Upphovsrätten. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Hämtar eller anger datum och tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Datum och tid. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Hämtar eller anger standardgränsen för minnesallokering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den standardmässiga gränsen för minnesallokering. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Värde: Standardersättningsfonten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Hämtar eller anger dokumentets namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Namnet på dokumentet. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Anger värden för extra prover.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Det extra provvärdet. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Hämtar eller anger fax t4-alternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Fax‑t4‑alternativen. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Hämtar eller anger TIFF-filstandarden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | TIFF‑filstandard. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Hämtar eller anger fyllningsordning för bytebitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Byte‑bits fyllningsordning. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Anger ett värde som anger om [full frame].

Värde:  true  om [full frame]; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som anger om [full frame]. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Hämtar eller anger halvtontips.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Halvtonstipsen. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Anger ICC‑profilströmmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] | ICC-profilen. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse.

Värde:  true  om ignorera efter skapa‑händelse; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Hämtar eller anger bildbeskrivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Bildbeskrivning. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Hämtar eller anger bildlängd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Bildlängd. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Hämtar eller anger bildbredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Bildens bredd. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Hämtar eller anger bläcknamnen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Bläcknamn. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Hämtar eller anger maximalt provvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Maximalt provvärde. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Hämtar eller anger minimalt provvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Minimalt provvärde. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Multipagesalternativen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Hämtar eller anger orienteringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Orienteringen. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Hämtar eller anger sidnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Sidnamn. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Hämtar eller anger sidnummeretiketten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Sidnumreringstagg. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Hämtar eller anger färgpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Hämtar eller anger fotometrisk information.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Fotometrisk. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Hämtar eller anger planär konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Planär konfiguration. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Hämtar eller anger förutsägaren för LZW-komprimering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Prediktortyp. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true  om komponenter måste förmultipliceras; annars,  false . |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Hämtar eller anger hanteraren för förlopps‑händelsen.

Värde: hanteraren för progress‑händelsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Hämtar eller anger upplösningsinställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Hämtar eller anger upplösningsenhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Upplösningsenhet. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Hämtar eller anger rader per remsa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Rader per remsa. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Hämtar eller anger provformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Provformat. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Hämtar eller anger skannertillverkaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Skannertillverkare. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Hämtar eller anger skannermodellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Skannermodell. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Hämtar eller anger det maximala provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long‑typ).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Maximalt provvärde. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Hämtar eller anger det minsta provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long‑typ).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Minimalt provvärde. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Hämtar eller anger programvarutypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Programvarutyp. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Hämtar eller anger källan där bilden ska skapas.

Värde: Källan där bilden ska skapas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Hämtar eller anger antalet byte per remsa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Remsbyteantal. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Hämtar eller anger remsaförskjutningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Strip‑offseten. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Allmän indikation på vilken typ av data som finns i denna delfil. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Hämtar eller anger taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Taggarna. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Hämtar eller anger målskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Målskrivaren. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Hämtar eller anger tröskelvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Tröskelvärdet. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Hämtar eller anger antalet byte per tile.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Hämtar eller anger tile-längden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Hämtar eller anger tile-förskjutningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Hämtar eller anger kakelbredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Hämtar eller anger vektor‑rasteriseringsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Anger bildens författare, som används av Windows Explorer.

Värde: Bildförfattare, används av Windows Explorer. XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) ignoreras av Windows Explorer om Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) taggen finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Bildförfattare, som används av Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Anger kommentar på bilden, som används av Windows Explorer.

Värde: Kommentar på bilden, används av Windows Explorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Kommentar på bilden, som används av Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Anger bildens ämne, som används av Windows Explorer.

Värde: Ämnesbild, används av Windows Explorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Bildens ämne, som används av Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Ställer in information om bilden, som används av Windows Explorer.

Värde: Information om bilden, används av Windows Explorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Information om bilden, som används av Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Ställer in information om bilden, som används av Windows Explorer.

Värde: Information om bilden, används av Windows Explorer. XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) ignoreras av Windows Explorer om ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) taggen finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Information om bilden, som används av Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Hämtar eller anger XMP‑metadata‑behållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP-datakontainer. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Hämtar eller anger x‑positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | X‑positionen. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Hämtar eller anger x-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | X‑upplösningen. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Hämtar eller anger YCbCr‑koefficienterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | YCbCr‑koefficienterna. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Hämtar eller anger underprovsningsfaktorerna för YCbCr‑fotometrisk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Undersamplingsfaktorerna för YCbCr‑fotometrisk. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Hämtar eller anger y‑positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Y‑positionen. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Hämtar eller anger y-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Y‑upplösningen. |

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


Validerar om alternativ har en giltig kombination av taggar

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

