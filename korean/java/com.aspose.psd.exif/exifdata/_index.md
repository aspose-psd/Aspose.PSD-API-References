---
title: "ExifData"
second_title: "Java용 Aspose.PSD API 참조"
description: "EXIF 데이터 컨테이너."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.exif/exifdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)
```
public class ExifData extends TiffDataTypeController
```

EXIF 데이터 컨테이너.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ExifData()](#ExifData--) | 새로운 ExifData 클래스 인스턴스를 초기화합니다. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | 배열의 데이터를 사용하여 새로운 ExifData 클래스 인스턴스를 초기화합니다. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | 배열의 데이터를 사용하여 새로운 ExifData 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | 조리개 값을 가져오거나 설정합니다. |
| [getBodySerialNumber()](#getBodySerialNumber--) | 카메라 본체 일련 번호를 가져오거나 설정합니다. |
| [getBrightnessValue()](#getBrightnessValue--) | 밝기 값을 가져오거나 설정합니다. |
| [getCFAPattern()](#getCFAPattern--) | CFA 패턴을 가져오거나 설정합니다. |
| [getCameraOwnerName()](#getCameraOwnerName--) | 카메라 소유자 이름을 가져오거나 설정합니다 |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | 색 공간을 가져오거나 설정합니다. |
| [getCommonTags()](#getCommonTags--) | 공통 섹션에 속하는 태그를 가져오거나 설정합니다. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | 구성 요소 구성을 가져오거나 설정합니다. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | 픽셀당 압축 비트를 가져오거나 설정합니다. |
| [getContrast()](#getContrast--) | 대비를 가져오거나 설정합니다. |
| [getCustomRendered()](#getCustomRendered--) | 사용자 정의 렌더링을 가져오거나 설정합니다. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | 디지털화된 날짜 및 시간을 가져오거나 설정합니다. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | 원본 날짜 및 시간을 가져오거나 설정합니다. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | 장치 설정 설명을 가져오거나 설정합니다 |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | 디지털 줌 비율을 가져오거나 설정합니다. |
| [getExifTags()](#getExifTags--) | EXIF 섹션에만 해당하는 태그를 가져오거나 설정합니다. |
| [getExifVersion()](#getExifVersion--) | EXIF 버전을 가져오거나 설정합니다. |
| [getExposureBiasValue()](#getExposureBiasValue--) | 노출 보정 값을 가져오거나 설정합니다. |
| [getExposureIndex()](#getExposureIndex--) | 노출 지수를 가져오거나 설정합니다. |
| [getExposureMode()](#getExposureMode--) | 노출 모드를 가져오거나 설정합니다. |
| [getExposureProgram()](#getExposureProgram--) | 노출 프로그램을 가져오거나 설정합니다. |
| [getExposureTime()](#getExposureTime--) | 노출 시간을 가져오거나 설정합니다. |
| [getFNumber()](#getFNumber--) | F-넘버를 가져오거나 설정합니다. |
| [getFileSource()](#getFileSource--) | 파일 소스 유형을 가져오거나 설정합니다. |
| [getFlash()](#getFlash--) | 플래시를 가져오거나 설정합니다. |
| [getFlashEnergy()](#getFlashEnergy--) | 플래시 에너지를 가져오거나 설정합니다. |
| [getFlashpixVersion()](#getFlashpixVersion--) | 플래시 픽스 버전을 가져오거나 설정합니다. |
| [getFocalLength()](#getFocalLength--) | 초점 거리를 가져오거나 설정합니다. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | 35mm 필름 기준 초점 거리를 가져오거나 설정합니다. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | 초점면 해상도 단위를 가져오거나 설정합니다. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | 초점면 X 해상도를 가져오거나 설정합니다. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | 초점면 Y 해상도를 가져오거나 설정합니다. |
| [getGPSAltitude()](#getGPSAltitude--) | GPS 고도를 가져오거나 설정합니다. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | 참조 고도로 사용되는 GPS 고도를 가져오거나 설정합니다. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | GPS 영역 정보를 가져오거나 설정합니다. |
| [getGPSDOP()](#getGPSDOP--) | GPS DOP(정밀도 데이터)를 가져오거나 설정합니다. |
| [getGPSDateStamp()](#getGPSDateStamp--) | UTC(협정 세계시)와 관련된 날짜 및 시간 정보를 기록하는 GPS 문자열을 가져오거나 설정합니다. |
| [getGPSDestBearing()](#getGPSDestBearing--) | 목적지에 대한 GPS 방위를 가져오거나 설정합니다. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | 목적지에 대한 방위를 제공하는 데 사용되는 GPS 기준을 가져오거나 설정합니다. |
| [getGPSDestDistance()](#getGPSDestDistance--) | 목적지까지의 GPS 거리를 가져오거나 설정합니다. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | 목적지까지의 거리를 표현하는 데 사용되는 GPS 단위를 가져오거나 설정합니다. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | 목적지의 GPS 위도를 가져오거나 설정합니다. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | 목적지 위도가 북위인지 남위인지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | 목적지의 GPS 경도를 가져오거나 설정합니다. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | 목적지 경도가 동경인지 서경인지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| [getGPSDifferential()](#getGPSDifferential--) | GPS 수신기에 차동 보정이 적용되는지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| [getGPSImgDirection()](#getGPSImgDirection--) | 이미지가 촬영될 때의 GPS 방향을 가져오거나 설정합니다. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | 이미지가 촬영될 때 방향을 제공하는 GPS 기준을 가져오거나 설정합니다. |
| [getGPSLatitude()](#getGPSLatitude--) | GPS 위도를 가져오거나 설정합니다. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | GPS 위도가 북위인지 남위인지를 가져오거나 설정합니다. |
| [getGPSLongitude()](#getGPSLongitude--) | GPS 경도를 가져오거나 설정합니다. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | GPS 경도가 동경인지 서경인지를 가져오거나 설정합니다. |
| [getGPSMapDatum()](#getGPSMapDatum--) | GPS 수신기에 사용되는 GPS 측지 조사 데이터를 가져오거나 설정합니다. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | GPS 측정 모드를 가져오거나 설정합니다. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | 위치 찾기에 사용된 방법의 이름을 기록하는 GPS 문자열을 가져오거나 설정합니다. |
| [getGPSSatellites()](#getGPSSatellites--) | 측정에 사용되는 GPS 위성을 가져오거나 설정합니다. |
| [getGPSSpeed()](#getGPSSpeed--) | GPS 수신기 이동 속도를 가져오거나 설정합니다. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | GPS 수신기 이동 속도를 표현하는 데 사용되는 단위를 가져오거나 설정합니다. |
| [getGPSStatus()](#getGPSStatus--) | 이미지가 기록될 때 GPS 수신기의 상태를 가져오거나 설정합니다. |
| [getGPSTags()](#getGPSTags--) | GPS 섹션에만 해당하는 태그를 가져오거나 설정합니다. |
| [getGPSTimestamp()](#getGPSTimestamp--) | UTC(협정 세계시)로 표시된 GPS 시간을 가져오거나 설정합니다. |
| [getGPSTrack()](#getGPSTrack--) | GPS 수신기 움직임의 방향을 가져오거나 설정합니다. |
| [getGPSTrackRef()](#getGPSTrackRef--) | GPS 수신기 움직임의 방향을 제공하기 위한 기준을 가져오거나 설정합니다. |
| [getGPSVersionID()](#getGPSVersionID--) | GPS 버전 식별자를 가져오거나 설정합니다. |
| [getGainControl()](#getGainControl--) | 전체 이미지 이득 조정 정도를 가져오거나 설정합니다. |
| [getGamma()](#getGamma--) | 감마 값을 가져오거나 설정합니다. |
| [getISOSpeed()](#getISOSpeed--) | ISO 속도를 가져오거나 설정합니다. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 yyy 값을 가져오거나 설정합니다. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 zzz 값을 가져오거나 설정합니다. |
| [getImageUniqueID()](#getImageUniqueID--) | 이미지 고유 식별자를 가져오거나 설정합니다. |
| [getLensMake()](#getLensMake--) | 렌즈 제조사를 가져오거나 설정합니다. |
| [getLensModel()](#getLensModel--) | 렌즈 모델을 가져오거나 설정합니다. |
| [getLensSerialNumber()](#getLensSerialNumber--) | 렌즈 일련 번호를 가져오거나 설정합니다. |
| [getLensSpecification()](#getLensSpecification--) | 렌즈 사양을 가져오거나 설정합니다. |
| [getLightSource()](#getLightSource--) | 광원을 가져오거나 설정합니다. |
| [getMake()](#getMake--) | 녹음 장비의 제조사를 가져옵니다. |
| [getMakerNoteData()](#getMakerNoteData--) | 제조사 메모 데이터를 가져옵니다. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | 제조사 메모 원시 데이터를 가져오거나 설정합니다. |
| [getMakerNotes()](#getMakerNotes--) | 제조사 메모를 가져옵니다. |
| [getMaxApertureValue()](#getMaxApertureValue--) | 최대 조리개 값을 가져오거나 설정합니다. |
| [getMeteringMode()](#getMeteringMode--) | 측광 모드를 가져오거나 설정합니다. |
| [getOECF()](#getOECF--) | ISO 14524에 지정된 광전 변환 함수 (OECF)를 가져오거나 설정합니다. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | 사진 감도를 가져오거나 설정합니다. |
| [getPixelXDimension()](#getPixelXDimension--) | 픽셀 x 차원을 가져오거나 설정합니다. |
| [getPixelYDimension()](#getPixelYDimension--) | 픽셀 y 차원을 가져오거나 설정합니다. |
| [getProperties()](#getProperties--) | 공통 및 GPS 태그를 포함한 모든 EXIF 태그를 가져오거나 설정합니다. |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | 권장 노출 지수를 가져오거나 설정합니다. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | 관련 사운드 파일을 가져오거나 설정합니다. |
| [getSaturation()](#getSaturation--) | 채도를 가져오거나 설정합니다. |
| [getSceneCaptureType()](#getSceneCaptureType--) | 장면 캡처 유형을 가져오거나 설정합니다. |
| [getSceneType()](#getSceneType--) | 장면 유형을 가져오거나 설정합니다. |
| [getSensingMethod()](#getSensingMethod--) | 감지 방법을 가져오거나 설정합니다. |
| [getSensitivityType()](#getSensitivityType--) | 감도 유형을 가져오거나 설정합니다. |
| [getSharpness()](#getSharpness--) | 선명도를 가져오거나 설정합니다. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | 셔터 속도 값을 가져오거나 설정합니다. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | 공간 주파수 응답을 가져오거나 설정합니다. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | 스펙트럼 감도를 가져오거나 설정합니다. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | 표준 출력 감도를 가져옵니다 |
| [getSubjectArea()](#getSubjectArea--) | 주제 영역을 가져오거나 설정합니다. |
| [getSubjectDistance()](#getSubjectDistance--) | 주제 거리를 가져오거나 설정합니다. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | 주제 거리 범위를 가져오거나 설정합니다. |
| [getSubjectLocation()](#getSubjectLocation--) | 주제 위치를 가져오거나 설정합니다. |
| [getSubsecTime()](#getSubsecTime--) | DateTime 태그의 초 분수를 가져오거나 설정합니다. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | DateTimeDigitized 태그의 초 분수를 가져오거나 설정합니다. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | DateTimeOriginal 태그의 초 분수를 가져오거나 설정합니다. |
| [getUserComment()](#getUserComment--) | 사용자 주석을 가져오거나 설정합니다. |
| [getWhiteBalance()](#getWhiteBalance--) | 화이트 밸런스를 가져오거나 설정합니다. |
| [getWhitePoint()](#getWhitePoint--) | 이미지의 화이트 포인트 색도를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | 스트림 EXIF 데이터가 빅 엔디안으로 생성되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | 컨테이너에서 태그를 제거합니다 |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | 조리개 값을 가져오거나 설정합니다. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | 스트림 EXIF 데이터가 빅 엔디안으로 생성되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | 카메라 본체 일련 번호를 가져오거나 설정합니다. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 밝기 값을 가져오거나 설정합니다. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | CFA 패턴을 가져오거나 설정합니다. |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | 카메라 소유자 이름을 가져오거나 설정합니다 |
| [setColorSpace(int value)](#setColorSpace-int-) | 색 공간을 가져오거나 설정합니다. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 공통 섹션에 속하는 태그를 가져오거나 설정합니다. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | 구성 요소 구성을 가져오거나 설정합니다. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | 픽셀당 압축 비트를 가져오거나 설정합니다. |
| [setContrast(int value)](#setContrast-int-) | 대비를 가져오거나 설정합니다. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | 사용자 정의 렌더링을 가져오거나 설정합니다. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | 디지털화된 날짜 및 시간을 가져오거나 설정합니다. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | 원본 날짜 및 시간을 가져오거나 설정합니다. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | 장치 설정 설명을 가져오거나 설정합니다 |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | 디지털 줌 비율을 가져오거나 설정합니다. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | EXIF 섹션에만 해당하는 태그를 가져오거나 설정합니다. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | EXIF 버전을 가져오거나 설정합니다. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 노출 보정 값을 가져오거나 설정합니다. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | 노출 지수를 가져오거나 설정합니다. |
| [setExposureMode(int value)](#setExposureMode-int-) | 노출 모드를 가져오거나 설정합니다. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | 노출 프로그램을 가져오거나 설정합니다. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | 노출 시간을 가져오거나 설정합니다. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | F-넘버를 가져오거나 설정합니다. |
| [setFileSource(byte value)](#setFileSource-byte-) | 파일 소스 유형을 가져오거나 설정합니다. |
| [setFlash(int value)](#setFlash-int-) | 플래시를 가져오거나 설정합니다. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | 플래시 에너지를 가져오거나 설정합니다. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | 플래시 픽스 버전을 가져오거나 설정합니다. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | 초점 거리를 가져오거나 설정합니다. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | 35mm 필름 기준 초점 거리를 가져오거나 설정합니다. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | 초점면 해상도 단위를 가져오거나 설정합니다. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 초점면 X 해상도를 가져오거나 설정합니다. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 초점면 Y 해상도를 가져오거나 설정합니다. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS 고도를 가져오거나 설정합니다. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | 참조 고도로 사용되는 GPS 고도를 가져오거나 설정합니다. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | GPS 영역 정보를 가져오거나 설정합니다. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS DOP(정밀도 데이터)를 가져오거나 설정합니다. |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | UTC(협정 세계시)와 관련된 날짜 및 시간 정보를 기록하는 GPS 문자열을 가져오거나 설정합니다. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | 목적지에 대한 GPS 방위를 가져오거나 설정합니다. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | 목적지에 대한 방위를 제공하는 데 사용되는 GPS 기준을 가져오거나 설정합니다. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | 목적지까지의 GPS 거리를 가져오거나 설정합니다. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | 목적지까지의 거리를 표현하는 데 사용되는 GPS 단위를 가져오거나 설정합니다. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 목적지의 GPS 위도를 가져오거나 설정합니다. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | 목적지 위도가 북위인지 남위인지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 목적지의 GPS 경도를 가져오거나 설정합니다. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | 목적지 경도가 동경인지 서경인지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | GPS 수신기에 차동 보정이 적용되는지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | 이미지가 촬영될 때의 GPS 방향을 가져오거나 설정합니다. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | 이미지가 촬영될 때 방향을 제공하는 GPS 기준을 가져오거나 설정합니다. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | GPS 위도를 가져오거나 설정합니다. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | GPS 위도가 북위인지 남위인지를 가져오거나 설정합니다. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | GPS 경도를 가져오거나 설정합니다. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | GPS 경도가 동경인지 서경인지를 가져오거나 설정합니다. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | GPS 수신기에 사용되는 GPS 측지 조사 데이터를 가져오거나 설정합니다. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | GPS 측정 모드를 가져오거나 설정합니다. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | 위치 찾기에 사용된 방법의 이름을 기록하는 GPS 문자열을 가져오거나 설정합니다. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | 측정에 사용되는 GPS 위성을 가져오거나 설정합니다. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS 수신기 이동 속도를 가져오거나 설정합니다. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | GPS 수신기 이동 속도를 표현하는 데 사용되는 단위를 가져오거나 설정합니다. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | 이미지가 기록될 때 GPS 수신기의 상태를 가져오거나 설정합니다. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | GPS 섹션에만 해당하는 태그를 가져오거나 설정합니다. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | UTC(협정 세계시)로 표시된 GPS 시간을 가져오거나 설정합니다. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | GPS 수신기 움직임의 방향을 가져오거나 설정합니다. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | GPS 수신기 움직임의 방향을 제공하기 위한 기준을 가져오거나 설정합니다. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | GPS 버전 식별자를 가져오거나 설정합니다. |
| [setGainControl(int value)](#setGainControl-int-) | 전체 이미지 이득 조정 정도를 가져오거나 설정합니다. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | 감마 값을 가져오거나 설정합니다. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | ISO 속도를 가져오거나 설정합니다. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 yyy 값을 가져오거나 설정합니다. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 zzz 값을 가져오거나 설정합니다. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | 이미지 고유 식별자를 가져오거나 설정합니다. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | 렌즈 제조사를 가져오거나 설정합니다. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | 렌즈 모델을 가져오거나 설정합니다. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | 렌즈 일련 번호를 가져오거나 설정합니다. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | 렌즈 사양을 가져오거나 설정합니다. |
| [setLightSource(int value)](#setLightSource-int-) | 광원을 가져오거나 설정합니다. |
| [setMake(String value)](#setMake-java.lang.String-) | 녹음 장비의 제조업체를 설정합니다. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | 제조사 메모 원시 데이터를 가져오거나 설정합니다. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | 최대 조리개 값을 가져오거나 설정합니다. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | 측광 모드를 가져오거나 설정합니다. |
| [setOECF(byte[] value)](#setOECF-byte---) | ISO 14524에 지정된 광전 변환 함수 (OECF)를 가져오거나 설정합니다. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | 사진 감도를 가져오거나 설정합니다. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | 픽셀 x 차원을 가져오거나 설정합니다. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | 픽셀 y 차원을 가져오거나 설정합니다. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | 공통 및 GPS 태그를 포함한 모든 EXIF 태그를 가져오거나 설정합니다. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | 권장 노출 지수를 가져오거나 설정합니다. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | 관련 사운드 파일을 가져오거나 설정합니다. |
| [setSaturation(int value)](#setSaturation-int-) | 채도를 가져오거나 설정합니다. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | 장면 캡처 유형을 가져오거나 설정합니다. |
| [setSceneType(byte value)](#setSceneType-byte-) | 장면 유형을 가져오거나 설정합니다. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | 감지 방법을 가져오거나 설정합니다. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | 감도 유형을 가져오거나 설정합니다. |
| [setSharpness(int value)](#setSharpness-int-) | 선명도를 가져오거나 설정합니다. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 셔터 속도 값을 가져오거나 설정합니다. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | 공간 주파수 응답을 가져오거나 설정합니다. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | 스펙트럼 감도를 가져오거나 설정합니다. |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | 표준 출력 감도를 설정합니다 |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | 주제 영역을 가져오거나 설정합니다. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | 주제 거리를 가져오거나 설정합니다. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | 주제 거리 범위를 가져오거나 설정합니다. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | 주제 위치를 가져오거나 설정합니다. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | DateTime 태그의 초 분수를 가져오거나 설정합니다. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | DateTimeDigitized 태그의 초 분수를 가져오거나 설정합니다. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | DateTimeOriginal 태그의 초 분수를 가져오거나 설정합니다. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | 사용자 주석을 가져오거나 설정합니다. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | 화이트 밸런스를 가져오거나 설정합니다. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | 이미지의 화이트 포인트 색도를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExifData() {#ExifData--}
```
public ExifData()
```


새로운 ExifData 클래스 인스턴스를 초기화합니다.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


배열의 데이터를 사용하여 새로운 ExifData 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 공통 태그 및 GPS 태그와 함께 제공되는 EXIF 태그 배열입니다. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


배열의 데이터를 사용하여 새로운 ExifData 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 공통 태그입니다. |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | EXIF 태그입니다. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | GPS 태그입니다. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


조리개 값을 가져오거나 설정합니다.

값: 조리개 값입니다.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


카메라 본체 일련 번호를 가져오거나 설정합니다.

값: 본체 일련 번호입니다.

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


밝기 값을 가져오거나 설정합니다.

값: 밝기 값입니다.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


CFA 패턴을 가져오거나 설정합니다.

값: CFA 패턴입니다.

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


카메라 소유자 이름을 가져오거나 설정합니다

값: 카메라 소유자 이름입니다.

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


색 공간을 가져오거나 설정합니다.

값: 색 공간입니다.

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


공통 섹션에 속하는 태그를 가져오거나 설정합니다. 이는 JPEG 이미지에만 적용되며, TIFF 형식에서는 대신 tiffOptions가 사용됩니다.

값: 공통 섹션 태그입니다.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


구성 요소 구성을 가져오거나 설정합니다.

값: 구성 요소 구성입니다.

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


픽셀당 압축 비트를 가져오거나 설정합니다.

값: 픽셀당 압축 비트 수입니다.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getContrast() {#getContrast--}
```
public int getContrast()
```


대비를 가져오거나 설정합니다.

값: 대비입니다.

**Returns:**
int
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


사용자 정의 렌더링을 가져오거나 설정합니다.

값: 사용자 정의 렌더링입니다.

**Returns:**
int
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


디지털화된 날짜 및 시간을 가져오거나 설정합니다.

값: 디지털화된 날짜 및 시간입니다.

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


원본 날짜 및 시간을 가져오거나 설정합니다.

값: 원본 날짜 및 시간입니다.

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


장치 설정 설명을 가져오거나 설정합니다

값: 장치 설정 설명입니다.

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


디지털 줌 비율을 가져오거나 설정합니다.

값: 디지털 줌 비율입니다.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


EXIF 섹션에만 해당하는 태그를 가져오거나 설정합니다.

값: EXIF 섹션 태그입니다.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


EXIF 버전을 가져오거나 설정합니다.

값: EXIF 버전입니다.

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


노출 보정 값을 가져오거나 설정합니다.

값: 노출 보정 값입니다.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


노출 지수를 가져오거나 설정합니다.

값: 노출의 인덱스.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


노출 모드를 가져오거나 설정합니다.

값: 노출 모드.

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


노출 프로그램을 가져오거나 설정합니다.

값: 노출 프로그램.

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


노출 시간을 가져오거나 설정합니다.

값: 노출 시간.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


F-넘버를 가져오거나 설정합니다.

값: F-number.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


파일 소스 유형을 가져오거나 설정합니다.

값: 파일 소스 유형.

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


플래시를 가져오거나 설정합니다.

값: 플래시.

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


플래시 에너지를 가져오거나 설정합니다.

값: 플래시 에너지.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


플래시 픽스 버전을 가져오거나 설정합니다.

값: 플래시 픽스 버전.

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


초점 거리를 가져오거나 설정합니다.

값: 초점 거리 길이.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


35mm 필름 기준 초점 거리를 가져오거나 설정합니다.

값: 35 mm 필름 기준 초점 거리.

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


초점면 해상도 단위를 가져오거나 설정합니다.

값: 초점면 해상도 단위.

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


초점면 X 해상도를 가져오거나 설정합니다.

값: 초점면 X 해상도.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


초점면 Y 해상도를 가져오거나 설정합니다.

값: 초점면 Y 해상도.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


GPS 고도를 가져오거나 설정합니다.

값: GPS 고도.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


참조 고도로 사용되는 GPS 고도를 가져오거나 설정합니다.

값: 기준 고도로 사용되는 GPS 고도.

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


GPS 영역 정보를 가져오거나 설정합니다.

값: GPS 영역 정보.

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


GPS DOP(정밀도 데이터)를 가져오거나 설정합니다.

값: GPS DOP(정밀도 데이터 정도).

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


UTC(협정 세계시)와 관련된 날짜 및 시간 정보를 기록하는 GPS 문자열을 가져오거나 설정합니다.

값: UTC(협정 세계시) 기준 GPS 문자 문자열 기록 날짜 및 시간 정보.

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


목적지에 대한 GPS 방위를 가져오거나 설정합니다.

값: 목적지까지의 GPS 방위.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


목적지에 대한 방위를 제공하는 데 사용되는 GPS 기준을 가져오거나 설정합니다.

값: 목적지 방위를 제공하는 데 사용되는 GPS 기준.

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


목적지까지의 GPS 거리를 가져오거나 설정합니다.

값: 목적지까지의 GPS 거리.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


목적지까지의 거리를 표현하는 데 사용되는 GPS 단위를 가져오거나 설정합니다.

값: 목적지 거리 표현에 사용되는 GPS 단위.

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


목적지의 GPS 위도를 가져오거나 설정합니다.

값: 목적지의 GPS 위도.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


목적지 위도가 북위인지 남위인지를 나타내는 GPS 값을 가져오거나 설정합니다.

값: 목적지 점의 위도가 북위인지 남위인지를 나타내는 GPS 값.

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


목적지의 GPS 경도를 가져오거나 설정합니다.

값: 목적지 점의 GPS 경도.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


목적지 경도가 동경인지 서경인지를 나타내는 GPS 값을 가져오거나 설정합니다.

값: 목적지 점의 경도가 동경인지 서경인지를 나타내는 GPS 값.

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


GPS 수신기에 차동 보정이 적용되는지를 나타내는 GPS 값을 가져오거나 설정합니다.

값: GPS 수신기에 차동 보정이 적용되는지를 나타내는 GPS 값.

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


이미지가 촬영될 때의 GPS 방향을 가져오거나 설정합니다.

값: 이미지가 촬영될 때의 GPS 방향.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


이미지가 촬영될 때 방향을 제공하는 GPS 기준을 가져오거나 설정합니다.

값: 이미지가 촬영될 때 방향을 제공하는 GPS 기준.

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


GPS 위도를 가져오거나 설정합니다.

값: GPS 위도.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


GPS 위도가 북위인지 남위인지를 가져오거나 설정합니다.

값: GPS 위도가 북위인지 남위인지.

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


GPS 경도를 가져오거나 설정합니다.

값: GPS 경도.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


GPS 경도가 동경인지 서경인지를 가져오거나 설정합니다.

값: GPS 경도가 동경인지 서경인지.

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


GPS 수신기에 사용되는 GPS 측지 조사 데이터를 가져오거나 설정합니다.

값: GPS 수신기에 사용되는 GPS 측지 조사 데이터.

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


GPS 측정 모드를 가져오거나 설정합니다.

값: GPS 측정 모드.

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


위치 찾기에 사용된 방법의 이름을 기록하는 GPS 문자열을 가져오거나 설정합니다.

값: 위치 찾기에 사용된 방법 이름을 기록하는 GPS 문자열.

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


측정에 사용되는 GPS 위성을 가져오거나 설정합니다.

값: 측정에 사용되는 GPS 위성.

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


GPS 수신기 이동 속도를 가져오거나 설정합니다.

값: GPS 수신기 이동 속도.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


GPS 수신기 이동 속도를 표현하는 데 사용되는 단위를 가져오거나 설정합니다.

값: GPS 수신기 이동 속도를 표현하는 단위.

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


이미지가 기록될 때 GPS 수신기의 상태를 가져오거나 설정합니다.

값: 이미지가 기록될 때 GPS 수신기의 상태.

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


GPS 섹션에만 해당하는 태그를 가져오거나 설정합니다.

값: GPS 태그.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


UTC(협정 세계시)로 표시된 GPS 시간을 가져오거나 설정합니다.

값: UTC(협정 세계시) 기준 GPS 시간.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


GPS 수신기 움직임의 방향을 가져오거나 설정합니다.

값: GPS 수신기 이동 방향.

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


GPS 수신기 움직임의 방향을 제공하기 위한 기준을 가져오거나 설정합니다.

값: GPS 수신기 이동 방향을 제공하는 기준.

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


GPS 버전 식별자를 가져오거나 설정합니다.

값: GPS 버전 식별자.

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


전체 이미지 이득 조정 정도를 가져오거나 설정합니다.

값: 전체 이미지 이득 조정 정도.

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


감마 값을 가져오거나 설정합니다.

값: 감마 값.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


ISO 속도를 가져오거나 설정합니다.

값: ISO 속도.

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 yyy 값을 가져오거나 설정합니다.

값: ISO 12232에 정의된 카메라 또는 입력 장치의 ISO speed latitude yyy 값.

이 태그는 ISOSpeed 및 ISOSpeedLatitudezzz 없이 기록해서는 안 됩니다.

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 zzz 값을 가져오거나 설정합니다.

값: ISO 12232에 정의된 카메라 또는 입력 장치의 ISO speed latitude zzz 값.

이 태그는 ISOSpeed 및 ISOSpeedLatitudeyyy 없이 기록해서는 안 됩니다.

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


이미지 고유 식별자를 가져오거나 설정합니다.

값: 이미지 고유 식별자.

**Returns:**
java.lang.String
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


렌즈 제조사를 가져오거나 설정합니다.

값: 렌즈 제조사.

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


렌즈 모델을 가져오거나 설정합니다.

값: 렌즈 모델.

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


렌즈 일련 번호를 가져오거나 설정합니다.

값: 렌즈 일련 번호.

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


렌즈 사양을 가져오거나 설정합니다.

값: 렌즈 사양.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


광원을 가져오거나 설정합니다.

값: 광원.

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


녹음 장비의 제조사를 가져옵니다.

값: 녹음 장비 제조사.

**Returns:**
java.lang.String - 녹음 장비 제조사.
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


제조사 메모 데이터를 가져옵니다.

값: 메이커 노트 데이터.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


제조사 메모 원시 데이터를 가져오거나 설정합니다.

값: 메이커 노트 원시 데이터.

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


제조사 메모를 가져옵니다.

값: 메이커 노트.

**Returns:**
com.aspose.psd.exif.MakerNote[] - 메이커 노트.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


최대 조리개 값을 가져오거나 설정합니다.

값: 최대 조리개 값.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


측광 모드를 가져오거나 설정합니다.

값: 측광 모드.

**Returns:**
int
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


ISO 14524에 지정된 광전 변환 함수 (OECF)를 가져오거나 설정합니다.

값: ISO 14524에 지정된 광전 변환 함수 (OECF).

**Returns:**
byte[]
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


사진 감도를 가져오거나 설정합니다.

값: 사진 감도.

**Returns:**
long
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


픽셀 x 차원을 가져오거나 설정합니다.

값: 픽셀 x 차원.

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


픽셀 y 차원을 가져오거나 설정합니다.

값: 픽셀 y 차원.

**Returns:**
long
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


공통 및 GPS 태그를 포함한 모든 EXIF 태그를 가져오거나 설정합니다.

값: EXIF 태그(공통 및 GPS 태그 포함).

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


권장 노출 지수를 가져오거나 설정합니다.

값: 권장 노출 지수.

**Returns:**
long
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


관련 사운드 파일을 가져오거나 설정합니다.

값: 관련 사운드 파일.

**Returns:**
java.lang.String
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


채도를 가져오거나 설정합니다.

값: 채도.

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


장면 캡처 유형을 가져오거나 설정합니다.

값: 장면 캡처 유형.

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


장면 유형을 가져오거나 설정합니다.

값: 장면 유형.

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


감지 방법을 가져오거나 설정합니다.

값: 감지 방법.

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


감도 유형을 가져오거나 설정합니다.

값: 감도 유형.

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


선명도를 가져오거나 설정합니다.

값: 선명도.

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


셔터 속도 값을 가져오거나 설정합니다.

값: 셔터 속도 값.

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


공간 주파수 응답을 가져오거나 설정합니다.

값: 공간 주파수 응답.

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


스펙트럼 감도를 가져오거나 설정합니다.

값: 스펙트럼 감도.

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


표준 출력 감도를 가져옵니다

값: 표준 출력 감도.

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


주제 영역을 가져오거나 설정합니다.

값: 피사체 영역.

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


주제 거리를 가져오거나 설정합니다.

값: 피사체 거리.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


주제 거리 범위를 가져오거나 설정합니다.

값: 피사체 거리 범위.

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


주제 위치를 가져오거나 설정합니다.

값: 피사체 위치.

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


DateTime 태그의 초 분수를 가져오거나 설정합니다.

값: DateTime 태그의 초 분수.

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


DateTimeDigitized 태그의 초 분수를 가져오거나 설정합니다.

값: DateTimeDigitized 태그의 초 분수.

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


DateTimeOriginal 태그의 초 분수를 가져오거나 설정합니다.

값: DateTimeOriginal 태그의 초 분수.

**Returns:**
java.lang.String
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


사용자 주석을 가져오거나 설정합니다.

값: 사용자 댓글.

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


화이트 밸런스를 가져오거나 설정합니다.

값: 화이트 밸런스.

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


이미지의 화이트 포인트 색도를 가져오거나 설정합니다.

값: 이미지 화이트 포인트의 색도.

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


스트림 EXIF 데이터가 빅 엔디안으로 생성되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  스트림 EXIF 데이터가 빅 엔디안인 경우; 그렇지 않으면  false .

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


컨테이너에서 태그를 제거합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tagId | int | 제거할 태그 식별자. |

### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


조리개 값을 가져오거나 설정합니다.

값: 조리개 값입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


스트림 EXIF 데이터가 빅 엔디안으로 생성되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  스트림 EXIF 데이터가 빅 엔디안인 경우; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


카메라 본체 일련 번호를 가져오거나 설정합니다.

값: 본체 일련 번호입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


밝기 값을 가져오거나 설정합니다.

값: 밝기 값입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


CFA 패턴을 가져오거나 설정합니다.

값: CFA 패턴입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


카메라 소유자 이름을 가져오거나 설정합니다

값: 카메라 소유자 이름입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


색 공간을 가져오거나 설정합니다.

값: 색 공간입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


공통 섹션에 속하는 태그를 가져오거나 설정합니다. 이는 JPEG 이미지에만 적용되며, TIFF 형식에서는 대신 tiffOptions가 사용됩니다.

값: 공통 섹션 태그입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


구성 요소 구성을 가져오거나 설정합니다.

값: 구성 요소 구성입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


픽셀당 압축 비트를 가져오거나 설정합니다.

값: 픽셀당 압축 비트 수입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


대비를 가져오거나 설정합니다.

값: 대비입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


사용자 정의 렌더링을 가져오거나 설정합니다.

값: 사용자 정의 렌더링입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


디지털화된 날짜 및 시간을 가져오거나 설정합니다.

값: 디지털화된 날짜 및 시간입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


원본 날짜 및 시간을 가져오거나 설정합니다.

값: 원본 날짜 및 시간입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


장치 설정 설명을 가져오거나 설정합니다

값: 장치 설정 설명입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


디지털 줌 비율을 가져오거나 설정합니다.

값: 디지털 줌 비율입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


EXIF 섹션에만 해당하는 태그를 가져오거나 설정합니다.

값: EXIF 섹션 태그입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


EXIF 버전을 가져오거나 설정합니다.

값: EXIF 버전입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


노출 보정 값을 가져오거나 설정합니다.

값: 노출 보정 값입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


노출 지수를 가져오거나 설정합니다.

값: 노출의 인덱스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


노출 모드를 가져오거나 설정합니다.

값: 노출 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


노출 프로그램을 가져오거나 설정합니다.

값: 노출 프로그램.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


노출 시간을 가져오거나 설정합니다.

값: 노출 시간.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


F-넘버를 가져오거나 설정합니다.

값: F-number.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


파일 소스 유형을 가져오거나 설정합니다.

값: 파일 소스 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


플래시를 가져오거나 설정합니다.

값: 플래시.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


플래시 에너지를 가져오거나 설정합니다.

값: 플래시 에너지.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


플래시 픽스 버전을 가져오거나 설정합니다.

값: 플래시 픽스 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


초점 거리를 가져오거나 설정합니다.

값: 초점 거리 길이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


35mm 필름 기준 초점 거리를 가져오거나 설정합니다.

값: 35 mm 필름 기준 초점 거리.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


초점면 해상도 단위를 가져오거나 설정합니다.

값: 초점면 해상도 단위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


초점면 X 해상도를 가져오거나 설정합니다.

값: 초점면 X 해상도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


초점면 Y 해상도를 가져오거나 설정합니다.

값: 초점면 Y 해상도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


GPS 고도를 가져오거나 설정합니다.

값: GPS 고도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


참조 고도로 사용되는 GPS 고도를 가져오거나 설정합니다.

값: 기준 고도로 사용되는 GPS 고도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


GPS 영역 정보를 가져오거나 설정합니다.

값: GPS 영역 정보.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


GPS DOP(정밀도 데이터)를 가져오거나 설정합니다.

값: GPS DOP(정밀도 데이터 정도).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


UTC(협정 세계시)와 관련된 날짜 및 시간 정보를 기록하는 GPS 문자열을 가져오거나 설정합니다.

값: UTC(협정 세계시) 기준 GPS 문자 문자열 기록 날짜 및 시간 정보.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


목적지에 대한 GPS 방위를 가져오거나 설정합니다.

값: 목적지까지의 GPS 방위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


목적지에 대한 방위를 제공하는 데 사용되는 GPS 기준을 가져오거나 설정합니다.

값: 목적지 방위를 제공하는 데 사용되는 GPS 기준.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


목적지까지의 GPS 거리를 가져오거나 설정합니다.

값: 목적지까지의 GPS 거리.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


목적지까지의 거리를 표현하는 데 사용되는 GPS 단위를 가져오거나 설정합니다.

값: 목적지 거리 표현에 사용되는 GPS 단위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


목적지의 GPS 위도를 가져오거나 설정합니다.

값: 목적지의 GPS 위도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


목적지 위도가 북위인지 남위인지를 나타내는 GPS 값을 가져오거나 설정합니다.

값: 목적지 점의 위도가 북위인지 남위인지를 나타내는 GPS 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


목적지의 GPS 경도를 가져오거나 설정합니다.

값: 목적지 점의 GPS 경도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


목적지 경도가 동경인지 서경인지를 나타내는 GPS 값을 가져오거나 설정합니다.

값: 목적지 점의 경도가 동경인지 서경인지를 나타내는 GPS 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


GPS 수신기에 차동 보정이 적용되는지를 나타내는 GPS 값을 가져오거나 설정합니다.

값: GPS 수신기에 차동 보정이 적용되는지를 나타내는 GPS 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


이미지가 촬영될 때의 GPS 방향을 가져오거나 설정합니다.

값: 이미지가 촬영될 때의 GPS 방향.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


이미지가 촬영될 때 방향을 제공하는 GPS 기준을 가져오거나 설정합니다.

값: 이미지가 촬영될 때 방향을 제공하는 GPS 기준.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


GPS 위도를 가져오거나 설정합니다.

값: GPS 위도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


GPS 위도가 북위인지 남위인지를 가져오거나 설정합니다.

값: GPS 위도가 북위인지 남위인지.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


GPS 경도를 가져오거나 설정합니다.

값: GPS 경도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


GPS 경도가 동경인지 서경인지를 가져오거나 설정합니다.

값: GPS 경도가 동경인지 서경인지.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


GPS 수신기에 사용되는 GPS 측지 조사 데이터를 가져오거나 설정합니다.

값: GPS 수신기에 사용되는 GPS 측지 조사 데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


GPS 측정 모드를 가져오거나 설정합니다.

값: GPS 측정 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


위치 찾기에 사용된 방법의 이름을 기록하는 GPS 문자열을 가져오거나 설정합니다.

값: 위치 찾기에 사용된 방법 이름을 기록하는 GPS 문자열.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


측정에 사용되는 GPS 위성을 가져오거나 설정합니다.

값: 측정에 사용되는 GPS 위성.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


GPS 수신기 이동 속도를 가져오거나 설정합니다.

값: GPS 수신기 이동 속도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


GPS 수신기 이동 속도를 표현하는 데 사용되는 단위를 가져오거나 설정합니다.

값: GPS 수신기 이동 속도를 표현하는 단위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


이미지가 기록될 때 GPS 수신기의 상태를 가져오거나 설정합니다.

값: 이미지가 기록될 때 GPS 수신기의 상태.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


GPS 섹션에만 해당하는 태그를 가져오거나 설정합니다.

값: GPS 태그.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


UTC(협정 세계시)로 표시된 GPS 시간을 가져오거나 설정합니다.

값: UTC(협정 세계시) 기준 GPS 시간.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


GPS 수신기 움직임의 방향을 가져오거나 설정합니다.

값: GPS 수신기 이동 방향.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


GPS 수신기 움직임의 방향을 제공하기 위한 기준을 가져오거나 설정합니다.

값: GPS 수신기 이동 방향을 제공하는 기준.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


GPS 버전 식별자를 가져오거나 설정합니다.

값: GPS 버전 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


전체 이미지 이득 조정 정도를 가져오거나 설정합니다.

값: 전체 이미지 이득 조정 정도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


감마 값을 가져오거나 설정합니다.

값: 감마 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


ISO 속도를 가져오거나 설정합니다.

값: ISO 속도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 yyy 값을 가져오거나 설정합니다.

값: ISO 12232에 정의된 카메라 또는 입력 장치의 ISO speed latitude yyy 값.

이 태그는 ISOSpeed 및 ISOSpeedLatitudezzz 없이 기록해서는 안 됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


ISO 12232에서 정의된 카메라 또는 입력 장치의 ISO 속도 위도 zzz 값을 가져오거나 설정합니다.

값: ISO 12232에 정의된 카메라 또는 입력 장치의 ISO speed latitude zzz 값.

이 태그는 ISOSpeed 및 ISOSpeedLatitudeyyy 없이 기록해서는 안 됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


이미지 고유 식별자를 가져오거나 설정합니다.

값: 이미지 고유 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


렌즈 제조사를 가져오거나 설정합니다.

값: 렌즈 제조사.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


렌즈 모델을 가져오거나 설정합니다.

값: 렌즈 모델.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


렌즈 일련 번호를 가져오거나 설정합니다.

값: 렌즈 일련 번호.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


렌즈 사양을 가져오거나 설정합니다.

값: 렌즈 사양.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


광원을 가져오거나 설정합니다.

값: 광원.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


녹음 장비의 제조업체를 설정합니다.

값: 녹음 장비 제조사.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 녹음 장비의 제조사. |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


제조사 메모 원시 데이터를 가져오거나 설정합니다.

값: 메이커 노트 원시 데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


최대 조리개 값을 가져오거나 설정합니다.

값: 최대 조리개 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


측광 모드를 가져오거나 설정합니다.

값: 측광 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


ISO 14524에 지정된 광전 변환 함수 (OECF)를 가져오거나 설정합니다.

값: ISO 14524에 지정된 광전 변환 함수 (OECF).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


사진 감도를 가져오거나 설정합니다.

값: 사진 감도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


픽셀 x 차원을 가져오거나 설정합니다.

값: 픽셀 x 차원.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


픽셀 y 차원을 가져오거나 설정합니다.

값: 픽셀 y 차원.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


공통 및 GPS 태그를 포함한 모든 EXIF 태그를 가져오거나 설정합니다.

값: EXIF 태그(공통 및 GPS 태그 포함).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


권장 노출 지수를 가져오거나 설정합니다.

값: 권장 노출 지수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


관련 사운드 파일을 가져오거나 설정합니다.

값: 관련 사운드 파일.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


채도를 가져오거나 설정합니다.

값: 채도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


장면 캡처 유형을 가져오거나 설정합니다.

값: 장면 캡처 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


장면 유형을 가져오거나 설정합니다.

값: 장면 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


감지 방법을 가져오거나 설정합니다.

값: 감지 방법.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


감도 유형을 가져오거나 설정합니다.

값: 감도 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


선명도를 가져오거나 설정합니다.

값: 선명도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


셔터 속도 값을 가져오거나 설정합니다.

값: 셔터 속도 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


공간 주파수 응답을 가져오거나 설정합니다.

값: 공간 주파수 응답.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


스펙트럼 감도를 가져오거나 설정합니다.

값: 스펙트럼 감도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


표준 출력 감도를 설정합니다

값: 표준 출력 감도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


주제 영역을 가져오거나 설정합니다.

값: 피사체 영역.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


주제 거리를 가져오거나 설정합니다.

값: 피사체 거리.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


주제 거리 범위를 가져오거나 설정합니다.

값: 피사체 거리 범위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


주제 위치를 가져오거나 설정합니다.

값: 피사체 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


DateTime 태그의 초 분수를 가져오거나 설정합니다.

값: DateTime 태그의 초 분수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


DateTimeDigitized 태그의 초 분수를 가져오거나 설정합니다.

값: DateTimeDigitized 태그의 초 분수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


DateTimeOriginal 태그의 초 분수를 가져오거나 설정합니다.

값: DateTimeOriginal 태그의 초 분수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


사용자 주석을 가져오거나 설정합니다.

값: 사용자 댓글.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


화이트 밸런스를 가져오거나 설정합니다.

값: 화이트 밸런스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


이미지의 화이트 포인트 색도를 가져오거나 설정합니다.

값: 이미지 화이트 포인트의 색도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

