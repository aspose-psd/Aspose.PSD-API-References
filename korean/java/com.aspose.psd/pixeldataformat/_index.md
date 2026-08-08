---
title: "PixelDataFormat"
second_title: "Java용 Aspose.PSD API 참조"
description: "픽셀 데이터 형식."
type: docs
weight: 80
url: /ko/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

픽셀 데이터 형식입니다. 이는 불변 객체입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된  System.Object  가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | 샘플당 지정된 비트 수를 사용하여 BGR 색상을 가져옵니다. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | 샘플당 지정된 비트 수를 사용하여 BGRA 색상을 가져옵니다. |
| [getBitsPerPixel()](#getBitsPerPixel--) | 픽셀당 비트를 가져옵니다. |
| [getCaption()](#getCaption--) | 픽셀 데이터 형식 캡션을 가져옵니다. |
| [getChannelBits()](#getChannelBits--) | 각 채널에 대한 비트 수를 가져옵니다. |
| [getChannelsCount()](#getChannelsCount--) | 채널 수를 가져옵니다. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | 샘플당 지정된 비트 수를 사용하여 CIE Lab 색상을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | 32비트당 픽셀에 대해 시안, 마젠타, 옐로우 및 블랙 각각에 8비트를 사용하는 PixelDataFormat 를 가져옵니다. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | 샘플당 지정된 비트 수를 사용하여 CMYK 색상을 가져옵니다. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | 샘플당 지정된 비트 수를 사용하여 CMYK 색상을 가져옵니다. |
| [getCmyk16()](#getCmyk16--) | 64비트당 픽셀에 대해 시안, 마젠타, 옐로우 및 블랙 각각에 16비트를 사용하는 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 를 가져옵니다. |
| [getCmyka()](#getCmyka--) | acmyk를 가져옵니다. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | 샘플당 지정된 비트 수를 사용하여 CMYKA 색상을 가져옵니다. |
| [getCmyka16()](#getCmyka16--) | acmyk를 가져옵니다. |
| [getGrayscale()](#getGrayscale--) | 8비트당 픽셀에 대해 0-255 구간에서 그레이스케일 강도를 나타내는 8비트를 사용하는 PixelDataFormat 를 가져옵니다. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | 샘플당 지정된 비트 수를 사용하여 그레이스케일 색상을 가져옵니다. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | 16비트당 픽셀에 대해 0-255 구간에서 그레이스케일 강도를 나타내는 8비트와 추가 8비트 알파 구성 요소를 사용하는 PixelDataFormat 를 가져옵니다. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | 샘플당 지정된 비트 수를 사용하여 GrayscaleAlpha 색상을 가져옵니다. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | 샘플당 지정된 비트 수를 사용하여 GrayscaleAlpha 색상을 가져옵니다. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | 32비트당 픽셀에 대해 부동 소수점 형식으로 그레이스케일 강도를 나타내는 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 를 가져옵니다. |
| [getPixelFormat()](#getPixelFormat--) | 픽셀 형식을 가져옵니다. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | 샘플당 지정된 비트 수를 사용하여 RGB 색상을 가져옵니다. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | 샘플당 지정된 비트 수를 사용하여 RGB 색상을 가져옵니다. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | 16비트당 픽셀에 대해 빨강, 초록, 파랑 각각에 5비트를 사용하는 PixelDataFormat 를 가져오며, 알파는 정의되지 않습니다. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | 16비트당 픽셀에 대해 빨강에 5비트, 초록에 6비트, 파랑에 5비트를 사용하는 PixelDataFormat 를 가져오며, 알파는 정의되지 않습니다. |
| [getRgb24Bpp()](#getRgb24Bpp--) | 24비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다. 알파는 정의되지 않았습니다. |
| [getRgb24BppPng()](#getRgb24BppPng--) | 24비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다. 알파는 정의되지 않았습니다. |
| [getRgb32Bpp()](#getRgb32Bpp--) | 32비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | 지정된 샘플당 비트 수로 BGRA 인덱스 색상을 가져옵니다. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | 색상당 1비트 인덱스로 정의된 PixelDataFormat을 가져옵니다. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | 색상당 2비트 인덱스로 정의된 PixelDataFormat을 가져옵니다. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | 색상당 4비트 인덱스로 정의된 PixelDataFormat을 가져옵니다. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | 색상당 8비트 인덱스로 정의된 PixelDataFormat을 가져옵니다. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | 지정된 샘플당 비트 수로 RGBA 색상을 가져옵니다. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | 지정된 샘플당 비트 수로 RGBA 색상을 가져옵니다. |
| [getRgba32Bpp()](#getRgba32Bpp--) | 32비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다. |
| [getRgba64Bpp()](#getRgba64Bpp--) | 픽셀당 64비트, 알파, 빨강, 초록 및 파랑 각각에 16비트로 정의된 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)을 가져옵니다. |
| [getYCbCr()](#getYCbCr--) | 픽셀당 24비트, 휘도, 청차 및 적차 색차 성분 각각에 8비트로 정의된 PixelDataFormat을 가져옵니다. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | 지정된 샘플당 비트 수로 YCbCr 색상을 가져옵니다. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | 지정된 샘플당 비트 수로 YCbCr 색상을 가져옵니다. |
| [getYcck()](#getYcck--) | 픽셀당 32비트, 휘도, 청차, 적차 및 검정 색차 성분 각각에 8비트로 정의된 PixelDataFormat을 가져옵니다. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | 지정된 샘플당 비트 수로 YCCK 색상을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [isIndexed_internalized()](#isIndexed-internalized--) | 이 인스턴스가 인덱스인지 여부를 나타내는 값을 가져옵니다. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | 두 PixelDataFormat 클래스의 동등성 결과를 반환합니다. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | 두 PixelDataFormat 클래스의 비동등성 결과를 반환합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는  System.String  을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된  System.Object  가 이 인스턴스와 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object. |

**Returns:**
boolean - 지정된 System.Object가 이 인스턴스와 같으면 true; 그렇지 않으면 false.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


샘플당 지정된 비트 수를 사용하여 BGR 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


샘플당 지정된 비트 수를 사용하여 BGRA 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


픽셀당 비트를 가져옵니다.

**Returns:**
int - 픽셀당 비트 수.
### getCaption() {#getCaption--}
```
public String getCaption()
```


픽셀 데이터 형식 캡션을 가져옵니다.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


각 채널에 대한 비트 수를 가져옵니다.

**Returns:**
int[] - 채널 비트.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


채널 수를 가져옵니다.

**Returns:**
int - 채널 수.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


샘플당 지정된 비트 수를 사용하여 CIE Lab 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerL | int | L 채널당 비트 수. |
| bitsPerA | int | A 채널당 비트 수. |
| bitsPerB | int | B 채널당 비트 수. |

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


32비트당 픽셀에 대해 시안, 마젠타, 옐로우 및 블랙 각각에 8비트를 사용하는 PixelDataFormat 를 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


샘플당 지정된 비트 수를 사용하여 CMYK 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


샘플당 지정된 비트 수를 사용하여 CMYK 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerCyanChannel | int | 시안 채널당 비트 수. |
| bitsPerMagentaChannel | int | 마젠타 채널당 비트 수. |
| bitsPerYellowChannel | int | 노란색 채널당 비트 수. |
| bitsPerKeyChannel | int | 키 채널당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


64비트당 픽셀에 대해 시안, 마젠타, 옐로우 및 블랙 각각에 16비트를 사용하는 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 를 가져옵니다.

값: 시안, 마젠타, 노란색 및 검정 각각에 16비트를 사용하여 픽셀당 64비트로 정의된 [PixelDataFormat](../../com.aspose.psd/pixeldataformat).

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


acmyk를 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


샘플당 지정된 비트 수를 사용하여 CMYKA 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerCyanChannel | int | 시안 채널당 비트 수. |
| bitsPerMagentaChannel | int | 마젠타 채널당 비트 수. |
| bitsPerYellowChannel | int | 노란색 채널당 비트 수. |
| bitsPerKeyChannel | int | 키 채널당 비트 수. |
| bitsPerAlphaChannel | int | 알파 채널당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


acmyk를 가져옵니다.

값: 알파, 시안, 마젠타, 노란색 및 검정 각각에 16비트를 사용하여 픽셀당 80비트로 정의된 [PixelDataFormat](../../com.aspose.psd/pixeldataformat).

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


8비트당 픽셀에 대해 0-255 구간에서 그레이스케일 강도를 나타내는 8비트를 사용하는 PixelDataFormat 를 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


샘플당 지정된 비트 수를 사용하여 그레이스케일 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


16비트당 픽셀에 대해 0-255 구간에서 그레이스케일 강도를 나타내는 8비트와 추가 8비트 알파 구성 요소를 사용하는 PixelDataFormat 를 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


샘플당 지정된 비트 수를 사용하여 GrayscaleAlpha 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


샘플당 지정된 비트 수를 사용하여 GrayscaleAlpha 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |
| alphaChannelBits | int | 알파 채널의 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


32비트당 픽셀에 대해 부동 소수점 형식으로 그레이스케일 강도를 나타내는 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 를 가져옵니다.

값: 부동 소수점 형식의 그레이스케일 강도를 나타내는 픽셀당 32비트로 정의된 [PixelDataFormat](../../com.aspose.psd/pixeldataformat).

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


픽셀 형식을 가져옵니다.

**Returns:**
int - 픽셀 형식.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


샘플당 지정된 비트 수를 사용하여 RGB 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


샘플당 지정된 비트 수를 사용하여 RGB 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerRedChannel | int | 빨간색 채널당 비트 수. |
| bitsPerGreenChannel | int | 녹색 채널당 비트 수. |
| bitsPerBlueChannel | int | 파란색 채널당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


16비트당 픽셀에 대해 빨강, 초록, 파랑 각각에 5비트를 사용하는 PixelDataFormat 를 가져오며, 알파는 정의되지 않습니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


16비트당 픽셀에 대해 빨강에 5비트, 초록에 6비트, 파랑에 5비트를 사용하는 PixelDataFormat 를 가져오며, 알파는 정의되지 않습니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


24비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다. 알파는 정의되지 않았습니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


24비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다. 알파는 정의되지 않았습니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


32비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


지정된 샘플당 비트 수로 BGRA 인덱스 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


색상당 1비트 인덱싱된 형태로 정의된 PixelDataFormat을 가져옵니다. 인덱스된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 하기 위해 설계되었습니다. 변환이 필요할 수 있으므로 주의해서 사용하십시오(예: 한 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 변환).

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


인덱스된 색상당 2비트에 대해 정의된 PixelDataFormat을 가져옵니다. 인덱스된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 합니다. 변환이 필요할 수 있으므로 주의해서 사용하십시오. 변환은 하나의 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 이루어질 수 있습니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


인덱스된 색상당 4비트에 대해 정의된 PixelDataFormat을 가져옵니다. 인덱스된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 합니다. 변환이 필요할 수 있으므로 주의해서 사용하십시오. 변환은 하나의 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 이루어질 수 있습니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


인덱스된 색상당 8비트에 대해 정의된 PixelDataFormat을 가져옵니다. 인덱스된 픽셀 데이터 저장소는 색상 팔레트가 사용되는 모든 곳에서 데이터 저장 및 검색을 가능하게 합니다. 변환이 필요할 수 있으므로 주의해서 사용하십시오. 변환은 하나의 팔레트에서 다른 팔레트로 또는 RGBA에서 인덱스 색상 모델로 이루어질 수 있습니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


지정된 샘플당 비트 수로 RGBA 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


지정된 샘플당 비트 수로 RGBA 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerRedChannel | int | 빨간색 채널당 비트 수. |
| bitsPerGreenChannel | int | 녹색 채널당 비트 수. |
| bitsPerBlueChannel | int | 파란색 채널당 비트 수. |
| bitsPerAlphaChannel | int | 알파 채널당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


32비트당 픽셀당 8비트씩 알파, 빨강, 초록 및 파랑에 대해 정의된 PixelDataFormat을 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


픽셀당 64비트, 알파, 빨강, 초록 및 파랑 각각에 16비트로 정의된 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)을 가져옵니다.

값: 알파, 레드, 그린, 블루 각각에 16비트를 사용하여 픽셀당 64비트로 정의된 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)입니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


픽셀당 24비트, 휘도, 청차 및 적차 색차 성분 각각에 8비트로 정의된 PixelDataFormat을 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


지정된 샘플당 비트 수로 YCbCr 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


지정된 샘플당 비트 수로 YCbCr 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerY | int | Y 채널당 비트 수. |
| bitsPerCb | int | Cb 채널당 비트 수. |
| bitsPerCr | int | Cr 채널당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


픽셀당 32비트, 휘도, 청차, 적차 및 검정 색차 성분 각각에 8비트로 정의된 PixelDataFormat을 가져옵니다.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


지정된 샘플당 비트 수로 YCCK 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitsPerSample | int | 샘플당 비트 수. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


이 인스턴스가 인덱스인지 여부를 나타내는 값을 가져옵니다.

값: 이 인스턴스가 인덱스된 경우 true, 그렇지 않으면 false.

**Returns:**
boolean - 이 인스턴스가 인덱스된 여부를 나타내는 값.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


두 PixelDataFormat 클래스의 동등성 결과를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 비교할 첫 번째 PixelDataFormat. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 비교할 두 번째 PixelDataFormat. |

**Returns:**
boolean - pixelFormat1과 pixelFormat2가 동일한 데이터를 포함하거나 두 매개변수가 모두 null인 경우 True.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


두 PixelDataFormat 클래스의 비동등성 결과를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 비교할 첫 번째 PixelDataFormat. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 비교할 두 번째 PixelDataFormat. |

**Returns:**
boolean - pixelFormat1과 pixelFormat2가 서로 다른 데이터를 포함하거나 매개변수 중 하나가 null인 경우 True.
### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는  System.String  을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 System.String.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

