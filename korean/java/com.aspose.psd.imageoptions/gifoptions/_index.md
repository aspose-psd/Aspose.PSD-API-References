---
title: "GifOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "GIF 파일 형식 생성 옵션."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

GIF 파일 형식 생성 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions 클래스의 새 인스턴스를 초기화합니다. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | GifOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [deepClone()](#deepClone--) | 이 인스턴스를 복제합니다. |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF 배경 색 인덱스를 가져오거나 설정합니다. |
| [getBufferSizeHint()](#getBufferSizeHint--) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | GIF 색 해상도를 가져오거나 설정합니다. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | 팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getFullFrame()](#getFullFrame--) | 전체 프레임인지 여부를 나타내는 값을 가져옵니다. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getInterlaced()](#getInterlaced--) | 이미지를 인터레이스해야 하는 경우 true. |
| [getMaxDiff()](#getMaxDiff--) | 허용되는 최대 픽셀 차이를 가져오거나 설정합니다. |
| [getMultiPageOptions()](#getMultiPageOptions--) | 다중 페이지 옵션 |
| [getPalette()](#getPalette--) | 색상 팔레트를 가져오거나 설정합니다. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF 픽셀 종횡비를 가져오거나 설정합니다. |
| [getProgressEventHandler()](#getProgressEventHandler--) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [getResolutionSettings()](#getResolutionSettings--) | 해상도 설정을 가져오거나 설정합니다. |
| [getSource()](#getSource--) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [getXmpData()](#getXmpData--) | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| [hasTrailer()](#hasTrailer--) | GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | 팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF 배경 색 인덱스를 가져오거나 설정합니다. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | GIF 색 해상도를 가져오거나 설정합니다. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | 팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 전체 프레임인지 여부를 나타내는 값을 설정합니다. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | 이미지를 인터레이스해야 하는 경우 true. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | 허용되는 최대 픽셀 차이를 가져오거나 설정합니다. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 다중 페이지 옵션 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 색상 팔레트를 가져오거나 설정합니다. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | 팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF 픽셀 종횡비를 가져오거나 설정합니다. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 해상도 설정을 가져오거나 설정합니다. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


GifOptions 클래스의 새 인스턴스를 초기화합니다.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


GifOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | GIF 옵션. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


이 인스턴스를 복제합니다.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


이 인스턴스를 복제합니다.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF 배경 색 인덱스를 가져오거나 설정합니다.

**Returns:**
byte - GIF 배경 색 인덱스.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF 색 해상도를 가져오거나 설정합니다.

**Returns:**
byte - 색 해상도.

색 해상도 - 원본 이미지에서 사용할 수 있는 기본 색당 비트 수에서 1을 뺀 값입니다. 이 값은 그래픽에서 선택된 색상이 포함된 전체 팔레트의 크기를 나타내며, 그래픽에서 실제로 사용된 색상의 수를 나타내지는 않습니다. 예를 들어, 이 필드의 값이 3이면 원본 이미지의 팔레트는 이미지 생성에 사용할 수 있는 기본 색당 4비트를 가지고 있었음을 의미합니다. 이 값은 전체 팔레트의 모든 색상이 소스 머신에서 사용 가능하지 않더라도 원본 팔레트의 풍부함을 나타내도록 설정해야 합니다.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). 기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

값: 기본 교체 글꼴.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean - 팔레트 보정이 적용된 경우 true; 그렇지 않으면 false.

팔레트 보정은 이미지를 GIF로 내보낼 때마다 원본 이미지 색상을 분석하여 최적의 일치 팔레트를 구축한다는 의미입니다(이미지 팔레트가 없거나 옵션에 지정되지 않은 경우). 분석 과정에는 시간이 소요되지만, 결과 이미지가 최적의 색 팔레트를 갖게 되어 시각적으로 더 나은 결과를 제공합니다.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


전체 프레임인지 여부를 나타내는 값을 가져옵니다.

값: 전체 프레임이면 true, 그렇지 않으면 false.

**Returns:**
boolean - 전체 프레임인지 여부를 나타내는 값.
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다.

값: 생성 이벤트 후 무시하면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


이미지를 인터레이스해야 하는 경우 true.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


허용되는 최대 픽셀 차이를 가져오거나 설정합니다. 0보다 큰 경우 손실 압축이 사용됩니다. 최적의 손실 압축을 위한 권장값은 80이며, 30은 매우 가벼운 압축, 200은 강한 압축을 의미합니다. 손실이 적게 발생할 때 가장 잘 작동하며, 압축 알고리즘의 제한으로 인해 매우 높은 손실 수준에서는 큰 이득을 얻기 어렵습니다. 허용값 범위는 [0, 1000]입니다.

**Returns:**
int - 허용값 범위.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


다중 페이지 옵션

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


색상 팔레트를 가져오거나 설정합니다.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF 픽셀 종횡비를 가져오거나 설정합니다.

픽셀 종횡비 - 원본 이미지에서 픽셀의 종횡비 근사값을 계산하는 데 사용되는 계수입니다. 필드 값이 0이 아니면 다음 공식에 따라 종횡비 근사값이 계산됩니다: 종횡비 = (픽셀 종횡비 + 15) / 64. 픽셀 종횡비는 픽셀의 너비를 높이로 나눈 값으로 정의됩니다. 이 필드의 값 범위는 1/64 단위로 4:1(가장 넓은 픽셀)부터 1:4(가장 높은 픽셀)까지 지정할 수 있습니다. 값: 0 - 종횡비 정보가 제공되지 않음. 1..255 - 계산에 사용되는 값.

**Returns:**
byte - GIF 픽셀 종횡비.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


진행 이벤트 핸들러를 가져오거나 설정합니다.

값: 진행 이벤트 핸들러.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


해상도 설정을 가져오거나 설정합니다.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


이미지를 생성할 소스를 가져오거나 설정합니다.

값: 이미지를 생성할 소스.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


벡터 래스터화 옵션을 가져오거나 설정합니다.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP 메타데이터 컨테이너를 가져오거나 설정합니다.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean - GIF에 트레일러가 있는 경우 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean -  palette entries가 정렬된 경우 true, 그렇지 않은 경우 false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF 배경 색 인덱스를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte | GIF 배경 색 인덱스. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF 색 해상도를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | byte | 색 해상도. |

Color Resolution - 원본 이미지에서 사용할 수 있는 기본 색당 비트 수에서 1을 뺀 값입니다. 이 값은 그래픽에서 선택된 색상이 있는 전체 팔레트의 크기를 나타내며, 그래픽에서 실제로 사용된 색상의 수를 나타내지는 않습니다. 예를 들어, 이 필드의 값이 3이면 원본 이미지의 팔레트는 이미지를 만들 때 사용할 수 있는 기본 색당 4비트를 가지고 있었음을 의미합니다. 이 값은 전체 팔레트의 모든 색상이 소스 머신에서 사용 가능하지 않더라도 원본 팔레트의 풍부함을 나타내도록 설정해야 합니다. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). 기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

값: 기본 교체 글꼴.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | palette correction이 적용된 경우 true, 그렇지 않은 경우 false . |

Palette correction은 이미지가 GIF로 내보내질 때마다 원본 이미지 색상이 최적의 일치 팔레트를 만들기 위해 분석된다는 의미입니다(이미지 Palette가 없거나 옵션에 지정되지 않은 경우). 분석 과정에 시간이 걸리지만 출력 이미지가 최적의 색 팔레트를 갖게 되어 시각적으로 더 나은 결과를 제공합니다. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


전체 프레임인지 여부를 나타내는 값을 설정합니다.

값: 전체 프레임이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 전체 프레임인지 여부를 나타내는 값. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다.

값: 생성 이벤트 후 무시하면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


이미지를 인터레이스해야 하는 경우 true.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


허용되는 최대 픽셀 차이를 가져오거나 설정합니다. 0보다 큰 경우 손실 압축이 사용됩니다. 최적의 손실 압축을 위한 권장값은 80이며, 30은 매우 가벼운 압축, 200은 강한 압축을 의미합니다. 손실이 적게 발생할 때 가장 잘 작동하며, 압축 알고리즘의 제한으로 인해 매우 높은 손실 수준에서는 큰 이득을 얻기 어렵습니다. 허용값 범위는 [0, 1000]입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 허용되는 값의 범위. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


다중 페이지 옵션

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


색상 팔레트를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | boolean -  palette entries가 정렬된 경우 true, 그렇지 않은 경우 false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF 픽셀 종횡비를 가져오거나 설정합니다.

픽셀 종횡비 - 원본 이미지에서 픽셀의 종횡비 근사값을 계산하는 데 사용되는 계수입니다. 필드 값이 0이 아니면 다음 공식에 따라 종횡비 근사값이 계산됩니다: 종횡비 = (픽셀 종횡비 + 15) / 64. 픽셀 종횡비는 픽셀의 너비를 높이로 나눈 값으로 정의됩니다. 이 필드의 값 범위는 1/64 단위로 4:1(가장 넓은 픽셀)부터 1:4(가장 높은 픽셀)까지 지정할 수 있습니다. 값: 0 - 종횡비 정보가 제공되지 않음. 1..255 - 계산에 사용되는 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte | GIF 픽셀 종횡비. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


진행 이벤트 핸들러를 가져오거나 설정합니다.

값: 진행 이벤트 핸들러.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


해상도 설정을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


이미지를 생성할 소스를 가져오거나 설정합니다.

값: 이미지를 생성할 소스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | GIF에 트레일러가 있는 경우 true, 그렇지 않은 경우 false . |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


벡터 래스터화 옵션을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP 메타데이터 컨테이너를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP 데이터 컨테이너. |

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

