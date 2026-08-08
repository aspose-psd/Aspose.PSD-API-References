---
title: "PsdLoadOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "Psd 로드 옵션"
type: docs
weight: 12
url: /ko/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Psd 로드 옵션
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | 새로운 [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) 클래스 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | 사용자 정의 글꼴 소스 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | 레이어가 수정되지 않은 경우 렌더링 중 원본 레이어 픽셀을 보존할지 여부를 가져오거나 설정합니다. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | 워프 변환 유무에 관계없이 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다. |
| [getBufferSizeHint()](#getBufferSizeHint--) | 내부 버퍼 전체에 허용되는 최대 크기로 정의된 버퍼 크기 힌트를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | 이미지 배경 색상을 가져옵니다. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | 데이터 복구 모드를 가져옵니다. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | 로드 후 [ignore after load] 여부를 나타내는 값을 가져옵니다. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | [ignore alpha channel] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | UpdateText 작업 실행 시 PSD 텍스트 레이어 고정 너비를 무시할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | [load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 리소스가 로드되지 않음). |
| [getProgressEventHandler()](#getProgressEventHandler--) | 진행 이벤트 핸들러를 가져옵니다. |
| [getReadOnlyMode()](#getReadOnlyMode--) | [use read only mode] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getReadOnlyType()](#getReadOnlyType--) | PSD 이미지를 로드할 때 사용되는 읽기 전용 모드를 가져오거나 설정합니다. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | [use disk for load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 디스크를 사용해 효과 리소스를 로드하지만, 이 값을 false로 설정하면 메모리를 사용할 수 있습니다). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | ICC 프로파일 변환을 적용할지 여부를 나타내는 값을 가져옵니다. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 이는 벤처 라이선스 패턴의 일부입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | 레이어가 수정되지 않은 경우 렌더링 중 원본 레이어 픽셀을 보존할지 여부를 가져오거나 설정합니다. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | 워프 변환 유무에 관계없이 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 설정합니다. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | 이미지 배경 색상을 설정합니다. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | 데이터 복구 모드를 설정합니다. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | [ignore after load] 여부를 나타내는 값을 설정합니다. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | [ignore alpha channel] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | UpdateText 작업 실행 시 PSD 텍스트 레이어 고정 너비를 무시할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | [load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 리소스가 로드되지 않음). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | 메모리 MGR을 가져오거나 설정합니다. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 진행 이벤트 핸들러를 설정합니다. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | [use read only mode] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | PSD 이미지를 로드할 때 사용되는 읽기 전용 모드를 가져오거나 설정합니다. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | [use disk for load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 디스크를 사용해 효과 리소스를 로드하지만, 이 값을 false로 설정하면 메모리를 사용할 수 있습니다). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | ICC 프로파일 변환을 적용할지 여부를 나타내는 값을 설정합니다. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | 이는 벤처 라이선스 패턴의 일부입니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


새로운 [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) 클래스 인스턴스를 초기화합니다.

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


사용자 정의 글꼴 소스

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


레이어가 수정되지 않은 경우 렌더링 중 원본 레이어 픽셀을 보존할지 여부를 가져오거나 설정합니다.

값: 변경되지 않은 레이어의 원본 픽셀을 유지하려면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


워프 변환 유무에 관계없이 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다.

값: 워프 변환으로 이미지를 렌더링하려면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


내부 버퍼 전체에 허용되는 최대 크기로 정의된 버퍼 크기 힌트를 가져옵니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Returns:**
int - 정의된 최대 허용 크기로, 모든 내부 버퍼에 대한 버퍼 크기 힌트입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


이미지 배경 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

일반적으로 픽셀 값이 데이터 손상으로 복구될 수 없을 때 배경 색상이 설정됩니다.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


데이터 복구 모드를 가져옵니다.

**Returns:**
int - 데이터 복구 모드.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


로드 후 [ignore after load] 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean -  true  if [ignore after load]; otherwise,  false .
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


[ignore alpha channel] 여부를 나타내는 값을 가져오거나 설정합니다.

값: [ignore alpha channel]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


UpdateText 작업 실행 시 PSD 텍스트 레이어 고정 너비를 무시할지 여부를 나타내는 값을 가져오거나 설정합니다.

값: [ignore text layer width]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


[load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 리소스가 로드되지 않음). 이 옵션을 설정하면 지원되는 효과만 최종 병합 이미지에 렌더링됩니다.

값: [load effects resource]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


진행 이벤트 핸들러를 가져옵니다.

값: 진행 이벤트 핸들러.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


[use read only mode] 여부를 나타내는 값을 가져오거나 설정합니다. 이는 Adobe Photoshop과 동일한 호환성을 위한 읽기 전용 모드이며, 이 옵션을 설정하면 레이어에 적용된 모든 변경 사항이 최종 이미지에 저장되지 않습니다. 모든 데이터는 ImageData 섹션에서 사용되므로 Photoshop과 동일합니다. 기본적으로 모든 로드된 이미지는 Adobe Photoshop과 호환되지 않습니다.

값: [use photoshop compatibility mode]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


PSD 이미지를 로드할 때 사용되는 읽기 전용 모드를 가져오거나 설정합니다.

값: ReadOnlyMode 중 하나 ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) 값:

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


[use disk for load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 디스크를 사용해 효과 리소스를 로드하지만, 이 값을 false로 설정하면 메모리를 사용할 수 있습니다).

값:  true  경우 [use disk for load effects resource]; 그렇지 않으면  false .

**Returns:**
boolean
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


ICC 프로파일 변환을 적용할지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


이는 벤처 라이선스 패턴의 일부입니다. 이 값은 벤처가 LoadOptions 객체를 전달하면 VentureLicenser에 의해 설정됩니다.

**Returns:**
java.lang.Object
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


레이어가 수정되지 않은 경우 렌더링 중 원본 레이어 픽셀을 보존할지 여부를 가져오거나 설정합니다.

값: 변경되지 않은 레이어의 원본 픽셀을 유지하려면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


워프 변환 유무에 관계없이 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다.

값: 워프 변환으로 이미지를 렌더링하려면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 설정합니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 내부 버퍼 전체에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


이미지 배경 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | 배경 색상. |

일반적으로 배경색은 데이터 손상으로 인해 픽셀 값을 복구할 수 없을 때 설정됩니다. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


데이터 복구 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 데이터 복구 모드. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


[ignore after load] 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  if [ignore after load]; otherwise,  false . |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


[ignore alpha channel] 여부를 나타내는 값을 가져오거나 설정합니다.

값: [ignore alpha channel]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


UpdateText 작업 실행 시 PSD 텍스트 레이어 고정 너비를 무시할지 여부를 나타내는 값을 가져오거나 설정합니다.

값: [ignore text layer width]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


[load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 리소스가 로드되지 않음). 이 옵션을 설정하면 지원되는 효과만 최종 병합 이미지에 렌더링됩니다.

값: [load effects resource]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


메모리 MGR을 가져오거나 설정합니다.

값: 메모리 MGR.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


진행 이벤트 핸들러를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 진행 이벤트 핸들러. |

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


[use read only mode] 여부를 나타내는 값을 가져오거나 설정합니다. 이는 Adobe Photoshop과 동일한 호환성을 위한 읽기 전용 모드이며, 이 옵션을 설정하면 레이어에 적용된 모든 변경 사항이 최종 이미지에 저장되지 않습니다. 모든 데이터는 ImageData 섹션에서 사용되므로 Photoshop과 동일합니다. 기본적으로 모든 로드된 이미지는 Adobe Photoshop과 호환되지 않습니다.

값: [use photoshop compatibility mode]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


PSD 이미지를 로드할 때 사용되는 읽기 전용 모드를 가져오거나 설정합니다.

값: ReadOnlyMode 중 하나 ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) 값:

 *  
 *  
 *  

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


[use disk for load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 디스크를 사용해 효과 리소스를 로드하지만, 이 값을 false로 설정하면 메모리를 사용할 수 있습니다).

값:  true  경우 [use disk for load effects resource]; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


ICC 프로파일 변환을 적용할지 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


이는 벤처 라이선스 패턴의 일부입니다. 이 값은 벤처가 LoadOptions 객체를 전달하면 VentureLicenser에 의해 설정됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

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

