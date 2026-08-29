---
title: "ExifProperties"
second_title: "Java용 Aspose.PSD API 참조"
description: "Exif 태그 목록"
type: docs
weight: 11
url: /ko/java/com.aspose.psd.exif/exifproperties/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif 태그 목록
## 필드

| 필드 | 설명 |
| --- | --- |
| [ApertureValue](#ApertureValue) | 렌즈 조리개 값. |
| [Artist](#Artist) | 이 태그는 카메라 소유자, 사진작가 또는 이미지 제작자의 이름을 기록합니다. |
| [BitsPerSample](#BitsPerSample) | 이미지 구성 요소당 비트 수. |
| [BodySerialNumber](#BodySerialNumber) | 카메라 본체 일련 번호를 포함합니다. |
| [BrightnessValue](#BrightnessValue) | 밝기 값. |
| [CFAPattern](#CFAPattern) | 단일 칩 컬러 영역 센서를 사용할 때 이미지 센서의 색상 필터 배열(CFA) 기하학적 패턴을 나타냅니다. |
| [CameraOwnerName](#CameraOwnerName) | 카메라 소유자 이름을 포함합니다 |
| [ColorSpace](#ColorSpace) | 색 공간 정보 태그(ColorSpace)는 항상 색 공간 지정자로 기록됩니다. |
| [ComponentsConfiguration](#ComponentsConfiguration) | 구성 요소 구성입니다. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | 압축 데이터에 특화된; 픽셀당 압축 비트를 나타냅니다. |
| [Compression](#Compression) | 이미지 데이터에 사용되는 압축 방식입니다. |
| [Contrast](#Contrast) | 이 태그는 이미지 촬영 시 카메라가 적용한 대비 처리 방향을 나타냅니다. |
| [Copyright](#Copyright) | 저작권 정보입니다. |
| [CustomRendered](#CustomRendered) | 이 태그는 출력에 맞춘 렌더링과 같은 이미지 데이터에 대한 특수 처리 사용을 나타냅니다. |
| [DateTime](#DateTime) | 이미지 생성 날짜와 시간입니다. |
| [DateTimeDigitized](#DateTimeDigitized) | 디지털화된 날짜와 시간입니다. |
| [DateTimeOriginal](#DateTimeOriginal) | 원본 이미지 데이터가 생성된 날짜와 시간입니다. |
| [DeviceSettingDescription](#DeviceSettingDescription) | 이 태그는 특정 카메라 모델의 촬영 조건에 대한 정보를 나타냅니다. |
| [DigitalZoomRatio](#DigitalZoomRatio) | 이 태그는 이미지 촬영 시 디지털 줌 비율을 나타냅니다. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | Exif IFD에 대한 포인터입니다. |
| [ExifVersion](#ExifVersion) | Exif 버전입니다. |
| [ExposureBiasValue](#ExposureBiasValue) | 노출 보정 값입니다. |
| [ExposureIndex](#ExposureIndex) | 이미지 촬영 시 카메라 또는 입력 장치에서 선택된 노출 지수를 나타냅니다. |
| [ExposureMode](#ExposureMode) | 이 태그는 이미지 촬영 시 설정된 노출 모드를 나타냅니다. |
| [ExposureProgram](#ExposureProgram) | 사진 촬영 시 카메라가 노출을 설정하는 데 사용한 프로그램의 클래스입니다. |
| [ExposureTime](#ExposureTime) | 노출 시간(초 단위)입니다. |
| [FNumber](#FNumber) | F값입니다. |
| [FileSource](#FileSource) | 파일 소스입니다. |
| [Flash](#Flash) | 이미지 촬영 시 플래시 상태를 나타냅니다. |
| [FlashEnergy](#FlashEnergy) | 이미지 촬영 시 스토브 에너지를 Beam Candle Power Seconds(BCPS) 단위로 측정한 값을 나타냅니다. |
| [FlashpixVersion](#FlashpixVersion) | FPXR 파일이 지원하는 Flashpix 포맷 버전입니다. |
| [FocalLength](#FocalLength) | 렌즈의 실제 초점 거리(mm)입니다. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | 이 태그는 35mm 필름 카메라를 가정한 등가 초점 거리(mm)를 나타냅니다. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | FocalPlaneXResolution 및 FocalPlaneYResolution 측정 단위를 나타냅니다. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | 카메라 초점면의 FocalPlaneResolutionUnit당 이미지 너비(X) 방향 픽셀 수를 나타냅니다. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | 카메라 초점면의 FocalPlaneResolutionUnit당 이미지 높이(Y) 방향 픽셀 수를 나타냅니다. |
| [GPSAltitude](#GPSAltitude) | GPSAltitudeRef 기준에 따른 고도를 나타냅니다. |
| [GPSAltitudeRef](#GPSAltitudeRef) | 참조 고도로 사용되는 고도를 나타냅니다. |
| [GPSAreaInformation](#GPSAreaInformation) | GPS 영역 이름을 기록하는 문자열입니다. |
| [GPSDOP](#GPSDOP) | GPS DOP(데이터 정밀도)를 나타냅니다. |
| [GPSDateStamp](#GPSDateStamp) | UTC(협정 세계시) 기준 날짜 및 시간 정보를 기록하는 문자열입니다. |
| [GPSDestBearing](#GPSDestBearing) | 목적지까지의 방위를 나타냅니다. |
| [GPSDestBearingRef](#GPSDestBearingRef) | 목적지까지의 방위를 제공하는 데 사용되는 기준을 나타냅니다. |
| [GPSDestDistance](#GPSDestDistance) | 목적지까지의 거리를 나타냅니다. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | 목적지까지의 거리를 표현하는 단위를 나타냅니다. |
| [GPSDestLatitude](#GPSDestLatitude) | 목적지의 위도를 나타냅니다. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | 목적지 위도가 북위인지 남위인지 나타냅니다. |
| [GPSDestLongitude](#GPSDestLongitude) | 목적지의 경도를 나타냅니다. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | 목적지 경도가 동경인지 서경인지 나타냅니다. |
| [GPSDifferential](#GPSDifferential) | GPS 수신기에 차동 보정이 적용되는지 여부를 나타냅니다. |
| [GPSIfdPointer](#GPSIfdPointer) | GPS IFD 포인터입니다. |
| [GPSImgDirection](#GPSImgDirection) | 이미지가 촬영될 때의 방향을 나타냅니다. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | 촬영 시 이미지 방향을 제공하는 기준을 나타냅니다. |
| [GPSLatitude](#GPSLatitude) | 위도를 나타냅니다. |
| [GPSLatitudeRef](#GPSLatitudeRef) | 위도가 북위인지 남위인지 나타냅니다. |
| [GPSLongitude](#GPSLongitude) | 경도를 나타냅니다. |
| [GPSLongitudeRef](#GPSLongitudeRef) | 경도가 동경인지 서경인지를 나타냅니다. |
| [GPSMapDatum](#GPSMapDatum) | GPS 수신기가 사용하는 측지 조사 데이터를 나타냅니다. |
| [GPSMeasureMode](#GPSMeasureMode) | GPS 측정 모드를 나타냅니다. |
| [GPSProcessingMethod](#GPSProcessingMethod) | 위치 찾기에 사용된 방법의 이름을 기록하는 문자열입니다. |
| [GPSSatellites](#GPSSatellites) | 측정에 사용되는 GPS 위성을 나타냅니다. |
| [GPSSpeed](#GPSSpeed) | GPS 수신기 이동 속도를 나타냅니다. |
| [GPSSpeedRef](#GPSSpeedRef) | GPS 수신기 이동 속도를 표현하는 단위를 나타냅니다. |
| [GPSStatus](#GPSStatus) | 이미지가 기록될 때 GPS 수신기의 상태를 나타냅니다. |
| [GPSTimestamp](#GPSTimestamp) | 시간을 UTC(협정 세계시)로 나타냅니다. |
| [GPSTrack](#GPSTrack) | GPS 수신기 이동 방향을 나타냅니다. |
| [GPSTrackRef](#GPSTrackRef) | GPS 수신기 이동 방향을 제공하는 기준을 나타냅니다. |
| [GPSVersionID](#GPSVersionID) | GPSInfoIFD의 버전을 나타냅니다. |
| [GainControl](#GainControl) | 이 태그는 전체 이미지 이득 조정 정도를 나타냅니다. |
| [Gamma](#Gamma) | 감마 값 |
| [ISOSpeed](#ISOSpeed) | ISO 12232에 정의된 ISO 속도 값에 대한 정보 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | 이 태그는 ISO 12232에 정의된 ISO 속도 위도 yyy 값을 나타냅니다. |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | 이 태그는 ISO 12232에 정의된 ISO 속도 위도 zzz 값을 나타냅니다. |
| [ImageDescription](#ImageDescription) | 이미지의 제목을 제공하는 문자열입니다. |
| [ImageLength](#ImageLength) | 이미지 데이터의 행 수입니다. |
| [ImageUniqueID](#ImageUniqueID) | 이미지 고유 ID입니다. |
| [ImageWidth](#ImageWidth) | 이미지 데이터의 열 수이며, 행당 픽셀 수와 같습니다. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | JPEG 압축 썸네일 데이터의 시작 바이트(SOI)까지의 오프셋입니다. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | JPEG 압축 썸네일 데이터의 바이트 수입니다. |
| [LensMake](#LensMake) | 이 태그는 렌즈 제조사를 기록합니다. |
| [LensModel](#LensModel) | 이 태그는 렌즈 모델 이름과 모델 번호를 기록합니다. |
| [LensSerialNumber](#LensSerialNumber) | 이 태그는 교환 가능한 렌즈의 일련 번호를 기록합니다. |
| [LensSpecification](#LensSpecification) | 이 태그는 최소 초점 거리, 최대 초점 거리, 최소 초점 거리에서의 최소 F값 및 최대 초점 거리에서의 최소 F값을 기록합니다. |
| [LightSource](#LightSource) | 광원의 종류. |
| [Make](#Make) | 녹화 장비의 제조업체. |
| [MakerNote](#MakerNote) | Exif 작성자의 제조업체가 원하는 정보를 기록하기 위한 태그. |
| [MaxApertureValue](#MaxApertureValue) | 최대 조리개 값. |
| [MeteringMode](#MeteringMode) | 측광 모드. |
| [Model](#Model) | 장비의 모델 이름 또는 모델 번호. |
| [OECF](#OECF) | ISO 14524에 지정된 광전 변환 기능(OECF)을 나타냅니다. |
| [Orientation](#Orientation) | 행과 열을 기준으로 본 이미지 방향. |
| [PhotographicSensitivity](#PhotographicSensitivity) | ISO 12232에 지정된 카메라 또는 입력 장치의 ISO 속도와 ISO 위도를 나타냅니다. |
| [PhotometricInterpretation](#PhotometricInterpretation) | 픽셀 구성. |
| [PixelXDimension](#PixelXDimension) | 압축 데이터에 대한 특정 정보. |
| [PixelYDimension](#PixelYDimension) | 압축 데이터에 대한 특정 정보. |
| [PlanarConfiguration](#PlanarConfiguration) | 픽셀 구성 요소가 청키 형식인지 플래너 형식인지 여부를 나타냅니다. |
| [PrimaryChromaticities](#PrimaryChromaticities) | 이미지의 세 기본 색상의 색도. |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | 권장 노출 지수를 나타냅니다. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | 참조 검은색 점값 및 참조 흰색 점값. |
| [RelatedSoundFile](#RelatedSoundFile) | 관련 사운드 파일. |
| [ResolutionUnit](#ResolutionUnit) | XResolution 및 YResolution을 측정하는 단위. |
| [RowsPerStrip](#RowsPerStrip) | 스트립당 행 수. |
| [SamplesPerPixel](#SamplesPerPixel) | 픽셀당 구성 요소 수. |
| [Saturation](#Saturation) | 이 태그는 촬영 시 카메라가 적용한 채도 처리 방향을 나타냅니다. |
| [SceneCaptureType](#SceneCaptureType) | 이 태그는 촬영된 장면의 유형을 나타냅니다. |
| [SceneType](#SceneType) | 장면 유형을 나타냅니다. |
| [SensingMethod](#SensingMethod) | 카메라 또는 입력 장치의 이미지 센서 유형을 나타냅니다. |
| [SensitivityType](#SensitivityType) | 사진 감도 유형 |
| [Sharpness](#Sharpness) | 이 태그는 이미지가 촬영될 때 카메라에 의해 적용된 선명도 처리 방향을 나타냅니다 |
| [ShutterSpeedValue](#ShutterSpeedValue) | 셔터 속도 값입니다. |
| [Software](#Software) | 이 태그는 이미지를 생성하는 데 사용된 카메라 또는 이미지 입력 장치의 소프트웨어 또는 펌웨어 이름과 버전을 기록합니다. |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | 이 태그는 ISO 12233에 명시된 대로 이미지 너비, 이미지 높이 및 대각선 방향의 공간 주파수 표와 SFR 값을 카메라 또는 입력 장치에 대해 기록합니다. |
| [SpectralSensitivity](#SpectralSensitivity) | 사용된 카메라 각 채널의 스펙트럼 감도를 나타냅니다. |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | 카메라의 표준 출력 감도를 나타냅니다 |
| [StripByteCounts](#StripByteCounts) | 각 스트립의 총 바이트 수입니다. |
| [StripOffsets](#StripOffsets) | 각 스트립에 대해 해당 스트립의 바이트 오프셋입니다. |
| [SubjectArea](#SubjectArea) | 이 태그는 전체 장면에서 주요 피사체의 위치와 영역을 나타냅니다. |
| [SubjectDistance](#SubjectDistance) | 피사체까지의 거리이며, 미터 단위입니다. |
| [SubjectDistanceRange](#SubjectDistanceRange) | 이 태그는 피사체까지의 거리를 나타냅니다. |
| [SubjectLocation](#SubjectLocation) | 장면에서 주요 피사체의 위치를 나타냅니다. |
| [SubsecTime](#SubsecTime) | DateTime 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | DateTimeDigitized 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | DateTimeOriginal 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다. |
| [TransferFunction](#TransferFunction) | 표 형식으로 설명된 이미지의 전송 함수입니다. |
| [UserComment](#UserComment) | Exif 사용자가 ImageDescription에 있는 내용 외에 이미지에 키워드나 주석을 작성할 수 있도록 하며, ImageDescription 태그의 문자 코드 제한이 없는 태그입니다. |
| [WhiteBalance](#WhiteBalance) | 이 태그는 이미지 촬영 시 설정된 화이트 밸런스 모드를 나타냅니다. |
| [WhitePoint](#WhitePoint) | 이미지의 화이트 포인트 색도입니다. |
| [XResolution](#XResolution) | ImageWidth 방향의 ResolutionUnit당 픽셀 수입니다. |
| [YCbCrCoefficients](#YCbCrCoefficients) | RGB에서 YCbCr 이미지 데이터로 변환하기 위한 행렬 계수입니다. |
| [YCbCrPositioning](#YCbCrPositioning) | 휘도 성분에 대한 색차 성분의 위치입니다. |
| [YCbCrSubSampling](#YCbCrSubSampling) | 휘도 성분에 대한 색차 성분의 샘플링 비율입니다. |
| [YResolution](#YResolution) | ImageLength 방향의 ResolutionUnit당 픽셀 수입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames()](#getNames--) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues()](#getValues--) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [getValues(Class<?> arg0)](#getValues-java.lang.Class----) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, String arg1)](#isDefined-java.lang.Class----java.lang.String-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [toString(long arg0)](#toString-long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


렌즈 조리개 값.

### Artist {#Artist}
```
public static final int Artist
```


이 태그는 카메라 소유자, 사진작가 또는 이미지 제작자의 이름을 기록합니다. 자세한 형식은 지정되지 않았지만, 상호 운용성을 위해 아래 예시와 같이 정보를 작성하는 것이 권장됩니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. 예) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James"

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


이미지 구성 요소당 비트 수입니다. 이 표준에서는 각 이미지 구성 요소가 8비트이므로 이 태그의 값은 8입니다.

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


카메라 본체 일련 번호를 포함합니다.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


밝기 값.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


단일 칩 컬러 영역 센서를 사용할 때 이미지 센서의 컬러 필터 어레이(CFA) 기하학적 패턴을 나타냅니다. 모든 감지 방식에 적용되는 것은 아닙니다.

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


카메라 소유자 이름을 포함합니다

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


색 공간 정보 태그(ColorSpace)는 항상 색 공간 지정자로 기록됩니다.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


구성 요소 구성입니다.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


압축 데이터에 특화된; 픽셀당 압축 비트를 나타냅니다.

### Compression {#Compression}
```
public static final int Compression
```


이미지 데이터에 사용되는 압축 방식입니다. 기본 이미지가 JPEG 압축된 경우 이 지정은 필요 없으며 생략됩니다.

### Contrast {#Contrast}
```
public static final int Contrast
```


이 태그는 이미지 촬영 시 카메라가 적용한 대비 처리 방향을 나타냅니다.

### Copyright {#Copyright}
```
public static final int Copyright
```


저작권 정보입니다. 이 표준에서는 태그를 사용하여 사진작가와 편집자 저작권을 모두 표시합니다. 이는 이미지에 대한 권리를 주장하는 개인 또는 조직의 저작권 고지를 의미합니다. 날짜와 권리를 포함한 상호 운용성 저작권 문구는 이 필드에 작성해야 합니다; 예) "Copyright, John Smith, 19xx. All rights reserved.". 이 표준에서는 필드가 사진작가와 편집자 저작권을 각각 별도의 부분에 기록합니다. 사진작가와 편집자 저작권이 명확히 구분될 경우, 사진작가 뒤에 편집자 저작권을 NULL으로 구분하여 기록합니다(이 경우 문장이 NULL으로 끝나므로 NULL 코드가 두 개 있습니다). 사진작가 저작권만 제공되는 경우 하나의 NULL 코드로 종료됩니다. 편집자 저작권만 제공되는 경우, 사진작가 저작권 부분은 공백 하나와 종료 NULL 코드로 구성되고, 그 뒤에 편집자 저작권이 기록됩니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


이 태그는 이미지 데이터에 대한 특수 처리를 나타냅니다(예: 출력에 맞춘 렌더링). 특수 처리가 수행될 경우, 리더는 추가 처리를 비활성화하거나 최소화해야 합니다.

### DateTime {#DateTime}
```
public static final int DateTime
```


이미지 생성 날짜 및 시간입니다. Exif 표준에서는 파일이 변경된 날짜와 시간으로 간주합니다.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


디지털화된 날짜와 시간입니다.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


원본 이미지 데이터가 생성된 날짜와 시간입니다.

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


이 태그는 특정 카메라 모델의 촬영 조건에 대한 정보를 나타냅니다. 이 태그는 리더에서 촬영 조건을 표시하는 데만 사용됩니다.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


이 태그는 촬영 시 디지털 줌 비율을 나타냅니다. 기록된 값의 분자가 0이면 디지털 줌이 사용되지 않은 것입니다.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Exif IFD에 대한 포인터입니다. 상호 운용성, Exif IFD는 TIFF에 지정된 IFD와 동일한 구조를 가집니다. 그러나 일반적으로 TIFF와 달리 이미지 데이터를 포함하지 않습니다.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Exif 버전입니다.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


노출 보정 값입니다.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


이미지 촬영 시 카메라 또는 입력 장치에서 선택된 노출 지수를 나타냅니다.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


이 태그는 촬영 시 설정된 노출 모드를 나타냅니다. 자동 브라케팅 모드에서는 카메라가 동일한 장면을 서로 다른 노출 설정으로 연속 촬영합니다.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


사진 촬영 시 카메라가 노출을 설정하는 데 사용한 프로그램의 클래스입니다.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


노출 시간(초 단위)입니다.

### FNumber {#FNumber}
```
public static final int FNumber
```


F값입니다.

### FileSource {#FileSource}
```
public static final int FileSource
```


파일 소스입니다.

### Flash {#Flash}
```
public static final int Flash
```


이미지 촬영 시 플래시 상태를 나타냅니다.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


이미지 촬영 시 스토브 에너지를 Beam Candle Power Seconds(BCPS) 단위로 측정한 값을 나타냅니다.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


FPXR 파일이 지원하는 Flashpix 포맷 버전입니다.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


렌즈의 실제 초점 거리(mm)입니다.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


이 태그는 35mm 필름 카메라를 가정했을 때의 등가 초점 거리를 mm 단위로 나타냅니다. 값이 0이면 초점 거리를 알 수 없는 것입니다. 이 태그는 FocalLength 태그와 다릅니다.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


FocalPlaneXResolution 및 FocalPlaneYResolution을 측정하는 단위를 나타냅니다. 이 값은 ResolutionUnit과 동일합니다.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


카메라 초점면의 FocalPlaneResolutionUnit당 이미지 너비(X) 방향 픽셀 수를 나타냅니다.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


카메라 초점면의 FocalPlaneResolutionUnit당 이미지 높이(Y) 방향 픽셀 수를 나타냅니다.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


GPSAltitudeRef에 따른 고도를 나타냅니다. 고도는 하나의 RATIONAL 값으로 표현됩니다. 기준 단위는 미터입니다.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


참조 고도로 사용되는 고도를 나타냅니다. 기준이 해수면이고 고도가 해수면 위에 있으면 0이 주어집니다. 고도가 해수면 아래에 있으면 값 1이 주어지고 GPSAltitude 태그에 절대값으로 표시됩니다.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


GPS 영역 이름을 기록하는 문자열입니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며, 그 뒤에 GPS 영역 이름이 이어집니다.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


GPS DOP(데이터 정밀도)를 나타냅니다. 2차원 측정 시 HDOP 값이 기록되고, 3차원 측정 시 PDOP 값이 기록됩니다.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


UTC(협정 세계시) 기준 날짜 및 시간 정보를 기록하는 문자열입니다. 형식은 YYYY:MM:DD입니다.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


목적지까지의 방위를 나타냅니다. 값 범위는 0.00에서 359.99까지입니다.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


목적지까지의 방위를 제공할 때 사용되는 기준을 나타냅니다. 'T'는 진방향을, 'M'은 자력방향을 의미합니다.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


목적지까지의 거리를 나타냅니다.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


목적지까지의 거리를 표현하는 단위를 나타냅니다. 'K', 'M', 'N'은 각각 킬로미터, 마일, 노트를 의미합니다.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


목적지의 위도를 나타냅니다. 위도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 위도가 도·분·초 형식으로 표현될 경우 일반적인 형식은 dd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 소수점 둘째 자리까지 분의 분수로 표시할 경우 형식은 dd/1,mmmm/100,0/1이 됩니다.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


목적지 위도가 북위인지 남위인지를 나타냅니다. ASCII 값 'N'은 북위, 'S'는 남위를 의미합니다.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


목적지의 경도를 나타냅니다. 경도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 경도가 도·분·초 형식으로 표현될 경우 일반적인 형식은 ddd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 소수점 둘째 자리까지 분의 분수로 표시할 경우 형식은 ddd/1,mmmm/100,0/1이 됩니다.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


목적지 경도가 동경인지 서경인지를 나타냅니다. ASCII 'E'는 동경, 'W'는 서경을 의미합니다.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


GPS 수신기에 차동 보정이 적용되는지 여부를 나타냅니다.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


GPS IFD 포인터입니다.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


이미지가 촬영될 때의 방향을 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


이미지가 촬영될 때 방향을 제공하기 위한 기준을 나타냅니다. 'T'는 진방향을, 'M'은 자기방향을 의미합니다.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


위도를 나타냅니다. 위도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 위도가 도·분·초 형식으로 표현될 경우 일반적인 형식은 dd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 분의 소수점 둘째 자리까지 표시하는 경우 형식은 dd/1,mmmm/100,0/1이 됩니다.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


위도가 북위인지 남위인지 나타냅니다.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


경도를 나타냅니다. 경도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 경도가 도·분·초 형식으로 표현될 경우 일반적인 형식은 ddd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 분의 소수점 둘째 자리까지 표시하는 경우 형식은 ddd/1,mmmm/100,0/1이 됩니다.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


경도가 동경인지 서경인지를 나타냅니다.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


GPS 수신기가 사용하는 측지 조사 데이터를 나타냅니다.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


GPS 측정 모드를 나타냅니다. - 2차원 또는 3차원.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


위치 찾기에 사용된 방법의 이름을 기록하는 문자열입니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며, 그 뒤에 방법 이름이 이어집니다.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


측정에 사용된 GPS 위성을 나타냅니다. 이 태그는 위성 수, ID 번호, 고도 각, 방위각, SNR 및 기타 정보를 ASCII 표기법으로 설명하는 데 사용할 수 있습니다. 형식은 지정되지 않았습니다. GPS 수신기가 측정을 수행할 수 없을 경우, 태그 값은 NULL로 설정되어야 합니다.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


GPS 수신기 이동 속도를 나타냅니다.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


GPS 수신기의 이동 속도를 표현하는 단위를 나타냅니다. 'K', 'M', 'N'은 각각 시속 킬로미터, 시속 마일, 노트를 의미합니다.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


이미지가 기록될 때 GPS 수신기의 상태를 나타냅니다.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


시간을 UTC(협정 세계시)로 나타냅니다. 타임스탬프는 시, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


GPS 수신기 이동 방향을 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


GPS 수신기 이동 방향을 제공하기 위한 기준을 나타냅니다. 'T'는 진방향을, 'M'은 자기방향을 의미합니다.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


GPSInfoIFD의 버전을 나타냅니다.

### GainControl {#GainControl}
```
public static final int GainControl
```


이 태그는 전체 이미지 이득 조정 정도를 나타냅니다.

### Gamma {#Gamma}
```
public static final int Gamma
```


감마 값

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


ISO 12232에 정의된 ISO 속도 값에 대한 정보

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


이 태그는 ISO 12232에 정의된 ISO 속도 위도 yyy 값을 나타냅니다.

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


이 태그는 ISO 12232에 정의된 ISO 속도 위도 zzz 값을 나타냅니다.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


이미지의 제목을 제공하는 문자열입니다. 예를 들어 "1988 회사 소풍"과 같은 주석일 수 있습니다.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


이미지 데이터의 행 수입니다.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


이미지 고유 ID입니다.

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


이미지 데이터의 열 수이며, 행당 픽셀 수와 같습니다.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


JPEG 압축 썸네일 데이터의 시작 바이트(SOI)까지의 오프셋입니다. 이는 기본 이미지 JPEG 데이터에는 사용되지 않습니다.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


JPEG 압축 썸네일 데이터의 바이트 수입니다. 이는 기본 이미지 JPEG 데이터에는 사용되지 않습니다. JPEG 썸네일은 분할되지 않고 SOI부터 EOI까지 연속적인 JPEG 비트스트림으로 기록됩니다. Appn 및 COM 마커는 기록되지 않아야 합니다. 압축된 썸네일은 APP1에 기록되는 모든 다른 데이터를 포함하여 64KB를 초과하지 않게 기록되어야 합니다.

### LensMake {#LensMake}
```
public static final int LensMake
```


이 태그는 렌즈 제조사를 기록합니다.

### LensModel {#LensModel}
```
public static final int LensModel
```


이 태그는 렌즈 모델 이름과 모델 번호를 기록합니다.

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


이 태그는 교환 가능한 렌즈의 일련 번호를 기록합니다.

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


이 태그는 최소 초점 거리, 최대 초점 거리, 최소 초점 거리에서의 최소 F값 및 최대 초점 거리에서의 최소 F값을 기록합니다.

### LightSource {#LightSource}
```
public static final int LightSource
```


광원의 종류.

### Make {#Make}
```
public static final int Make
```


녹화 장비의 제조업체입니다. 이는 이미지를 생성한 DSC, 스캐너, 비디오 디지털라이저 또는 기타 장비의 제조업체를 의미합니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Exif 작성자가 원하는 정보를 기록하기 위한 제조업체용 태그입니다. 내용은 제조업체에 따라 다르지만, 이 태그는 의도된 목적 이외에는 사용되지 않아야 합니다.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


최대 조리개 값.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


측광 모드.

### Model {#Model}
```
public static final int Model
```


장비의 모델명 또는 모델 번호입니다. 이는 이미지를 생성한 DSC, 스캐너, 비디오 디지털라이저 또는 기타 장비의 모델명 또는 번호를 의미합니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다.

### OECF {#OECF}
```
public static final int OECF
```


ISO 14524에 지정된 광전 변환 기능(OECF)을 나타냅니다.

### Orientation {#Orientation}
```
public static final int Orientation
```


행과 열을 기준으로 본 이미지 방향.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


ISO 12232에 지정된 카메라 또는 입력 장치의 ISO 속도와 ISO 위도를 나타냅니다.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


픽셀 구성.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


압축 데이터에 특화된 정보입니다. 압축 파일이 기록될 때, 패딩 데이터나 재시작 마커가 있든 없든 의미 있는 이미지의 유효 너비가 이 태그에 기록됩니다.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


압축 데이터에 특화된 정보입니다. 압축 파일이 기록될 때, 의미 있는 이미지의 유효 높이가 이 태그에 기록됩니다.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


픽셀 구성 요소가 청키(Chunky) 형식인지 플래너(Planar) 형식인지 여부를 나타냅니다. 이 필드가 없으면 TIFF 기본값인 1(청키)으로 간주됩니다.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


이미지의 세 기본 색상의 색도입니다. 일반적으로 색상 공간이 ColorSpace 태그의 색상 공간 정보에 지정되어 있기 때문에 이 태그는 필요하지 않습니다.

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


권장 노출 지수를 나타냅니다.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


참조 검은점 값과 참조 흰점 값을 나타냅니다. TIFF에서는 기본값이 제공되지 않지만, 여기서는 아래 값을 기본값으로 제시합니다. 색상 공간은 색상 공간 정보 태그에 선언되며, 기본값은 최적의 이미지 특성을 제공하는 값입니다.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


관련 사운드 파일.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


XResolution과 YResolution을 측정하는 단위입니다. XResolution과 YResolution 모두 동일한 단위가 사용됩니다. 이미지 해상도가 알 수 없을 경우 2(인치)가 지정됩니다.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


스트립당 행 수입니다. 이미지를 스트립으로 나눌 때 한 스트립에 포함되는 이미지 행 수를 나타냅니다.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


픽셀당 구성 요소 수입니다. 이 표준은 RGB 및 YCbCr 이미지에 적용되므로 이 태그에 설정되는 값은 3입니다.

### Saturation {#Saturation}
```
public static final int Saturation
```


이 태그는 촬영 시 카메라가 적용한 채도 처리 방향을 나타냅니다.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


이 태그는 촬영된 장면의 유형을 나타냅니다. 또한 이미지가 촬영된 모드를 기록하는 데에도 사용할 수 있습니다.

### SceneType {#SceneType}
```
public static final int SceneType
```


장면의 유형을 나타냅니다. DSC가 이미지를 기록한 경우, 이 태그 값은 항상 1로 설정되어 이미지가 직접 촬영되었음을 나타냅니다.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


카메라 또는 입력 장치의 이미지 센서 유형을 나타냅니다.

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


사진 감도 유형

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


이 태그는 이미지가 촬영될 때 카메라에 의해 적용된 선명도 처리 방향을 나타냅니다

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


셔터 속도 값입니다.

### Software {#Software}
```
public static final int Software
```


이 태그는 이미지를 생성하는 데 사용된 카메라 또는 이미지 입력 장치의 소프트웨어 또는 펌웨어 이름과 버전을 기록합니다. 자세한 형식은 지정되지 않았지만 아래 예시를 따르는 것이 권장됩니다. 필드를 비워두면 알 수 없는 것으로 처리됩니다.

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


이 태그는 ISO 12233에 명시된 대로 이미지 너비, 이미지 높이 및 대각선 방향의 공간 주파수 표와 SFR 값을 카메라 또는 입력 장치에 대해 기록합니다.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


사용된 카메라 각 채널의 스펙트럼 감도를 나타냅니다.

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


카메라의 표준 출력 감도를 나타냅니다

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


각 스트립의 총 바이트 수입니다.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


각 스트립에 대해 해당 스트립의 바이트 오프셋을 지정합니다. 스트립 바이트 수가 64KB를 초과하지 않도록 선택하는 것이 권장됩니다. 보조 태그.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


이 태그는 전체 장면에서 주요 피사체의 위치와 영역을 나타냅니다.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


피사체까지의 거리이며, 미터 단위입니다.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


이 태그는 피사체까지의 거리를 나타냅니다.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


장면에서 주요 피사체의 위치를 나타냅니다. 이 태그의 값은 회전 태그에 따른 회전 처리 이전에 왼쪽 가장자리 기준으로 주요 피사체 중심에 해당하는 픽셀을 나타냅니다.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


DateTime 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


DateTimeDigitized 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


DateTimeOriginal 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


이미지에 대한 전송 함수를 표 형식으로 설명합니다. 일반적으로 색 공간이 색 공간 정보인 ColorSpace 태그에 지정되어 있기 때문에 이 태그는 필요하지 않습니다.

### UserComment {#UserComment}
```
public static final int UserComment
```


Exif 사용자가 ImageDescription에 있는 내용 외에 이미지에 키워드나 주석을 작성할 수 있도록 하며, ImageDescription 태그의 문자 코드 제한이 없는 태그입니다.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


이 태그는 이미지 촬영 시 설정된 화이트 밸런스 모드를 나타냅니다.

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


이미지의 백색점 색도입니다. 일반적으로 색 공간이 색 공간 정보인 ColorSpace 태그에 지정되어 있기 때문에 이 태그는 필요하지 않습니다.

### XResolution {#XResolution}
```
public static final int XResolution
```


ImageWidth 방향의 ResolutionUnit당 픽셀 수입니다. 이미지 해상도를 알 수 없을 경우 72 [dpi]가 지정됩니다.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


RGB에서 YCbCr 이미지 데이터로 변환하기 위한 행렬 계수입니다.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


크로마성분이 휘도 성분과 위치 관계를 갖는 위치입니다. 이 필드는 JPEG 압축 데이터 또는 비압축 YCbCr 데이터에만 지정됩니다. TIFF 기본값은 1(중심)이며, Y:Cb:Cr = 4:2:2인 경우 이 표준에서는 TV 시스템에서 이미지 품질을 향상시키기 위해 2(동시 배치)를 사용하여 데이터를 기록할 것을 권장합니다. 이 필드가 존재하지 않을 경우, 리더는 TIFF 기본값을 가정해야 합니다. Y:Cb:Cr = 4:2:0인 경우에는 TIFF 기본값(중심)이 권장됩니다. 리더가 두 종류의 YCbCrPositioning을 모두 지원할 능력이 없을 경우, 이 필드의 값에 관계없이 TIFF 기본값을 따라야 합니다. 리더가 \"both centered and co-sited positioning\"을 지원할 수 있으면 바람직합니다.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


휘도 성분에 대한 색차 성분의 샘플링 비율입니다.

### YResolution {#YResolution}
```
public static final int YResolution
```


ImageLength 방향의 ResolutionUnit당 픽셀 수입니다. XResolution과 동일한 값이 지정됩니다.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames() {#getNames--}
```
public String[] getNames()
```




**Returns:**
java.lang.String[]
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues() {#getValues--}
```
public Long[] getValues()
```




**Returns:**
java.lang.Long[]
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Long[]
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, String arg1) {#isDefined-java.lang.Class----java.lang.String-}
```
public static boolean isDefined(Class<?> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### toString(long arg0) {#toString-long-}
```
public String toString(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

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

