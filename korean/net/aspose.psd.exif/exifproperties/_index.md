---
title: Enum ExifProperties
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Exif.ExifProperties 열거형. Exif 태그 목록
type: docs
weight: 1000
url: /ko/net/aspose.psd.exif/exifproperties/
---
## ExifProperties enumeration

Exif 태그 목록

```csharp
public enum ExifProperties : ushort
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ImageWidth | `256` | 행당 픽셀 수와 동일한 이미지 데이터의 열 수입니다. |
| ImageLength | `257` | 이미지 데이터의 행 수입니다. |
| BitsPerSample | `258` | 이미지 구성 요소당 비트 수. 이 표준에서 이미지의 각 구성 요소는 8비트이므로 이 태그의 값은 8. 입니다. |
| Compression | `259` | 이미지 데이터에 사용되는 압축 방식입니다. 기본 이미지가 JPEG 압축인 경우 이 지정은 필요하지 않으며 생략됩니다. |
| PhotometricInterpretation | `262` | 픽셀 구성. |
| ImageDescription | `270` | 이미지의 제목을 나타내는 문자열. "1988년 회사 야유회" 등의 댓글이 될 수 있습니다. |
| Make | `271` | 녹음 장비 제조업체입니다. 이미지를 생성한 DSC, 스캐너, 비디오 디지타이저 또는 기타 장비의 제조업체입니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| Model | `272` | 장비의 모델명 또는 모델 번호입니다. 이것은 이미지를 생성한 DSC, 스캐너, 비디오 디지타이저 또는 기타 장비의 모델 이름 또는 번호입니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| Orientation | `274` | 행과 열로 표시되는 이미지 방향입니다. |
| SamplesPerPixel | `277` | 픽셀당 구성 요소 수입니다. 이 표준은 RGB 및 YCbCr 이미지에 적용되므로 이 태그에 설정된 값은 3. 입니다. |
| XResolution | `282` | ImageWidth 방향에서 ResolutionUnit당 픽셀 수입니다. 이미지 해상도를 알 수 없는 경우 72[dpi]를 지정합니다. |
| YResolution | `283` | ImageLength 방향에서 ResolutionUnit당 픽셀 수입니다. XResolution과 동일한 값이 지정됩니다. |
| PlanarConfiguration | `284` | 픽셀 구성 요소가 Chunky 또는 Planar 형식으로 기록되는지 여부를 나타냅니다. 이 필드가 없으면 TIFF 기본값인 1(청키)이 가정됩니다. |
| ResolutionUnit | `296` | XResolution 및 YResolution을 측정하는 단위입니다. XResolution과 YResolution 모두에 동일한 단위가 사용됩니다. 이미지 해상도를 알 수 없는 경우 2(인치)가 지정됩니다. |
| TransferFunction | `301` | 표 형식으로 설명된 이미지의 전달 함수입니다. 색 공간 정보 ColorSpace tag. 에 색 공간이 지정되어 있으므로 일반적으로 이 태그는 필요하지 않습니다. |
| Software | `305` | 이 태그는 이미지를 생성하는 데 사용되는 카메라 또는 이미지 입력 장치의 소프트웨어 또는 펌웨어의 이름과 버전을 기록합니다. 구체적인 형식은 명시되어 있지 않으나 아래의 예를 따를 것을 권장합니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| DateTime | `306` | 이미지 생성 날짜 및 시간. Exif 표준에서는 파일이 변경된 날짜와 시간입니다. |
| Artist | `315` | 이 태그는 카메라 소유자, 사진가 또는 이미지 작성자의 이름을 기록합니다. 구체적인 형식은 명시되어 있지 않으나, 상호운용의 편의를 위해 아래 예시와 같이 정보를 작성하는 것을 권장합니다. 필드를 비워두면 알 수 없는 것으로 처리됩니다. 예) "카메라 소유자, John Smith, 사진 작가, Michael Brown, 이미지 제작자, Ken James" |
| WhitePoint | `318` | 이미지의 백색점의 색도. 색 공간 정보 ColorSpace tag. 에 색 공간이 지정되어 있으므로 일반적으로 이 태그는 필요하지 않습니다. |
| PrimaryChromaticities | `319` | 이미지의 삼원색의 색도. 색공간 정보 ColorSpace tag. 에 색공간이 지정되어 있으므로 일반적으로 이 태그는 필요하지 않습니다. |
| YCbCrCoefficients | `529` | RGB에서 YCbCr 이미지 데이터로 변환하기 위한 행렬 계수입니다. |
| YCbCrSubSampling | `530` | 휘도 성분에 대한 색차 성분의 샘플링 비율. |
| YCbCrPositioning | `531` | 휘도 구성 요소와 관련된 색차 구성 요소의 위치입니다. 이 필드는 JPEG 압축 데이터 또는 압축되지 않은 YCbCr 데이터에만 지정됩니다. TIFF 기본값은 1(중앙)입니다. 그러나 Y:Cb:Cr = 4:2:2일 때 TV 시스템에서 볼 때 이미지 품질을 향상시키기 위해 데이터를 기록하는 데 2(co-sited)를 사용하는 것이 이 표준에서 권장됩니다. 이 필드가 존재하지 않으면 판독기는 TIFF 기본값을 가정합니다. Y:Cb:Cr = 4:2:0의 경우 TIFF 기본값(중앙)을 권장합니다. reader 가 두 종류의 YCbCrPositioning을 모두 지원할 수 없는 경우 이 필드 값의 에 관계없이 TIFF 기본값을 따릅니다. 판독기 " 가 중앙 및 공동 위치 지정을 모두 지원할 수 있는 것이 바람직합니다. |
| ReferenceBlackWhite | `532` | 참조 블랙 포인트 값 및 참조 화이트 포인트 값. TIFF에는 기본값이 주어지지 않지만 여기서는 아래 값이 기본값으로 주어집니다. 색 공간은 색 공간 정보 태그에서 선언된 이며, default 는 최적의 이미지 특성을 제공하는 값입니다. 상호 운용성 이러한 조건 |
| Copyright | `33432` | 저작권 정보. 이 표준에서 태그는 사진가와 편집자 저작권을 모두 표시하는 데 사용됩니다. 이미지에 대한 권리를 주장하는 사람이나 조직의 저작권 표시입니다. 날짜 및 권한을 포함하는 상호 운용성 copyright 설명은 this 필드에 작성해야 합니다. 예: "Copyright, John Smith, 19xx. All rights reserved.". 이 표준에서 필드는 the 사진작가와 편집자 저작권을 모두 기록하며 각각은 진술의 a 별도 부분에 기록됩니다. 사진가와 편집자 저작권 사이에 명확한 구분 이 있을 때, 이들은 사진가와 편집자 저작권 순으로 작성되고, 는 NULL로 구분됩니다(이 경우 문도 NULL로 끝나므로 두 개의 NULL 코드가 있습니다 ). photographer copyright 만 부여하면 하나의 NULL 코드로 종료됩니다. only 에 편집자 저작권이 주어지면 사진 작가 저작권 part 는 하나의 공백과 종료 NULL 코드로 구성되고 then 에 편집자 저작권이 주어집니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| ExposureTime | `33434` | 노출 시간(초 단위). |
| FNumber | `33437` | F 번호. |
| ExposureProgram | `34850` | 사진을 찍을 때 노출을 설정하기 위해 카메라에서 사용하는 프로그램 클래스입니다. |
| SpectralSensitivity | `34852` | 사용된 카메라의 각 채널의 분광 감도를 나타냅니다. |
| PhotographicSensitivity | `34855` | ISO 12232에 지정된 대로 카메라 또는 입력 장치의 ISO 속도 및 ISO 위도를 나타냅니다. |
| OECF | `34856` | ISO 14524에 지정된 광전기 변환 기능(OECF)을 나타냅니다. |
| ExifVersion | `36864` | exif 버전. |
| DateTimeOriginal | `36867` | 원본 이미지 데이터가 생성된 날짜와 시간입니다. |
| DateTimeDigitized | `36868` | 디지털화된 날짜 시간입니다. |
| ComponentsConfiguration | `37121` | 구성 요소 구성. |
| CompressedBitsPerPixel | `37122` | 압축 데이터에만 적용됩니다. 픽셀당 압축된 비트를 나타냅니다. |
| ShutterSpeedValue | `37377` | 셔터 속도 값입니다. |
| ApertureValue | `37378` | 렌즈 조리개 값입니다. |
| BrightnessValue | `37379` | 밝기 값입니다. |
| ExposureBiasValue | `37380` | 노출 바이어스 값입니다. |
| MaxApertureValue | `37381` | 최대 조리개 값입니다. |
| SubjectDistance | `37382` | 피사체까지의 거리(미터 단위). |
| MeteringMode | `37383` | 측광 모드입니다. |
| LightSource | `37384` | 친절한 광원. |
| Flash | `37385` | 이미지가 촬영되었을 때 플래시 상태를 나타냅니다. |
| FocalLength | `37386` | 렌즈의 실제 초점 거리(mm). |
| SubjectArea | `37396` | 이 태그는 전체 장면에서 주요 피사체의 위치와 영역을 나타냅니다. |
| MakerNote | `37500` | Exif 작성기 제조업체가 원하는 정보를 기록하기 위한 태그입니다. 내용물은 제조사의 판단에 따르지만, 이 태그는 본래의 용도 이외의 용도로 사용해서는 안됩니다. |
| UserComment | `37510` | Exif 사용자가 ImageDescription 태그의 문자 코드 제한 없이 ImageDescription 이외의 이미지에 키워드나 댓글을 작성할 수 있는 태그입니다. |
| SubsecTime | `37520` | DateTime 태그의 초 단위를 기록하는 데 사용되는 태그입니다. |
| SubsecTimeOriginal | `37521` | DateTimeOriginal 태그의 초 단위를 기록하는 데 사용되는 태그입니다. |
| SubsecTimeDigitized | `37522` | DateTimeDigitized 태그의 초 단위를 기록하는 데 사용되는 태그입니다. |
| FlashpixVersion | `40960` | FPXR 파일에서 지원하는 Flashpix 형식 버전입니다. |
| ColorSpace | `40961` | 색 공간 정보 태그(ColorSpace)는 항상 색 공간 지정자로 기록됩니다. |
| RelatedSoundFile | `40964` | 관련 사운드 파일. |
| FlashEnergy | `41483` | BCPS(Beam Candle Power Seconds)로 측정된 이미지 캡처 시간의 스트로브 에너지를 나타냅니다. |
| SpatialFrequencyResponse | `41484` | 이 태그는 ISO 12233에 지정된 대로 카메라 또는 입력 장치 공간 주파수 테이블과 이미지 너비, 이미지 높이 및 대각선 방향의 SFR 값을 기록합니다. |
| FocalPlaneXResolution | `41486` | 카메라 초점면에서 FocalPlaneResolutionUnit당 이미지 너비(X) 방향의 픽셀 수를 나타냅니다. |
| FocalPlaneYResolution | `41487` | 카메라 초점면에서 FocalPlaneResolutionUnit당 이미지 높이(Y) 방향의 픽셀 수를 나타냅니다. |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution 및 FocalPlaneYResolution 측정 단위를 나타냅니다. 이 값은 ResolutionUnit. 와 동일합니다. |
| SubjectLocation | `41492` | 장면에서 주 피사체의 위치를 나타냅니다. 이 태그의 값은 회전 태그에 따라 회전 처리하기 전에 왼쪽 가장자리를 기준으로 주 피사체의 중심에 있는 픽셀을 나타냅니다. |
| ExposureIndex | `41493` | 이미지 촬영 시 카메라 또는 입력 장치에서 선택한 노출 지수를 나타냅니다. |
| SensingMethod | `41495` | 카메라 또는 입력 장치의 이미지 센서 유형을 나타냅니다. |
| FileSource | `41728` | 파일 소스입니다. |
| SceneType | `41729` | 장면 유형을 나타냅니다. DSC가 이미지를 기록했다면 이 태그 값은 항상 1로 설정되어 이미지가 직접 촬영되었음을 나타냅니다. |
| CFAPattern | `41730` | 원칩 컬러 영역 센서를 사용할 때 이미지 센서의 컬러 필터 어레이(CFA) 기하학적 패턴을 나타냅니다. 모든 센싱 방식에 적용되는 것은 아닙니다. |
| CustomRendered | `41985` | 이 태그는 출력용 렌더링과 같은 이미지 데이터에 대한 특수 처리 사용을 나타냅니다. 특수 처리가 수행되면 판독기는 추가 처리를 비활성화하거나 최소화해야 합니다. |
| ExposureMode | `41986` | 이 태그는 이미지가 촬영될 때 설정된 노출 모드를 나타냅니다. 자동 브라케팅 모드에서 카메라는 다른 노출 설정에서 동일한 장면의 일련의 프레임을 촬영합니다. |
| WhiteBalance | `41987` | 이 태그는 이미지를 촬영할 때 설정한 화이트 밸런스 모드를 나타냅니다. |
| DigitalZoomRatio | `41988` | 이 태그는 이미지가 촬영되었을 때의 디지털 줌 비율을 나타냅니다. 기록된 값의 분자가 0이면 디지털 줌을 사용하지 않은 것입니다. |
| FocalLengthIn35MmFilm | `41989` | 이 태그는 35mm 필름 카메라를 가정하여 해당 초점 거리를 mm 단위로 나타냅니다. 0 값은 초점 거리를 알 수 없음을 의미합니다. 이 태그는 FocalLength 태그와 다릅니다. |
| SceneCaptureType | `41990` | 이 태그는 촬영된 장면의 유형을 나타냅니다. 이미지가 촬영된 모드를 기록하는 데에도 사용할 수 있습니다. |
| GainControl | `41991` | 이 태그는 전반적인 이미지 게인 조정 정도를 나타냅니다. |
| Contrast | `41992` | 이 태그는 이미지가 촬영될 때 카메라가 적용한 대비 처리의 방향을 나타냅니다. |
| Saturation | `41993` | 이 태그는 이미지가 촬영될 때 카메라가 적용한 채도 처리 방향을 나타냅니다. |
| Sharpness | `41994` | 이 태그는 이미지가 촬영되었을 때 카메라가 적용한 선명도 처리 방향을 나타냅니다 |
| DeviceSettingDescription | `41995` | 이 태그는 특정 카메라 모델의 촬영 조건에 대한 정보를 나타냅니다. 태그는 판독기에서 사진 촬영 조건을 나타내는 데만 사용됩니다. |
| SubjectDistanceRange | `41996` | 이 태그는 피사체까지의 거리를 나타냅니다. |
| ImageUniqueID | `42016` | 이미지 고유 ID. |
| GPSVersionID | `0` | GPSInfoIFD의 버전을 나타냅니다. |
| GPSLatitudeRef | `1` | 위도가 북위인지 남위인지 나타냅니다. |
| GPSLatitude | `2` | 위도를 나타냅니다. 위도는 각각 도, 분 및 초를 제공하는 3개의 RATIONAL 값으로 표현됩니다. 위도가 도, 분, 초로 표시되는 경우 일반적인 형식은 dd/1,mm/1,ss/1입니다. 도와 분을 사용하고 예를 들어 분의 분수가 소수점 두 자리까지 주어지면 형식은 dd/1,mmmm/100,0/1. 가 됩니다. |
| GPSLongitudeRef | `3` | 경도가 동경인지 서경인지를 나타냅니다. |
| GPSLongitude | `4` | 경도를 나타냅니다. 경도는 각각 도, 분 및 초를 제공하는 3개의 RATIONAL 값으로 표현됩니다. 경도가 도, 분, 초로 표시되는 경우 일반적인 형식은 ddd/1,mm/1,ss/1입니다. 도와 분을 사용하고 예를 들어 분의 분수가 소수점 두 자리까지 주어지면 형식은 ddd/1,mmmm/100,0/1. 가 됩니다. |
| GPSAltitudeRef | `5` | 기준 고도로 사용되는 고도를 나타냅니다. 기준이 해수면이고 고도가 해수면보다 높으면 0이 주어집니다. 고도가 해수면보다 낮으면 값 1이 주어지고 고도는 GPSAltitude 태그 에 절대값으로 표시됩니다. |
| GPSAltitude | `6` | GPSAltitudeRef의 참조를 기반으로 고도를 나타냅니다. 고도는 하나의 RATIONAL 값으로 표현됩니다. 기준 단위는 미터입니다. |
| GPSTimestamp | `7` | 시간을 UTC(Coordinated Universal Time)로 나타냅니다. 타임스탬프는 시, 분, 초를 제공하는 3개의 RATIONAL values 로 표현됩니다. |
| GPSSatellites | `8` | 측정에 사용되는 GPS 위성을 나타냅니다. 이 태그는 위성의 수, 위성의 ID 번호, 앙각, 방위각, SNR 및 ASCII 표기법의 기타 정보를 설명하는 데 사용할 수 있습니다. 형식이 not 지정되었습니다. GPS 수신기가 측정을 수행할 수 없는 경우 태그 값은 NULL로 설정되어야 합니다. |
| GPSStatus | `9` | 이미지가 기록될 때 GPS 수신기의 상태를 나타냅니다. |
| GPSMeasureMode | `10` | GPS 측정 모드를 나타냅니다. - 2차원 또는 3차원. |
| GPSDOP | `11` | GPS DOP(데이터 정밀도)를 나타냅니다. HDOP 값은 2차원 측정 시, , PDOP는 3차원 측정 시 기록됩니다. |
| GPSSpeedRef | `12` | GPS 수신기 이동 속도를 표현하는 데 사용되는 단위를 나타냅니다. 'K' 'M' 및 'N'은 킬로미터 per 시간, 시간당 마일 및 노트를 나타냅니다. |
| GPSSpeed | `13` | GPS 수신기 이동 속도를 나타냅니다. |
| GPSTrackRef | `14` | GPS 수신기 이동 방향을 알려주는 기준을 나타냅니다. 'T'는 실제 방향을 나타내고 'M'은 자기 방향입니다. |
| GPSTrack | `15` | GPS 수신기 이동 방향을 나타냅니다. 값의 범위는 0.00에서 359.99. 까지입니다. |
| GPSImgDirectionRef | `16` | 이미지를 촬영할 때 이미지의 방향을 알려주는 기준을 나타냅니다. 'T'는 실제 방향을 나타내고 'M'은 자기 방향입니다. |
| GPSImgDirection | `17` | 이미지가 캡처되었을 때의 방향을 나타냅니다. 값의 범위는 0.00에서 359.99. 까지입니다. |
| GPSMapDatum | `18` | GPS 수신기에서 사용하는 측지 측량 데이터를 나타냅니다. |
| GPSDestLatitudeRef | `19` | 목적지 지점의 위도가 북위인지 남위인지를 나타냅니다. ASCII 값 'N'은 north 위도를 나타내고 'S'는 남위. 를 나타냅니다. |
| GPSDestLatitude | `20` | 목적지 지점의 위도를 나타냅니다. 위도는 각각 도, 분, 초를 제공하는 세 개의 RATIONAL 값으로 표현됩니다. 위도가 도, 분, 초로 표시되는 경우 Typical 형식은 dd/1,mm/1,ss/1입니다. 도와 분을 사용하고 예를 들어 분의 분수가 소수점 이하 두 자리까지 주어지는 경우 형식은 dd/1,mmmm/100,0/1. 입니다. |
| GPSDestLongitudeRef | `21` | 목적지 지점의 경도가 동경인지 서경인지를 나타냅니다. ASCII 'E'는 동경, 를 나타내고 'W'는 서경을 나타냅니다. |
| GPSDestLongitude | `22` | 목적지 지점의 경도를 나타냅니다. 경도는 각각 도, 분, 초를 제공하는 3개의 RATIONAL 값으로 표현됩니다. 경도가 도, 분, 초로 표시되는 경우 Typical 형식은 ddd/1,mm/1,ss/1입니다. 도와 분을 사용하고 예를 들어 분의 분수가 소수점 이하 두 자리까지 주어지는 경우 형식은 ddd/1,mmmm/100,0/1. 가 됩니다. |
| GPSDestBearingRef | `23` | 목적지에 방위를 부여하는 데 사용되는 참조를 나타냅니다. 'T'는 실제 방향을 나타내고 'M'은 자기 방향입니다. |
| GPSDestBearing | `24` | 목적지 지점까지의 방위를 나타냅니다. 값의 범위는 0.00에서 359.99. 까지입니다. |
| GPSDestDistanceRef | `25` | 목적지까지의 거리를 나타내는 단위를 나타냅니다. 'K', 'M' 및 'N'은 킬로미터, 마일 및 매듭을 나타냅니다. |
| GPSDestDistance | `26` | 목적지까지의 거리를 나타냅니다. |
| GPSProcessingMethod | `27` | 위치 찾기에 사용된 방법의 이름을 기록한 문자열입니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며 그 뒤에는 방법의 이름 가 옵니다. |
| GPSAreaInformation | `28` | GPS 영역의 이름을 기록한 문자열. 첫 번째 바이트는 사용된 문자 코드를 나타내고 그 뒤에 GPS 영역의 이름이 옵니다. |
| GPSDateStamp | `29` | UTC (Coordinated Universal Time)에 대한 날짜 및 시간 정보를 기록한 문자열. 형식은 YYYY:MM:DD. 입니다. |
| GPSDifferential | `30` | GPS 수신기에 차분 보정 적용 여부를 나타냅니다. |
| StripOffsets | `273` | 각 스트립에 대해 해당 스트립의 바이트 오프셋. 스트립 바이트 수가 64KB를 초과하지 않도록 선택하는 것이 좋습니다. Aux 태그. |
| JPEGInterchangeFormat | `513` | JPEG 압축 썸네일 데이터의 시작 바이트(SOI)에 대한 오프셋입니다. 기본 이미지 JPEG 데이터에는 사용되지 않습니다. |
| JPEGInterchangeFormatLength | `514` | JPEG 압축 섬네일 데이터의 바이트 수. 기본 이미지 JPEG 데이터에는 사용되지 않습니다. JPEG 썸네일은 분할되지 않고 SOI에서 EOI까지 연속적인 JPEG 비트스트림으로 기록됩니다. Appn 및 COM 마커는 기록되지 않아야 합니다. 압축된 썸네일은 APP1. 에 기록될 다른 모든 데이터를 포함하여 64KB 이하로 기록되어야 합니다. |
| ExifIfdPointer | `34665` | Exif IFD에 대한 포인터입니다. 상호 운용성, Exif IFD는 TIFF에 명시된 IFD와 동일한 구조를 가집니다. 그러나 일반적으로 TIFF. 의 경우와 같이 이미지 데이터를 포함하지 않습니다. |
| GPSIfdPointer | `34853` | GPS ifd 포인터. |
| RowsPerStrip | `278` | 스트립당 행 수. 이미지를 스트립으로 나눌 때 한 스트립의 이미지에 있는 행 수입니다. |
| StripByteCounts | `279` | 각 스트립의 총 바이트 수입니다. |
| PixelXDimension | `40962` | 압축 데이터 관련 정보. 압축 파일을 기록할 때 패딩 데이터가 있든 재시작 마커가 있든 없든 의미 있는 이미지의 유효한 너비를 이 태그에 기록해야 합니다. |
| PixelYDimension | `40963` | 압축 데이터 관련 정보. 압축파일을 기록할 때 의미 있는 이미지의 유효 높이는 이 tag 에 기록됩니다. |
| Gamma | `42240` | 감마값 |
| SensitivityType | `34864` | 사진 감도 유형 |
| StandardOutputSensitivity | `34865` | 카메라 의 표준 출력 감도를 나타냅니다. |
| RecommendedExposureIndex | `34866` | 권장 노출 지수를 나타냅니다 |
| ISOSpeed | `34867` | ISO 12232 에 정의된 ISO 속도 값에 대한 정보 |
| ISOSpeedLatitudeYYY | `34868` | 이 태그는 ISO 12232 에 정의된 ISO 속도 관용도 yyy 값을 나타냅니다. |
| ISOSpeedLatitudeZZZ | `34869` | 이 태그는 ISO 12232 에 정의된 ISO 속도 관용도 zzz 값을 나타냅니다. |
| CameraOwnerName | `42032` | 카메라 소유자 이름 포함 |
| BodySerialNumber | `42033` | 카메라 본체 일련 번호 포함 |
| LensMake | `42035` | 이 태그는 lens manufacturer 를 기록합니다. |
| LensModel | `42036` | 이 태그는 렌즈의 모델명과 모델 번호를 기록합니다 |
| LensSerialNumber | `42037` | 이 태그는 교환식 렌즈 의 일련 번호를 기록합니다. |
| LensSpecification | `42034` | 이 태그는 최소 초점 거리, 최대 초점 거리, 최소 초점 거리의 최소 F 번호 및 최대 초점 거리의 최소 F 번호를 기록합니다 |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.Exif](../../aspose.psd.exif/)
* 집회 [Aspose.PSD](../../)


