---
title: "ExifProperties 列挙体"
type: docs
weight: 160
url: /ja/python-net/aspose.psd.exif/exifproperties/
---

Exif タグ一覧

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifProperties

**Aspose.PSD Version:** 24.12.0

## **Members**
| **メンバー名** | **説明** |
| :- | :- |
| APERTURE_VALUE | レンズの絞り値です。 |
| ARTIST | このタグはカメラ所有者、撮影者または画像作成者の名前を記録します。詳細な形式は指定されていませんが、相互運用性を容易にするために以下の例のように情報を書き込むことが推奨されます。フィールドが空白の場合は不明として扱われます。例）"Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | 画像コンポーネントあたりのビット数です。この標準では各コンポーネントは8ビットであるため、このタグの値は8です。 |
| BODY_SERIAL_NUMBER | カメラ本体のシリアル番号を含みます |
| BRIGHTNESS_VALUE | 明るさの値です。 |
| CAMERA_OWNER_NAME | カメラ所有者の名前を含みます |
| CFA_PATTERN | ワンチップカラーエリアセンサーが使用されている場合の画像センサーのカラーフィルタ配列（CFA）幾何学パターンを示します。すべてのセンシング方式に適用されるわけではありません。 |
| COLOR_SPACE | カラースペース情報タグ（ColorSpace）は常にカラースペース指定子として記録されます。 |
| COMPONENTS_CONFIGURATION | コンポーネント構成です。 |
| COMPRESSED_BITS_PER_PIXEL | 圧縮データ固有で、圧縮ビット/ピクセルを示します。 |
| COMPRESSION | 画像データに使用される圧縮方式です。プライマリ画像が JPEG 圧縮されている場合、この指定は不要で省略されます。 |
| CONTRAST | このタグは撮影時にカメラが適用したコントラスト処理の方向を示します。 |
| COPYRIGHT | 著作権情報。この標準ではこのタグは<br/>                撮影者と編集者の両方の著作権を示すために使用されます。これは<br/>                画像の権利を主張する個人または組織の著作権表示です。相互運用性の<br/>                著作権ステートメント（日付と権利を含む）はこのフィールドに記入すべきです；例："Copyright, John Smith, 19xx. All rights<br/>                reserved."。この標準ではフィールドは撮影者と編集者の著作権の両方を記録し、各々はステートメントの別々の部分に記載されます。撮影者と編集者の著作権が明確に区別できる場合、これらは撮影者の著作権の後に編集者の著作権の順で記述し、NULLで区切ります（この場合、ステートメントがNULLで終了するため、NULLコードが二つあります）。撮影者の著作権のみが与えられる場合は、1つのNULLコードで終了します。編集者の著作権のみが与えられる場合、撮影者の著作権部分はスペース1つと終端NULLコードで構成され、その後に編集者の著作権が記述されます。フィールドが空白の場合は不明として扱われます。 |
| CUSTOM_RENDERED | このタグは画像データに対する特別な処理（出力向けのレンダリングなど）の使用を示します。特別な処理が行われた場合、リーダーはさらに処理を無効化または最小化することが期待されます。 |
| DATE_TIME | 画像作成の日時です。Exif 標準では、ファイルが変更された日時がこれにあたります。 |
| DATE_TIME_DIGITIZED | デジタル化された日時です。 |
| DATE_TIME_ORIGINAL | 元の画像データが生成された日時です。 |
| DEVICE_SETTING_DESCRIPTION | このタグは特定のカメラモデルの撮影条件に関する情報を示します。このタグはリーダー内で撮影条件を示すためだけに使用されます。 |
| DIGITAL_ZOOM_RATIO | このタグは画像が撮影されたときのデジタルズーム比率を示します。記録された値の分子が 0 の場合、デジタルズームは使用されていないことを示します。 |
| EXIF_IFD_POINTER | Exif IFD へのポインタです。相互運用性において、Exif IFD は TIFF で指定された IFD と同じ構造を持ちます。ただし、通常は TIFF の場合と同様に画像データは含まれません。 |
| EXIF_VERSION | Exif バージョンです。 |
| EXPOSURE_BIAS_VALUE | 露出補正値です。 |
| EXPOSURE_INDEX | 画像が撮影された時点でカメラまたは入力デバイスで選択された露出指数を示します。 |
| EXPOSURE_MODE | このタグは画像が撮影されたときに設定された露出モードを示します。オートブランケティングモードでは、カメラは同じシーンを異なる露出設定で複数のフレームとして撮影します。 |
| EXPOSURE_PROGRAM | 撮影時にカメラが露出を設定するために使用するプログラムのクラスです。 |
| EXPOSURE_TIME | 露出時間（秒単位）です。 |
| FILE_SOURCE | ファイルのソースです。 |
| FLASH | 画像が撮影されたときのフラッシュの状態を示します。 |
| FLASHPIX_VERSION | FPXR ファイルがサポートする Flashpix フォーマットのバージョンです。 |
| FLASH_ENERGY | 画像が撮影された時点のストローブエネルギーを、ビームキャンドルパワー秒（BCPS）で測定した値として示します。 |
| FOCAL_LENGTH | レンズの実際の焦点距離（mm）です。 |
| FOCAL_LENGTH_IN_35_MM_FILM | このタグは、35mmフィルムカメラを想定した等価焦点距離（mm）を示します。値が0の場合、焦点距離は不明です。このタグはFocalLengthタグとは異なることに注意してください。 |
| FOCAL_PLANE_RESOLUTION_UNIT | FocalPlaneXResolution と FocalPlaneYResolution の測定単位を示します。この値は ResolutionUnit と同じです。 |
| FOCAL_PLANE_X_RESOLUTION | カメラの焦点面上で、FocalPlaneResolutionUnit あたりの画像幅（X）方向のピクセル数を示します。 |
| FOCAL_PLANE_Y_RESOLUTION | カメラの焦点面上で、FocalPlaneResolutionUnit あたりの画像高さ（Y）方向のピクセル数を示します。 |
| F_NUMBER | F値です。 |
| GAIN_CONTROL | このタグは、画像全体のゲイン調整度合いを示します。 |
| GAMMA | ガンマ値 |
| GPSDOP | GPS DOP（精度のデータ度合い）を示します。2次元測定時には HDOP 値が記録され、<br/>                3次元測定時には PDOP が記録されます。 |
| GPS_ALTITUDE | GPSAltitudeRef の参照に基づく高度を示します。高度は 1 つの RATIONAL 値で表され、<br/>                参照単位はメートルです。 |
| GPS_ALTITUDE_REF | 参照高度として使用される高度を示します。参照が海面で高度が海面上の場合は<br/>                0 が設定されます。高度が海面下の場合は 1 が設定され、GPSAltitude タグで絶対高度として示されます。 |
| GPS_AREA_INFORMATION | GPSエリアの名前を記録した文字列です。最初のバイトは使用された文字コードを示し、<br/>                続いて GPSエリアの名前が続きます。 |
| GPS_DATE_STAMP | UTC（協定世界時）に対する日付と時刻情報を記録する文字列です<br/>                （Coordinated Universal Time）。形式は YYYY:MM:DD です。 |
| GPS_DEST_BEARING | 目的地点への方位を示します。値の範囲は 0.00 から 359.99 です。 |
| GPS_DEST_BEARING_REF | 目的地点への方位を示す際に使用される基準を示します。'T' は真方位を、'M' は<br/>                磁方位を表します。 |
| GPS_DEST_DISTANCE | 目的地点までの距離を示します。 |
| GPS_DEST_DISTANCE_REF | 目的地点までの距離を表す単位を示します。'K'、'M'、'N' はそれぞれキロメートル、マイル、<br/>                ノットを表します。 |
| GPS_DEST_LATITUDE | 目的地点の緯度を示します。緯度は、度、分、秒をそれぞれ表す 3 つの RATIONAL 値で表されます。<br/>                緯度が度・分・秒で表される場合、典型的な形式は dd/1,mm/1,ss/1 です。度と分が使用され、たとえば分の小数が<br/>                小数点以下二桁まで示される場合、形式は dd/1,mmmm/100,0/1 となります。 |
| GPS_DEST_LATITUDE_REF | 目的地点の緯度が北緯か南緯かを示します。ASCII 値の 'N' は北緯を<br/>                示し、'S' は南緯を表します。 |
| GPS_DEST_LONGITUDE | 目的地点の経度を示します。経度は、度、分、秒をそれぞれ表す 3 つの RATIONAL 値で表されます。<br/>                経度が度・分・秒で表される場合、典型的な形式は ddd/1,mm/1,ss/1 です。度と分が使用され、たとえば分の小数が<br/>                小数点以下二桁まで示される場合、形式は ddd/1,mmmm/100,0/1 となります。 |
| GPS_DEST_LONGITUDE_REF | 目的地点の経度が東経か西経かを示します。ASCII の 'E' は東経を、<br/>                'W' は西経を表します。 |
| GPS_DIFFERENTIAL | GPS 受信機に対して微分補正が適用されているかどうかを示します。 |
| GPS_IFD_POINTER | GPS IFD ポインタです。 |
| GPS_IMG_DIRECTION | 画像が撮影されたときの方向を示します。値の範囲は 0.00 から 359.99 です。 |
| GPS_IMG_DIRECTION_REF | 画像が撮影されたときの方向を示す参照を示します。'T' は真の方向を、'M' は<br/>                磁気方向を表します。 |
| GPS_LATITUDE | 緯度を示します。緯度は、度、分、秒をそれぞれ示す3つのRATIONAL値で表されます。緯度が度・分・秒で表される場合、典型的な形式は<br/>                dd/1,mm/1,ss/1 です。度と分が使用され、例えば分の小数部が小数第2位まで与えられる場合、形式は dd/1,mmmm/100,0/1 となります。 |
| GPS_LATITUDE_REF | 緯度が北緯か南緯かを示します。 |
| GPS_LONGITUDE | 経度を示します。経度は、度、分、秒をそれぞれ示す3つのRATIONAL値で表されます。経度が度・分・秒で表される場合、典型的な形式は<br/>                ddd/1,mm/1,ss/1 です。度と分が使用され、例えば分の小数部が小数第2位まで与えられる場合、形式は ddd/1,mmmm/100,0/1 となります。 |
| GPS_LONGITUDE_REF | 経度が東経か西経かを示します。 |
| GPS_MAP_DATUM | GPS受信機で使用される測地測量データを示します。 |
| GPS_MEASURE_MODE | GPS測定モードを示します。- 2次元または3次元。 |
| GPS_PROCESSING_METHOD | 位置特定に使用された手法の名前を記録した文字列です。<br/>                最初のバイトは使用された文字コードを示し、その後に手法の名前が続きます。 |
| GPS_SATELLITES | 測定に使用されたGPS衛星を示します。このタグは、衛星の数、ID番号、仰角、方位角、SNR およびその他の情報を ASCII 表記で記述するために使用できます。形式は指定されていません。GPS受信機が測定できない場合、タグの値は NULL に設定されます。 |
| GPS_SPEED | GPS受信機の移動速度を示します。 |
| GPS_SPEED_REF | GPS受信機の移動速度を表す単位を示します。'K'、'M'、'N' はそれぞれ時速キロメートル、時速マイル、ノットを表します。 |
| GPS_STATUS | 画像が記録されたときのGPS受信機の状態を示します。 |
| GPS_TIMESTAMP | 時間を UTC（協定世界時）として示します。タイムスタンプは、時、分、秒を示す3つのRATIONAL値で表されます。<br/>                時、分、秒を示す。 |
| GPS_TRACK | GPS受信機の移動方向を示します。値の範囲は0.00から359.99です。 |
| GPS_TRACK_REF | GPS受信機の移動方向を示す基準を示します。'T'は真北方向、'M'は<br/>                磁北方向を表します。 |
| GPS_VERSION_ID | GPSInfoIFDのバージョンを示します。 |
| IMAGE_DESCRIPTION | 画像のタイトルを示す文字列です。例として "1988 company picnic" のようなコメントになることがあります。 |
| IMAGE_LENGTH | 画像データの行数です。 |
| IMAGE_UNIQUE_ID | 画像のユニークIDです。 |
| IMAGE_WIDTH | 画像データの列数で、1行あたりのピクセル数に相当します。 |
| ISO_SPEED | ISO 12232で定義されたISO感度値に関する情報です。 |
| ISO_SPEED_LATITUDE_YYY | このタグはISO 12232で定義されたISO感度緯度YYY値を示します。 |
| ISO_SPEED_LATITUDE_ZZZ | このタグはISO 12232で定義されたISO感度緯度ZZZ値を示します。 |
| JPEG_INTERCHANGE_FORMAT | JPEG圧縮サムネイルデータの開始バイト（SOI）へのオフセットです。これは主画像のJPEGデータには使用されません。 |
| JPEG_INTERCHANGE_FORMAT_LENGTH | JPEG圧縮サムネイルデータのバイト数です。これは主画像のJPEGデータには使用されません。JPEGサムネイルは分割されず、SOIからEOIまでの連続したJPEGビットストリームとして記録されます。AppnおよびCOMマーカーは記録すべきではありません。圧縮サムネイルは、APP1に記録される他のすべてのデータを含めて、64KB以下で記録しなければなりません。 |
| LENS_MAKE | このタグはレンズの製造元を記録します。 |
| LENS_MODEL | このタグはレンズのモデル名とモデル番号を記録します。 |
| LENS_SERIAL_NUMBER | このタグは交換レンズのシリアル番号を記録します |
| LENS_SPECIFICATION | このタグは最小焦点距離、最大焦点距離、最小焦点距離における最小F値、最大焦点距離における最小F値を記録します |
| LIGHT_SOURCE | 光源の種類です。 |
| MAKE | 記録機器の製造元です。これは画像を生成したDSC、スキャナ、ビデオデジタイザ、またはその他の機器の製造元を示します。フィールドが空白のままの場合、未知として扱われます。 |
| MAKER_NOTE | Exifライターの製造元が任意の情報を記録するためのタグです。内容は製造元次第ですが、このタグは本来の目的以外には使用すべきではありません。 |
| MAX_APERTURE_VALUE | 最大絞り値です。 |
| METERING_MODE | 測光モードです。 |
| MODEL | 機器のモデル名またはモデル番号です。これは画像を生成したDSC、スキャナ、ビデオデジタイザ、またはその他の機器のモデル名または番号を示します。フィールドが空白の場合、未知として扱われます。 |
| OECF | ISO 14524で規定された光電変換関数（OECF）を示します。 |
| ORIENTATION | 行と列の観点から見た画像の向きを示します。 |
| PHOTOGRAPHIC_SENSITIVITY | ISO 12232で規定されたカメラまたは入力デバイスのISO感度とISO緯度を示します。 |
| PHOTOMETRIC_INTERPRETATION | ピクセルの構成です。 |
| PIXEL_X_DIMENSION | 圧縮データに特有の情報です。圧縮ファイルが記録される際、パディングデータやリスタートマーカーの有無にかかわらず、有効な画像の幅をこのタグに記録します。 |
| PIXEL_Y_DIMENSION | 圧縮データに特有の情報です。圧縮ファイルが記録される際、有効な画像の高さをこのタグに記録します。 |
| PLANAR_CONFIGURATION | ピクセルコンポーネントがチャンク形式またはプラナー形式で記録されるかどうかを示します。このフィールドが存在しない場合、TIFF のデフォルトである 1（チャンク）が想定されます。 |
| PRIMARY_CHROMATICITIES | 画像の三原色の色度を示します。通常、このタグは必要ありません。なぜなら色空間は色空間情報の ColorSpace タグで指定されているからです。 |
| RECOMMENDED_EXPOSURE_INDEX | 推奨露出指数を示します |
| REFERENCE_BLACK_WHITE | 参照黒点値と参照白点<br/>                値。TIFF ではデフォルトは与えられていませんが、以下の値がここではデフォルトとして提供されています。<br/>                カラースペースは<br/>                カラースペース情報タグで宣言され、デフォルトは<br/>                最適な画像特性を提供する値です<br/>                これらの条件における相互運用性 |
| RELATED_SOUND_FILE | 関連するサウンドファイルです。 |
| RESOLUTION_UNIT | XResolution と YResolution を測定する単位です。XResolution と YResolution の両方で同じ単位が使用されます。画像の解像度が不明な場合、2（インチ）が指定されます。 |
| ROWS_PER_STRIP | ストリップあたりの行数です。画像がストリップに分割される際、1 つのストリップ内の画像の行数を示します。 |
| SAMPLES_PER_PIXEL | ピクセルあたりのコンポーネント数です。この標準は RGB および YCbCr 画像に適用されるため、このタグの設定値は 3 です。 |
| SATURATION | このタグは、画像が撮影された際にカメラが適用した彩度処理の方向を示します。 |
| SCENE_CAPTURE_TYPE | このタグは撮影されたシーンの種類を示します。また、画像が撮影されたモードを記録するためにも使用できます。 |
| SCENE_TYPE | シーンの種類を示します。DSC が画像を記録した場合、このタグの値は常に 1 に設定され、画像が直接撮影されたことを示します。 |
| SENSING_METHOD | カメラまたは入力デバイス上のイメージセンサーのタイプを示します。 |
| SENSITIVITY_TYPE | 写真感度のタイプ |
| SHARPNESS | このタグは、画像が撮影された際にカメラが適用したシャープネス処理の方向を示します |
| SHUTTER_SPEED_VALUE | シャッタースピードの値です。 |
| SOFTWARE | このタグは、画像生成に使用されたカメラまたは画像入力デバイスのソフトウェアまたはファームウェアの名前とバージョンを記録します。詳細な形式は指定されていませんが、以下に示す例に従うことが推奨されます。フィールドが空白のままの場合、未知として扱われます。 |
| SPATIAL_FREQUENCY_RESPONSE | このタグは、ISO 12233で規定されているように、カメラまたは入力デバイスの空間周波数テーブルと、画像幅、画像高さ、対角方向のSFR値を記録します。 |
| SPECTRAL_SENSITIVITY | 使用されるカメラの各チャンネルのスペクトル感度を示します。 |
| STANDARD_OUTPUT_SENSITIVITY | カメラの標準出力感度を示します。 |
| STRIP_BYTE_COUNTS | 各ストリップのバイト総数です。 |
| STRIP_OFFSETS | 各ストリップについて、そのストリップのバイトオフセットです。ストリップのバイト数が64KBを超えないように選択することが推奨されます。<br/>                Aux tag. |
| SUBJECT_AREA | このタグは、全体シーンにおける主対象の位置と領域を示します。 |
| SUBJECT_DISTANCE | 対象までの距離をメートルで示します。 |
| SUBJECT_DISTANCE_RANGE | このタグは対象までの距離を示します。 |
| SUBJECT_LOCATION | シーン内の主対象の位置を示します。このタグの値は、Rotationタグに従った回転処理前に、左端を基準とした主対象中心のピクセル位置を表します。 |
| SUBSEC_TIME | DateTimeタグの秒以下の小数部を記録するために使用されるタグです。 |
| SUBSEC_TIME_DIGITIZED | DateTimeDigitizedタグの秒以下の小数部を記録するために使用されるタグです。 |
| SUBSEC_TIME_ORIGINAL | DateTimeOriginalタグの秒以下の小数部を記録するために使用されるタグです。 |
| TRANSFER_FUNCTION | 画像のトランスファー関数を表形式で記述します。通常、このタグは不要です。なぜなら、カラースペースはColorSpaceタグのカラースペース情報で指定されているからです。 |
| USER_COMMENT | ExifユーザーがImageDescriptionタグ以外に画像にキーワードやコメントを書き込むためのタグで、ImageDescriptionタグの文字コード制限を受けません。 |
| WHITE_BALANCE | このタグは、画像が撮影されたときに設定されたホワイトバランスモードを示します。 |
| WHITE_POINT | 画像のホワイトポイントの色度です。通常、このタグは必要ありません。なぜなら、色空間はカラースペース情報の ColorSpace タグで指定されているからです。 |
| X_RESOLUTION | ImageWidth 方向の ResolutionUnit 当たりのピクセル数です。画像の解像度が不明な場合、72 [dpi] が指定されます。 |
| Y_CB_CR_COEFFICIENTS | RGB から YCbCr 画像データへの変換に使用される行列係数です。 |
| Y_CB_CR_POSITIONING | 色差成分の位置は輝度成分に対しての位置です。<br/>                このフィールドは JPEG 圧縮データまたは非圧縮 YCbCr データに対してのみ指定されます。TIFF のデフォルトは 1（センタリング）です；ただし Y:Cb:Cr = 4:2:2 の場合、本標準ではデータ記録時に画像品質を TV システムでの表示時に向上させるため、2（同位置）を使用することが推奨されています。フィールドが存在しない場合、リーダーは TIFF のデフォルトを想定すべきです。Y:Cb:Cr = 4:2:0 の場合、TIFF のデフォルト（センタリング）が推奨されます。リーダーが YCbCrPositioning の両方の方式をサポートする機能を持たない場合、フィールドの値に関わらず TIFF のデフォルトに従うべきです。リーダーが "<br/>                センター配置と同位置配置の両方をサポートできることが望ましいです。 |
| Y_CB_CR_SUB_SAMPLING | 色差成分のサンプリング比率は輝度成分に対しての比率です。 |
| Y_RESOLUTION | ImageLength 方向の ResolutionUnit 当たりのピクセル数です。XResolution と同じ値が指定されます。 |
