---
title: "PixelDataFormat"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ピクセルデータ形式です。"
type: docs
weight: 80
url: /ja/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

ピクセル データ フォーマットです。これは不変オブジェクトです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。 |
| [getBgr(int bitsPerSample)](#getBgr-int-) | サンプルあたり指定されたビット数で BGR カラーを取得します。 |
| [getBgra(int bitsPerSample)](#getBgra-int-) | サンプルあたり指定されたビット数で BGRA カラーを取得します。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | ピクセルあたりのビット数を取得します。 |
| [getCaption()](#getCaption--) | ピクセル データ フォーマットのキャプションを取得します。 |
| [getChannelBits()](#getChannelBits--) | 各チャンネルのビット数を取得します。 |
| [getChannelsCount()](#getChannelsCount--) | チャンネル数を取得します。 |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | サンプルあたり指定されたビット数で CIE Lab カラーを取得します。 |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | 32 ビット/ピクセルで、シアン、マゼンタ、イエロー、ブラックそれぞれに 8 ビットが割り当てられた  PixelDataFormat  を取得します。 |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | サンプルあたり指定されたビット数で CMYK カラーを取得します。 |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | サンプルあたり指定されたビット数で CMYK カラーを取得します。 |
| [getCmyk16()](#getCmyk16--) | 64 ビット/ピクセルで、シアン、マゼンタ、イエロー、ブラックそれぞれに 16 ビットが割り当てられた [PixelDataFormat](../../com.aspose.psd/pixeldataformat) を取得します。 |
| [getCmyka()](#getCmyka--) | acmyk を取得します。 |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | サンプルあたり指定されたビット数で CMYKA カラーを取得します。 |
| [getCmyka16()](#getCmyka16--) | acmyk を取得します。 |
| [getGrayscale()](#getGrayscale--) | 8 ビット/ピクセルで、0〜255 の範囲でグレースケール強度を表す 8 ビットが割り当てられた  PixelDataFormat  を取得します。 |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | サンプルあたり指定されたビット数でグレースケール カラーを取得します。 |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | 16 ビット/ピクセルで、0〜255 の範囲でグレースケール強度を表す 8 ビットと、追加の 8 ビットアルファ成分が含まれる  PixelDataFormat  を取得します。 |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | サンプルあたり指定されたビット数で GrayscaleAlpha カラーを取得します。 |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | サンプルあたり指定されたビット数で GrayscaleAlpha カラーを取得します。 |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | 32 ビット/ピクセルで、浮動小数点形式でグレースケール強度を表す [PixelDataFormat](../../com.aspose.psd/pixeldataformat) を取得します。 |
| [getPixelFormat()](#getPixelFormat--) | ピクセルフォーマットを取得します。 |
| [getRgb(int bitsPerSample)](#getRgb-int-) | サンプルあたり指定されたビット数で RGB カラーを取得します。 |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | サンプルあたり指定されたビット数で RGB カラーを取得します。 |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | 16 ビット/ピクセルで、赤、緑、青それぞれに 5 ビットが割り当てられ、アルファは未定義の  PixelDataFormat  を取得します。 |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | 16 ビット/ピクセルで、赤に 5 ビット、緑に 6 ビット、青に 5 ビットが割り当てられ、アルファは未定義の  PixelDataFormat  を取得します。 |
| [getRgb24Bpp()](#getRgb24Bpp--) | 24ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します（アルファは定義されていません）。 |
| [getRgb24BppPng()](#getRgb24BppPng--) | 24ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します（アルファは定義されていません）。 |
| [getRgb32Bpp()](#getRgb32Bpp--) | 32ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します。 |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | 指定されたサンプルあたりビット数で BGRA インデックスカラーを取得します。 |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | 色ごとに1ビットのインデックスを持つ PixelDataFormat を取得します。 |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | 色ごとに2ビットのインデックスを持つ PixelDataFormat を取得します。 |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | 色ごとに4ビットのインデックスを持つ PixelDataFormat を取得します。 |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | 色ごとに8ビットのインデックスを持つ PixelDataFormat を取得します。 |
| [getRgba(int bitsPerSample)](#getRgba-int-) | 指定されたサンプルあたりビット数で RGBA カラーを取得します。 |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | 指定されたサンプルあたりビット数で RGBA カラーを取得します。 |
| [getRgba32Bpp()](#getRgba32Bpp--) | 32ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します。 |
| [getRgba64Bpp()](#getRgba64Bpp--) | 64ビット/ピクセルで、アルファ、赤、緑、青それぞれに16ビットを割り当てた [PixelDataFormat](../../com.aspose.psd/pixeldataformat) を取得します。 |
| [getYCbCr()](#getYCbCr--) | 24ビット/ピクセルで、輝度、青差、赤差の各色差成分に8ビットを割り当てた PixelDataFormat を取得します。 |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | 指定されたサンプルあたりビット数で YCbCr カラーを取得します。 |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | 指定されたサンプルあたりビット数で YCbCr カラーを取得します。 |
| [getYcck()](#getYcck--) | 32ビット/ピクセルで、輝度、青差、赤差、黒色差の各成分に8ビットを割り当てた PixelDataFormat を取得します。 |
| [getYcck(int bitsPerSample)](#getYcck-int-) | 指定されたサンプルあたりビット数で YCCK カラーを取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isIndexed_internalized()](#isIndexed-internalized--) | このインスタンスがインデックス化されているかどうかを示す値を取得します。 |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | 2つの PixelDataFormat クラスの等価性の結果を返します。 |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | 2つの PixelDataFormat クラスの非等価性の結果を返します。 |
| [toString()](#toString--) | このインスタンスを表す  System.String  を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する System.Object。 |

**Returns:**
boolean - この指定された System.Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


サンプルあたり指定されたビット数で BGR カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


サンプルあたり指定されたビット数で BGRA カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


ピクセルあたりのビット数を取得します。

**Returns:**
int - ピクセルあたりのビット数です。
### getCaption() {#getCaption--}
```
public String getCaption()
```


ピクセル データ フォーマットのキャプションを取得します。

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


各チャンネルのビット数を取得します。

**Returns:**
int[] - チャネルのビット数です。
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


チャンネル数を取得します。

**Returns:**
int - チャネル数です。
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


サンプルあたり指定されたビット数で CIE Lab カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerL | int | L チャネルあたりのビット数です。 |
| bitsPerA | int | A チャネルあたりのビット数です。 |
| bitsPerB | int | B チャネルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CIE Lab color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


32 ビット/ピクセルで、シアン、マゼンタ、イエロー、ブラックそれぞれに 8 ビットが割り当てられた  PixelDataFormat  を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


サンプルあたり指定されたビット数で CMYK カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


サンプルあたり指定されたビット数で CMYK カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerCyanChannel | int | シアンチャネルあたりのビット数です。 |
| bitsPerMagentaChannel | int | マゼンタチャネルあたりのビット数です。 |
| bitsPerYellowChannel | int | イエローチャネルあたりのビット数です。 |
| bitsPerKeyChannel | int | キー チャネルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


64 ビット/ピクセルで、シアン、マゼンタ、イエロー、ブラックそれぞれに 16 ビットが割り当てられた [PixelDataFormat](../../com.aspose.psd/pixeldataformat) を取得します。

値: 64 ビット/ピクセルで、シアン、マゼンタ、イエロー、ブラックそれぞれに 16 ビットが割り当てられた [PixelDataFormat](../../com.aspose.psd/pixeldataformat) が定義されています。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


acmyk を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


サンプルあたり指定されたビット数で CMYKA カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerCyanChannel | int | シアンチャネルあたりのビット数です。 |
| bitsPerMagentaChannel | int | マゼンタチャネルあたりのビット数です。 |
| bitsPerYellowChannel | int | イエローチャネルあたりのビット数です。 |
| bitsPerKeyChannel | int | キー チャネルあたりのビット数です。 |
| bitsPerAlphaChannel | int | アルファチャネルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


acmyk を取得します。

値: 80 ビット/ピクセルで、アルファ、シアン、マゼンタ、イエロー、ブラックそれぞれに 16 ビットが割り当てられた [PixelDataFormat](../../com.aspose.psd/pixeldataformat) が定義されています。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


8 ビット/ピクセルで、0〜255 の範囲でグレースケール強度を表す 8 ビットが割り当てられた  PixelDataFormat  を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


サンプルあたり指定されたビット数でグレースケール カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


16 ビット/ピクセルで、0〜255 の範囲でグレースケール強度を表す 8 ビットと、追加の 8 ビットアルファ成分が含まれる  PixelDataFormat  を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


サンプルあたり指定されたビット数で GrayscaleAlpha カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


サンプルあたり指定されたビット数で GrayscaleAlpha カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |
| alphaChannelBits | int | アルファチャネルのサンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


32 ビット/ピクセルで、浮動小数点形式でグレースケール強度を表す [PixelDataFormat](../../com.aspose.psd/pixeldataformat) を取得します。

値: 32 ビット/ピクセルで、浮動小数点形式のグレースケール強度を表す [PixelDataFormat](../../com.aspose.psd/pixeldataformat) が定義されています。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


ピクセルフォーマットを取得します。

**Returns:**
int - ピクセル形式です。
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


サンプルあたり指定されたビット数で RGB カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


サンプルあたり指定されたビット数で RGB カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerRedChannel | int | レッドチャネルあたりのビット数です。 |
| bitsPerGreenChannel | int | グリーンチャネルあたりのビット数です。 |
| bitsPerBlueChannel | int | ブルーチャネルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


16 ビット/ピクセルで、赤、緑、青それぞれに 5 ビットが割り当てられ、アルファは未定義の  PixelDataFormat  を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


16 ビット/ピクセルで、赤に 5 ビット、緑に 6 ビット、青に 5 ビットが割り当てられ、アルファは未定義の  PixelDataFormat  を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


24ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します（アルファは定義されていません）。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


24ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します（アルファは定義されていません）。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


32ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


指定されたサンプルあたりビット数で BGRA インデックスカラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


インデックスカラーで色ごとに 1 ビットが定義された PixelDataFormat を取得します。インデックスピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。注意して使用してください。パレット間、または RGBA からインデックスカラー形式への変換が必要になる場合があります。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


インデックス化された 2 ビット/カラー 用に定義された  PixelDataFormat  を取得します。インデックス化されたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを意図しています。注意して使用してください。パレット間の変換や RGBA からインデックスカラー形式への変換が必要になる場合があります。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


インデックス化された 4 ビット/カラー 用に定義された  PixelDataFormat  を取得します。インデックス化されたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを意図しています。注意して使用してください。パレット間の変換や RGBA からインデックスカラー形式への変換が必要になる場合があります。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


インデックス化された 8 ビット/カラー 用に定義された  PixelDataFormat  を取得します。インデックス化されたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを意図しています。注意して使用してください。パレット間の変換や RGBA からインデックスカラー形式への変換が必要になる場合があります。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


指定されたサンプルあたりビット数で RGBA カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


指定されたサンプルあたりビット数で RGBA カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerRedChannel | int | レッドチャネルあたりのビット数です。 |
| bitsPerGreenChannel | int | グリーンチャネルあたりのビット数です。 |
| bitsPerBlueChannel | int | ブルーチャネルあたりのビット数です。 |
| bitsPerAlphaChannel | int | アルファチャネルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


32ビット/ピクセルで、アルファ、赤、緑、青それぞれに8ビットを割り当てた PixelDataFormat を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


64ビット/ピクセルで、アルファ、赤、緑、青それぞれに16ビットを割り当てた [PixelDataFormat](../../com.aspose.psd/pixeldataformat) を取得します。

値: アルファ、赤、緑、青それぞれに 16 ビットを持つ、1 ピクセルあたり 64 ビットで定義された [PixelDataFormat](../../com.aspose.psd/pixeldataformat) です。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


24ビット/ピクセルで、輝度、青差、赤差の各色差成分に8ビットを割り当てた PixelDataFormat を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


指定されたサンプルあたりビット数で YCbCr カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


指定されたサンプルあたりビット数で YCbCr カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerY | int | Y チャネルあたりのビット数です。 |
| bitsPerCb | int | Cb チャネルあたりのビット数です。 |
| bitsPerCr | int | Cr チャネルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


32ビット/ピクセルで、輝度、青差、赤差、黒色差の各成分に8ビットを割り当てた PixelDataFormat を取得します。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


指定されたサンプルあたりビット数で YCCK カラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitsPerSample | int | サンプルあたりのビット数です。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコード。ハッシュアルゴリズムやハッシュテーブルのようなデータ構造での使用に適しています。
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


このインスタンスがインデックス化されているかどうかを示す値を取得します。

値: このインスタンスがインデックス化されている場合は  true  、それ以外の場合は  false です。

**Returns:**
boolean - このインスタンスがインデックス化されているかどうかを示す値です。
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| caption | java.lang.String |  |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


2つの PixelDataFormat クラスの等価性の結果を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 比較対象となる最初の  PixelDataFormat  です。 |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 比較対象となる2番目の  PixelDataFormat  です。 |

**Returns:**
boolean - 両方の  pixelFormat1  と  pixelFormat2  が同等のデータを含むか、または両方のパラメータが null の場合は True です。
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


2つの PixelDataFormat クラスの非等価性の結果を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 比較対象となる最初の  PixelDataFormat  です。 |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 比較対象となる2番目の  PixelDataFormat  です。 |

**Returns:**
boolean - 両方の  pixelFormat1  と  pixelFormat2  が異なるデータを含むか、いずれかのパラメータが null の場合は True です。
### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す  System.String  を返します。

**Returns:**
java.lang.String - このインスタンスを表す System.String。
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

