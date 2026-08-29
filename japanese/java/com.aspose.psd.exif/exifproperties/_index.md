---
title: "ExifProperties"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Exif タグ一覧"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.exif/exifproperties/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif タグ一覧
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ApertureValue](#ApertureValue) | レンズの絞り値。 |
| [Artist](#Artist) | このタグはカメラ所有者、写真家、または画像作成者の名前を記録します。 |
| [BitsPerSample](#BitsPerSample) | 画像コンポーネントあたりのビット数。 |
| [BodySerialNumber](#BodySerialNumber) | カメラ本体のシリアル番号を含みます |
| [BrightnessValue](#BrightnessValue) | 明るさの値。 |
| [CFAPattern](#CFAPattern) | ワンチップカラーエリアセンサーが使用されている場合の、イメージセンサーのカラーフィルタ配列（CFA）幾何学的パターンを示します。 |
| [CameraOwnerName](#CameraOwnerName) | カメラ所有者の名前が含まれています |
| [ColorSpace](#ColorSpace) | カラー空間情報タグ（ColorSpace）は常にカラー空間指定子として記録されます。 |
| [ComponentsConfiguration](#ComponentsConfiguration) | コンポーネントの構成です。 |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | 圧縮データに特有で、ピクセルあたりの圧縮ビット数を示します。 |
| [Compression](#Compression) | 画像データに使用される圧縮方式です。 |
| [Contrast](#Contrast) | このタグは、画像が撮影されたときにカメラが適用したコントラスト処理の方向を示します。 |
| [Copyright](#Copyright) | 著作権情報です。 |
| [CustomRendered](#CustomRendered) | このタグは、出力に合わせたレンダリングなど、画像データに対する特別な処理の使用を示します。 |
| [DateTime](#DateTime) | 画像作成の日付と時刻です。 |
| [DateTimeDigitized](#DateTimeDigitized) | デジタル化された日時です。 |
| [DateTimeOriginal](#DateTimeOriginal) | 元の画像データが生成された日時です。 |
| [DeviceSettingDescription](#DeviceSettingDescription) | このタグは、特定のカメラモデルの撮影条件に関する情報を示します。 |
| [DigitalZoomRatio](#DigitalZoomRatio) | このタグは、画像が撮影されたときのデジタルズーム比率を示します。 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ExifIfdPointer](#ExifIfdPointer) | Exif IFD へのポインタです。 |
| [ExifVersion](#ExifVersion) | Exif バージョンです。 |
| [ExposureBiasValue](#ExposureBiasValue) | 露出補正値です。 |
| [ExposureIndex](#ExposureIndex) | 画像が撮影された時点でカメラまたは入力デバイスで選択された露出インデックスを示します。 |
| [ExposureMode](#ExposureMode) | このタグは、画像が撮影されたときに設定された露出モードを示します。 |
| [ExposureProgram](#ExposureProgram) | 写真撮影時にカメラが露出を設定するために使用するプログラムのクラスです。 |
| [ExposureTime](#ExposureTime) | 露出時間（秒単位）です。 |
| [FNumber](#FNumber) | F 値です。 |
| [FileSource](#FileSource) | ファイルソースです。 |
| [Flash](#Flash) | 画像が撮影されたときのフラッシュの状態を示します。 |
| [FlashEnergy](#FlashEnergy) | 画像が撮影された時点でのストロボエネルギーを、ビームキャンドルパワー秒（BCPS）で測定した値として示します。 |
| [FlashpixVersion](#FlashpixVersion) | FPXR ファイルがサポートする Flashpix フォーマットバージョンです。 |
| [FocalLength](#FocalLength) | レンズの実際の焦点距離（単位は mm）。 |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | このタグは、35mm フィルムカメラを想定した等価焦点距離（単位は mm）を示します。 |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | FocalPlaneXResolution と FocalPlaneYResolution の測定単位を示します。 |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | カメラの焦点面上の FocalPlaneResolutionUnit あたりの画像幅（X）方向のピクセル数を示します。 |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | カメラの焦点面上の FocalPlaneResolutionUnit あたりの画像高さ（Y）方向のピクセル数を示します。 |
| [GPSAltitude](#GPSAltitude) | GPSAltitudeRef の参照に基づく高度を示します。 |
| [GPSAltitudeRef](#GPSAltitudeRef) | 参照高度として使用される高度を示します。 |
| [GPSAreaInformation](#GPSAreaInformation) | GPS エリアの名前を記録した文字列です。 |
| [GPSDOP](#GPSDOP) | GPS DOP（データ精度）を示します。 |
| [GPSDateStamp](#GPSDateStamp) | UTC（協定世界時）に対する日時情報を記録した文字列です。 |
| [GPSDestBearing](#GPSDestBearing) | 目的地点への方位を示します。 |
| [GPSDestBearingRef](#GPSDestBearingRef) | 目的地点への方位を示す際に使用される参照を示します。 |
| [GPSDestDistance](#GPSDestDistance) | 目的地点までの距離を示します。 |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | 目的地点までの距離を表す単位を示します。 |
| [GPSDestLatitude](#GPSDestLatitude) | 目的地点の緯度を示します。 |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | 目的地点の緯度が北緯か南緯かを示します。 |
| [GPSDestLongitude](#GPSDestLongitude) | 目的地点の経度を示します。 |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | 目的地点の経度が東経か西経かを示します。 |
| [GPSDifferential](#GPSDifferential) | GPS 受信機に差分補正が適用されているかどうかを示します。 |
| [GPSIfdPointer](#GPSIfdPointer) | GPS IFD ポインタです。 |
| [GPSImgDirection](#GPSImgDirection) | 撮影時の画像の向きを示します。 |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | 撮影時の画像の向きを示す際の参照を示します。 |
| [GPSLatitude](#GPSLatitude) | 緯度を示します。 |
| [GPSLatitudeRef](#GPSLatitudeRef) | 緯度が北緯か南緯かを示します。 |
| [GPSLongitude](#GPSLongitude) | 経度を示します。 |
| [GPSLongitudeRef](#GPSLongitudeRef) | 経度が東経か西経かを示します。 |
| [GPSMapDatum](#GPSMapDatum) | GPS受信機で使用される測地測量データを示します。 |
| [GPSMeasureMode](#GPSMeasureMode) | GPS測定モードを示します。 |
| [GPSProcessingMethod](#GPSProcessingMethod) | 位置特定に使用される方法の名前を記録した文字列です。 |
| [GPSSatellites](#GPSSatellites) | 測定に使用されるGPS衛星を示します。 |
| [GPSSpeed](#GPSSpeed) | GPS受信機の移動速度を示します。 |
| [GPSSpeedRef](#GPSSpeedRef) | GPS受信機の移動速度を表す単位を示します。 |
| [GPSStatus](#GPSStatus) | 画像が記録されたときのGPS受信機の状態を示します。 |
| [GPSTimestamp](#GPSTimestamp) | 時間をUTC（協定世界時）で示します。 |
| [GPSTrack](#GPSTrack) | GPS受信機の移動方向を示します。 |
| [GPSTrackRef](#GPSTrackRef) | GPS受信機の移動方向を示す基準を示します。 |
| [GPSVersionID](#GPSVersionID) | GPSInfoIFDのバージョンを示します。 |
| [GainControl](#GainControl) | このタグは画像全体のゲイン調整度合いを示します。 |
| [Gamma](#Gamma) | ガンマ値 |
| [ISOSpeed](#ISOSpeed) | ISO 12232で定義されたISO感度値に関する情報 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | このタグはISO 12232で定義されたISO感度緯度 yyy 値を示します。 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | このタグはISO 12232で定義されたISO感度緯度 zzz 値を示します。 |
| [ImageDescription](#ImageDescription) | 画像のタイトルを示す文字列です。 |
| [ImageLength](#ImageLength) | 画像データの行数です。 |
| [ImageUniqueID](#ImageUniqueID) | 画像のユニークIDです。 |
| [ImageWidth](#ImageWidth) | 画像データの列数で、1行あたりのピクセル数に相当します。 |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | JPEG圧縮サムネイルデータの開始バイト（SOI）へのオフセットです。 |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | JPEG圧縮サムネイルデータのバイト数です。 |
| [LensMake](#LensMake) | このタグはレンズメーカーを記録します。 |
| [LensModel](#LensModel) | このタグはレンズのモデル名とモデル番号を記録します。 |
| [LensSerialNumber](#LensSerialNumber) | このタグは交換可能なレンズのシリアル番号を記録します |
| [LensSpecification](#LensSpecification) | このタグは最小焦点距離、最大焦点距離、最小焦点距離における最小F値、最大焦点距離における最小F値を記録します |
| [LightSource](#LightSource) | 光源の種類です。 |
| [Make](#Make) | 記録機器の製造元です。 |
| [MakerNote](#MakerNote) | Exifライターの製造元が任意の情報を記録するためのタグです。 |
| [MaxApertureValue](#MaxApertureValue) | 最大絞り値です。 |
| [MeteringMode](#MeteringMode) | 測光モードです。 |
| [Model](#Model) | 機器のモデル名またはモデル番号です。 |
| [OECF](#OECF) | ISO 14524で規定された光電変換関数（OECF）を示します。 |
| [Orientation](#Orientation) | 行と列の観点から見た画像の向きです。 |
| [PhotographicSensitivity](#PhotographicSensitivity) | ISO 12232で規定されたカメラまたは入力デバイスのISO感度とISO緯度を示します。 |
| [PhotometricInterpretation](#PhotometricInterpretation) | ピクセル構成です。 |
| [PixelXDimension](#PixelXDimension) | 圧縮データに特有の情報です。 |
| [PixelYDimension](#PixelYDimension) | 圧縮データに特有の情報です。 |
| [PlanarConfiguration](#PlanarConfiguration) | ピクセル成分がチャンク形式か平面形式で記録されているかを示します。 |
| [PrimaryChromaticities](#PrimaryChromaticities) | 画像の3つの原色の色度です。 |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | 推奨露出指数を示します |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | 参照黒点値と参照白点値です。 |
| [RelatedSoundFile](#RelatedSoundFile) | 関連するサウンドファイルです。 |
| [ResolutionUnit](#ResolutionUnit) | X解像度とY解像度の測定単位です。 |
| [RowsPerStrip](#RowsPerStrip) | ストリップあたりの行数です。 |
| [SamplesPerPixel](#SamplesPerPixel) | ピクセルあたりのコンポーネント数です。 |
| [Saturation](#Saturation) | このタグは、画像が撮影されたときにカメラが適用した彩度処理の方向を示します。 |
| [SceneCaptureType](#SceneCaptureType) | このタグは、撮影されたシーンのタイプを示します。 |
| [SceneType](#SceneType) | シーンのタイプを示します。 |
| [SensingMethod](#SensingMethod) | カメラまたは入力デバイスのイメージセンサータイプを示します。 |
| [SensitivityType](#SensitivityType) | 写真感度のタイプ |
| [Sharpness](#Sharpness) | このタグは、画像が撮影されたときにカメラが適用したシャープネス処理の方向を示します |
| [ShutterSpeedValue](#ShutterSpeedValue) | シャッタースピードの値です。 |
| [Software](#Software) | このタグは、画像生成に使用されたカメラまたは画像入力デバイスのソフトウェアまたはファームウェアの名前とバージョンを記録します。 |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | このタグは、ISO 12233で規定された画像幅、画像高さ、対角方向の空間周波数テーブルとSFR値をカメラまたは入力デバイスから記録します。 |
| [SpectralSensitivity](#SpectralSensitivity) | 使用されたカメラの各チャンネルのスペクトル感度を示します。 |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | カメラの標準出力感度を示します |
| [StripByteCounts](#StripByteCounts) | 各ストリップの総バイト数です。 |
| [StripOffsets](#StripOffsets) | 各ストリップについて、そのストリップのバイトオフセットです。 |
| [SubjectArea](#SubjectArea) | このタグは、全体シーンにおける主被写体の位置と領域を示します。 |
| [SubjectDistance](#SubjectDistance) | 被写体までの距離（メートル単位）です。 |
| [SubjectDistanceRange](#SubjectDistanceRange) | このタグは、被写体までの距離を示します。 |
| [SubjectLocation](#SubjectLocation) | シーン内の主被写体の位置を示します。 |
| [SubsecTime](#SubsecTime) | DateTimeタグの秒以下の小数部を記録するために使用されるタグです。 |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | DateTimeDigitizedタグの秒以下の小数部を記録するために使用されるタグです。 |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | DateTimeOriginalタグの秒以下の小数部を記録するために使用されるタグです。 |
| [TransferFunction](#TransferFunction) | 画像の転送関数で、表形式で記述されています。 |
| [UserComment](#UserComment) | ExifユーザーがImageDescriptionタグ以外のキーワードやコメントを書き込むためのタグで、ImageDescriptionタグの文字コード制限がありません。 |
| [WhiteBalance](#WhiteBalance) | このタグは、画像撮影時に設定されたホワイトバランスモードを示します。 |
| [WhitePoint](#WhitePoint) | 画像のホワイトポイントの色度です。 |
| [XResolution](#XResolution) | ImageWidth方向のResolutionUnitあたりのピクセル数です。 |
| [YCbCrCoefficients](#YCbCrCoefficients) | RGBからYCbCr画像データへの変換のための行列係数です。 |
| [YCbCrPositioning](#YCbCrPositioning) | 輝度成分に対する色差成分の位置です。 |
| [YCbCrSubSampling](#YCbCrSubSampling) | 輝度成分に対する色差成分のサンプリング比です。 |
| [YResolution](#YResolution) | ImageLength方向のResolutionUnitあたりのピクセル数です。 |
## メソッド

| メソッド | 説明 |
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


レンズの絞り値。

### Artist {#Artist}
```
public static final int Artist
```


このタグはカメラ所有者、撮影者または画像作成者の名前を記録します。詳細な形式は指定されていませんが、相互運用性を容易にするために以下の例のように情報を書き込むことが推奨されます。フィールドが空白の場合は不明として扱われます。例）"Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James"

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


画像コンポーネントあたりのビット数。この標準では画像の各コンポーネントは8ビットであるため、このタグの値は8です。

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


カメラ本体のシリアル番号を含みます

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


明るさの値。

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


ワンチップカラーエリアセンサーが使用される場合の画像センサーのカラーフィルタアレイ（CFA）幾何学パターンを示します。すべての撮像方式に適用されるわけではありません。

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


カメラ所有者の名前が含まれています

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


カラー空間情報タグ（ColorSpace）は常にカラー空間指定子として記録されます。

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


コンポーネントの構成です。

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


圧縮データに特有で、ピクセルあたりの圧縮ビット数を示します。

### Compression {#Compression}
```
public static final int Compression
```


画像データに使用される圧縮方式です。主画像がJPEG圧縮されている場合、この指定は不要となり省略されます。

### Contrast {#Contrast}
```
public static final int Contrast
```


このタグは、画像が撮影されたときにカメラが適用したコントラスト処理の方向を示します。

### Copyright {#Copyright}
```
public static final int Copyright
```


著作権情報。この標準では、このタグは撮影者と編集者の両方の著作権を示すために使用されます。画像の権利を主張する個人または組織の著作権表示です。相互運用性の著作権表記（日付と権利を含む）をこのフィールドに記入する必要があります。例："Copyright, John Smith, 19xx. All rights reserved."。この標準では、フィールドは撮影者と編集者の著作権をそれぞれ文の別々の部分に記録します。撮影者と編集者の著作権が明確に区別できる場合、撮影者の著作権の後に編集者の著作権を記述し、NULLで区切ります（この場合、文末もNULLになるため、NULLコードが2つになります）。撮影者の著作権のみが与えられる場合は、1つのNULLコードで終了します。編集者の著作権のみが与えられる場合は、撮影者の著作権部分はスペース1つと終了NULLコードで構成され、その後に編集者の著作権が記入されます。フィールドが空白の場合は不明として扱われます。

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


このタグは、出力向けのレンダリングなど、画像データに対する特殊処理の使用を示します。特殊処理が行われた場合、リーダーはそれ以降の処理を無効化または最小化することが期待されます。

### DateTime {#DateTime}
```
public static final int DateTime
```


画像作成の日付と時刻。Exif 標準では、ファイルが変更された日時を指します。

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


デジタル化された日時です。

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


元の画像データが生成された日時です。

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


このタグは特定のカメラモデルの撮影条件に関する情報を示します。このタグはリーダー内で撮影条件を示すためだけに使用されます。

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


このタグは画像撮影時のデジタルズーム比率を示します。記録された値の分子が 0 の場合、デジタルズームが使用されていないことを示します。

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Exif IFD へのポインタ。相互運用性において、Exif IFD は TIFF で指定された IFD と同じ構造を持ちます。ただし、通常は TIFF の場合と同様に画像データは含まれません。

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Exif バージョンです。

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


露出補正値です。

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


画像が撮影された時点でカメラまたは入力デバイスで選択された露出インデックスを示します。

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


このタグは画像撮影時に設定された露出モードを示します。オートブランケットモードでは、カメラは同一シーンを異なる露出設定で連続撮影します。

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


写真撮影時にカメラが露出を設定するために使用するプログラムのクラスです。

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


露出時間（秒単位）です。

### FNumber {#FNumber}
```
public static final int FNumber
```


F 値です。

### FileSource {#FileSource}
```
public static final int FileSource
```


ファイルソースです。

### Flash {#Flash}
```
public static final int Flash
```


画像が撮影されたときのフラッシュの状態を示します。

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


画像が撮影された時点でのストロボエネルギーを、ビームキャンドルパワー秒（BCPS）で測定した値として示します。

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


FPXR ファイルがサポートする Flashpix フォーマットバージョンです。

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


レンズの実際の焦点距離（単位は mm）。

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


このタグは 35mm フィルムカメラを想定した等価焦点距離（mm）を示します。値が 0 の場合は焦点距離が不明であることを意味します。このタグは FocalLength タグとは異なることに注意してください。

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


FocalPlaneXResolution と FocalPlaneYResolution の測定単位を示します。この値は ResolutionUnit と同じです。

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


カメラの焦点面上の FocalPlaneResolutionUnit あたりの画像幅（X）方向のピクセル数を示します。

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


カメラの焦点面上の FocalPlaneResolutionUnit あたりの画像高さ（Y）方向のピクセル数を示します。

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


GPSAltitudeRef の参照に基づく高度を示します。高度は 1 つの RATIONAL 値で表され、参照単位はメートルです。

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


参照高度として使用される高度を示します。参照が海面で高度が海面上の場合は 0 が与えられます。海面下の場合は 1 が与えられ、GPSAltitude タグで絶対高度として示されます。

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


GPS エリア名を記録する文字列。最初のバイトは使用された文字コードを示し、その後に GPS エリア名が続きます。

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


GPS DOP（精度の度合い）を示します。2 次元測定時には HDOP 値が、3 次元測定時には PDOP 値が記録されます。

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


UTC（協定世界時）に対する日付と時刻情報を記録する文字列。形式は YYYY:MM:DD です。

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


目的地点への方位を示します。値の範囲は 0.00 から 359.99 です。

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


目的地点への方位の基準を示します。'T' は真方位、'M' は磁方位を表します。

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


目的地点までの距離を示します。

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


目的地点までの距離の単位を示します。'K'、'M'、'N' はそれぞれキロメートル、マイル、ノットを表します。

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


目的地点の緯度を示します。緯度は度、分、秒を表す 3 つの RATIONAL 値で表されます。度・分・秒で表す場合、典型的な形式は dd/1,mm/1,ss/1 です。度と分のみを使用し、例えば分の小数を小数点以下2桁まで示す場合は、形式は dd/1,mmmm/100,0/1 となります。

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


目的地点の緯度が北緯か南緯かを示します。ASCII 値の 'N' は北緯、'S' は南緯を表します。

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


目的地点の経度を示します。経度は度、分、秒を表す 3 つの RATIONAL 値で表されます。度・分・秒で表す場合、典型的な形式は ddd/1,mm/1,ss/1 です。度と分のみを使用し、例えば分の小数を小数点以下2桁まで示す場合は、形式は ddd/1,mmmm/100,0/1 となります。

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


目的地点の経度が東経か西経かを示します。ASCII の 'E' は東経、'W' は西経を表します。

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


GPS 受信機に差分補正が適用されているかどうかを示します。

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


GPS IFD ポインタです。

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


画像が撮影されたときの方向を示します。値の範囲は 0.00 から 359.99 です。

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


画像が撮影されたときの方向を示す基準を示します。'T' は真方向、'M' は磁気方向を表します。

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


緯度を示します。緯度は、度、分、秒をそれぞれ表す 3 つの RATIONAL 値で表されます。緯度が度・分・秒で表される場合、典型的な形式は dd/1,mm/1,ss/1 です。度と分が使用され、たとえば分の小数が小数点以下2桁まで与えられる場合、形式は dd/1,mmmm/100,0/1 となります。

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


緯度が北緯か南緯かを示します。

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


経度を示します。経度は、度、分、秒をそれぞれ表す 3 つの RATIONAL 値で表されます。経度が度・分・秒で表される場合、典型的な形式は ddd/1,mm/1,ss/1 です。度と分が使用され、たとえば分の小数が小数点以下2桁まで与えられる場合、形式は ddd/1,mmmm/100,0/1 となります。

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


経度が東経か西経かを示します。

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


GPS受信機で使用される測地測量データを示します。

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


GPS 測定モードを示します。- 2 次元または 3 次元。

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


位置測定に使用された方法の名前を記録する文字列です。最初のバイトは使用された文字コードを示し、その後に方法名が続きます。

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


測定に使用された GPS 衛星を示します。このタグは、衛星の数、ID 番号、仰角、方位角、SNR などの情報を ASCII 表記で記述するために使用できます。形式は指定されていません。GPS 受信機が測定できない場合、タグの値は NULL に設定されます。

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


GPS受信機の移動速度を示します。

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


GPS 受信機の移動速度を表す単位を示します。'K'、'M'、'N' はそれぞれ時速キロメートル、時速マイル、ノットを表します。

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


画像が記録されたときのGPS受信機の状態を示します。

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


時間を UTC（協定世界時）として示します。TimeStamp は時、分、秒を示す 3 つの RATIONAL 値で表されます。

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


GPS 受信機の移動方向を示します。値の範囲は 0.00 から 359.99 です。

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


GPS 受信機の移動方向を示す基準を示します。'T' は真方向、'M' は磁気方向を表します。

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


GPSInfoIFDのバージョンを示します。

### GainControl {#GainControl}
```
public static final int GainControl
```


このタグは画像全体のゲイン調整度合いを示します。

### Gamma {#Gamma}
```
public static final int Gamma
```


ガンマ値

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


ISO 12232で定義されたISO感度値に関する情報

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


このタグはISO 12232で定義されたISO感度緯度 yyy 値を示します。

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


このタグはISO 12232で定義されたISO感度緯度 zzz 値を示します。

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


画像のタイトルを示す文字列です。たとえば "1988 company picnic" のようなコメントになることがあります。

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


画像データの行数です。

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


画像のユニークIDです。

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


画像データの列数で、1行あたりのピクセル数に相当します。

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


JPEG 圧縮サムネイルデータの開始バイト (SOI) へのオフセットです。これは主画像の JPEG データには使用されません。

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


JPEG 圧縮サムネイルデータのバイト数です。これは主画像の JPEG データには使用されません。JPEG サムネイルは分割されず、SOI から EOI までの連続した JPEG ビットストリームとして記録されます。Appn と COM マーカーは記録すべきではありません。圧縮サムネイルは、APP1 に記録される他のすべてのデータを含めて 64 K バイト以下で記録しなければなりません。

### LensMake {#LensMake}
```
public static final int LensMake
```


このタグはレンズメーカーを記録します。

### LensModel {#LensModel}
```
public static final int LensModel
```


このタグはレンズのモデル名とモデル番号を記録します。

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


このタグは交換可能なレンズのシリアル番号を記録します

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


このタグは最小焦点距離、最大焦点距離、最小焦点距離における最小F値、最大焦点距離における最小F値を記録します

### LightSource {#LightSource}
```
public static final int LightSource
```


光源の種類です。

### Make {#Make}
```
public static final int Make
```


記録機器のメーカーです。これは画像を生成した DSC、スキャナ、ビデオデジタイザ、またはその他の機器のメーカーを示します。フィールドが空白の場合、未知として扱われます。

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Exif ライターメーカーが任意の情報を記録するためのタグです。内容はメーカー次第ですが、このタグは本来の目的以外には使用すべきではありません。

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


最大絞り値です。

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


測光モードです。

### Model {#Model}
```
public static final int Model
```


機器のモデル名またはモデル番号です。これは画像を生成した DSC、スキャナ、ビデオデジタイザ、またはその他の機器のモデル名または番号を示します。フィールドが空白の場合、未知として扱われます。

### OECF {#OECF}
```
public static final int OECF
```


ISO 14524で規定された光電変換関数（OECF）を示します。

### Orientation {#Orientation}
```
public static final int Orientation
```


行と列の観点から見た画像の向きです。

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


ISO 12232で規定されたカメラまたは入力デバイスのISO感度とISO緯度を示します。

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


ピクセル構成です。

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


圧縮データ固有の情報です。圧縮ファイルが記録される際、パディングデータやリスタートマーカーの有無にかかわらず、有効な画像幅をこのタグに記録します。

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


圧縮データ固有の情報です。圧縮ファイルが記録される際、有効な画像高さをこのタグに記録します。

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


ピクセル成分がチャンク形式かプラナ形式で記録されているかを示します。このフィールドが存在しない場合、TIFF のデフォルトである 1（チャンク）が使用されるとみなされます。

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


画像の 3 原色の色度です。通常、このタグは必要ありません。なぜなら、色空間は色空間情報の ColorSpace タグで指定されているからです。

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


推奨露出指数を示します

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


参照黒点値と参照白点値です。TIFF ではデフォルトは設定されていませんが、ここでは以下の値をデフォルトとして示します。色空間は色空間情報タグで宣言され、デフォルトは最適な画像特性を提供する値です。

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


関連するサウンドファイルです。

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


XResolution と YResolution の測定単位です。両方とも同じ単位が使用されます。画像解像度が不明な場合、2（インチ）が指定されます。

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


ストリップあたりの行数です。画像がストリップに分割される場合、1 ストリップ内の行数を示します。

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


ピクセルあたりのコンポーネント数です。この規格は RGB および YCbCr 画像に適用されるため、このタグの値は 3 に設定されています。

### Saturation {#Saturation}
```
public static final int Saturation
```


このタグは、画像が撮影されたときにカメラが適用した彩度処理の方向を示します。

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


このタグは撮影されたシーンのタイプを示します。また、画像が撮影されたモードを記録するためにも使用できます。

### SceneType {#SceneType}
```
public static final int SceneType
```


シーンのタイプを示します。DSCで画像が記録された場合、このタグの値は常に1に設定され、画像が直接撮影されたことを示します。

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


カメラまたは入力デバイスのイメージセンサータイプを示します。

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


写真感度のタイプ

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


このタグは、画像が撮影されたときにカメラが適用したシャープネス処理の方向を示します

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


シャッタースピードの値です。

### Software {#Software}
```
public static final int Software
```


このタグは画像生成に使用されたカメラまたは画像入力デバイスのソフトウェアまたはファームウェアの名前とバージョンを記録します。詳細な形式は指定されていませんが、以下の例に従うことが推奨されます。フィールドが空白の場合、未知として扱われます。

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


このタグは、ISO 12233で規定された画像幅、画像高さ、対角方向の空間周波数テーブルとSFR値をカメラまたは入力デバイスから記録します。

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


使用されたカメラの各チャンネルのスペクトル感度を示します。

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


カメラの標準出力感度を示します

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


各ストリップの総バイト数です。

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


各ストリップについて、そのストリップのバイトオフセットです。ストリップバイト数が64KBを超えないように選択することが推奨されます。Auxタグ。

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


このタグは、全体シーンにおける主被写体の位置と領域を示します。

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


被写体までの距離（メートル単位）です。

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


このタグは、被写体までの距離を示します。

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


シーン内の主対象の位置を示します。このタグの値は、Rotationタグに従った回転処理前に、左端から見た主対象の中心ピクセルを表します。

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


DateTimeタグの秒以下の小数部を記録するために使用されるタグです。

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


DateTimeDigitizedタグの秒以下の小数部を記録するために使用されるタグです。

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


DateTimeOriginalタグの秒以下の小数部を記録するために使用されるタグです。

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


画像の転送関数で、表形式で記述されます。通常、このタグは必要ありません。なぜなら、カラースペースはカラースペース情報のColorSpaceタグで指定されているからです。

### UserComment {#UserComment}
```
public static final int UserComment
```


ExifユーザーがImageDescriptionタグ以外のキーワードやコメントを書き込むためのタグで、ImageDescriptionタグの文字コード制限がありません。

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


このタグは、画像撮影時に設定されたホワイトバランスモードを示します。

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


画像の白色点の色度です。通常、このタグは必要ありません。カラースペースはカラースペース情報のColorSpaceタグで指定されているためです。

### XResolution {#XResolution}
```
public static final int XResolution
```


ImageWidth方向のResolutionUnitあたりのピクセル数です。画像の解像度が不明な場合、72[dpi]が指定されます。

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


RGBからYCbCr画像データへの変換のための行列係数です。

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


色差成分の位置を輝度成分に対して示します。このフィールドはJPEG圧縮データまたは非圧縮YCbCrデータにのみ指定されます。TIFFのデフォルトは1（センタリング）ですが、Y:Cb:Cr = 4:2:2 の場合、本標準では画像品質をテレビシステムでの表示時に向上させるために2（共置）を使用してデータを記録することが推奨されています。このフィールドが存在しない場合、リーダーはTIFFのデフォルトを想定します。Y:Cb:Cr = 4:2:0 の場合、TIFFのデフォルト（センタリング）が推奨されます。リーダーが両方のYCbCrPositioningに対応できない場合、フィールドの値に関わらずTIFFのデフォルトに従う必要があります。リーダーは「センタリングと共置の両方の位置決めをサポートできる」ことが望ましいです。

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


輝度成分に対する色差成分のサンプリング比です。

### YResolution {#YResolution}
```
public static final int YResolution
```


ImageLength方向のResolutionUnitあたりのピクセル数です。XResolutionと同じ値が指定されます。

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

