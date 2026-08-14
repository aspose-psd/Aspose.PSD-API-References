---
title: "ExifData クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ExifData()](#ExifData__1) | 新しい [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) クラスのインスタンスを初期化します。 |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | 配列からのデータを使用して新しい [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) クラスのインスタンスを初期化します。 |
| [ExifData(exifdata)](#ExifData_exifdata_3) | 配列からのデータを使用して新しい [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 絞り値を取得または設定します。 |
| body_serial_number | string | r/w | カメラ本体のシリアル番号を取得または設定します。 |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 明るさの値を取得または設定します。 |
| camera_owner_name | string | r/w | カメラ所有者の名前を取得または設定します。 |
| cfa_pattern | byte | r/w | CFA パターンを取得または設定します。 |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | 色空間を取得または設定します。 |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 共通セクションに属するタグを取得または設定します。これは jpeg 画像にのみ適用され、tiff 形式では代わりに tiffOptions が使用されます。 |
| components_configuration | byte | r/w | コンポーネントの構成を取得または設定します。 |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | ピクセルあたりの圧縮ビット数を取得または設定します。 |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | コントラストを取得または設定します。 |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | カスタムレンダリングを取得または設定します。 |
| date_time_digitized | string | r/w | デジタル化された日時を取得または設定します。 |
| date_time_original | string | r/w | 元の日時を取得または設定します。 |
| device_setting_description | byte | r/w | デバイス設定の説明を取得または設定します |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | デジタルズーム比率を取得または設定します。 |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | EXIF セクションにのみ属するタグを取得または設定します。 |
| exif_version | byte | r/w | EXIF バージョンを取得または設定します。 |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | 露出補正値を取得または設定します。 |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 露出インデックスを取得または設定します。 |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | 露出モードを取得または設定します。 |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | 露出プログラムを取得または設定します。 |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 露出時間を取得または設定します。 |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | F値を取得または設定します。 |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | ファイルソースタイプを取得または設定します。 |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | フラッシュを取得または設定します。 |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | フラッシュエネルギーを取得または設定します。 |
| flashpix_version | byte | r/w | FlashPix バージョンを取得または設定します。 |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 焦点距離を取得または設定します。 |
| focal_length_in_35_mm_film | ushort | r/w | 35mmフィルムにおける焦点距離を取得または設定します。 |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | 焦点面解像度の単位を取得または設定します。 |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 焦点面のX解像度を取得または設定します。 |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 焦点面のY解像度を取得または設定します。 |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | 全体画像ゲイン調整の度合いを取得または設定します。 |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | ガンマを取得または設定します。 |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS高度を取得または設定します。 |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | 基準高度として使用されるGPS高度を取得または設定します。 |
| gps_area_information | byte | r/w | GPSエリア情報を取得または設定します。 |
| gps_date_stamp | string | r/w | UTC（協定世界時）に相対する日時情報を記録するGPS文字列を取得または設定します。 |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 目的地点へのGPS方位を取得または設定します。 |
| gps_dest_bearing_ref | string | r/w | 目的地点への方位を示すために使用されるGPS参照を取得または設定します。 |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 目的地点までのGPS距離を取得または設定します。 |
| gps_dest_distance_ref | string | r/w | 目的地点までの距離を表すために使用されるGPS単位を取得または設定します。 |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 目的地点のGPS緯度を取得または設定します。 |
| gps_dest_latitude_ref | string | r/w | 目的地点の緯度が北緯か南緯かを示すGPS値を取得または設定します。 |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 目的地点のGPS経度を取得または設定します。 |
| gps_dest_longitude_ref | string | r/w | 目的地点の経度が東経か西経かを示すGPS値を取得または設定します。 |
| gps_differential | ushort | r/w | GPS 受信機に差分補正が適用されているかどうかを示す GPS 値を取得または設定します。 |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 画像が撮影されたときの GPS 方向を取得または設定します。 |
| gps_img_direction_ref | string | r/w | 画像が撮影されたときの方向を示す GPS 参照を取得または設定します。 |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 緯度を取得または設定します。 |
| gps_latitude_ref | string | r/w | GPS 緯度が北緯か南緯かを取得または設定します。 |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 経度を取得または設定します。 |
| gps_longitude_ref | string | r/w | GPS 経度が東経か西経かを取得または設定します。 |
| gps_map_datum | string | r/w | GPS 受信機で使用される測地測量データを取得または設定します。 |
| gps_measure_mode | string | r/w | GPS 測定モードを取得または設定します。 |
| gps_processing_method | byte | r/w | 位置特定に使用された方法名を記録する GPS 文字列を取得または設定します。 |
| gps_satellites | string | r/w | 測定に使用される GPS 衛星を取得または設定します。 |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 受信機の移動速度を取得または設定します。 |
| gps_speed_ref | string | r/w | GPS 受信機の移動速度を表す単位を取得または設定します。 |
| gps_status | string | r/w | 画像が記録されたときの GPS 受信機の状態を取得または設定します。 |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | GPS セクションにのみ属するタグを取得または設定します。 |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS 時間を UTC（協定世界時）として取得または設定します。 |
| gps_track | string | r/w | GPS 受信機の移動方向を取得または設定します。 |
| gps_track_ref | string | r/w | GPS 受信機の移動方向を示す参照を取得または設定します。 |
| gps_version_id | byte | r/w | GPS バージョン識別子を取得または設定します。 |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS DOP（データ精度）を取得または設定します。 |
| image_unique_id | string | r/w | 画像の一意識別子を取得または設定します。 |
| is_big_endian | bool | r/w | ストリームから作成された EXIF データがビッグエンディアンかどうかを示す値を取得または設定します。 |
| iso_speed | uint | r/w | ISO 速度を取得または設定します。 |
| iso_speed_latitude_yyy | uint | r/w | ISO 12232 で定義されたカメラまたは入力デバイスの ISO 速度緯度 yyy 値を取得または設定します。 |
| iso_speed_latitude_zzz | uint | r/w | ISO 12232 で定義されたカメラまたは入力デバイスの ISO 速度緯度 zzz 値を取得または設定します。 |
| lens_make | string | r/w | レンズの製造元を取得または設定します。 |
| lens_model | string | r/w | レンズモデルを取得または設定します。 |
| lens_serial_number | string | r/w | レンズのシリアル番号を取得または設定します。 |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | レンズの仕様を取得または設定します。 |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | 光源を取得または設定します。 |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | メーカー注記データを取得します。 |
| maker_note_raw_data | byte | r/w | メーカー注記の生データを取得または設定します。 |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 最大絞り値を取得または設定します。 |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | 測光モードを取得または設定します。 |
| oecf | byte | r/w | ISO 14524で規定された光電変換関数（OECF）を取得または設定します。 |
| photographic_sensitivity | uint | r/w | 写真感度を取得または設定します。 |
| pixel_x_dimension | uint | r/w | ピクセルのX寸法を取得または設定します。 |
| pixel_y_dimension | uint | r/w | ピクセルのY寸法を取得または設定します。 |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | すべてのEXIFタグ（共通タグとGPSタグを含む）を取得または設定します。 |
| recommended_exposure_index | uint | r/w | 推奨露出指数を取得または設定します。 |
| related_sound_file | string | r/w | 関連するサウンドファイルを取得または設定します。 |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | saturation を取得または設定します。 |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | シーン撮影タイプを取得または設定します。 |
| scene_type | byte | r/w | シーンタイプを取得または設定します。 |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | センシング方式を取得または設定します。 |
| sensitivity_type | ushort | r/w | 感度タイプを取得または設定します。 |
| 鮮明度 | ushort | r/w | 鮮明度を取得または設定します。 |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | シャッタースピードの値を取得または設定します。 |
| 空間周波数応答 | byte | r/w | 空間周波数応答を取得または設定します。 |
| スペクトル感度 | string | r/w | スペクトル感度を取得または設定します。 |
| 標準出力感度 | uint | r/w | 標準出力感度を取得または設定します |
| 被写体領域 | ushort | r/w | 被写体領域を取得または設定します。 |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 被写体距離を取得または設定します。 |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | 被写体距離範囲を取得または設定します。 |
| 被写体位置 | ushort | r/w | 被写体位置を取得または設定します。 |
| サブ秒時間 | string | r/w | DateTime タグの秒以下の小数部を取得または設定します。 |
| デジタル化サブ秒時間 | string | r/w | DateTimeDigitized タグの秒以下の小数部を取得または設定します。 |
| オリジナルサブ秒時間 | string | r/w | DateTimeOriginal タグの秒以下の小数部を取得または設定します。 |
| ユーザーコメント | string | r/w | ユーザーコメントを取得または設定します。 |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | ホワイトバランスを取得または設定します。 |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 画像の白色点の色度を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | コンテナからタグを削除する |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | コンテナからタグを削除する |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

新しい [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) クラスのインスタンスを初期化します。

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

配列からのデータを使用して新しい [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 共通タグ。 |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | EXIFタグ。 |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | GPSタグ。 |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

配列からのデータを使用して新しい [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 共通タグとGPSタグを含むEXIFタグの配列。 |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

コンテナからタグを削除する

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | 削除するタグ |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

コンテナからタグを削除する

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tag_id | ushort | 削除するタグ識別子です。 |

