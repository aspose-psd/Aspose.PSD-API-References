---
title: "JpegExifData 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | 새 인스턴스를 초기화합니다 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 클래스. |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | 배열의 데이터로 새 인스턴스를 초기화합니다 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 클래스. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | 배열의 데이터로 새 인스턴스를 초기화합니다 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | 허용되는 최대 EXIF 세그먼트 크기(바이트). |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 조리개 값을 가져오거나 설정합니다. |
| artist | 문자열 | r/w | 아티스트를 가져오거나 설정합니다. |
| bits_per_sample | ushort | r/w | 샘플당 비트를 가져오거나 설정합니다. |
| body_serial_number | 문자열 | r/w | 카메라 본체 일련 번호를 가져오거나 설정합니다. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 밝기 값을 가져오거나 설정합니다. |
| camera_owner_name | 문자열 | r/w | 카메라 소유자 이름을 가져오거나 설정합니다. |
| cfa_pattern | byte | r/w | CFA 패턴을 가져오거나 설정합니다. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | 색 공간을 가져오거나 설정합니다. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 공통 섹션에 속하는 태그를 가져오거나 설정합니다. 이는 jpeg 이미지에만 적용되며, tiff 형식에서는 대신 tiffOptions가 사용됩니다. |
| components_configuration | byte | r/w | 구성 요소 구성을 가져오거나 설정합니다. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 픽셀당 압축 비트를 가져오거나 설정합니다. |
| compression | ushort | r/w | 압축을 가져오거나 설정합니다. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | 대비를 가져오거나 설정합니다. |
| copyright | 문자열 | r/w | 저작권 정보를 가져오거나 설정합니다. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | 사용자 정의 렌더링을 가져오거나 설정합니다. |
| date_time | 문자열 | r/w | 날짜 및 시간을 가져오거나 설정합니다. |
| date_time_digitized | 문자열 | r/w | 디지털화된 날짜 및 시간을 가져오거나 설정합니다. |
| date_time_original | 문자열 | r/w | 원본 날짜 및 시간을 가져오거나 설정합니다. |
| device_setting_description | byte | r/w | 장치 설정 설명을 가져오거나 설정합니다. |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 디지털 줌 비율을 가져오거나 설정합니다. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | EXIF 섹션에만 해당하는 태그를 가져오거나 설정합니다. |
| exif_version | byte | r/w | EXIF 버전을 가져오거나 설정합니다. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 노출 보정 값을 가져오거나 설정합니다. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 노출 인덱스를 가져오거나 설정합니다. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | 노출 모드를 가져오거나 설정합니다. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | 노출 프로그램을 가져오거나 설정합니다. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 노출 시간을 가져오거나 설정합니다. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | F-넘버를 가져오거나 설정합니다. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | 파일 소스 유형을 가져오거나 설정합니다. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | 플래시를 가져오거나 설정합니다. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 플래시 에너지를 가져오거나 설정합니다. |
| flashpix_version | byte | r/w | 플래시 픽스 버전을 가져오거나 설정합니다. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 초점 거리를 가져오거나 설정합니다. |
| focal_length_in_35_mm_film | ushort | r/w | 35mm 필름에서 초점 거리를 가져오거나 설정합니다. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | 초점면 해상도 단위를 가져오거나 설정합니다. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 초점면 X 해상도를 가져오거나 설정합니다. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 초점면 Y 해상도를 가져오거나 설정합니다. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | 전체 이미지 이득 조정 정도를 가져오거나 설정합니다. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 감마를 가져오거나 설정합니다. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 고도를 가져오거나 설정합니다. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | 참조 고도로 사용되는 GPS 고도를 가져오거나 설정합니다. |
| gps_area_information | byte | r/w | GPS 영역 정보를 가져오거나 설정합니다. |
| gps_date_stamp | 문자열 | r/w | UTC(협정 세계시)와 관련된 날짜 및 시간 정보를 기록하는 GPS 문자열을 가져오거나 설정합니다. |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 목적지에 대한 GPS 방위를 가져오거나 설정합니다. |
| gps_dest_bearing_ref | 문자열 | r/w | 목적지에 대한 방위를 제공하는 데 사용되는 GPS 기준을 가져오거나 설정합니다. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 목적지까지의 GPS 거리를 가져오거나 설정합니다. |
| gps_dest_distance_ref | 문자열 | r/w | 목적지까지의 거리를 나타내는 데 사용되는 GPS 단위를 가져오거나 설정합니다. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 목적지의 GPS 위도를 가져오거나 설정합니다. |
| gps_dest_latitude_ref | 문자열 | r/w | 목적지 위도가 북위인지 남위인지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 목적지의 GPS 경도를 가져오거나 설정합니다. |
| gps_dest_longitude_ref | 문자열 | r/w | 목적지 경도가 동경인지 서경인지를 나타내는 GPS 값을 가져오거나 설정합니다. |
| gps_differential | ushort | r/w | GPS 수신기에 차동 보정이 적용되는지 여부를 나타내는 GPS 값을 가져오거나 설정합니다. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 이미지가 촬영될 때의 GPS 방향을 가져오거나 설정합니다. |
| gps_img_direction_ref | 문자열 | r/w | 이미지가 촬영될 때 방향을 제공하기 위한 GPS 기준을 가져오거나 설정합니다. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 위도를 가져오거나 설정합니다. |
| gps_latitude_ref | 문자열 | r/w | GPS 위도가 북위인지 남위인지를 가져오거나 설정합니다. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 경도를 가져오거나 설정합니다. |
| gps_longitude_ref | 문자열 | r/w | GPS 경도가 동경인지 서경인지를 가져오거나 설정합니다. |
| gps_map_datum | 문자열 | r/w | GPS 수신기에서 사용하는 GPS 측지 조사 데이터를 가져오거나 설정합니다. |
| gps_measure_mode | 문자열 | r/w | GPS 측정 모드를 가져오거나 설정합니다. |
| gps_processing_method | byte | r/w | 위치 찾기에 사용된 방법의 이름을 기록하는 GPS 문자열을 가져오거나 설정합니다. |
| gps_satellites | 문자열 | r/w | 측정에 사용되는 GPS 위성을 가져오거나 설정합니다. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 수신기 이동 속도를 가져오거나 설정합니다. |
| gps_speed_ref | 문자열 | r/w | GPS 수신기 이동 속도를 표현하는 단위를 가져오거나 설정합니다. |
| gps_status | 문자열 | r/w | 이미지가 기록될 때 GPS 수신기의 상태를 가져오거나 설정합니다. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | GPS 섹션에만 해당되는 태그를 가져오거나 설정합니다. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 시간을 UTC(협정 세계시)로 가져오거나 설정합니다. |
| gps_track | 문자열 | r/w | GPS 수신기 움직임의 방향을 가져오거나 설정합니다. |
| gps_track_ref | 문자열 | r/w | GPS 수신기 움직임의 방향을 제공하기 위한 기준을 가져오거나 설정합니다. |
| gps_version_id | byte | r/w | GPS 버전 식별자를 가져오거나 설정합니다. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS DOP(데이터 정밀도)를 가져오거나 설정합니다. |
| image_description | 문자열 | r/w | 이미지 설명을 가져오거나 설정합니다. |
| image_length | uint | r/w | 이미지 길이를 가져오거나 설정합니다. |
| image_unique_id | 문자열 | r/w | 이미지 고유 식별자를 가져오거나 설정합니다. |
| image_width | uint | r/w | 이미지 너비를 가져오거나 설정합니다. |
| is_big_endian | bool | r/w | 스트림 EXIF 데이터가 빅 엔디언인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| iso_speed | uint | r/w | ISO 속도를 가져오거나 설정합니다. |
| iso_speed_latitude_yyy | uint | r/w | ISO 12232에 정의된 카메라 또는 입력 장치의 ISO 속도 위도 yyy 값을 가져오거나 설정합니다. |
| iso_speed_latitude_zzz | uint | r/w | ISO 12232에 정의된 카메라 또는 입력 장치의 ISO 속도 위도 zzz 값을 가져오거나 설정합니다. |
| lens_make | 문자열 | r/w | 렌즈 제조사를 가져오거나 설정합니다. |
| lens_model | 문자열 | r/w | 렌즈 모델을 가져오거나 설정합니다. |
| lens_serial_number | 문자열 | r/w | 렌즈 일련 번호를 가져오거나 설정합니다. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 렌즈 사양을 가져오거나 설정합니다. |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | 조명 소스를 가져오거나 설정합니다. |
| 제조사 | 문자열 | r/w | 녹음 장비의 제조업체를 가져오거나 설정합니다. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | 제조업체 메모 데이터를 가져옵니다. |
| maker_note_raw_data | byte | r/w | 제조업체 메모 원시 데이터를 가져오거나 설정합니다. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 최대 조리개 값을 가져오거나 설정합니다. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | 노출 측정 모드를 가져오거나 설정합니다. |
| 모델 | 문자열 | r/w | 모델을 가져오거나 설정합니다. |
| oecf | byte | r/w | ISO 14524에 지정된 광전 변환 함수(OECF)를 가져오거나 설정합니다. |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | 방향을 가져오거나 설정합니다. |
| photographic_sensitivity | uint | r/w | 사진 감도를 가져오거나 설정합니다. |
| photometric_interpretation | ushort | r/w | 광도 해석을 가져오거나 설정합니다. |
| pixel_x_dimension | uint | r/w | 픽셀 X 차원을 가져오거나 설정합니다. |
| pixel_y_dimension | uint | r/w | 픽셀 Y 차원을 가져오거나 설정합니다. |
| planar_configuration | ushort | r/w | 플래너 구성을 가져오거나 설정합니다. |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 이미지의 세 기본 색상의 색채도를 가져오거나 설정합니다. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 공통 및 GPS 태그를 포함한 모든 EXIF 태그를 가져오거나 설정합니다. |
| recommended_exposure_index | uint | r/w | 권장 노출 지수를 가져오거나 설정합니다. |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 참조 검은색 및 흰색을 가져오거나 설정합니다. |
| related_sound_file | 문자열 | r/w | 관련 사운드 파일을 가져오거나 설정합니다. |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | 해상도 단위를 가져오거나 설정합니다. |
| samples_per_pixel | ushort | r/w | 픽셀당 샘플을 가져오거나 설정합니다. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | 채도를 가져오거나 설정합니다. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | 장면 캡처 유형을 가져오거나 설정합니다. |
| scene_type | byte | r/w | 장면 유형을 가져오거나 설정합니다. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | 감지 방식을 가져오거나 설정합니다. |
| sensitivity_type | ushort | r/w | 감도 유형을 가져오거나 설정합니다. |
| 선명도 | ushort | r/w | 선명도를 가져오거나 설정합니다. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 셔터 속도 값을 가져오거나 설정합니다. |
| 소프트웨어 | 문자열 | r/w | 소프트웨어를 가져오거나 설정합니다. |
| 공간_주파수_응답 | byte | r/w | 공간 주파수 응답을 가져오거나 설정합니다. |
| 스펙트럼_감도 | 문자열 | r/w | 스펙트럼 감도를 가져오거나 설정합니다. |
| 표준_출력_감도 | uint | r/w | 표준 출력 감도를 가져오거나 설정합니다 |
| 피사체_영역 | ushort | r/w | 피사체 영역을 가져오거나 설정합니다. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 피사체 거리를 가져오거나 설정합니다. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | 피사체 거리 범위를 가져오거나 설정합니다. |
| 피사체_위치 | ushort | r/w | 피사체 위치를 가져오거나 설정합니다. |
| subsec_time | 문자열 | r/w | DateTime 태그의 초 단위 소수를 가져오거나 설정합니다. |
| subsec_time_digitized | 문자열 | r/w | DateTimeDigitized 태그의 초 단위 소수를 가져오거나 설정합니다. |
| subsec_time_original | 문자열 | r/w | DateTimeOriginal 태그의 초 단위 소수를 가져오거나 설정합니다. |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | 썸네일 이미지를 가져오거나 설정합니다. |
| transfer_function | ushort | r/w | 전송 함수를 가져오거나 설정합니다. |
| user_comment | 문자열 | r/w | 사용자 댓글을 가져오거나 설정합니다. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | 화이트 밸런스를 가져오거나 설정합니다. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 이미지의 화이트 포인트 색도 값을 가져오거나 설정합니다. |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x 해상도를 가져오거나 설정합니다. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | RGB에서 YCbCr 이미지 데이터로 변환하기 위한 행렬 계수를 가져오거나 설정합니다. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | 휘도 성분에 대한 색차 성분의 위치를 가져오거나 설정합니다. |
| y_cb_cr_sub_sampling | ushort | r/w | 휘도 성분에 대한 색차 성분의 샘플링 비율을 가져오거나 설정합니다. |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y 해상도를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | 컨테이너에서 태그 제거 |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | 컨테이너에서 태그 제거 |
| [serialize_exif_data()](#serialize_exif_data__3) | EXIF 데이터를 직렬화합니다. 태그 값과 내용을 기록합니다. 가장 큰 영향을 주는 크기 태그는 썸네일 태그 내용입니다. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

새 인스턴스를 초기화합니다 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 클래스.

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

배열의 데이터로 새 인스턴스를 초기화합니다 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 공통 태그. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | EXIF 태그. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | GPS 태그. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

배열의 데이터로 새 인스턴스를 초기화합니다 [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 공통 및 GPS 태그와 함께하는 EXIF 태그 배열. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

컨테이너에서 태그 제거

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | 제거할 태그 |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

컨테이너에서 태그 제거

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tag_id | ushort | 제거할 태그 식별자. |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

EXIF 데이터를 직렬화합니다. 태그 값과 내용을 기록합니다. 가장 큰 영향을 주는 크기 태그는 썸네일 태그 내용입니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | 직렬화된 EXIF 데이터. |


