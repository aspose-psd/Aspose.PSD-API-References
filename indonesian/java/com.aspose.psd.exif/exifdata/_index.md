---
title: "ExifData"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kontainer data EXIF."
type: docs
weight: 10
url: /id/java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

Kontainer data EXIF.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ExifData()](#ExifData--) | Menginisialisasi instance baru dari kelas  ExifData  . |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | Menginisialisasi instance baru dari kelas  ExifData  dengan data dari array. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | Menginisialisasi instance baru dari kelas  ExifData  dengan data dari array. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | Mendapatkan atau mengatur nilai aperture. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Mendapatkan atau mengatur nomor seri badan kamera. |
| [getBrightnessValue()](#getBrightnessValue--) | Mendapatkan atau mengatur nilai kecerahan. |
| [getCFAPattern()](#getCFAPattern--) | Mendapatkan atau mengatur pola CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Mendapatkan atau mengatur nama pemilik kamera |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Mendapatkan atau mengatur ruang warna. |
| [getCommonTags()](#getCommonTags--) | Mendapatkan atau mengatur tag, yang termasuk dalam bagian umum. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Mendapatkan atau mengatur konfigurasi komponen. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Mendapatkan atau mengatur bit terkompresi per piksel. |
| [getContrast()](#getContrast--) | Mendapatkan atau mengatur kontras. |
| [getCustomRendered()](#getCustomRendered--) | Mendapatkan atau mengatur render khusus. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Mendapatkan atau mengatur tanggal waktu digitalisasi. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Mendapatkan atau mengatur tanggal waktu asli. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Mendapatkan atau mengatur deskripsi pengaturan perangkat |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Mendapatkan atau mengatur rasio zoom digital. |
| [getExifTags()](#getExifTags--) | Mendapatkan atau mengatur tag yang hanya termasuk dalam bagian EXIF. |
| [getExifVersion()](#getExifVersion--) | Mendapatkan atau mengatur versi EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Mendapatkan atau mengatur nilai bias eksposur. |
| [getExposureIndex()](#getExposureIndex--) | Mendapatkan atau mengatur indeks eksposur. |
| [getExposureMode()](#getExposureMode--) | Mendapatkan atau mengatur mode eksposur. |
| [getExposureProgram()](#getExposureProgram--) | Mendapatkan atau mengatur program eksposur. |
| [getExposureTime()](#getExposureTime--) | Mendapatkan atau mengatur waktu eksposur. |
| [getFNumber()](#getFNumber--) | Mendapatkan atau mengatur nomor F. |
| [getFileSource()](#getFileSource--) | Mendapatkan atau mengatur tipe sumber file. |
| [getFlash()](#getFlash--) | Mendapatkan atau mengatur flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Mendapatkan atau mengatur energi flash. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Mendapatkan atau mengatur versi pix flash. |
| [getFocalLength()](#getFocalLength--) | Mendapatkan atau mengatur panjang fokus. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Mendapatkan atau mengatur panjang fokus dalam film 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Mendapatkan atau mengatur satuan resolusi bidang fokus. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Mendapatkan atau mengatur resolusi x bidang fokus. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Mendapatkan atau mengatur resolusi y bidang fokus. |
| [getGPSAltitude()](#getGPSAltitude--) | Mendapatkan atau mengatur ketinggian GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Mendapatkan atau mengatur ketinggian GPS yang digunakan sebagai ketinggian referensi. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Mendapatkan atau mengatur informasi area GPS. |
| [getGPSDOP()](#getGPSDOP--) | Mendapatkan atau mengatur GPS DOP (derajat presisi data). |
| [getGPSDateStamp()](#getGPSDateStamp--) | Mendapatkan atau mengatur string karakter GPS yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Mendapatkan atau mengatur arah GPS ke titik tujuan. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Mendapatkan atau mengatur referensi GPS yang digunakan untuk memberikan arah ke titik tujuan. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Mendapatkan atau mengatur jarak GPS ke titik tujuan. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Mendapatkan atau mengatur satuan GPS yang digunakan untuk menyatakan jarak ke titik tujuan. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Mendapatkan atau mengatur lintang GPS dari titik tujuan. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah lintang titik tujuan berada di lintang utara atau selatan. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Mendapatkan atau mengatur bujur GPS dari titik tujuan. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat. |
| [getGPSDifferential()](#getGPSDifferential--) | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Mendapatkan atau mengatur arah GPS gambar saat diambil. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Mendapatkan atau mengatur referensi GPS untuk memberikan arah gambar saat diambil. |
| [getGPSLatitude()](#getGPSLatitude--) | Mendapatkan atau mengatur lintang GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Mendapatkan atau mengatur apakah lintang GPS berada di lintang utara atau selatan. |
| [getGPSLongitude()](#getGPSLongitude--) | Mendapatkan atau mengatur bujur GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Mendapatkan atau mengatur apakah bujur GPS berada di bujur timur atau barat. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Mendapatkan atau mengatur data survei geodetik GPS yang digunakan oleh penerima GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Mendapatkan atau mengatur mode pengukuran GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Mendapatkan atau mengatur string karakter GPS yang merekam nama metode yang digunakan untuk menemukan lokasi. |
| [getGPSSatellites()](#getGPSSatellites--) | Mendapatkan atau mengatur satelit GPS yang digunakan untuk pengukuran. |
| [getGPSSpeed()](#getGPSSpeed--) | Mendapatkan atau mengatur kecepatan pergerakan penerima GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Mendapatkan atau mengatur satuan yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS. |
| [getGPSStatus()](#getGPSStatus--) | Mendapatkan atau mengatur status penerima GPS saat gambar direkam. |
| [getGPSTags()](#getGPSTags--) | Mendapatkan atau mengatur tag, yang hanya termasuk dalam bagian GPS. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Mendapatkan atau mengatur waktu GPS sebagai UTC (Coordinated Universal Time). |
| [getGPSTrack()](#getGPSTrack--) | Mendapatkan atau mengatur arah pergerakan penerima GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Mendapatkan atau mengatur referensi untuk memberikan arah pergerakan penerima GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Mendapatkan atau mengatur pengidentifikasi versi GPS. |
| [getGainControl()](#getGainControl--) | Mendapatkan atau mengatur tingkat penyesuaian gain gambar secara keseluruhan. |
| [getGamma()](#getGamma--) | Mendapatkan atau mengatur gamma. |
| [getISOSpeed()](#getISOSpeed--) | Mendapatkan atau mengatur kecepatan ISO |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Mendapatkan atau mengatur nilai latitude kecepatan ISO yyy dari kamera atau perangkat input yang didefinisikan dalam ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Mendapatkan atau mengatur nilai latitude kecepatan ISO zzz dari kamera atau perangkat input yang didefinisikan dalam ISO 12232. |
| [getImageUniqueID()](#getImageUniqueID--) | Mendapatkan atau mengatur pengidentifikasi unik gambar. |
| [getLensMake()](#getLensMake--) | Mendapatkan atau mengatur pembuat lensa. |
| [getLensModel()](#getLensModel--) | Mendapatkan atau mengatur model lensa. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Mendapatkan atau mengatur nomor seri lensa. |
| [getLensSpecification()](#getLensSpecification--) | Mendapatkan atau mengatur spesifikasi lensa |
| [getLightSource()](#getLightSource--) | Mendapatkan atau mengatur sumber cahaya. |
| [getMake()](#getMake--) | Mendapatkan produsen peralatan perekaman. |
| [getMakerNoteData()](#getMakerNoteData--) | Mendapatkan data catatan pembuat. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Mendapatkan atau mengatur data mentah catatan pembuat. |
| [getMakerNotes()](#getMakerNotes--) | Mendapatkan catatan pembuat. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Mendapatkan atau mengatur nilai apertur maksimum. |
| [getMeteringMode()](#getMeteringMode--) | Mendapatkan atau mengatur mode pengukuran. |
| [getOECF()](#getOECF--) | Mendapatkan atau mengatur Fungsi Konversi Opto-Elektrik (OECF) yang ditentukan dalam ISO 14524. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Mendapatkan atau mengatur sensitivitas fotografi. |
| [getPixelXDimension()](#getPixelXDimension--) | Mendapatkan atau mengatur dimensi x piksel. |
| [getPixelYDimension()](#getPixelYDimension--) | Mendapatkan atau mengatur dimensi y piksel. |
| [getProperties()](#getProperties--) | Mendapatkan atau mengatur semua tag EXIF (termasuk tag umum dan GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Mendapatkan atau mengatur indeks eksposur yang direkomendasikan. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Mendapatkan atau mengatur file suara terkait. |
| [getSaturation()](#getSaturation--) | Mendapatkan atau mengatur saturasi. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Mendapatkan atau mengatur tipe penangkapan adegan. |
| [getSceneType()](#getSceneType--) | Mendapatkan atau mengatur tipe adegan. |
| [getSensingMethod()](#getSensingMethod--) | Mendapatkan atau mengatur metode penginderaan. |
| [getSensitivityType()](#getSensitivityType--) | Mendapatkan atau mengatur tipe sensitivitas. |
| [getSharpness()](#getSharpness--) | Mendapatkan atau mengatur ketajaman. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Mendapatkan atau mengatur nilai kecepatan rana. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Mendapatkan atau mengatur respons frekuensi spasial. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Mendapatkan atau mengatur sensitivitas spektral. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Mendapatkan sensitivitas output standar |
| [getSubjectArea()](#getSubjectArea--) | Mendapatkan atau mengatur area subjek. |
| [getSubjectDistance()](#getSubjectDistance--) | Mendapatkan atau mengatur jarak subjek. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Mendapatkan atau mengatur rentang jarak subjek. |
| [getSubjectLocation()](#getSubjectLocation--) | Mendapatkan atau mengatur lokasi subjek. |
| [getSubsecTime()](#getSubsecTime--) | Mendapatkan atau mengatur fraksi detik untuk tag DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Mendapatkan atau mengatur fraksi detik untuk tag DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Mendapatkan atau mengatur fraksi detik untuk tag DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | Mendapatkan atau mengatur komentar pengguna. |
| [getWhiteBalance()](#getWhiteBalance--) | Mendapatkan atau mengatur keseimbangan putih. |
| [getWhitePoint()](#getWhitePoint--) | Mendapatkan atau mengatur kromatisitas titik putih gambar. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah data EXIF aliran yang dibuat dari berurutan big endian. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | Hapus tag dari kontainer |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur nilai aperture. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah data EXIF aliran yang dibuat dari berurutan big endian. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Mendapatkan atau mengatur nomor seri badan kamera. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Mendapatkan atau mengatur nilai kecerahan. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Mendapatkan atau mengatur pola CFA. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Mendapatkan atau mengatur nama pemilik kamera |
| [setColorSpace(int value)](#setColorSpace-int-) | Mendapatkan atau mengatur ruang warna. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Mendapatkan atau mengatur tag, yang termasuk dalam bagian umum. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Mendapatkan atau mengatur konfigurasi komponen. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur bit terkompresi per piksel. |
| [setContrast(int value)](#setContrast-int-) | Mendapatkan atau mengatur kontras. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Mendapatkan atau mengatur render khusus. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Mendapatkan atau mengatur tanggal waktu digitalisasi. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Mendapatkan atau mengatur tanggal waktu asli. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Mendapatkan atau mengatur deskripsi pengaturan perangkat |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur rasio zoom digital. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Mendapatkan atau mengatur tag yang hanya termasuk dalam bagian EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Mendapatkan atau mengatur versi EXIF. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Mendapatkan atau mengatur nilai bias eksposur. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur indeks eksposur. |
| [setExposureMode(int value)](#setExposureMode-int-) | Mendapatkan atau mengatur mode eksposur. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Mendapatkan atau mengatur program eksposur. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur waktu eksposur. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur nomor F. |
| [setFileSource(byte value)](#setFileSource-byte-) | Mendapatkan atau mengatur tipe sumber file. |
| [setFlash(int value)](#setFlash-int-) | Mendapatkan atau mengatur flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur energi flash. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Mendapatkan atau mengatur versi pix flash. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur panjang fokus. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Mendapatkan atau mengatur panjang fokus dalam film 35 mm. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Mendapatkan atau mengatur satuan resolusi bidang fokus. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur resolusi x bidang fokus. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur resolusi y bidang fokus. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur ketinggian GPS. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Mendapatkan atau mengatur ketinggian GPS yang digunakan sebagai ketinggian referensi. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Mendapatkan atau mengatur informasi area GPS. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur GPS DOP (derajat presisi data). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Mendapatkan atau mengatur string karakter GPS yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time). |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur arah GPS ke titik tujuan. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Mendapatkan atau mengatur referensi GPS yang digunakan untuk memberikan arah ke titik tujuan. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur jarak GPS ke titik tujuan. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Mendapatkan atau mengatur satuan GPS yang digunakan untuk menyatakan jarak ke titik tujuan. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur lintang GPS dari titik tujuan. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah lintang titik tujuan berada di lintang utara atau selatan. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur bujur GPS dari titik tujuan. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur arah GPS gambar saat diambil. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Mendapatkan atau mengatur referensi GPS untuk memberikan arah gambar saat diambil. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur lintang GPS. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Mendapatkan atau mengatur apakah lintang GPS berada di lintang utara atau selatan. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur bujur GPS. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Mendapatkan atau mengatur apakah bujur GPS berada di bujur timur atau barat. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Mendapatkan atau mengatur data survei geodetik GPS yang digunakan oleh penerima GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Mendapatkan atau mengatur mode pengukuran GPS. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Mendapatkan atau mengatur string karakter GPS yang merekam nama metode yang digunakan untuk menemukan lokasi. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Mendapatkan atau mengatur satelit GPS yang digunakan untuk pengukuran. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur kecepatan pergerakan penerima GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Mendapatkan atau mengatur satuan yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Mendapatkan atau mengatur status penerima GPS saat gambar direkam. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Mendapatkan atau mengatur tag, yang hanya termasuk dalam bagian GPS. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur waktu GPS sebagai UTC (Coordinated Universal Time). |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Mendapatkan atau mengatur arah pergerakan penerima GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Mendapatkan atau mengatur referensi untuk memberikan arah pergerakan penerima GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Mendapatkan atau mengatur pengidentifikasi versi GPS. |
| [setGainControl(int value)](#setGainControl-int-) | Mendapatkan atau mengatur tingkat penyesuaian gain gambar secara keseluruhan. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur gamma. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Mendapatkan atau mengatur kecepatan ISO |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Mendapatkan atau mengatur nilai latitude kecepatan ISO yyy dari kamera atau perangkat input yang didefinisikan dalam ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Mendapatkan atau mengatur nilai latitude kecepatan ISO zzz dari kamera atau perangkat input yang didefinisikan dalam ISO 12232. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Mendapatkan atau mengatur pengidentifikasi unik gambar. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Mendapatkan atau mengatur pembuat lensa. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Mendapatkan atau mengatur model lensa. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Mendapatkan atau mengatur nomor seri lensa. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur spesifikasi lensa |
| [setLightSource(int value)](#setLightSource-int-) | Mendapatkan atau mengatur sumber cahaya. |
| [setMake(String value)](#setMake-java.lang.String-) | Mengatur produsen peralatan perekaman. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Mendapatkan atau mengatur data mentah catatan pembuat. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur nilai apertur maksimum. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Mendapatkan atau mengatur mode pengukuran. |
| [setOECF(byte[] value)](#setOECF-byte---) | Mendapatkan atau mengatur Fungsi Konversi Opto-Elektrik (OECF) yang ditentukan dalam ISO 14524. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Mendapatkan atau mengatur sensitivitas fotografi. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Mendapatkan atau mengatur dimensi x piksel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Mendapatkan atau mengatur dimensi y piksel. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | Mendapatkan atau mengatur semua tag EXIF (termasuk tag umum dan GPS). |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Mendapatkan atau mengatur indeks eksposur yang direkomendasikan. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Mendapatkan atau mengatur file suara terkait. |
| [setSaturation(int value)](#setSaturation-int-) | Mendapatkan atau mengatur saturasi. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Mendapatkan atau mengatur tipe penangkapan adegan. |
| [setSceneType(byte value)](#setSceneType-byte-) | Mendapatkan atau mengatur tipe adegan. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Mendapatkan atau mengatur metode penginderaan. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Mendapatkan atau mengatur tipe sensitivitas. |
| [setSharpness(int value)](#setSharpness-int-) | Mendapatkan atau mengatur ketajaman. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | Mendapatkan atau mengatur nilai kecepatan rana. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Mendapatkan atau mengatur respons frekuensi spasial. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Mendapatkan atau mengatur sensitivitas spektral. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Mengatur sensitivitas output standar |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Mendapatkan atau mengatur area subjek. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur jarak subjek. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Mendapatkan atau mengatur rentang jarak subjek. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Mendapatkan atau mengatur lokasi subjek. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Mendapatkan atau mengatur fraksi detik untuk tag DateTime. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Mendapatkan atau mengatur fraksi detik untuk tag DateTimeDigitized. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Mendapatkan atau mengatur fraksi detik untuk tag DateTimeOriginal. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Mendapatkan atau mengatur komentar pengguna. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Mendapatkan atau mengatur keseimbangan putih. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur kromatisitas titik putih gambar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


Menginisialisasi instance baru dari kelas  ExifData  .

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Menginisialisasi instance baru dari kelas  ExifData  dengan data dari array.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Array tag EXIF bersama dengan tag umum dan GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Menginisialisasi instance baru dari kelas  ExifData  dengan data dari array.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag umum. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag GPS. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Mendapatkan atau mengatur nilai aperture.

Nilai: Nilai bukaan.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Mendapatkan atau mengatur nomor seri badan kamera.

Nilai: Nomor seri bodi.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Mendapatkan atau mengatur nilai kecerahan.

Nilai: Nilai kecerahan.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Mendapatkan atau mengatur pola CFA.

Nilai: Pola CFA.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Mendapatkan atau mengatur nama pemilik kamera

Nilai: Nama pemilik kamera.

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


Mendapatkan atau mengatur ruang warna.

Nilai: Ruang warna.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Mendapatkan atau mengatur tag yang termasuk dalam bagian umum. Ini hanya berlaku untuk gambar jpeg, pada format tiff opsi tiffOptions digunakan sebagai gantinya

Nilai: Tag bagian umum.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Mendapatkan atau mengatur konfigurasi komponen.

Nilai: Konfigurasi komponen.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Mendapatkan atau mengatur bit terkompresi per piksel.

Nilai: Bit terkompresi per piksel.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


Mendapatkan atau mengatur kontras.

Nilai: Kontras.

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Mendapatkan atau mengatur render khusus.

Nilai: Rendering khusus.

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Mendapatkan atau mengatur tanggal waktu digitalisasi.

Nilai: Tanggal dan waktu digitalisasi.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Mendapatkan atau mengatur tanggal waktu asli.

Nilai: Tanggal dan waktu asli.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Mendapatkan atau mengatur deskripsi pengaturan perangkat

Nilai: Deskripsi pengaturan perangkat.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Mendapatkan atau mengatur rasio zoom digital.

Nilai: Rasio zoom digital.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Mendapatkan atau mengatur tag yang hanya termasuk dalam bagian EXIF.

Nilai: Tag bagian EXIF.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Mendapatkan atau mengatur versi EXIF.

Nilai: Versi EXIF.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Mendapatkan atau mengatur nilai bias eksposur.

Nilai: Nilai bias eksposur.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Mendapatkan atau mengatur indeks eksposur.

Nilai: Indeks eksposur.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Mendapatkan atau mengatur mode eksposur.

Nilai: Mode eksposur.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Mendapatkan atau mengatur program eksposur.

Nilai: Program eksposur.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Mendapatkan atau mengatur waktu eksposur.

Nilai: Waktu eksposur.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Mendapatkan atau mengatur nomor F.

Nilai: Nomor-F.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Mendapatkan atau mengatur tipe sumber file.

Nilai: Tipe sumber file.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


Mendapatkan atau mengatur flash.

Nilai: Lampu kilat.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Mendapatkan atau mengatur energi flash.

Nilai: Energi lampu kilat.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Mendapatkan atau mengatur versi pix flash.

Nilai: Versi pix lampu kilat.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Mendapatkan atau mengatur panjang fokus.

Nilai: Panjang fokus.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Mendapatkan atau mengatur panjang fokus dalam film 35 mm.

Nilai: Panjang fokus dalam film 35 mm.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Mendapatkan atau mengatur satuan resolusi bidang fokus.

Nilai: Unit resolusi bidang fokus.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Mendapatkan atau mengatur resolusi x bidang fokus.

Nilai: Resolusi x bidang fokus.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Mendapatkan atau mengatur resolusi y bidang fokus.

Nilai: Resolusi y bidang fokus.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Mendapatkan atau mengatur ketinggian GPS.

Nilai: Ketinggian GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Mendapatkan atau mengatur ketinggian GPS yang digunakan sebagai ketinggian referensi.

Nilai: Ketinggian GPS yang digunakan sebagai ketinggian referensi.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Mendapatkan atau mengatur informasi area GPS.

Nilai: Informasi area GPS.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Mendapatkan atau mengatur GPS DOP (derajat presisi data).

Nilai: GPS DOP (derajat presisi data).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Mendapatkan atau mengatur string karakter GPS yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time).

Nilai: String karakter GPS yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time).

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Mendapatkan atau mengatur arah GPS ke titik tujuan.

Nilai: Arah GPS ke titik tujuan.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Mendapatkan atau mengatur referensi GPS yang digunakan untuk memberikan arah ke titik tujuan.

Nilai: Referensi GPS yang digunakan untuk memberikan arah ke titik tujuan.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Mendapatkan atau mengatur jarak GPS ke titik tujuan.

Nilai: Jarak GPS ke titik tujuan.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Mendapatkan atau mengatur satuan GPS yang digunakan untuk menyatakan jarak ke titik tujuan.

Nilai: Unit GPS yang digunakan untuk menyatakan jarak ke titik tujuan.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Mendapatkan atau mengatur lintang GPS dari titik tujuan.

Nilai: Garis lintang GPS dari titik tujuan.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah lintang titik tujuan berada di lintang utara atau selatan.

Nilai: Nilai GPS yang menunjukkan apakah garis lintang titik tujuan berada di lintang utara atau selatan.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Mendapatkan atau mengatur bujur GPS dari titik tujuan.

Nilai: Garis bujur GPS dari titik tujuan.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat.

Nilai: Nilai GPS yang menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS.

Nilai: Nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Mendapatkan atau mengatur arah GPS gambar saat diambil.

Nilai: Arah GPS gambar saat diambil.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Mendapatkan atau mengatur referensi GPS untuk memberikan arah gambar saat diambil.

Nilai: Referensi GPS untuk memberikan arah gambar saat diambil.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Mendapatkan atau mengatur lintang GPS.

Nilai: Garis lintang GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Mendapatkan atau mengatur apakah lintang GPS berada di lintang utara atau selatan.

Nilai: Garis lintang GPS adalah lintang utara atau selatan.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Mendapatkan atau mengatur bujur GPS.

Nilai: Garis bujur GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Mendapatkan atau mengatur apakah bujur GPS berada di bujur timur atau barat.

Nilai: Garis bujur GPS adalah bujur timur atau barat.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Mendapatkan atau mengatur data survei geodetik GPS yang digunakan oleh penerima GPS.

Nilai: Data survei geodetik GPS yang digunakan oleh penerima GPS.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Mendapatkan atau mengatur mode pengukuran GPS.

Nilai: Mode pengukuran GPS.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Mendapatkan atau mengatur string karakter GPS yang merekam nama metode yang digunakan untuk menemukan lokasi.

Nilai: String karakter GPS yang merekam nama metode yang digunakan untuk menemukan lokasi.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Mendapatkan atau mengatur satelit GPS yang digunakan untuk pengukuran.

Nilai: Satelit GPS yang digunakan untuk pengukuran.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Mendapatkan atau mengatur kecepatan pergerakan penerima GPS.

Nilai: Kecepatan pergerakan penerima GPS.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Mendapatkan atau mengatur satuan yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS.

Nilai: Unit yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Mendapatkan atau mengatur status penerima GPS saat gambar direkam.

Nilai: Status penerima GPS saat gambar direkam.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Mendapatkan atau mengatur tag, yang hanya termasuk dalam bagian GPS.

Nilai: Tag GPS.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Mendapatkan atau mengatur waktu GPS sebagai UTC (Coordinated Universal Time).

Nilai: Waktu GPS sebagai UTC (Coordinated Universal Time).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Mendapatkan atau mengatur arah pergerakan penerima GPS.

Nilai: Arah pergerakan penerima GPS.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Mendapatkan atau mengatur referensi untuk memberikan arah pergerakan penerima GPS.

Nilai: Referensi untuk memberikan arah pergerakan penerima GPS.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Mendapatkan atau mengatur pengidentifikasi versi GPS.

Nilai: Pengidentifikasi versi GPS.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Mendapatkan atau mengatur tingkat penyesuaian gain gambar secara keseluruhan.

Nilai: Derajat penyesuaian gain keseluruhan gambar.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Mendapatkan atau mengatur gamma.

Nilai: Nilai gamma.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Mendapatkan atau mengatur kecepatan ISO

Nilai: Kecepatan ISO.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Mendapatkan atau mengatur nilai latitude kecepatan ISO yyy dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Nilai: Nilai latitude yyy kecepatan ISO dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Tag ini tidak boleh direkam tanpa ISOSpeed dan ISOSpeedLatitudezzz

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Mendapatkan atau mengatur nilai latitude kecepatan ISO zzz dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Nilai: Kecepatan ISO latitude zzz dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Tag ini tidak boleh direkam tanpa ISOSpeed dan ISOSpeedLatitudeyyy

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Mendapatkan atau mengatur pengidentifikasi unik gambar.

Nilai: Pengidentifikasi unik gambar.

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Mendapatkan atau mengatur pembuat lensa.

Nilai: Pembuat lensa.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Mendapatkan atau mengatur model lensa.

Nilai: Model lensa.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Mendapatkan atau mengatur nomor seri lensa.

Nilai: Nomor seri lensa.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Mendapatkan atau mengatur spesifikasi lensa

Nilai: Spesifikasi lensa.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Mendapatkan atau mengatur sumber cahaya.

Nilai: Sumber cahaya.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


Mendapatkan produsen peralatan perekaman.

Nilai: Produsen peralatan perekaman.

**Returns:**
java.lang.String - produsen peralatan perekaman.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Mendapatkan data catatan pembuat.

Nilai: Data catatan pembuat.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Mendapatkan atau mengatur data mentah catatan pembuat.

Nilai: Data mentah catatan pembuat.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Mendapatkan catatan pembuat.

Nilai: Catatan pembuat.

**Returns:**
com.aspose.psd.exif.MakerNote[] - catatan pembuat.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Mendapatkan atau mengatur nilai apertur maksimum.

Nilai: Nilai apertur maksimum.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Mendapatkan atau mengatur mode pengukuran.

Nilai: Mode pengukuran.

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Mendapatkan atau mengatur Fungsi Konversi Opto-Elektrik (OECF) yang ditentukan dalam ISO 14524.

Nilai: Fungsi Konversi Opto-Listrik (OECF) yang ditentukan dalam ISO 14524.

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Mendapatkan atau mengatur sensitivitas fotografi.

Nilai: Sensitivitas fotografi.

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Mendapatkan atau mengatur dimensi x piksel.

Nilai: Dimensi x piksel.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Mendapatkan atau mengatur dimensi y piksel.

Nilai: Dimensi y piksel.

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Mendapatkan atau mengatur semua tag EXIF (termasuk tag umum dan GPS).

Nilai: Tag EXIF (termasuk tag umum dan GPS).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Mendapatkan atau mengatur indeks eksposur yang direkomendasikan.

Nilai: Indeks eksposur yang direkomendasikan.

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Mendapatkan atau mengatur file suara terkait.

Nilai: Berkas suara terkait.

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Mendapatkan atau mengatur saturasi.

Nilai: Saturasi.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Mendapatkan atau mengatur tipe penangkapan adegan.

Nilai: Jenis penangkapan adegan.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Mendapatkan atau mengatur tipe adegan.

Nilai: Jenis adegan.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Mendapatkan atau mengatur metode penginderaan.

Nilai: Metode penginderaan.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Mendapatkan atau mengatur tipe sensitivitas.

Nilai: Jenis sensitivitas.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Mendapatkan atau mengatur ketajaman.

Nilai: Ketajaman.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Mendapatkan atau mengatur nilai kecepatan rana.

Nilai: Nilai kecepatan rana.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Mendapatkan atau mengatur respons frekuensi spasial.

Nilai: Respons frekuensi spasial.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Mendapatkan atau mengatur sensitivitas spektral.

Nilai: Sensitivitas spektral.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Mendapatkan sensitivitas output standar

Nilai: Sensitivitas output standar.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Mendapatkan atau mengatur area subjek.

Nilai: Area subjek.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Mendapatkan atau mengatur jarak subjek.

Nilai: Jarak subjek.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Mendapatkan atau mengatur rentang jarak subjek.

Nilai: Rentang jarak subjek.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Mendapatkan atau mengatur lokasi subjek.

Nilai: Lokasi subjek.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Mendapatkan atau mengatur fraksi detik untuk tag DateTime.

Nilai: Pecahan detik untuk tag DateTime.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Mendapatkan atau mengatur fraksi detik untuk tag DateTimeDigitized.

Nilai: Pecahan detik untuk tag DateTimeDigitized.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Mendapatkan atau mengatur fraksi detik untuk tag DateTimeOriginal.

Nilai: Pecahan detik untuk tag DateTimeOriginal.

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Mendapatkan atau mengatur komentar pengguna.

Nilai: Komentar pengguna.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Mendapatkan atau mengatur keseimbangan putih.

Nilai: Keseimbangan putih.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Mendapatkan atau mengatur kromatisitas titik putih gambar.

Nilai: Kromatisitas titik putih gambar.

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


Mendapatkan atau mengatur nilai yang menunjukkan apakah data EXIF aliran yang dibuat dari berurutan big endian.

Nilai:  true  jika data EXIF aliran yang dibuat darinya berurutan besar; jika tidak,  false .

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


Hapus tag dari kontainer

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tagId | int | Pengidentifikasi tag yang akan dihapus. |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Mendapatkan atau mengatur nilai aperture.

Nilai: Nilai bukaan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah data EXIF aliran yang dibuat dari berurutan big endian.

Nilai:  true  jika data EXIF aliran yang dibuat darinya berurutan besar; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Mendapatkan atau mengatur nomor seri badan kamera.

Nilai: Nomor seri bodi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Mendapatkan atau mengatur nilai kecerahan.

Nilai: Nilai kecerahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Mendapatkan atau mengatur pola CFA.

Nilai: Pola CFA.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Mendapatkan atau mengatur nama pemilik kamera

Nilai: Nama pemilik kamera.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Mendapatkan atau mengatur ruang warna.

Nilai: Ruang warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Mendapatkan atau mengatur tag yang termasuk dalam bagian umum. Ini hanya berlaku untuk gambar jpeg, pada format tiff opsi tiffOptions digunakan sebagai gantinya

Nilai: Tag bagian umum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Mendapatkan atau mengatur konfigurasi komponen.

Nilai: Konfigurasi komponen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Mendapatkan atau mengatur bit terkompresi per piksel.

Nilai: Bit terkompresi per piksel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Mendapatkan atau mengatur kontras.

Nilai: Kontras.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Mendapatkan atau mengatur render khusus.

Nilai: Rendering khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Mendapatkan atau mengatur tanggal waktu digitalisasi.

Nilai: Tanggal dan waktu digitalisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Mendapatkan atau mengatur tanggal waktu asli.

Nilai: Tanggal dan waktu asli.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Mendapatkan atau mengatur deskripsi pengaturan perangkat

Nilai: Deskripsi pengaturan perangkat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Mendapatkan atau mengatur rasio zoom digital.

Nilai: Rasio zoom digital.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Mendapatkan atau mengatur tag yang hanya termasuk dalam bagian EXIF.

Nilai: Tag bagian EXIF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Mendapatkan atau mengatur versi EXIF.

Nilai: Versi EXIF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Mendapatkan atau mengatur nilai bias eksposur.

Nilai: Nilai bias eksposur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Mendapatkan atau mengatur indeks eksposur.

Nilai: Indeks eksposur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Mendapatkan atau mengatur mode eksposur.

Nilai: Mode eksposur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Mendapatkan atau mengatur program eksposur.

Nilai: Program eksposur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Mendapatkan atau mengatur waktu eksposur.

Nilai: Waktu eksposur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Mendapatkan atau mengatur nomor F.

Nilai: Nomor-F.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Mendapatkan atau mengatur tipe sumber file.

Nilai: Tipe sumber file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Mendapatkan atau mengatur flash.

Nilai: Lampu kilat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Mendapatkan atau mengatur energi flash.

Nilai: Energi lampu kilat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Mendapatkan atau mengatur versi pix flash.

Nilai: Versi pix lampu kilat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Mendapatkan atau mengatur panjang fokus.

Nilai: Panjang fokus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Mendapatkan atau mengatur panjang fokus dalam film 35 mm.

Nilai: Panjang fokus dalam film 35 mm.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Mendapatkan atau mengatur satuan resolusi bidang fokus.

Nilai: Unit resolusi bidang fokus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Mendapatkan atau mengatur resolusi x bidang fokus.

Nilai: Resolusi x bidang fokus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Mendapatkan atau mengatur resolusi y bidang fokus.

Nilai: Resolusi y bidang fokus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Mendapatkan atau mengatur ketinggian GPS.

Nilai: Ketinggian GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Mendapatkan atau mengatur ketinggian GPS yang digunakan sebagai ketinggian referensi.

Nilai: Ketinggian GPS yang digunakan sebagai ketinggian referensi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Mendapatkan atau mengatur informasi area GPS.

Nilai: Informasi area GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Mendapatkan atau mengatur GPS DOP (derajat presisi data).

Nilai: GPS DOP (derajat presisi data).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Mendapatkan atau mengatur string karakter GPS yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time).

Nilai: String karakter GPS yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Mendapatkan atau mengatur arah GPS ke titik tujuan.

Nilai: Arah GPS ke titik tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Mendapatkan atau mengatur referensi GPS yang digunakan untuk memberikan arah ke titik tujuan.

Nilai: Referensi GPS yang digunakan untuk memberikan arah ke titik tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Mendapatkan atau mengatur jarak GPS ke titik tujuan.

Nilai: Jarak GPS ke titik tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Mendapatkan atau mengatur satuan GPS yang digunakan untuk menyatakan jarak ke titik tujuan.

Nilai: Unit GPS yang digunakan untuk menyatakan jarak ke titik tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Mendapatkan atau mengatur lintang GPS dari titik tujuan.

Nilai: Garis lintang GPS dari titik tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah lintang titik tujuan berada di lintang utara atau selatan.

Nilai: Nilai GPS yang menunjukkan apakah garis lintang titik tujuan berada di lintang utara atau selatan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Mendapatkan atau mengatur bujur GPS dari titik tujuan.

Nilai: Garis bujur GPS dari titik tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat.

Nilai: Nilai GPS yang menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS.

Nilai: Nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Mendapatkan atau mengatur arah GPS gambar saat diambil.

Nilai: Arah GPS gambar saat diambil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Mendapatkan atau mengatur referensi GPS untuk memberikan arah gambar saat diambil.

Nilai: Referensi GPS untuk memberikan arah gambar saat diambil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Mendapatkan atau mengatur lintang GPS.

Nilai: Garis lintang GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Mendapatkan atau mengatur apakah lintang GPS berada di lintang utara atau selatan.

Nilai: Garis lintang GPS adalah lintang utara atau selatan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Mendapatkan atau mengatur bujur GPS.

Nilai: Garis bujur GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Mendapatkan atau mengatur apakah bujur GPS berada di bujur timur atau barat.

Nilai: Garis bujur GPS adalah bujur timur atau barat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Mendapatkan atau mengatur data survei geodetik GPS yang digunakan oleh penerima GPS.

Nilai: Data survei geodetik GPS yang digunakan oleh penerima GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Mendapatkan atau mengatur mode pengukuran GPS.

Nilai: Mode pengukuran GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Mendapatkan atau mengatur string karakter GPS yang merekam nama metode yang digunakan untuk menemukan lokasi.

Nilai: String karakter GPS yang merekam nama metode yang digunakan untuk menemukan lokasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Mendapatkan atau mengatur satelit GPS yang digunakan untuk pengukuran.

Nilai: Satelit GPS yang digunakan untuk pengukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Mendapatkan atau mengatur kecepatan pergerakan penerima GPS.

Nilai: Kecepatan pergerakan penerima GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Mendapatkan atau mengatur satuan yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS.

Nilai: Unit yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Mendapatkan atau mengatur status penerima GPS saat gambar direkam.

Nilai: Status penerima GPS saat gambar direkam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Mendapatkan atau mengatur tag, yang hanya termasuk dalam bagian GPS.

Nilai: Tag GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Mendapatkan atau mengatur waktu GPS sebagai UTC (Coordinated Universal Time).

Nilai: Waktu GPS sebagai UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Mendapatkan atau mengatur arah pergerakan penerima GPS.

Nilai: Arah pergerakan penerima GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Mendapatkan atau mengatur referensi untuk memberikan arah pergerakan penerima GPS.

Nilai: Referensi untuk memberikan arah pergerakan penerima GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Mendapatkan atau mengatur pengidentifikasi versi GPS.

Nilai: Pengidentifikasi versi GPS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Mendapatkan atau mengatur tingkat penyesuaian gain gambar secara keseluruhan.

Nilai: Derajat penyesuaian gain keseluruhan gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Mendapatkan atau mengatur gamma.

Nilai: Nilai gamma.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Mendapatkan atau mengatur kecepatan ISO

Nilai: Kecepatan ISO.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Mendapatkan atau mengatur nilai latitude kecepatan ISO yyy dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Nilai: Nilai latitude yyy kecepatan ISO dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Tag ini tidak boleh direkam tanpa ISOSpeed dan ISOSpeedLatitudezzz

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Mendapatkan atau mengatur nilai latitude kecepatan ISO zzz dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Nilai: Kecepatan ISO latitude zzz dari kamera atau perangkat input yang didefinisikan dalam ISO 12232.

Tag ini tidak boleh direkam tanpa ISOSpeed dan ISOSpeedLatitudeyyy

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Mendapatkan atau mengatur pengidentifikasi unik gambar.

Nilai: Pengidentifikasi unik gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Mendapatkan atau mengatur pembuat lensa.

Nilai: Pembuat lensa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Mendapatkan atau mengatur model lensa.

Nilai: Model lensa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Mendapatkan atau mengatur nomor seri lensa.

Nilai: Nomor seri lensa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Mendapatkan atau mengatur spesifikasi lensa

Nilai: Spesifikasi lensa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Mendapatkan atau mengatur sumber cahaya.

Nilai: Sumber cahaya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Mengatur produsen peralatan perekaman.

Nilai: Produsen peralatan perekaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | pabrikan peralatan perekaman. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Mendapatkan atau mengatur data mentah catatan pembuat.

Nilai: Data mentah catatan pembuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Mendapatkan atau mengatur nilai apertur maksimum.

Nilai: Nilai apertur maksimum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Mendapatkan atau mengatur mode pengukuran.

Nilai: Mode pengukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Mendapatkan atau mengatur Fungsi Konversi Opto-Elektrik (OECF) yang ditentukan dalam ISO 14524.

Nilai: Fungsi Konversi Opto-Listrik (OECF) yang ditentukan dalam ISO 14524.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Mendapatkan atau mengatur sensitivitas fotografi.

Nilai: Sensitivitas fotografi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Mendapatkan atau mengatur dimensi x piksel.

Nilai: Dimensi x piksel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Mendapatkan atau mengatur dimensi y piksel.

Nilai: Dimensi y piksel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Mendapatkan atau mengatur semua tag EXIF (termasuk tag umum dan GPS).

Nilai: Tag EXIF (termasuk tag umum dan GPS).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Mendapatkan atau mengatur indeks eksposur yang direkomendasikan.

Nilai: Indeks eksposur yang direkomendasikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Mendapatkan atau mengatur file suara terkait.

Nilai: Berkas suara terkait.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Mendapatkan atau mengatur saturasi.

Nilai: Saturasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Mendapatkan atau mengatur tipe penangkapan adegan.

Nilai: Jenis penangkapan adegan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Mendapatkan atau mengatur tipe adegan.

Nilai: Jenis adegan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Mendapatkan atau mengatur metode penginderaan.

Nilai: Metode penginderaan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Mendapatkan atau mengatur tipe sensitivitas.

Nilai: Jenis sensitivitas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Mendapatkan atau mengatur ketajaman.

Nilai: Ketajaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Mendapatkan atau mengatur nilai kecepatan rana.

Nilai: Nilai kecepatan rana.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Mendapatkan atau mengatur respons frekuensi spasial.

Nilai: Respons frekuensi spasial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Mendapatkan atau mengatur sensitivitas spektral.

Nilai: Sensitivitas spektral.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Mengatur sensitivitas output standar

Nilai: Sensitivitas output standar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Mendapatkan atau mengatur area subjek.

Nilai: Area subjek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Mendapatkan atau mengatur jarak subjek.

Nilai: Jarak subjek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Mendapatkan atau mengatur rentang jarak subjek.

Nilai: Rentang jarak subjek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Mendapatkan atau mengatur lokasi subjek.

Nilai: Lokasi subjek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Mendapatkan atau mengatur fraksi detik untuk tag DateTime.

Nilai: Pecahan detik untuk tag DateTime.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Mendapatkan atau mengatur fraksi detik untuk tag DateTimeDigitized.

Nilai: Pecahan detik untuk tag DateTimeDigitized.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Mendapatkan atau mengatur fraksi detik untuk tag DateTimeOriginal.

Nilai: Pecahan detik untuk tag DateTimeOriginal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Mendapatkan atau mengatur komentar pengguna.

Nilai: Komentar pengguna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Mendapatkan atau mengatur keseimbangan putih.

Nilai: Keseimbangan putih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Mendapatkan atau mengatur kromatisitas titik putih gambar.

Nilai: Kromatisitas titik putih gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

