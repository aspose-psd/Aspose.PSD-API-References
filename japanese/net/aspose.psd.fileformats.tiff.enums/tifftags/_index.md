---
title: "TiffTags 列挙体"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags 列挙体。tiff タグ列挙体。"
type: docs
weight: 4640
url: /ja/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

tiff タグ列挙体です。

```csharp
public enum TiffTags
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| SubFileType | `254` | サブファイル データ記述子。 |
| OsubfileType | `255` | [TIFF rev. 5.0 により廃止] サブファイル内のデータの種類。 |
| ImageWidth | `256` | 画像の幅（ピクセル単位）。 |
| ImageLength | `257` | 画像の高さ（ピクセル単位）。 |
| BitsPerSample | `258` | チャンネルあたりのビット数（サンプル）。 |
| Compression | `259` | データ圧縮手法。 |
| Photometric | `262` | フォトメトリック解釈。 |
| Thresholding | `263` | [TIFF rev. 5.0 により廃止] データに使用されるしきい値処理。 |
| CellWidth | `264` | [TIFF rev. 5.0 により廃止] ディザリング行列の幅。 |
| CellLength | `265` | [TIFF rev. 5.0 により廃止] ディザリング行列の高さ。 |
| FillOrder | `266` | バイト内のデータ順序。 |
| DocumentName | `269` | 画像が含まれる文書の名前。 |
| ImageDescription | `270` | 画像に関する情報。 |
| Make | `271` | スキャナーの製造元名。 |
| Model | `272` | スキャナーのモデル名/番号。 |
| StripOffsets | `273` | データストリップへのオフセット。 |
| Orientation | `274` | [TIFF rev. 5.0で廃止] 画像の向き。 |
| SamplesPerPixel | `277` | ピクセルあたりのサンプル数。 |
| RowsPerStrip | `278` | データストリップあたりの行数。 |
| StripByteCounts | `279` | ストリップのバイト数。 |
| MinSampleValue | `280` | [TIFF rev. 5.0で廃止] 最小サンプル値。 |
| MaxSampleValue | `281` | [TIFF rev. 5.0で廃止] 最大サンプル値。 |
| Xresolution | `282` | X方向のピクセル/解像度。 |
| Yresolution | `283` | Y方向のピクセル/解像度。 |
| PlanarConfig | `284` | ストレージ構成。 |
| PageName | `285` | 画像が属するページ名。 |
| Xposition | `286` | 画像左上のXページオフセット。 |
| Yposition | `287` | 画像左上のYページオフセット。 |
| FreeOffsets | `288` | [TIFF rev. 5.0で廃止] 空きブロックへのバイトオフセット。 |
| FreeByteCounts | `289` | [TIFF rev. 5.0で廃止] 空きブロックのサイズ。 |
| GrayResponseUnit | `290` | [TIFF rev. 6.0で廃止] グレースケール曲線の精度。 |
| GrayResponseCurve | `291` | [TIFF rev. 6.0で廃止] グレースケール応答曲線。 |
| T4Options | `292` | TIFF 6.0 の正式名エイリアスである GROUP3OPTIONS。CCITT Group 3 ファックスエンコーディングのオプション。32 ビットのフラグ。 |
| T6Options | `293` | CCITT Group 4 ファックスエンコーディングのオプション。32 ビットのフラグ。TIFF 6.0 の正式名エイリアスである GROUP4OPTIONS。 |
| ResolutionUnit | `296` | 解像度の単位。 |
| PageNumber | `297` | マルチページのページ番号。 |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] カラーカーブの精度。 |
| TransferFunction | `301` | 色測定情報。 |
| Software | `305` | 名前とリリース。 |
| DateTime | `306` | 作成日時。 |
| Artist | `315` | 画像の作成者。 |
| HostComputer | `316` | 作成されたマシン。 |
| Predictor | `317` | LZW を使用した予測方式。 |
| WhitePoint | `318` | 画像の白色点。 |
| PrimaryChromaticities | `319` | 一次色度。 |
| ColorMap | `320` | パレット画像の RGB マップ。 |
| HalftoneHints | `321` | ハイライト + シャドウ情報。 |
| TileWidth | `322` | タイル幅（ピクセル）。 |
| TileLength | `323` | タイル高さ（ピクセル）。 |
| TileOffsets | `324` | データタイルへのオフセット。 |
| TileByteCounts | `325` | タイルのバイト数。 |
| BadFaxLines | `326` | ピクセル数が間違っている行。 |
| CleanFaxData | `327` | 再生成された行情報。 |
| ConsecutiveBadFaxLines | `328` | 最大連続不良行数。 |
| SubIfd | `330` | サブイメージ記述子。 |
| InkSet | `332` | 分離画像のインク。 |
| InkNames | `333` | インクの ASCII 名称。 |
| NumberOfInks | `334` | インクの数。 |
| DotRange | `336` | 0% と 100% のドットコード。 |
| TargetPrinter | `337` | 分離対象。 |
| ExtraSamples | `338` | 余分なサンプルに関する情報。 |
| SampleFormat | `339` | データサンプルの形式。 |
| SminSampleValue | `340` | 変数 MinSampleValue。 |
| SmaxSampleValue | `341` | 変数 MaxSampleValue。 |
| TransferRange | `342` | 変数 TransferRange |
| ClipPath | `343` | ClipPath。Adobe TIFF テクニックノート 2 によって TIFF rev 6.0 以降に導入されました。 |
| Xclippathunits | `344` | XClipPathUnits。Adobe TIFF テクニックノート 2 によって TIFF rev 6.0 以降に導入されました。 |
| Yclippathunits | `345` | YClipPathUnits。Adobe TIFF テクニックノート 2 によって TIFF rev 6.0 以降に導入されました。 |
| Indexed | `346` | Indexed。Adobe TIFF テクニックノート 3 によって TIFF rev 6.0 以降に導入されました。 |
| JpegTables | `347` | JPEG テーブルストリーム。TIFF rev 6.0 以降に導入されました。 |
| OpiProxy | `351` | OPI プロキシ。Adobe TIFF テクニックノートにより TIFF rev 6.0 以降に導入されました。 |
| JpegProc | `512` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] JPEG 処理アルゴリズム。 |
| JpegInerchangeFormat | `513` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] SOI マーカーへのポインタ。 |
| JpegInterchangeFormatLength | `514` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] JFIF ストリーム長 |
| JpegRestartInterval | `515` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] 再開間隔長。 |
| JpegLosslessPredictors | `517` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] ロスレス処理予測子。 |
| JpegPointTransform | `518` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] ロスレスポイント変換。 |
| JpegQTables | `519` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] Q 行列オフセット。 |
| JpegDCtables | `520` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] DCT テーブルオフセット。 |
| JpegACtables | `521` | [obsoleted by Technical Note #2 which specifies a revised JPEG-in-TIFF scheme] AC 係数オフセット。 |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr 変換。 |
| YcbcrSubSampling | `530` | YCbCr サブサンプリング係数。 |
| YcbcrPositioning | `531` | サブサンプルの位置決め。 |
| ReferenceBlackWhite | `532` | 色測定情報。 |
| XmlPacket | `700` | XML パケット。Adobe XMP 仕様（2004年1月）により TIFF rev 6.0 以降で導入されました。 |
| OpiImageid | `32781` | OPI ImageID。Adobe TIFF テクニックノートにより TIFF rev 6.0 以降に導入されました。 |
| Refpts | `32953` | 画像参照ポイント。Island Graphics に登録されたプライベートタグ。 |
| Copyright | `33432` | 著作権文字列。このタグは TIFF rev. 6.0 にリストされており、所有者は不明です。 |
| PhotoshopResources | `34377` | Photoshop 画像リソース。 |
| IccProfile | `34675` | 埋め込み ICC デバイスプロファイル |
| ExifIfdPointer | `34665` | Exif IFD へのポインタ。 |
| XPTitle | `40091` | 画像に関する情報で、Windows Explorer が使用します。ImageDescription タグが存在する場合、XPTitle は Windows Explorer に無視されます。 |
| XPComment | `40092` | 画像のコメントで、Windows Explorer が使用します。 |
| XPAuthor | `40093` | 画像の作者で、Windows Explorer が使用します。Artist タグが存在する場合、XPAuthor は Windows Explorer に無視されます。 |
| XPKeywords | `40094` | 画像のキーワードで、Windows Explorer が使用します。 |
| XPSubject | `40095` | 画像のサブジェクトで、Windows Explorer が使用します。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


