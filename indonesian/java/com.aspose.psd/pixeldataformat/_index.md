---
title: "PixelDataFormat"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Format data piksel."
type: docs
weight: 80
url: /id/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Format data piksel. Ini adalah objek yang tidak dapat diubah.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah  System.Object  yang ditentukan sama dengan instance ini. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Menampilkan warna BGR dengan jumlah bit per sampel yang ditentukan. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Menampilkan warna BGRA dengan jumlah bit per sampel yang ditentukan. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Menampilkan bit per piksel. |
| [getCaption()](#getCaption--) | Menampilkan keterangan format data piksel. |
| [getChannelBits()](#getChannelBits--) | Menampilkan jumlah bit untuk setiap saluran. |
| [getChannelsCount()](#getChannelsCount--) | Menampilkan jumlah saluran. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Menampilkan warna CIE Lab dengan jumlah bit per sampel yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing cyan, magenta, kuning, dan hitam. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Menampilkan warna CMYK dengan jumlah bit per sampel yang ditentukan. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Menampilkan warna CMYK dengan jumlah bit per sampel yang ditentukan. |
| [getCmyk16()](#getCmyk16--) | Menampilkan [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 64 bit per piksel dengan 16 bit untuk masing‑masing cyan, magenta, kuning, dan hitam. |
| [getCmyka()](#getCmyka--) | Menampilkan acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Menampilkan warna CMYKA dengan jumlah bit per sampel yang ditentukan. |
| [getCmyka16()](#getCmyka16--) | Menampilkan acmyk. |
| [getGrayscale()](#getGrayscale--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 8 bit per piksel dengan 8 bit yang mewakili intensitas skala abu‑abu dalam interval 0‑255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Menampilkan warna Grayscale dengan jumlah bit per sampel yang ditentukan. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 16 bit per piksel dengan 8 bit yang mewakili intensitas skala abu‑abu dalam interval 0‑255 dan komponen alfa tambahan 8 bit. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Menampilkan warna GrayscaleAlpha dengan jumlah bit per sampel yang ditentukan. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Menampilkan warna GrayscaleAlpha dengan jumlah bit per sampel yang ditentukan. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Menampilkan [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 32 bit per piksel yang merepresentasikan intensitas skala abu‑abu dalam format titik mengambang. |
| [getPixelFormat()](#getPixelFormat--) | Menampilkan format piksel. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Menampilkan warna RGB dengan jumlah bit per sampel yang ditentukan. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Menampilkan warna RGB dengan jumlah bit per sampel yang ditentukan. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 16 bit per piksel dengan 5 bit untuk masing‑masing merah, hijau, dan biru, alfa tidak didefinisikan. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 16 bit per piksel dengan 5 bit untuk merah, 6 bit untuk hijau, dan 5 bit untuk biru, alfa tidak didefinisikan. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 24 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru, alfa tidak didefinisikan. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 24 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru, alfa tidak didefinisikan. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Mendapatkan warna terindeks BGRA dengan jumlah bit per sampel yang ditentukan. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 1 bit per warna. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 2 bit per warna. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 4 bit per warna. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 8 bit per warna. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Mendapatkan warna RGBA dengan jumlah bit per sampel yang ditentukan. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Mendapatkan warna RGBA dengan jumlah bit per sampel yang ditentukan. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Menampilkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Mendapatkan [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 64 bit per piksel dengan 16 bit untuk masing‑masing alfa, merah, hijau, dan biru. |
| [getYCbCr()](#getYCbCr--) | Mendapatkan  PixelDataFormat  yang didefinisikan untuk 24 bit per piksel dengan 8 bit untuk masing‑masing komponen kromatik luma, perbedaan biru, dan perbedaan merah. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Mendapatkan warna YCbCr dengan jumlah bit per sampel yang ditentukan. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Mendapatkan warna YCbCr dengan jumlah bit per sampel yang ditentukan. |
| [getYcck()](#getYcck--) | Mendapatkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing komponen kromatik luma, perbedaan biru, perbedaan merah, dan hitam. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Mendapatkan warna YCCK dengan jumlah bit per sampel yang ditentukan. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Mendapatkan nilai yang menunjukkan apakah instansi ini terindeks. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Mengembalikan hasil kesetaraan untuk dua kelas  PixelDataFormat . |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Mengembalikan hasil ketidaksamaan untuk dua kelas  PixelDataFormat . |
| [toString()](#toString--) | Mengembalikan sebuah  System.String  yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah  System.Object  yang ditentukan sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | System.Object yang akan dibandingkan dengan instance ini. |

**Returns:**
boolean - true jika System.Object yang ditentukan sama dengan instance ini; jika tidak, false.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Menampilkan warna BGR dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Menampilkan warna BGRA dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Menampilkan bit per piksel.

**Returns:**
int - Bit per piksel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Menampilkan keterangan format data piksel.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Menampilkan jumlah bit untuk setiap saluran.

**Returns:**
int[] - Bit kanal.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Menampilkan jumlah saluran.

**Returns:**
int - Jumlah kanal.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Menampilkan warna CIE Lab dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerL | int | Jumlah bit per kanal L. |
| bitsPerA | int | Jumlah bit per kanal A. |
| bitsPerB | int | Jumlah bit per kanal B. |

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


Menampilkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing cyan, magenta, kuning, dan hitam.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Menampilkan warna CMYK dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Menampilkan warna CMYK dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerCyanChannel | int | Jumlah bit per saluran Cyan. |
| bitsPerMagentaChannel | int | Jumlah bit per saluran Magenta. |
| bitsPerYellowChannel | int | Jumlah bit per saluran Yellow. |
| bitsPerKeyChannel | int | Jumlah bit per saluran Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Menampilkan [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 64 bit per piksel dengan 16 bit untuk masing‑masing cyan, magenta, kuning, dan hitam.

Nilai: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 64 bit per piksel dengan 16 bit untuk masing-masing cyan, magenta, yellow, dan black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Menampilkan acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Menampilkan warna CMYKA dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerCyanChannel | int | Jumlah bit per saluran Cyan. |
| bitsPerMagentaChannel | int | Jumlah bit per saluran Magenta. |
| bitsPerYellowChannel | int | Jumlah bit per saluran Yellow. |
| bitsPerKeyChannel | int | Jumlah bit per saluran Key. |
| bitsPerAlphaChannel | int | Jumlah bit per saluran Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Menampilkan acmyk.

Nilai: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 80 bit per piksel dengan 16 bit untuk masing-masing alpha, cyan, magenta, yellow, dan black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 8 bit per piksel dengan 8 bit yang mewakili intensitas skala abu‑abu dalam interval 0‑255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Menampilkan warna Grayscale dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 16 bit per piksel dengan 8 bit yang mewakili intensitas skala abu‑abu dalam interval 0‑255 dan komponen alfa tambahan 8 bit.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Menampilkan warna GrayscaleAlpha dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Menampilkan warna GrayscaleAlpha dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |
| alphaChannelBits | int | Jumlah bit per sampel dalam saluran alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Menampilkan [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 32 bit per piksel yang merepresentasikan intensitas skala abu‑abu dalam format titik mengambang.

Nilai: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 32 bit per piksel yang merepresentasikan intensitas skala abu-abu dalam format floating point.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Menampilkan format piksel.

**Returns:**
int - Format piksel.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Menampilkan warna RGB dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Menampilkan warna RGB dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerRedChannel | int | Jumlah bit per saluran Red. |
| bitsPerGreenChannel | int | Jumlah bit per saluran Green. |
| bitsPerBlueChannel | int | Jumlah bit per saluran Blue. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 16 bit per piksel dengan 5 bit untuk masing‑masing merah, hijau, dan biru, alfa tidak didefinisikan.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 16 bit per piksel dengan 5 bit untuk merah, 6 bit untuk hijau, dan 5 bit untuk biru, alfa tidak didefinisikan.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 24 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru, alfa tidak didefinisikan.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 24 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru, alfa tidak didefinisikan.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Mendapatkan warna terindeks BGRA dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 1 bit per warna. Penyimpanan data piksel terindeks dimaksudkan untuk memungkinkan penyimpanan dan pengambilan data di mana pun palet warna digunakan. Gunakan dengan hati-hati, karena mungkin memerlukan konversi dari satu palet ke yang lain atau dari RGBA ke model warna terindeks.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 2 bit per warna. Penyimpanan data piksel terindeks dimaksudkan untuk memungkinkan penyimpanan dan pengambilan data di mana pun palet warna digunakan. Gunakan dengan hati-hati, karena mungkin memerlukan konversi dari satu palet ke yang lain atau dari RGBA ke model warna terindeks.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 4 bit per warna. Penyimpanan data piksel terindeks dimaksudkan untuk memungkinkan penyimpanan dan pengambilan data di mana pun palet warna digunakan. Gunakan dengan hati-hati, karena mungkin memerlukan konversi dari satu palet ke yang lain atau dari RGBA ke model warna terindeks.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Mendapatkan  PixelDataFormat  yang didefinisikan untuk indeks 8 bit per warna. Penyimpanan data piksel terindeks dimaksudkan untuk memungkinkan penyimpanan dan pengambilan data di mana pun palet warna digunakan. Gunakan dengan hati-hati, karena mungkin memerlukan konversi dari satu palet ke yang lain atau dari RGBA ke model warna terindeks.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Mendapatkan warna RGBA dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Mendapatkan warna RGBA dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerRedChannel | int | Jumlah bit per saluran Red. |
| bitsPerGreenChannel | int | Jumlah bit per saluran Green. |
| bitsPerBlueChannel | int | Jumlah bit per saluran Blue. |
| bitsPerAlphaChannel | int | Jumlah bit per saluran Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Menampilkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing alfa, merah, hijau, dan biru.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Mendapatkan [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 64 bit per piksel dengan 16 bit untuk masing‑masing alfa, merah, hijau, dan biru.

Nilai: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) yang didefinisikan untuk 64 bit per piksel dengan 16 bit untuk masing‑masing alfa, merah, hijau, dan biru.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Mendapatkan  PixelDataFormat  yang didefinisikan untuk 24 bit per piksel dengan 8 bit untuk masing‑masing komponen kromatik luma, perbedaan biru, dan perbedaan merah.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Mendapatkan warna YCbCr dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Mendapatkan warna YCbCr dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerY | int | Jumlah bit per saluran Y. |
| bitsPerCb | int | Jumlah bit per saluran Cb. |
| bitsPerCr | int | Jumlah bit per saluran Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Mendapatkan  PixelDataFormat  yang didefinisikan untuk 32 bit per piksel dengan 8 bit untuk masing‑masing komponen kromatik luma, perbedaan biru, perbedaan merah, dan hitam.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Mendapatkan warna YCCK dengan jumlah bit per sampel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitsPerSample | int | Jumlah bit per sampel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash untuk instance ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Mendapatkan nilai yang menunjukkan apakah instansi ini terindeks.

Nilai:  true  jika instance ini terindeks; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah instance ini terindeks.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengembalikan hasil kesetaraan untuk dua kelas  PixelDataFormat .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | PixelDataFormat  pertama  untuk dibandingkan. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | PixelDataFormat  kedua  untuk dibandingkan. |

**Returns:**
boolean - True jika kedua  pixelFormat1  dan  pixelFormat2  berisi data yang sama atau kedua parameter bernilai null.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Mengembalikan hasil ketidaksamaan untuk dua kelas  PixelDataFormat .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | PixelDataFormat  pertama  untuk dibandingkan. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | PixelDataFormat  kedua  untuk dibandingkan. |

**Returns:**
boolean - True jika kedua  pixelFormat1  dan  pixelFormat2  berisi data yang tidak sama atau salah satu parameter bernilai null.
### toString() {#toString--}
```
public String toString()
```


Mengembalikan sebuah  System.String  yang mewakili instance ini.

**Returns:**
java.lang.String - Sebuah  System.String  yang mewakili instance ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

