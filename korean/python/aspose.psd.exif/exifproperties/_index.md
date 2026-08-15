---
title: "ExifProperties 열거형"
type: docs
weight: 160
url: /ko/python-net/aspose.psd.exif/exifproperties/
---

Exif 태그 목록

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifProperties

**Aspose.PSD Version:** 24.12.0

## **Members**
| **멤버 이름** | **설명** |
| :- | :- |
| APERTURE_VALUE | 렌즈 조리개 값. |
| ARTIST | 이 태그는 카메라 소유자, 사진작가 또는 이미지 제작자의 이름을 기록합니다. 자세한 형식은 지정되지 않았지만, 상호 운용성을 위해 아래 예시와 같이 정보를 작성하는 것이 권장됩니다. 필드를 비워두면 알 수 없는 것으로 처리됩니다. 예) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | 이미지 구성 요소당 비트 수입니다. 이 표준에서는 이미지의 각 구성 요소가 8비트이므로, 이 태그의 값은 8입니다. |
| BODY_SERIAL_NUMBER | 카메라 본체 일련 번호를 포함합니다. |
| BRIGHTNESS_VALUE | 밝기 값입니다. |
| CAMERA_OWNER_NAME | 카메라 소유자 이름을 포함합니다. |
| CFA_PATTERN | 이미지 센서가 원칩 컬러 영역 센서를 사용할 때 색 필터 어레이(CFA) 기하학적 패턴을 나타냅니다. 모든 감지 방식에 적용되는 것은 아닙니다. |
| COLOR_SPACE | 색 공간 정보 태그(ColorSpace)는 항상 색 공간 지정자로 기록됩니다. |
| COMPONENTS_CONFIGURATION | 구성 요소 구성을 나타냅니다. |
| COMPRESSED_BITS_PER_PIXEL | 압축 데이터에만 해당되며, 압축된 픽셀당 비트를 나타냅니다. |
| COMPRESSION | 이미지 데이터에 사용된 압축 방식입니다. 기본 이미지가 JPEG 압축된 경우 이 지정은 필요 없으며 생략됩니다. |
| CONTRAST | 이 태그는 촬영 시 카메라에 의해 적용된 대비 처리 방향을 나타냅니다. |
| COPYRIGHT | 저작권 정보. 이 표준에서는 태그가 사진작가와 편집자 저작권을 모두 표시하는 데 사용됩니다.<br/>                사진작가와 편집자 모두의 저작권을 나타내는 저작권 고지이며, 이미지에 대한 권리를 주장하는 개인 또는 조직의 저작권 고지입니다.<br/>                상호 운용성 저작권 문구에는 날짜와 권리가 포함되어 이 필드에 작성되어야 합니다; 예: "Copyright, John Smith, 19xx. All rights<br/>                reserved.". 이 표준에서는 필드가 사진작가와 편집자 저작권을 모두 기록하며, 각각은 문구의 별도 부분에 기록됩니다.<br/>                사진작가와 편집자 저작권 사이에 명확한 구분이 있을 경우, 사진작가 저작권 뒤에 편집자 저작권을 순서대로 작성하고, NULL로 구분합니다(이 경우 문구가 NULL로 끝나므로 NULL 코드가 두 개 있습니다).<br/>                사진작가 저작권만 제공된 경우 하나의 NULL 코드로 종료됩니다. 편집자 저작권만 제공된 경우, 사진작가 저작권 부분은 하나의 공백 뒤에 종료 NULL 코드가 포함되고, 그 뒤에 편집자 저작권이 제공됩니다.<br/>                필드를 비워두면 알 수 없는 것으로 처리됩니다. |
| CUSTOM_RENDERED | 이 태그는 이미지 데이터에 대한 특수 처리(예: 출력에 맞춘 렌더링)의 사용을 나타냅니다. 특수 처리가 수행될 경우, 리더는 추가 처리를 비활성화하거나 최소화해야 합니다. |
| DATE_TIME | 이미지 생성 날짜와 시간입니다. Exif 표준에서는 파일이 변경된 날짜와 시간으로 기록됩니다. |
| DATE_TIME_DIGITIZED | 디지털화된 날짜와 시간입니다. |
| DATE_TIME_ORIGINAL | 원본 이미지 데이터가 생성된 날짜와 시간입니다. |
| DEVICE_SETTING_DESCRIPTION | 이 태그는 특정 카메라 모델의 촬영 조건에 대한 정보를 나타냅니다. 이 태그는 리더에서 촬영 조건을 표시하기 위해서만 사용됩니다. |
| DIGITAL_ZOOM_RATIO | 이 태그는 이미지가 촬영될 때의 디지털 줌 비율을 나타냅니다. 기록된 값의 분자가 0인 경우, 디지털 줌이 사용되지 않았음을 의미합니다. |
| EXIF_IFD_POINTER | Exif IFD에 대한 포인터입니다. 상호 운용성을 위해 Exif IFD는 TIFF에 지정된 IFD와 동일한 구조를 가지고 있습니다. 그러나 일반적으로 TIFF와 달리 이미지 데이터를 포함하지 않습니다. |
| EXIF_VERSION | Exif 버전입니다. |
| EXPOSURE_BIAS_VALUE | 노출 보정 값입니다. |
| EXPOSURE_INDEX | 이미지가 캡처될 때 카메라 또는 입력 장치에서 선택된 노출 지수를 나타냅니다. |
| EXPOSURE_MODE | 이 태그는 이미지가 촬영될 때 설정된 노출 모드를 나타냅니다. 자동 브라케팅 모드에서는 카메라가 동일한 장면을 서로 다른 노출 설정으로 여러 프레임 촬영합니다. |
| EXPOSURE_PROGRAM | 사진을 촬영할 때 카메라가 노출을 설정하는 데 사용하는 프로그램의 클래스입니다. |
| EXPOSURE_TIME | 노출 시간(초 단위)입니다. |
| FILE_SOURCE | 파일 소스입니다. |
| FLASH | 플래시 상태를 나타냅니다. |
| FLASHPIX_VERSION | FPXR 파일이 지원하는 Flashpix 형식 버전입니다. |
| FLASH_ENERGY | 이미지가 촬영될 때의 스트로브 에너지를 Beam Candle Power Seconds(BCPS) 단위로 나타냅니다. |
| FOCAL_LENGTH | 렌즈의 실제 초점 거리(mm)입니다. |
| FOCAL_LENGTH_IN_35_MM_FILM | 이 태그는 35mm 필름 카메라를 가정한 등가 초점 거리를 mm 단위로 나타냅니다. 값이 0이면 초점 거리를 알 수 없습니다. 이 태그는 FocalLength 태그와 다릅니다. |
| FOCAL_PLANE_RESOLUTION_UNIT | FocalPlaneXResolution 및 FocalPlaneYResolution을 측정하는 단위를 나타냅니다. 이 값은 ResolutionUnit과 동일합니다. |
| FOCAL_PLANE_X_RESOLUTION | 카메라 초점면에서 FocalPlaneResolutionUnit당 이미지 너비(X) 방향의 픽셀 수를 나타냅니다. |
| FOCAL_PLANE_Y_RESOLUTION | 카메라 초점면에서 FocalPlaneResolutionUnit당 이미지 높이(Y) 방향의 픽셀 수를 나타냅니다. |
| F_NUMBER | F 번호입니다. |
| GAIN_CONTROL | 이 태그는 전체 이미지 게인 조정 정도를 나타냅니다. |
| GAMMA | 감마 값 |
| GPSDOP | GPS DOP(데이터 정밀도)를 나타냅니다. 2차원 측정 시 HDOP 값이 기록되고,<br/>                3차원 측정 시 PDOP 값이 기록됩니다. |
| GPS_ALTITUDE | GPSAltitudeRef에 따른 고도를 나타냅니다. 고도는 하나의 RATIONAL 값으로 표현됩니다.<br/>                기준 단위는 미터입니다. |
| GPS_ALTITUDE_REF | 참조 고도로 사용되는 고도를 나타냅니다. 기준이 해수면이고 고도가 해수면 위에 있으면,<br/>                0이 지정됩니다. 고도가 해수면 아래이면 값 1이 지정되고 고도는 GPSAltitude 태그에 절대값으로 표시됩니다. |
| GPS_AREA_INFORMATION | GPS 영역 이름을 기록하는 문자열입니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며, 그 뒤에 GPS 영역 이름이 이어집니다.<br/>                 |
| GPS_DATE_STAMP | UTC에 상대적인 날짜 및 시간 정보를 기록하는 문자열입니다.<br/>                (Coordinated Universal Time). 형식은 YYYY:MM:DD입니다. |
| GPS_DEST_BEARING | 목적지까지의 방위를 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다. |
| GPS_DEST_BEARING_REF | 목적지까지의 방위를 제공하는 데 사용되는 기준을 나타냅니다. 'T'는 진방위를 의미하고 'M'은<br/>                자기방위를 의미합니다. |
| GPS_DEST_DISTANCE | 목적지까지의 거리를 나타냅니다. |
| GPS_DEST_DISTANCE_REF | 목적지까지의 거리를 표현하는 데 사용되는 단위를 나타냅니다. 'K', 'M', 'N'은 각각 킬로미터, 마일<br/>                및 노트를 나타냅니다. |
| GPS_DEST_LATITUDE | 목적지의 위도를 나타냅니다. 위도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다.<br/>                위도가 도·분·초로 표현되는 경우 일반적인 형식은 dd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 분의 소수점 둘째 자리까지 표시하는 경우 형식은 dd/1,mmmm/100,0/1이 됩니다. |
| GPS_DEST_LATITUDE_REF | 목적지 위도가 북위인지 남위인지를 나타냅니다. ASCII 값 'N'은 북위를, <br/>                'S'는 남위를 나타냅니다. |
| GPS_DEST_LONGITUDE | 목적지의 경도를 나타냅니다. 경도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다.<br/>                경도가 도·분·초로 표현되는 경우 일반적인 형식은 ddd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 분의 소수점 둘째 자리까지 표시하는 경우 형식은 ddd/1,mmmm/100,0/1이 됩니다. |
| GPS_DEST_LONGITUDE_REF | 목적지의 경도가 동경인지 서경인지를 나타냅니다. ASCII 'E'는 동경을, <br/>                'W'는 서경을 나타냅니다. |
| GPS_DIFFERENTIAL | GPS 수신기에 차동 보정이 적용되는지 여부를 나타냅니다. |
| GPS_IFD_POINTER | gps ifd 포인터입니다. |
| GPS_IMG_DIRECTION | 이미지가 촬영될 때의 방향을 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다. |
| GPS_IMG_DIRECTION_REF | 이미지가 캡처될 때 방향을 제공하기 위한 기준을 나타냅니다. 'T'는 실제 방향을 의미하고 'M'은<br/>                자기 방향을 의미합니다. |
| GPS_LATITUDE | 위도를 나타냅니다. 위도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다.<br/>                위도가 도·분·초로 표현되는 경우 일반적인 형식은 dd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 분의 소수점 둘째 자리까지 표시하는 경우 형식은 dd/1,mmmm/100,0/1이 됩니다. |
| GPS_LATITUDE_REF | 위도가 북위인지 남위인지를 나타냅니다. |
| GPS_LONGITUDE | 경도를 나타냅니다. 경도는 각각 도, 분, 초를 나타내는 세 개의 RATIONAL 값으로 표현됩니다.<br/>                경도가 도·분·초로 표현되는 경우 일반적인 형식은 ddd/1,mm/1,ss/1입니다. 도와 분만 사용하고 예를 들어 분의 소수점 둘째 자리까지 표시하는 경우 형식은 ddd/1,mmmm/100,0/1이 됩니다. |
| GPS_LONGITUDE_REF | 경도가 동경인지 서경인지를 나타냅니다. |
| GPS_MAP_DATUM | GPS 수신기가 사용하는 측지 조사 데이터를 나타냅니다. |
| GPS_MEASURE_MODE | GPS 측정 모드를 나타냅니다. - 2차원 또는 3차원. |
| GPS_PROCESSING_METHOD | 위치 찾기에 사용된 방법의 이름을 기록하는 문자열입니다.<br/>                첫 번째 바이트는 사용된 문자 코드를 나타내며, 그 뒤에 방법의 이름이 이어집니다. |
| GPS_SATELLITES | 측정을 위해 사용된 GPS 위성을 나타냅니다. 이 태그는 위성 수, 위성 ID, 고도 각, 방위, SNR 및 기타 정보를 ASCII 표기법으로 설명하는 데 사용할 수 있습니다. 형식은 지정되지 않았습니다. GPS 수신기가 측정을 수행할 수 없을 경우, 태그 값은 NULL로 설정되어야 합니다. |
| GPS_SPEED | GPS 수신기 이동 속도를 나타냅니다. |
| GPS_SPEED_REF | GPS 수신기 이동 속도를 표현하는 단위를 나타냅니다. 'K' 'M' 및 'N'은 각각 킬로미터/시간,<br/>                마일/시간 및 노트를 나타냅니다. |
| GPS_STATUS | 이미지가 기록될 때 GPS 수신기의 상태를 나타냅니다. |
| GPS_TIMESTAMP | 시간을 UTC(협정 세계시)로 표시합니다. 타임스탬프는 세 개의 RATIONAL 값으로 표현되며,<br/>                시, 분 및 초를 제공합니다. |
| GPS_TRACK | GPS 수신기 움직임의 방향을 나타냅니다. 값의 범위는 0.00에서 359.99까지입니다. |
| GPS_TRACK_REF | GPS 수신기 움직임의 방향을 제공하기 위한 기준을 나타냅니다. 'T'는 진짜 방향을, 'M'은<br/>                자기 방향을 의미합니다. |
| GPS_VERSION_ID | GPSInfoIFD의 버전을 나타냅니다. |
| IMAGE_DESCRIPTION | 이미지의 제목을 제공하는 문자열입니다. "1988 company picnic"와 같은 주석일 수 있습니다. |
| IMAGE_LENGTH | 이미지 데이터의 행 수입니다. |
| IMAGE_UNIQUE_ID | 이미지 고유 ID입니다. |
| IMAGE_WIDTH | 이미지 데이터의 열 수이며, 행당 픽셀 수와 같습니다. |
| ISO_SPEED | ISO 12232에 정의된 ISO 속도 값에 대한 정보입니다. |
| ISO_SPEED_LATITUDE_YYY | 이 태그는 ISO 12232에 정의된 ISO 속도 위도 yyy 값을 나타냅니다. |
| ISO_SPEED_LATITUDE_ZZZ | 이 태그는 ISO 12232에 정의된 ISO 속도 위도 zzz 값을 나타냅니다. |
| JPEG_INTERCHANGE_FORMAT | JPEG 압축 썸네일 데이터의 시작 바이트(SOI)까지의 오프셋입니다. 이는 기본 이미지 JPEG 데이터에는 사용되지 않습니다. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | JPEG 압축 썸네일 데이터의 바이트 수입니다. 이는 기본 이미지 JPEG 데이터에는 사용되지 않습니다. JPEG 썸네일은 분할되지 않고 SOI부터 EOI까지 연속적인 JPEG 비트스트림으로 기록됩니다. Appn 및 COM 마커는 기록되지 않아야 합니다. 압축된 썸네일은 APP1에 기록될 모든 다른 데이터를 포함하여 64KB를 초과하지 않도록 기록되어야 합니다. |
| LENS_MAKE | 이 태그는 렌즈 제조사를 기록합니다. |
| LENS_MODEL | 이 태그는 렌즈의 모델 이름과 모델 번호를 기록합니다. |
| LENS_SERIAL_NUMBER | 이 태그는 교환 가능한 렌즈의 일련 번호를 기록합니다. |
| LENS_SPECIFICATION | 이 태그는 최소 초점 거리, 최대 초점 거리, 최소 초점 거리에서의 최소 F값 및 최대 초점 거리에서의 최소 F값을 기록합니다. |
| LIGHT_SOURCE | 광원 종류. |
| MAKE | 녹화 장비의 제조사입니다. 이는 이미지 생성 장비인 DSC, 스캐너, 비디오 디지털 변환기 또는 기타 장비의 제조사를 의미합니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| MAKER_NOTE | Exif 작성자 제조업체가 원하는 정보를 기록하기 위한 태그입니다. 내용은 제조업체에 따라 다르지만, 이 태그는 의도된 목적 이외에는 사용되지 않아야 합니다. |
| MAX_APERTURE_VALUE | 최대 조리개 값. |
| METERING_MODE | 측광 모드. |
| MODEL | 장비의 모델명 또는 모델 번호입니다. 이는 이미지 생성 장비인 DSC, 스캐너, 비디오 디지털 변환기 또는 기타 장비의 모델명 또는 번호를 의미합니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| OECF | ISO 14524에 명시된 광전 변환 함수(OECF)를 나타냅니다. |
| ORIENTATION | 행과 열 기준으로 본 이미지 방향. |
| PHOTOGRAPHIC_SENSITIVITY | ISO 12232에 명시된 카메라 또는 입력 장치의 ISO 속도와 ISO 범위를 나타냅니다. |
| PHOTOMETRIC_INTERPRETATION | 픽셀 구성. |
| PIXEL_X_DIMENSION | 압축 데이터에 대한 정보입니다. 압축 파일이 기록될 때, 패딩 데이터나 재시작 마커의 존재 여부와 관계없이 의미 있는 이미지의 유효 너비를 이 태그에 기록해야 합니다. |
| PIXEL_Y_DIMENSION | 압축 데이터에 대한 정보입니다. 압축 파일이 기록될 때, 의미 있는 이미지의 유효 높이를 이 태그에 기록해야 합니다. |
| PLANAR_CONFIGURATION | 픽셀 구성 요소가 청키(Chunky) 형식 또는 플래너(Planar) 형식으로 기록되는지 여부를 나타냅니다. 이 필드가 없으면 TIFF 기본값인 1(청키)이 가정됩니다. |
| PRIMARY_CHROMATICITIES | 이미지의 세 기본 색상의 색도입니다. 일반적으로 이 태그는 필요하지 않으며, 색 공간은 색 공간 정보인 ColorSpace 태그에 지정됩니다. |
| RECOMMENDED_EXPOSURE_INDEX | 권장 노출 지수를 나타냅니다. |
| REFERENCE_BLACK_WHITE | 참조 검은점 값과 참조 흰점 값<br/>                TIFF에서는 기본값이 제공되지 않지만, 아래 값이 여기서 기본값으로 제공됩니다.<br/>                색 공간은<br/>                색 공간 정보 태그에 선언되며, 기본값은<br/>                최적의 이미지 특성을 제공하는 값이며<br/>                이러한 조건의 상호 운용성을 의미합니다 |
| RELATED_SOUND_FILE | 관련 사운드 파일입니다. |
| RESOLUTION_UNIT | XResolution 및 YResolution을 측정하는 단위입니다. XResolution과 YResolution 모두 동일한 단위가 사용됩니다. 이미지 해상도가 알려지지 않은 경우 2(인치)로 지정됩니다. |
| ROWS_PER_STRIP | 스트립당 행 수입니다. 이미지를 스트립으로 나눌 때 하나의 스트립에 해당하는 이미지의 행 수를 나타냅니다. |
| SAMPLES_PER_PIXEL | 픽셀당 구성 요소 수입니다. 이 표준은 RGB 및 YCbCr 이미지에 적용되므로 이 태그에 설정된 값은 3입니다. |
| SATURATION | 이 태그는 이미지 촬영 시 카메라에 의해 적용된 채도 처리 방향을 나타냅니다. |
| SCENE_CAPTURE_TYPE | 이 태그는 촬영된 장면의 유형을 나타냅니다. 또한 이미지가 촬영된 모드를 기록하는 데 사용할 수 있습니다. |
| SCENE_TYPE | 장면의 유형을 나타냅니다. DSC가 이미지를 기록한 경우, 이 태그 값은 항상 1로 설정되어 이미지가 직접 촬영되었음을 나타냅니다. |
| SENSING_METHOD | 카메라 또는 입력 장치의 이미지 센서 유형을 나타냅니다. |
| SENSITIVITY_TYPE | 사진 감도의 유형 |
| SHARPNESS | 이 태그는 이미지 촬영 시 카메라에 의해 적용된 선명도 처리 방향을 나타냅니다. |
| SHUTTER_SPEED_VALUE | 셔터 속도 값입니다. |
| SOFTWARE | 이 태그는 이미지를 생성하는 데 사용된 카메라 또는 이미지 입력 장치의 소프트웨어 또는 펌웨어의 이름과 버전을 기록합니다. 자세한 형식은 지정되지 않았지만, 아래 예시를 따르는 것이 권장됩니다. 필드가 비어 있으면 알 수 없는 것으로 처리됩니다. |
| SPATIAL_FREQUENCY_RESPONSE | 이 태그는 ISO 12233에 지정된 대로 이미지 너비, 이미지 높이 및 대각선 방향에서 카메라 또는 입력 장치의 공간 주파수 표와 SFR 값을 기록합니다. |
| SPECTRAL_SENSITIVITY | 사용된 카메라의 각 채널에 대한 스펙트럼 감도를 나타냅니다. |
| STANDARD_OUTPUT_SENSITIVITY | 카메라의 표준 출력 감도를 나타냅니다. |
| STRIP_BYTE_COUNTS | 각 스트립의 총 바이트 수입니다. |
| STRIP_OFFSETS | 각 스트립에 대해 해당 스트립의 바이트 오프셋을 지정합니다. 스트립 바이트 수가 64KB를 초과하지 않도록 선택하는 것이 권장됩니다.<br/>                Aux 태그. |
| SUBJECT_AREA | 이 태그는 전체 장면에서 주요 피사체의 위치와 영역을 나타냅니다. |
| SUBJECT_DISTANCE | 피사체까지의 거리를 미터 단위로 나타냅니다. |
| SUBJECT_DISTANCE_RANGE | 이 태그는 피사체까지의 거리를 나타냅니다. |
| SUBJECT_LOCATION | 장면에서 주요 피사체의 위치를 나타냅니다. 이 태그의 값은 회전 태그에 따라 회전 처리 이전에 왼쪽 가장자리 기준으로 주요 피사체 중심에 해당하는 픽셀을 나타냅니다. |
| SUBSEC_TIME | DateTime 태그의 초 단위 소수 부분을 기록하는 데 사용되는 태그입니다. |
| SUBSEC_TIME_DIGITIZED | DateTimeDigitized 태그의 초 단위 소수 부분을 기록하는 데 사용되는 태그입니다. |
| SUBSEC_TIME_ORIGINAL | DateTimeOriginal 태그의 초 단위 소수 부분을 기록하는 데 사용되는 태그입니다. |
| TRANSFER_FUNCTION | 이미지에 대한 전송 함수이며 표 형식으로 설명됩니다. 일반적으로 색 공간이 색 공간 정보인 ColorSpace 태그에 지정되어 있기 때문에 이 태그는 필요하지 않습니다. |
| USER_COMMENT | Exif 사용자가 ImageDescription에 있는 내용 외에 이미지에 키워드나 주석을 작성할 수 있도록 하는 태그이며, ImageDescription 태그의 문자 코드 제한을 받지 않습니다. |
| WHITE_BALANCE | 이 태그는 이미지가 촬영될 때 설정된 화이트 밸런스 모드를 나타냅니다. |
| WHITE_POINT | 이미지의 화이트 포인트 색도입니다. 일반적으로 이 태그는 필요하지 않으며, 색 공간은 색공간 정보인 ColorSpace 태그에 지정됩니다. |
| X_RESOLUTION | ImageWidth 방향의 ResolutionUnit당 픽셀 수입니다. 이미지 해상도를 알 수 없을 경우 72 [dpi]가 지정됩니다. |
| Y_CB_CR_COEFFICIENTS | RGB에서 YCbCr 이미지 데이터로 변환하기 위한 행렬 계수입니다. |
| Y_CB_CR_POSITIONING | 크로미넌스 구성 요소가 휘도 구성 요소와 상대적인 위치입니다.<br/>                이 필드는 JPEG 압축 데이터 또는 비압축 YCbCr 데이터에만 지정됩니다. TIFF<br/>                기본값은 1(중심)이며, Y:Cb:Cr = 4:2:2인 경우 이 표준에서는 데이터 기록에 2(동시 배치)를 사용하도록 권장합니다. 이는 TV 시스템에서 볼 때 이미지 품질을 향상시키기 위함입니다. 이 필드가 존재하지 않을 경우, 리더는 TIFF 기본값을 가정해야 합니다. Y:Cb:Cr = 4:2:0인 경우, TIFF 기본값(중심)이 권장됩니다. 리더가 두 종류의 YCbCrPositioning을 모두 지원할 능력이 없으면, 이 필드의 값과 관계없이 TIFF 기본값을 따라야 합니다. 리더가 \"<br/>                중심 및 동시 배치 위치를 모두 지원할 수 있으면 좋습니다. |
| Y_CB_CR_SUB_SAMPLING | 휘도 구성 요소에 대한 크로미넌스 구성 요소의 샘플링 비율입니다. |
| Y_RESOLUTION | ImageLength 방향의 ResolutionUnit당 픽셀 수입니다. XResolution과 동일한 값이 지정됩니다. |
