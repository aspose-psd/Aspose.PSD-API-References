---
title: "JpegExifData"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "JPEG ファイル用の EXIF データコンテナです。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.exif/jpegexifdata/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.exif.TiffDataTypeController](../../com.aspose.psd.exif/tiffdatatypecontroller)、[com.aspose.psd.exif.ExifData](../../com.aspose.psd.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

JPEG ファイル用の EXIF データコンテナです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | JpegExifData クラスの新しいインスタンスを初期化します。 |
| [JpegExifData(TiffDataType[] exifdata)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---) | 配列からデータを使用して JpegExifData クラスの新しいインスタンスを初期化します。 |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---) | 配列からデータを使用して JpegExifData クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MaxExifSegmentSize](#MaxExifSegmentSize) | 許可される最大 EXIF セグメントサイズ（バイト単位）。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApertureValue()](#getApertureValue--) | 絞り値を取得または設定します。 |
| [getArtist()](#getArtist--) | アーティストを取得または設定します。 |
| [getBitsPerSample()](#getBitsPerSample--) | サンプルあたりのビット数を取得または設定します。 |
| [getBodySerialNumber()](#getBodySerialNumber--) | カメラ本体のシリアル番号を取得または設定します。 |
| [getBrightnessValue()](#getBrightnessValue--) | 明るさの値を取得または設定します。 |
| [getCFAPattern()](#getCFAPattern--) | CFAパターンを取得または設定します。 |
| [getCameraOwnerName()](#getCameraOwnerName--) | カメラ所有者の名前を取得または設定します |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | カラースペースを取得または設定します。 |
| [getCommonTags()](#getCommonTags--) | 共通セクションに属するタグを取得または設定します。 |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | コンポーネント構成を取得または設定します。 |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | ピクセルあたりの圧縮ビット数を取得または設定します。 |
| [getCompression()](#getCompression--) | 圧縮を取得または設定します。 |
| [getContrast()](#getContrast--) | コントラストを取得または設定します。 |
| [getCopyright()](#getCopyright--) | 著作権情報を取得または設定します。 |
| [getCustomRendered()](#getCustomRendered--) | カスタムレンダリングを取得または設定します。 |
| [getDateTime()](#getDateTime--) | 日時を取得または設定します。 |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | 取得または設定します デジタル化日時。 |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | 取得または設定します オリジナル日時。 |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | 取得または設定します デバイス設定の説明。 |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | 取得または設定します デジタルズーム比率。 |
| [getExifTags()](#getExifTags--) | 取得または設定します EXIF セクションのみのタグ。 |
| [getExifVersion()](#getExifVersion--) | 取得または設定します EXIF バージョン。 |
| [getExposureBiasValue()](#getExposureBiasValue--) | 取得または設定します 露出補正値。 |
| [getExposureIndex()](#getExposureIndex--) | 取得または設定します 露出指数。 |
| [getExposureMode()](#getExposureMode--) | 取得または設定します 露出モード。 |
| [getExposureProgram()](#getExposureProgram--) | 取得または設定します 露出プログラム。 |
| [getExposureTime()](#getExposureTime--) | 取得または設定します 露出時間。 |
| [getFNumber()](#getFNumber--) | 取得または設定します F値。 |
| [getFileSource()](#getFileSource--) | 取得または設定します ファイルソースタイプ。 |
| [getFlash()](#getFlash--) | 取得または設定します フラッシュ。 |
| [getFlashEnergy()](#getFlashEnergy--) | 取得または設定します フラッシュエネルギー。 |
| [getFlashpixVersion()](#getFlashpixVersion--) | 取得または設定します フラッシュピクセルバージョン。 |
| [getFocalLength()](#getFocalLength--) | 取得または設定します 焦点距離。 |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | 取得または設定します 35mm フィルムの焦点距離。 |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | 取得または設定します 焦点面解像度単位。 |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | 取得または設定します 焦点面 X 解像度。 |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | 取得または設定します 焦点面 Y 解像度。 |
| [getGPSAltitude()](#getGPSAltitude--) | 取得または設定します GPS 高度。 |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | 取得または設定します 参照高度として使用される GPS 高度。 |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | 取得または設定します GPS エリア情報。 |
| [getGPSDOP()](#getGPSDOP--) | 取得または設定します GPS DOP（精度のデータ度）。 |
| [getGPSDateStamp()](#getGPSDateStamp--) | UTC（協定世界時）に相対する日付と時刻情報を記録する GPS 文字列を取得または設定します。 |
| [getGPSDestBearing()](#getGPSDestBearing--) | 目的地への GPS 方位を取得または設定します。 |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | 目的地への方位を示すために使用される GPS 基準を取得または設定します。 |
| [getGPSDestDistance()](#getGPSDestDistance--) | 目的地までの GPS 距離を取得または設定します。 |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | 目的地までの距離を表すために使用される GPS 単位を取得または設定します。 |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | 目的地の GPS 緯度を取得または設定します。 |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | 目的地の緯度が北緯か南緯かを示す GPS 値を取得または設定します。 |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | 目的地の GPS 経度を取得または設定します。 |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | 目的地の経度が東経か西経かを示す GPS 値を取得または設定します。 |
| [getGPSDifferential()](#getGPSDifferential--) | GPS 受信機に差分補正が適用されているかどうかを示す GPS 値を取得または設定します。 |
| [getGPSImgDirection()](#getGPSImgDirection--) | 画像が撮影されたときの GPS 方向を取得または設定します。 |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | 画像が撮影されたときの方向を示すための GPS 基準を取得または設定します。 |
| [getGPSLatitude()](#getGPSLatitude--) | GPS 緯度を取得または設定します。 |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | GPS 緯度が北緯か南緯かを取得または設定します。 |
| [getGPSLongitude()](#getGPSLongitude--) | GPS 経度を取得または設定します。 |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | GPS 経度が東経か西経かを取得または設定します。 |
| [getGPSMapDatum()](#getGPSMapDatum--) | GPS 受信機で使用される GPS 測地測量データを取得または設定します。 |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | GPS 測定モードを取得または設定します。 |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | 位置特定に使用された方法名を記録する GPS 文字列を取得または設定します。 |
| [getGPSSatellites()](#getGPSSatellites--) | 測定に使用される GPS 衛星を取得または設定します。 |
| [getGPSSpeed()](#getGPSSpeed--) | GPS 受信機の移動速度を取得または設定します。 |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | GPS 受信機の移動速度を表すために使用される単位を取得または設定します。 |
| [getGPSStatus()](#getGPSStatus--) | 画像が記録されたときの GPS 受信機の状態を取得または設定します。 |
| [getGPSTags()](#getGPSTags--) | GPS セクションのみ属するタグを取得または設定します。 |
| [getGPSTimestamp()](#getGPSTimestamp--) | UTC（協定世界時）としての GPS 時間を取得または設定します。 |
| [getGPSTrack()](#getGPSTrack--) | GPS受信機の移動方向を取得または設定します。 |
| [getGPSTrackRef()](#getGPSTrackRef--) | GPS受信機の移動方向を示す参照を取得または設定します。 |
| [getGPSVersionID()](#getGPSVersionID--) | GPSバージョン識別子を取得または設定します。 |
| [getGainControl()](#getGainControl--) | 全体画像ゲイン調整の度合いを取得または設定します。 |
| [getGamma()](#getGamma--) | ガンマを取得または設定します。 |
| [getISOSpeed()](#getISOSpeed--) | ISO感度を取得または設定します。 |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 yyy 値を取得または設定します。 |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 zzz 値を取得または設定します。 |
| [getImageDescription()](#getImageDescription--) | 画像の説明を取得または設定します。 |
| [getImageLength()](#getImageLength--) | 画像の長さを取得または設定します。 |
| [getImageUniqueID()](#getImageUniqueID--) | 画像のユニーク識別子を取得または設定します。 |
| [getImageWidth()](#getImageWidth--) | 画像の幅を取得または設定します。 |
| [getLensMake()](#getLensMake--) | レンズのメーカーを取得または設定します。 |
| [getLensModel()](#getLensModel--) | レンズモデルを取得または設定します。 |
| [getLensSerialNumber()](#getLensSerialNumber--) | レンズのシリアル番号を取得または設定します。 |
| [getLensSpecification()](#getLensSpecification--) | レンズ仕様を取得または設定します。 |
| [getLightSource()](#getLightSource--) | 光源を取得または設定します。 |
| [getMake()](#getMake--) | 録音機器の製造元を取得します。 |
| [getMakerNoteData()](#getMakerNoteData--) | メーカー注記データを取得します。 |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | メーカー注記の生データを取得または設定します。 |
| [getMakerNotes()](#getMakerNotes--) | メーカー注記を取得します。 |
| [getMaxApertureValue()](#getMaxApertureValue--) | 最大絞り値を取得または設定します。 |
| [getMeteringMode()](#getMeteringMode--) | 測光モードを取得または設定します。 |
| [getModel()](#getModel--) | モデルを取得または設定します。 |
| [getOECF()](#getOECF--) | ISO 14524で規定された光電変換関数 (OECF) を取得または設定します。 |
| [getOrientation()](#getOrientation--) | 向きを取得または設定します。 |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | 写真感度を取得または設定します。 |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | フォトメトリック解釈を取得または設定します。 |
| [getPixelXDimension()](#getPixelXDimension--) | ピクセルの X 軸寸法を取得または設定します。 |
| [getPixelYDimension()](#getPixelYDimension--) | ピクセルの Y 軸寸法を取得または設定します。 |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 平面構成を取得または設定します。 |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | 画像の 3 つの主要色の色度を取得または設定します。 |
| [getProperties()](#getProperties--) | すべての EXIF タグ（共通タグと GPS タグを含む）を取得または設定します。 |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | 推奨露出指数を取得または設定します。 |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | 参照黒白値を取得または設定します。 |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | 関連するサウンドファイルを取得または設定します。 |
| [getResolutionUnit()](#getResolutionUnit--) | 解像度単位を取得または設定します。 |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | ピクセルあたりのサンプル数を取得または設定します。 |
| [getSaturation()](#getSaturation--) | 彩度を取得または設定します。 |
| [getSceneCaptureType()](#getSceneCaptureType--) | シーンキャプチャタイプを取得または設定します。 |
| [getSceneType()](#getSceneType--) | シーンタイプを取得または設定します。 |
| [getSensingMethod()](#getSensingMethod--) | センシング方法を取得または設定します。 |
| [getSensitivityType()](#getSensitivityType--) | 感度タイプを取得または設定します。 |
| [getSharpness()](#getSharpness--) | シャープネスを取得または設定します。 |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | シャッタースピード値を取得または設定します。 |
| [getSoftware()](#getSoftware--) | ソフトウェアを取得または設定します。 |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | 空間周波数応答を取得または設定します。 |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | スペクトル感度を取得または設定します。 |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | 標準出力感度を取得します。 |
| [getSubjectArea()](#getSubjectArea--) | 被写体領域を取得または設定します。 |
| [getSubjectDistance()](#getSubjectDistance--) | 被写体距離を取得または設定します。 |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | 被写体距離範囲を取得または設定します。 |
| [getSubjectLocation()](#getSubjectLocation--) | 被写体位置を取得または設定します。 |
| [getSubsecTime()](#getSubsecTime--) | DateTime タグの秒以下の小数部を取得または設定します。 |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | DateTimeDigitized タグの秒以下の小数部を取得または設定します。 |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | DateTimeOriginal タグの秒以下の小数部を取得または設定します。 |
| [getThumbnail()](#getThumbnail--) | サムネイル画像を取得または設定します。 |
| [getTransferFunction()](#getTransferFunction--) | 転送関数を取得または設定します。 |
| [getUserComment()](#getUserComment--) | ユーザーコメントを取得または設定します。 |
| [getWhiteBalance()](#getWhiteBalance--) | ホワイトバランスを取得または設定します。 |
| [getWhitePoint()](#getWhitePoint--) | 画像の白色点の色度を取得または設定します。 |
| [getXResolution()](#getXResolution--) | X 解像度を取得または設定します。 |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | RGB から YCbCr 画像データへの変換に使用される行列係数を取得または設定します。 |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | 輝度成分に対する色差成分の位置を取得または設定します。 |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | 輝度成分に対する色差成分のサンプリング比率を取得または設定します。 |
| [getYResolution()](#getYResolution--) | Y 解像度を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isBigEndian()](#isBigEndian--) | ストリームから作成された EXIF データがビッグエンディアンかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tagId)](#removeTag-int-) | コンテナからタグを削除します。 |
| [serializeExifData()](#serializeExifData--) | EXIF データをシリアライズします。 |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | 絞り値を取得または設定します。 |
| [setArtist(String value)](#setArtist-java.lang.String-) | アーティストを取得または設定します。 |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | ストリームから作成された EXIF データがビッグエンディアンかどうかを示す値を取得または設定します。 |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | サンプルあたりのビット数を取得または設定します。 |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | カメラ本体のシリアル番号を取得または設定します。 |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 明るさの値を取得または設定します。 |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | CFAパターンを取得または設定します。 |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | カメラ所有者の名前を取得または設定します |
| [setColorSpace(int value)](#setColorSpace-int-) | カラースペースを取得または設定します。 |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 共通セクションに属するタグを取得または設定します。 |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | コンポーネント構成を取得または設定します。 |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-) | ピクセルあたりの圧縮ビット数を取得または設定します。 |
| [setCompression(int value)](#setCompression-int-) | 圧縮を取得または設定します。 |
| [setContrast(int value)](#setContrast-int-) | コントラストを取得または設定します。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 著作権情報を取得または設定します。 |
| [setCustomRendered(int value)](#setCustomRendered-int-) | カスタムレンダリングを取得または設定します。 |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | 日時を取得または設定します。 |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | 取得または設定します デジタル化日時。 |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | 取得または設定します オリジナル日時。 |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | 取得または設定します デバイス設定の説明。 |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します デジタルズーム比率。 |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 取得または設定します EXIF セクションのみのタグ。 |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | 取得または設定します EXIF バージョン。 |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | 取得または設定します 露出補正値。 |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します 露出指数。 |
| [setExposureMode(int value)](#setExposureMode-int-) | 取得または設定します 露出モード。 |
| [setExposureProgram(int value)](#setExposureProgram-int-) | 取得または設定します 露出プログラム。 |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します 露出時間。 |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します F値。 |
| [setFileSource(byte value)](#setFileSource-byte-) | 取得または設定します ファイルソースタイプ。 |
| [setFlash(int value)](#setFlash-int-) | 取得または設定します フラッシュ。 |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します フラッシュエネルギー。 |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | 取得または設定します フラッシュピクセルバージョン。 |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します 焦点距離。 |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | 取得または設定します 35mm フィルムの焦点距離。 |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | 取得または設定します 焦点面解像度単位。 |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します 焦点面 X 解像度。 |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します 焦点面 Y 解像度。 |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します GPS 高度。 |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | 取得または設定します 参照高度として使用される GPS 高度。 |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | 取得または設定します GPS エリア情報。 |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-) | 取得または設定します GPS DOP（精度のデータ度）。 |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | UTC（協定世界時）に相対する日付と時刻情報を記録する GPS 文字列を取得または設定します。 |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-) | 目的地への GPS 方位を取得または設定します。 |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | 目的地への方位を示すために使用される GPS 基準を取得または設定します。 |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | 目的地までの GPS 距離を取得または設定します。 |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | 目的地までの距離を表すために使用される GPS 単位を取得または設定します。 |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 目的地の GPS 緯度を取得または設定します。 |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | 目的地の緯度が北緯か南緯かを示す GPS 値を取得または設定します。 |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | 目的地の GPS 経度を取得または設定します。 |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | 目的地の経度が東経か西経かを示す GPS 値を取得または設定します。 |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | GPS 受信機に差分補正が適用されているかどうかを示す GPS 値を取得または設定します。 |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-) | 画像が撮影されたときの GPS 方向を取得または設定します。 |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | 画像が撮影されたときの方向を示すための GPS 基準を取得または設定します。 |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---) | GPS 緯度を取得または設定します。 |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | GPS 緯度が北緯か南緯かを取得または設定します。 |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---) | GPS 経度を取得または設定します。 |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | GPS 経度が東経か西経かを取得または設定します。 |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | GPS 受信機で使用される GPS 測地測量データを取得または設定します。 |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | GPS 測定モードを取得または設定します。 |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | 位置特定に使用された方法名を記録する GPS 文字列を取得または設定します。 |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | 測定に使用される GPS 衛星を取得または設定します。 |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-) | GPS 受信機の移動速度を取得または設定します。 |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | GPS 受信機の移動速度を表すために使用される単位を取得または設定します。 |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | 画像が記録されたときの GPS 受信機の状態を取得または設定します。 |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | GPS セクションのみ属するタグを取得または設定します。 |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---) | UTC（協定世界時）としての GPS 時間を取得または設定します。 |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | GPS受信機の移動方向を取得または設定します。 |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | GPS受信機の移動方向を示す参照を取得または設定します。 |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | GPSバージョン識別子を取得または設定します。 |
| [setGainControl(int value)](#setGainControl-int-) | 全体画像ゲイン調整の度合いを取得または設定します。 |
| [setGamma(TiffRational value)](#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-) | ガンマを取得または設定します。 |
| [setISOSpeed(long value)](#setISOSpeed-long-) | ISO感度を取得または設定します。 |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 yyy 値を取得または設定します。 |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 zzz 値を取得または設定します。 |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | 画像の説明を取得または設定します。 |
| [setImageLength(long value)](#setImageLength-long-) | 画像の長さを取得または設定します。 |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | 画像のユニーク識別子を取得または設定します。 |
| [setImageWidth(long value)](#setImageWidth-long-) | 画像の幅を取得または設定します。 |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | レンズのメーカーを取得または設定します。 |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | レンズモデルを取得または設定します。 |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | レンズのシリアル番号を取得または設定します。 |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---) | レンズ仕様を取得または設定します。 |
| [setLightSource(int value)](#setLightSource-int-) | 光源を取得または設定します。 |
| [setMake(String value)](#setMake-java.lang.String-) | 録音機器のメーカーを設定します。 |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | メーカー注記の生データを取得または設定します。 |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-) | 最大絞り値を取得または設定します。 |
| [setMeteringMode(int value)](#setMeteringMode-int-) | 測光モードを取得または設定します。 |
| [setModel(String value)](#setModel-java.lang.String-) | モデルを取得または設定します。 |
| [setOECF(byte[] value)](#setOECF-byte---) | ISO 14524で規定された光電変換関数 (OECF) を取得または設定します。 |
| [setOrientation(int value)](#setOrientation-int-) | 向きを取得または設定します。 |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | 写真感度を取得または設定します。 |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | フォトメトリック解釈を取得または設定します。 |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | ピクセルの X 軸寸法を取得または設定します。 |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | ピクセルの Y 軸寸法を取得または設定します。 |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | 平面構成を取得または設定します。 |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---) | 画像の 3 つの主要色の色度を取得または設定します。 |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---) | すべての EXIF タグ（共通タグと GPS タグを含む）を取得または設定します。 |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | 推奨露出指数を取得または設定します。 |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---) | 参照黒白値を取得または設定します。 |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | 関連するサウンドファイルを取得または設定します。 |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 解像度単位を取得または設定します。 |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | ピクセルあたりのサンプル数を取得または設定します。 |
| [setSaturation(int value)](#setSaturation-int-) | 彩度を取得または設定します。 |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | シーンキャプチャタイプを取得または設定します。 |
| [setSceneType(byte value)](#setSceneType-byte-) | シーンタイプを取得または設定します。 |
| [setSensingMethod(int value)](#setSensingMethod-int-) | センシング方法を取得または設定します。 |
| [setSensitivityType(int value)](#setSensitivityType-int-) | 感度タイプを取得または設定します。 |
| [setSharpness(int value)](#setSharpness-int-) | シャープネスを取得または設定します。 |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-) | シャッタースピード値を取得または設定します。 |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | ソフトウェアを取得または設定します。 |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | 空間周波数応答を取得または設定します。 |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | スペクトル感度を取得または設定します。 |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | 標準出力感度を設定します |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | 被写体領域を取得または設定します。 |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-) | 被写体距離を取得または設定します。 |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | 被写体距離範囲を取得または設定します。 |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | 被写体位置を取得または設定します。 |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | DateTime タグの秒以下の小数部を取得または設定します。 |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | DateTimeDigitized タグの秒以下の小数部を取得または設定します。 |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | DateTimeOriginal タグの秒以下の小数部を取得または設定します。 |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.psd.RasterImage-) | サムネイル画像を取得または設定します。 |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | 転送関数を取得または設定します。 |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | ユーザーコメントを取得または設定します。 |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | ホワイトバランスを取得または設定します。 |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---) | 画像の白色点の色度を取得または設定します。 |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | X 解像度を取得または設定します。 |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | RGB から YCbCr 画像データへの変換に使用される行列係数を取得または設定します。 |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | 輝度成分に対する色差成分の位置を取得または設定します。 |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | 輝度成分に対する色差成分のサンプリング比率を取得または設定します。 |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Y 解像度を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


JpegExifData クラスの新しいインスタンスを初期化します。

### JpegExifData(TiffDataType[] exifdata) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifdata)
```


配列からデータを使用して JpegExifData クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 共通タグとGPSタグを含むEXIFタグの配列です。 |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


配列からデータを使用して JpegExifData クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 共通タグです。 |
| exifTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | EXIFタグです。 |
| gpsTags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | GPSタグです。 |

### MaxExifSegmentSize {#MaxExifSegmentSize}
```
public static final int MaxExifSegmentSize
```


許可される最大 EXIF セグメントサイズ（バイト単位）。

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
### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


絞り値を取得または設定します。

値: 絞り値です。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getArtist() {#getArtist--}
```
public String getArtist()
```


アーティストを取得または設定します。

値: アーティスト。

**Returns:**
java.lang.String
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


サンプルあたりのビット数を取得または設定します。

値: サンプルあたりのビット数。

**Returns:**
int[]
### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


カメラ本体のシリアル番号を取得または設定します。

値: 本体シリアル番号です。

**Returns:**
java.lang.String
### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


明るさの値を取得または設定します。

値: 明るさの値です。

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


CFAパターンを取得または設定します。

値: CFAパターンです。

**Returns:**
byte[]
### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


カメラ所有者の名前を取得または設定します

値: カメラ所有者の名前です。

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


カラースペースを取得または設定します。

値: カラースペースです。

**Returns:**
int
### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


共通セクションに属するタグを取得または設定します。これはjpeg画像にのみ適用され、tiff形式では代わりにtiffOptionsが使用されます。

値: 共通セクションのタグです。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


コンポーネント構成を取得または設定します。

値: コンポーネント構成です。

**Returns:**
byte[]
### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


ピクセルあたりの圧縮ビット数を取得または設定します。

値: ピクセルあたりの圧縮ビット数です。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getCompression() {#getCompression--}
```
public int getCompression()
```


圧縮を取得または設定します。

値: 圧縮方式。

**Returns:**
int
### getContrast() {#getContrast--}
```
public int getContrast()
```


コントラストを取得または設定します。

値: コントラストです。

**Returns:**
int
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


著作権情報を取得または設定します。

値: 著作権情報。

**Returns:**
java.lang.String
### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


カスタムレンダリングを取得または設定します。

値: カスタムレンダリングです。

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


日時を取得または設定します。

値: 日付と時刻。

**Returns:**
java.lang.String
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


取得または設定します デジタル化日時。

値: デジタル化日時です。

**Returns:**
java.lang.String
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


取得または設定します オリジナル日時。

値: 元の日時です。

**Returns:**
java.lang.String
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


取得または設定します デバイス設定の説明。

値: デバイス設定の説明です。

**Returns:**
byte[]
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


取得または設定します デジタルズーム比率。

値: デジタルズーム比率です。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


取得または設定します EXIF セクションのみのタグ。

値: EXIFセクションのタグです。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


取得または設定します EXIF バージョン。

値: EXIFバージョンです。

**Returns:**
byte[]
### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


取得または設定します 露出補正値。

値: 露出補正値です。

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


取得または設定します 露出指数。

値: 露出のインデックス。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


取得または設定します 露出モード。

値: 露出モード。

**Returns:**
int
### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


取得または設定します 露出プログラム。

値: 露出プログラム。

**Returns:**
int
### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


取得または設定します 露出時間。

値: 露出時間。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


取得または設定します F値。

値: F値。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


取得または設定します ファイルソースタイプ。

値: ファイルソースの種類。

**Returns:**
byte
### getFlash() {#getFlash--}
```
public int getFlash()
```


取得または設定します フラッシュ。

値: フラッシュ。

**Returns:**
int
### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


取得または設定します フラッシュエネルギー。

値: フラッシュエネルギー。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


取得または設定します フラッシュピクセルバージョン。

値: フラッシュ pix バージョン。

**Returns:**
byte[]
### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


取得または設定します 焦点距離。

値: 焦点の長さ。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


取得または設定します 35mm フィルムの焦点距離。

値: 35mmフィルムの焦点距離。

**Returns:**
int
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


取得または設定します 焦点面解像度単位。

値: 焦点面解像度単位。

**Returns:**
int
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


取得または設定します 焦点面 X 解像度。

値: 焦点面のX解像度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


取得または設定します 焦点面 Y 解像度。

値: 焦点面のY解像度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


取得または設定します GPS 高度。

値: GPS高度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


取得または設定します 参照高度として使用される GPS 高度。

値: 基準高度として使用されるGPS高度。

**Returns:**
byte
### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


取得または設定します GPS エリア情報。

値: GPSエリア情報。

**Returns:**
byte[]
### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


取得または設定します GPS DOP（精度のデータ度）。

値: GPS DOP（データ精度の度合い）。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


UTC（協定世界時）に相対する日付と時刻情報を記録する GPS 文字列を取得または設定します。

値: UTC（協定世界時）に相対する日時情報を記録するGPS文字列。

**Returns:**
java.lang.String
### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


目的地への GPS 方位を取得または設定します。

値: 目的地点へのGPS方位。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


目的地への方位を示すために使用される GPS 基準を取得または設定します。

値: 目的地点への方位を示すために使用されるGPS参照。

**Returns:**
java.lang.String
### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


目的地までの GPS 距離を取得または設定します。

値: 目的地点までのGPS距離。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


目的地までの距離を表すために使用される GPS 単位を取得または設定します。

値: 目的地点までの距離を表すために使用されるGPS単位。

**Returns:**
java.lang.String
### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


目的地の GPS 緯度を取得または設定します。

値: 目的地点のGPS緯度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


目的地の緯度が北緯か南緯かを示す GPS 値を取得または設定します。

値: 目的地点の緯度が北緯か南緯かを示すGPS値。

**Returns:**
java.lang.String
### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


目的地の GPS 経度を取得または設定します。

値: 目的地点のGPS経度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


目的地の経度が東経か西経かを示す GPS 値を取得または設定します。

値: 目的地点の経度が東経か西経かを示すGPS値。

**Returns:**
java.lang.String
### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


GPS 受信機に差分補正が適用されているかどうかを示す GPS 値を取得または設定します。

値: GPS受信機に差分補正が適用されているかどうかを示すGPS値。

**Returns:**
int
### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


画像が撮影されたときの GPS 方向を取得または設定します。

値: 画像が撮影されたときのGPS方向。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


画像が撮影されたときの方向を示すための GPS 基準を取得または設定します。

値: 画像が撮影されたときの方向を示すGPS参照。

**Returns:**
java.lang.String
### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


GPS 緯度を取得または設定します。

値: GPS緯度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


GPS 緯度が北緯か南緯かを取得または設定します。

値: GPS緯度が北緯か南緯か。

**Returns:**
java.lang.String
### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


GPS 経度を取得または設定します。

値: GPS経度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


GPS 経度が東経か西経かを取得または設定します。

値: GPS経度が東経か西経か。

**Returns:**
java.lang.String
### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


GPS 受信機で使用される GPS 測地測量データを取得または設定します。

値: GPS受信機が使用するGPS測地測量データ。

**Returns:**
java.lang.String
### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


GPS 測定モードを取得または設定します。

値: GPS測定モード。

**Returns:**
java.lang.String
### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


位置特定に使用された方法名を記録する GPS 文字列を取得または設定します。

値: 位置特定に使用された方法名を記録するGPS文字列。

**Returns:**
byte[]
### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


測定に使用される GPS 衛星を取得または設定します。

値: 測定に使用されたGPS衛星。

**Returns:**
java.lang.String
### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


GPS 受信機の移動速度を取得または設定します。

値: GPS受信機の移動速度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


GPS 受信機の移動速度を表すために使用される単位を取得または設定します。

値: GPS受信機の移動速度を表す単位。

**Returns:**
java.lang.String
### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


画像が記録されたときの GPS 受信機の状態を取得または設定します。

値: 画像が記録されたときのGPS受信機の状態。

**Returns:**
java.lang.String
### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


GPS セクションのみ属するタグを取得または設定します。

値: GPSタグ。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


UTC（協定世界時）としての GPS 時間を取得または設定します。

値: UTC（協定世界時）としてのGPS時間。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


GPS受信機の移動方向を取得または設定します。

値: GPS受信機の移動方向。

**Returns:**
java.lang.String
### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


GPS受信機の移動方向を示す参照を取得または設定します。

値: GPS受信機の移動方向を示す参照。

**Returns:**
java.lang.String
### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


GPSバージョン識別子を取得または設定します。

値: GPSバージョン識別子。

**Returns:**
byte[]
### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


全体画像ゲイン調整の度合いを取得または設定します。

値: 画像全体のゲイン調整度合い。

**Returns:**
int
### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


ガンマを取得または設定します。

値: ガンマ値。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


ISO感度を取得または設定します。

値: ISO感度。

**Returns:**
long
### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 yyy 値を取得または設定します。

値: ISO 12232で定義されているカメラまたは入力デバイスのISO speed latitude yyy値。

このタグはISOSpeedとISOSpeedLatitudezzzがない場合は記録できません。

**Returns:**
long
### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 zzz 値を取得または設定します。

値: ISO 12232で定義されているカメラまたは入力デバイスのISO speed latitude zzz値。

このタグはISOSpeedとISOSpeedLatitudeyyyがない場合は記録できません。

**Returns:**
long
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


画像の説明を取得または設定します。

値: 画像の説明。

**Returns:**
java.lang.String
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


画像の長さを取得または設定します。

値: 画像の長さ。

**Returns:**
long
### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


画像のユニーク識別子を取得または設定します。

値: 画像の一意識別子。

**Returns:**
java.lang.String
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


画像の幅を取得または設定します。

値: 画像の幅。

**Returns:**
long
### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


レンズのメーカーを取得または設定します。

値: レンズメーカー。

**Returns:**
java.lang.String
### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


レンズモデルを取得または設定します。

値: レンズモデル。

**Returns:**
java.lang.String
### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


レンズのシリアル番号を取得または設定します。

値: レンズシリアル番号。

**Returns:**
java.lang.String
### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


レンズ仕様を取得または設定します。

値: レンズ仕様。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


光源を取得または設定します。

値: 光源。

**Returns:**
int
### getMake() {#getMake--}
```
public final String getMake()
```


録音機器の製造元を取得します。

値: 録音機器の製造元。

**Returns:**
java.lang.String - 録音機器の製造元。
### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


メーカー注記データを取得します。

値: メーカーノートデータ。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


メーカー注記の生データを取得または設定します。

値: メーカーノートの生データ。

**Returns:**
byte[]
### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


メーカー注記を取得します。

値: メーカーノート。

**Returns:**
com.aspose.psd.exif.MakerNote[] - メーカーノート。
### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


最大絞り値を取得または設定します。

値: 最大絞り値。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


測光モードを取得または設定します。

値: 測光モード。

**Returns:**
int
### getModel() {#getModel--}
```
public String getModel()
```


モデルを取得または設定します。

値: モデル。

**Returns:**
java.lang.String
### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


ISO 14524で規定された光電変換関数 (OECF) を取得または設定します。

値: ISO 14524で規定された光電変換関数（OECF）。

**Returns:**
byte[]
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


向きを取得または設定します。

値: 方向。

**Returns:**
int
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


写真感度を取得または設定します。

値: 写真感度。

**Returns:**
long
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


フォトメトリック解釈を取得または設定します。

値: フォトメトリック解釈。

**Returns:**
int
### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


ピクセルの X 軸寸法を取得または設定します。

値: ピクセルのX寸法。

**Returns:**
long
### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


ピクセルの Y 軸寸法を取得または設定します。

値: ピクセルのY寸法。

**Returns:**
long
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


平面構成を取得または設定します。

値: プレーナ構成。

**Returns:**
int
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


画像の 3 つの主要色の色度を取得または設定します。

値: 画像の3つの主要色の色度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


すべての EXIF タグ（共通タグと GPS タグを含む）を取得または設定します。

値: EXIFタグ（共通タグとGPSタグを含む）。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[]
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


推奨露出指数を取得または設定します。

値: 推奨露出指数。

**Returns:**
long
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


参照黒白値を取得または設定します。

値: 基準黒白。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


関連するサウンドファイルを取得または設定します。

値: 関連するサウンドファイル。

**Returns:**
java.lang.String
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


解像度単位を取得または設定します。

値: 解像度単位。

**Returns:**
int
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


ピクセルあたりのサンプル数を取得または設定します。

値: ピクセルあたりのサンプル数。

**Returns:**
int
### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


彩度を取得または設定します。

値: 飽和度。

**Returns:**
int
### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


シーンキャプチャタイプを取得または設定します。

値: シーンキャプチャのタイプ。

**Returns:**
int
### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


シーンタイプを取得または設定します。

値: シーンのタイプ。

**Returns:**
byte
### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


センシング方法を取得または設定します。

値: センシング方法。

**Returns:**
int
### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


感度タイプを取得または設定します。

値: 感度の種類。

**Returns:**
int
### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


シャープネスを取得または設定します。

値: 鮮明度。

**Returns:**
int
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


シャッタースピード値を取得または設定します。

値: シャッタースピード値。

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational)
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


ソフトウェアを取得または設定します。

値: ソフトウェア。

**Returns:**
java.lang.String
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


空間周波数応答を取得または設定します。

値: 空間周波数応答。

**Returns:**
byte[]
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


スペクトル感度を取得または設定します。

値: スペクトル感度。

**Returns:**
java.lang.String
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


標準出力感度を取得します。

値: 標準出力感度。

**Returns:**
long
### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


被写体領域を取得または設定します。

値: 被写体領域。

**Returns:**
int[]
### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


被写体距離を取得または設定します。

値: 被写体距離。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


被写体距離範囲を取得または設定します。

値: 被写体距離範囲。

**Returns:**
int
### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


被写体位置を取得または設定します。

値: 被写体位置。

**Returns:**
int[]
### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


DateTime タグの秒以下の小数部を取得または設定します。

値: DateTime タグの秒以下の小数。

**Returns:**
java.lang.String
### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


DateTimeDigitized タグの秒以下の小数部を取得または設定します。

値: DateTimeDigitized タグの秒以下の小数。

**Returns:**
java.lang.String
### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


DateTimeOriginal タグの秒以下の小数部を取得または設定します。

値: DateTimeOriginal タグの秒以下の小数。

**Returns:**
java.lang.String
### getThumbnail() {#getThumbnail--}
```
public RasterImage getThumbnail()
```


サムネイル画像を取得または設定します。

値: サムネイル。

**Returns:**
[RasterImage](../../com.aspose.psd/rasterimage)
### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


転送関数を取得または設定します。

値: 転送関数。

**Returns:**
int[]
### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


ユーザーコメントを取得または設定します。

値: ユーザーコメント。

**Returns:**
java.lang.String
### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


ホワイトバランスを取得または設定します。

値: ホワイトバランス。

**Returns:**
int
### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


画像の白色点の色度を取得または設定します。

値: 画像の白色点の色度。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


X 解像度を取得または設定します。

値: X 解像度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


RGB から YCbCr 画像データへの変換に使用される行列係数を取得または設定します。

値: RGB から YCbCr 画像データへの変換用行列係数。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[]
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


輝度成分に対する色差成分の位置を取得または設定します。

値: 輝度成分に対する色差成分の位置。

**Returns:**
int
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


輝度成分に対する色差成分のサンプリング比率を取得または設定します。

値: 輝度成分に対する色差成分のサンプリング比率。

**Returns:**
int[]
### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Y 解像度を取得または設定します。

値: y 解像度。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational)
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


ストリームから作成された EXIF データがビッグエンディアンかどうかを示す値を取得または設定します。

値:  true で、ストリームの EXIF データがビッグエンディアンで作成された場合; それ以外の場合は  false です。

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


コンテナからタグを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tagId | int | 削除するタグ識別子。 |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


EXIF データをシリアライズします。タグの値と内容を書き込みます。サイズに最も影響するタグはサムネイルタグの内容です。

**Returns:**
byte[] - シリアライズされた EXIF データ。

正しい JPEG 画像を生成するために、全体のセグメントサイズは MaxExifSegmentSize バイト以下である必要があります。ヒント: サムネイルサイズを縮小するか、圧縮方式を変更して、EXIF セクションのサイズが大きすぎる場合に対処してください。
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


絞り値を取得または設定します。

値: 絞り値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


アーティストを取得または設定します。

値: アーティスト。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


ストリームから作成された EXIF データがビッグエンディアンかどうかを示す値を取得または設定します。

値:  true で、ストリームの EXIF データがビッグエンディアンで作成された場合; それ以外の場合は  false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


サンプルあたりのビット数を取得または設定します。

値: サンプルあたりのビット数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


カメラ本体のシリアル番号を取得または設定します。

値: 本体シリアル番号です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


明るさの値を取得または設定します。

値: 明るさの値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


CFAパターンを取得または設定します。

値: CFAパターンです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


カメラ所有者の名前を取得または設定します

値: カメラ所有者の名前です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


カラースペースを取得または設定します。

値: カラースペースです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


共通セクションに属するタグを取得または設定します。これはjpeg画像にのみ適用され、tiff形式では代わりにtiffOptionsが使用されます。

値: 共通セクションのタグです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


コンポーネント構成を取得または設定します。

値: コンポーネント構成です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


ピクセルあたりの圧縮ビット数を取得または設定します。

値: ピクセルあたりの圧縮ビット数です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


圧縮を取得または設定します。

値: 圧縮方式。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


コントラストを取得または設定します。

値: コントラストです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


著作権情報を取得または設定します。

値: 著作権情報。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


カスタムレンダリングを取得または設定します。

値: カスタムレンダリングです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


日時を取得または設定します。

値: 日付と時刻。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


取得または設定します デジタル化日時。

値: デジタル化日時です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


取得または設定します オリジナル日時。

値: 元の日時です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


取得または設定します デバイス設定の説明。

値: デバイス設定の説明です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


取得または設定します デジタルズーム比率。

値: デジタルズーム比率です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


取得または設定します EXIF セクションのみのタグ。

値: EXIFセクションのタグです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


取得または設定します EXIF バージョン。

値: EXIFバージョンです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


取得または設定します 露出補正値。

値: 露出補正値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


取得または設定します 露出指数。

値: 露出のインデックス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


取得または設定します 露出モード。

値: 露出モード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


取得または設定します 露出プログラム。

値: 露出プログラム。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


取得または設定します 露出時間。

値: 露出時間。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFNumber(TiffRational value) {#setFNumber-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


取得または設定します F値。

値: F値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


取得または設定します ファイルソースタイプ。

値: ファイルソースの種類。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


取得または設定します フラッシュ。

値: フラッシュ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


取得または設定します フラッシュエネルギー。

値: フラッシュエネルギー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


取得または設定します フラッシュピクセルバージョン。

値: フラッシュ pix バージョン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


取得または設定します 焦点距離。

値: 焦点の長さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


取得または設定します 35mm フィルムの焦点距離。

値: 35mmフィルムの焦点距離。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


取得または設定します 焦点面解像度単位。

値: 焦点面解像度単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


取得または設定します 焦点面 X 解像度。

値: 焦点面のX解像度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


取得または設定します 焦点面 Y 解像度。

値: 焦点面のY解像度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


取得または設定します GPS 高度。

値: GPS高度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


取得または設定します 参照高度として使用される GPS 高度。

値: 基準高度として使用されるGPS高度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


取得または設定します GPS エリア情報。

値: GPSエリア情報。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


取得または設定します GPS DOP（精度のデータ度）。

値: GPS DOP（データ精度の度合い）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


UTC（協定世界時）に相対する日付と時刻情報を記録する GPS 文字列を取得または設定します。

値: UTC（協定世界時）に相対する日時情報を記録するGPS文字列。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


目的地への GPS 方位を取得または設定します。

値: 目的地点へのGPS方位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


目的地への方位を示すために使用される GPS 基準を取得または設定します。

値: 目的地点への方位を示すために使用されるGPS参照。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


目的地までの GPS 距離を取得または設定します。

値: 目的地点までのGPS距離。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


目的地までの距離を表すために使用される GPS 単位を取得または設定します。

値: 目的地点までの距離を表すために使用されるGPS単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


目的地の GPS 緯度を取得または設定します。

値: 目的地点のGPS緯度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


目的地の緯度が北緯か南緯かを示す GPS 値を取得または設定します。

値: 目的地点の緯度が北緯か南緯かを示すGPS値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


目的地の GPS 経度を取得または設定します。

値: 目的地点のGPS経度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


目的地の経度が東経か西経かを示す GPS 値を取得または設定します。

値: 目的地点の経度が東経か西経かを示すGPS値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


GPS 受信機に差分補正が適用されているかどうかを示す GPS 値を取得または設定します。

値: GPS受信機に差分補正が適用されているかどうかを示すGPS値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


画像が撮影されたときの GPS 方向を取得または設定します。

値: 画像が撮影されたときのGPS方向。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


画像が撮影されたときの方向を示すための GPS 基準を取得または設定します。

値: 画像が撮影されたときの方向を示すGPS参照。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


GPS 緯度を取得または設定します。

値: GPS緯度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


GPS 緯度が北緯か南緯かを取得または設定します。

値: GPS緯度が北緯か南緯か。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


GPS 経度を取得または設定します。

値: GPS経度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


GPS 経度が東経か西経かを取得または設定します。

値: GPS経度が東経か西経か。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


GPS 受信機で使用される GPS 測地測量データを取得または設定します。

値: GPS受信機が使用するGPS測地測量データ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


GPS 測定モードを取得または設定します。

値: GPS測定モード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


位置特定に使用された方法名を記録する GPS 文字列を取得または設定します。

値: 位置特定に使用された方法名を記録するGPS文字列。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


測定に使用される GPS 衛星を取得または設定します。

値: 測定に使用されたGPS衛星。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


GPS 受信機の移動速度を取得または設定します。

値: GPS受信機の移動速度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


GPS 受信機の移動速度を表すために使用される単位を取得または設定します。

値: GPS受信機の移動速度を表す単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


画像が記録されたときの GPS 受信機の状態を取得または設定します。

値: 画像が記録されたときのGPS受信機の状態。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


GPS セクションのみ属するタグを取得または設定します。

値: GPSタグ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


UTC（協定世界時）としての GPS 時間を取得または設定します。

値: UTC（協定世界時）としてのGPS時間。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


GPS受信機の移動方向を取得または設定します。

値: GPS受信機の移動方向。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


GPS受信機の移動方向を示す参照を取得または設定します。

値: GPS受信機の移動方向を示す参照。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


GPSバージョン識別子を取得または設定します。

値: GPSバージョン識別子。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


全体画像ゲイン調整の度合いを取得または設定します。

値: 画像全体のゲイン調整度合い。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGamma(TiffRational value) {#setGamma-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


ガンマを取得または設定します。

値: ガンマ値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


ISO感度を取得または設定します。

値: ISO感度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 yyy 値を取得または設定します。

値: ISO 12232で定義されているカメラまたは入力デバイスのISO speed latitude yyy値。

このタグはISOSpeedとISOSpeedLatitudezzzがない場合は記録できません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


ISO 12232で定義されたカメラまたは入力デバイスのISO感度緯度 zzz 値を取得または設定します。

値: ISO 12232で定義されているカメラまたは入力デバイスのISO speed latitude zzz値。

このタグはISOSpeedとISOSpeedLatitudeyyyがない場合は記録できません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


画像の説明を取得または設定します。

値: 画像の説明。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


画像の長さを取得または設定します。

値: 画像の長さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


画像のユニーク識別子を取得または設定します。

値: 画像の一意識別子。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


画像の幅を取得または設定します。

値: 画像の幅。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


レンズのメーカーを取得または設定します。

値: レンズメーカー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


レンズモデルを取得または設定します。

値: レンズモデル。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


レンズのシリアル番号を取得または設定します。

値: レンズシリアル番号。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


レンズ仕様を取得または設定します。

値: レンズ仕様。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


光源を取得または設定します。

値: 光源。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


録音機器のメーカーを設定します。

値: 録音機器の製造元。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 録音機器の製造元。 |

### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


メーカー注記の生データを取得または設定します。

値: メーカーノートの生データ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


最大絞り値を取得または設定します。

値: 最大絞り値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


測光モードを取得または設定します。

値: 測光モード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


モデルを取得または設定します。

値: モデル。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


ISO 14524で規定された光電変換関数 (OECF) を取得または設定します。

値: ISO 14524で規定された光電変換関数（OECF）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


向きを取得または設定します。

値: 方向。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


写真感度を取得または設定します。

値: 写真感度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


フォトメトリック解釈を取得または設定します。

値: フォトメトリック解釈。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


ピクセルの X 軸寸法を取得または設定します。

値: ピクセルのX寸法。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


ピクセルの Y 軸寸法を取得または設定します。

値: ピクセルのY寸法。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


平面構成を取得または設定します。

値: プレーナ構成。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


画像の 3 つの主要色の色度を取得または設定します。

値: 画像の3つの主要色の色度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setProperties(TiffDataType[] value) {#setProperties-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


すべての EXIF タグ（共通タグと GPS タグを含む）を取得または設定します。

値: EXIFタグ（共通タグとGPSタグを含む）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) |  |

### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


推奨露出指数を取得または設定します。

値: 推奨露出指数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


参照黒白値を取得または設定します。

値: 基準黒白。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


関連するサウンドファイルを取得または設定します。

値: 関連するサウンドファイル。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


解像度単位を取得または設定します。

値: 解像度単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


ピクセルあたりのサンプル数を取得または設定します。

値: ピクセルあたりのサンプル数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


彩度を取得または設定します。

値: 飽和度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


シーンキャプチャタイプを取得または設定します。

値: シーンキャプチャのタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


シーンタイプを取得または設定します。

値: シーンのタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


センシング方法を取得または設定します。

値: センシング方法。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


感度タイプを取得または設定します。

値: 感度の種類。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


シャープネスを取得または設定します。

値: 鮮明度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


シャッタースピード値を取得または設定します。

値: シャッタースピード値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) |  |

### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


ソフトウェアを取得または設定します。

値: ソフトウェア。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


空間周波数応答を取得または設定します。

値: 空間周波数応答。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


スペクトル感度を取得または設定します。

値: スペクトル感度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


標準出力感度を設定します

値: 標準出力感度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


被写体領域を取得または設定します。

値: 被写体領域。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


被写体距離を取得または設定します。

値: 被写体距離。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


被写体距離範囲を取得または設定します。

値: 被写体距離範囲。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


被写体位置を取得または設定します。

値: 被写体位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


DateTime タグの秒以下の小数部を取得または設定します。

値: DateTime タグの秒以下の小数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


DateTimeDigitized タグの秒以下の小数部を取得または設定します。

値: DateTimeDigitized タグの秒以下の小数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


DateTimeOriginal タグの秒以下の小数部を取得または設定します。

値: DateTimeOriginal タグの秒以下の小数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.psd.RasterImage-}
```
public void setThumbnail(RasterImage value)
```


サムネイル画像を取得または設定します。

値: サムネイル。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


転送関数を取得または設定します。

値: 転送関数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


ユーザーコメントを取得または設定します。

値: ユーザーコメント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


ホワイトバランスを取得または設定します。

値: ホワイトバランス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


画像の白色点の色度を取得または設定します。

値: 画像の白色点の色度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setXResolution(TiffRational value) {#setXResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


X 解像度を取得または設定します。

値: X 解像度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


RGB から YCbCr 画像データへの変換に使用される行列係数を取得または設定します。

値: RGB から YCbCr 画像データへの変換用行列係数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


輝度成分に対する色差成分の位置を取得または設定します。

値: 輝度成分に対する色差成分の位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


輝度成分に対する色差成分のサンプリング比率を取得または設定します。

値: 輝度成分に対する色差成分のサンプリング比率。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setYResolution(TiffRational value) {#setYResolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Y 解像度を取得または設定します。

値: y 解像度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) |  |

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

