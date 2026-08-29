---
title: "PsdOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 파일 형식 생성 옵션."
type: docs
weight: 21
url: /ko/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

PSD 파일 형식 생성 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | 새로운 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 클래스 인스턴스를 초기화합니다. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | 새로운 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 클래스 인스턴스를 초기화합니다. |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | 새로운 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [deepClone()](#deepClone--) | 이 인스턴스를 복제합니다. |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | 배경 색상을 가져오거나 설정합니다. |
| [getBufferSizeHint()](#getBufferSizeHint--) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [getChannelBitsCount()](#getChannelBitsCount--) | 색상 채널당 비트 수를 가져오거나 설정합니다. |
| [getChannelsCount()](#getChannelsCount--) | 색상 채널 수를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | PSD 색상 모드를 가져오거나 설정합니다. |
| [getCompressionMethod()](#getCompressionMethod--) | PSD 압축 방식을 가져오거나 설정합니다. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getFullFrame()](#getFullFrame--) | 전체 프레임인지 여부를 나타내는 값을 가져옵니다. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getMultiPageOptions()](#getMultiPageOptions--) | 다중 페이지 옵션 |
| [getPalette()](#getPalette--) | 색상 팔레트를 가져오거나 설정합니다. |
| [getProgressEventHandler()](#getProgressEventHandler--) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [getPsdVersion()](#getPsdVersion--) | 파일 형식 버전을 가져오거나 설정합니다. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | 다른 PSD 이미지 뷰어와의 호환성을 최대화하기 위해 사용되는 [refresh image preview data] 옵션을 나타내는 값을 가져오거나 설정합니다. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | 전역 텍스트 엔진 리소스를 제거하는지 여부를 나타내는 값을 가져오거나 설정합니다. 이 옵션은 일부 텍스트 레이어 PSD 파일에 사용되며, 처리 후 Adobe Photoshop에서 열 수 없을 때(주로 누락된 폰트 텍스트 레이어와 관련) 적용됩니다. |
| [getResolutionSettings()](#getResolutionSettings--) | 해상도 설정을 가져오거나 설정합니다. |
| [getResources()](#getResources--) | PSD 리소스를 가져오거나 설정합니다. |
| [getSource()](#getSource--) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [getUpdateMetadata()](#getUpdateMetadata--) | [update metadata] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | PSD 파일 버전을 가져오거나 설정합니다. |
| [getXmpData()](#getXmpData--) | XMP 데이터 컨테이너를 가져오거나 설정합니다 |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | ColorMode 속성이 할당되었는지 표시합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 배경 색상을 가져오거나 설정합니다. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | 색상 채널당 비트 수를 가져오거나 설정합니다. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | 색상 채널 수를 가져오거나 설정합니다. |
| [setColorMode(short value)](#setColorMode-short-) | PSD 색상 모드를 가져오거나 설정합니다. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | PSD 압축 방식을 가져오거나 설정합니다. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 전체 프레임인지 여부를 나타내는 값을 설정합니다. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 다중 페이지 옵션 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 색상 팔레트를 가져오거나 설정합니다. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | 파일 형식 버전을 가져오거나 설정합니다. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | 다른 PSD 이미지 뷰어와의 호환성을 최대화하기 위해 사용되는 [refresh image preview data] 옵션을 나타내는 값을 가져오거나 설정합니다. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | 전역 텍스트 엔진 리소스를 제거하는지 여부를 나타내는 값을 가져오거나 설정합니다. 이 옵션은 일부 텍스트 레이어 PSD 파일에 사용되며, 처리 후 Adobe Photoshop에서 열 수 없을 때(주로 누락된 폰트 텍스트 레이어와 관련) 적용됩니다. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 해상도 설정을 가져오거나 설정합니다. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | PSD 리소스를 가져오거나 설정합니다. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | [update metadata] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [setVersion(int value)](#setVersion-int-) | PSD 파일 버전을 가져오거나 설정합니다. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP 데이터 컨테이너를 가져오거나 설정합니다 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


새로운 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 클래스 인스턴스를 초기화합니다.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


새로운 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | 옵션. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


새로운 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | 이미지입니다. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


배경 색상을 가져오거나 설정합니다. 투명 객체 아래에서 볼 수 있습니다.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


색상 채널당 비트 수를 가져오거나 설정합니다.

값: 색 채널당 비트 수.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


색상 채널 수를 가져오거나 설정합니다.

값: 색 채널 수.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


PSD 색상 모드를 가져오거나 설정합니다.

값: 색상 모드.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


PSD 압축 방식을 가져오거나 설정합니다.

값: 압축 방법.

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다.

값: 파일 형식 버전.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


다른 PSD 이미지 뷰어와의 호환성을 최대화하기 위해 사용되는 옵션인 [refresh image preview data]인지 여부를 가져오거나 설정합니다. Compact Framework 플랫폼에서는 최종 레이아웃에 텍스트 레이어를 그리는 것이 지원되지 않음을 참고하십시오.

값: [refresh image preview data]인 경우 true, 그렇지 않으면 false.

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


전역 텍스트 엔진 리소스를 제거할지 여부를 나타내는 값을 가져오거나 설정합니다. 이 옵션은 일부 텍스트 레이어가 포함된 PSD 파일에서 처리 후 Adobe Photoshop에서 열 수 없을 때(주로 누락된 폰트 텍스트 레이어와 관련) 사용됩니다. 이 옵션을 사용한 후에는 Photoshop에서 연 파일에서 다음을 수행해야 합니다: 메뉴 "Text" -> "Process absent fonts". 해당 작업 후 모든 텍스트가 다시 표시됩니다. 이 작업이 최종 레이아웃에 일부 변경을 일으킬 수 있음을 참고하십시오.

값: [remove global text engine resource]인 경우 true, 그렇지 않으면 false.

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


해상도 설정을 가져오거나 설정합니다.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


psd 리소스를 가져오거나 설정합니다. 값이 NULL인 경우 원본 ImageResources를 저장합니다(기본 동작). 비어 있지 않은 경우 이 속성에 전달된 리소스와 [required resources]를 저장합니다. 비어 있는 경우 오직 [required resources]만 저장됩니다. 필수 리소스: ResolutionInfoResource, XmpResource

값: psd 리소스.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


이미지를 생성할 소스를 가져오거나 설정합니다.

값: 이미지를 생성할 소스.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


이미지를 저장하는 동안 메타데이터를 업데이트할지 여부를 나타내는 [update metadata] 값을 가져오거나 설정합니다. 값이 true이면 메타데이터가 업데이트됩니다.

값: [update metadata]인 경우 true, 그렇지 않으면 false.

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


벡터 래스터화 옵션을 가져오거나 설정합니다.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


PSD 파일 버전을 가져오거나 설정합니다.

값: psd 파일 버전.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP 데이터 컨테이너를 가져오거나 설정합니다

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


ColorMode 속성이 할당되었는지 표시합니다.

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




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


배경 색상을 가져오거나 설정합니다. 투명 객체 아래에서 볼 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


색상 채널당 비트 수를 가져오거나 설정합니다.

값: 색 채널당 비트 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


색상 채널 수를 가져오거나 설정합니다.

값: 색 채널 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


PSD 색상 모드를 가져오거나 설정합니다.

값: 색상 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


PSD 압축 방식을 가져오거나 설정합니다.

값: 압축 방법.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다.

값: 파일 형식 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


다른 PSD 이미지 뷰어와의 호환성을 최대화하기 위해 사용되는 옵션인 [refresh image preview data]인지 여부를 가져오거나 설정합니다. Compact Framework 플랫폼에서는 최종 레이아웃에 텍스트 레이어를 그리는 것이 지원되지 않음을 참고하십시오.

값: [refresh image preview data]인 경우 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


전역 텍스트 엔진 리소스를 제거할지 여부를 나타내는 값을 가져오거나 설정합니다. 이 옵션은 일부 텍스트 레이어가 포함된 PSD 파일에서 처리 후 Adobe Photoshop에서 열 수 없을 때(주로 누락된 폰트 텍스트 레이어와 관련) 사용됩니다. 이 옵션을 사용한 후에는 Photoshop에서 연 파일에서 다음을 수행해야 합니다: 메뉴 "Text" -> "Process absent fonts". 해당 작업 후 모든 텍스트가 다시 표시됩니다. 이 작업이 최종 레이아웃에 일부 변경을 일으킬 수 있음을 참고하십시오.

값: [remove global text engine resource]인 경우 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


해상도 설정을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


psd 리소스를 가져오거나 설정합니다. 값이 NULL인 경우 원본 ImageResources를 저장합니다(기본 동작). 비어 있지 않은 경우 이 속성에 전달된 리소스와 [required resources]를 저장합니다. 비어 있는 경우 오직 [required resources]만 저장됩니다. 필수 리소스: ResolutionInfoResource, XmpResource

값: psd 리소스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


이미지를 저장하는 동안 메타데이터를 업데이트할지 여부를 나타내는 [update metadata] 값을 가져오거나 설정합니다. 값이 true이면 메타데이터가 업데이트됩니다.

값: [update metadata]인 경우 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


벡터 래스터화 옵션을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


PSD 파일 버전을 가져오거나 설정합니다.

값: psd 파일 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP 데이터 컨테이너를 가져오거나 설정합니다

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

