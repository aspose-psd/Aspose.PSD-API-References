---
title: "ImageOptionsBase"
second_title: "Java용 Aspose.PSD API 참조"
description: "이미지 기본 옵션."
type: docs
weight: 60
url: /ko/java/com.aspose.psd/imageoptionsbase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class ImageOptionsBase extends DisposableObject implements Cloneable
```

이미지 기본 옵션.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [deepClone()](#deepClone--) | 이 인스턴스를 복제합니다. |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getFullFrame()](#getFullFrame--) | 전체 프레임인지 여부를 나타내는 값을 가져옵니다. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getMultiPageOptions()](#getMultiPageOptions--) | 다중 페이지 옵션 |
| [getPalette()](#getPalette--) | 색상 팔레트를 가져오거나 설정합니다. |
| [getProgressEventHandler()](#getProgressEventHandler--) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [getResolutionSettings()](#getResolutionSettings--) | 해상도 설정을 가져오거나 설정합니다. |
| [getSource()](#getSource--) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [getXmpData()](#getXmpData--) | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 전체 프레임인지 여부를 나타내는 값을 설정합니다. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 다중 페이지 옵션 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 색상 팔레트를 가져오거나 설정합니다. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 해상도 설정을 가져오거나 설정합니다. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

값: XMP 데이터 컨테이너.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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

값: XMP 데이터 컨테이너.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

