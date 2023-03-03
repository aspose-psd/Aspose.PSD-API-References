---
title: Enum TiffTags
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Tiff.Enums.TiffTags 列挙. tiff タグ列挙型.
type: docs
weight: 4170
url: /ja/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

tiff タグ列挙型.

```csharp
public enum TiffTags
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| SubFileType | `254` | サブファイル データ記述子. |
| OsubfileType | `255` | [TIFF rev で廃止。 5.0] サブファイル内のデータの種類。 |
| ImageWidth | `256` | ピクセル単位の画像幅. |
| ImageLength | `257` | ピクセル単位の画像の高さ. |
| BitsPerSample | `258` | チャネルあたりのビット数 (サンプル). |
| Compression | `259` | データ圧縮技術. |
| Photometric | `262` | 測光解釈. |
| Thresholding | `263` | [TIFF rev で廃止。 5.0] データで使用されるしきい値。 |
| CellWidth | `264` | [TIFF rev で廃止。 5.0] ディザリング マトリックス幅. |
| CellLength | `265` | [TIFF rev で廃止。 5.0] ディザリング マトリックスの高さ. |
| FillOrder | `266` | バイト内のデータ順序. |
| DocumentName | `269` | 画像を保持するドキュメントの名前. |
| ImageDescription | `270` | 画像に関する情報. |
| Make | `271` | スキャナーメーカー名. |
| Model | `272` | スキャナのモデル名/番号. |
| StripOffsets | `273` | データ ストリップへのオフセット。 |
| Orientation | `274` | [TIFF rev で廃止。 5.0] 画像の向き。 |
| SamplesPerPixel | `277` | ピクセルあたりのサンプル数. |
| RowsPerStrip | `278` | データ ストリップあたりの行数. |
| StripByteCounts | `279` | ストリップのバイト数。 |
| MinSampleValue | `280` | [TIFF rev で廃止。 5.0] 最小サンプル値. |
| MaxSampleValue | `281` | [TIFF rev で廃止。 5.0] 最大サンプル値. |
| Xresolution | `282` | x. のピクセル/解像度 |
| Yresolution | `283` | y. のピクセル/解像度 |
| PlanarConfig | `284` | ストレージ組織. |
| PageName | `285` | ページ名画像は from. |
| Xposition | `286` | 画像の X ページ オフセット lhs. |
| Yposition | `287` | 画像の Y ページ オフセット lhs. |
| FreeOffsets | `288` | [TIFF rev で廃止。 5.0] フリーブロックへのバイトオフセット. |
| FreeByteCounts | `289` | [TIFF rev で廃止。 5.0] フリー ブロックのサイズ。 |
| GrayResponseUnit | `290` | [TIFF rev で廃止。 6.0] グレースケール曲線の精度. |
| GrayResponseCurve | `291` | [TIFF rev で廃止。 6.0] グレースケール応答曲線. |
| T4Options | `292` | GROUP3OPTIONS の TIFF 6.0 固有名エイリアス。 CCITT Group 3 ファックス エンコーディングのオプション。 32 フラグ ビット. |
| T6Options | `293` | CCITT グループ 4 ファックス エンコーディングのオプション。 32 フラグ ビット. GROUP4OPTIONS の TIFF 6.0 固有名エイリアス. |
| ResolutionUnit | `296` | 解像度の単位。 |
| PageNumber | `297` | マルチページのページ番号. |
| ColorResponseUnit | `300` | [TIFF rev で廃止。 6.0] カラーカーブの精度. |
| TransferFunction | `301` | 測色情報. |
| Software | `305` | 名前とリリース. |
| DateTime | `306` | 作成日時. |
| Artist | `315` | 画像の作成者. |
| HostComputer | `316` | 作成されたマシン. |
| Predictor | `317` | LZW を使用した予測スキーム. |
| WhitePoint | `318` | 画像の白色点. |
| PrimaryChromaticities | `319` | 一次色度. |
| ColorMap | `320` | パレット画像の RGB マップ. |
| HalftoneHints | `321` | ハイライト + シャドー情報. |
| TileWidth | `322` | ピクセル単位のタイル幅. |
| TileLength | `323` | ピクセル単位のタイルの高さ. |
| TileOffsets | `324` | データ タイルへのオフセット。 |
| TileByteCounts | `325` | タイルのバイト数。 |
| BadFaxLines | `326` | ピクセル数が間違っている行。 |
| CleanFaxData | `327` | 再生成された回線情報. |
| ConsecutiveBadFaxLines | `328` | 最大連続不良行. |
| SubIfd | `330` | サブイメージ記述子. |
| InkSet | `332` | 分離された画像のインク. |
| InkNames | `333` | インクの ASCII 名。 |
| NumberOfInks | `334` | インク数. |
| DotRange | `336` | 0% と 100% のドット コード。 |
| TargetPrinter | `337` | 分離対象. |
| ExtraSamples | `338` | 追加サンプルに関する情報。 |
| SampleFormat | `339` | データサンプル形式. |
| SminSampleValue | `340` | 変数 MinSampleValue. |
| SmaxSampleValue | `341` | 変数 MaxSampleValue. |
| TransferRange | `342` | 変数 TransferRange |
| ClipPath | `343` | クリップパス。 Adobe TIFF テクニカルノート 2. によってポスト TIFF リビジョン 6.0 が導入されました。 |
| Xclippathunits | `344` | XClipPathUnits。 Adobe TIFF テクニカルノート 2. によってポスト TIFF リビジョン 6.0 が導入されました。 |
| Yclippathunits | `345` | YClipPathUnits。 Adobe TIFF テクニカルノート 2. によってポスト TIFF リビジョン 6.0 が導入されました。 |
| Indexed | `346` | 索引付き。 Adobe TIFF Technote 3. によってポスト TIFF rev 6.0 が導入されました。 |
| JpegTables | `347` | JPEG テーブル ストリーム。導入されたポスト TIFF リビジョン 6.0. |
| OpiProxy | `351` | OPI プロキシ。 Adobe TIFF technote. によってポスト TIFF rev 6.0 が導入されました。 |
| JpegProc | `512` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] JPEG 処理アルゴリズム. |
| JpegInerchangeFormat | `513` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] SOI マーカーへのポインター。 |
| JpegInterchangeFormatLength | `514` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] JFIF ストリームの長さ |
| JpegRestartInterval | `515` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] 再起動間隔の長さ. |
| JpegLosslessPredictors | `517` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] ロスレス proc プレディクタ. |
| JpegPointTransform | `518` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] 無損失点変換. |
| JpegQTables | `519` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] Q 行列オフセット. |
| JpegDCtables | `520` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] DCT テーブルのオフセット。 |
| JpegACtables | `521` | [改訂された JPEG-in-TIFF スキームを指定する Technical Note #2 により廃止] AC 係数オフセット. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr 変換. |
| YcbcrSubSampling | `530` | YCbCr サブサンプリング係数. |
| YcbcrPositioning | `531` | サブサンプルの配置. |
| ReferenceBlackWhite | `532` | 測色情報. |
| XmlPacket | `700` | XML パケット。 2004 年 1 月、Adobe XMP 仕様による TIFF rev 6.0 以降の導入。 |
| OpiImageid | `32781` | OPI イメージ ID。 Adobe TIFF technote. によってポスト TIFF rev 6.0 が導入されました。 |
| Refpts | `32953` | 画像の基準点。 Island Graphics. に登録されたプライベートタグ |
| Copyright | `33432` | 著作権文字列。このタグは、TIFF rev にリストされています。 6.0 所有者不明. |
| PhotoshopResources | `34377` | Photoshop 画像リソース. |
| IccProfile | `34675` | 組み込み ICC デバイス プロファイル |
| ExifIfdPointer | `34665` | Exif IFD へのポインター。 |
| XPTitle | `40091` | Windows エクスプローラで使用される画像に関する情報。XPTitle場合、Windows エクスプローラーによって無視されます。ImageDescriptionタグが存在します. |
| XPComment | `40092` | Windows エクスプローラーで使用されるイメージのコメント。 |
| XPAuthor | `40093` | Windows Explorer で使用される Image Author. XPAuthor場合、Windows エクスプローラーによって無視されます。Artistタグが存在します. |
| XPKeywords | `40094` | Windows エクスプローラーで使用される画像キーワード。 |
| XPSubject | `40095` | Windows Explorer で使用されるサブジェクト イメージ。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* 組み立て [Aspose.PSD](../../)


