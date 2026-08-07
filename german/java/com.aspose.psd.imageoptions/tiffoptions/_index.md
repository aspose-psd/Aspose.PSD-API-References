---
title: "TiffOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die TIFF‑Dateiformat‑Optionen."
type: docs
weight: 25
url: /de/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Die TIFF-Dateiformatoptionen. Hinweis: Die Breiten- und Höhen-Tags werden bei der Bildgenerierung durch die Breiten- und Höhen-Parameter überschrieben, sodass sie nicht direkt angegeben werden müssen. Hinweis: Viele Optionen geben einen Standardwert zurück, das bedeutet jedoch nicht, dass diese Option explizit als Tag-Wert gesetzt ist. Um zu überprüfen, ob das Tag vorhanden ist, verwenden Sie die Eigenschaft Tags oder die entsprechende Methode IsTagPresent.

WARNUNG! Ändern Sie die TIFF-Optionen während des Speicherns niemals, da dies Nebenwirkungen und schwer zu findende Fehler verursachen kann. Die folgende Zeile wurde bewusst auskommentiert, weil sie zu einer falschen Bestimmung des Datenbeginns führte. Die übergebenen Optionen enthielten kein spp (obwohl die Optionen in einem solchen Fall nicht korrekt sind, verursacht dieses Szenario dennoch Fehler) und die nächste Zeile fügte das +spp-Tag und das +bpp-Tag hinzu, und wenn die Optionen nach vollständig geschriebenen Daten geschrieben wurden, haben sie den Datenbeginn für den unkomprimierten Codec überschrieben!!! Siehe TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initialisiert eine neue Instanz der Klasse  TiffOptions . |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initialisiert eine neue Instanz der Klasse  TiffOptions . |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Initialisiert eine neue Instanz der Klasse  TiffOptions . |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der Klasse  TiffOptions . |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Fügt ein neues Tag hinzu. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Fügt die Tags hinzu. |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Klont diese Instanz. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Liest oder setzt die Alpha-Speicheroption. |
| [getArtist()](#getArtist--) | Liest oder setzt den Künstler. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Liest oder setzt die Hintergrundfarbe. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gibt die Bits pro Pixel zurück. |
| [getBitsPerSample()](#getBitsPerSample--) | Liest die Bits pro Sample. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getByteOrder()](#getByteOrder--) | Liest oder setzt einen Wert, der die Byte-Reihenfolge von TIFF angibt. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Liest den Cache. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Liest oder setzt die Farbkarte. |
| [getCompressedQuality()](#getCompressedQuality--) | Liest die Qualität des komprimierten Bildes. |
| [getCompression()](#getCompression--) | Liest die Kompression. |
| [getCopyright()](#getCopyright--) | Liest das Copyright. |
| [getDateTime()](#getDateTime--) | Liest oder setzt Datum und Uhrzeit. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Liest oder setzt das Standard-Limit für Speicherzuweisungen. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getDocumentName()](#getDocumentName--) | Liest oder setzt den Namen des Dokuments. |
| [getExifIfd()](#getExifIfd--) | Liest oder setzt den Zeiger auf EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Liest die Anzahl zusätzlicher Samples. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Liest die Werte zusätzlicher Samples. |
| [getFaxT4Options()](#getFaxT4Options--) | Liest oder setzt die Fax‑T4‑Optionen. |
| [getFileStandard()](#getFileStandard--) | Liest oder setzt den TIFF-Dateistandard. |
| [getFillOrder()](#getFillOrder--) | Liest oder setzt die Füllreihenfolge der Byte‑Bits. |
| [getFullFrame()](#getFullFrame--) | Gibt einen Wert zurück, der angibt, ob [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Liest oder setzt die halftone hints. |
| [getIccProfile()](#getIccProfile--) | Liest den icc profile stream. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [getImageDescription()](#getImageDescription--) | Liest oder setzt die Bildbeschreibung. |
| [getImageLength()](#getImageLength--) | Liest oder setzt die Bildlänge. |
| [getImageWidth()](#getImageWidth--) | Liest oder setzt die Bildbreite. |
| [getInkNames()](#getInkNames--) | Liest oder setzt die ink names. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Liest oder setzt die max sample value. |
| [getMinSampleValue()](#getMinSampleValue--) | Liest oder setzt die min sample value. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Die Mehrseitenoptionen |
| [getOrientation()](#getOrientation--) | Liest oder setzt die Ausrichtung. |
| [getPageName()](#getPageName--) | Liest den page name. |
| [getPageNumber()](#getPageNumber--) | Liest oder setzt das page number tag. |
| [getPalette()](#getPalette--) | Ruft die Farbpalette ab oder legt sie fest. |
| [getPhotometric()](#getPhotometric--) | Liest oder setzt die photometric. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Liest oder setzt die planare Konfiguration. |
| [getPredictor()](#getPredictor--) | Liest oder setzt den predictor für LZW compression. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [getResolutionSettings()](#getResolutionSettings--) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [getResolutionUnit()](#getResolutionUnit--) | Liest oder setzt die Auflösungseinheit. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Liest oder setzt die rows per strip. |
| [getSampleFormat()](#getSampleFormat--) | Liest oder setzt das sample format. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Liest die samples per pixel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Liest oder setzt den scanner manufacturer. |
| [getScannerModel()](#getScannerModel--) | Liest oder setzt das scanner model. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Liest oder setzt die max sample value. |
| [getSminSampleValue()](#getSminSampleValue--) | Liest oder setzt die min sample value. |
| [getSoftwareType()](#getSoftwareType--) | Liest oder setzt den software type. |
| [getSource()](#getSource--) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [getStripByteCounts()](#getStripByteCounts--) | Liest oder setzt die strip byte counts. |
| [getStripOffsets()](#getStripOffsets--) | Liest oder setzt die strip offsets. |
| [getSubFileType()](#getSubFileType--) | Liest oder setzt eine allgemeine Angabe über die Art der Daten, die in dieser subfile enthalten sind. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Liest die instance des tags nach Typ. |
| [getTags()](#getTags--) | Liest oder setzt die tags. |
| [getTargetPrinter()](#getTargetPrinter--) | Liest oder setzt den target printer. |
| [getThreshholding()](#getThreshholding--) | Liest oder setzt das threshholding. |
| [getTileByteCounts()](#getTileByteCounts--) | Liest oder setzt die tile byte counts. |
| [getTileLength()](#getTileLength--) | Liest ot setzt tile length. |
| [getTileOffsets()](#getTileOffsets--) | Liest oder setzt die Kachelversätze. |
| [getTileWidth()](#getTileWidth--) | Liest oder setzt die Kachelbreite. |
| [getTotalPages()](#getTotalPages--) | Liest die Gesamtseiten. |
| [getValidTagCount()](#getValidTagCount--) | Liest die gültige Tag-Anzahl. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Gibt die Anzahl gültiger Tags zurück. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [getXPAuthor()](#getXPAuthor--) | Liest den Bildautor, der von Windows Explorer verwendet wird. |
| [getXPComment()](#getXPComment--) | Liest den Kommentar zum Bild, der von Windows Explorer verwendet wird. |
| [getXPKeywords()](#getXPKeywords--) | Liest das Bildthema, das von Windows Explorer verwendet wird. |
| [getXPSubject()](#getXPSubject--) | Liest Informationen zum Bild, die von Windows Explorer verwendet werden. |
| [getXPTitle()](#getXPTitle--) | Liest Informationen zum Bild, die von Windows Explorer verwendet werden. |
| [getXmpData()](#getXmpData--) | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [getXposition()](#getXposition--) | Liest oder setzt die x-Position. |
| [getXresolution()](#getXresolution--) | Liest oder setzt die X‑Auflösung. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Liest oder setzt die YCbCrCoefficients. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Liest oder setzt die Subsampling-Faktoren für YCbCr-Photometrie. |
| [getYposition()](#getYposition--) | Liest oder setzt die y-Position. |
| [getYresolution()](#getYresolution--) | Liest oder setzt die Y‑Auflösung. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Liest einen Wert, der angibt, ob die zusätzlichen Proben vorhanden sind. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht. |
| [isTiled()](#isTiled--) | Liest einen Wert, der angibt, ob das Bild gekachelt ist. |
| [isValid()](#isValid--) | Liest einen Wert, der angibt, ob die  TiffOptions  korrekt konfiguriert wurden. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Entfernt das Tag. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Liest oder setzt die Alpha-Speicheroption. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Liest oder setzt den Künstler. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Liest oder setzt die Hintergrundfarbe. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Setzt die Bits pro Probe. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setByteOrder(int value)](#setByteOrder-int-) | Liest oder setzt einen Wert, der die Byte-Reihenfolge von TIFF angibt. |
| [setColorMap(int[] value)](#setColorMap-int---) | Liest oder setzt die Farbkarte. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Setzt die Qualität des komprimierten Bildes. |
| [setCompression(int value)](#setCompression-int-) | Setzt die Kompression. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Setzt das Urheberrecht. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Liest oder setzt Datum und Uhrzeit. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Liest oder setzt das Standard-Limit für Speicherzuweisungen. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Liest oder setzt den Namen des Dokuments. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Setzt die Werte der zusätzlichen Proben. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Liest oder setzt die Fax‑T4‑Optionen. |
| [setFileStandard(int value)](#setFileStandard-int-) | Liest oder setzt den TIFF-Dateistandard. |
| [setFillOrder(int value)](#setFillOrder-int-) | Liest oder setzt die Füllreihenfolge der Byte‑Bits. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Legt einen Wert fest, der angibt, ob [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Liest oder setzt die halftone hints. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Setzt den ICC-Profil-Stream. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Liest oder setzt die Bildbeschreibung. |
| [setImageLength(long value)](#setImageLength-long-) | Liest oder setzt die Bildlänge. |
| [setImageWidth(long value)](#setImageWidth-long-) | Liest oder setzt die Bildbreite. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Liest oder setzt die ink names. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Liest oder setzt die max sample value. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Liest oder setzt die min sample value. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Die Mehrseitenoptionen |
| [setOrientation(int value)](#setOrientation-int-) | Liest oder setzt die Ausrichtung. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Liest den page name. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Liest oder setzt das page number tag. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ruft die Farbpalette ab oder legt sie fest. |
| [setPhotometric(int value)](#setPhotometric-int-) | Liest oder setzt die photometric. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Liest oder setzt die planare Konfiguration. |
| [setPredictor(int value)](#setPredictor-int-) | Liest oder setzt den predictor für LZW compression. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Liest oder setzt die Auflösungseinheit. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Liest oder setzt die rows per strip. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Liest oder setzt das sample format. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Liest oder setzt den scanner manufacturer. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Liest oder setzt das scanner model. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Liest oder setzt die max sample value. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Liest oder setzt die min sample value. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Liest oder setzt den software type. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Liest oder setzt die strip byte counts. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Liest oder setzt die strip offsets. |
| [setSubFileType(long value)](#setSubFileType-long-) | Liest oder setzt eine allgemeine Angabe über die Art der Daten, die in dieser subfile enthalten sind. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Liest oder setzt die tags. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Liest oder setzt den target printer. |
| [setThreshholding(int value)](#setThreshholding-int-) | Liest oder setzt das threshholding. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Liest oder setzt die tile byte counts. |
| [setTileLength(long value)](#setTileLength-long-) | Liest ot setzt tile length. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Liest oder setzt die Kachelversätze. |
| [setTileWidth(long value)](#setTileWidth-long-) | Liest oder setzt die Kachelbreite. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Setzt den Bildautor, der von Windows Explorer verwendet wird. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Setzt den Kommentar zum Bild, der von Windows Explorer verwendet wird. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Legt das Quellbild fest, das vom Windows Explorer verwendet wird. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Legt Informationen über das Bild fest, die vom Windows Explorer verwendet werden. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Legt Informationen über das Bild fest, die vom Windows Explorer verwendet werden. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die x-Position. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die X‑Auflösung. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Liest oder setzt die YCbCrCoefficients. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Liest oder setzt die Subsampling-Faktoren für YCbCr-Photometrie. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die y-Position. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Liest oder setzt die Y‑Auflösung. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Validiert, ob die Optionen eine gültige Kombination von Tags haben |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Initialisiert eine neue Instanz der Klasse  TiffOptions .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | int | Das erwartete TIFF-Dateiformat. |
| byteOrder | int | Die Byte-Reihenfolge des TIFF-Dateiformats, die verwendet werden soll. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initialisiert eine neue Instanz der Klasse TiffOptions. Standardmäßig wird die Little-Endian-Konvention verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | int | Das erwartete TIFF-Dateiformat. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initialisiert eine neue Instanz der Klasse  TiffOptions .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Die Optionen, von denen kopiert werden soll. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initialisiert eine neue Instanz der Klasse  TiffOptions .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Die Tags, mit denen die Optionen initialisiert werden. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Fügt ein neues Tag hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Das Tag, das hinzugefügt werden soll. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Fügt die Tags hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Die Tags, die hinzugefügt werden sollen. |

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


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klont diese Instanz.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Klont diese Instanz.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Liest oder setzt die Alpha-Speicheroption. Optionen außer TiffAlphaStorage.Unspecified werden verwendet, wenn mehr als 3 SamplesPerPixel definiert sind.

**Returns:**
int - Die Alpha-Speicheroption.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Liest oder setzt den Künstler.

**Returns:**
java.lang.String - Der Künstler.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Liest oder setzt die Farbe des Hintergrunds. Wird für interne Zwecke verwendet, um die Hintergrundfarbe des Bildes zu speichern.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gibt die Bits pro Pixel zurück.

**Returns:**
int – Die Bits pro Pixel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Liest die Bits pro Sample.

**Returns:**
int[] - Der Bits‑pro‑Sample‑Wert.

Beim Setzen dieses Wertes beachten Sie, dass er auch den SamplesPerPixel‑Wert auf die Array‑Länge setzt. Diese beiden Eigenschaften sind sehr eng gekoppelt, sodass sie nur zusammen gesetzt werden können.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Liest oder setzt einen Wert, der die Byte-Reihenfolge von TIFF angibt.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Liest den Cache.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tag | int | Das Tag (ein Array‑Typ). |

**Returns:**
long[] - Der Tag‑Wert.
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


Liest oder setzt die Farbkarte.

**Returns:**
int[] - Die Farbtabelle.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Liest die komprimierte Bildqualität. Wird mit der JPEG-Kompression verwendet.

**Returns:**
int - komprimierte Bildqualität.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Liest die Kompression.

**Returns:**
int - Die Kompression.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Liest das Copyright.

**Returns:**
java.lang.String - Das Urheberrecht.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Liest oder setzt Datum und Uhrzeit.

**Returns:**
java.lang.String - Das Datum und die Uhrzeit.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Liest oder setzt das Standard-Limit für Speicherzuweisungen.

**Returns:**
int - Das standardmäßige Speicherzuweisungs-Limit.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Ruft die Standardschriftart für den Ersatz ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die Schriftart der vorhandenen Ebene in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann folgender Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Wert: Die Standardschriftart für den Ersatz.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Liest oder setzt den Namen des Dokuments.

**Returns:**
java.lang.String - Der Name des Dokuments.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Liest oder setzt den Zeiger auf EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Liest die Anzahl zusätzlicher Samples.

Wert: Die zusätzliche Probenanzahl.

**Returns:**
long - die zusätzliche Probenanzahl.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Liest die Werte zusätzlicher Samples.

Wert: Der zusätzliche Probenwert.

**Returns:**
int[] - die zusätzlichen Probenwerte.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Liest oder setzt die Fax‑T4‑Optionen.

**Returns:**
long - Die Fax‑T4‑Optionen.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Liest oder setzt den TIFF-Dateistandard.

**Returns:**
int - Der TIFF‑Dateistandard.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Liest oder setzt die Füllreihenfolge der Byte‑Bits.

**Returns:**
int - Die Byte‑Bit‑Füllreihenfolge.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Gibt einen Wert zurück, der angibt, ob [full frame].

Wert:  true  wenn [full frame]; andernfalls  false .

**Returns:**
boolescher Wert – ein Wert, der angibt, ob [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Liest oder setzt die halftone hints.

**Returns:**
int[] - Die Halfton‑Hinweise.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Liest den icc profile stream.

**Returns:**
byte[] - Das ICC‑Profil.
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


Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird.

Wert:  true  wenn nach dem Erstellen-Ereignis ignoriert wird; andernfalls  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Liest oder setzt die Bildbeschreibung.

**Returns:**
java.lang.String - Die Bildbeschreibung.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Liest oder setzt die Bildlänge.

**Returns:**
long - Die Bildlänge.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Liest oder setzt die Bildbreite.

**Returns:**
long - Die Bildbreite.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Liest oder setzt die ink names.

**Returns:**
java.lang.String - Die Tinten­namen.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Liest oder setzt die max sample value.

**Returns:**
int[] - Der maximale Probenwert.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Liest oder setzt die min sample value.

**Returns:**
int[] - Der minimale Probenwert.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Die Mehrseitenoptionen

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Liest oder setzt die Ausrichtung.

**Returns:**
int - Die Orientierung.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Liest den page name.

**Returns:**
java.lang.String - Der Seitenname.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Liest oder setzt das page number tag.

**Returns:**
int[] - Das Seitenzahl‑Tag.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ruft die Farbpalette ab oder legt sie fest.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Liest oder setzt die photometric.

**Returns:**
int - Die Photometrie.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Liest oder setzt die planare Konfiguration.

**Returns:**
int - Die planare Konfiguration.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Liest oder setzt den predictor für LZW compression.

**Returns:**
int - Der Prädiktortyp.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen.

**Returns:**
boolean -  true  wenn Komponenten vormultipliziert werden müssen; andernfalls,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Liest oder setzt die Auflösungseinheit.

**Returns:**
int - Die Auflösungseinheit.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Liest oder setzt die rows per strip.

**Returns:**
long - Die Zeilen pro Streifen.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Liest oder setzt das sample format.

**Returns:**
int[] - Das Sample-Format.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Liest die Proben pro Pixel. Um diesen Eigenschaftswert zu ändern, verwenden Sie den  BitsPerSample  Eigenschaftssetter.

**Returns:**
int - Die Proben pro Pixel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Liest oder setzt den scanner manufacturer.

**Returns:**
java.lang.String - Der Scannerhersteller.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Liest oder setzt das scanner model.

**Returns:**
java.lang.String - Das Scanner-Modell.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Liest oder setzt den maximalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte, Short oder Long Typ).

**Returns:**
long[] - Der maximale Sample-Wert.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Liest oder setzt den minimalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte, Short oder Long Typ).

**Returns:**
long[] - Der minimale Sample-Wert.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Liest oder setzt den software type.

**Returns:**
java.lang.String - Der Softwaretyp.
### getSource() {#getSource--}
```
public final Source getSource()
```


Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest.

Wert: Die Quelle, in der das Bild erstellt wird.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Liest oder setzt die strip byte counts.

**Returns:**
long[] - Die Byte-Anzahlen der Streifen.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Liest oder setzt die strip offsets.

**Returns:**
long[] - Die Streifen-Offsets.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Liest oder setzt eine allgemeine Angabe über die Art der Daten, die in dieser subfile enthalten sind.

**Returns:**
long - Der allgemeine Hinweis auf die Art der in dieser Unterdatei enthaltenen Daten.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Liest die instance des tags nach Typ.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagKey | int | Der Tag-Schlüssel. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Liest oder setzt die tags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Die Tags.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Liest oder setzt den target printer.

**Returns:**
java.lang.String - Der Ziel-Drucker.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Liest oder setzt das threshholding.

**Returns:**
int - Der Schwellenwert.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Liest oder setzt die tile byte counts.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Liest ot setzt tile length.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Liest oder setzt die Kachelversätze.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Liest oder setzt die Kachelbreite.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Liest die Gesamtseiten.

**Returns:**
int - Die Gesamtseiten.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Liest die gültige Tag-Anzahl. Dies ist nicht die Gesamtzahl der Tags, sondern die Anzahl der Tags, die erhalten bleiben können.

**Returns:**
int - Die gültige Tag-Anzahl.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Gibt die Anzahl gültiger Tags zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Die zu validierenden Tags. |

**Returns:**
int - Die Anzahl gültiger Tags.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Liest den Bildautor, der von Windows Explorer verwendet wird.

Wert: Bildautor, verwendet von Windows Explorer. Der  XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) wird von Windows Explorer ignoriert, wenn das  Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) Tag existiert.

**Returns:**
java.lang.String - Bildautor, der von Windows Explorer verwendet wird.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Liest den Kommentar zum Bild, der von Windows Explorer verwendet wird.

Wert: Kommentar zum Bild, verwendet von Windows Explorer.

**Returns:**
java.lang.String - Kommentar zum Bild, das von Windows Explorer verwendet wird.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Liest das Bildthema, das von Windows Explorer verwendet wird.

Wert: Betreffbild, verwendet von Windows Explorer.

**Returns:**
java.lang.String - Betreffbild, das von Windows Explorer verwendet wird.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Liest Informationen zum Bild, die von Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer.

**Returns:**
java.lang.String - Informationen zum Bild, das von Windows Explorer verwendet wird.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Liest Informationen zum Bild, die von Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer. Der  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) wird von Windows Explorer ignoriert, wenn das  ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) Tag existiert.

**Returns:**
java.lang.String - Informationen zum Bild, das von Windows Explorer verwendet wird.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ruft den XMP-Metadatencontainer ab oder legt ihn fest.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Liest oder setzt die x-Position.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Liest oder setzt die X‑Auflösung.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Liest oder setzt die YCbCrCoefficients.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Die YCbCr-Koeffizienten.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Liest oder setzt die Subsampling-Faktoren für YCbCr-Photometrie.

**Returns:**
int[] - Die Subsampling-Faktoren für YCbCr-Photometrie.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Liest oder setzt die y-Position.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Liest oder setzt die Y‑Auflösung.

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


Liest einen Wert, der angibt, ob die zusätzlichen Proben vorhanden sind.

**Returns:**
boolean -  true  wenn die zusätzlichen Proben vorhanden sind; andernfalls  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tag | int | Die Tag-ID zum Prüfen. |

**Returns:**
boolean -  true  wenn das Tag vorhanden ist; andernfalls  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Liest einen Wert, der angibt, ob das Bild gekachelt ist.

**Returns:**
boolean -  true  wenn das Bild kachelartig ist; andernfalls  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Gibt einen Wert zurück, der angibt, ob die  TiffOptions  korrekt konfiguriert wurden. Verwenden Sie die Validate-Methode, um den Grund für das Scheitern zu finden.

**Returns:**
boolean -  true  wenn TiffOptions korrekt konfiguriert sind; andernfalls  false .
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


Entfernt das Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tag | int | Das zu entfernende Tag. |

**Returns:**
boolean - true wenn erfolgreich entfernt
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Liest oder setzt die Alpha-Speicheroption. Optionen außer TiffAlphaStorage.Unspecified werden verwendet, wenn mehr als 3 SamplesPerPixel definiert sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Alpha-Speicheroption. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Liest oder setzt den Künstler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Künstler. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Liest oder setzt die Farbe des Hintergrunds. Wird für interne Zwecke verwendet, um die Hintergrundfarbe des Bildes zu speichern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Die Hintergrundfarbe. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Setzt die Bits pro Probe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Der Bits‑pro‑Sample‑Wert. |

Beim Setzen dieses Wertes beachten Sie, dass dadurch auch der SamplesPerPixel‑Wert auf die Array‑Länge gesetzt wird. Diese 2 Eigenschaften sind sehr eng gekoppelt, sodass sie nur zusammen gesetzt werden können. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Liest oder setzt einen Wert, der die Byte-Reihenfolge von TIFF angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Liest oder setzt die Farbkarte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Farbkarte. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Setzt die Qualität des komprimierten Bildes. Wird mit der JPEG-Kompression verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Komprimierte Bildqualität. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Setzt die Kompression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Komprimierung. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Setzt das Urheberrecht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Das Urheberrecht. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Liest oder setzt Datum und Uhrzeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Das Datum und die Uhrzeit. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Liest oder setzt das Standard-Limit für Speicherzuweisungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das standardmäßige Speicherzuweisungs-Limit. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Ruft die Standardschriftart für den Ersatz ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die Schriftart der vorhandenen Ebene in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann folgender Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Wert: Die Standardschriftart für den Ersatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Liest oder setzt den Namen des Dokuments.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Name des Dokuments. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Setzt die Werte der zusätzlichen Proben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Der Wert der zusätzlichen Proben. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Liest oder setzt die Fax‑T4‑Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Fax-T4-Optionen. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Liest oder setzt den TIFF-Dateistandard.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der TIFF-Dateistandard. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Liest oder setzt die Füllreihenfolge der Byte‑Bits.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Byte-Bit-Füllreihenfolge. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Legt einen Wert fest, der angibt, ob [full frame].

Wert:  true  wenn [full frame]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [full frame]. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Liest oder setzt die halftone hints.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Halftone-Hinweise. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Setzt den ICC-Profil-Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] | Das icc-Profil. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird.

Wert:  true  wenn nach dem Erstellen-Ereignis ignoriert wird; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Liest oder setzt die Bildbeschreibung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die Bildbeschreibung. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Liest oder setzt die Bildlänge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Bildlänge. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Liest oder setzt die Bildbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Bildbreite. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Liest oder setzt die ink names.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die Tintenamen. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Liest oder setzt die max sample value.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Der maximale Probenwert. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Liest oder setzt die min sample value.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Der minimale Probenwert. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Die Mehrseitenoptionen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Liest oder setzt die Ausrichtung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Ausrichtung. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Liest den page name.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Seitenname. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Liest oder setzt das page number tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Das Seitenzahl-Tag. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ruft die Farbpalette ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Liest oder setzt die photometric.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Photometrie. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Liest oder setzt die planare Konfiguration.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die planare Konfiguration. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Liest oder setzt den predictor für LZW compression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Prädiktortyp. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true, wenn Komponenten vormultipliziert werden müssen; andernfalls false. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Liest oder setzt die Auflösungseinheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Auflösungseinheit. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Liest oder setzt die rows per strip.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Zeilen pro Streifen. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Liest oder setzt das sample format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Das Probenformat. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Liest oder setzt den scanner manufacturer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Scanner-Hersteller. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Liest oder setzt das scanner model.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Das Scanner-Modell. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Liest oder setzt den maximalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte, Short oder Long Typ).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Der maximale Probenwert. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Liest oder setzt den minimalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte, Short oder Long Typ).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Der minimale Probenwert. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Liest oder setzt den software type.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Softwaretyp. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest.

Wert: Die Quelle, in der das Bild erstellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Liest oder setzt die strip byte counts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Die Byte-Anzahl der Streifen. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Liest oder setzt die strip offsets.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Die Streifen-Offsets. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Liest oder setzt eine allgemeine Angabe über die Art der Daten, die in dieser subfile enthalten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die allgemeine Angabe der Art der in dieser Unterdatei enthaltenen Daten. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Liest oder setzt die tags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Die Tags. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Liest oder setzt den target printer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Ziel-Drucker. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Liest oder setzt das threshholding.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Schwellenwertbestimmung. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Liest oder setzt die tile byte counts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Liest ot setzt tile length.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Liest oder setzt die Kachelversätze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Liest oder setzt die Kachelbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Setzt den Bildautor, der von Windows Explorer verwendet wird.

Wert: Bildautor, verwendet von Windows Explorer. Der  XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) wird von Windows Explorer ignoriert, wenn das  Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) Tag existiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Bildautor, der von Windows Explorer verwendet wird. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Setzt den Kommentar zum Bild, der von Windows Explorer verwendet wird.

Wert: Kommentar zum Bild, verwendet von Windows Explorer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Kommentar zum Bild, der von Windows Explorer verwendet wird. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Legt das Quellbild fest, das vom Windows Explorer verwendet wird.

Wert: Betreffbild, verwendet von Windows Explorer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Betreff des Bildes, der von Windows Explorer verwendet wird. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Legt Informationen über das Bild fest, die vom Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Informationen zum Bild, die von Windows Explorer verwendet werden. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Legt Informationen über das Bild fest, die vom Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer. Der  XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) wird von Windows Explorer ignoriert, wenn das  ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) Tag existiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Informationen zum Bild, die von Windows Explorer verwendet werden. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ruft den XMP-Metadatencontainer ab oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Der XMP-Datencontainer. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Liest oder setzt die x-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Die x-Position. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Liest oder setzt die X‑Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Die x-Auflösung. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Liest oder setzt die YCbCrCoefficients.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Die YCbCrCoefficients. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Liest oder setzt die Subsampling-Faktoren für YCbCr-Photometrie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Subsampling-Faktoren für YCbCr-photometrisch. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Liest oder setzt die y-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Die y-Position. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Liest oder setzt die Y‑Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Die y-Auflösung. |

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


Validiert, ob die Optionen eine gültige Kombination von Tags haben

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

