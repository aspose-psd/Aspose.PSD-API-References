---
title: "クラス PixelDataFormat"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.PixelDataFormat クラス。ピクセルデータ形式です。これは不変オブジェクトです。"
type: docs
weight: 5720
url: /ja/net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

ピクセルデータ形式です。これは不変オブジェクトです。

```csharp
public class PixelDataFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | `PixelDataFormat` を取得します。シアン、マゼンタ、イエロー、ブラックそれぞれに 8 ビット、合計 32 ビット/ピクセルで定義されています。 |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | acmyk を取得します。 |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | `PixelDataFormat` を取得します。8 ビット/ピクセルで、0〜255 の範囲でグレースケール強度を表す 8 ビットで定義されています。 |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | `PixelDataFormat` を取得します。16 ビット/ピクセルで、0〜255 の範囲でグレースケール強度を表す 8 ビットと、追加の 8 ビットアルファコンポーネントで定義されています。 |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | `PixelDataFormat` を取得します。16 ビット/ピクセルで、赤、緑、青それぞれに 5 ビット、アルファは定義されていません。 |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | `PixelDataFormat` を取得します。16 ビット/ピクセルで、赤に 5 ビット、緑に 6 ビット、青に 5 ビット、アルファは定義されていません。 |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | `PixelDataFormat` を取得します。24 ビット/ピクセルで、アルファ、赤、緑、青それぞれに 8 ビット、アルファは定義されていません。 |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | `PixelDataFormat` を取得します。24 ビット/ピクセルで、アルファ、赤、緑、青それぞれに 8 ビット、アルファは定義されていません。 |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | `PixelDataFormat` を取得します。32 ビット/ピクセルで、アルファ、赤、緑、青それぞれに 8 ビットで定義されています。 |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | `PixelDataFormat` を取得します。32 ビット/ピクセルで、アルファ、赤、緑、青それぞれに 8 ビットで定義されています。 |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | `PixelDataFormat` を取得します。64 ビット/ピクセルで、アルファ、赤、緑、青それぞれに 16 ビットで定義されています。 |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | `PixelDataFormat` を取得します。色ごとに 1 ビットのインデックス形式で定義されています。インデックス化されたピクセルデータストレージは、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを意図しています。変換が必要になる可能性があるため、注意して使用してください（パレット間の変換や RGBA からインデックスカラー形式への変換など）。 |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | インデックス化された 2 ビット/カラー 用に定義された `PixelDataFormat` を取得します。インデックス化されたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。変換が必要になる可能性があるため、注意して使用してください（パレット間の変換や RGBA からインデックスカラーへの変換）。 |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | インデックス化された 4 ビット/カラー 用に定義された `PixelDataFormat` を取得します。インデックス化されたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。変換が必要になる可能性があるため、注意して使用してください（パレット間の変換や RGBA からインデックスカラーへの変換）。 |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | インデックス化された 8 ビット/カラー 用に定義された `PixelDataFormat` を取得します。インデックス化されたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。変換が必要になる可能性があるため、注意して使用してください（パレット間の変換や RGBA からインデックスカラーへの変換）。 |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | 輝度、青差、赤差の各クロマ成分が 8 ビットずつ、合計 24 ビット/ピクセル 用に定義された `PixelDataFormat` を取得します。 |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | 輝度、青差、赤差、黒クロマの各成分が 8 ビットずつ、合計 32 ビット/ピクセル 用に定義された `PixelDataFormat` を取得します。 |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | ピクセルあたりのビット数を取得します。 |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | ピクセルデータ形式のキャプションを取得します。 |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | 各チャンネルのビット数を取得します。 |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | チャンネル数を取得します。 |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | ピクセルフォーマットを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | サンプルあたり指定されたビット数の BGR カラーを取得します。 |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | サンプルあたり指定されたビット数の BGRA カラーを取得します。 |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | サンプルあたり指定されたビット数の CIE Lab カラーを取得します。 |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | サンプルあたり指定されたビット数の CMYK カラーを取得します。 |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | サンプルあたり指定されたビット数の CMYK カラーを取得します。 |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | サンプルあたり指定されたビット数の CMYKA カラーを取得します。 |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | サンプルあたり指定されたビット数のグレースケールカラーを取得します。 |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | サンプルあたり指定されたビット数のグレースケールアルファカラーを取得します。 |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | サンプルあたり指定されたビット数のグレースケールアルファカラーを取得します。 |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | サンプルあたり指定されたビット数の RGB カラーを取得します。 |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | サンプルあたり指定されたビット数の RGB カラーを取得します。 |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | サンプルあたり指定されたビット数の RGBA カラーを取得します。 |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | サンプルあたり指定されたビット数の RGBA カラーを取得します。 |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | サンプルあたり指定されたビット数の BGRA インデックスカラーを取得します。 |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | サンプルあたり指定されたビット数の YCbCr カラーを取得します。 |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | サンプルあたり指定されたビット数の YCbCr カラーを取得します。 |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | サンプルあたり指定されたビット数の YCCK カラーを取得します。 |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | 指定された Object がこのインスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | このインスタンスを表すStringを返します。 |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | `PixelDataFormat` クラス 2 つの等価性の結果を返します。 |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | `PixelDataFormat` クラス 2 つの非等価性の結果を返します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


