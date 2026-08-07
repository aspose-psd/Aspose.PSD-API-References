---
title: "ExifData"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "EXIF डेटा कंटेनर।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

EXIF डेटा कंटेनर।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ExifData()](#ExifData--) | ExifData क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | एक नया ExifData क्लास का उदाहरण एरे से डेटा के साथ प्रारंभ करता है। |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | एक नया ExifData क्लास का उदाहरण एरे से डेटा के साथ प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | अपर्चर मान को प्राप्त या सेट करता है। |
| [getBodySerialNumber()](#getBodySerialNumber--) | कैमरा बॉडी सीरियल नंबर को प्राप्त या सेट करता है। |
| [getBrightnessValue()](#getBrightnessValue--) | ब्राइटनेस मान को प्राप्त या सेट करता है। |
| [getCFAPattern()](#getCFAPattern--) | CFA पैटर्न को प्राप्त या सेट करता है। |
| [getCameraOwnerName()](#getCameraOwnerName--) | कैमरा मालिक का नाम प्राप्त या सेट करता है |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | कलर स्पेस को प्राप्त या सेट करता है। |
| [getCommonTags()](#getCommonTags--) | टैग्स को प्राप्त या सेट करता है, जो सामान्य सेक्शन से संबंधित हैं। |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | घटक कॉन्फ़िगरेशन को प्राप्त या सेट करता है। |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | प्रति पिक्सेल संकुचित बिट्स को प्राप्त या सेट करता है। |
| [getContrast()](#getContrast--) | कॉन्ट्रास्ट को प्राप्त या सेट करता है। |
| [getCustomRendered()](#getCustomRendered--) | कस्टम रेंडर्ड को प्राप्त या सेट करता है। |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | डिजिटाइज़्ड डेट टाइम को प्राप्त या सेट करता है। |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | ऑरिजिनल डेट टाइम को प्राप्त या सेट करता है। |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | डिवाइस सेटिंग्स विवरण प्राप्त करता है या सेट करता है |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | डिजिटल ज़ूम अनुपात प्राप्त करता है या सेट करता है। |
| [getExifTags()](#getExifTags--) | केवल EXIF सेक्शन से संबंधित टैग प्राप्त करता है या सेट करता है। |
| [getExifVersion()](#getExifVersion--) | EXIF संस्करण प्राप्त करता है या सेट करता है। |
| [getExposureBiasValue()](#getExposureBiasValue--) | एक्सपोज़र बायस मान प्राप्त करता है या सेट करता है। |
| [getExposureIndex()](#getExposureIndex--) | एक्सपोज़र इंडेक्स प्राप्त करता है या सेट करता है। |
| [getExposureMode()](#getExposureMode--) | एक्सपोज़र मोड प्राप्त करता है या सेट करता है। |
| [getExposureProgram()](#getExposureProgram--) | एक्सपोज़र प्रोग्राम प्राप्त करता है या सेट करता है। |
| [getExposureTime()](#getExposureTime--) | एक्सपोज़र समय प्राप्त करता है या सेट करता है। |
| [getFNumber()](#getFNumber--) | F-नंबर प्राप्त करता है या सेट करता है। |
| [getFileSource()](#getFileSource--) | फ़ाइल स्रोत प्रकार प्राप्त करता है या सेट करता है। |
| [getFlash()](#getFlash--) | फ़्लैश प्राप्त करता है या सेट करता है। |
| [getFlashEnergy()](#getFlashEnergy--) | फ़्लैश ऊर्जा प्राप्त करता है या सेट करता है। |
| [getFlashpixVersion()](#getFlashpixVersion--) | फ़्लैश पिक्स संस्करण प्राप्त करता है या सेट करता है। |
| [getFocalLength()](#getFocalLength--) | फ़ोकल लंबाई प्राप्त करता है या सेट करता है। |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | 35 मिमी फ़िल्म में फ़ोकल लंबाई प्राप्त करता है या सेट करता है। |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | फ़ोकल प्लेन रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है। |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | फ़ोकल प्लेन X रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | फ़ोकल प्लेन Y रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| [getGPSAltitude()](#getGPSAltitude--) | GPS ऊँचाई प्राप्त करता है या सेट करता है। |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | संदर्भ ऊँचाई के रूप में उपयोग की गई GPS ऊँचाई प्राप्त करता है या सेट करता है। |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | GPS क्षेत्र जानकारी प्राप्त करता है या सेट करता है। |
| [getGPSDOP()](#getGPSDOP--) | GPS DOP (डेटा सटीकता डिग्री) प्राप्त करता है या सेट करता है। |
| [getGPSDateStamp()](#getGPSDateStamp--) | UTC (समन्वित सार्वभौमिक समय) के सापेक्ष GPS कैरेक्टर स्ट्रिंग रिकॉर्डिंग तिथि और समय जानकारी प्राप्त करता है या सेट करता है। |
| [getGPSDestBearing()](#getGPSDestBearing--) | गंतव्य बिंदु की ओर GPS बियरिंग प्राप्त करता है या सेट करता है। |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | प्राप्त करता है या सेट करता है GPS रेफ़रेंस जिसका उपयोग गंतव्य बिंदु की दिशा देने के लिए किया जाता है। |
| [getGPSDestDistance()](#getGPSDestDistance--) | प्राप्त करता है या सेट करता है GPS दूरी गंतव्य बिंदु तक। |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | प्राप्त करता है या सेट करता है GPS इकाई जिसका उपयोग गंतव्य बिंदु तक की दूरी व्यक्त करने के लिए किया जाता है। |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | प्राप्त करता है या सेट करता है GPS अक्षांश गंतव्य बिंदु का। |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का अक्षांश उत्तर है या दक्षिण। |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | प्राप्त करता है या सेट करता है GPS देशांतर गंतव्य बिंदु का। |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का देशांतर पूर्व है या पश्चिम। |
| [getGPSDifferential()](#getGPSDifferential--) | प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि अंतरात्मक सुधार GPS रिसीवर पर लागू किया गया है या नहीं। |
| [getGPSImgDirection()](#getGPSImgDirection--) | प्राप्त करता है या सेट करता है GPS दिशा छवि की जब इसे कैप्चर किया गया था। |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | प्राप्त करता है या सेट करता है GPS रेफ़रेंस छवि की दिशा देने के लिए जब इसे कैप्चर किया जाता है। |
| [getGPSLatitude()](#getGPSLatitude--) | प्राप्त करता है या सेट करता है GPS अक्षांश। |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | प्राप्त करता है या सेट करता है GPS अक्षांश उत्तर है या दक्षिण। |
| [getGPSLongitude()](#getGPSLongitude--) | प्राप्त करता है या सेट करता है GPS देशांतर। |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | प्राप्त करता है या सेट करता है GPS देशांतर पूर्व है या पश्चिम। |
| [getGPSMapDatum()](#getGPSMapDatum--) | प्राप्त करता है या सेट करता है GPS भू-आकृतिक सर्वे डेटा जिसका उपयोग GPS रिसीवर द्वारा किया जाता है। |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | प्राप्त करता है या सेट करता है GPS मापन मोड। |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | प्राप्त करता है या सेट करता है GPS अक्षर स्ट्रिंग जो स्थान खोजने के लिए उपयोग की गई विधि का नाम रिकॉर्ड करती है। |
| [getGPSSatellites()](#getGPSSatellites--) | प्राप्त करता है या सेट करता है GPS उपग्रह जो माप के लिए उपयोग किए जाते हैं। |
| [getGPSSpeed()](#getGPSSpeed--) | प्राप्त करता है या सेट करता है GPS रिसीवर की गति। |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | प्राप्त करता है या सेट करता है इकाई जिसका उपयोग GPS रिसीवर की गति व्यक्त करने के लिए किया जाता है। |
| [getGPSStatus()](#getGPSStatus--) | प्राप्त करता है या सेट करता है GPS रिसीवर की स्थिति जब छवि रिकॉर्ड की जाती है। |
| [getGPSTags()](#getGPSTags--) | प्राप्त करता है या सेट करता है टैग, जो केवल GPS सेक्शन से संबंधित हैं। |
| [getGPSTimestamp()](#getGPSTimestamp--) | प्राप्त करता है या सेट करता है GPS समय को UTC (समन्वित सार्वभौमिक समय) के रूप में। |
| [getGPSTrack()](#getGPSTrack--) | प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा। |
| [getGPSTrackRef()](#getGPSTrackRef--) | प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा देने के लिए रेफ़रेंस। |
| [getGPSVersionID()](#getGPSVersionID--) | GPS संस्करण पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| [getGainControl()](#getGainControl--) | समग्र छवि गेन समायोजन की डिग्री को प्राप्त करता है या सेट करता है। |
| [getGamma()](#getGamma--) | गामा को प्राप्त करता है या सेट करता है। |
| [getISOSpeed()](#getISOSpeed--) | ISO गति को प्राप्त करता है या सेट करता है। |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड yyy मान को प्राप्त करता है या सेट करता है। |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड zzz मान को प्राप्त करता है या सेट करता है। |
| [getImageUniqueID()](#getImageUniqueID--) | छवि अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| [getLensMake()](#getLensMake--) | लेंस निर्माता को प्राप्त करता है या सेट करता है। |
| [getLensModel()](#getLensModel--) | लेंस मॉडल को प्राप्त करता है या सेट करता है। |
| [getLensSerialNumber()](#getLensSerialNumber--) | लेंस सीरियल नंबर को प्राप्त करता है या सेट करता है। |
| [getLensSpecification()](#getLensSpecification--) | लेंस विनिर्देश को प्राप्त करता है या सेट करता है। |
| [getLightSource()](#getLightSource--) | प्रकाश स्रोत को प्राप्त करता है या सेट करता है। |
| [getMake()](#getMake--) | रिकॉर्डिंग उपकरण के निर्माता को प्राप्त करता है। |
| [getMakerNoteData()](#getMakerNoteData--) | निर्माता नोट डेटा को प्राप्त करता है। |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | निर्माता नोट कच्चा डेटा को प्राप्त करता है या सेट करता है। |
| [getMakerNotes()](#getMakerNotes--) | निर्माता नोट्स को प्राप्त करता है। |
| [getMaxApertureValue()](#getMaxApertureValue--) | अधिकतम एपर्चर मान को प्राप्त करता है या सेट करता है। |
| [getMeteringMode()](#getMeteringMode--) | मीटरिंग मोड को प्राप्त करता है या सेट करता है। |
| [getOECF()](#getOECF--) | ISO 14524 में निर्दिष्ट ऑप्टो-इलेक्ट्रिक कन्वर्ज़न फ़ंक्शन (OECF) को प्राप्त करता है या सेट करता है। |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | फ़ोटोग्राफ़िक संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [getPixelXDimension()](#getPixelXDimension--) | पिक्सेल X आयाम को प्राप्त करता है या सेट करता है। |
| [getPixelYDimension()](#getPixelYDimension--) | पिक्सेल Y आयाम को प्राप्त करता है या सेट करता है। |
| [getProperties()](#getProperties--) | सभी EXIF टैग्स (सामान्य और GPS टैग्स सहित) को प्राप्त करता है या सेट करता है। |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | सिफ़ारिश किया गया एक्सपोज़र इंडेक्स को प्राप्त करता है या सेट करता है। |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | संबंधित साउंड फ़ाइल को प्राप्त करता है या सेट करता है। |
| [getSaturation()](#getSaturation--) | सैचुरेशन को प्राप्त करता है या सेट करता है। |
| [getSceneCaptureType()](#getSceneCaptureType--) | सीन कैप्चर प्रकार को प्राप्त करता है या सेट करता है। |
| [getSceneType()](#getSceneType--) | सीन प्रकार को प्राप्त करता है या सेट करता है। |
| [getSensingMethod()](#getSensingMethod--) | सेंसिंग विधि को प्राप्त करता है या सेट करता है। |
| [getSensitivityType()](#getSensitivityType--) | संवेदनशीलता प्रकार को प्राप्त करता है या सेट करता है। |
| [getSharpness()](#getSharpness--) | तीक्ष्णता को प्राप्त करता है या सेट करता है। |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | शटर स्पीड मान को प्राप्त करता है या सेट करता है। |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | स्पैशियल फ़्रीक्वेंसी रिस्पॉन्स को प्राप्त करता है या सेट करता है। |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | स्पेक्ट्रल संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | मानक आउटपुट संवेदनशीलता को प्राप्त करता है |
| [getSubjectArea()](#getSubjectArea--) | सब्जेक्ट एरिया को प्राप्त करता है या सेट करता है। |
| [getSubjectDistance()](#getSubjectDistance--) | सब्जेक्ट दूरी को प्राप्त करता है या सेट करता है। |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | सब्जेक्ट दूरी रेंज को प्राप्त करता है या सेट करता है। |
| [getSubjectLocation()](#getSubjectLocation--) | सब्जेक्ट लोकेशन को प्राप्त करता है या सेट करता है। |
| [getSubsecTime()](#getSubsecTime--) | DateTime टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | DateTimeDigitized टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | DateTimeOriginal टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| [getUserComment()](#getUserComment--) | उपयोगकर्ता टिप्पणी को प्राप्त करता है या सेट करता है। |
| [getWhiteBalance()](#getWhiteBalance--) | व्हाइट बैलेंस को प्राप्त करता है या सेट करता है। |
| [getWhitePoint()](#getWhitePoint--) | छवि के व्हाइट पॉइंट की क्रोमैटिसिटी को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि स्ट्रीम EXIF डेटा बिग एंडियन है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | कंटेनर से टैग हटाएँ |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | अपर्चर मान को प्राप्त या सेट करता है। |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि स्ट्रीम EXIF डेटा बिग एंडियन है या नहीं। |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | कैमरा बॉडी सीरियल नंबर को प्राप्त या सेट करता है। |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | ब्राइटनेस मान को प्राप्त या सेट करता है। |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | CFA पैटर्न को प्राप्त या सेट करता है। |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | कैमरा मालिक का नाम प्राप्त या सेट करता है |
| [setColorSpace(int value)](#setColorSpace-int-) | कलर स्पेस को प्राप्त या सेट करता है। |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | टैग्स को प्राप्त या सेट करता है, जो सामान्य सेक्शन से संबंधित हैं। |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | घटक कॉन्फ़िगरेशन को प्राप्त या सेट करता है। |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | प्रति पिक्सेल संकुचित बिट्स को प्राप्त या सेट करता है। |
| [setContrast(int value)](#setContrast-int-) | कॉन्ट्रास्ट को प्राप्त या सेट करता है। |
| [setCustomRendered(int value)](#setCustomRendered-int-) | कस्टम रेंडर्ड को प्राप्त या सेट करता है। |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | डिजिटाइज़्ड डेट टाइम को प्राप्त या सेट करता है। |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | ऑरिजिनल डेट टाइम को प्राप्त या सेट करता है। |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | डिवाइस सेटिंग्स विवरण प्राप्त करता है या सेट करता है |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | डिजिटल ज़ूम अनुपात प्राप्त करता है या सेट करता है। |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | केवल EXIF सेक्शन से संबंधित टैग प्राप्त करता है या सेट करता है। |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | EXIF संस्करण प्राप्त करता है या सेट करता है। |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | एक्सपोज़र बायस मान प्राप्त करता है या सेट करता है। |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | एक्सपोज़र इंडेक्स प्राप्त करता है या सेट करता है। |
| [setExposureMode(int value)](#setExposureMode-int-) | एक्सपोज़र मोड प्राप्त करता है या सेट करता है। |
| [setExposureProgram(int value)](#setExposureProgram-int-) | एक्सपोज़र प्रोग्राम प्राप्त करता है या सेट करता है। |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | एक्सपोज़र समय प्राप्त करता है या सेट करता है। |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | F-नंबर प्राप्त करता है या सेट करता है। |
| [setFileSource(byte value)](#setFileSource-byte-) | फ़ाइल स्रोत प्रकार प्राप्त करता है या सेट करता है। |
| [setFlash(int value)](#setFlash-int-) | फ़्लैश प्राप्त करता है या सेट करता है। |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | फ़्लैश ऊर्जा प्राप्त करता है या सेट करता है। |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | फ़्लैश पिक्स संस्करण प्राप्त करता है या सेट करता है। |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | फ़ोकल लंबाई प्राप्त करता है या सेट करता है। |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | 35 मिमी फ़िल्म में फ़ोकल लंबाई प्राप्त करता है या सेट करता है। |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | फ़ोकल प्लेन रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है। |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | फ़ोकल प्लेन X रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | फ़ोकल प्लेन Y रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS ऊँचाई प्राप्त करता है या सेट करता है। |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | संदर्भ ऊँचाई के रूप में उपयोग की गई GPS ऊँचाई प्राप्त करता है या सेट करता है। |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | GPS क्षेत्र जानकारी प्राप्त करता है या सेट करता है। |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS DOP (डेटा सटीकता डिग्री) प्राप्त करता है या सेट करता है। |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | UTC (समन्वित सार्वभौमिक समय) के सापेक्ष GPS कैरेक्टर स्ट्रिंग रिकॉर्डिंग तिथि और समय जानकारी प्राप्त करता है या सेट करता है। |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | गंतव्य बिंदु की ओर GPS बियरिंग प्राप्त करता है या सेट करता है। |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS रेफ़रेंस जिसका उपयोग गंतव्य बिंदु की दिशा देने के लिए किया जाता है। |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | प्राप्त करता है या सेट करता है GPS दूरी गंतव्य बिंदु तक। |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS इकाई जिसका उपयोग गंतव्य बिंदु तक की दूरी व्यक्त करने के लिए किया जाता है। |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | प्राप्त करता है या सेट करता है GPS अक्षांश गंतव्य बिंदु का। |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का अक्षांश उत्तर है या दक्षिण। |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | प्राप्त करता है या सेट करता है GPS देशांतर गंतव्य बिंदु का। |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का देशांतर पूर्व है या पश्चिम। |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि अंतरात्मक सुधार GPS रिसीवर पर लागू किया गया है या नहीं। |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | प्राप्त करता है या सेट करता है GPS दिशा छवि की जब इसे कैप्चर किया गया था। |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS रेफ़रेंस छवि की दिशा देने के लिए जब इसे कैप्चर किया जाता है। |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | प्राप्त करता है या सेट करता है GPS अक्षांश। |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS अक्षांश उत्तर है या दक्षिण। |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | प्राप्त करता है या सेट करता है GPS देशांतर। |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS देशांतर पूर्व है या पश्चिम। |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | प्राप्त करता है या सेट करता है GPS भू-आकृतिक सर्वे डेटा जिसका उपयोग GPS रिसीवर द्वारा किया जाता है। |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | प्राप्त करता है या सेट करता है GPS मापन मोड। |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | प्राप्त करता है या सेट करता है GPS अक्षर स्ट्रिंग जो स्थान खोजने के लिए उपयोग की गई विधि का नाम रिकॉर्ड करती है। |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | प्राप्त करता है या सेट करता है GPS उपग्रह जो माप के लिए उपयोग किए जाते हैं। |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | प्राप्त करता है या सेट करता है GPS रिसीवर की गति। |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | प्राप्त करता है या सेट करता है इकाई जिसका उपयोग GPS रिसीवर की गति व्यक्त करने के लिए किया जाता है। |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | प्राप्त करता है या सेट करता है GPS रिसीवर की स्थिति जब छवि रिकॉर्ड की जाती है। |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | प्राप्त करता है या सेट करता है टैग, जो केवल GPS सेक्शन से संबंधित हैं। |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | प्राप्त करता है या सेट करता है GPS समय को UTC (समन्वित सार्वभौमिक समय) के रूप में। |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा। |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा देने के लिए रेफ़रेंस। |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | GPS संस्करण पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| [setGainControl(int value)](#setGainControl-int-) | समग्र छवि गेन समायोजन की डिग्री को प्राप्त करता है या सेट करता है। |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | गामा को प्राप्त करता है या सेट करता है। |
| [setISOSpeed(long value)](#setISOSpeed-long-) | ISO गति को प्राप्त करता है या सेट करता है। |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड yyy मान को प्राप्त करता है या सेट करता है। |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड zzz मान को प्राप्त करता है या सेट करता है। |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | छवि अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | लेंस निर्माता को प्राप्त करता है या सेट करता है। |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | लेंस मॉडल को प्राप्त करता है या सेट करता है। |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | लेंस सीरियल नंबर को प्राप्त करता है या सेट करता है। |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | लेंस विनिर्देश को प्राप्त करता है या सेट करता है। |
| [setLightSource(int value)](#setLightSource-int-) | प्रकाश स्रोत को प्राप्त करता है या सेट करता है। |
| [setMake(String value)](#setMake-java.lang.String-) | रिकॉर्डिंग उपकरण के निर्माता को सेट करता है। |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | निर्माता नोट कच्चा डेटा को प्राप्त करता है या सेट करता है। |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | अधिकतम एपर्चर मान को प्राप्त करता है या सेट करता है। |
| [setMeteringMode(int value)](#setMeteringMode-int-) | मीटरिंग मोड को प्राप्त करता है या सेट करता है। |
| [setOECF(byte[] value)](#setOECF-byte---) | ISO 14524 में निर्दिष्ट ऑप्टो-इलेक्ट्रिक कन्वर्ज़न फ़ंक्शन (OECF) को प्राप्त करता है या सेट करता है। |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | फ़ोटोग्राफ़िक संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | पिक्सेल X आयाम को प्राप्त करता है या सेट करता है। |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | पिक्सेल Y आयाम को प्राप्त करता है या सेट करता है। |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | सभी EXIF टैग्स (सामान्य और GPS टैग्स सहित) को प्राप्त करता है या सेट करता है। |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | सिफ़ारिश किया गया एक्सपोज़र इंडेक्स को प्राप्त करता है या सेट करता है। |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | संबंधित साउंड फ़ाइल को प्राप्त करता है या सेट करता है। |
| [setSaturation(int value)](#setSaturation-int-) | सैचुरेशन को प्राप्त करता है या सेट करता है। |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | सीन कैप्चर प्रकार को प्राप्त करता है या सेट करता है। |
| [setSceneType(byte value)](#setSceneType-byte-) | सीन प्रकार को प्राप्त करता है या सेट करता है। |
| [setSensingMethod(int value)](#setSensingMethod-int-) | सेंसिंग विधि को प्राप्त करता है या सेट करता है। |
| [setSensitivityType(int value)](#setSensitivityType-int-) | संवेदनशीलता प्रकार को प्राप्त करता है या सेट करता है। |
| [setSharpness(int value)](#setSharpness-int-) | तीक्ष्णता को प्राप्त करता है या सेट करता है। |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | शटर स्पीड मान को प्राप्त करता है या सेट करता है। |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | स्पैशियल फ़्रीक्वेंसी रिस्पॉन्स को प्राप्त करता है या सेट करता है। |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | स्पेक्ट्रल संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | मानक आउटपुट संवेदनशीलता को सेट करता है |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | सब्जेक्ट एरिया को प्राप्त करता है या सेट करता है। |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | सब्जेक्ट दूरी को प्राप्त करता है या सेट करता है। |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | सब्जेक्ट दूरी रेंज को प्राप्त करता है या सेट करता है। |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | सब्जेक्ट लोकेशन को प्राप्त करता है या सेट करता है। |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | DateTime टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | DateTimeDigitized टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | DateTimeOriginal टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | उपयोगकर्ता टिप्पणी को प्राप्त करता है या सेट करता है। |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | व्हाइट बैलेंस को प्राप्त करता है या सेट करता है। |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | छवि के व्हाइट पॉइंट की क्रोमैटिसिटी को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


ExifData क्लास का एक नया उदाहरण प्रारंभ करता है।

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


एक नया ExifData क्लास का उदाहरण एरे से डेटा के साथ प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | सामान्य और GPS टैग के साथ EXIF टैग की एरे। |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


एक नया ExifData क्लास का उदाहरण एरे से डेटा के साथ प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | सामान्य टैग। |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | EXIF टैग। |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | GPS टैग। |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


अपर्चर मान को प्राप्त या सेट करता है।

मान: अपर्चर मान।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


कैमरा बॉडी सीरियल नंबर को प्राप्त या सेट करता है।

मान: बॉडी सीरियल नंबर।

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


ब्राइटनेस मान को प्राप्त या सेट करता है।

मान: ब्राइटनेस मान।

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


CFA पैटर्न को प्राप्त या सेट करता है।

मान: CFA पैटर्न।

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


कैमरा मालिक का नाम प्राप्त या सेट करता है

मान: कैमरा मालिक का नाम।

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


कलर स्पेस को प्राप्त या सेट करता है।

मान: कलर स्पेस।

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


सामान्य सेक्शन से संबंधित टैग प्राप्त करता है या सेट करता है। यह केवल jpeg छवियों पर लागू होता है, tiff फ़ॉर्मेट में tiffOptions का उपयोग किया जाता है।

मान: सामान्य सेक्शन टैग।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


घटक कॉन्फ़िगरेशन को प्राप्त या सेट करता है।

मान: कंपोनेंट्स कॉन्फ़िगरेशन।

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


प्रति पिक्सेल संकुचित बिट्स को प्राप्त या सेट करता है।

मान: प्रति पिक्सेल संपीड़ित बिट्स।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


कॉन्ट्रास्ट को प्राप्त या सेट करता है।

मान: कंट्रास्ट।

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


कस्टम रेंडर्ड को प्राप्त या सेट करता है।

मान: कस्टम रेंडर किया गया।

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


डिजिटाइज़्ड डेट टाइम को प्राप्त या सेट करता है।

मान: डेट टाइम डिजिटाइज़्ड।

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


ऑरिजिनल डेट टाइम को प्राप्त या सेट करता है।

मान: मूल डेट टाइम।

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


डिवाइस सेटिंग्स विवरण प्राप्त करता है या सेट करता है

मान: डिवाइस सेटिंग विवरण।

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


डिजिटल ज़ूम अनुपात प्राप्त करता है या सेट करता है।

मान: डिजिटल ज़ूम अनुपात।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


केवल EXIF सेक्शन से संबंधित टैग प्राप्त करता है या सेट करता है।

मान: EXIF सेक्शन टैग।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


EXIF संस्करण प्राप्त करता है या सेट करता है।

मान: EXIF संस्करण।

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


एक्सपोज़र बायस मान प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र बायस मान।

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


एक्सपोज़र इंडेक्स प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र का इंडेक्स।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


एक्सपोज़र मोड प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र मोड।

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


एक्सपोज़र प्रोग्राम प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र प्रोग्राम।

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


एक्सपोज़र समय प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र समय।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


F-नंबर प्राप्त करता है या सेट करता है।

मान: F-नंबर।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


फ़ाइल स्रोत प्रकार प्राप्त करता है या सेट करता है।

मान: फ़ाइल स्रोत प्रकार।

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


फ़्लैश प्राप्त करता है या सेट करता है।

मान: फ्लैश।

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


फ़्लैश ऊर्जा प्राप्त करता है या सेट करता है।

मान: फ्लैश ऊर्जा।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


फ़्लैश पिक्स संस्करण प्राप्त करता है या सेट करता है।

मान: फ्लैश पिक्स संस्करण।

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


फ़ोकल लंबाई प्राप्त करता है या सेट करता है।

मान: फोकल की लंबाई।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


35 मिमी फ़िल्म में फ़ोकल लंबाई प्राप्त करता है या सेट करता है।

मान: 35 मिमी फ़िल्म में फोकल लंबाई।

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


फ़ोकल प्लेन रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है।

मान: फोकल प्लेन रिज़ॉल्यूशन इकाई।

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


फ़ोकल प्लेन X रिज़ॉल्यूशन प्राप्त करता है या सेट करता है।

मान: फोकल प्लेन X रिज़ॉल्यूशन।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


फ़ोकल प्लेन Y रिज़ॉल्यूशन प्राप्त करता है या सेट करता है।

मान: फोकल प्लेन Y रिज़ॉल्यूशन।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


GPS ऊँचाई प्राप्त करता है या सेट करता है।

मान: GPS ऊँचाई।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


संदर्भ ऊँचाई के रूप में उपयोग की गई GPS ऊँचाई प्राप्त करता है या सेट करता है।

मान: GPS ऊँचाई को संदर्भ ऊँचाई के रूप में उपयोग किया गया।

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


GPS क्षेत्र जानकारी प्राप्त करता है या सेट करता है।

मान: GPS क्षेत्र जानकारी।

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


GPS DOP (डेटा सटीकता डिग्री) प्राप्त करता है या सेट करता है।

मान: GPS DOP (डेटा सटीकता डिग्री)।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


UTC (समन्वित सार्वभौमिक समय) के सापेक्ष GPS कैरेक्टर स्ट्रिंग रिकॉर्डिंग तिथि और समय जानकारी प्राप्त करता है या सेट करता है।

मान: GPS कैरेक्टर स्ट्रिंग रिकॉर्डिंग तिथि और समय जानकारी UTC (समन्वित सार्वभौमिक समय) के सापेक्ष।

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


गंतव्य बिंदु की ओर GPS बियरिंग प्राप्त करता है या सेट करता है।

मान: GPS बियरिंग गंतव्य बिंदु की ओर।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


प्राप्त करता है या सेट करता है GPS रेफ़रेंस जिसका उपयोग गंतव्य बिंदु की दिशा देने के लिए किया जाता है।

मान: GPS संदर्भ जिसका उपयोग गंतव्य बिंदु की ओर बियरिंग देने के लिए किया जाता है।

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


प्राप्त करता है या सेट करता है GPS दूरी गंतव्य बिंदु तक।

मान: GPS दूरी गंतव्य बिंदु तक।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


प्राप्त करता है या सेट करता है GPS इकाई जिसका उपयोग गंतव्य बिंदु तक की दूरी व्यक्त करने के लिए किया जाता है।

मान: GPS इकाई जिसका उपयोग गंतव्य बिंदु तक की दूरी व्यक्त करने के लिए किया जाता है।

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


प्राप्त करता है या सेट करता है GPS अक्षांश गंतव्य बिंदु का।

मान: गंतव्य बिंदु की GPS अक्षांश।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का अक्षांश उत्तर है या दक्षिण।

मान: GPS मान जो दर्शाता है कि गंतव्य बिंदु की अक्षांश उत्तर या दक्षिण अक्षांश है।

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


प्राप्त करता है या सेट करता है GPS देशांतर गंतव्य बिंदु का।

मान: गंतव्य बिंदु की GPS देशांतर।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का देशांतर पूर्व है या पश्चिम।

मान: वह GPS मान जो दर्शाता है कि गंतव्य बिंदु की देशांतर पूर्व या पश्चिम है।

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि अंतरात्मक सुधार GPS रिसीवर पर लागू किया गया है या नहीं।

मान: वह GPS मान जो दर्शाता है कि क्या अंतरात्मक सुधार GPS रिसीवर पर लागू किया गया है।

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


प्राप्त करता है या सेट करता है GPS दिशा छवि की जब इसे कैप्चर किया गया था।

मान: वह GPS दिशा जिसमें छवि ली गई थी।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


प्राप्त करता है या सेट करता है GPS रेफ़रेंस छवि की दिशा देने के लिए जब इसे कैप्चर किया जाता है।

मान: वह GPS संदर्भ जो छवि ली जाने पर उसकी दिशा देता है।

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


प्राप्त करता है या सेट करता है GPS अक्षांश।

मान: GPS अक्षांश।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


प्राप्त करता है या सेट करता है GPS अक्षांश उत्तर है या दक्षिण।

मान: GPS अक्षांश उत्तर या दक्षिण अक्षांश है।

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


प्राप्त करता है या सेट करता है GPS देशांतर।

मान: GPS देशांतर।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


प्राप्त करता है या सेट करता है GPS देशांतर पूर्व है या पश्चिम।

मान: GPS देशांतर पूर्व या पश्चिम है।

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


प्राप्त करता है या सेट करता है GPS भू-आकृतिक सर्वे डेटा जिसका उपयोग GPS रिसीवर द्वारा किया जाता है।

मान: GPS जियोडेटिक सर्वे डेटा जो GPS रिसीवर द्वारा उपयोग किया जाता है।

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


प्राप्त करता है या सेट करता है GPS मापन मोड।

मान: GPS मापन मोड।

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


प्राप्त करता है या सेट करता है GPS अक्षर स्ट्रिंग जो स्थान खोजने के लिए उपयोग की गई विधि का नाम रिकॉर्ड करती है।

मान: वह GPS अक्षर स्ट्रिंग जो स्थान खोजने के लिए उपयोग की गई विधि का नाम रिकॉर्ड करती है।

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


प्राप्त करता है या सेट करता है GPS उपग्रह जो माप के लिए उपयोग किए जाते हैं।

मान: माप के लिए उपयोग किए गए GPS उपग्रह।

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


प्राप्त करता है या सेट करता है GPS रिसीवर की गति।

मान: GPS रिसीवर की गति।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


प्राप्त करता है या सेट करता है इकाई जिसका उपयोग GPS रिसीवर की गति व्यक्त करने के लिए किया जाता है।

मान: वह इकाई जिसका उपयोग GPS रिसीवर की गति व्यक्त करने के लिए किया जाता है।

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


प्राप्त करता है या सेट करता है GPS रिसीवर की स्थिति जब छवि रिकॉर्ड की जाती है।

मान: वह स्थिति जब छवि रिकॉर्ड की जाती है, GPS रिसीवर की।

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


प्राप्त करता है या सेट करता है टैग, जो केवल GPS सेक्शन से संबंधित हैं।

मान: GPS टैग।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


प्राप्त करता है या सेट करता है GPS समय को UTC (समन्वित सार्वभौमिक समय) के रूप में।

मान: GPS समय UTC (समन्वित सार्वभौमिक समय) के रूप में।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा।

मान: GPS रिसीवर की गति की दिशा।

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा देने के लिए रेफ़रेंस।

मान: GPS रिसीवर की गति की दिशा देने के लिए संदर्भ।

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


GPS संस्करण पहचानकर्ता को प्राप्त करता है या सेट करता है।

मान: GPS संस्करण पहचानकर्ता।

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


समग्र छवि गेन समायोजन की डिग्री को प्राप्त करता है या सेट करता है।

मान: कुल छवि गेन समायोजन की डिग्री।

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


गामा को प्राप्त करता है या सेट करता है।

मान: गामा मान।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


ISO गति को प्राप्त करता है या सेट करता है।

मान: ISO गति।

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड yyy मान को प्राप्त करता है या सेट करता है।

मान: ISO गति अक्षांश yyy मान एक कैमरा या इनपुट डिवाइस का जो ISO 12232 में परिभाषित है।

यह टैग ISOSpeed और ISOSpeedLatitudezzz के बिना रिकॉर्ड नहीं किया जाना चाहिए।

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड zzz मान को प्राप्त करता है या सेट करता है।

मान: एक कैमरा या इनपुट डिवाइस का ISO स्पीड लैटिट्यूड zzz मान, जो ISO 12232 में परिभाषित है।

इस टैग को ISOSpeed और ISOSpeedLatitudeyyy के बिना रिकॉर्ड नहीं किया जाना चाहिए।

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


छवि अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है।

मान: छवि का अद्वितीय पहचानकर्ता।

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


लेंस निर्माता को प्राप्त करता है या सेट करता है।

मान: लेंस निर्माता।

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


लेंस मॉडल को प्राप्त करता है या सेट करता है।

मान: लेंस मॉडल।

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


लेंस सीरियल नंबर को प्राप्त करता है या सेट करता है।

मान: लेंस सीरियल नंबर।

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


लेंस विनिर्देश को प्राप्त करता है या सेट करता है।

मान: लेंस विनिर्देश।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


प्रकाश स्रोत को प्राप्त करता है या सेट करता है।

मान: प्रकाश स्रोत।

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


रिकॉर्डिंग उपकरण के निर्माता को प्राप्त करता है।

मान: रिकॉर्डिंग उपकरण का निर्माता।

**Returns:**
java.lang.String - रिकॉर्डिंग उपकरण का निर्माता।
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


निर्माता नोट डेटा को प्राप्त करता है।

मान: मेकर नोट डेटा।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


निर्माता नोट कच्चा डेटा को प्राप्त करता है या सेट करता है।

मान: मेकर नोट कच्चा डेटा।

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


निर्माता नोट्स को प्राप्त करता है।

मान: मेकर नोट्स।

**Returns:**
com.aspose.psd.exif.MakerNote[] - मेकर नोट्स।
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


अधिकतम एपर्चर मान को प्राप्त करता है या सेट करता है।

मान: अधिकतम एपर्चर मान।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


मीटरिंग मोड को प्राप्त करता है या सेट करता है।

मान: मीटरिंग मोड।

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


ISO 14524 में निर्दिष्ट ऑप्टो-इलेक्ट्रिक कन्वर्ज़न फ़ंक्शन (OECF) को प्राप्त करता है या सेट करता है।

मान: ISO 14524 में निर्दिष्ट ऑप्टो-इलेक्ट्रिक कन्वर्ज़न फ़ंक्शन (OECF)।

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


फ़ोटोग्राफ़िक संवेदनशीलता को प्राप्त करता है या सेट करता है।

मान: फ़ोटोग्राफ़िक संवेदनशीलता।

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


पिक्सेल X आयाम को प्राप्त करता है या सेट करता है।

मान: पिक्सेल X आयाम।

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


पिक्सेल Y आयाम को प्राप्त करता है या सेट करता है।

मान: पिक्सेल Y आयाम।

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


सभी EXIF टैग्स (सामान्य और GPS टैग्स सहित) को प्राप्त करता है या सेट करता है।

मान: EXIF टैग्स (सामान्य और GPS टैग्स सहित)।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


सिफ़ारिश किया गया एक्सपोज़र इंडेक्स को प्राप्त करता है या सेट करता है।

मान: अनुशंसित एक्सपोज़र इंडेक्स।

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


संबंधित साउंड फ़ाइल को प्राप्त करता है या सेट करता है।

मान: संबंधित साउंड फ़ाइल।

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


सैचुरेशन को प्राप्त करता है या सेट करता है।

मान: संतृप्ति।

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


सीन कैप्चर प्रकार को प्राप्त करता है या सेट करता है।

मान: सीन कैप्चर का प्रकार।

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


सीन प्रकार को प्राप्त करता है या सेट करता है।

Value: दृश्य का प्रकार।

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


सेंसिंग विधि को प्राप्त करता है या सेट करता है।

Value: संवेदन विधि।

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


संवेदनशीलता प्रकार को प्राप्त करता है या सेट करता है।

Value: संवेदनशीलता का प्रकार।

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


तीक्ष्णता को प्राप्त करता है या सेट करता है।

Value: तीक्ष्णता।

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


शटर स्पीड मान को प्राप्त करता है या सेट करता है।

Value: शटर स्पीड मान।

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


स्पैशियल फ़्रीक्वेंसी रिस्पॉन्स को प्राप्त करता है या सेट करता है।

Value: स्थानिक आवृत्ति प्रतिक्रिया।

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


स्पेक्ट्रल संवेदनशीलता को प्राप्त करता है या सेट करता है।

Value: स्पेक्ट्रल संवेदनशीलता।

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


मानक आउटपुट संवेदनशीलता को प्राप्त करता है

Value: मानक आउटपुट संवेदनशीलता।

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


सब्जेक्ट एरिया को प्राप्त करता है या सेट करता है।

Value: विषय क्षेत्र।

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


सब्जेक्ट दूरी को प्राप्त करता है या सेट करता है।

Value: विषय दूरी।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


सब्जेक्ट दूरी रेंज को प्राप्त करता है या सेट करता है।

Value: विषय दूरी सीमा।

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


सब्जेक्ट लोकेशन को प्राप्त करता है या सेट करता है।

Value: विषय स्थान।

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


DateTime टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है।

Value: DateTime टैग के लिए सेकंड के अंश।

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


DateTimeDigitized टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है।

Value: DateTimeDigitized टैग के लिए सेकंड के अंश।

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


DateTimeOriginal टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है।

Value: DateTimeOriginal टैग के लिए सेकंड के अंश।

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


उपयोगकर्ता टिप्पणी को प्राप्त करता है या सेट करता है।

Value: उपयोगकर्ता टिप्पणी।

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


व्हाइट बैलेंस को प्राप्त करता है या सेट करता है।

Value: व्हाइट बैलेंस।

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


छवि के व्हाइट पॉइंट की क्रोमैटिसिटी को प्राप्त करता है या सेट करता है।

Value: छवि के व्हाइट पॉइंट की रंगता।

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


एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि स्ट्रीम EXIF डेटा बिग एंडियन है या नहीं।

Value:  true  यदि स्ट्रीम EXIF डेटा बिग एंडियन है; अन्यथा,  false .

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


कंटेनर से टैग हटाएँ

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tagId | int | हटाने के लिए टैग पहचानकर्ता। |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


अपर्चर मान को प्राप्त या सेट करता है।

मान: अपर्चर मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि स्ट्रीम EXIF डेटा बिग एंडियन है या नहीं।

Value:  true  यदि स्ट्रीम EXIF डेटा बिग एंडियन है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


कैमरा बॉडी सीरियल नंबर को प्राप्त या सेट करता है।

मान: बॉडी सीरियल नंबर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


ब्राइटनेस मान को प्राप्त या सेट करता है।

मान: ब्राइटनेस मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


CFA पैटर्न को प्राप्त या सेट करता है।

मान: CFA पैटर्न।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


कैमरा मालिक का नाम प्राप्त या सेट करता है

मान: कैमरा मालिक का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


कलर स्पेस को प्राप्त या सेट करता है।

मान: कलर स्पेस।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


सामान्य सेक्शन से संबंधित टैग प्राप्त करता है या सेट करता है। यह केवल jpeg छवियों पर लागू होता है, tiff फ़ॉर्मेट में tiffOptions का उपयोग किया जाता है।

मान: सामान्य सेक्शन टैग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


घटक कॉन्फ़िगरेशन को प्राप्त या सेट करता है।

मान: कंपोनेंट्स कॉन्फ़िगरेशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


प्रति पिक्सेल संकुचित बिट्स को प्राप्त या सेट करता है।

मान: प्रति पिक्सेल संपीड़ित बिट्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


कॉन्ट्रास्ट को प्राप्त या सेट करता है।

मान: कंट्रास्ट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


कस्टम रेंडर्ड को प्राप्त या सेट करता है।

मान: कस्टम रेंडर किया गया।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


डिजिटाइज़्ड डेट टाइम को प्राप्त या सेट करता है।

मान: डेट टाइम डिजिटाइज़्ड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


ऑरिजिनल डेट टाइम को प्राप्त या सेट करता है।

मान: मूल डेट टाइम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


डिवाइस सेटिंग्स विवरण प्राप्त करता है या सेट करता है

मान: डिवाइस सेटिंग विवरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


डिजिटल ज़ूम अनुपात प्राप्त करता है या सेट करता है।

मान: डिजिटल ज़ूम अनुपात।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


केवल EXIF सेक्शन से संबंधित टैग प्राप्त करता है या सेट करता है।

मान: EXIF सेक्शन टैग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


EXIF संस्करण प्राप्त करता है या सेट करता है।

मान: EXIF संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


एक्सपोज़र बायस मान प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र बायस मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


एक्सपोज़र इंडेक्स प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र का इंडेक्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


एक्सपोज़र मोड प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


एक्सपोज़र प्रोग्राम प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र प्रोग्राम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


एक्सपोज़र समय प्राप्त करता है या सेट करता है।

मान: एक्सपोज़र समय।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


F-नंबर प्राप्त करता है या सेट करता है।

मान: F-नंबर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


फ़ाइल स्रोत प्रकार प्राप्त करता है या सेट करता है।

मान: फ़ाइल स्रोत प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


फ़्लैश प्राप्त करता है या सेट करता है।

मान: फ्लैश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


फ़्लैश ऊर्जा प्राप्त करता है या सेट करता है।

मान: फ्लैश ऊर्जा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


फ़्लैश पिक्स संस्करण प्राप्त करता है या सेट करता है।

मान: फ्लैश पिक्स संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


फ़ोकल लंबाई प्राप्त करता है या सेट करता है।

मान: फोकल की लंबाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


35 मिमी फ़िल्म में फ़ोकल लंबाई प्राप्त करता है या सेट करता है।

मान: 35 मिमी फ़िल्म में फोकल लंबाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


फ़ोकल प्लेन रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है।

मान: फोकल प्लेन रिज़ॉल्यूशन इकाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


फ़ोकल प्लेन X रिज़ॉल्यूशन प्राप्त करता है या सेट करता है।

मान: फोकल प्लेन X रिज़ॉल्यूशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


फ़ोकल प्लेन Y रिज़ॉल्यूशन प्राप्त करता है या सेट करता है।

मान: फोकल प्लेन Y रिज़ॉल्यूशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


GPS ऊँचाई प्राप्त करता है या सेट करता है।

मान: GPS ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


संदर्भ ऊँचाई के रूप में उपयोग की गई GPS ऊँचाई प्राप्त करता है या सेट करता है।

मान: GPS ऊँचाई को संदर्भ ऊँचाई के रूप में उपयोग किया गया।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


GPS क्षेत्र जानकारी प्राप्त करता है या सेट करता है।

मान: GPS क्षेत्र जानकारी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


GPS DOP (डेटा सटीकता डिग्री) प्राप्त करता है या सेट करता है।

मान: GPS DOP (डेटा सटीकता डिग्री)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


UTC (समन्वित सार्वभौमिक समय) के सापेक्ष GPS कैरेक्टर स्ट्रिंग रिकॉर्डिंग तिथि और समय जानकारी प्राप्त करता है या सेट करता है।

मान: GPS कैरेक्टर स्ट्रिंग रिकॉर्डिंग तिथि और समय जानकारी UTC (समन्वित सार्वभौमिक समय) के सापेक्ष।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


गंतव्य बिंदु की ओर GPS बियरिंग प्राप्त करता है या सेट करता है।

मान: GPS बियरिंग गंतव्य बिंदु की ओर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


प्राप्त करता है या सेट करता है GPS रेफ़रेंस जिसका उपयोग गंतव्य बिंदु की दिशा देने के लिए किया जाता है।

मान: GPS संदर्भ जिसका उपयोग गंतव्य बिंदु की ओर बियरिंग देने के लिए किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


प्राप्त करता है या सेट करता है GPS दूरी गंतव्य बिंदु तक।

मान: GPS दूरी गंतव्य बिंदु तक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


प्राप्त करता है या सेट करता है GPS इकाई जिसका उपयोग गंतव्य बिंदु तक की दूरी व्यक्त करने के लिए किया जाता है।

मान: GPS इकाई जिसका उपयोग गंतव्य बिंदु तक की दूरी व्यक्त करने के लिए किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


प्राप्त करता है या सेट करता है GPS अक्षांश गंतव्य बिंदु का।

मान: गंतव्य बिंदु की GPS अक्षांश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का अक्षांश उत्तर है या दक्षिण।

मान: GPS मान जो दर्शाता है कि गंतव्य बिंदु की अक्षांश उत्तर या दक्षिण अक्षांश है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


प्राप्त करता है या सेट करता है GPS देशांतर गंतव्य बिंदु का।

मान: गंतव्य बिंदु की GPS देशांतर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि गंतव्य बिंदु का देशांतर पूर्व है या पश्चिम।

मान: वह GPS मान जो दर्शाता है कि गंतव्य बिंदु की देशांतर पूर्व या पश्चिम है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


प्राप्त करता है या सेट करता है GPS मान जो दर्शाता है कि अंतरात्मक सुधार GPS रिसीवर पर लागू किया गया है या नहीं।

मान: वह GPS मान जो दर्शाता है कि क्या अंतरात्मक सुधार GPS रिसीवर पर लागू किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


प्राप्त करता है या सेट करता है GPS दिशा छवि की जब इसे कैप्चर किया गया था।

मान: वह GPS दिशा जिसमें छवि ली गई थी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


प्राप्त करता है या सेट करता है GPS रेफ़रेंस छवि की दिशा देने के लिए जब इसे कैप्चर किया जाता है।

मान: वह GPS संदर्भ जो छवि ली जाने पर उसकी दिशा देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


प्राप्त करता है या सेट करता है GPS अक्षांश।

मान: GPS अक्षांश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


प्राप्त करता है या सेट करता है GPS अक्षांश उत्तर है या दक्षिण।

मान: GPS अक्षांश उत्तर या दक्षिण अक्षांश है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


प्राप्त करता है या सेट करता है GPS देशांतर।

मान: GPS देशांतर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


प्राप्त करता है या सेट करता है GPS देशांतर पूर्व है या पश्चिम।

मान: GPS देशांतर पूर्व या पश्चिम है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


प्राप्त करता है या सेट करता है GPS भू-आकृतिक सर्वे डेटा जिसका उपयोग GPS रिसीवर द्वारा किया जाता है।

मान: GPS जियोडेटिक सर्वे डेटा जो GPS रिसीवर द्वारा उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


प्राप्त करता है या सेट करता है GPS मापन मोड।

मान: GPS मापन मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


प्राप्त करता है या सेट करता है GPS अक्षर स्ट्रिंग जो स्थान खोजने के लिए उपयोग की गई विधि का नाम रिकॉर्ड करती है।

मान: वह GPS अक्षर स्ट्रिंग जो स्थान खोजने के लिए उपयोग की गई विधि का नाम रिकॉर्ड करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


प्राप्त करता है या सेट करता है GPS उपग्रह जो माप के लिए उपयोग किए जाते हैं।

मान: माप के लिए उपयोग किए गए GPS उपग्रह।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


प्राप्त करता है या सेट करता है GPS रिसीवर की गति।

मान: GPS रिसीवर की गति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


प्राप्त करता है या सेट करता है इकाई जिसका उपयोग GPS रिसीवर की गति व्यक्त करने के लिए किया जाता है।

मान: वह इकाई जिसका उपयोग GPS रिसीवर की गति व्यक्त करने के लिए किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


प्राप्त करता है या सेट करता है GPS रिसीवर की स्थिति जब छवि रिकॉर्ड की जाती है।

मान: वह स्थिति जब छवि रिकॉर्ड की जाती है, GPS रिसीवर की।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


प्राप्त करता है या सेट करता है टैग, जो केवल GPS सेक्शन से संबंधित हैं।

मान: GPS टैग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


प्राप्त करता है या सेट करता है GPS समय को UTC (समन्वित सार्वभौमिक समय) के रूप में।

मान: GPS समय UTC (समन्वित सार्वभौमिक समय) के रूप में।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा।

मान: GPS रिसीवर की गति की दिशा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


प्राप्त करता है या सेट करता है GPS रिसीवर की गति की दिशा देने के लिए रेफ़रेंस।

मान: GPS रिसीवर की गति की दिशा देने के लिए संदर्भ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


GPS संस्करण पहचानकर्ता को प्राप्त करता है या सेट करता है।

मान: GPS संस्करण पहचानकर्ता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


समग्र छवि गेन समायोजन की डिग्री को प्राप्त करता है या सेट करता है।

मान: कुल छवि गेन समायोजन की डिग्री।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


गामा को प्राप्त करता है या सेट करता है।

मान: गामा मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


ISO गति को प्राप्त करता है या सेट करता है।

मान: ISO गति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड yyy मान को प्राप्त करता है या सेट करता है।

मान: ISO गति अक्षांश yyy मान एक कैमरा या इनपुट डिवाइस का जो ISO 12232 में परिभाषित है।

यह टैग ISOSpeed और ISOSpeedLatitudezzz के बिना रिकॉर्ड नहीं किया जाना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति लैटिट्यूड zzz मान को प्राप्त करता है या सेट करता है।

मान: एक कैमरा या इनपुट डिवाइस का ISO स्पीड लैटिट्यूड zzz मान, जो ISO 12232 में परिभाषित है।

इस टैग को ISOSpeed और ISOSpeedLatitudeyyy के बिना रिकॉर्ड नहीं किया जाना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


छवि अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है।

मान: छवि का अद्वितीय पहचानकर्ता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


लेंस निर्माता को प्राप्त करता है या सेट करता है।

मान: लेंस निर्माता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


लेंस मॉडल को प्राप्त करता है या सेट करता है।

मान: लेंस मॉडल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


लेंस सीरियल नंबर को प्राप्त करता है या सेट करता है।

मान: लेंस सीरियल नंबर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


लेंस विनिर्देश को प्राप्त करता है या सेट करता है।

मान: लेंस विनिर्देश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


प्रकाश स्रोत को प्राप्त करता है या सेट करता है।

मान: प्रकाश स्रोत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


रिकॉर्डिंग उपकरण के निर्माता को सेट करता है।

मान: रिकॉर्डिंग उपकरण का निर्माता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | रिकॉर्डिंग उपकरण का निर्माता। |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


निर्माता नोट कच्चा डेटा को प्राप्त करता है या सेट करता है।

मान: मेकर नोट कच्चा डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


अधिकतम एपर्चर मान को प्राप्त करता है या सेट करता है।

मान: अधिकतम एपर्चर मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


मीटरिंग मोड को प्राप्त करता है या सेट करता है।

मान: मीटरिंग मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


ISO 14524 में निर्दिष्ट ऑप्टो-इलेक्ट्रिक कन्वर्ज़न फ़ंक्शन (OECF) को प्राप्त करता है या सेट करता है।

मान: ISO 14524 में निर्दिष्ट ऑप्टो-इलेक्ट्रिक कन्वर्ज़न फ़ंक्शन (OECF)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


फ़ोटोग्राफ़िक संवेदनशीलता को प्राप्त करता है या सेट करता है।

मान: फ़ोटोग्राफ़िक संवेदनशीलता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


पिक्सेल X आयाम को प्राप्त करता है या सेट करता है।

मान: पिक्सेल X आयाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


पिक्सेल Y आयाम को प्राप्त करता है या सेट करता है।

मान: पिक्सेल Y आयाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


सभी EXIF टैग्स (सामान्य और GPS टैग्स सहित) को प्राप्त करता है या सेट करता है।

मान: EXIF टैग्स (सामान्य और GPS टैग्स सहित)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


सिफ़ारिश किया गया एक्सपोज़र इंडेक्स को प्राप्त करता है या सेट करता है।

मान: अनुशंसित एक्सपोज़र इंडेक्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


संबंधित साउंड फ़ाइल को प्राप्त करता है या सेट करता है।

मान: संबंधित साउंड फ़ाइल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


सैचुरेशन को प्राप्त करता है या सेट करता है।

मान: संतृप्ति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


सीन कैप्चर प्रकार को प्राप्त करता है या सेट करता है।

मान: सीन कैप्चर का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


सीन प्रकार को प्राप्त करता है या सेट करता है।

Value: दृश्य का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


सेंसिंग विधि को प्राप्त करता है या सेट करता है।

Value: संवेदन विधि।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


संवेदनशीलता प्रकार को प्राप्त करता है या सेट करता है।

Value: संवेदनशीलता का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


तीक्ष्णता को प्राप्त करता है या सेट करता है।

Value: तीक्ष्णता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


शटर स्पीड मान को प्राप्त करता है या सेट करता है।

Value: शटर स्पीड मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


स्पैशियल फ़्रीक्वेंसी रिस्पॉन्स को प्राप्त करता है या सेट करता है।

Value: स्थानिक आवृत्ति प्रतिक्रिया।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


स्पेक्ट्रल संवेदनशीलता को प्राप्त करता है या सेट करता है।

Value: स्पेक्ट्रल संवेदनशीलता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


मानक आउटपुट संवेदनशीलता को सेट करता है

Value: मानक आउटपुट संवेदनशीलता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


सब्जेक्ट एरिया को प्राप्त करता है या सेट करता है।

Value: विषय क्षेत्र।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


सब्जेक्ट दूरी को प्राप्त करता है या सेट करता है।

Value: विषय दूरी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


सब्जेक्ट दूरी रेंज को प्राप्त करता है या सेट करता है।

Value: विषय दूरी सीमा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


सब्जेक्ट लोकेशन को प्राप्त करता है या सेट करता है।

Value: विषय स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


DateTime टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है।

Value: DateTime टैग के लिए सेकंड के अंश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


DateTimeDigitized टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है।

Value: DateTimeDigitized टैग के लिए सेकंड के अंश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


DateTimeOriginal टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है।

Value: DateTimeOriginal टैग के लिए सेकंड के अंश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


उपयोगकर्ता टिप्पणी को प्राप्त करता है या सेट करता है।

Value: उपयोगकर्ता टिप्पणी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


व्हाइट बैलेंस को प्राप्त करता है या सेट करता है।

Value: व्हाइट बैलेंस।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


छवि के व्हाइट पॉइंट की क्रोमैटिसिटी को प्राप्त करता है या सेट करता है।

Value: छवि के व्हाइट पॉइंट की रंगता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

