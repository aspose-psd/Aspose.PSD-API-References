---
title: "ColorPaletteHelper"
second_title: "Java용 Aspose.PSD API 참조"
description: "색상 팔레트 조작을 위한 도우미 클래스입니다."
type: docs
weight: 28
url: /ko/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

색상 팔레트 조작을 위한 도우미 클래스입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create4Bit()](#create4Bit--) | 4 비트 컬러 팔레트를 생성합니다. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | 4 비트 그레이스케일 팔레트를 생성합니다. |
| [create8Bit()](#create8Bit--) | 8 비트 컬러 팔레트를 생성합니다. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | 8 비트 그레이스케일 팔레트를 생성합니다. |
| [createMonochrome()](#createMonochrome--) | 2가지 색상만 포함하는 단색 컬러 팔레트를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | 이미지에 팔레트가 없는 경우 래스터 이미지에서 컬러 팔레트를 가져옵니다 (이미지를 팔레트화). |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | 이미지에 팔레트가 없는 경우 래스터 이미지에서 컬러 팔레트를 가져옵니다 (이미지를 팔레트화). |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | 이미지에 팔레트가 없는 경우 래스터 이미지에서 컬러 팔레트를 가져옵니다 (이미지를 팔레트화). |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | 초기 이미지 색상 값의 상위 비트로 구성된 256색 팔레트를 가져옵니다. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | 균일한 256색 팔레트를 가져옵니다. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | 지정된 팔레트에 투명 색상이 있는지 확인합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


4 비트 컬러 팔레트를 생성합니다.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


4 비트 그레이스케일 팔레트를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| minIsWhite | boolean | true 로 설정하면 팔레트가 흰색으로 시작하고, 그렇지 않으면 검은색으로 시작합니다. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


8 비트 컬러 팔레트를 생성합니다.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


8 비트 그레이스케일 팔레트를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| minIsWhite | boolean | true 로 설정하면 팔레트가 흰색으로 시작하고, 그렇지 않으면 검은색으로 시작합니다. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


2가지 색상만 포함하는 단색 컬러 팔레트를 생성합니다.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


이미지에 팔레트가 없는 경우 래스터 이미지에서 컬러 팔레트를 가져옵니다 (이미지를 팔레트화). 팔레트가 존재하는 경우 계산을 수행하는 대신 해당 팔레트를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 래스터 이미지입니다. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계입니다. |
| entriesCount | int | 원하는 항목 수입니다. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


이미지에 팔레트가 없는 경우 래스터 이미지에서 컬러 팔레트를 가져옵니다 (이미지를 팔레트화). 팔레트가 존재하는 경우 계산을 수행하는 대신 해당 팔레트를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 래스터 이미지입니다. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계입니다. |
| entriesCount | int | 원하는 항목 수입니다. |
| useImagePalette | boolean | 설정하면 사용 가능한 경우 자체 이미지 팔레트를 사용합니다. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


이미지에 팔레트가 없는 경우 래스터 이미지에서 컬러 팔레트를 가져옵니다 (이미지를 팔레트화). 팔레트가 존재하는 경우 계산을 수행하는 대신 해당 팔레트를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 래스터 이미지입니다. |
| entriesCount | int | 원하는 항목 수입니다. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


초기 이미지 색상 값의 상위 비트로 구성된 256색 팔레트를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 이미지입니다. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


균일한 256색 팔레트를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 이미지입니다. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


지정된 팔레트에 투명 색상이 있는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 팔레트. |

**Returns:**
boolean - 지정된 팔레트에 투명 색상이 있으면  true , 그렇지 않으면  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

