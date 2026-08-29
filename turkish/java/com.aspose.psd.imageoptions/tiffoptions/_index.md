---
title: "TiffOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "TIFF dosya formatı seçenekleri."
type: docs
weight: 25
url: /tr/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Tiff dosya formatı seçenekleri. Genişlik ve yükseklik etiketlerinin, görüntü oluşturulurken genişlik ve yükseklik parametreleriyle üzerine yazılacağını, bu yüzden doğrudan belirtilmelerine gerek olmadığını unutmayın. Birçok seçeneğin varsayılan bir değer döndürdüğü, bunun bu seçeneğin etiket değeri olarak açıkça ayarlandığı anlamına gelmediğini unutmayın. Etiketin mevcut olduğunu doğrulamak için Tags property veya ilgili IsTagPresent method kullanın.

UYARI! Kaydetme sırasında tiff seçeneklerini asla değiştirmeyin, çünkü bu yan etkilere ve bulunması zor hatalara neden olabilir. Aşağıdaki satır, veri başlangıcının yanlış belirlenmesine yol açtığı için özellikle yorum satırı olarak bırakıldı. Geçen seçenekler spp içermiyordu (bu durumda seçenekler doğru olmasa da bu senaryo hatalara yol açar) ve sonraki satır +spp etiketi +bpp etiketi eklenmesine neden oldu ve seçenekler veri tamamen yazıldıktan sonra yazıldığında sıkıştırılmamış codec için veri başlangıcını üzerine yazdılar!!! TiffUncompressedCodec.Encode bakın. this.Options.SamplesPerPixel = 3;
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | TiffOptions sınıfının yeni bir örneğini başlatır. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | TiffOptions sınıfının yeni bir örneğini başlatır. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | TiffOptions sınıfının yeni bir örneğini başlatır. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | TiffOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Yeni bir etiket ekler. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Etiketleri ekler. |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Bu örneği klonlar. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Alfa depolama seçeneğini alır veya ayarlar. |
| [getArtist()](#getArtist--) | Sanatçıyı alır veya ayarlar. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Arka plan rengini alır veya ayarlar. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Piksel başına bit sayısını alır. |
| [getBitsPerSample()](#getBitsPerSample--) | Örnek başına bit sayısını alır. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [getByteOrder()](#getByteOrder--) | Tiff bayt sırasını gösteren bir değeri alır veya ayarlar. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Önbelleği alır. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Renk haritasını alır veya ayarlar. |
| [getCompressedQuality()](#getCompressedQuality--) | Sıkıştırılmış görüntü kalitesini alır. |
| [getCompression()](#getCompression--) | Sıkıştırmayı alır. |
| [getCopyright()](#getCopyright--) | Telif hakkını alır. |
| [getDateTime()](#getDateTime--) | Tarih ve saat alır veya ayarlar. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getDocumentName()](#getDocumentName--) | Belgenin adını alır veya ayarlar. |
| [getExifIfd()](#getExifIfd--) | EXIF IFD işaretçisini alır veya ayarlar. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Ek örnek sayısını alır. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Ek örnek değerlerini alır. |
| [getFaxT4Options()](#getFaxT4Options--) | Faks t4 seçeneklerini alır veya ayarlar. |
| [getFileStandard()](#getFileStandard--) | TIFF dosya standardını alır veya ayarlar. |
| [getFillOrder()](#getFillOrder--) | Bayt bit doldurma sırasını alır veya ayarlar. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeve olup olmadığını gösteren bir değeri alır. |
| [getHalfToneHints()](#getHalfToneHints--) | Yarı ton ipuçlarını alır veya ayarlar. |
| [getIccProfile()](#getIccProfile--) | icc profil akışını alır. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [getImageDescription()](#getImageDescription--) | Alır veya ayarlar görüntü açıklamasını. |
| [getImageLength()](#getImageLength--) | Alır veya ayarlar görüntü uzunluğunu. |
| [getImageWidth()](#getImageWidth--) | Alır veya ayarlar görüntü genişliğini. |
| [getInkNames()](#getInkNames--) | Mürekkep adlarını alır veya ayarlar. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Maksimum örnek değerini alır veya ayarlar. |
| [getMinSampleValue()](#getMinSampleValue--) | Minimum örnek değerini alır veya ayarlar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Çok sayfalı seçenekler |
| [getOrientation()](#getOrientation--) | Alır veya ayarlar yönelimi. |
| [getPageName()](#getPageName--) | Sayfa adını alır veya ayarlar. |
| [getPageNumber()](#getPageNumber--) | Sayfa numarası etiketini alır veya ayarlar. |
| [getPalette()](#getPalette--) | Renk paletini alır veya ayarlar. |
| [getPhotometric()](#getPhotometric--) | Fotometrik değerini alır veya ayarlar. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Alır veya ayarlar düzlemsel yapılandırmayı. |
| [getPredictor()](#getPredictor--) | LZW sıkıştırması için tahmin ediciyi alır veya ayarlar. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [getResolutionSettings()](#getResolutionSettings--) | Çözünürlük ayarlarını alır veya ayarlar. |
| [getResolutionUnit()](#getResolutionUnit--) | Alır veya ayarlar çözünürlük birimini. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Şerit başına satır sayısını alır veya ayarlar. |
| [getSampleFormat()](#getSampleFormat--) | Örnek formatını alır veya ayarlar. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Piksel başına örnek sayısını alır. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Tarayıcı üreticisini alır veya ayarlar. |
| [getScannerModel()](#getScannerModel--) | Tarayıcı modelini alır veya ayarlar. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Maksimum örnek değerini alır veya ayarlar. |
| [getSminSampleValue()](#getSminSampleValue--) | Minimum örnek değerini alır veya ayarlar. |
| [getSoftwareType()](#getSoftwareType--) | Yazılım tipini alır veya ayarlar. |
| [getSource()](#getSource--) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [getStripByteCounts()](#getStripByteCounts--) | Şerit bayt sayısını alır veya ayarlar. |
| [getStripOffsets()](#getStripOffsets--) | Şerit ofsetlerini alır veya ayarlar. |
| [getSubFileType()](#getSubFileType--) | Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Etiketin türüne göre örneğini alır. |
| [getTags()](#getTags--) | Etiketleri alır veya ayarlar. |
| [getTargetPrinter()](#getTargetPrinter--) | Hedef yazıcıyı alır veya ayarlar. |
| [getThreshholding()](#getThreshholding--) | Eşikleme değerini alır veya ayarlar. |
| [getTileByteCounts()](#getTileByteCounts--) | Döşeme bayt sayılarını alır veya ayarlar. |
| [getTileLength()](#getTileLength--) | Döşeme uzunluğunu alır veya ayarlar. |
| [getTileOffsets()](#getTileOffsets--) | Döşeme ofsetlerini alır veya ayarlar. |
| [getTileWidth()](#getTileWidth--) | Döşeme genişliğini alır veya ayarlar. |
| [getTotalPages()](#getTotalPages--) | Toplam sayfaları alır. |
| [getValidTagCount()](#getValidTagCount--) | Geçerli etiket sayısını alır. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Geçerli etiket sayısını alır. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [getXPAuthor()](#getXPAuthor--) | Windows Gezgini tarafından kullanılan görüntü yazarını alır. |
| [getXPComment()](#getXPComment--) | Windows Gezgini tarafından kullanılan görüntü yorumunu alır. |
| [getXPKeywords()](#getXPKeywords--) | Windows Gezgini tarafından kullanılan konu görüntüsünü alır. |
| [getXPSubject()](#getXPSubject--) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır. |
| [getXPTitle()](#getXPTitle--) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır. |
| [getXmpData()](#getXmpData--) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [getXposition()](#getXposition--) | x konumunu alır veya ayarlar. |
| [getXresolution()](#getXresolution--) | Alır veya ayarlar x çözünürlüğünü. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | YCbCrKatsayılarını alır veya ayarlar. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| [getYposition()](#getYposition--) | y konumunu alır veya ayarlar. |
| [getYresolution()](#getYresolution--) | Alır veya ayarlar y çözünürlüğünü. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Ek örneklerin mevcut olup olmadığını gösteren bir değeri alır. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Etiketin seçeneklerde bulunup bulunmadığını belirler. |
| [isTiled()](#isTiled--) | Görüntünün döşenmiş olup olmadığını gösteren bir değeri alır. |
| [isValid()](#isValid--) | TiffOptions'ın doğru şekilde yapılandırılıp yapılandırılmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Etiketi kaldırır. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Alfa depolama seçeneğini alır veya ayarlar. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sanatçıyı alır veya ayarlar. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Arka plan rengini alır veya ayarlar. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Örnek başına bitleri ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar. |
| [setByteOrder(int value)](#setByteOrder-int-) | Tiff bayt sırasını gösteren bir değeri alır veya ayarlar. |
| [setColorMap(int[] value)](#setColorMap-int---) | Renk haritasını alır veya ayarlar. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Sıkıştırılmış görüntü kalitesini ayarlar. |
| [setCompression(int value)](#setCompression-int-) | Sıkıştırmayı ayarlar. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Telif hakkını ayarlar. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Tarih ve saat alır veya ayarlar. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Varsayılan yedek yazı tipini alır veya ayarlar (rastera dışa aktarırken metni çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Belgenin adını alır veya ayarlar. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Ek örnek değerlerini ayarlar. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Faks t4 seçeneklerini alır veya ayarlar. |
| [setFileStandard(int value)](#setFileStandard-int-) | TIFF dosya standardını alır veya ayarlar. |
| [setFillOrder(int value)](#setFillOrder-int-) | Bayt bit doldurma sırasını alır veya ayarlar. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Tam çerçeve olup olmadığını gösteren bir değeri ayarlar. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Yarı ton ipuçlarını alır veya ayarlar. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | ICC profil akışını ayarlar. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Alır veya ayarlar görüntü açıklamasını. |
| [setImageLength(long value)](#setImageLength-long-) | Alır veya ayarlar görüntü uzunluğunu. |
| [setImageWidth(long value)](#setImageWidth-long-) | Alır veya ayarlar görüntü genişliğini. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Mürekkep adlarını alır veya ayarlar. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Maksimum örnek değerini alır veya ayarlar. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Minimum örnek değerini alır veya ayarlar. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Çok sayfalı seçenekler |
| [setOrientation(int value)](#setOrientation-int-) | Alır veya ayarlar yönelimi. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Sayfa adını alır veya ayarlar. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Sayfa numarası etiketini alır veya ayarlar. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Renk paletini alır veya ayarlar. |
| [setPhotometric(int value)](#setPhotometric-int-) | Fotometrik değerini alır veya ayarlar. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Alır veya ayarlar düzlemsel yapılandırmayı. |
| [setPredictor(int value)](#setPredictor-int-) | LZW sıkıştırması için tahmin ediciyi alır veya ayarlar. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | İlerleme olayı işleyicisini alır veya ayarlar. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Çözünürlük ayarlarını alır veya ayarlar. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Alır veya ayarlar çözünürlük birimini. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Şerit başına satır sayısını alır veya ayarlar. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Örnek formatını alır veya ayarlar. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Tarayıcı üreticisini alır veya ayarlar. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Tarayıcı modelini alır veya ayarlar. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Maksimum örnek değerini alır veya ayarlar. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Minimum örnek değerini alır veya ayarlar. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Yazılım tipini alır veya ayarlar. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Görselin oluşturulacağı kaynağı alır veya ayarlar. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Şerit bayt sayısını alır veya ayarlar. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Şerit ofsetlerini alır veya ayarlar. |
| [setSubFileType(long value)](#setSubFileType-long-) | Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Etiketleri alır veya ayarlar. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Hedef yazıcıyı alır veya ayarlar. |
| [setThreshholding(int value)](#setThreshholding-int-) | Eşikleme değerini alır veya ayarlar. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Döşeme bayt sayılarını alır veya ayarlar. |
| [setTileLength(long value)](#setTileLength-long-) | Döşeme uzunluğunu alır veya ayarlar. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Döşeme ofsetlerini alır veya ayarlar. |
| [setTileWidth(long value)](#setTileWidth-long-) | Döşeme genişliğini alır veya ayarlar. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntü yazarını ayarlar. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntü üzerindeki yorumu ayarlar. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Windows Gezgini tarafından kullanılan konu görüntüsünü ayarlar. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgiyi ayarlar. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgiyi ayarlar. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | x konumunu alır veya ayarlar. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Alır veya ayarlar x çözünürlüğünü. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | YCbCrKatsayılarını alır veya ayarlar. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | y konumunu alır veya ayarlar. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Alır veya ayarlar y çözünürlüğünü. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Seçeneklerin geçerli bir etiket kombinasyonuna sahip olup olmadığını doğrular |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


TiffOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expectedFormat | int | Beklenen tiff dosya formatı. |
| byteOrder | int | Kullanılacak tiff dosya formatı bayt sırası. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


TiffOptions sınıfının yeni bir örneğini başlatır. Varsayılan olarak küçük endian kuralı kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expectedFormat | int | Beklenen tiff dosya formatı. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


TiffOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Kopyalanacak seçenekler. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


TiffOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Seçenekleri başlatmak için kullanılacak etiketler. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Yeni bir etiket ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Eklenecek etiket. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Etiketleri ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Eklenecek etiketler. |

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


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Bu örneği klonlar.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Bu örneği klonlar.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Alfa depolama seçeneğini alır veya ayarlar. TiffAlphaStorage.Unspecified dışındaki seçenekler, 3'ten fazla SamplesPerPixel tanımlandığında kullanılır.

**Returns:**
int - Alfa depolama seçeneği.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Sanatçıyı alır veya ayarlar.

**Returns:**
java.lang.String - Sanatçı.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Arka plan rengini alır veya ayarlar. Görüntünün arka plan rengini depolamak için dahili amaçlarla kullanılır.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Piksel başına bit sayısını alır.

**Returns:**
int - Piksel başına bitler.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Örnek başına bit sayısını alır.

**Returns:**
int[] - Örnek başına bit değeri.

Bu değeri ayarlarken, aynı zamanda SamplesPerPixel değerini dizi uzunluğuna ayarlayacağını unutmayın. Bu iki özellik çok sıkı bir şekilde bağlıdır, bu yüzden yalnızca birlikte ayarlanabilir.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Tiff bayt sırasını gösteren bir değeri alır veya ayarlar.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Önbelleği alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| etiket | int | Etiket (dizi türüdür). |

**Returns:**
long[] - Etiket değeri.
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


Renk haritasını alır veya ayarlar.

**Returns:**
int[] - Renk haritası.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Sıkıştırılmış görüntü kalitesini alır. Jpeg sıkıştırmasıyla birlikte kullanılır.

**Returns:**
int - sıkıştırılmış görüntü kalitesi.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Sıkıştırmayı alır.

**Returns:**
int - Sıkıştırma.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Telif hakkını alır.

**Returns:**
java.lang.String - Telif hakkı.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Tarih ve saat alır veya ayarlar.

**Returns:**
java.lang.String - Tarih ve saat.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Varsayılan bellek tahsis sınırını alır veya ayarlar.

**Returns:**
int - Varsayılan bellek tahsis sınırı.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Varsayılan değiştirme yazı tipini alır veya ayarlar (yazı tipi, rastera dışa aktarırken metin çizerken kullanılacak, PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Değer: Varsayılan değiştirme yazı tipi.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Belgenin adını alır veya ayarlar.

**Returns:**
java.lang.String - Belgenin adı.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


EXIF IFD işaretçisini alır veya ayarlar.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Ek örnek sayısını alır.

Değer: Ek örnek sayısı.

**Returns:**
long - ek örnek sayısı.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Ek örnek değerlerini alır.

Değer: Ek örneklerin değeri.

**Returns:**
int[] - ek örneklerin değerleri.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Faks t4 seçeneklerini alır veya ayarlar.

**Returns:**
long - Fax t4 seçenekleri.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


TIFF dosya standardını alır veya ayarlar.

**Returns:**
int - TIFF dosya standardı.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Bayt bit doldurma sırasını alır veya ayarlar.

**Returns:**
int - Bayt bitlerinin doldurma sırası.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Tam çerçeve olup olmadığını gösteren bir değeri alır.

Değer:  true  eğer [full frame]; aksi takdirde,  false .

**Returns:**
boolean - [full frame] olup olmadığını gösteren bir değer.
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Yarı ton ipuçlarını alır veya ayarlar.

**Returns:**
int[] - Yarı ton ipuçları.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


icc profil akışını alır.

**Returns:**
byte[] - icc profili.
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


Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar.

Değer:  true  oluşturma olayından sonra yok sayılırsa; aksi takdirde,  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Alır veya ayarlar görüntü açıklamasını.

**Returns:**
java.lang.String - Görüntü açıklaması.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Alır veya ayarlar görüntü uzunluğunu.

**Returns:**
long - Görüntü uzunluğu.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Alır veya ayarlar görüntü genişliğini.

**Returns:**
long - Görüntü genişliği.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Mürekkep adlarını alır veya ayarlar.

**Returns:**
java.lang.String - Mürekkep adları.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Maksimum örnek değerini alır veya ayarlar.

**Returns:**
int[] - Azami örnek değeri.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Minimum örnek değerini alır veya ayarlar.

**Returns:**
int[] - Minimum örnek değeri.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Çok sayfalı seçenekler

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Alır veya ayarlar yönelimi.

**Returns:**
int - Yön.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Sayfa adını alır veya ayarlar.

**Returns:**
java.lang.String - Sayfa adı.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Sayfa numarası etiketini alır veya ayarlar.

**Returns:**
int[] - Sayfa numarası etiketi.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Renk paletini alır veya ayarlar.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Fotometrik değerini alır veya ayarlar.

**Returns:**
int - Fotometrik.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Alır veya ayarlar düzlemsel yapılandırmayı.

**Returns:**
int - Düzlemsel yapılandırma.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


LZW sıkıştırması için tahmin ediciyi alır veya ayarlar.

**Returns:**
int - Tahminci tipi.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean -  true  ise bileşenler önceden çarpılmış olmalıdır; aksi takdirde,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


İlerleme olayı işleyicisini alır veya ayarlar.

Değer: İlerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Çözünürlük ayarlarını alır veya ayarlar.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Alır veya ayarlar çözünürlük birimini.

**Returns:**
int - Çözünürlük birimi.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Şerit başına satır sayısını alır veya ayarlar.

**Returns:**
long - Şerit başına satır sayısı.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Örnek formatını alır veya ayarlar.

**Returns:**
int[] - Örnek biçimi.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Piksel başına örnekleri alır. Bu özellik değerini değiştirmek için  BitsPerSample  özellik ayarlayıcısını kullanın.

**Returns:**
int - Piksel başına örnek sayısı.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Tarayıcı üreticisini alır veya ayarlar.

**Returns:**
java.lang.String - Tarayıcı üreticisi.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Tarayıcı modelini alır veya ayarlar.

**Returns:**
java.lang.String - Tarayıcı modeli.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Maksimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Returns:**
long[] - Maksimum örnek değeri.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Minimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Returns:**
long[] - Minimum örnek değeri.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Yazılım tipini alır veya ayarlar.

**Returns:**
java.lang.String - Yazılım türü.
### getSource() {#getSource--}
```
public final Source getSource()
```


Görselin oluşturulacağı kaynağı alır veya ayarlar.

Değer: Görüntünün oluşturulacağı kaynak.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Şerit bayt sayısını alır veya ayarlar.

**Returns:**
long[] - Şerit bayt sayıları.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Şerit ofsetlerini alır veya ayarlar.

**Returns:**
long[] - Şerit ofsetleri.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar.

**Returns:**
long - Bu alt dosyada bulunan veri türünün genel göstergesi.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Etiketin türüne göre örneğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagKey | int | Etiket anahtarı. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Etiketleri alır veya ayarlar.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Etiketler.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Hedef yazıcıyı alır veya ayarlar.

**Returns:**
java.lang.String - Hedef yazıcı.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Eşikleme değerini alır veya ayarlar.

**Returns:**
int - Eşikleme.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Döşeme bayt sayılarını alır veya ayarlar.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Döşeme uzunluğunu alır veya ayarlar.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Döşeme ofsetlerini alır veya ayarlar.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Döşeme genişliğini alır veya ayarlar.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Toplam sayfaları alır.

**Returns:**
int - Toplam sayfa sayısı.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Geçerli etiket sayısını alır. Bu, toplam etiket sayısı değil, korunabilecek etiketlerin sayısıdır.

**Returns:**
int - Geçerli etiket sayısı.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Geçerli etiket sayısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Doğrulanacak etiketler. |

**Returns:**
int - Geçerli etiket sayısı.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Vektör rasterleştirme seçeneklerini alır veya ayarlar.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Windows Gezgini tarafından kullanılan görüntü yazarını alır.

Değer: Görüntü Yazarı, Windows Explorer tarafından kullanılır. XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) Windows Explorer tarafından, Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) etiketi mevcutsa yok sayılır.

**Returns:**
java.lang.String - Görüntü yazarı, Windows Explorer tarafından kullanılır.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Windows Gezgini tarafından kullanılan görüntü yorumunu alır.

Değer: Görüntü yorumu, Windows Explorer tarafından kullanılır.

**Returns:**
java.lang.String - Görüntü yorumu, Windows Explorer tarafından kullanılır.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Windows Gezgini tarafından kullanılan konu görüntüsünü alır.

Değer: Görüntü konusu, Windows Explorer tarafından kullanılır.

**Returns:**
java.lang.String - Görüntü konusu, Windows Explorer tarafından kullanılır.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır.

Değer: Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır.

**Returns:**
java.lang.String - Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır.

Değer: Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır. XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) Windows Explorer tarafından, ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) etiketi mevcutsa yok sayılır.

**Returns:**
java.lang.String - Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP meta veri kapsayıcısını alır veya ayarlar.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


x konumunu alır veya ayarlar.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Alır veya ayarlar x çözünürlüğünü.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


YCbCrKatsayılarını alır veya ayarlar.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - YCbCr Katsayıları.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar.

**Returns:**
int[] - YCbCr fotometrik için alt örnekleme faktörleri.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


y konumunu alır veya ayarlar.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Alır veya ayarlar y çözünürlüğünü.

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


Ek örneklerin mevcut olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean -  true  eğer ekstra örnekler mevcutsa; aksi takdirde,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Etiketin seçeneklerde bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| etiket | int | Kontrol edilecek etiket kimliği. |

**Returns:**
boolean -  true  eğer etiket mevcutsa; aksi takdirde,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Görüntünün döşenmiş olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean -  true  eğer görüntü döşeliyse; aksi takdirde,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


TiffOptions'ın doğru bir şekilde yapılandırılıp yapılandırılmadığını gösteren bir değer alır. Hata nedenini bulmak için Validate yöntemini kullanın.

**Returns:**
boolean -  true  eğer TiffOptions doğru yapılandırılmışsa; aksi takdirde,  false .
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


Etiketi kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| etiket | int | Kaldırılacak etiket. |

**Returns:**
boolean - true eğer başarıyla kaldırıldı
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Alfa depolama seçeneğini alır veya ayarlar. TiffAlphaStorage.Unspecified dışındaki seçenekler, 3'ten fazla SamplesPerPixel tanımlandığında kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Alfa depolama seçeneği. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Sanatçıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Sanatçı. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Arka plan rengini alır veya ayarlar. Görüntünün arka plan rengini depolamak için dahili amaçlarla kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Arka planın rengi. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Örnek başına bitleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Örnek başına bit değeri. |

Bu değeri ayarlarken, aynı zamanda SamplesPerPixel değerinin dizi uzunluğuna ayarlanacağını unutmayın. Bu iki özellik çok sıkı bir şekilde bağlanmıştır, bu yüzden yalnızca birlikte ayarlanabilir. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucunu alır veya ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Tiff bayt sırasını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Renk haritasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Renk haritası. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Sıkıştırılmış görüntü kalitesini ayarlar. Jpeg sıkıştırmasıyla birlikte kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | sıkıştırılmış görüntü kalitesi. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Sıkıştırmayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Sıkıştırma. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Telif hakkını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Telif hakkı. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Tarih ve saat alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Tarih ve saat. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Varsayılan bellek tahsis sınırını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Varsayılan bellek tahsis sınırı. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Varsayılan değiştirme yazı tipini alır veya ayarlar (yazı tipi, rastera dışa aktarırken metin çizerken kullanılacak, PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Değer: Varsayılan değiştirme yazı tipi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Belgenin adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Belgenin adı. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Ek örnek değerlerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Ek örnek değeri. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Faks t4 seçeneklerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Fax t4 seçenekleri. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


TIFF dosya standardını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | TIFF dosya standardı. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Bayt bit doldurma sırasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bayt bit doldurma sırası. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Tam çerçeve olup olmadığını gösteren bir değeri ayarlar.

Değer:  true  eğer [full frame]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [full frame] olup olmadığını gösteren bir değer. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Yarı ton ipuçlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Yarı ton ipuçları. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


ICC profil akışını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] | Bu icc profili. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Oluşturma olayından sonra yoksayma durumunu gösteren bir değeri alır veya ayarlar.

Değer:  true  oluşturma olayından sonra yok sayılırsa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Alır veya ayarlar görüntü açıklamasını.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Görüntü açıklaması. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Alır veya ayarlar görüntü uzunluğunu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Görüntü uzunluğu. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Alır veya ayarlar görüntü genişliğini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Görüntü genişliği. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Mürekkep adlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Mürekkep adları. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Maksimum örnek değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Maksimum örnek değeri. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Minimum örnek değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Minimum örnek değeri. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Çok sayfalı seçenekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Alır veya ayarlar yönelimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yönlendirme. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Sayfa adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Sayfa adı. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Sayfa numarası etiketini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Sayfa numarası etiketi. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Renk paletini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Fotometrik değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Fotometrik. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Alır veya ayarlar düzlemsel yapılandırmayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Planar yapılandırma. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


LZW sıkıştırması için tahmin ediciyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Tahminci türü. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer bileşenlerin önceden çarpılması gerekiyorsa; aksi takdirde,  false . |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


İlerleme olayı işleyicisini alır veya ayarlar.

Değer: İlerleme olayı işleyicisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Çözünürlük ayarlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Alır veya ayarlar çözünürlük birimini.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Çözünürlük birimi. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Şerit başına satır sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Şerit başına satır sayısı. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Örnek formatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Örnek formatı. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Tarayıcı üreticisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Tarayıcı üreticisi. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Tarayıcı modelini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Tarayıcı modeli. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Maksimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Maksimum örnek değeri. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Minimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Minimum örnek değeri. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Yazılım tipini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yazılım türü. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Görselin oluşturulacağı kaynağı alır veya ayarlar.

Değer: Görüntünün oluşturulacağı kaynak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Şerit bayt sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Şerit bayt sayıları. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Şerit ofsetlerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Şerit ofsetleri. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Bu alt dosyada bulunan veri türünün genel göstergesi. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Etiketleri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Etiketler. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Hedef yazıcıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Hedef yazıcı. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Eşikleme değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Eşikleme. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Döşeme bayt sayılarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Döşeme uzunluğunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Döşeme ofsetlerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Döşeme genişliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Vektör rasterleştirme seçeneklerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Windows Gezgini tarafından kullanılan görüntü yazarını ayarlar.

Değer: Image Author, Windows Explorer tarafından kullanılır. XPAuthor ([.getXPAuthor](../../null/\\#getXPAuthor)/ \\#setXPAuthor(String) ) Windows Explorer tarafından, Artist ([.getArtist](../../null/\\#getArtist)/[.setArtist(String)](../../null/\\#setArtist-String-)) etiketi mevcutsa yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | image author, Windows Explorer tarafından kullanılan. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Windows Gezgini tarafından kullanılan görüntü üzerindeki yorumu ayarlar.

Değer: Görüntü yorumu, Windows Explorer tarafından kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntü yorumu, Windows Explorer tarafından kullanılan. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Windows Gezgini tarafından kullanılan konu görüntüsünü ayarlar.

Değer: Görüntü konusu, Windows Explorer tarafından kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | konu görüntüsü, Windows Explorer tarafından kullanılan. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgiyi ayarlar.

Değer: Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntü hakkında bilgi, Windows Explorer tarafından kullanılan. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgiyi ayarlar.

Değer: Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır. XPTitle ([.getXPTitle](../../null/\\#getXPTitle)/ \\#setXPTitle(String) ) Windows Explorer tarafından, ImageDescription ([.getImageDescription](../../null/\\#getImageDescription)/[.setImageDescription(String)](../../null/\\#setImageDescription-String-)) etiketi mevcutsa yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntü hakkında bilgi, Windows Explorer tarafından kullanılan. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP meta veri kapsayıcısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP veri kapsayıcısı. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


x konumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x konumu. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Alır veya ayarlar x çözünürlüğünü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x çözünürlüğü. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


YCbCrKatsayılarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | YCbCrCoefficients. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | YCbCr fotometrik için alt örnekleme faktörleri. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


y konumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y konumu. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Alır veya ayarlar y çözünürlüğünü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y çözünürlüğü. |

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


Seçeneklerin geçerli bir etiket kombinasyonuna sahip olup olmadığını doğrular

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

