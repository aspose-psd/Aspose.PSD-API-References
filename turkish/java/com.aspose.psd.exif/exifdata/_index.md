---
title: "ExifData"
second_title: "Java için Aspose.PSD API Referansı"
description: "EXIF veri kapsayıcısı."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

EXIF veri kapsayıcısı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExifData()](#ExifData--) | ExifData sınıfının yeni bir örneğini başlatır. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | ExifData sınıfının, dizi verileriyle yeni bir örneğini başlatır. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | ExifData sınıfının, dizi verileriyle yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Açıklık değerini alır veya ayarlar. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Kamera gövdesi seri numarasını alır veya ayarlar. |
| [getBrightnessValue()](#getBrightnessValue--) | Parlaklık değerini alır veya ayarlar. |
| [getCFAPattern()](#getCFAPattern--) | CFA desenini alır veya ayarlar. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Kamera sahibinin adını alır veya ayarlar |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Renk uzayını alır veya ayarlar. |
| [getCommonTags()](#getCommonTags--) | Ortak bölüme ait etiketleri alır veya ayarlar. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Bileşen yapılandırmasını alır veya ayarlar. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar. |
| [getContrast()](#getContrast--) | Kontrastı alır veya ayarlar. |
| [getCustomRendered()](#getCustomRendered--) | Özel işlenmiş değeri alır veya ayarlar. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Sayısallaştırma tarih ve saatini alır veya ayarlar. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Orijinal tarih ve saatini alır veya ayarlar. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Cihaz ayarları açıklamasını alır veya ayarlar |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Dijital zoom oranını alır veya ayarlar. |
| [getExifTags()](#getExifTags--) | Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar. |
| [getExifVersion()](#getExifVersion--) | EXIF sürümünü alır veya ayarlar. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Pozlama sapma değerini alır veya ayarlar. |
| [getExposureIndex()](#getExposureIndex--) | Pozlama indeksini alır veya ayarlar. |
| [getExposureMode()](#getExposureMode--) | Pozlama modunu alır veya ayarlar. |
| [getExposureProgram()](#getExposureProgram--) | Pozlama programını alır veya ayarlar. |
| [getExposureTime()](#getExposureTime--) | Pozlama süresini alır veya ayarlar. |
| [getFNumber()](#getFNumber--) | F-numarasını alır veya ayarlar. |
| [getFileSource()](#getFileSource--) | Dosya kaynağı türünü alır veya ayarlar. |
| [getFlash()](#getFlash--) | Flaş'ı alır veya ayarlar. |
| [getFlashEnergy()](#getFlashEnergy--) | Flaş enerjisini alır veya ayarlar. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Flaş pix sürümünü alır veya ayarlar. |
| [getFocalLength()](#getFocalLength--) | Odak uzaklığını alır veya ayarlar. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | 35 mm filmde odak uzaklığını alır veya ayarlar. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Odak düzlemi çözünürlük birimini alır veya ayarlar. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Odak düzlemi x çözünürlüğünü alır veya ayarlar. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Odak düzlemi y çözünürlüğünü alır veya ayarlar. |
| [getGPSAltitude()](#getGPSAltitude--) | GPS yüksekliğini alır veya ayarlar. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | GPS bölge bilgisini alır veya ayarlar. |
| [getGPSDOP()](#getGPSDOP--) | GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar. |
| [getGPSDateStamp()](#getGPSDateStamp--) | UTC'ye (Eşgüdümlü Evrensel Zaman) göre GPS karakter dizisi tarih ve saat bilgisini alır veya ayarlar. |
| [getGPSDestBearing()](#getGPSDestBearing--) | Hedef noktaya GPS yönünü alır veya ayarlar. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Hedef noktaya GPS mesafesini alır veya ayarlar. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Hedef noktaya mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Hedef noktanın GPS enlemini alır veya ayarlar. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Hedef noktanın GPS boylamını alır veya ayarlar. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar. |
| [getGPSDifferential()](#getGPSDifferential--) | GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Görüntünün yakalandığı zamandaki GPS yönünü alır veya ayarlar. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Görüntünün yakalandığı zamandaki yönü vermek için GPS referansını alır veya ayarlar. |
| [getGPSLatitude()](#getGPSLatitude--) | GPS enlemini alır veya ayarlar. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | GPS enleminin kuzey mi yoksa güney mi olduğunu alır veya ayarlar. |
| [getGPSLongitude()](#getGPSLongitude--) | GPS boylamını alır veya ayarlar. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | GPS boylamının doğu mu yoksa batı mı olduğunu alır veya ayarlar. |
| [getGPSMapDatum()](#getGPSMapDatum--) | GPS alıcısı tarafından kullanılan GPS jeodetik ölçüm verilerini alır veya ayarlar. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | GPS ölçüm modunu alır veya ayarlar. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar. |
| [getGPSSatellites()](#getGPSSatellites--) | Ölçümler için kullanılan GPS uydularını alır veya ayarlar. |
| [getGPSSpeed()](#getGPSSpeed--) | GPS alıcısının hareket hızını alır veya ayarlar. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar. |
| [getGPSStatus()](#getGPSStatus--) | Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar. |
| [getGPSTags()](#getGPSTags--) | Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar. |
| [getGPSTimestamp()](#getGPSTimestamp--) | GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar. |
| [getGPSTrack()](#getGPSTrack--) | GPS alıcısının hareket yönünü alır veya ayarlar. |
| [getGPSTrackRef()](#getGPSTrackRef--) | GPS alıcısının hareket yönünü vermek için referansı alır veya ayarlar. |
| [getGPSVersionID()](#getGPSVersionID--) | GPS sürüm tanımlayıcısını alır veya ayarlar. |
| [getGainControl()](#getGainControl--) | Genel görüntü kazanç ayarının derecesini alır veya ayarlar. |
| [getGamma()](#getGamma--) | Gammayı alır veya ayarlar. |
| [getISOSpeed()](#getISOSpeed--) | ISO hızını alır veya ayarlar. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar. |
| [getImageUniqueID()](#getImageUniqueID--) | Görselin benzersiz tanımlayıcısını alır veya ayarlar. |
| [getLensMake()](#getLensMake--) | Lensin üreticisini alır veya ayarlar. |
| [getLensModel()](#getLensModel--) | Lens modelini alır veya ayarlar. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Lens seri numarasını alır veya ayarlar. |
| [getLensSpecification()](#getLensSpecification--) | Lens özelliklerini alır veya ayarlar. |
| [getLightSource()](#getLightSource--) | Işık kaynağını alır veya ayarlar. |
| [getMake()](#getMake--) | Kayıt ekipmanının üreticisini alır. |
| [getMakerNoteData()](#getMakerNoteData--) | Üretici not verisini alır. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Üretici not ham verisini alır veya ayarlar. |
| [getMakerNotes()](#getMakerNotes--) | Üretici notlarını alır. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Maksimum diyafram değerini alır veya ayarlar. |
| [getMeteringMode()](#getMeteringMode--) | Ölçüm modunu alır veya ayarlar. |
| [getOECF()](#getOECF--) | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Fotoğrafik duyarlılığı alır veya ayarlar. |
| [getPixelXDimension()](#getPixelXDimension--) | Piksel x boyutunu alır veya ayarlar. |
| [getPixelYDimension()](#getPixelYDimension--) | Piksel y boyutunu alır veya ayarlar. |
| [getProperties()](#getProperties--) | Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar. |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Önerilen pozlama indeksini alır veya ayarlar. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | İlgili ses dosyasını alır veya ayarlar. |
| [getSaturation()](#getSaturation--) | Doygunluğu alır veya ayarlar. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Sahne yakalama türünü alır veya ayarlar. |
| [getSceneType()](#getSceneType--) | Sahne türünü alır veya ayarlar. |
| [getSensingMethod()](#getSensingMethod--) | Algılama yöntemini alır veya ayarlar. |
| [getSensitivityType()](#getSensitivityType--) | Duyarlılık türünü alır veya ayarlar. |
| [getSharpness()](#getSharpness--) | Keskinliği alır veya ayarlar. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Deklanşör hızı değerini alır veya ayarlar. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Uzamsal frekans yanıtını alır veya ayarlar. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Spektral duyarlılığı alır veya ayarlar. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Standart çıkış duyarlılığını alır |
| [getSubjectArea()](#getSubjectArea--) | Konu alanını alır veya ayarlar. |
| [getSubjectDistance()](#getSubjectDistance--) | Konu mesafesini alır veya ayarlar. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Konu mesafe aralığını alır veya ayarlar. |
| [getSubjectLocation()](#getSubjectLocation--) | Konu konumunu alır veya ayarlar. |
| [getSubsecTime()](#getSubsecTime--) | DateTime etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [getUserComment()](#getUserComment--) | Kullanıcı yorumunu alır veya ayarlar. |
| [getWhiteBalance()](#getWhiteBalance--) | Beyaz dengesini alır veya ayarlar. |
| [getWhitePoint()](#getWhitePoint--) | Görüntünün beyaz noktasının kromatikliğini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Etiketi konteynerden kaldır |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Açıklık değerini alır veya ayarlar. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren değeri alır veya ayarlar. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Kamera gövdesi seri numarasını alır veya ayarlar. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Parlaklık değerini alır veya ayarlar. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | CFA desenini alır veya ayarlar. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Kamera sahibinin adını alır veya ayarlar |
| [setColorSpace(int value)](#setColorSpace-int-) | Renk uzayını alır veya ayarlar. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Ortak bölüme ait etiketleri alır veya ayarlar. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Bileşen yapılandırmasını alır veya ayarlar. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar. |
| [setContrast(int value)](#setContrast-int-) | Kontrastı alır veya ayarlar. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Özel işlenmiş değeri alır veya ayarlar. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Sayısallaştırma tarih ve saatini alır veya ayarlar. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Orijinal tarih ve saatini alır veya ayarlar. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Cihaz ayarları açıklamasını alır veya ayarlar |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Dijital zoom oranını alır veya ayarlar. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | EXIF sürümünü alır veya ayarlar. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Pozlama sapma değerini alır veya ayarlar. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Pozlama indeksini alır veya ayarlar. |
| [setExposureMode(int value)](#setExposureMode-int-) | Pozlama modunu alır veya ayarlar. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Pozlama programını alır veya ayarlar. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Pozlama süresini alır veya ayarlar. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | F-numarasını alır veya ayarlar. |
| [setFileSource(byte value)](#setFileSource-byte-) | Dosya kaynağı türünü alır veya ayarlar. |
| [setFlash(int value)](#setFlash-int-) | Flaş'ı alır veya ayarlar. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Flaş enerjisini alır veya ayarlar. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Flaş pix sürümünü alır veya ayarlar. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Odak uzaklığını alır veya ayarlar. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | 35 mm filmde odak uzaklığını alır veya ayarlar. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Odak düzlemi çözünürlük birimini alır veya ayarlar. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Odak düzlemi x çözünürlüğünü alır veya ayarlar. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Odak düzlemi y çözünürlüğünü alır veya ayarlar. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS yüksekliğini alır veya ayarlar. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | GPS bölge bilgisini alır veya ayarlar. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar. |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | UTC'ye (Eşgüdümlü Evrensel Zaman) göre GPS karakter dizisi tarih ve saat bilgisini alır veya ayarlar. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Hedef noktaya GPS yönünü alır veya ayarlar. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Hedef noktaya GPS mesafesini alır veya ayarlar. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Hedef noktaya mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Hedef noktanın GPS enlemini alır veya ayarlar. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Hedef noktanın GPS boylamını alır veya ayarlar. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Görüntünün yakalandığı zamandaki GPS yönünü alır veya ayarlar. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Görüntünün yakalandığı zamandaki yönü vermek için GPS referansını alır veya ayarlar. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | GPS enlemini alır veya ayarlar. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | GPS enleminin kuzey mi yoksa güney mi olduğunu alır veya ayarlar. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | GPS boylamını alır veya ayarlar. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | GPS boylamının doğu mu yoksa batı mı olduğunu alır veya ayarlar. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | GPS alıcısı tarafından kullanılan GPS jeodetik ölçüm verilerini alır veya ayarlar. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | GPS ölçüm modunu alır veya ayarlar. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Ölçümler için kullanılan GPS uydularını alır veya ayarlar. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS alıcısının hareket hızını alır veya ayarlar. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | GPS alıcısının hareket yönünü alır veya ayarlar. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | GPS alıcısının hareket yönünü vermek için referansı alır veya ayarlar. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | GPS sürüm tanımlayıcısını alır veya ayarlar. |
| [setGainControl(int value)](#setGainControl-int-) | Genel görüntü kazanç ayarının derecesini alır veya ayarlar. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Gammayı alır veya ayarlar. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | ISO hızını alır veya ayarlar. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Görselin benzersiz tanımlayıcısını alır veya ayarlar. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Lensin üreticisini alır veya ayarlar. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Lens modelini alır veya ayarlar. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Lens seri numarasını alır veya ayarlar. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Lens özelliklerini alır veya ayarlar. |
| [setLightSource(int value)](#setLightSource-int-) | Işık kaynağını alır veya ayarlar. |
| [setMake(String value)](#setMake-java.lang.String-) | Kayıt ekipmanının üreticisini ayarlar. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Üretici not ham verisini alır veya ayarlar. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Maksimum diyafram değerini alır veya ayarlar. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Ölçüm modunu alır veya ayarlar. |
| [setOECF(byte[] value)](#setOECF-byte---) | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Fotoğrafik duyarlılığı alır veya ayarlar. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Piksel x boyutunu alır veya ayarlar. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Piksel y boyutunu alır veya ayarlar. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Önerilen pozlama indeksini alır veya ayarlar. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | İlgili ses dosyasını alır veya ayarlar. |
| [setSaturation(int value)](#setSaturation-int-) | Doygunluğu alır veya ayarlar. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Sahne yakalama türünü alır veya ayarlar. |
| [setSceneType(byte value)](#setSceneType-byte-) | Sahne türünü alır veya ayarlar. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Algılama yöntemini alır veya ayarlar. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Duyarlılık türünü alır veya ayarlar. |
| [setSharpness(int value)](#setSharpness-int-) | Keskinliği alır veya ayarlar. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Deklanşör hızı değerini alır veya ayarlar. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Uzamsal frekans yanıtını alır veya ayarlar. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Spektral duyarlılığı alır veya ayarlar. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Standart çıkış duyarlılığını ayarlar. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Konu alanını alır veya ayarlar. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Konu mesafesini alır veya ayarlar. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Konu mesafe aralığını alır veya ayarlar. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Konu konumunu alır veya ayarlar. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | DateTime etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Kullanıcı yorumunu alır veya ayarlar. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Beyaz dengesini alır veya ayarlar. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Görüntünün beyaz noktasının kromatikliğini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


ExifData sınıfının yeni bir örneğini başlatır.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


ExifData sınıfının, dizi verileriyle yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


ExifData sınıfının, dizi verileriyle yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Ortak etiketler. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | EXIF etiketleri. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | GPS etiketleri. |

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
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Açıklık değerini alır veya ayarlar.

Değer: Diyafram değeri.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Kamera gövdesi seri numarasını alır veya ayarlar.

Değer: Gövde seri numarası.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Parlaklık değerini alır veya ayarlar.

Değer: Parlaklık değeri.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


CFA desenini alır veya ayarlar.

Değer: CFA deseni.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Kamera sahibinin adını alır veya ayarlar

Değer: kamera sahibinin adı.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Renk uzayını alır veya ayarlar.

Değer: renk uzayı.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Ortak bölüme ait etiketleri alır veya ayarlar. Bu yalnızca jpeg görüntüler için geçerlidir, tiff formatında ise tiffOptions kullanılır.

Değer: ortak bölüm etiketleri.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Bileşen yapılandırmasını alır veya ayarlar.

Değer: bileşen yapılandırması.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar.

Değer: piksel başına sıkıştırılmış bitler.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


Kontrastı alır veya ayarlar.

Değer: kontrast.

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Özel işlenmiş değeri alır veya ayarlar.

Değer: özel işlenmiş.

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Sayısallaştırma tarih ve saatini alır veya ayarlar.

Değer: dijitalleştirilme tarih ve saati.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Orijinal tarih ve saatini alır veya ayarlar.

Değer: orijinal tarih ve saat.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Cihaz ayarları açıklamasını alır veya ayarlar

Değer: cihaz ayarı açıklaması.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Dijital zoom oranını alır veya ayarlar.

Değer: dijital yakınlaştırma oranı.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar.

Değer: EXIF bölüm etiketleri.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


EXIF sürümünü alır veya ayarlar.

Değer: EXIF sürümü.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Pozlama sapma değerini alır veya ayarlar.

Değer: pozlama sapma değeri.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Pozlama indeksini alır veya ayarlar.

Değer: pozlamanın indeksi.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Pozlama modunu alır veya ayarlar.

Değer: pozlama modu.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Pozlama programını alır veya ayarlar.

Değer: pozlama programı.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Pozlama süresini alır veya ayarlar.

Değer: pozlama süresi.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


F-numarasını alır veya ayarlar.

Değer: F-numarası.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Dosya kaynağı türünü alır veya ayarlar.

Değer: dosya kaynağı türü.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Flaş'ı alır veya ayarlar.

Değer: flaş.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Flaş enerjisini alır veya ayarlar.

Değer: flaş enerjisi.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Flaş pix sürümünü alır veya ayarlar.

Değer: Flash pix sürümü.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Odak uzaklığını alır veya ayarlar.

Değer: Odak uzunluğu.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


35 mm filmde odak uzaklığını alır veya ayarlar.

Değer: 35 mm filmde odak uzunluğu.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Odak düzlemi çözünürlük birimini alır veya ayarlar.

Değer: Odak düzlemi çözünürlük birimi.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Odak düzlemi x çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi x çözünürlüğü.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Odak düzlemi y çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi y çözünürlüğü.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


GPS yüksekliğini alır veya ayarlar.

Değer: GPS yüksekliği.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar.

Değer: Referans yüksekliği olarak kullanılan GPS yüksekliği.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


GPS bölge bilgisini alır veya ayarlar.

Değer: GPS bölge bilgisi.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar.

Değer: GPS DOP (veri kesinlik derecesi).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


UTC'ye (Eşgüdümlü Evrensel Zaman) göre GPS karakter dizisi tarih ve saat bilgisini alır veya ayarlar.

Değer: UTC'ye (Eşgüdümlü Evrensel Zaman) göre GPS karakter dizisi kayıt tarih ve saat bilgisi.

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Hedef noktaya GPS yönünü alır veya ayarlar.

Değer: Hedef noktaya olan GPS yönü.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar.

Değer: Hedef noktaya yön vermek için kullanılan GPS referansı.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Hedef noktaya GPS mesafesini alır veya ayarlar.

Değer: Hedef noktaya olan GPS mesafesi.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Hedef noktaya mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar.

Değer: Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimi.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Hedef noktanın GPS enlemini alır veya ayarlar.

Değer: Hedef noktanın GPS enlemi.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değeri.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Hedef noktanın GPS boylamını alır veya ayarlar.

Değer: Hedef noktanın GPS boylamı.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değeri.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar.

Değer: GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösteren GPS değeri.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Görüntünün yakalandığı zamandaki GPS yönünü alır veya ayarlar.

Değer: Görüntünün çekildiği zamanki GPS yönü.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Görüntünün yakalandığı zamandaki yönü vermek için GPS referansını alır veya ayarlar.

Değer: Görüntünün çekildiği zamanki yönü vermek için GPS referansı.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


GPS enlemini alır veya ayarlar.

Değer: GPS enlemi.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


GPS enleminin kuzey mi yoksa güney mi olduğunu alır veya ayarlar.

Değer: GPS enlemi kuzey mi yoksa güney mi.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


GPS boylamını alır veya ayarlar.

Değer: GPS boylamı.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


GPS boylamının doğu mu yoksa batı mı olduğunu alır veya ayarlar.

Değer: GPS boylamı doğu ya da batı boylamıdır.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


GPS alıcısı tarafından kullanılan GPS jeodetik ölçüm verilerini alır veya ayarlar.

Değer: GPS alıcısı tarafından kullanılan GPS jeodetik ölçüm verileri.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


GPS ölçüm modunu alır veya ayarlar.

Değer: GPS ölçüm modu.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar.

Değer: Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizgesi.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Ölçümler için kullanılan GPS uydularını alır veya ayarlar.

Değer: Ölçümler için kullanılan GPS uyduları.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


GPS alıcısının hareket hızını alır veya ayarlar.

Değer: GPS alıcısının hareket hızı.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar.

Değer: GPS alıcısının hareket hızını ifade etmek için kullanılan birim.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar.

Değer: Görüntü kaydedildiğinde GPS alıcısının durumu.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar.

Değer: GPS etiketleri.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar.

Değer: GPS zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


GPS alıcısının hareket yönünü alır veya ayarlar.

Değer: GPS alıcısının hareket yönü.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


GPS alıcısının hareket yönünü vermek için referansı alır veya ayarlar.

Değer: GPS alıcısının hareket yönünü vermek için referans.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


GPS sürüm tanımlayıcısını alır veya ayarlar.

Değer: GPS sürüm tanımlayıcısı.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Genel görüntü kazanç ayarının derecesini alır veya ayarlar.

Değer: Genel görüntü kazanç ayarının derecesi.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Gammayı alır veya ayarlar.

Değer: Gama değeri.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


ISO hızını alır veya ayarlar.

Değer: ISO hızı.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO speed latitude yyy değeri.

Bu etiket, ISOSpeed ve ISOSpeedLatitudezzz olmadan kaydedilmemelidir.

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO speed latitude zzz değeri.

Bu etiket, ISOSpeed ve ISOSpeedLatitudeyyy olmadan kaydedilmemelidir.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Görselin benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Görüntünün benzersiz tanımlayıcısı.

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Lensin üreticisini alır veya ayarlar.

Değer: Lens üreticisi.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Lens modelini alır veya ayarlar.

Değer: Lens modeli.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Lens seri numarasını alır veya ayarlar.

Değer: Lens seri numarası.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Lens özelliklerini alır veya ayarlar.

Değer: Lens spesifikasyonu.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Işık kaynağını alır veya ayarlar.

Değer: Işık kaynağı.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Kayıt ekipmanının üreticisini alır.

Değer: Kayıt ekipmanının üreticisi.

**Returns:**
java.lang.String - kayıt ekipmanının üreticisi.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Üretici not verisini alır.

Değer: Üretici not verileri.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Üretici not ham verisini alır veya ayarlar.

Değer: Üretici not ham verileri.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Üretici notlarını alır.

Değer: Üretici notlar.

**Returns:**
com.aspose.psd.exif.MakerNote[] - üretici notlar.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Maksimum diyafram değerini alır veya ayarlar.

Değer: Maksimum diyafram değeri.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Ölçüm modunu alır veya ayarlar.

Değer: Ölçüm modu.

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar.

Değer: ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonu (OECF).

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Fotoğrafik duyarlılığı alır veya ayarlar.

Değer: Fotoğrafik duyarlılık.

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Piksel x boyutunu alır veya ayarlar.

Değer: Piksel x boyutu.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Piksel y boyutunu alır veya ayarlar.

Değer: Piksel y boyutu.

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar.

Değer: EXIF etiketleri (ortak ve GPS etiketleri dahil).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Önerilen pozlama indeksini alır veya ayarlar.

Değer: Önerilen pozlama indeksi.

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


İlgili ses dosyasını alır veya ayarlar.

Değer: İlgili ses dosyası.

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Doygunluğu alır veya ayarlar.

Değer: Doygunluk.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Sahne yakalama türünü alır veya ayarlar.

Değer: Sahne yakalama türü.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Sahne türünü alır veya ayarlar.

Değer: Sahne türü.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Algılama yöntemini alır veya ayarlar.

Değer: Algılama yöntemi.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Duyarlılık türünü alır veya ayarlar.

Değer: Duyarlılık türü.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Keskinliği alır veya ayarlar.

Değer: Keskinlik.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Deklanşör hızı değerini alır veya ayarlar.

Değer: Enstantane hızı değeri.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Uzamsal frekans yanıtını alır veya ayarlar.

Değer: Uzamsal frekans yanıtı.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Spektral duyarlılığı alır veya ayarlar.

Değer: Spektral duyarlılık.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Standart çıkış duyarlılığını alır

Değer: Standart çıkış duyarlılığı.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Konu alanını alır veya ayarlar.

Değer: Konu alanı.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Konu mesafesini alır veya ayarlar.

Değer: Konu mesafesi.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Konu mesafe aralığını alır veya ayarlar.

Değer: Konu mesafesi aralığı.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Konu konumunu alır veya ayarlar.

Değer: Konu konumu.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


DateTime etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTime etiketi için saniyenin kesirleri.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeDigitized etiketi için saniyenin kesirleri.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeOriginal etiketi için saniyenin kesirleri.

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Kullanıcı yorumunu alır veya ayarlar.

Değer: Kullanıcı yorumu.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Beyaz dengesini alır veya ayarlar.

Değer: Beyaz dengesi.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Görüntünün beyaz noktasının kromatikliğini alır veya ayarlar.

Değer: Görüntünün beyaz noktasının kromatikliği.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren değeri alır veya ayarlar.

Değer:  true  eğer oluşturulan akış EXIF verisi büyük endian ise; aksi takdirde,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Etiketi konteynerden kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Kaldırılacak etiket tanımlayıcısı. |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Açıklık değerini alır veya ayarlar.

Değer: Diyafram değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren değeri alır veya ayarlar.

Değer:  true  eğer oluşturulan akış EXIF verisi büyük endian ise; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Kamera gövdesi seri numarasını alır veya ayarlar.

Değer: Gövde seri numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Parlaklık değerini alır veya ayarlar.

Değer: Parlaklık değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


CFA desenini alır veya ayarlar.

Değer: CFA deseni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Kamera sahibinin adını alır veya ayarlar

Değer: kamera sahibinin adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Renk uzayını alır veya ayarlar.

Değer: renk uzayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Ortak bölüme ait etiketleri alır veya ayarlar. Bu yalnızca jpeg görüntüler için geçerlidir, tiff formatında ise tiffOptions kullanılır.

Değer: ortak bölüm etiketleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Bileşen yapılandırmasını alır veya ayarlar.

Değer: bileşen yapılandırması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar.

Değer: piksel başına sıkıştırılmış bitler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Kontrastı alır veya ayarlar.

Değer: kontrast.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Özel işlenmiş değeri alır veya ayarlar.

Değer: özel işlenmiş.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Sayısallaştırma tarih ve saatini alır veya ayarlar.

Değer: dijitalleştirilme tarih ve saati.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Orijinal tarih ve saatini alır veya ayarlar.

Değer: orijinal tarih ve saat.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Cihaz ayarları açıklamasını alır veya ayarlar

Değer: cihaz ayarı açıklaması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Dijital zoom oranını alır veya ayarlar.

Değer: dijital yakınlaştırma oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar.

Değer: EXIF bölüm etiketleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


EXIF sürümünü alır veya ayarlar.

Değer: EXIF sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Pozlama sapma değerini alır veya ayarlar.

Değer: pozlama sapma değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Pozlama indeksini alır veya ayarlar.

Değer: pozlamanın indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Pozlama modunu alır veya ayarlar.

Değer: pozlama modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Pozlama programını alır veya ayarlar.

Değer: pozlama programı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Pozlama süresini alır veya ayarlar.

Değer: pozlama süresi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


F-numarasını alır veya ayarlar.

Değer: F-numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Dosya kaynağı türünü alır veya ayarlar.

Değer: dosya kaynağı türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Flaş'ı alır veya ayarlar.

Değer: flaş.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Flaş enerjisini alır veya ayarlar.

Değer: flaş enerjisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Flaş pix sürümünü alır veya ayarlar.

Değer: Flash pix sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Odak uzaklığını alır veya ayarlar.

Değer: Odak uzunluğu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


35 mm filmde odak uzaklığını alır veya ayarlar.

Değer: 35 mm filmde odak uzunluğu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Odak düzlemi çözünürlük birimini alır veya ayarlar.

Değer: Odak düzlemi çözünürlük birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Odak düzlemi x çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi x çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Odak düzlemi y çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi y çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


GPS yüksekliğini alır veya ayarlar.

Değer: GPS yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar.

Değer: Referans yüksekliği olarak kullanılan GPS yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


GPS bölge bilgisini alır veya ayarlar.

Değer: GPS bölge bilgisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar.

Değer: GPS DOP (veri kesinlik derecesi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


UTC'ye (Eşgüdümlü Evrensel Zaman) göre GPS karakter dizisi tarih ve saat bilgisini alır veya ayarlar.

Değer: UTC'ye (Eşgüdümlü Evrensel Zaman) göre GPS karakter dizisi kayıt tarih ve saat bilgisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Hedef noktaya GPS yönünü alır veya ayarlar.

Değer: Hedef noktaya olan GPS yönü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar.

Değer: Hedef noktaya yön vermek için kullanılan GPS referansı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Hedef noktaya GPS mesafesini alır veya ayarlar.

Değer: Hedef noktaya olan GPS mesafesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Hedef noktaya mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar.

Değer: Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Hedef noktanın GPS enlemini alır veya ayarlar.

Değer: Hedef noktanın GPS enlemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Hedef noktanın GPS boylamını alır veya ayarlar.

Değer: Hedef noktanın GPS boylamı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar.

Değer: GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösteren GPS değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Görüntünün yakalandığı zamandaki GPS yönünü alır veya ayarlar.

Değer: Görüntünün çekildiği zamanki GPS yönü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Görüntünün yakalandığı zamandaki yönü vermek için GPS referansını alır veya ayarlar.

Değer: Görüntünün çekildiği zamanki yönü vermek için GPS referansı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


GPS enlemini alır veya ayarlar.

Değer: GPS enlemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


GPS enleminin kuzey mi yoksa güney mi olduğunu alır veya ayarlar.

Değer: GPS enlemi kuzey mi yoksa güney mi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


GPS boylamını alır veya ayarlar.

Değer: GPS boylamı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


GPS boylamının doğu mu yoksa batı mı olduğunu alır veya ayarlar.

Değer: GPS boylamı doğu ya da batı boylamıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


GPS alıcısı tarafından kullanılan GPS jeodetik ölçüm verilerini alır veya ayarlar.

Değer: GPS alıcısı tarafından kullanılan GPS jeodetik ölçüm verileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


GPS ölçüm modunu alır veya ayarlar.

Değer: GPS ölçüm modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar.

Değer: Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizgesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Ölçümler için kullanılan GPS uydularını alır veya ayarlar.

Değer: Ölçümler için kullanılan GPS uyduları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


GPS alıcısının hareket hızını alır veya ayarlar.

Değer: GPS alıcısının hareket hızı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar.

Değer: GPS alıcısının hareket hızını ifade etmek için kullanılan birim.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar.

Değer: Görüntü kaydedildiğinde GPS alıcısının durumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar.

Değer: GPS etiketleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar.

Değer: GPS zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


GPS alıcısının hareket yönünü alır veya ayarlar.

Değer: GPS alıcısının hareket yönü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


GPS alıcısının hareket yönünü vermek için referansı alır veya ayarlar.

Değer: GPS alıcısının hareket yönünü vermek için referans.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


GPS sürüm tanımlayıcısını alır veya ayarlar.

Değer: GPS sürüm tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Genel görüntü kazanç ayarının derecesini alır veya ayarlar.

Değer: Genel görüntü kazanç ayarının derecesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Gammayı alır veya ayarlar.

Değer: Gama değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


ISO hızını alır veya ayarlar.

Değer: ISO hızı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO speed latitude yyy değeri.

Bu etiket, ISOSpeed ve ISOSpeedLatitudezzz olmadan kaydedilmemelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO speed latitude zzz değeri.

Bu etiket, ISOSpeed ve ISOSpeedLatitudeyyy olmadan kaydedilmemelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Görselin benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Görüntünün benzersiz tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Lensin üreticisini alır veya ayarlar.

Değer: Lens üreticisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Lens modelini alır veya ayarlar.

Değer: Lens modeli.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Lens seri numarasını alır veya ayarlar.

Değer: Lens seri numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Lens özelliklerini alır veya ayarlar.

Değer: Lens spesifikasyonu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Işık kaynağını alır veya ayarlar.

Değer: Işık kaynağı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Kayıt ekipmanının üreticisini ayarlar.

Değer: Kayıt ekipmanının üreticisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | kayıt ekipmanının üreticisi. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Üretici not ham verisini alır veya ayarlar.

Değer: Üretici not ham verileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Maksimum diyafram değerini alır veya ayarlar.

Değer: Maksimum diyafram değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Ölçüm modunu alır veya ayarlar.

Değer: Ölçüm modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar.

Değer: ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonu (OECF).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Fotoğrafik duyarlılığı alır veya ayarlar.

Değer: Fotoğrafik duyarlılık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Piksel x boyutunu alır veya ayarlar.

Değer: Piksel x boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Piksel y boyutunu alır veya ayarlar.

Değer: Piksel y boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar.

Değer: EXIF etiketleri (ortak ve GPS etiketleri dahil).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Önerilen pozlama indeksini alır veya ayarlar.

Değer: Önerilen pozlama indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


İlgili ses dosyasını alır veya ayarlar.

Değer: İlgili ses dosyası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Doygunluğu alır veya ayarlar.

Değer: Doygunluk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Sahne yakalama türünü alır veya ayarlar.

Değer: Sahne yakalama türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Sahne türünü alır veya ayarlar.

Değer: Sahne türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Algılama yöntemini alır veya ayarlar.

Değer: Algılama yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Duyarlılık türünü alır veya ayarlar.

Değer: Duyarlılık türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Keskinliği alır veya ayarlar.

Değer: Keskinlik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Deklanşör hızı değerini alır veya ayarlar.

Değer: Enstantane hızı değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Uzamsal frekans yanıtını alır veya ayarlar.

Değer: Uzamsal frekans yanıtı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Spektral duyarlılığı alır veya ayarlar.

Değer: Spektral duyarlılık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Standart çıkış duyarlılığını ayarlar.

Değer: Standart çıkış duyarlılığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Konu alanını alır veya ayarlar.

Değer: Konu alanı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Konu mesafesini alır veya ayarlar.

Değer: Konu mesafesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Konu mesafe aralığını alır veya ayarlar.

Değer: Konu mesafesi aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Konu konumunu alır veya ayarlar.

Değer: Konu konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


DateTime etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTime etiketi için saniyenin kesirleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeDigitized etiketi için saniyenin kesirleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeOriginal etiketi için saniyenin kesirleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Kullanıcı yorumunu alır veya ayarlar.

Değer: Kullanıcı yorumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Beyaz dengesini alır veya ayarlar.

Değer: Beyaz dengesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Görüntünün beyaz noktasının kromatikliğini alır veya ayarlar.

Değer: Görüntünün beyaz noktasının kromatikliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

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

