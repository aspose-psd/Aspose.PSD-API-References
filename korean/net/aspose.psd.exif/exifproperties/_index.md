---
title: "Enum ExifProperties"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Exif.ExifProperties 열거형. Exif 태그 목록"
type: docs
weight: 1010
url: /ko/net/aspose.psd.exif/exifproperties/
---
{{< psd/tize >}}
## ExifProperties enumeration

Exif 태그 목록

```csharp
public enum ExifProperties : ushort
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ImageWidth | `256` | 이미지 데이터의 열 수이며, 행당 픽셀 수와 같습니다. |
| ImageLength | `257` | 이미지 데이터의 행 수. |
| BitsPerSample | `258` | 이미지 구성 요소당 비트 수입니다. 이 표준에서는 이미지의 각 구성 요소가 8비트이므로 이 태그의 값은 8입니다. |
| Compression | `259` | 이미지 데이터에 사용되는 압축 방식입니다. 기본 이미지가 JPEG 압축된 경우 이 지정은 필요 없으며 생략됩니다. |
| PhotometricInterpretation | `262` | 픽셀 구성. |
| ImageDescription | `270` | 이미지의 제목을 제공하는 문자열입니다. "1988 company picnic"와 같은 주석일 수 있습니다. |
| Make | `271` | 녹화 장비의 제조업체입니다. 이는 이미지를 생성한 DSC, 스캐너, 비디오 디지털 변환기 또는 기타 장비의 제조업체를 의미합니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| Model | `272` | 장비의 모델명 또는 모델 번호입니다. 이는 이미지를 생성한 DSC, 스캐너, 비디오 디지털 변환기 또는 기타 장비의 모델명 또는 번호를 의미합니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| Orientation | `274` | 행과 열을 기준으로 보는 이미지 방향. |
| SamplesPerPixel | `277` | 픽셀당 구성 요소 수. 이 표준은 RGB 및 YCbCr 이미지에 적용되므로 이 태그에 설정된 값은 3입니다. |
| XResolution | `282` | ImageWidth 방향의 ResolutionUnit당 픽셀 수. 이미지 해상도가 알려지지 않은 경우 72 [dpi]가 지정됩니다. |
| YResolution | `283` | ImageLength 방향의 ResolutionUnit당 픽셀 수. XResolution과 동일한 값이 지정됩니다. |
| PlanarConfiguration | `284` | 픽셀 구성 요소가 청키 형식인지 플래너 형식인지 표시합니다. 이 필드가 없으면 TIFF 기본값인 1(청키)으로 간주됩니다. |
| ResolutionUnit | `296` | XResolution 및 YResolution을 측정하는 단위. XResolution과 YResolution 모두 동일한 단위가 사용됩니다. 이미지 해상도가 알려지지 않은 경우 2(인치)가 지정됩니다. |
| TransferFunction | `301` | 표 형식으로 설명된 이미지 전송 함수. 일반적으로 색 공간이 색 공간 정보 ColorSpace 태그에 지정되어 있기 때문에 이 태그는 필요하지 않습니다. |
| Software | `305` | 이 태그는 이미지를 생성하는 데 사용된 카메라 또는 이미지 입력 장치의 소프트웨어 또는 펌웨어 이름과 버전을 기록합니다. 자세한 형식은 지정되지 않았지만 아래 예시를 따르는 것이 권장됩니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| DateTime | `306` | 이미지 생성 날짜와 시간. Exif 표준에서는 파일이 변경된 날짜와 시간입니다. |
| Artist | `315` | 이 태그는 카메라 소유자, 사진작가 또는 이미지 제작자의 이름을 기록합니다. 자세한 형식은 지정되지 않았지만 상호 운용성을 위해 아래 예시와 같이 정보를 작성하는 것이 권장됩니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. 예) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| WhitePoint | `318` | 이미지의 화이트 포인트 색도. 일반적으로 색 공간이 색 공간 정보 ColorSpace 태그에 지정되어 있기 때문에 이 태그는 필요하지 않습니다. |
| PrimaryChromaticities | `319` | 이미지의 세 기본 색상의 색도. 일반적으로 색 공간이 색 공간 정보 ColorSpace 태그에 지정되어 있기 때문에 이 태그는 필요하지 않습니다. |
| YCbCrCoefficients | `529` | RGB에서 YCbCr 이미지 데이터로 변환하기 위한 행렬 계수. |
| YCbCrSubSampling | `530` | 휘도 성분에 대한 색차 성분의 샘플링 비율. |
| YCbCrPositioning | `531` | 휘도 성분에 대한 색차 성분의 위치. 이 필드는 JPEG 압축 데이터 또는 비압축 YCbCr 데이터에만 지정됩니다. TIFF 기본값은 1(중심)이며, Y:Cb:Cr = 4:2:2인 경우 이 표준에서는 이미지 품질을 TV 시스템에서 향상시키기 위해 2(동시 배치)를 사용하여 데이터를 기록하도록 권장합니다. 이 필드가 없으면 리더는 TIFF 기본값을 가정해야 합니다. Y:Cb:Cr = 4:2:0인 경우 TIFF 기본값(중심)이 권장됩니다. 리더가 두 종류의 YCbCrPositioning을 모두 지원할 능력이 없으면 해당 필드 값에 관계없이 TIFF 기본값을 따라야 합니다. 리더가 " both centered and co-sited positioning을 지원할 수 있으면 바람직합니다. |
| ReferenceBlackWhite | `532` | 참조 블랙 포인트 값과 참조 화이트 포인트 값. TIFF에는 기본값이 제공되지 않지만 아래 값이 여기서 기본값으로 제공됩니다. 색 공간은 색 공간 정보 태그에 선언되며, 기본값은 최적의 이미지 특성을 제공하는 값입니다. |
| Copyright | `33432` | Kopyright 정보. 이 표준에서는 태그가 사진작가와 편집자 저작권을 모두 표시하는 데 사용됩니다. 이는 이미지에 대한 권리를 주장하는 개인 또는 조직의 저작권 고지입니다. 상호 운용성 저작권 진술문(날짜 및 권리 포함)은 이 필드에 작성해야 합니다; 예: "Copyright, John Smith, 19xx. All rights reserved.". 이 표준에서는 필드가 사진작가와 편집자 저작권을 모두 기록하며, 각각은 진술문의 별도 부분에 기록됩니다. 사진작가와 편집자 저작권이 명확히 구분될 경우, 사진작가 뒤에 편집자 저작권을 순서대로 작성하고 NULL로 구분합니다(이 경우 진술문이 NULL로 끝나므로 NULL 코드가 두 개 있습니다). 사진작가 저작권만 제공되는 경우 하나의 NULL 코드로 종료됩니다. 편집자 저작권만 제공되는 경우, 사진작가 저작권 부분은 하나의 공백 뒤에 종료 NULL 코드를 포함하고, 그 다음에 편집자 저작권이 제공됩니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| ExposureTime | `33434` | 노출 시간(초 단위). |
| FNumber | `33437` | F값. |
| ExposureProgram | `34850` | 사진 촬영 시 카메라가 노출을 설정하는 데 사용하는 프로그램의 클래스. |
| SpectralSensitivity | `34852` | 사용된 카메라 각 채널의 스펙트럼 감도를 나타냅니다. |
| PhotographicSensitivity | `34855` | ISO 12232에 명시된 대로 카메라 또는 입력 장치의 ISO 속도와 ISO 위도(범위)를 나타냅니다. |
| OECF | `34856` | ISO 14524에 지정된 광전 변환 함수(OECF)를 나타냅니다. |
| ExifVersion | `36864` | Exif 버전. |
| DateTimeOriginal | `36867` | 원본 이미지 데이터가 생성된 날짜와 시간. |
| DateTimeDigitized | `36868` | 디지털화된 날짜와 시간. |
| ComponentsConfiguration | `37121` | 구성 요소 설정. |
| CompressedBitsPerPixel | `37122` | 압축된 데이터에 특화되어; 픽셀당 압축 비트를 나타냅니다. |
| ShutterSpeedValue | `37377` | 셔터 속도 값. |
| ApertureValue | `37378` | 렌즈 조리개 값. |
| BrightnessValue | `37379` | 밝기 값. |
| ExposureBiasValue | `37380` | 노출 보정 값. |
| MaxApertureValue | `37381` | 최대 조리개 값. |
| SubjectDistance | `37382` | 피사체까지의 거리(미터). |
| MeteringMode | `37383` | 측광 모드. |
| LightSource | `37384` | 광원 종류. |
| Flash | `37385` | 촬영 시 플래시 상태를 나타냅니다. |
| FocalLength | `37386` | 렌즈의 실제 초점 거리(mm). |
| SubjectArea | `37396` | 이 태그는 전체 장면에서 주요 피사체의 위치와 영역을 나타냅니다. |
| MakerNote | `37500` | Exif 작성기 제조업체가 원하는 정보를 기록하기 위한 태그입니다. 내용은 제조업체에 따라 다르지만, 이 태그는 의도된 목적 외에는 사용해서는 안 됩니다. |
| UserComment | `37510` | Exif 사용자가 ImageDescription에 있는 내용 외에 이미지에 키워드나 주석을 작성하고, ImageDescription 태그의 문자 코드 제한 없이 사용할 수 있는 태그입니다. |
| SubsecTime | `37520` | DateTime 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다. |
| SubsecTimeOriginal | `37521` | DateTimeOriginal 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다. |
| SubsecTimeDigitized | `37522` | DateTimeDigitized 태그의 초 단위 소수를 기록하는 데 사용되는 태그입니다. |
| FlashpixVersion | `40960` | FPXR 파일이 지원하는 Flashpix 포맷 버전. |
| ColorSpace | `40961` | 색 공간 정보 태그(ColorSpace)는 항상 색 공간 지정자로 기록됩니다. |
| RelatedSoundFile | `40964` | 관련 사운드 파일. |
| FlashEnergy | `41483` | 이미지가 촬영될 때의 스트로브 에너지를 Beam Candle Power Seconds(BCPS) 단위로 나타냅니다. |
| SpatialFrequencyResponse | `41484` | 이 태그는 ISO 12233에 명시된 대로 이미지 너비, 높이 및 대각선 방향의 공간 주파수 표와 SFR 값을 카메라 또는 입력 장치에 기록합니다. |
| FocalPlaneXResolution | `41486` | 카메라 초점면의 FocalPlaneResolutionUnit당 이미지 너비(X) 방향 픽셀 수를 나타냅니다. |
| FocalPlaneYResolution | `41487` | 카메라 초점면에서 FocalPlaneResolutionUnit당 이미지 높이(Y) 방향의 픽셀 수를 나타냅니다. |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution 및 FocalPlaneYResolution을 측정하는 단위를 나타냅니다. 이 값은 ResolutionUnit과 동일합니다. |
| SubjectLocation | `41492` | 장면에서 주요 피사체의 위치를 나타냅니다. 이 태그의 값은 Rotation 태그에 따른 회전 처리 이전에 왼쪽 가장자리를 기준으로 주요 피사체 중심에 해당하는 픽셀을 나타냅니다. |
| ExposureIndex | `41493` | 이미지가 촬영될 때 카메라 또는 입력 장치에서 선택된 노출 지수를 나타냅니다. |
| SensingMethod | `41495` | 카메라 또는 입력 장치의 이미지 센서 유형을 나타냅니다. |
| FileSource | `41728` | 파일 소스. |
| SceneType | `41729` | 장면 유형을 나타냅니다. DSC가 이미지를 기록한 경우 이 태그 값은 항상 1로 설정되어 이미지가 직접 촬영되었음을 나타냅니다. |
| CFAPattern | `41730` | 단일 칩 컬러 영역 센서를 사용할 때 이미지 센서의 색 필터 배열(CFA) 기하학적 패턴을 나타냅니다. 모든 감지 방식에 적용되는 것은 아닙니다. |
| CustomRendered | `41985` | 이 태그는 출력에 맞춘 렌더링과 같은 이미지 데이터에 대한 특수 처리를 사용함을 나타냅니다. 특수 처리가 수행될 경우 리더는 추가 처리를 비활성화하거나 최소화해야 합니다. |
| ExposureMode | `41986` | 이 태그는 이미지 촬영 시 설정된 노출 모드를 나타냅니다. 자동 브라케팅 모드에서는 카메라가 동일한 장면을 다양한 노출 설정으로 연속 촬영합니다. |
| WhiteBalance | `41987` | 이 태그는 이미지 촬영 시 설정된 화이트 밸런스 모드를 나타냅니다. |
| DigitalZoomRatio | `41988` | 이 태그는 이미지 촬영 시 디지털 줌 비율을 나타냅니다. 기록된 값의 분자가 0이면 디지털 줌이 사용되지 않았음을 의미합니다. |
| FocalLengthIn35MmFilm | `41989` | 이 태그는 35mm 필름 카메라를 가정한 등가 초점 거리(mm)를 나타냅니다. 값이 0이면 초점 거리를 알 수 없음을 의미합니다. 이 태그는 FocalLength 태그와 다릅니다. |
| SceneCaptureType | `41990` | 이 태그는 촬영된 장면 유형을 나타냅니다. 또한 이미지가 촬영된 모드를 기록하는 데 사용할 수 있습니다. |
| GainControl | `41991` | 이 태그는 전체 이미지 이득 조정 정도를 나타냅니다. |
| Contrast | `41992` | 이 태그는 이미지 촬영 시 카메라가 적용한 대비 처리 방향을 나타냅니다. |
| Saturation | `41993` | 이 태그는 이미지 촬영 시 카메라가 적용한 채도 처리 방향을 나타냅니다. |
| Sharpness | `41994` | 이 태그는 이미지 촬영 시 카메라가 적용한 선명도 처리 방향을 나타냅니다 |
| DeviceSettingDescription | `41995` | 이 태그는 특정 카메라 모델의 촬영 조건에 대한 정보를 나타냅니다. 이 태그는 리더에서 촬영 조건을 표시하는 데만 사용됩니다. |
| SubjectDistanceRange | `41996` | 이 태그는 피사체까지의 거리를 나타냅니다. |
| ImageUniqueID | `42016` | 이미지 고유 ID. |
| GPSVersionID | `0` | GPSInfoIFD의 버전을 나타냅니다. |
| GPSLatitudeRef | `1` | 위도가 북위인지 남위인지를 나타냅니다. |
| GPSLatitude | `2` | 위도를 나타냅니다. 위도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 위도가 도·분·초 형식으로 표현될 경우 일반적인 형식은 dd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 분의 소수점 둘째 자리까지 표시할 경우 형식은 dd/1,mmmm/100,0/1이 됩니다. |
| GPSLongitudeRef | `3` | 경도가 동경인지 서경인지를 나타냅니다. |
| GPSLongitude | `4` | 경도를 나타냅니다. 경도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 경도가 도, 분, 초로 표현되는 경우 일반적인 형식은 ddd/1,mm/1,ss/1 입니다. 도와 분을 사용하고 예를 들어 분의 소수점 이하 두 자리까지 표시하는 경우 형식은 ddd/1,mmmm/100,0/1 입니다. |
| GPSAltitudeRef | `5` | 참조 고도로 사용되는 고도를 나타냅니다. 기준이 해수면이고 고도가 해수면 위에 있으면 0이 제공됩니다. 고도가 해수면 아래에 있으면 값 1이 제공되며 고도는 GPSAltitude 태그에 절대값으로 표시됩니다. |
| GPSAltitude | `6` | GPSAltitudeRef에 있는 기준을 기반으로 고도를 나타냅니다. 고도는 하나의 RATIONAL 값으로 표현됩니다. 기준 단위는 미터입니다. |
| GPSTimestamp | `7` | 시간을 UTC(협정 세계시)로 나타냅니다. TimeStamp는 시, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. |
| GPSSatellites | `8` | 측정에 사용되는 GPS 위성을 나타냅니다. 이 태그는 위성 수, ID 번호, 고도 각, 방위각, SNR 및 기타 정보를 ASCII 표기법으로 설명하는 데 사용할 수 있습니다. 형식은 지정되지 않았습니다. GPS 수신기가 측정을 할 수 없는 경우 태그 값은 NULL로 설정되어야 합니다. |
| GPSStatus | `9` | 이미지가 기록될 때 GPS 수신기의 상태를 나타냅니다. |
| GPSMeasureMode | `10` | GPS 측정 모드를 나타냅니다. - 2차원 또는 3차원. |
| GPSDOP | `11` | GPS DOP(데이터 정밀도)를 나타냅니다. 2차원 측정 시 HDOP 값이 기록되고, 3차원 측정 시 PDOP 값이 기록됩니다. |
| GPSSpeedRef | `12` | GPS 수신기 이동 속도를 표현하는 단위를 나타냅니다. 'K', 'M', 'N'은 각각 시속 킬로미터, 시속 마일, 노트를 의미합니다. |
| GPSSpeed | `13` | GPS 수신기 이동 속도를 나타냅니다. |
| GPSTrackRef | `14` | GPS 수신기 이동 방향을 제공하는 기준을 나타냅니다. 'T'는 진북 방향을, 'M'은 자기 방향을 의미합니다. |
| GPSTrack | `15` | GPS 수신기 이동 방향을 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다. |
| GPSImgDirectionRef | `16` | 이미지가 촬영될 때 이미지 방향을 제공하는 기준을 나타냅니다. 'T'는 진북 방향을, 'M'은 자기 방향을 의미합니다. |
| GPSImgDirection | `17` | 촬영된 이미지의 방향을 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다. |
| GPSMapDatum | `18` | GPS 수신기가 사용하는 측지 조사 데이터를 나타냅니다. |
| GPSDestLatitudeRef | `19` | 목적지의 위도가 북위인지 남위인지를 나타냅니다. ASCII 값 'N'은 북위, 'S'는 남위를 의미합니다. |
| GPSDestLatitude | `20` | 목적지의 위도를 나타냅니다. 위도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 위도가 도, 분, 초로 표현되는 경우 일반적인 형식은 dd/1,mm/1,ss/1 입니다. 도와 분을 사용하고 예를 들어 분의 소수점 이하 두 자리까지 표시하는 경우 형식은 dd/1,mmmm/100,0/1 입니다. |
| GPSDestLongitudeRef | `21` | 목적지의 경도가 동경인지 서경인지를 나타냅니다. ASCII 'E'는 동경, 'W'는 서경을 의미합니다. |
| GPSDestLongitude | `22` | 목적지의 경도를 나타냅니다. 경도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다. 경도가 도, 분, 초로 표현되는 경우 일반적인 형식은 ddd/1,mm/1,ss/1 입니다. 도와 분을 사용하고 예를 들어 분의 소수점 이하 두 자리까지 표시하는 경우 형식은 ddd/1,mmmm/100,0/1 입니다. |
| GPSDestBearingRef | `23` | 목적지에 대한 방위각을 제공하는 기준을 나타냅니다. 'T'는 진북 방향을, 'M'은 자기 방향을 의미합니다. |
| GPSDestBearing | `24` | 목적지에 대한 방위각을 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다. |
| GPSDestDistanceRef | `25` | 목적지까지의 거리를 표현하는 단위를 나타냅니다. 'K', 'M', 'N'은 각각 킬로미터, 마일, 노트를 의미합니다. |
| GPSDestDistance | `26` | 목적지까지의 거리를 나타냅니다. |
| GPSProcessingMethod | `27` | 위치 찾기에 사용된 방법의 이름을 기록하는 문자열입니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며, 그 뒤에 방법 이름이 이어집니다. |
| GPSAreaInformation | `28` | GPS 영역의 이름을 기록하는 문자열입니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며, 그 뒤에 GPS 영역 이름이 이어집니다. |
| GPSDateStamp | `29` | UTC(협정 세계시)를 기준으로 날짜와 시간 정보를 기록하는 문자열입니다. 형식은 YYYY:MM:DD입니다. |
| GPSDifferential | `30` | GPS 수신기에 차동 보정이 적용되는지 여부를 나타냅니다. |
| StripOffsets | `273` | 각 스트립에 대해 해당 스트립의 바이트 오프셋을 나타냅니다. 스트립 바이트 수가 64 Kbytes를 초과하지 않도록 선택하는 것이 권장됩니다. Aux 태그. |
| JPEGInterchangeFormat | `513` | JPEG 압축 썸네일 데이터의 시작 바이트(SOI)까지의 오프셋입니다. 이는 기본 이미지 JPEG 데이터에는 사용되지 않습니다. |
| JPEGInterchangeFormatLength | `514` | JPEG 압축 썸네일 데이터의 바이트 수입니다. 이는 기본 이미지 JPEG 데이터에는 사용되지 않습니다. JPEG 썸네일은 분할되지 않고 SOI부터 EOI까지 연속적인 JPEG 비트스트림으로 기록됩니다. Appn 및 COM 마커는 기록되지 않아야 합니다. 압축 썸네일은 APP1에 기록되는 모든 기타 데이터를 포함하여 64 Kbytes를 초과하지 않도록 기록해야 합니다. |
| ExifIfdPointer | `34665` | Exif IFD에 대한 포인터입니다. 상호 운용성을 위해 Exif IFD는 TIFF에 지정된 IFD와 동일한 구조를 가집니다. 그러나 일반적으로 TIFF와 달리 이미지 데이터를 포함하지 않습니다. |
| GPSIfdPointer | `34853` | GPS IFD 포인터입니다. |
| RowsPerStrip | `278` | 스트립당 행 수입니다. 이미지를 스트립으로 나눌 때 하나의 스트립에 해당하는 이미지 행 수를 나타냅니다. |
| StripByteCounts | `279` | 각 스트립의 총 바이트 수입니다. |
| PixelXDimension | `40962` | 압축 데이터에 특화된 정보입니다. 압축 파일이 기록될 때, 패딩 데이터나 재시작 마커의 유무와 관계없이 의미 있는 이미지의 유효 너비가 이 태그에 기록됩니다. |
| PixelYDimension | `40963` | 압축 데이터에 특화된 정보입니다. 압축 파일이 기록될 때, 의미 있는 이미지의 유효 높이가 이 태그에 기록됩니다. |
| Gamma | `42240` | 감마 값 |
| SensitivityType | `34864` | 사진 감도 유형 |
| StandardOutputSensitivity | `34865` | 카메라의 표준 출력 감도를 나타냅니다. |
| RecommendedExposureIndex | `34866` | 권장 노출 지수를 나타냅니다. |
| ISOSpeed | `34867` | ISO 12232에서 정의된 ISO 속도 값에 대한 정보입니다. |
| ISOSpeedLatitudeYYY | `34868` | 이 태그는 ISO 12232에서 정의된 ISO 속도 위도 yyy 값을 나타냅니다. |
| ISOSpeedLatitudeZZZ | `34869` | 이 태그는 ISO 12232에서 정의된 ISO 속도 위도 zzz 값을 나타냅니다. |
| CameraOwnerName | `42032` | 카메라 소유자 이름을 포함합니다. |
| BodySerialNumber | `42033` | 카메라 본체 일련 번호를 포함합니다. |
| LensMake | `42035` | 이 태그는 렌즈 제조사를 기록합니다. |
| LensModel | `42036` | 이 태그는 렌즈`s 모델 이름과 모델 번호를 기록합니다. |
| LensSerialNumber | `42037` | 이 태그는 교환 가능한 렌즈의 일련 번호를 기록합니다. |
| LensSpecification | `42034` | 이 태그는 최소 초점 거리, 최대 초점 거리, 최소 초점 거리에서의 최소 F값 및 최대 초점 거리에서의 최소 F값을 기록합니다. |

### 또 보기

* namespace [Aspose.PSD.Exif](../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../)


